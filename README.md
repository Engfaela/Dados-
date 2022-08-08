# Dados-
Primeiro Projeto Analise Dados

Hello, world!

# Variáveis: Definição e tipos

# Declarando 3 variáveis e atribuindo valores a elas
var_string = "Hello!"
var_number = 9
var_float = 9.0

# Imprimindo os valores das variáveis
print(var_string)
print(var_number)
print(var_float)

# Imprimindo os tipos das variáveis
print(type(var_string))
print(type(var_number))
print(type(var_float))

# Conversões de variáveis

print(var_float)
print(str(var_float))          # Convert to string
print(int(var_float))          # Convert to int
print(var_float)

pnad = pd.read_csv('dados_pnad.csv',sep=',')

    normalize = True
dist_freq_quantitativas_personalizadas = pd.DataFrame(
    {'Frequência': frequencia, 'Porcentagem (%)': percentual * 100}
)
dist_freq_quantitativas_personalizadas.round(2)
