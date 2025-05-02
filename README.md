📊 Base de Dados  

A base de dados coletada neste projeto contempla os palpites de resultados das partidas da Série A do Campeonato Brasileiro, referentes às edições de 2023 e 2024. Os dados foram obtidos manualmente e via web scraping, a partir de diferentes fontes online.

📁 Estrutura comum dos dados
Tanto em 2023 quanto em 2024, a base compartilha os seguintes atributos principais:

- Rodada: Número da rodada do campeonato (de 1 a 38).
- Mandante: Nome do time que jogou como mandante.
- Visitante: Nome do time visitante na partida.
- Resultado: Resultado real da partida, codificado da seguinte forma:

  - 1 – Vitória do mandante
  - 2 – Vitória do visitante
  - 0 – Empate
  - -1 – Informação não disponível

📅 Dados de 2023  

A aba '2023' da base de dados inclui os seguintes colunistas, cujos palpites foram extraídos do portal ge.globo.com (Globo Esporte), com exceção do último, que pertence a um portal externo:

- Alex Escobar
- Barbara Coelho
- Carlos Mansur
- Espião Estatístico
- Felipe Diniz
- Henrique Fernandes
- Richarlyson
- Tiago Medeiros
- UmDoisEsportes ← palpites extraídos do portal UmDoisEsportes

📅 Dados de 2024  

Na aba '2024' da base de dados, também composta majoritariamente por colunistas do ge.globo.com, temos os seguintes palpiteiros:

- André Loffredo
- Alex Escobar
- Carlos Mansur
- Espião Estatístico
- Felipe Diniz
- Jessica Cescon
- Rodrigo Coutinho
- Tiago Medeiros
- 90 minutos ← palpites extraídos do portal 90minutos

🔗 Aba URLs  

A aba URLs da planilha reúne todos os links consultados durante o processo de coleta manual dos dados. Cada conjunto de links está nomeado no seguinte formato:

[nome do site] - [edição do campeonato]  

Exemplo:
- GloboEsporte - 2023
- 90minutos - 2024

🧠 Aba UmDois2023  

Essa aba foi gerada automaticamente com os dados extraídos por meio de um scraper implementado em Python com a biblioteca BeautifulSoup. O funcionamento detalhado desse processo está descrito no capítulo de Desenvolvimento do TCC.

Além disso, o arquivo Python disponível no repositório contém comentários explicativos que detalham o funcionamento do código, facilitando o entendimento e possíveis adaptações futuras.
