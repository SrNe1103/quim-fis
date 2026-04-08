# Desigualdad de Clausius
Recordando [[13_entropía#Desigualdad de Clausius]]
$$dE_{irrev}=dE_{rev}$$
$$\delta Q+P_{ext}dV=\delta Q_{rev}-P_{int}dV$$
$$\delta Q_{rev}-\delta Q=(P-P_{ext})dV$$
En una expansión: $(P-P_{ext})dV=+\cdot+>0$
En una compresión: $(P-P_{ext})dV=-\cdot->0$
Entonces: 
$$\delta Q_{rev}>\delta Q$$
$$\frac{\delta Q_{rev}}{T}>\frac{\delta Q}{T}$$
$$dS>\frac{\delta Q}{T}$$

---
$$\Delta S_{\text{universo}}=\Delta S_{\text{sistema}}+\Delta S_{\text{medio}}$$
Si el proceso es reversible e isotérmico:
$$\Delta S_{\text{sistema}}=-\Delta S_{\text{medio}}$$
$$\Delta S_{\text{sistema}}=nR\ln \frac{V_{f}}{V_{i}}$$
Para proceso irreversible
$$\Delta S_{\text{sistema}}\neq-\Delta S_{\text{medio}}$$
Sin embargo, si los estados iniciales y finales reversibles e irreversibles son iguales, se pueden calcular de la misma forma

## Función de Helmholtz
Por la $1^a$ Ley:
$$dE_{rev}=\delta Q_{rev}-PdV$$
$$dE=TdS-PdV$$
$$dE_{irrev}=\delta Q-P_{ext}dV$$
$$\delta Q=dE+P_{ext}dV$$
Jugando con la desigualdad $TdS>\delta Q$ se llega a:
$$dE-TdS<-P_{ext}\cancel {dV}$$
A volumen constante, de la cual
$$dE-TdS=dA<0$$
Con $dA$ la función de Helmholtz.

Si $dS$ es grande, $dA<0$. 
	El aumento en la entropía es la dirección natural.
	Si el $dA$ es negativo, el proceso es **espontáneo**
	Si $dA$ es positivo, el cambio no es espontáneo, por lo que es necesario **agregar energía** al sistema.
	Si $dA = 0$, el sistema se encuentra en **equilibrio**

A presión constante:
$$TdS>dE+P_{ext}dV$$
$$TdS>dH$$
$$-dH+TdS>0$$
$$dH-TdS<0$$
Son dos funciones de estados, lo que combinadas genera otra función de estado:
$$dG<0$$
**Energía libre de Gibbs**
Se comporta igual que la función de Helmholtz respecto a la espontaneidad.
- La función de Gibbs se utiliza a Presión constante
- La función de Helmholtz a Volumen constante

---
1a ley: $dE=TdS-Pdv$ => $E(S,V)$
Entalpía: $dH=dE+PdV$
	$H=E+PV$ $/d$
	$dH=dE+PdV+VdP$
	$dH=TdS-PdV+PdV+VdP$
	$dH=TdS+VdP$ => $H(S,P)$
S, V y P son **variables naturales** (por definición)
	Las variables de las que depende la función son los diferenciales de la ecuación

---
Asumiendo entalpía y entropía constantes. Correcta en ciertos contextos
$$\Delta G=\Delta H-T\Delta S$$
---

Ahora, para las funciones $dA$ y $dG$:
Helmholtz
	En equilibro $dA=0$
	$A=E-TS$ $/d$
	$dA=dE-TdS-SdT$
	$dA=TdS-PdV-TdS-SdT$
	$dA=-PdV-SdT$ => $A(V,T)$
Gibbs
	$G=H-TS$ $/d$
	$dG=dH-TdS-SdT$
	$dG=dE+PdV+VdP-TdS-SdT$
	$dG=TdS-PdV+PdV+VdP-TdS-SdT$
	$dG=VdP-SdT$ => $G(P,T)$

Para estas funciones, los equilibrios se cumplen de manera distinta
	En $dA$ con $V$ y $T$ constantes
	En $dG$ con $P$ y $T$ constantes

*En general se usa más la Función de Gibbs porque es más común en la naturaleza*

---
Trabajo 100% matemático:
Con una función $Z(x,y)$
$$dZ(x,y)=\left( \frac{\delta Z}{\delta x} \right)_{Y}+\left( \frac{\delta Z}{\delta y} \right)_{x}$$
$\left( \frac{\delta Z}{\delta x} \right)_{Y}$ es un vector
Ahora, para la entalpía:
$$dH=\left( \frac{\delta H}{\delta S} \right)_{P}+\left( \frac{\delta H}{\delta P} \right)_{S}$$
$$dH=(TdS+VdP)\delta S+(TdS+VdP)\delta P$$
	$dH=T+V$? => Próxima clase
