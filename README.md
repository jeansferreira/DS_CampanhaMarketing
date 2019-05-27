#O dataset fornece o resultado de uma campanha de marketing para cada usuário (sim - comprou / nao - não comprou)

#Temos como variáveis:

#Dados do cliente:
#1 - idade
#2 - profissao
#3 - estado_civil
#  4 - educacao
#  5 - inadimplente
#  6 - emprestimo_moradia: possui empréstimo para moradia?
#  7 - emprestimo_pessoal: possui empréstimo pessoal?
#Dados relacionados com últimos contatos:
#  8 - meio_contato: tipo de contato
#  9 - mes: último mês de contato
#  10 - dia_da_semana: último dia da semana de contato
#  11 - duracao: última duração do contato, em segundos. Nota: este atributo causa overfitting no modelo.
#Outras variáveis:
#  12 - qtd_contatos_campanha: number of contacts performed during this campaign and for this client (numeric, includes last contact)
#  13 - dias_ultimo_contato: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)
#  14 - qtd_contatos_total: number of contacts performed before this campaign and for this client (numeric)
#  15 - campanha_anterior: outcome of the previous marketing campaign (categorical: "failure","nonexistent","success")
#Variáveis de contexto econômico e social:
#  16 - indice_precos_consumidor: mensal 
#  17 - indice_confianca_consumidor: mensal
#  18 - euribor3m: EURIBOR (European Interbank Offered Rate) diário
#  19 - numero_empregados: quaternário
