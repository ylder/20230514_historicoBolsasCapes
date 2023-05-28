# 20230514_historicoBolsasCapes

## 1 Descrição do projeto
	
    Coleta, armazenamento e análise de dados históricos das distribuições de bolsas de
    estudos do CAPES. No período entre abr/2004 a dez/2019.
    
    Os dados foram coletados do Data Lake público da iniciativa base dos dados, hospedado
    na Google Cloud Plataform. Dessa forma, é necessário que se tenha uma conta cadastrada
    nesse ambiente, para se ter acesso ao Google BigQuery.
    
    Tendo isso, utilizando a biblioteca python 'basedosdados', foi consultada a tabela de
    interesse no Data Lake, diretamente pelo python, e os dados resultantes foram armazenados
    em um banco de dados criado pela biblioteca 'sqlite3'.
    
    Assim, seguiu-se com uma consulta ao banco de dados do projeto e a construção da análise
    exploratória e seu resumo.

## 2 Ferramentas e técnicas utilizadas

    VS Code
    Jupyter Notebook
    SQL
    Python 3.9.10
    PowerPoint

## 3 Objetivos do autor

    • Exercitar prática da exploração de dados;
    • explorar e aprofundasr conhecimento sobre o funcionamento da visualização dedados no python;
    • aplicação de conceitos de design do livro Storytelling com dados, de Cole Nussbaumer, e;
    • por meio da escrita, exercitar a apresentação dos resultados de maneira objetiva.

## 4 Processo de execução do projeto

![fluxograma](https://github.com/ylder/20230514_historicoBolsasCapes/assets/126031404/349f6865-5465-40d1-9e6a-f5f278fe282a)

## 5 Considerações

    A pasta "projeto", possui um arquivo README.md com os resultados encontrados pela análise
    exploratória realizada no script do arquivo ".ipynb".
    
    O Script do projeto possui comentários e explicações sobre seu próprio funcionamento.
    Necessário esse aprofundamento para que haja completa compreensão do projeto.
