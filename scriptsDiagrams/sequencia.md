sequenceDiagram
    actor Usuario
    participant Cadastro
    participant DB

    Usuario ->>+ Cadastro: Informações cadastro
    Cadastro -->>- Usuario: status()
    Usuario ->>+ DB: Busca Informações necessárias
    DB -->>- Usuario: status()
