# TitanicProject Kaggle - Top 17% - Acurácia 0.78468
O naufrágio do Titanic é um dos naufrágios mais infames da história.

Em 15 de Abril de 1912, durante a sua viagem inaugural, o então considerado não afundável RMS Titanic afundou-se após colidir com um iceberg. Infelizmente, não havia barcos salva-vidas suficientes para todos a bordo, resultando na morte de 1502 dos 2224 passageiros e tripulação.

Embora houvesse algum elemento de sorte envolvido na sobrevivência, parece que alguns grupos de pessoas tinham mais probabilidades de sobreviver do que outros.

Neste desafio, irei produzir um modelo preditivo que responda à seguinte pergunta: "que tipos de pessoas tinham mais probabilidades de sobreviver?", utilizando dados sobre passageiros (ou seja, nome, idade, sexo, classe socioeconómica, etc.). 

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
