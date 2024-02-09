flowchart TD
    acessarSite[Acessar site FleetMaster] --> gerenciamentoVeiculos[Gerenciamento de veículos]
    gerenciamentoVeiculos --> cadastroVeiculo[Cadastrar veículo]
    cadastroVeiculo[Cadastrar veículo] --> veiculosCadastrados[Visualizar veículos cadastrado]
    gerenciamentoVeiculos --> cadastroMotorista[Cadastrar Motorista]
    cadastroMotorista --> visualizarMaps
    veiculosCadastrados --> visualizarMaps[Visualizar localização no Maps]
    visualizarMaps --> manutencaoVeiculo{Manutenção necessária?}
    manutencaoVeiculo --> sim[Sim]
    manutencaoVeiculo --> nao[Não]
    nao --> manutencaoVeiculo
    sim --> acionarTerceiro[Acionar empresa tercerizada]