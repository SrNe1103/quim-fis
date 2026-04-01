# Ciclo de Carnot
Es un ciclo que muestra los efectos de la $2^a$ ley de la termodinámica
$$dS=\frac{\delta Q_{\text{reversible}}}{T}$$
Integrando ambos lados $$\Delta S=\frac{Q_{\text{rev}}}{T}$$
No alcancé a escuchar la definición, pero creo que es así:
A->B: Compresión isotérmica
B->C: Compresión adiabática
C->D: Expansión isotérmica
D->A: Expansión adiabática
Este ciclo puede funcionar para extraer trabajo, ingresando calor al sistema o como un refrigerador, revirtiendo los flujos de calor y entregando trabajo.
$$W_{\text{exp}}=W_{AD}+W_{DC}$$
$$W_{\text{comp}}=W_{CB}+W_{BA}$$
**Esquema refrigerador de Carnot**
*Fuente caliente (exterior, como la habitación)*
^
| $Q_{AB}$
Sistema <= $W_{\text{ciclo}}$
^
| $Q_{CD}$
*Fuente fría (interior del refrigerador)*

**Coeficiente de desempeño (refrigerador)**
$$COD=\frac{Q_{CD}}{W_{\text{ciclo}}}=\frac{T_{CD}}{T_{AB}-T_{CD}}$$
$$W_{\text{ciclo}}=Q_{AB}-Q_{CD}$$
Ejemplo: $COD=\frac{Q_{CD}}{W_{\text{ciclo}}}=6=\frac{6J}{1J}$
	1 joule de trabajo mueven 6 joule de calor?

## Cálculo de Entropía
**Isotérmico** $\delta Q_{rev}=dQ+PdV$ => $dE=\delta Q_{rev}-PdV$
$$dS=\frac{\cancel{dE}+PdV}{T}$$
$$dS=\frac{PdV}{T}$$
$$dS=\frac{nR\cancel{T}}{V\cancel{T}}dV$$
Integrando: $$\Delta S=nR\ln \frac{V_{2}}{V_{1}}$$

---
### **Isocórico** 
	$dS=\frac{\delta Q_{rev}}{T}=\frac{dE+\cancel{PdV}}{T}$
$$dS=\frac{dE}{T}=\frac{nC_{V}dT}{T}$$
Integrando: $$\int^{S_{2}}_{S_{1}}dS=nC_{V}\int_{T_{1}}^{T_{2}}\frac{dT}{T}$$
$$\Delta S=nC_{V}\ln \frac{T_{2}}{T_{1}}$$
---
### **Isobárico** 
	$dS=\frac{dE+PdV}{T}$
		Recordando: $dH=nC_{P}dT=Q_{P}$
		$dH=\delta Q_{P}=dE+PdV$
$$dS=\frac{dH}{T}$$
$$dS=\frac{nC_{P}dT}{T}$$
Integrando: $$\Delta S=nC_{P}\ln \frac{T_{2}}{T_{1}}$$

---
### **Adiabático**
	$dS=\frac{\cancel{\delta Q_{rev}}}{T}$
	Por definición, un proceso adiabático no tiene intercambio de calor