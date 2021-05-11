# TitanicProject
 Projeto de DataScience Titanic

Dicionário dos dados
Variável  | Definição | Chave
--- | --- | ---
survival | Se o passageiro sobreviveu | 0 = Não; 1 = Sim
pclass | Classe do bilhete | 1 = 1ª, 2=2ª, 3=3ª
sex    | Sexo |
Age    | Idade |
sibsp | Número de 'irmãos'/'conjûge' abordo |
parch | Número de pais/filhos de um passageiro abordo |
ticket | Número do bilhete |
fare   | Tarifa do passageiro |
cabin  | Cabine |
embarked | Porto de embarcação | C = Cherbourg, Q = Queenstown, S = Southampton

Notas sobre as variáveis:\
pclass: Uma "aproximação" da classe social do indíviduo.\
1: Classe Alta\
2: Classe Média\
3: Classe Baixa

Age: A idade é uma fração se menor que 1.

sibsp: O dataset define as relações familiares da seguinte maneira:\
irmãos = Irmã, irmão, meio-irmão, meia-irmã\
conjûge = Marido ou esposa (Amantes ou Noivos foram ignorados)

parch: O dataset define as relações familiares da seguinte maneira:\
Pais = Mãe, pai\
Filhos = Filha, filho, enteado(tanto homem quanto mulher)\
Algumas crianças só vieram com uma babá, então parch=0 para elas