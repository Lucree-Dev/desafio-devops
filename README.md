# Parte 1

## Sobre o 'teste'

Esse é um teste feito para conhecer um  pouco mais de cada candidato a vaga de DevOps na Lucree. Não se trata de um teste objetivo, capaz de gerar uma nota ou uma taxa de acerto, mas sim de um estudo de caso com o propósito de conhecer os conhecimentos, experiências e modo de trabalhar de um cadidato. Sinta-se livre para desenvolver sua solução para o problema proposto e em caso de dúvidas entre em contato no tech`at`lucree.com.br.

## Cenário

Dentro do diretório `app` existe uma aplicação muito simples em Flask. Quando essa aplicação  subir ela irá ler uma variável de ambiente `LUCREE_PASSWD` que será a senha da api. Ou seja, ao executarmos uma chamada para essa aplicação devemos passar um `Header` de  `Authorization` com o token específico. Por exemplo: `curl -H "Authorization: Token VALOR_DA_ENVVAR_LUCREE_PASSWD" http://localhost/`. Você deve nos informar como podemos definir/trocar esse token facilmente.

Seu objetivo é fazer deploy dessa aplicação na AWS. Você provavelmente precisará criar uma conta free-tier na AWS, ou utilizar uma sua já existente. Mas não se preocupe, não iremos olhar sua conta ou chamar sua aplicação já rodando, queremos que você crie uma forma de que possamos recriar toda sua infraestrutura em nossa conta de forma simples. Você escolhe a forma. Crie um arquivo `part1.md` descrevendo todos os passos para que possamos executar sua infraestrutura em nosso ambiente. Esses são os pontos de atenção:

* Você deverá partir de um ambiente na AWS sem nenhuma infraestrutura já criada.
* A aplicação deverá rodar em containner docker.

Sinta-se livre para mudar o código da aplicação se julgar necessário.

# Parte 2

## Sobre o 'teste'

Esse teste busca entender seus conceitos de arquitetura na AWS, observando um cenário já existente. Queremos saber se você entende a AWS e seus produtos e como funciona a comunicação entre eles.

## Cenário 

Observando a imagem abaixo, crie um arquivo `part2.md` com a descrição técnica do fluxo dessa topologia, conforme seu entendimento.

![cenario-aws-teste](https://challenges-lucree.s3-us-west-2.amazonaws.com/schemadevops.png)

# Entrega

* Você deve clonar esse repositório e commitar todas as modificações, porém, não abra um pull request ou deixe seu código de resposta aberto em um fork, por exemplo.
* Depois que terminar, compacte todo o diretório e nos envie. **Queremos analisar seus commits**.
* Envie para o email tech`at`lucree.com.br.


Bom trabalho!
