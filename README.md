# Como rodar o site localmente
## Instalação do Ruby
No console (powershell, se no Windows), veja se há alguma versão do ruby já instalado digitando:
`ruby -v`

Caso não esteja instalado, ou se a versão é 3.4.x ou superior, 
instale uma versão 3.1.x do Ruby:
https://www.ruby-lang.org/pt/downloads/

## Instalação de Bundler e Jekyll
No console, digite:
`gem install bundler jekyll`

## Instale dependências e hospede o site localmente
Vá para o local onde este projeto está:
`cd LOCAL-DO-PROJETO`

Para instalar as dependências, digite:
`bundle install`

Caso ocorra algum erro com alguma dependência, tente atualizá-lo.
(no meu caso, deu erro com "ffi")
`bundle update ffi`

Finalmente, hospede:
`bundle exec jekyll serve`
