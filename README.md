# Crystal_Kemal_Jennifer
This repository aims to store my path learning Crystal Language + Kemal + Jennifer ORM
Este repositório visa armazenar meu caminho aprendendo Crystal Language + Kemal + Jennifer ORM

## Aviso do autor.
**Antes até de começar**, se seguir esse guia, garanta que antes de fazer qualquer deploy leia a última parte sobre o Crystal Lang com o tema:
"**IMPRESCINDÍVEL (antes de qualquer deploy)**".
Responsabilidade sempre e bons estudos.

Antes de abrir a documentação para ler, eu prefiro me familiarizar de outras formas com a linguagem já que a documentação de algumas linguagens podem nos assustar.
Visando isso eu busco formas diferentes de interagir com a linguagem.

## Vídeos
As bases das linguagens não tendem a mudar muito.
- Variáveis
- Funções
- Objetos
- Classes
- Repetição

Por causa dessas características sempre começo por um vídeo que faz um resumo rápido da linguagem e mostra algum código sendo escrito na hora, pois ali eu vou fazendo as associações das bases que mencionei acima.
E o vídeo que deixarei abaixo mostra de uma forma bem tranquila todos os pontos da linguagem:

Vídeo para Crystal
- https://www.youtube.com/watch?v=g27YffcLYXg&ab_channel=DreamsofCode

Sei que o vídeo acima diz que a linguagem não está pronta para ser usada em produção, e esse tópico eu vou deixar para os desenvolvedores mais sêniores discutir.

Vídeo para Kemal
- https://www.youtube.com/watch?v=6CHdjlgnE5U&ab_channel=SerdarDogruyol

Vídeo rápido e que já nos coloca pronto para fazermos requisição a uma api sem configurar muita coisa.
E é muito fácil de visualizar as estruturas que são usadas para se criar uma rota.

## Mão na massa
Agora vamos começar de verdade a programar na linguagem, você pode estar se perguntando, mas sem ler a documentação?
Eeee... Sim e não... Vamos abrir a documentação mas primeiro:

### Compliadores online:
https://play.crystal-lang.org/#/cr

Simm! Compiladores online, a forma mais fácil de testar, errar e acertar sem se preocupar ainda em instalar o programa.
Se acostume com estruturas de decisão, repetição, funções, objetos, classes. Realize exercícios simples. Vai ver que provavelmente você vai errar algo.

### Documentação
Agora sim abra a documentação, e use enquanto coda para tirar dúvidas ou apenas leia ela:

#### Base
Na Crystal Lang sugiro que comece pelos tópicos:
- [Hello World 🌎](https://crystal-lang.org/reference/1.8/tutorials/basics/10_hello_world.html)
- [Variáveis](https://crystal-lang.org/reference/1.8/tutorials/basics/20_variables.html)
- [Matemática](https://crystal-lang.org/reference/1.8/tutorials/basics/30_math.html)
- [strings](https://crystal-lang.org/reference/1.8/tutorials/basics/40_strings.html)
- [Estruturas de controle](https://crystal-lang.org/reference/1.8/tutorials/basics/50_control_flow.html)
- [Métodos](https://crystal-lang.org/reference/1.8/tutorials/basics/60_methods.html)

Depois de se habituar a isso, sugiro dar uma olhada no guia, você encontrará informações importantes sobre a linguagem, mas eu sugiro focar em:
[Padrões da linguagem (Estilo, formatação, etc)](https://crystal-lang.org/reference/1.8/conventions/coding_style.html)
[Testes](https://crystal-lang.org/reference/1.8/guides/testing.html)

Você pode ver mais se você quiser:
[Guia completo](https://crystal-lang.org/reference/1.8/guides/index.html)

#### Importantes
Existe uma seção de especificações da linguagem que diz como devemos fazer uma série de coisas, no começo eu focaria em:
[Como fazer comentários](https://crystal-lang.org/reference/1.8/syntax_and_semantics/comments.html)
[Documentação automática](https://crystal-lang.org/reference/1.8/syntax_and_semantics/documenting_code.html)
[Tipos de variáveis](https://crystal-lang.org/reference/1.8/syntax_and_semantics/literals/index.html)

Muito importante, muitos devs deixam isso passar, mas é importante saber o que a linguagem entende como true e false. Exemplo: Algumas linguagens consideram int 0 como false, outras não.
[O que é verdadeiro e o que é falso](https://crystal-lang.org/reference/1.8/syntax_and_semantics/truthy_and_falsey_values.html)

#### **IMPRESCINDÍVEL (antes de qualquer deploy)**
Leia sobre código inseguro.
Principalmente se você trabalha como desenvolvedor e principalmente com deploys.
Primeira coisa, você é um desenvolvedor, sumariamente a sua sina deve ser lutar contra defeitos e falhas.
Segundo, você está lidando com negócios e pessoas, vidas. Lembre-se disso. Responsabilidade sempre.

[Código não seguro](https://crystal-lang.org/reference/1.8/syntax_and_semantics/unsafe.html)
