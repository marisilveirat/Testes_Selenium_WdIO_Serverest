# Projeto de Testes com WebdriverIO

Este projeto utiliza WebdriverIO para realizar testes automatizados na página de cadastro de usuários em `https://front.serverest.dev/cadastrarusuarios`.

### Estrutura do Projeto
wdio.conf.js: Arquivo de configuração do WebdriverIO.
test/specs/: Diretório contendo os arquivos de teste.
Testes Realizados
Cadastro de Usuário
Este teste realiza as seguintes ações:

Navega até a página de cadastro de usuários.
Preenche o campo de nome de usuário com tomsmith.
Preenche o campo de senha com SuperSecretPassword!.
Seleciona a opção "Cadastrar como administrador?" (Ajuste o seletor conforme necessário).
Submete o formulário de cadastro.
Verifica se a mensagem de sucesso está presente na página.
