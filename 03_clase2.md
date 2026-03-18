## Variables macroscópicas

Permiten definir un estado termodinámico / el estado de un sistema termodinámico
Las variables pueden condicionarse entre sí o producir sistemas con una de ellas constantes
	Volumen frente a Temperatura a presión constante
	(Gráfico V/T)
En estos casos se trabaja con **diferenciales inexactas**

Pueden ser: **Intensivas o Extensivas** ([[quim-fis/02_introducción|02_introducción]])
	Las variables extensivas pueden ser normalizadas entre si para que funcionen independiente del tamaño del sistema.
		Em = Energía molar (J/mol)
		Vm = Volumen molar
		Sabiendo la cantidad de materia (moles) se puede conocer el valor de distintas variables extensivas.

### Ejemplos de relaciones entre variables

- Ley de Boyle (pulmones)
	P ~ I/V (n y T constantes)

- Ley de Charles (respiración)
	V ~ T (P y n constantes)

- Ley de Gay-Lusaac (Esterilización)
	P ~ T (V y n constantes)

- Ley de Avogadro
	V ~ n (P y T constantes)
	A mayor cantidad de partículas, mayor volumen

T = Temperatura = movimiento de partículas
P = Presión = choques de partículas contra el borde (paredes)
	P = F/A (F: fuerza (N), A: área (m²))
n = Moles = cantidad de materia en el recipiente
R = Cte. universal de los gases = k_b x N
	k_b = cte. de Boltzmann (J/Kelvin)
	N = N° partículas por mol (1/mol)
	Proviene de análisis experimentales

- **Ley de Gases ideales** -> Modelo termodinámico
	PV = nRT
	**Limitaciones**:
	- Se asume *partículas infinitesimales* (sin volumen) o volumen del sistema mucho mayor al de las partículas
	- Se asume *sin interacciones* entre partículas (Fuerzas atractivas y repulsivas ausentes)
	- Debe aplicarse cuando la presión tiende a 0 (P->0)
		- La presión implica fuerzas entre partículas
		- Esto significa que el sistema debe tener baja densidad

Ec = Energía cinética promedio por partícula = 3/2 x k_b x T
	3/2 -> 3 x 1/2
		1/2 -> Teorema de equipartición de la energía
		3 -> 3 dimensiones
Ec = Energía cinética promedio por mol = 3/2 x R x T

## Estado termodinámico

Estado de un sistema que puede ser descrito por x variables macroscópicas
Si se altera alguna de esas variables, se puede saber las respuestas de las otras.

Ej: P, V, T, n -> Responde a ley de Gases ideales
Estado 1         | Estado 2
P1, V1, T1, n  |  P2, V2, T2, n

A presión constante (P1 = P2)
P1 = nRT1 / V1 | P2 = nRT2 / V2
P1 = T1/V1        | P2 = T2/V2
	T1/V1 = T2/V2

## Ecuación de estado

Debe tener una igualdad que relacione distintas variables termodinámicas

**PV = nRT** -> Ecuación de estado
	Si se quiere despejar X, las variables serán (n)
		P(T, V, n)
		V(T. P, n)
		T(V, P, n)

Esto actúa como una función:
	F(x, y) = x² + y²
	P(T, V, n) = nRT / V
		Con R constante

(dV/dT)P = nR(T)'/P = nR/P

### Gas de Van der Waals
-> Modelo más realista
	**Considera interacciones** repulsivas o atractivas

**P = nRT/(V-nb) - (an²)/V²**
	V-nb -> Corrección del volumen 
		Las partículas tienen volumen
	an²/V² -> Corrección de las interacciones
		Las interacciones tienen efecto sobre la presión. Cohesivas reducen la presión, repulsivas la aumentan

Esta ecuación es **empírica**, no meramente teórica, que introduce las constantes **a** y **b** cuyos valores *dependen del tipo de gas* que se relaciona con los resultados experimentales y ajusta los resultados a la realidad.
	**Si a y b = 0**, se transforma en la ley de los *gases ideales*. Esta última es una ley límite que se cumple en condiciones específicas de la ley de Van der Waals.


**Gráfico Epot / r**

Ep = Energía potencial
	Depende de posición e interacciones
r = Distancia de separación entre partículas (Dist. interpartícula)

En el caso de un Gas ideal:
	Cuando r > 0 -> Ep = 0
	Si r = 0 -> Ep ~ ∞

En un Gas de Van der Waals
	Siguiente clase