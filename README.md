# trunkcd
Pipeline continuous deploy com Trunk Based
Aqui a idéia é criar uma pipe de exemplo completa baseada em trunk based para fazer continuous deploy.
Aqui utilizarei Node, Github actions e azure contemplando os seguintes steps:
- Pull request
- Teste unitário
- Build
- Teste de mutação
- Analise estática
- Analise Segurança
- Versionameto de pacote
- Teste Integração
- Teste aceite
- Estratégia de Deploy(Blue/green)
