# Guia de instalação do Jekyll no Windows

### Instalação do Ruby

- Baixar e instalar Ruby com DevKit:
  https://rubyinstaller.org/downloads/

- Abrir Terminal e executar o comando:
`ruby -v`

- Executar o comando:
`ridk install`

- Selecionar opção 3: 
`MSY and MINGW Development Toolchain`

---

###  Instalação do Jekyll

- Executar o comando:
`gem install jekyll bundler`

- Reiniciar a máquina

###  Execução do Jekyll

- Abrir VSCode dentro da pasta escolhida
Ex: `c:\dev-front`

- Criando a pasta/estrutura "meu-blog":
`jekyll new meu-blog` | `jekyll new nome-do-projeto`

- Executar comando dentro da pasta criada:
 `bundle add webrick`

- Iniciar servidor local:
`jekyll serve` ou `bundle exec jekyll serve`

- Gerar arquivos estáticos
`jekyll build`
