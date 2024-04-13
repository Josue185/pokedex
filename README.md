# Minha Pokedex

Introdução ao Projeto
Na qualidade de analista de dados, sempre procurei integrar as metodologias analíticas avançadas no contexto de interesses pessoais para aprimorar tanto a minha compreensão técnica quanto o meu engajamento com os dados. Assim, decidi empreender um projeto onde eu poderia extrair e analisar dados de uma API pública - a API Pokémon - utilizando ferramentas sofisticadas como o Google Colab para scripts Python e o Power BI para visualizações de dados, focando nas métricas de ataque dos Pokémon.

Coleta e Preparação de Dados
O primeiro passo foi estabelecer uma conexão com a API Pokémon através de requisições HTTP no Google Colab. Utilizei o pacote requests para acessar dados de cada Pokémon, especificamente suas estatísticas de ataque, um fator crítico nas estratégias de batalha do jogo. Através de iterações sequenciais, obtive informações de cada Pokémon, filtrando e armazenando dados essenciais como nome, tipo e valor de ataque.

![Captura de tela 2024-04-13 145450](https://github.com/Josue185/pokedex/assets/92592495/4d9a8add-dd22-4c9f-ade1-1d76dc076500)

![Captura de tela 2024-03-29 153528](https://github.com/Josue185/pokedex/assets/92592495/f821ec19-97da-4950-8bbf-30bd727baca9)

![Captura de tela 2024-03-29 153506](https://github.com/Josue185/pokedex/assets/92592495/ade7512e-4628-4d2f-9652-135cfdbe9bed)



Com os dados em mãos, procedi com a etapa de limpeza e transformação dos dados, utilizando a biblioteca pandas para manipular as estruturas de dados e preparar um conjunto limpo para análise. O critério foi identificar e isolar os cinco Pokémon com os maiores índices de ataque de cada tipo, garantindo uma análise focada na capacidade ofensiva.

Visualização e Análise no Power BI
Uma vez preparados e exportados os dados para um arquivo CSV, carreguei-os no Power BI, onde configurei um gráfico de barras para ilustrar de maneira eficaz os dados coletados. A visualização foi desenhada para enfatizar a comparação direta entre os valores de ataque dos cinco Pokémon mais fortes, com barras coloridas correspondentes a cada tipo de Pokémon.

No Power BI, apliquei uma série de técnicas de formatação para aprimorar a visualização, incluindo ajustes de cores para corresponder aos tipos elementares dos Pokémon, configuração de rótulos e escalas e, crucialmente, a implementação de interatividade através de tooltips que fornecem mais contexto sobre os dados exibidos.

![Captura de tela 2024-04-13 165224](https://github.com/Josue185/pokedex/assets/92592495/343362b4-8bf9-4222-a4df-360d9e17e082)

![Captura de tela 2024-04-13 165246](https://github.com/Josue185/pokedex/assets/92592495/f07ae1f9-cbef-4b8e-974b-d335ff28de57)

![Captura de tela 2024-04-13 165306](https://github.com/Josue185/pokedex/assets/92592495/572cdbd3-70b4-4cd1-af88-43acc165f7cc)


Conclusão
Este projeto não apenas me permitiu revisitar um interesse de infância com uma perspectiva analítica, mas também reforçou a aplicabilidade das técnicas de ciência de dados em diversos contextos, demonstrando a flexibilidade e a robustez das ferramentas contemporâneas de análise de dados. Através do Power BI, pude não só visualizar, mas também comunicar de forma intuitiva e acessível.






