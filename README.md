# Dead Cells Analysis with StreamLit & NgRok

"Análise de diversos gameplays registrados em planilha + dicionário de armas"

Com a intenção de criar um ambiente interativo e simplista, este projeto possui como estrutura, 2 códigos:
- Contrução do ambiente e importação do streamlit e ngrok (cria o link de acesso pelo navegador);
- Leitura e agrupamentos dos dados utilizando pandas.

Colunas do dataset "trilha-deadcells.csv":
- runid
- lastDungeon
- gear01
- gear01ScaleWith
- gear02
- gear02ScaleWith
- gear03
- gear03ScaleWith
- gear04
- gear04ScaleWith
- Brutality
- Tactical
- Survivor
- totalScrolls
- bonusCollar
- lifeValue
- mutation01
- mutation02
- mutation03
- beatConcierge?
- beatConjuntivictus?
- beatTimeGuardian?
- beatHandOfTheKing?
- deathBy
- death?

Quais informações podemos extrair deste projeto?
- Nas vitórias contra o primeiro chefe, quais as armas e habilidades mais selecionadas pelo jogador? E nas derrotas?
- Qual a frequência de escolha nos status de equipamento (Brutalidade, Tática e Sobrevivência)?
- Análise do crescimento dos status de equipamento em série temporal utilizando dados coletados de um gameplay completo.

Colunas do dataset "gear-data.csv":
- gearPosition
- class
- name
- description
- base dps
- base special dps
