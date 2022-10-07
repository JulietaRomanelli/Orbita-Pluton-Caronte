# Orbita-Pluton-Caronte

El objetivo de este trabajo es modelizar la Ley de Newton a través de métodos numéricos, que describen la trayectoria de un satélite alrededor del sistema Plutón-Caronte.
A partir de la selección de determinados parámetros y el método matemático a emplear (como Euler Explícito, Runge Kutta 2 o Runge Kutta 4), el código devuelve la órbita realizada así como un gráfico de Velocidad vs Energía. 
Los parámetros a elección se pueden ir modificando para observar diferentes peculiaridades en la órbita. Por ejemplo, el código permite analizar las variaciones ante la presencia o no de la luna Caronte así como considerar o no la rotación entre ellos. 
Además, se puede realizar una evaluación de los métodos empleados ya que también se calculan los errores en las trayectorias según el modelo usado. 

A partir de diferentes simulaciones se obtuvo los rangos de velocidades iniciales del satélite a partir de los que este chocaba con Plutón o daba órbitas por ciertas características, hasta que se salia del sistema. 

Además para analizar la influencia de la rotación entre los cuerpos al agregarle una fuerza centrífuga, se realizó un código aparte que permita hallas los Puntos de Lagrange del sistema rotante. 
