<!-- Título do Respositório -->
# Blaise Would Be Proud! u-u
<!-- -->

<!-- Badges -->
<p align="center">
    <img src="https://img.shields.io/badge/made%20with-Pascal-blue.svg?style=flat&colorB=9D62F4" alt="Pascal Badge">
</p>
<!-- -->

<!-- Msg de boas vindas -->
<p align="center">Bem-vindo ao meu repositório de
<!-- -->

<!-- Logo -->
<p align="center">
    <img src="https://s3.amazonaws.com/s3.timetoast.com/public/uploads/photos/8574093/pascal_logo.png" alt="Pascal Logo" height="100">
</p>
<!-- -->

<!-- Links Principais-->
<p align="center">
    <a href="https://www.freepascal.org/docs.var" target="_blank"><strong>Documentação da linguagem »</strong></a>
    <br/>
    <a href="https://pt.wikipedia.org/wiki/Pascal_(linguagem_de_programa%C3%A7%C3%A3o)" target="_blank"><strong>Página no Wikipedia »</strong></a>
    <br/>
    <a href="https://www.freepascal.org/" target="_blank"><strong>Site Oficial »</strong></a>
    <br/>
</p>
<!-- -->

<!-- Links do Repositório -->
<p align="center">
    <a href="Exercícios Resolvidos">Exercícios Resolvidos</a>
    ·
    <a href="Programas">Programas</a>
</p>
<!-- -->

<!-- Language Preview -->
<p align="center">
    <img align="center" src="https://i.github-camo.com/ed6e69f1ffae0f7b751043dd64d25b26b1413129/68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f616c65667261676e616e692f61746f6d2d6c616e67756167652d70617363616c2f6d61737465722f696d616765732f61746f6d2d70617363616c2d73796e7461782e706e67" alt="Go Coding" width="400">
</p>
<!-- -->

---

<!-- Table of Contents -->
## Glossário
- [Blaise Would Be Proud! u-u](#Blaise-Would-Be-Proud-u-u)
  - [Glossário](#Gloss%C3%A1rio)
  - [Objetivo](#Objetivo)
  - [Material Utilizado](#Material-Utilizado)
    - [Sistema Operacional](#Sistema-Operacional)
    - [Compilador](#Compilador)
    - [IDE](#IDE)
  - [Programando em Pascal](#Programando-em-Pascal)
    - [Pré-Requisitos](#Pr%C3%A9-Requisitos)
    - [Executando .pp pelo CMD](#Executando-pp-pelo-CMD)
    - [Exemplo de Hello World](#Exemplo-de-Hello-World)
  - [Links Úteis](#Links-%C3%9Ateis)
  - [Autor](#Autor)
  - [Licença](#Licen%C3%A7a)
<!-- -->

<!-- Objetivo -->
## Objetivo
Este repositório foi criado com a finalidade de guardar meus projetos, ideias, anotações, exercícios e programas pessoais feitos em <strong>Pascal</strong>.
<!-- -->

<!-- Material Utilizado -->
## Material Utilizado
Estes são os materiais usados por mim para desenvolver e rodar meus programas em Pascal.
### Sistema Operacional
- [Windows 10](https://www.microsoft.com/pt-br/windows/)
### Compilador
- [Free Pascal](#Links-%C3%9Ateis)
### IDE
- [Visual Studio Code](https://code.visualstudio.com/)
  - Com as extensões: <br/>
    [Pascal](https://marketplace.visualstudio.com/items?itemName=alefragnani.pascal) <br/>
    [OmniPascal](https://marketplace.visualstudio.com/items?itemName=Wosi.omnipascal) <br/>
    <img src="https://omnipascal.com/img/portfolio/peekdefinition2.gif" width="400">
<!-- -->

<!-- Programando em ... -->
## Programando em Pascal
O que foi necessário para criar e rodar meus programas em Pascal.

### Pré-Requisitos
Para programar em Pascal basta baixar e instalar o pacote da linguagem pelo site oficial. [(ver Links Úteis)](#Links-%C3%9Ateis)

- Para verificar se o Go está instalado no PC, basta executar o comando no CMD: <br/>
    `> fpc`
> - Se o comando não for reconhecido: **não está** instalado! *(ver [Links Úteis](#Links-%C3%9Ateis) para instalar)* <br/>
> - Caso exiba funcionalidades e comandos da linguagem: **está** instalado! <br/>

### Executando .pp pelo CMD
Criando e executando um programa simples com Free Pascal pelo CMD

1. Para executar arquivos *.pp* pelo terminal deve-se ter o compilador Free Pascal devidamente instalado e configurado no PC. <br/>
   Para isso, baixar e executar o pacote pelo site oficial. *(ver [Links Úteis](#Links-%C3%9Ateis))*

2. Após ter baixado e executado o instalador, já será capaz de criar e executar programas Pascal no Windows usando a extensão .pp e o compilador Free Pascal.

- Para compilar programas *".pp"* e executá-los no terminal/cmd:
  - Abrir pasta onde se localiza o arquivo main *.pp*: <br/>
     `> cd "pasta do programa"`
  - Compilar o programa: <br/>
     `> fpc "nome do programa".pp`
  - Executar o programa: <br/>
     `> "nome do programa"`
  
  - Exemplo: <br/>
     `> cd "C:\Users\Guilherme\Documentos\Meus Programas\Pascal\Programa Hello World" // Para ir até a pasta do arquivo .pp` <br/>
     `> fpc HelloWorld.pp // Para compilar um programa chamado "HelloWorld.pp"` <br/>
     `> HelloWorld.exe // Para executar o programa (a extensão .exe pode ser omitida)`

### Exemplo de Hello World
``` Pascal
Program HelloWorld;

Begin
	Write('Hello Gui! =)');
	Readln;
End.
```

Saída: <br/>
`> Hello Gui! =)`
<!-- -->

<!-- Links-->
## Links Úteis
- [Download](https://www.freepascal.org/download.html)
<!-- -->

<!-- Autor/Contato -->
## Autor
* **Guilherme Esdras (guilherme.esdras@outlook.com)** - [GitHub Page](https://github.com/GuilhermeEsdras) <br/>
  <img src="https://img.shields.io/github/followers/GuilhermeEsdras.svg?label=Segue%20%3A3&style=social">
<!-- -->

<!-- Licença -->
## Licença
*Distributed under the MIT License. See LICENSE for more information.*