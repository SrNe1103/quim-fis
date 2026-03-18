# Procesos Termodinámicos
- Isotérmicos
- Isobáricos
- Isocóricos
- Adiabáticos
**Procesos adiabáticos**
Un proceso es adiabático cuando $\delta Q=0$ => $\Delta E=-W$
	En una expansión adiabática la temperatura del gas disminuye.
	Es un sistema aislado

**Procesos isotérmicos**
$T_{1}=T_{2}$
$$P=\frac{nRT}{V}\rightarrow T=\frac{P_{1}V_{1}}{nR}=\frac{P_{2}V_{2}}{nR} \rightarrow \frac{P_{1}}{V_{1}}=\frac{P_{2}}{V_{2}}$$
$$P_{2}=\frac{P_{1}V_{2}}{V_{1}}$$
**Proceso isobárico**
$P_{1}=P_{2}$
$$\frac{nRT_{1}}{V_{1}}=\frac{nRT_{2}}{V_{2}}\rightarrow \frac{T_{1}}{V_{1}}=\frac{T_{2}}{V_{2}}$$
$$T_{2}=\frac{T_{1}V_{2}}{V_{1}}$$
**Proceso isocórico**
$V_{1}=V_{2}$
$$\frac{T_{1}}{P_{1}}=\frac{T_{2}}{P_{2}}$$
$$P_{2}=\frac{P_{1}T_{2}}{T_{1}}$$
---
En un gráfico P/V, el área bajo la curva es el W.
	Además, 
	$V_{f}>V_{i}$ implica expansión
	$V_{i}>V_{f}$ implica compresión
Un régimen isobárico es una recta horizontal, un rég. isocórico es una recta vertical y en un rég. isotérmico es una asíntota (ej. de func $\frac{x+1}{x-1}$)
	Cada asíntota representa una temperatura definida.

**Gas ideal adiabático**
	No entra ni sale calor
$$dE=\delta W$$
$$nC_{v}\cdot dT=P\cdot dV$$
Por ser reversible, se usa ecuación de los gases ideales
$$nC_{v}\cdot dT=\frac{nRT}{V}\cdot dV$$
$$nC_{V}\cdot \frac{dT}{T} = nR\cdot\frac{dV}{V}$$
Integrando y cancelando n  $$C_{V}\ln \frac{T_{f}}{T_{i}}=-R\ln \frac{V_{f}}{V_{i}}$$
$$\ln \frac{T_{f}}{T_{i}}=-\frac{R}{C_{V}}\ln \frac{V_{f}}{V_{i}}$$
Aplicando $\exp$ $$\frac{T_{f}}{T_{i}}=\left( \frac{V_{f}}{V_{i}} \right) ^{\frac{-R}{C_{V}}}$$
Para simplificar esta ecuación,
En un gas ideal: $$C_{P}-C_{V}=R$$
Dividiendo por $C_{V}$ $$1-\frac{C_{P}}{C_{V}}=-\frac{R}{C_{V}}$$
Ahora, $\frac{C_{P}}{C_{V}}$ es la constante adiabática ($\gamma$).
	Dado que $C_{P}>C_{V}\Rightarrow \gamma>1$

$$\frac{T_{f}}{T_{i}}=\left( \frac{V_{f}}{V_{i}} \right) ^{1-\gamma}$$
Si se combina con $V=\frac{nRT}{P}$: $$P_{i}V_{i}^\gamma=P_{f}V_{f}^\gamma$$
	Ec isotérmica: $P_{i}V_{i}=P_{f}V_{f}$

Entonces, en un régimen isotérmico: $$P\cdot V=\text{Cte.}$$
$$P=\frac{\text{Cte.}}{V}$$
Ahora, en uno adiabático: $$P\cdot V^\gamma=\text{Cte.}$$
$$P=\frac{\text{Cte.}}{V^\gamma}$$
Considerando que $\gamma>1$, el régimen adiabático disminuye su presión mucho más rápido con un aumento de volumen
$$\Delta E=nC_{V}\cdot \Delta T$$
$$\Delta H=nC_{P}\cdot \Delta T$$
En un gas ideal, $C_{V}$ y $C_{P}$ son constantes. Estas dos ecuaciones se pueden usar en cualquier régimen de cte. (temperatura, presión, volumen, adiabático).

---
Próxima clase, demostrar $$C_{P}-C_{V}=R$$