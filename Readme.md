## Projeto de Leitura de Sitemap
Este projeto é um script Python que lê sitemaps XML a partir de URLs fornecidas, extrai todas as URLs listadas e as salva em um arquivo Excel. O script faz uso das bibliotecas requests, xml.etree.ElementTree, e pandas para realizar a requisição HTTP, parsing do XML e manipulação de dados, respectivamente.

## Passos para utilização
1. Configure a URL do Sitemap:

    - Modifique a lista sitemap_xml com as URLs dos sitemaps que você deseja processar.

2. Execute o Script:

    - Rode o script Python. Ele fará o download dos sitemaps, extrairá as URLs e as salvará em um arquivo Excel.

3. Verifique o Resultado:

    - O arquivo Excel gerado será salvo no diretório especificado em xlsx_dir. Verifique o arquivo links_produtos.xlsx para ver a lista de URLs extraídas.

## Requisitos para Executar o Programa
- Jupyter Notebook
- Python 3.x
- Conexão com a Internet (para acessar os sitemaps)
- Permissão para escrever no diretório onde o arquivo Excel será salvo

## Pré-requisitos
- Antes de executar o script, você precisa instalar as bibliotecas necessárias. Essas bibliotecas podem ser instaladas usando pip.

## Instalação das Bibliotecas Necessárias: 
    pip install requests pandas
    pip install requests


## Permissões: 

Certifique-se de que você tem permissões adequadas para:
- Ler as URLs dos sitemaps (deve ser acessível a partir do seu ambiente de execução).
- Gravar no diretório especificado para salvar o arquivo Excel.