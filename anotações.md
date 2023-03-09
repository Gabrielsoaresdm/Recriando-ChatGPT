src = source (código fonte)

dentro da src - código fonte
fora da src - arquivos de configuração

Server que sustenta uma aplicação

Conceito de arquitetura N-layer 

camadas:
- Controllers: controlar quem acessa e controlar as respostas de devolução(request e responses)

- Rotas: Quem faz os apontamentos para os endereços dos nossos controllers

- Model: É a forma de entrada/saida de dados no seu servidor

- Config: serve para colocar configurações de outras aplicações (aplicações de terceiros) e dados não sensíveis 

- Configurações não embarcadas (.env):
serve para isolar dados sensíveis