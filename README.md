## 📊 Case iFood: Análise Exploratória de Dados (EDA)
Este projeto foi desenvolvido como parte do meu primeiro desafio real de análise de dados. O objetivo principal foi realizar uma exploração profunda na base de clientes do iFood para identificar padrões de comportamento, perfis de consumo e gerar insights estratégicos para as áreas de Marketing e Negócios.

## 🎯 Objetivos
Limpar e tratar os dados (duplicados, nulos e tipos de dados).

Entender o perfil demográfico (Educação, Estado Civil e Renda).

Investigar correlações entre renda, presença de filhos e volume de gastos.

Propor soluções de negócio baseadas em evidências estatísticas.

## 🛠️ Tecnologias Utilizadas
Python 3.x

Pandas: Manipulação e limpeza de dados.

Numpy: Funções matemáticas.

Jupyter Notebook / Google Colab: Ambiente de desenvolvimento.

## 🔍 Principais Insights Encontrados
Após a análise, os seguintes pontos foram destacados:


Perfil de Elite: A base de clientes é majoritariamente composta por pessoas com alto nível de instrução (Graduação, Mestrado ou PhD).  

Influência da Renda: Identificamos uma correlação forte de 0.82 entre a renda e o volume de gastos, confirmando que o aumento do poder aquisitivo impacta diretamente no faturamento.

Impacto de Filhos no Consumo: Clientes sem filhos gastam, em média, mais que o dobro do que clientes com filhos. Famílias tendem a ter um ticket médio menor.

O Fenômeno do "Vitrinismo": A correlação entre o número de visitas no site/app e o tempo sem comprar (Recency) foi próxima de 0. Isso indica que muitos clientes visitam a plataforma apenas para "olhar", sem uma intenção de compra imediata.

## 💡 Conclusões de Negócio
Com base nos dados, a estratégia recomendada para o iFood foca em:

Conversão para Famílias: Criação de combos "família" e cupons de frete grátis para incentivar o gasto de clientes com menor renda e filhos.

Quebra do Vitrinismo: Implementação de gatilhos de urgência (cronômetros e ofertas relâmpago) para converter o alto tráfego de visitas em vendas reais.

## 📂 Estrutura do Repositório

A estrutura de diretórios e arquivos do projeto está organizada da seguinte forma:
```text
DESAFIO-IFOOD/
├── .venv/                   # Ambiente virtual Python
├── data/                    # Diretório de dados
│   └── mkt_data.csv         # Base de dados bruta do iFood utilizada na análise
├── .gitignore               # Arquivos e pastas ignorados pelo Git (ex: .venv)
├── desafio-ifood.ipynb      # Notebook contendo todo o código da Análise Exploratória (EDA)
├── README.md                # Documentação principal do projeto
└── requirements.txt         # Lista de dependências e bibliotecas Python utilizadas