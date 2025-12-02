Análise da Relação entre Fatores Ambientais e a Gravidade de Acidentes no Nordeste

Autores:

- Flavio Henrique Santos
- Gustavo Henrique Passiani Florêncio
  
Centro Universitário SENAI São Paulo

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Resumo do Projeto:

Este estudo de Análise de Dados investigou a correlação estatística entre fatores ambientais (clima e fase do dia/iluminação) e a gravidade dos acidentes de trânsito na Região Nordeste do Brasil.

Utilizando dados abertos da Polícia Rodoviária Federal (PRF), a pesquisa comprovou, via Teste de Qui-quadrado ($\chi^2$), que a visibilidade reduzida é um fator que aumenta significativamente a chance de acidentes serem classificados como Gravíssimos ou Fatais.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Palavras-Chave:

Segurança Viária · Análise de Acidentes · Condições Climáticas · Iluminação · Qui-quadrado

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Objetivo:

O objetivo central foi validar a hipótese de que o ambiente (clima e iluminação) possui uma influência direta e mensurável na severidade final de uma colisão, e não apenas na sua ocorrência.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Metodologia e Pipeline de Dados:

O projeto seguiu um rigoroso pipeline de Data Science, implementado majoritariamente em Python, utilizando o Jupyter Notebook (Script_analises_Nordeste.ipynb).

1. Fonte de Dados
     
    -	Origem: Dados Abertos Oficiais da Polícia Rodoviária Federal (PRF).
      
    -	Período: Dados de acidentes de 2024 (filtrados para a Região Nordeste).
      
    -	Variáveis Chave: gravidade, condicao_metereologica, fase_do_dia.

2. Ferramentas (Python)

    Pandas ->	Limpeza, manipulação e categorização dos dados.

    Matplotlib / Seaborn -> Geração de gráficos de frequência e proporção de risco.

    SciPy.stats -> Validação estatística (função chi2_contingency).

3. Passos da Análise:
   
  1.	Importação e Filtragem: Carregamento do dataset e seleção de acidentes na Região Nordeste.
  	
  2.	Limpeza/Categorização: Normalização e padronização das colunas (Ex: Gravidade: Sem Vítimas, Feridos Leves, Feridos Graves, Fatais).
  
  3.	Análise Descritiva: Geração de gráficos para visualizar a distribuição da gravidade em função do clima e da fase do dia.
     
  4.	Validação Estatística: Aplicação do Teste de Qui-quadrado para testar a independência.










