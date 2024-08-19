# Speedtest - Analise

Prepara e visualiza dados das velocidades de download de internet no Brasil durante 2021. Utilizando gráficos e tabelas, comparamos essas velocidades com o Índice de Desenvolvimento Humano (IDH) do mesmo período. O objetivo é obter insights visuais e analíticos sobre como a qualidade da internet se relaciona com o desenvolvimento regional.

## Utilização

#### O programa possui duas partes principais: preparação inicial do conjunto de dados e a filtragem e geração de gráficos e tabelas. 

Para facilitar a utilização, o seguinte <a href="https://drive.google.com/file/d/1taFnCSQX3_zY2mHjmmjFRSu4Jb9jkoo8/view?usp=sharing">Link</a> já contém o arquivo "2021-Q04.parquet". No entanto, na pasta AWS, estão disponíveis os códigos utilizados para extrair a base de dados da AWS por meio do script "Download_baseAWS.sh". É necessário ter o AWS CLI instalado em seu computador. O arquivo "Modifica_nomeparquet.py" renomeia automaticamente os arquivos baixados para o formato: Ano-Quartil.

Após ter o acesso aos arquivos baixados e renomeados corretamente basta abrir o arquivo "Mapas de calor.ipynb" ou "Speedtest_Analysis.ipynb", o primeiro realiza uma filtragem para gerar um mapa de calor do Brasil com o IDH de 2021 e outro de velocidade de download(mbps) do mesmo ano, o segundo arquivo gera os Boxplots e correlações alem de uma nova filtragem que será utilizada pelo arquivo "Resumo Estatístico.r". 

## Images:

### Resumo Estatístico:
![resumo_estatistico](https://github.com/gabs4841/Speedtest-Analysis/assets/74026100/afe33e10-f4b9-4192-b00c-780ac0de623f)

### Boxspots:
![Boxplots](https://github.com/gabs4841/Speedtest-Analysis/assets/74026100/f5f2562f-1cee-4ec9-9b70-7eddded97f79)

### Mapa do Brasil - Velocidade de Download (2021):
![ff](https://github.com/gabs4841/Speedtest-Analysis/assets/74026100/0339992b-d047-41ee-877f-2b4e27eaac16)

### Mapa do Brasil - IDH (2021):
![ee](https://github.com/gabs4841/Speedtest-Analysis/assets/74026100/a644e03e-9640-46df-b7dc-62e9b3aa20ed)

### Correlação entre IDH e Velocidade de Download:
![Correlacao_idh_velocidade](https://github.com/gabs4841/Speedtest-Analysis/assets/74026100/7f4814d6-13a6-49de-b1ef-72b4986d3948)

### Correlação entre Velocidade de Upload e Download:
![correlacao_upload_download](https://github.com/gabs4841/Speedtest-Analysis/assets/74026100/c81b64e6-9ca5-4983-933a-f9dc75f2dc9a)

## Créditos
Este trabalho utiliza a base de dados "<a href="https://github.com/teamookla/ookla-open-data">ookla-open-data</a>" disponibilizados por Amazon e Ookla 

Também utiliza o "<a href="http://www.atlasbrasil.org.br/ranking">Ranking Todos Estados do Brasil em 2021</a>" disponibilizados por Atlas Brasil

Este programa foi criado por [Gabriel Medina da Assunção](https://github.com/gabs4841) e [Jonatas Fernandes Andrade](https://github.com/JFA000).
