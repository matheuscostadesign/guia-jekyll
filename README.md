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

---

###  Execução do Jekyll

- Abrir VSCode dentro da pasta escolhida
Ex: `c:\dev-front`

- Criando a pasta/estrutura "meu-blog":
`jekyll new meu-blog` | `jekyll new nome-do-projeto`

- Criando estrutura do Jekyll direto na pasta:
`jekyll new . --force`

- Executar comando dentro da pasta criada:
 `bundle add webrick` ou apenas `bundle`

- Iniciar servidor local:
`jekyll serve` ou `bundle exec jekyll serve` ou `bundle exec jekyll s`

- Gerar arquivos estáticos
`jekyll build` ou `bundle exec jekyll build` ou `bundle exec jekyll b`
