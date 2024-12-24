### BI Comercial Contoso Microsoft - Power BI | Análise de dados

Link de acesso ao pbix publicado:

https://app.powerbi.com/view?r=eyJrIjoiMTBhZTQ5YzMtMmYyZi00N2YyLTlkYjMtNzNkYTQzMzNjMDVmIiwidCI6ImI1NTBlNzA3LTEwY2MtNDc2ZC05NDExLWJkOGM5ZGU3ZWNjNCJ9

### Objetivo

O objetivo deste projeto é proporcionar uma análise abrangente das operações de vendas da empresa fictícia Contoso, explorando diferentes aspectos de sua performance comercial. Por meio do uso de ferramentas como Power BI, busca-se analisar as principais métricas de desempenho, como receita total, lucro líquido, margem de lucro e quantidade de produtos vendidos, oferecendo uma visão clara e objetiva dos resultados financeiros da empresa.

Outro foco central é a avaliação da performance regional, comparando o desempenho de vendas em diferentes localidades e identificando áreas com maior potencial de crescimento ou que necessitam de estratégias de melhoria. Essa análise regional é crucial para entender o mercado e planejar ações de expansão.

Por fim, o projeto inclui uma análise detalhada de tendências de mercado, utilizando dados temporais para identificar sazonalidades e prever demandas futuras. Isso possibilita à empresa antecipar necessidades do mercado e tomar decisões estratégicas baseadas em dados concretos, aumentando sua competitividade no setor.
Este projeto visa demonstrar como a análise de dados pode transformar informações brutas em insights valiosos, promovendo decisões mais embasadas e estratégias de negócio mais eficientes.

### Detalhes das métricas utilizadas e resumo dos resultados

Dentro do projeto, implementei um novo tipo de campo no visual nativo de "card", visando aprimorar a experiência de análise de dados, graças há uma atualização do Power BI.

![image](https://github.com/user-attachments/assets/23f485ac-5bab-478f-bfdc-53ad5de81e14)

Agora com essa nova funcionalidade, a visualização ficou mais granular mesmo construída de modo simples. Como podemos ver, neste ano selecionado o faturamento caiu aproximadamente 10% em comparação ao ano anterior. 

Ademais, um dos objetivos do BI era o acompanhamento de indicadores ao longo do tempo. 

![image](https://github.com/user-attachments/assets/4578b3ce-6db9-4484-b55d-85670cbcc39a)

O Relatório apresenta isso muito bem e de dois modos, sendo a segunda com uma análise YoY.

Os indicadores estão vinculados a um parâmetro que é de seleção obrigatória para escolher a métrica que será analisada.

![image](https://github.com/user-attachments/assets/f830bdf5-13b0-44c8-8f8a-b621b64caee7)

Outras métricas são apresentadas vinculadas ao mesmo parâmetro, como o indicador de seleção distriubido por meio da venda atráves de um gráfico de barras horizontais.  

![image](https://github.com/user-attachments/assets/78e60292-6591-4e0d-839e-02abaedb646f)

Além também da métrica distribuída por Classifição do produto, atráves de um gráfico de pizza. Essa análise é importante para saber de quais classes são os produtos mais vendidos, os que dão mais lucro, mais faturamento e que detém maior quantidade no estoque. 

![image](https://github.com/user-attachments/assets/c65ef63a-171f-406c-96a4-1e3a53fd69bc)

À vista disso, podemos logo identificar que temos a classificação 'Regular' com maior quantidade de produtos vendidos, representando 50%. Porém, isso não quer dizer que essa categoria tem o maior faturamento ou maior lucro por conta desse indicador, será preciso verificar alterando os parâmetros de selecão. 

Por fim, para uma visão mais no detalhe a nível regional temos um grid também vinculado ao parâmetro. 

![image](https://github.com/user-attachments/assets/ba66d330-c88e-4cf9-960a-d7414bc0df88)

### Ferramentas e Metodologia

 - Ferramentas Utilizadas: Power BI e Figma.

 - Conexão de Dados: A base de dados foi importada de um View no SQL Server.

 - Processo ETL: Todo o processo de transformação e limpeza dos dados foi realizado no SQL. 

### Como Reproduzir o Projeto

- O link no início do README contém a publicação do BI de forma pública.

 - Baixar o arquivo .pbib (necessário mudar a extensão para pbix depois de baixar), dessa forma, tem acesso a todo o projeto, como: bases, cálculos, imagens, modelagem e ícones. (É necessário ter o Power BI Desktop instalado)
