![](https://github.com/CintiaAguiar/academia-e-maternidade-analise/blob/main/analise-exploratoria/woman.png)

# <br> Projeto Final {Reprograma} - Maternidade Acadêmica

Este é o projeto final do curso "Fundamentos de Python e Análise de Dados" da Turma On26 da [{Reprograma}](https://www.reprograma.com.br/).

O projeto consiste em uma análise de dados realizada no Jupyter Notebook, com visualização no Tableau.

Sinta-se à vontade para explorar, contribuir ou fornecer feedback! Juntos, podemos promover uma compreensão mais abrangente das experiências de mulheres na academia.

<br>

## Estrutura do Projeto:
<!--ts-->

- [🎯 Objetivo](#-Objetivo)
- [🏗️ Arquitetura do Projeto](#-Arquitetura-do-Projeto)
- [💻 Tecnologias e Dependências Utilizadas](#-Tecnologias-e-Dependências-Utilizadas)
- [🔧 Visualização](#-Visualização)
- [🛠️ Interface Gráfica](#-Interface-Gráfica)
- [🙏 Agradecimentos](#-Agradecimentos)
- [👩🏾‍💻 Autora](#-Autora)

---

**[🎯 Objetivo](#-Objetivo) | [🏗️ Arquitetura do Projeto](#-Arquitetura-do-Projeto) | [💻 Tecnologias e Dependências Utilizadas](#-Tecnologias-e-Dependências-Utilizadas) | [🔧 Visualização](#-Visualização) | [🛠️ Interface Gráfica](#-Interface-Gráfica) | [👩🏾‍💻 Autora](#-Autora)**

<!--ts-->

<br>

## 🎯 Objetivo
Este projeto tem como objetivo esclarecer a lacuna de informações relacionadas à maternidade na carreira acadêmica no Brasil. Utilizando dados do IBGE de 2021, explorei a interseção entre mulheres, mães e pesquisadoras (em níveis de mestrado e doutorado) para evidenciar a importância de uma discussão mais aprofundada sobre essa temática.

## Objetivos específicos:
- Contextualizar a presença de mulheres no Brasil, destacando aquelas que são mães.
- Analisar a representatividade de mulheres nos cursos de mestrado e doutorado brasileiros com base nos dados disponíveis.
- Argumentar sobre a necessidade de coleta de dados específicos sobre a maternidade na carreira acadêmica.

## Nota sobre os Dados
Esta análise é baseada em uma amostra de dados disponíveis na internet. É importante ressaltar que os dados reais sobre maternidade na carreira acadêmica podem variar, e a precisão dessas informações depende da inclusão de dados sobre maternidade por agências de fomento e universidades em seus levantamentos. Espera-se que, no futuro, dados oficiais mais abrangentes estejam disponíveis para uma análise mais completa.

**Nota Importante:** Este é projeto de cunho pessoal e busca incentivar a inclusão de informações sobre maternidade em futuras pesquisas e levantamentos oficiais.

<br>

**[Apresentação do Projeto Final](https://www.canva.com/design/DAF198g1AiI/BxHt-XCF1e8vkqsANClkjg/edit?utm_content=DAF198g1AiI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)**

<br>

## 🏗️ Arquitetura do Projeto

<br>

```
 📁academia-e-maternidade-analise
   |
   |
   |--📁 analise-exploratoria
   |  ||
   |  ||
   |  ||--📁 datasets
   |  |    |- 📄 ibge_educacao.csv
   |  |    |- 📄 ibge_maternidade.csv
   |  |    |- 📄 ibge_populacao.csv
   |  |    
   |  ||--📄analise_exploratoria.ipynb
   |  ||--📄base_final.csv
   |  ||--📄woman.png
   |  |
   |  |
   |--📄 canva.pdf
   |--📄 README.md
   

```

<br>
<br>

## 💻 Tecnologias e Dependências Utilizadas

<br>

| Ferramenta | Descrição |
| --- | --- |
| `python` | Linguagem de programação. |
| `pandas` | Biblioteca Python para manipulação e análise eficiente de dados.|
| `matplotlib` | Biblioteca para criação de gráficos e visualizações em Python.|
| `seaborn` | Ferramenta para plotagem de diversos tipos de gráficos em Python.|
| `jupyter notebook` | Aplicação web para desenvolvimento interativo em várias linguagens, incluindo Python.|
| `Tableau` | Plataforma para análise, exploração e gerenciamento visual de dados.|
| `Canva` | Ferramenta de design online utilizada na criação da apresentação do projeto.|

<br>
Link para o site com as bases de dados utilizadas:

📝 [Instituto Brasileiro de Geografia e Estatística (IBGE)](https://www.ibge.gov.br/)

<br>
<br>

## 🔧 Visualização

<br>

```bash
# Clonar o repositório
$ git clone https://github.com/CintiaAguiar/academia-e-maternidade-analise.git

# Entrar na pasta do repositório
$ cd academia-e-maternidade-analise

# Instalar as bibliotecas
$ pip install pandas as pd
$ pip install matplotlib.pyplot as plt
$ pip install seaborn as sns

# Executar o arquivo de análise no Jupyter Notebook
$ jupyter notebook analise_exploratoria.ipynb

```
<br>
<br>

## 🛠️ Interface Gráfica

<br>

📌 Este projeto está com visualizações públicas no Tableau. Você pode acessar clicando [AQUI](https://public.tableau.com/views/AInvisibilidadedaMaternidadenaCarreiraAcadmica/Histria1?:language=pt-BR&:display_count=n&:origin=viz_share_link).


## 🙏 Agradecimentos

Agradeço a todos que contribuíram e apoiaram este projeto de alguma forma. Cada ajuda, feedback e suporte são imensamente valiosos.

Este projeto é fruto da inspiração e orientação valiosa da Professora [Mariana Rezende](https://www.linkedin.com/in/mariana-vb-rezende/). Gostaria de expressar minha sincera gratidão a todas as incríveis professoras que iluminaram meu caminho durante este percurso, à líder técnica Mayhhara por sua orientação inestimável, e à Babi, mentora de diversidade, pelo suporte constante.

Um agradecimento especial ao meu esposo, que esteve ao meu lado durante todo o processo, à Jani, nossa facilitadora excepcional, e à Ju, cujo acolhimento foi um farol nos momentos de caos e incerteza. Às amigas da On26, cujo apoio e colaboração transformaram este projeto em uma jornada significativa. Agradeço a todas as pessoas envolvidas, cada uma contribuindo de maneira única para a construção desse conhecimento enriquecedor. Este projeto é uma celebração da potência que surge quando mulheres se unem para criar, aprender e prosperar. 🚀

Se você também contribuiu e não foi mencionado aqui, saiba que sua ajuda é igualmente apreciada. Obrigada a todos que fazem parte desta jornada!

<br>
<br>

<span align="center">

# Muito obrigada a todos que acompanharam até aqui! 💜


## 🙋🏾‍♀️ Autora

<br>

<p align="center">
  <a>
    <img style="border-radius: 50%;" src="https://imgur.com/sKLVGPl" alt="Foto de Perfil de Cintia"/>
    <br/>
  </a>
</p>

<p align="center"> Desenvolvido por <a href="https://www.linkedin.com/in/cintiaaguiar/" target="_blank"><img src="https://img.shields.io/badge/-Cintia_Aguiar-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/cintiaaguiar/" target="_blank"></a> </p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/84551213/171416454-ab93ab7f-e5a0-4276-81ec-4f5cb79dff31.png" alt="Logo da Reprograma" border="0" width="200" />
</p>
