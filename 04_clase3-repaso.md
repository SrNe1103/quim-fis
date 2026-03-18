Hoy, por el paro, vamos a hacer un repaso de lo que vimos antes.


Es necesario definir los siguientes conceptos:
- Termodinámica -> Transformación de energía de forma eficiente y limpia
- Sistema -> Ej: Sala, vaso precipitado, cuerpo humano, células
- Variables termodinámicas macroscópicas/de estado -> 
	- P
	- T
	- V
	- n
	- $\rho$
	- m
	- E
	- H?
- Límites o paredes
- Entorno o ambiente
- Tipos de sistema

Pregunta en termodinámica:
	¿Qué pasa si el Volumen cambia con la Temperatura y Presión constante?
$$\frac{\partial{V}}{\partial{T}}_{P}$$
Variable dependiente -> V
Variable independiente -> T
Constante -> P 

Otro ejemplo:
$$\frac{\partial{V}}{\partial{P}}_{T}$$
## Modelos de trabajo

- Ley de Boyle
	$P \propto \frac{I}{V}$
	T, n constantes
- Ley de Charles
	$V \propto T$
	P, n constantes
- Ley de Avogadro
	$V \propto n$
	P, T constantes
- Ley de Gay Lusaac
	$P \propto T$
	V, n constantes

Combinando estas leyes se llega a modelo de **gas ideal**
$$ P = \frac{nRT}{V} $$
R -> Cte. universal de los gases
	$R=k_{B} \times N$
	$k_B$ -> Constante de Boltzmann
		En $\left( \frac{J}{K} \right)$

De estos modelos se pueden derivar ecuaciones de estado.
	Estas son funciones que definen una variable dependiente a partir de otras independientes
	Generalizado como $Y(x,z,q)$
Ejemplos:
	$P(n,T,V)$
	$T(n,P,V)$
	$V(n,T,P)$

En particular, el modelo del gas ideal asume que:
- P -> 0 (la presión tiende a cero)
- Partículas sin volumen (muy pequeñas en comparación al sistema)
- No interacciones moleculares

---

Si se tiene una mezcla de gases A y B, cómo se puede calcular la $P_{total}$
	Depende de las presiones parciales de los gases que la componen
	**Ley de Dalton**
	$P_{total}=P_{A}+P_{B}$
De esta forma
	$P_{A}=X_{A}P_{total}$
	$X_{A}$ = Fracción molar de A

Ejemplo de un sistema:
	Un gas ideal en un recipiente rígido con un émbolo móvil sumergido en un baño termostatado
	Sistema -> Gas ideal
	Entorno -> Baño termostatado
	Paredes -> recipiente y émbolo?
	Se puede planificar un experimento pensando en el universo termodinámico que queremos construir.

---

¿ $\left( \frac{\partial P}{\partial T}\right)_{V}$ ? $=\left( \frac{nR}{V} \right)\times T$ 

## Gas real de Van der Waals

$$ P=\frac{nRT}{V \times n b} \times \frac{an^2}{V^2}$$
**a** y **b** son constantes que dependen del gas.
	Corrección de volumen: $V\times nb$
	Corrección de la presión: $\frac{an^2}{V^2}$
Ahora:
$$ \left( \frac{\partial P}{\partial T} \right)_{V} = \left( \frac{nR}{V \times nb} \right) \times (T) - \frac{an^2}{V^2}$$
Dado $\frac{an^2}{V^2}$ constante
$$  \left( \frac{\partial P}{\partial T} \right)_{V} = \left( \frac{nR}{V \times nb} \right) \times (T) - 0 $$


Gráfico de $E_{pot}$ / $r$ 
	Con r -> Distancia interpartícula
	A medida que r varía, debería haber un cambio en la $E_{pot}$.
	
En el modelo de **Gas ideal**, la $E_{pot}$ es insensible a la variación de la distancia interpartícula
En un **Gas de Van der Waals** introduce una variabilidad más dinámica de la $E_{pot}$. 
	A distancias pequeñas, mayores a 0, las fuerzas repulsivas se disparan.
	A medida que aumenta, se presenta un "pozo" energético, que presenta fuerzas atractivas entre las partículas del gas.
		$r_{\text{umbral}}$ -> Pasado el pozo se acercan nuevamente las fuerzas a 0
			Las partículas presentan menos interacciones.
		$r_{\text{equilibrio}}$ -> Punto más profundo del pozo
			Aquí se encuentra subidas de $E_{\text{pot}}$ a ambos lados de la función.
			Presenta la mayor cantidad de **fuerzas atractivas**
			**Determina la distancia de enlace**
		Cuando $r\to 0$, la $E_{\text{pot}}\to \infty$
