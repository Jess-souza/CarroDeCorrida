### Exercício carro de corrida :octocat: :heavy_check_mark:

**O programa deve:**
Criar um sistema para uma corrida.<br>Para isso você vai precisar criar as seguintes classes e métodos:

**Classe CarroCorrida**
- **Atributos**<br>
numeroCarro : Interger<br>
piloto : Piloto<br>
velocidadeMaxima : float<br>
velocidadeAtual : float<br>
ligado : boolean<br>
- **Métodos**<br>
"Construtor"<br>
set... (alterar atributos da Classe - "Modificadores")<br>
get... (retorna valores dos atributos da Classe - "Acessores")<br>
acelerar(float) - aumenta a velocidade em Km/h (Soma em Km/h a velocidade atual)<br>
frear(float) - reduz a velocidade em Km/h (subtrair em Km/h a velocidade atual)<br>
parar() - velocidade igual a 0 Km/h<br>
ligar()<br>
desligar()<br>
*Observações: *Não ultrapassar a velocidade máxima *Frear e Acelerar só funcionam se o carro estiver ligado *Desligar só funciona se o carro estiver parado<br>


**Classe Piloto**
- **Atributos**<br>
nome : String<br>
idade : Interger<br>
sexo : Enum<br>
equipe : String<br>
- **Métodos**<br>
"Construtor"<br>
set... (alterar atributos da Classe - "Modificadores")<br>
get... (retorna valores dos atributos da Classe - "Acessores")<br>
