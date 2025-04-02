Tratamento dos dados:

Preenchimento de valores nulos: df['score'].fillna(df['score'].mean()) substitui valores nulos pela média da coluna, uma técnica comum para tratamento de valores ausentes.
Definição de limites aceitáveis: Isso é importante para remover dados que estão fora do escopo esperado (possíveis erros ou outliers).
Filtragem de valores fora do padrão: Mantém apenas os registros dentro dos limites aceitáveis definidos, garantindo que a análise subsequente seja mais precisa.
