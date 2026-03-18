## Tabla procesos
Utilizando las ecuaciones
	$\Delta E=Q-W$
	$\Delta H=n\cdot C_{P}\cdot \Delta T$ ?
	$W=\int P_{\text{ext}}dV$
	Isotérmico
		

| Iso        | $\Delta E$       | $\Delta H$       | $Q$                  | $W$                          |
| ---------- | ---------------- | ---------------- | -------------------- | ---------------------------- |
| Térmico    | 0                | 0                | $Q=W$                | $nRT\ln \frac{V_{f}}{V_{i}}$ |
| Bárico     | $nC_{V}\Delta T$ | $nC_{P}\Delta T$ | $\Delta E+P\Delta V$ | $P\Delta V$                  |
| Córico     | $nC_{V}\Delta T$ | $nC_{P}\Delta T$ | $Q=\Delta E$         | 0                            |
| Adiabático | $nC_{V}\Delta T$ | $nC_{P}\Delta T$ | 0                    | $\Delta E=-W$                |

## Isotérmico
$$\left( \frac{\Delta E}{dV} \right)_{T}=0$$
Porque $$\delta E=nC_{v}dT$$ y $dT = 0$
De manera similar, la entalpía vale 0
$$\left( \frac{\Delta H}{dP} \right)_{T}=0$$
$$P_{1}V_{1}=P_{2}V_{2}$$
$$P_{2}=\frac{P_{1}V_{1}}{V_{2}}$$
## Adiabático
$$\frac{T_{2}}{T_{1}}=\left( \frac{V_{2}}{V_{1}} \right)^{1-\gamma}$$
Con $\gamma=\frac{C_{P}}{C_{V}}$
$$P_{1}V_{1}^\gamma=P_{2}V_{2}^\gamma$$
## Demostración clase pasada
[[07_2a-ley]]
$$\Delta H=\Delta E+P\Delta V$$
$$H=E+PV$$
Diferenciando (ec. diferenciales) $$ dH=dE+(PdV+VdP)$$
Considerando Presión constante, $dP\rightarrow 0$
$$dH=dE+PdV$$
$$C_{P}dT=C_{V}+PdV$$
Dividiendo por $dT$
$$C_{P}=C_{V}+P\left( \frac{\delta V}{\delta T} \right)_{P}$$
En un gas ideal, derivando T = 1
$$\left( \frac{\delta V}{\delta T} \right)_{P}=\frac{nRT}{P}=\frac{nR}{P}$$
$$C_{P}=C_{V}+P\cdot \frac{nR}{P}$$
$$C_{P}=C_{V}+nR$$
$$C_{P}-C_{V}=nR$$
Esto es aplicable a cualquier sistema
# Termoquímica
Medir el calor que desprende o absorbe una reacción química.
$dH=C_{P}dT$
$dE=C_{V}dT$

En un gráfico Energía/Coordenada de Reacción se grafica la energía entre Reactantes y Productos.
Se puede observar el $\Delta H_{\text{reacción}}$ que nos muestra si la reacción es endotérmica o exotérmica.
	$\Delta H$ Es una ecuación de estado, por lo tanto nos interesa los estados inicial y final.

Definir:
- Cambios de entalpía estándar: Condiciones de 1 bar y 298 K
	$\Delta H^0$
- Entalpía estándar de formación: 
	$\Delta H^0_{f}$

Ejemplo:
$$H_{2}O_{(l)}\Rightarrow \Delta H^0_{f}=-285.8 \left[ \frac{kJ}{mol} \right]$$
El $H_{2(g)}$ y el $O_{2(g)}$ se encuentran como gases di-atómicos en condiciones estándar. Por esto, se considera este estado con entalpía de formación 0.
$$H_{2(g)}\Rightarrow \Delta H^0_{f}=0$$
$$O_{2(g)}\Rightarrow \Delta H^0_{f}=0$$
Todo lo que se forme desde el estado basal se cuantifica:
$$H_{2(g)}+\frac{1}{2}O_{2(g)}\rightarrow H_{2}O_{(l)}$$

---
Otro ejemplo:
$$NaCl_{(s)}\Rightarrow \Delta H^0_{f}=-46.1 \left[ \frac{kJ}{mol} \right]$$
Para $Na_{(s)}$ y $Cl_{2(g)}$:
$$Na_{(s)}\Rightarrow \Delta H^0_{f}=0$$
$$Cl_{2(g)}\Rightarrow \Delta H^0_{f}=0$$
---
$$CH_{4(g)}\Rightarrow \Delta H^0_{f}=-74.81 \left[ \frac{kJ}{mol} \right]$$
Igualmente, C y H tienen Hf 0.

---
$$Fe_{3}O_{4(s)}+4H_{2(g)}\rightarrow 3Fe_{(s)}+4H_{2}O_{(l)}$$
Para esta reacción, 
$$\Delta H^0_{\text{Reacción}} = \sum V\cdot\Delta H^0_{f\text{ Productos}}-\sum V\cdot\Delta H^0_{f\text{ Reactantes}}$$
Donde $V=$ Cantidad de mol estequimétrica.
Entonces:
$$\Delta H^0_{f}=[4\cdot \Delta H^0_{fH_{2}O(l)}+3\cdot \Delta H^0_{fFe(s)}]-[1\cdot \Delta H^0_{fFe_{3}O_{4}(l)}+3\cdot \Delta H^0_{fH_{2}(g)}]$$
$$\Delta H^0_{fFe(s)}=0$$
$$\Delta H^0_{fH_{2}(s)}=0$$
$$\Delta H^0_{f}=4\cdot \Delta H^0_{fH_{2}O(l)}-\Delta H^0_{fFe_{3}O_{4}(l)}$$
Para el agua
$$H_{2(g)}+\frac{1}{2}O_{2(g)}\rightarrow H_{2}O_{(l)}$$
$$\Delta H^0_{\text{Reacción}}=[1\cdot \Delta H^0_{fH_{2}O}]-[0]$$
Porque reactantes son el estado estándar de los elementos
$$H_{2}O_{(l)}\Rightarrow \Delta H^0_{\text{Reacción}}= \Delta H^0_{f}=-285.8 \left[ \frac{kJ}{mol} \right]$$
# Ley de Hess
Se tiene un intermediario A, uno B y uno C entre los Reactantes y Productos una reacción, con $\Delta H_{1-4}$. La suma de todas las energías intermedias es igual a la energía de reacción entre reactantes y productos.
$$\Delta H_{Reacción}=\Delta H_{1}+\Delta H_{2}+\Delta H_{3}+\Delta H_{4}$$
Ejemplo_
$$CH_{2}=C_{H}-CH_{3(g)} + \frac{9}{2}O_{2(g)} \rightarrow 3CO_{2}+3H_{2}O$$
Cómo se calcula la Entalpía de reacción? Se pueden plantear 3 reacciones intermedias con $\Delta H^0_{R}$ conocidos.