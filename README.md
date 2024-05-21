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

### Baixar as dependências

`bundle install`

---

###  Execução do Jekyll

- Abrir VSCode como administrador dentro da pasta escolhida
Ex: `c:\dev-front`

- Criando a pasta/estrutura "meu-blog":
`jekyll new meu-blog` | `jekyll new nome-do-projeto`

- Criando estrutura do Jekyll direto na pasta:
`jekyll new . --force`

- Executar comando dentro da pasta criada: (p/versao 3)
 `bundle add webrick` ou apenas `bundle`

- Iniciar servidor local:
`bundle exec jekyll serve` ou `bundle exec jekyll s` ou `jekyll serve`

- Iniciar servidor local (c/ atualização instantânea):
`bundle exec jekyll serve --livereload`

- Gerar arquivos estáticos
`jekyll build` ou `bundle exec jekyll build` ou `bundle exec jekyll b`

---

###  Publicar Jekyll no Github Pages
- Editar o arquivo: `Gemfile`
- Comentar a linha: `gem "jekyll", "~> 4.2.1"`
- Habilitar a linha: `gem "github-pages", group: :jekyll_plugins`
- Remover o arquivo: `Gemfile.lock`
- Executar o comando: `bundle install` e `bundle update`
- O arquivo `Gemfile.lock` será criado automaticamente
