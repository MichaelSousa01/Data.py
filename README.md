📊 ETL - Pesquisa Nacional por Amostra de Domicílios

Este projeto realiza um processo simples de ETL (Extração, Transformação e Carga) em dados da Pesquisa Nacional por Amostra de Domicílios (PNAD), utilizando Python e bibliotecas populares como pandas, numpy e matplotlib.
🚀 Objetivo

Transformar dados brutos da PNAD em um formato mais legível e interpretável, substituindo códigos por valores descritivos (como unidades da federação, sexo, cor/raça e anos de estudo), além de realizar análises iniciais sobre os dados.
📂 Estrutura

    etl_pesquisanacional.py: Script principal com as etapas de ETL.

    Fonte dos dados: CSV localizado no Google Drive, extraído via Google Colab.

🛠️ Tecnologias Utilizadas

    Python 3

    Google Colab

    pandas

    numpy

    matplotlib

🔄 Etapas do Processo

    Extração:

        Leitura dos dados em CSV a partir do Google Drive.

    Transformação:

        Identificação e exibição de valores nulos.

        Substituição de códigos numéricos por categorias legíveis:

            UF (estados) segundo tabela do IBGE.

            Sexo, cor/raça e anos de estudo.

    Carga:

        O dataframe transformado é mantido na memória para futuras análises ou exportação.

📈 Resultados Esperados

Após a execução do script, o dataset estará com colunas mais compreensíveis, prontas para análises estatísticas, geração de gráficos ou aplicação de modelos de dados.
📌 Observações

    O arquivo foi originalmente desenvolvido em Jupyter Notebook no Google Colab.

    Algumas células comentadas com instruções educacionais foram mantidas para fins didáticos.

🤝 Contribuição

Sinta-se à vontade para abrir issues, sugerir melhorias ou enviar pull requests.
