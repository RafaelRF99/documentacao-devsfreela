# FleetMaster
Serviço de gerenciamento de frota de veiculos.

## Finalidade
O website da FleetMaster auxilia as empresas no gerenciamento de seus veículos disponibilizando diversas ferramentas para o melhor desempenho.

## Sobre
O projeto se trata de um website de gerenciamento de frota de veiculos, onde o foco é empresas de qualquer porte e 
terá acesso a funcionalidades de gerenciamento após o cadastro com CNPJ. O sistema será acessado somente pelos administradores ou pessoas autorizadas. Onde a mesma poderá ter diversas funcionalizadas como:
 - Controle de quantidade total de veículos.
 - Status dos veículos.
 - Agendamento de manutenção (Empresa terceirizada).
 - Localização em tempo real.

Para cadastrar o motorista a empresa irá enviar o link, onde o mesmo deverá entrar e preencher conforme necessário. Ao termino do cadastro já vai estar no sistema da 
empresa.
Quando o motorista for iniciar o dia deverá fazer o check-in para iniciar a localização em tempo real e para cancelar a localização basta deslogar, caso a localização 
seja interrompida e não volta em 10 minutos um alerta será emitido para a gerencia.

Benefícios:
- Planejamento mais amplo.
- Segurança para o motorista.
- Taxa de quebra de veiculos reduzido.
- Gestão de veículos/motoristas.

## Regras de negócio
- Restrições de acesso: Apenas usuários com permissão deveram ter acesso.
- Verificação de dados: Validar veículo e motorista para garantir a integridade.
- Monitoramento em tempo real: Monitoramento continuo.
- Segurança/Privacidade: Garantir a segurança das informações.
- Veículos disponiveis: Liberar veículos para trafegar somente se estiver disponivel.
- Gestão de motoristas: Deve ser possivel cadastrar e incluir informações como nome, idade, CPF, CNH, etc.

## Arquitetura
<b>Front-End</b>
- pages: Local para páginas
- components: Pode ser utilizado em mais de um local ou ajuda na composição de algo
- routes: Rotas da aplicação
- styles: Estilização da página
- assets: Todas as imagens

  
<b>Back-End</b>
- database: Conexão com o banco
- controllers: Interage com banco fazendo requisição
- routes: Toda lógica de rotas
- server: Arquivo base para rodar a aplicação

## Referência
Diagrama: `https://www.plantuml.com/plantuml/uml/SyfFKj2rKt3CoKnELR1Io4ZDoSa70000`, `https://mermaid.live/edit`
