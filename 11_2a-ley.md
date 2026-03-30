# $2^a$ Ley de la Termodinámica
*Falté al inicio, por lo que no está todo anotado. Mostraron este concepto con un ejemplo de ciclo de Carnot*
No se puede transformar todo el calor en trabajo

$$Eficiencia=\frac{W_{\text{ciclo}}}{Q_{\text{A}\rightarrow \text{B}}}$$

Dado que $$|Q_{A-B}|>|W_{\text{ciclo}}|$$
La eficiencia siempre es menor que 1. 
	Esta energía se pierde como **Entropía**.

Para que la Eficiencia fuera 1:
$$Eficiencia=\frac{W_{\text{ciclo}}}{Q_{\text{A}\rightarrow \text{B}}}=\frac{Q_{\text{A}\rightarrow \text{B}}-Q_{\text{C}\rightarrow \text{D}}}{Q_{\text{A}\rightarrow \text{B}}}=1-\frac{Q_{\text{C}\rightarrow \text{D}}}{Q_{\text{A}\rightarrow \text{B}}};\text{ Con: }Q_{\text{C}\rightarrow \text{D}}\rightarrow 0, Q_{\text{A}\rightarrow \text{B}}\rightarrow \infty$$

Utilizando las fórmulas en [[08_termoquímica#Tabla procesos]] muestran el cálculo de la eficiencia de un ciclo de Carnot.
	El profe quedó de subir este desarrollo para llegar al resultado
	$$E = 1-\frac{T_{C}}{T_{D}}=\frac{T_{D}-T_{C}}{T_{D}}$$
Esto muestra que la eficiencia siempre es < 1. $T_{D}\neq \infty$
$$E=\frac{Q_{\text{A}\rightarrow \text{B}}-Q_{\text{C}\rightarrow \text{D}}}{Q_{\text{A}\rightarrow \text{B}}}=\frac{T_{\text{A}\rightarrow \text{B}}-T_{\text{C}\rightarrow \text{D}}}{T_{\text{A}\rightarrow \text{B}}}$$
$$T_{A-B}\cdot Q_{C-D}=T_{C-D}\cdot Q_{A-B}$$
$$\frac{Q_{A-B}}{T_{A-B}}-\frac{Q_{C-D}}{T_{C-D}}=0$$
Esta ecuación se muestra como $\text{Estado 2}-\text{Estado 1}=0$, lo que la transforma en una **función de estado** de la cual sale el concepto de **Entropía** $\Delta S$
$$\sum \frac{Q}{T}\rightarrow_{reversible} \int \frac{\delta Q}{T}=dS$$
Con $T: \text{Temperatura absoluta}$