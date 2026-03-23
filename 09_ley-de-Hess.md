# Ley de Hess
[[08_termoquímica#Ley de Hess]]
$$\Delta H_{Reacción}=\Delta H_{1}+\Delta H_{2}+\Delta H_{3}+\Delta H_{4}$$
Esto se extiende a los n $\Delta H_{\text{Reacción}}$ intermedios

Ejemplo:
$$C_{3}H_{6}+\frac{9}{2}O_{2(g)}\rightarrow_{3}CO_{2(g)}+3H_{2}O_{(l)}$$
$$C_{3}H_{6}+H_{2(g)}\rightarrow C_{3}H_{8}; \Delta H^0_{1}=-124\left[ \frac{KJ}{mol} \right]$$
$$C_{3}H_{8}+5O_{2}\rightarrow 3CO_{2}+4H_{2}O;\Delta H^0_{2}=-2220\left[ \frac{KJ}{mol} \right]$$
$$H_{2}O\rightarrow H_{2}+\frac{1}{2}O_{2};\Delta H^0_{3}=286\left[ \frac{KJ}{mol} \right]$$
Tenemos 2 $\Delta H$ negativos y el último es positivo. Estos datos están tabulados y deberían darse en ejercicios de prueba. *Invirtiendo el sentido de la reacción se invierte el sentido de la entalpía.*
$$H_{2}+\frac{1}{2}O_{2}\rightarrow H_{2}O;\Delta H^0=-286\left[ \frac{KJ}{mol} \right]$$

Ahora, con las ecuaciones 1-3 se "anula hacia abajo"

$$C_{3}H_{6}+\cancel{H_{2(g)}}\rightarrow \cancel{C_{3}H_{8}}; \Delta H^0_{1}=-124\left[ \frac{KJ}{mol} \right]$$
$$\cancel{C_{3}H_{8}}+\cancel{5} \frac{9}{2} O_{2}\rightarrow 3CO_{2}+\cancel{4}3H_{2}O;\Delta H^0_{2}=-2220\left[ \frac{KJ}{mol} \right]$$
$$\cancel{H_{2}O}\rightarrow \cancel{H_{2}}+\cancel{\frac{1}{2}O_{2}};\Delta H^0_{3}=286\left[ \frac{KJ}{mol} \right]$$
Esto debería dejar la reacción inicial. Se hace para comprobar que estemos considerando las entalpías de formación correctas:
$$C_{3}H_{6}+\frac{9}{2}O_{2(g)}\rightarrow_{3}CO_{2(g)}+3H_{2}O_{(l)}$$
Por lo tanto el $\Delta H$ de reacción sería
$$\Delta H^0_{\text{reacción}}=-124-2220+286=-2058\left[ \frac{KJ}{mol} \right]$$

---
Otro ejemplo:

$$Fe_{3}O_{4}+2H_{2}\rightarrow_{3}Fe+4H_{2}O$$
Necesitamos los siguientes $\Delta H$
- $\Delta H^0_{f}H_{2}=0$
- $\Delta H^0_{f}Fe_{3}O_{4}$
- $\Delta H^0_{f}Fe=0$
- $\Delta H^0_{f}H_{2}O$
	2 de estos valen 0 por ser el estado estándar
De esta forma:
$$\Delta H^0_{R}=4\Delta H^0_{f}H_{2}O-\Delta H^0_{f}Fe_{3}O_{4}$$
**Productos - Reactantes**

---
## Cambios de fase
Los cambios de fase se pueden estimar con la ley de Hess.
Si el $\Delta T=0$, se encuentra en un cambio de fase donde puede almacenar una gran cantidad de energía. Su capacidad calorífica $C\rightarrow \infty$

Por ejemplo $H_{2}O_{(l)}\rightarrow H_{2}O_{(g)}$
	Esta reacción tiene un $\Delta H^0_{\text{Cambio de Fase}}$
Esto debería estar tabulado$$H_{2}O_{(l)}\rightarrow H_{2}+\frac{1}{2}O_{2};\Delta H^0_{1}=286\left[ \frac{KJ}{mol} \right]$$
De la misma forma, debería existir la forma gaseosa:
$$H_{2}+\frac{1}{2}O_{2}\rightarrow H_{2}O_{(g)};\Delta H^0_{1}=-242\left[ \frac{KJ}{mol} \right]$$
Hacemos lo mismo de antes y cancelamos en las dos ecuaciones, obteniendo la reacción que deseamos: $$H_{2}O_{(l)}\rightarrow H_{2}O_{(g)};\Delta H^0_{1}=44\left[ \frac{KJ}{mol} \right]$$
Así obtenemos la energía necesaria para convertir $H_{2}O$ líquida en gaseosa.
	*Los $\Delta H$ utilizados no son de formación, son de reacción*

Los cambio de fases están involucrados en la $3^a$ ley de la termodinámica.

---
## Ley de Kirchhoff
¿Qué pasa con el $\Delta H^0_{\text{Reacicón}}$ ante cambios en temperatura ($\Delta T$)?
$$\Delta H^0_{R}=H^0_{\text{productos}}-H^0_{\text{reactantes}}$$
$$\Delta H_{R}=H_{\text{productos}}-H_{\text{reactantes}}$$
Esto quiere decir que habría que buscar las entalpías a la temperatura indicada. No es muy práctico, por lo que, usando ecuaciones diferenciales:
$$\delta \Delta H_{R}=dH_{P}-\delta H_{R}$$
Según visto antes: $\delta H=C_{P}\cdot dT$
$$\delta \Delta H_{R}=C_{P(\text{productos})}\cdot dT-C_{P(\text{reactantes})}\cdot dT$$
$$\delta \Delta H_{R}=(C_{P(\text{productos})}-C_{P(\text{reactantes})})\cdot dT$$
Integrando entre estado 1 y 2 $\int_{1}^2$:
$$\Delta H_{R_{2}}-\Delta H_{R_{1}}=\Delta C_{P}\cdot(T_{1}-T_{2})$$
Reordenando:
$$\Delta H_{R_{2}}=\Delta H_{R_{1}}+\Delta C_{P}\Delta T$$
Podemos asumir que $\Delta H_{R_{1}}=\Delta H_{R}^0$
	Podemos tomar el estado inicial como el estado estándar ($1bar;298K$)
Así, quedaría:
$$\Delta H_{R_{2}}=\Delta H_{R}^0+\Delta C_{P}\cdot(T_{1}-298)$$
Esta ecuación se le conoce como la **ley de Kirchhoff**

De esta forma se puede extender la Ley de Hess a cualquier temperatura

---
### Líquidos
La capacidad calorífica se puede expresar con una expansión de Taylor (Ecuación de Virial)
$$C_{P}=a+bT+cT^2+\dots+nT^{n}$$
En gases se asume $C_{P}=a$
En líquidos: $C_{P}=a+bT+cT^2$
En sólidos: $C_{P}=a+bT+cT^2+dT^3$

---
## Entalpías de enlace

En una reacción tipo:
$$AB_{(g)}\rightarrow A_{(g)}+B_{(g)}$$
Por ejemplo:
$$H_{2(g)}+Cl_{2(g)}\rightarrow 2HCl_{(g)}; \Delta H_{R}^0$$
$$\Delta H^0_{R}=\sum \Delta H_{\text{Enlaces rotos}}-\sum \Delta H_{\text{Enlaces formados}}$$
**Próxima clase**
