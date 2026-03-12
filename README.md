# Sprint 4 - Modelagem Matemática aplicada à Energia Solar

## Visão geral
Este projeto apresenta uma análise de **otimização de slope (inclinação)** e **azimuth (orientação)** em painéis solares, com foco em maximizar a geração anual de energia.

O estudo foi desenvolvido em **Jupyter Notebook** e utiliza como contexto a região da **Avenida Paulista, São Paulo - SP**. A proposta foi comparar diferentes cenários de instalação fotovoltaica para entender como a configuração dos painéis influencia o desempenho energético ao longo do ano.

## Objetivo
Avaliar o impacto da otimização dos parâmetros **slope** e **azimuth** na produção de energia de um sistema fotovoltaico, comparando cenários fixos e cenários otimizados.

## Conceitos trabalhados
- **Slope (inclinação):** ângulo entre o painel e o solo.
- **Azimuth (azimute):** orientação horizontal do painel em relação ao norte.
- **Otimização:** busca pela melhor configuração possível para aumentar a eficiência do sistema.

## Localização analisada
**Avenida Paulista, São Paulo - SP**  
Latitude: **-23.56**  
Longitude: **-46.65**

## Metodologia
No notebook, foram comparados três cenários principais:
1. **Simulação 1 - Configuração fixa**
2. **Simulação 2 - Otimização do slope**
3. **Simulação 3 - Otimização do slope e do azimuth**

A análise considera:
- produção anual de energia (**kWh/ano**);
- média mensal de geração (**kWh/mês**);
- comparação visual por gráficos;
- interpretação prática dos resultados para projetos reais.

## Principais resultados
- **Pior cenário:** Simulação 1 (fixa), com **1325 kWh/ano**
- **Melhores cenários:** Simulação 2 e Simulação 3, ambas com **1380 kWh/ano**
- **Ganho estimado:** cerca de **4,15%** em relação ao cenário fixo

## Conclusões
A análise mostra que a otimização dos parâmetros de instalação pode melhorar a geração de energia do sistema fotovoltaico. Mesmo quando o ganho percentual não parece muito alto, esse aumento pode representar melhor aproveitamento energético e maior retorno financeiro em projetos reais.

Além disso, o projeto reforça a importância da modelagem matemática e da análise de variáveis físicas na tomada de decisão em soluções de engenharia e tecnologia.

## Estrutura do repositório
```bash
.
├── README.md
├── Notebook.ipynb
└── .gitignore
```

## Como visualizar
1. Baixe ou clone este repositório.
2. Abra o arquivo `Notebook` em:
   - **Jupyter Notebook**
   - **JupyterLab**
   - **Google Colab**

## Tecnologias e recursos
- Python / Jupyter Notebook
- Modelagem matemática
- Análise de eficiência energética
- Conceitos de energia solar fotovoltaica

## Autor
**Matheus**
