## Método de la pendiente
![[IMG_20260427_095915893.jpg|326]]
![[IMG_20260427_100100684.jpg|307]]
![[IMG_20260427_100414513.jpg|313]]
$$\bar{V}_{A}=28,4-0,4\cdot(30)=16,4\left[ \frac{cm^3}{mol} \right]$$
$$\bar{V}_{E}=28,4+(1-0,4)\cdot(30)=46,4\left[ \frac{cm^3}{mol} \right]$$
El volumen molar puro de agua está reportado $\bar{V}_{A}^*=18\left[ \frac{cm^3}{mol} \right]$ y el  del etanol $\bar{V}_{E}^*=58,4\left[ \frac{cm^3}{mol} \right]$
	Así, a la disolución definida anteriormente, al agregar 1 mol de agua cambia $16,4\left[ \frac{cm^3}{mol} \right]$ y su respectiva cantidad con etanol

Un volumen molar está dado por
$$V=n_{A}\cdot \bar{V}_{A}+n_{B}\cdot \bar{V}_{B}\space /\cdot \frac{1}{nT}$$
$$V_{m}=X_{A}\cdot \bar{V}_{A}+X_{B}\cdot \bar{V}_{B}$$
## Sistema real
![[IMG_20260427_102156229.jpg|177]]
Volvamos a la ley de Raoult
	$P_{A}=X_{A}\cdot P_{A}^*$
	$P_{A}=\text{Presión parcial de A}$
	$X_{A}=\text{Fracción molar}$
	$P_{A}^*=\text{Presión pura de A}$
Para el potencial químico
	$M_{A}=M_{A}^*+RT\ln X_{A}$
	[[17_dG#^8746e7]]

En el equilibrio el potencial químico del líquido = vapor

A temperatura constante
$$dG=\cancel{-SdT}+VdP$$
$$dG=VdP$$
$$d\bar{G}=\bar{V}dP$$
$\bar{G}=\frac{G}{n}=M$
$\bar{V}=\frac{V}{n}=\frac{RT}{P}$
$$dM=\frac{RT}{P}dP$$
$$\int dM=RT\int \frac{dP}{P}$$
$$M_{2}-M_{1}=RT\ln \frac{P_{2}}{P_{1}^0}$$
$P_{1}^0=1[atm]$
$$M_{2}=M_{1}+RT\ln P_{2}$$

Ejemplo:
Acetona/Cloroformo
![[IMG_20260427_103619506.jpg|213]]
Ideal y real presentan diferencia considerable
	Ya no es suficiente $M_{i}=M_{i}^{0}ref+RT\ln X_{i}\text{ (solución diluída)}$
Ahora, para modelar este efecto se considera y define la **Actividad**
$$a_{i}=\gamma_{i}X_{i}$$
	$a_{i}=\text{actividad}$
	$\gamma_{i}=\text{coeficiente de actividad}$
	$X_{i}=\text{fracción molar}$

Esto quiere decir que al agregar compuesto, no todo ese componente va a tener actividad termodinámica. 
Ahora, la ecuación se transforma en:
$$M_{i}=M_{i}^{ref}+RT\ln a_{i}$$
$$M_{i}=M_{i}^{ref}+RT\ln (\gamma_{i}\cdot X_{i})$$
$$M_{i}=M_{i}^{ref}+RT\ln X_{i}+RT\ln\gamma_{i}$$
El coeficiente de actividad es una corrección al sistema ideal y representa una desviación positiva o negativa
	$\gamma_{i}>1\text{ Desviación positiva}$
	$\gamma_{i}<1\text{ Desviación negativa}$

Próxima clase veremos la solución electrolítica, donde la actividad se vuelve más relevante.
