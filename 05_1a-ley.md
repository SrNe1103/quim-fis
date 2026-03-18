# Primera ley de la termodinámica
"La energía no se destruye, se transforma"
	Trabajaremos en sistemas cerrados
		n => cte.

## Modelo cilindro pistón
- Cilindro con paredes rígidas
- Pistón sería una pared móvil (dibujo en la parte superior)
- Sistema cerrado
- Gas ideal dentro 
	$P = \frac{nRT}{V}$

Flujo de Calor => Q
Flujo de Trabajo => W

Este sistema busca mostrar la transformación de calor en trabajo y viceversa.
	Entregar **Q** al sistema se transforma en **W**
Una vez entra el calor al sistema, deja de tener un sentido físico como tal.
	Dentro, se traduce en un cambio de la **Energía interna**

$E$ => Energía interna ( **J** Joule) ($N \cdot m$)
	$E_{\text{potencial}}$
	$E_{\text{rotacional}}$
	$E_{\text{vibracional}}$
	$E_{\text{traslacional}}$
$$ \Delta E = E_{\text{f}} - E_{\text{i}} $$
El estado inicial tiene ciertos valores para las variables termodinámicas. Al ingresar energía por medio de calor o trabajo, esto se reflejará en las variables, obteniendo un estado final.
	El estado general del sistema se ve reflejado en la Energía total, que cambia o se mantiene entre estados.
**Q** y **W** son funciones de tránsito.
	No hay un $\Delta Q$
**$\Delta E$** es una función de estado

En el sistema cilindro pistón, Q <-> W y la energía remanente en el sistema se transforma en Energía interna. 

**Primera ley de la termodinámica** $$ \Delta E = Q - W$$
Si el sistema absorbe calor, $Q>0$
Si el sistema desprende calor, $Q<0$
$\Delta E>0$ si $E_{f}>E_{i}$
$\Delta E<0$ si $E_{i}>E_{f}$

--- 
## Trabajo
En un gráfico de Fuerza vs Distancia, W es el área bajo la curva
$$ W=\int_{x_{1}}^{x_{2}} F(x) dx $$
$$ W=\int F dx \frac{dA}{dA} $$
$dA$ = Cambio en área
$$ W=\int \frac{F}{dA} dx dA $$
$dxdA$ ($m\cdot m²$) = $dV$ ($m³$)

En un gráfico de Presión vs Volumen, W es el área bajo la curva
$$ W=\int PdV$$
$P$ = Presión externa

---
## Capacidad calorífica
$$ C_{x\to_{0}} = \frac{Q}{\Delta T} = \frac{\delta Q}{dT} $$
C => Capacidad calorífica
Q => Calor
$\Delta T$ => Cambio de temperatura

$\delta$ => diferencial en funciones de tránsito/camino
	$\delta Q$ o $\delta W$
$d$ => diferencial para funciones de estado
	$dE$, $dT$, $dP$ o $dV$

$$ \int_{inicio}^{final} dE = \Delta E $$
$$ \int_{ini}^{fin} \delta Q = Q_{i\to_f} $$
$$ \int_{ini}^{fin} \delta W = W_{i\to_f} $$

---
**En nuestro sistema cilindro pistón**
	A V cte. => $dV = 0$ => $W=0$
	$\delta Q=dE$
	$C_{V}$ => Capacidad calorífica a volumen constante
	sub V
$$ C_{V} = \frac{\delta Q_{V}}{dT_{V}} = \frac{dE}{dT} $$
$$ dE = C_{V} \cdot dT $$
Integrando, $$ \Delta E = C_{V} \cdot \Delta T $$
$C_{V}$ => $\frac{J}{K}$
$$ \Delta E = n \cdot c_{V} \cdot \Delta T $$
$c_{V}$ => $\frac{J}{K mol}$

---
Próxima clase
$C_{P}$: presión constante
$$ \delta Q_{P} = n\cdot C_{P}\cdot dT = \delta H$$
$\delta H$ = Entalpía
