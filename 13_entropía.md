# Cálculos de la función de estado Entropía
De manera natural la entropía tiende a aumentar. Si la diferencia de entropía es = 0, el proceso se considera reversible.
Un proceso es reversible si se utiliza la misma energía para ir de inicio -> fin que para ir de fin -> inicio.
## Sistema isotérmico
Antes explicaron el $\Delta S$ reversible, obteniendo que $\Delta S_{sistema}=-\Delta S_{medio}$ y que $\Delta S_{sistema}=nR\ln \frac{V_{2}}{V_{1}}$

Natural = irreversible
$$\Delta S_{universo}=\Delta S_{sistema}+\Delta S_{medio}$$
Un proceso reversible se da cuando $P_{ext}=P_{int}$
$$\Delta S=\Delta S_{f}-\Delta S_{i}$$
La entropía para un sistema irreversible y reversible pueden calcularse igual si las entropías iniciales y finales son iguales
$$dS_{reversible}=dS_{irreversible}$$
$$dS_{sistema(irrev)}=nR\ln \frac{V_{2}}{V_{1}}$$
Ahora, el medio. Si isotérmico irreversible ($P_{externa}$)
$$dS_{medio}=\frac{\delta Q}{T}=dE+P_{externa}dV$$
$$dS_{medio}=P_{ext}dV$$
Con presión externa constante e integrando
$$\Delta S_{medio}=P_{ext}\cdot\Delta V$$
$$\Delta S_{universo}=nR\ln \frac{V_{2}}{V_{1}}+P_{externa}\cdot \Delta V$$
Si ocurre una expansión:
$$\Delta S_{universo}>0$$
# $3^a$ Ley de la Termodinámica
1. Ley -> Cómo se transforma la energía
2. Hay un sentido en las reacciones
3. Se basa en el $0K$ (cero absoluto).

"Un sistema alcanza una temperatura de 0 K cuando su entropía molar es 0" $$S=0$$
La entropía tiene que ver con el número de configuraciones posibles para un sistema.
Ejemplo sala (lo dio el profe):
	Si sale la mitad de alumnos del curso, los que se quedan ocupan ciertas sillas. Luego se cambian, sin poder usar las mismas sillas, eventualmente llegamos a un número de configuraciones posibles. Si entra el resto del curso, habrán menos configuraciones posibles.

A mayor número de configuraciones hay mayor entropía en el sistema.
	Si la mitad del curso ocupa las sillas de la derecha, sólo pueden llegar a esa configuración de una forma. Mientras que las configuraciones posibles aleatorias son muchas más.

---
**Boltzmann** -> Mecánica estadística
$$S=k\ln \Omega $$
Con $\Omega=\text{N° de configuraciones/estados}$.
Definición microscópica. El profe quería hacer la relación micro -> macro
	No hay un sistema con entropía = 0
$\Omega$ nos dice que la entropía es sumativa
	$S_{total}=S_{\text{sistema 1}}+S_{\text{sistema 2}}$

---
La entropía se puede observar en los cambios de fases.
## Cambios de fase
A presión constante 
$$\delta Q_{P}=dH=nC_{P}dT=dE+P_{ext}dP$$
$$dS=\frac{\delta Q_{reversible}}{T}=\frac{dE+P_{ext}dV}{T}$$
$$dS=\frac{nC_{P}}{T}dT$$
$$\Delta S=nC_{P}\ln \frac{T_{2}}{T_{1}}$$
Ahora, la entropía molar ($S$):
$$S(T)=S(0K)+\int_{Ti}^{Tf}C_{\text{P (sólido)}}\ln \frac{T_{f}}{T_{i}}+\frac{\Delta H_{fusión}}{T_{fusión}}+\int_{Ti'}^{Tf'}C_{\text{P (líqui)}}\ln \frac{T_{f}'}{T_{i}'}+\frac{\Delta H_{evapo}}{T_{evapo}}+\int_{Ti''}^{Tf''}C_{\text{P (líquido)}}\ln \frac{T_{f}''}{T_{i}''}$$
$S(0K)=\text{Entropía residual}$
$\int_{Ti}^{Tf}C_{P}\ln \frac{T_{f}}{T_{i}}=\text{Estados Sólido, Líquido o Gaseoso}$
$\frac{\Delta H}{T}=\text{Cambios de estado}$

## Desigualdad de Clausius
"Herramienta matemática con impacto conceptual"
$$dS_{irrev}=dS_{rev}$$
Siempre que $S_{\text{ini irrev}}=S_{\text{ini rev}}$ y $S_{\text{fin irrev}}=S_{\text{fin rev}}$
Además $dE_{irrev}=dE_{rev}$
$$\delta Q+P_{ext}dV=\delta Q_{rev}-P_{int}dV$$
$$\delta Q_{rev}-\delta Q=PdV-P_{ext}dV$$
Con $PdV$ reversible y $P_{ext}dV$ irreversible
En caso de:
- Expansión 
	$P_{\text{interna}}>P_{\text{externa}}$ Para poder empujar el pistón
- Compresión
	$P_{\text{externa}}>P_{\text{interna}}$ El pistón cede a la presión

$$\delta Q_{rev}-\delta Q=(P-P_{ext})dV$$
En una expansión: $(P-P_{ext})dV=+\cdot+>0$
En una compresión: $(P-P_{ext})dV=-\cdot->0$

Entonces 
$$\delta Q_{rev}-\delta Q>0$$
$$\delta Q_{rev}>\delta Q$$
$$\frac{\delta Q_{rev}}{T}>\frac{\delta Q}{T}$$
**Desigualdad de Clausius:**
$$dS>\frac{\delta Q}{T}$$
A partir de esta desigualdad llegaremos a la función de Energía libre de gibbs y Helmholtz