# Modelo dissertação PPGCC

Modelo de dissertação baseado no template da [ABNTex2](https://github.com/abntex/abntex2) (Trabalho acadêmico). Esse projeto
tem como finalidade facilitar a escrita da dissertação dos mestrandos do [Programa de Pós-Graduação em Ciência da Computação (PPGCC)](http://ppgcc.ifce.edu.br) do Instituto Federal do Ceará (IFCE).

## Por onde começar?

1. Faça um clone do projeto `git clone https://github.com/omadson/modelo-dissertacao-ppgcc minha-dissertacao` ou baixe o [.ZIP](https://github.com/omadson/modelo-dissertacao-ppgcc/archive/master.zip)
2. Modifique o arquivo `informacoes.tex` com suas próprias informações
3. _Hands-on_

## Funcionalidades
O projeto conta com algumas facilidades:
 - Arquivo contendo todas as informações em separado, dessa maneira você não se repete 
 (DRY - don't repeat yourself).
 - Diretórios específicos para capítulos, anexos, apêndices e figuras. Dessa 
 maneira você tem um projeto mais organizado.

## Utilizando o projeto
Para melhor utilização do projeto, você deve seguir algumas boas práticas.

Os capítulos devem ser separados em vários arquivos `.tex` e salvos no diretório `capitulos`. 
Como no exemplo abaixo:

```
modelo-dissertacao-ppgcc
├── capitulos
│   ├── conclusao.tex
│   ├── capitulo-exemplo.tex
│   ├── ...
│   └── introducao.tex
├── dissertacao.tex
├── informacoes.tex
...
├── README.md
└── referencias.bib
```
Assim como as imagens e gráficos devem ser colocados no diretório `figuras/imagens` e
`figuras/graficos` respectivamente.

Elementos pré-textuais devem residir no diretório `pretextual`, tais como o `resumo.tex`,
`abstract.tex`, `dedicatoria.tex` entre outros já listados lá.

Os diretórios `apendices` e `anexos` guardam os apêndices e anexos respectivamente.

O arquivo `informacoes.tex` contém os dados relacionados ao seu trabalho, tais como, título,
autor, área de concentração, orientador etc. Caso você não tenha um coorientador, basta
apagar a linha referente.

O arquivo que deve ser compilado é o `dissertacao.tex`, após a compilação, você deve ter
disponível no seu diretório de trabalho o arquivo `dissertacao.pdf`.

## Dúvidas?
 - [Madson Dias](mailto:madsonddias@gmail.com)
 - [Vitor Carvalho](mailto:vitorcarvalhoml@gmail.com)

## Veja também
 - [Modelo de apresentação PPGCC](https://github.com/vitorcarvalhoml/modelo-apresentacao-ppgcc)