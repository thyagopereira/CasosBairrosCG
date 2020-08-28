![](Logo.jpg)



# CasosBairrosCG

Trata-se de uma base de dados para o projeto "Predição Georeferrenciada de surtos de Covid - 19 "
A contagem dos dados foi feita de acordo com diversas metricas e o processo pode ser detalhado abaixo.

# Processo 

A principio foi necessario filtrar todos os casos tidos como positivos dentro da cidade de Campina Grande.
Em seguida, quando o cep estava disponível utilizamos nossa base de dados de ceps , para identificar o bairro oficial segundo o IBGE.
Uma vez que algumas localizações tinham ceps/ invalidos ou Inexistentes , foi preciso tratar esses dados com bibliotecas lexicas. 
Gerar uma linha do tempo na qual mantivesse uma regularidade nas datas e no respectivo numero de casos de cada bairro.
Por fim foi possivel criar uma noção acumulada do crescimento do numero de casos de COVID-19 em cada bairro de Campina Grande .

# Importante

Levamos em consideração apenas os bairros de Campina Grande que é o foco do projeto ,e tivemos uma clara perca de dados, devido ao fato de pacientes moradores de outras cidades foram atendidos em hospitais de Campina.


# Agradecimentos 
[Arthur](https://github.com/arthuralv)  Pelo grande auxilio com a produção do codigo e com o tratamento das bibliotecas. 
E a todos os participantes do nosso projeto. 




