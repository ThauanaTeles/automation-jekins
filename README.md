# automation-jekins

Repositório do projeto Kabug com Cucumber, Capybara e Ruby

## Como executar o projeto

* Importante ter o Ruby instalado (versão 2.5 ou superior)

### Instalar o bundler

` 
gem install bundler 
`

### Instalar as dependências do ruby (projeto)

` 
bundle install 
`

### Executar localmente (minha máquina)

`
bundle exec cucumber 
`

### Executar no servidor de CI (gerando reports em JSON)

`
bundle exec cucumber -p ci
`
