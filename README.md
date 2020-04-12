![Portal sem Porteiras](/assets/img/logo.png)

Preparando o caminho:
  - Precisa ter ruby e gem instalado. Usa Ubuntu? [Saca isso](https://www.ruby-lang.org/pt/documentation/installation/).
  - Também ajuda se tiver git

Para rodar o site:
  - Usando o terminal, vai na pasta onde vai salvar o projeto do site, tipo "Documentos", "Projetos", "Coisas que nao sei onde guardar".
  - Depois, copia o site, executando esse comando no terminal:
    ´´´
      git clone https://github.com/portalsemporteiras/portalsemporteiras.github.io.git
    ´´´
  - Entra na pasta do site:
    ´´´
      cd portalsemporteiras.github.io.git
    ´´´
  - Instala o bundler para facilitar a vida
    ´´´
      gem install bundler
    ´´´
      PS: se aparecer algo assim na tela: "WARNING:  You don't have /lalala/.gem/ruby/algum.numero.aqui/bin in your PATH", [isso](https://stackoverflow.com/questions/14637979/how-to-permanently-set-path-on-linux-unix) pode te ajudar
  - Instala as dependencias do site, executando isso no terminal:
    ´´´
      bundler install
    ´´´
  - Bota o site no "ar":
    ´´´
      bundle exec jekyll serve
    ´´´

Nao quer ficar recarregando o site toda vez que alterar o CSS? Instala gulp e roda o comando abaixo antes de rodar o serve:
    ´´´
      bundle exec gulp
    ´´´

Gostou do site?
A gente tá usando o tema Long Haul, credito pro [@brianmaierjr](https://twitter.com/brianmaierjr).
