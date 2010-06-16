# Rake para Compilacao JRuby #
***
## Sobre o Rake ##
Criei este rake com a finalidade de automatizar a compilação de scripts ruby.

## Como funciona ##
Bem, a pouco tempo, eu mandei um email para Charles Nutter, perguntando sobre uma estrutura default ou padrão para projetos JRuby, a resposta dele foi...
"Well I suppose there's many ways to do it, but none have really become
the "default"."
Traduzindo...
Bem, eu suponho que existam muitas maneiras de fazer isso, mas nenhuma se tornou a padrão.

Apos isso, eu decidi utilizar a seguinte estrutura...

<pre>app/lib/lib # scripts ruby (.rb)
app/lib/bin # compilacoes (.class)</pre>

O rake e baseado nessa estrutura, ele replica a estrutura de pastas de app/lib/lib em app/lib/bin e depois compila os .rbs de dentro de app/lib/lib para app/lib/bin.
Obs.: Se tiver algum arquivo .rb dentro de app/lib ele eh compilado dentro do proprio diretorio app/lib

Bem, eh isso, qualquer duvida, sugestao, critica, etc meus contatos estao logo abaixo...

## Sobre mim ##
*   _Nome:_ Hugo Roque
*   _Email:_ hugo.roque@caelum.com.br
*   _Twitter:_ http://twitter.com/hugolnx
