# Documentação do Projeto

## Tópicos em Banco de Dados

Este documento apresenta a documentação detalhada de cada etapa do projeto desenvolvido para a disciplina de **Tópicos em Banco de Dados**. Seu objetivo é servir como um tutorial, garantindo que todos os integrantes do grupo compreendam o passo a passo da execução do projeto.

---

## Sumário

1. [Coleta de dados](#coleta-de-dados)  
   1.1. [Crawler](#crawler)

---

## Coleta de dados

**Objetivo:** Coleta de artigos sobre NLP publicados nos anais do congresso do BRACIS no ano de 2024.

**Caminho de acesso aos artigos (utilizado no crawler):**  
[https://sol.sbc.org.br/index.php/bracis](https://sol.sbc.org.br/index.php/bracis)

O crawler faz a busca por títulos que possuem as seguintes expressões:

> `nlp`, `linguagem`, `language`, `text`, `texto`, `corpus`, `bert`, `transformer`, `llm`, `summariz`, `resum`, `translation`, `tradu[cç]`, `sentiment`, `opini`, `classifica`, `parsing`, `tagging`, `entity`, `question`, `answer`, `dialog`, `speech`

Os artigos são salvos em uma lista contendo:

- Título  
- Autor  
- Página  
- DOI  
- URL do artigo  
- URL do PDF

> Obs: A URL do PDF direciona para o Springer, que requer login e senha, dificultando o download dos artigos.

Foi utilizada a lista gerada pelo crawler para realizar a busca manual dos artigos no site do BRACIS, e todos os arquivos foram encontrados no seguinte drive:

🔗 [Link para o drive](https://drive.google.com/drive/folders/1WaGDb_3rEzs38MXeRXYyVVB7b0M0CBVC)

Para auxiliar na busca dos artigos no drive, utilizamos o seguinte arquivo para encontrar os artigos por tema:

🔗 [Link para o arquivo](https://drive.google.com/file/d/18VVKUG2H9K-i3GeqGUtburhT-Ez1XJwA/view)

Alguns artigos que não estavam na lista do crowler também foram incluídos.
