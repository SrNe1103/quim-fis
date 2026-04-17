$$dG=-SdT+VdP$$
Depende de T y P
$$dP=\left( \frac{\delta P}{\delta T} \right)_{V}dT+\left( \frac{\delta P}{\delta V} \right)_{T}dV$$

$$dG=\left( \frac{\delta G}{\delta T} \right)_{P}dT+\left( \frac{\delta G}{\delta P} \right)_{T}dP$$
$$\left( \frac{\delta G}{\delta T} \right)_{P}=-S$$
$$\left( \frac{\delta G}{\delta P} \right)_{T}=V$$
Ahora con derivadas de 2° orden:
$$\left(\frac{\delta}{\delta P} \left( \frac{\delta G}{\delta T} \right)_{P} \right)_{T}=\left( \frac{\delta}{\delta T}\left( \frac{\delta G}{\delta P} \right)_{T} \right)_{P}$$
	Estas dos expresiones son iguales, están calculando lo mismo en distinto orden
$$\left( \frac{\delta}{\delta P}-\delta S\right)_{T}=-\left(\frac{\delta S}{\delta P} \right)_{T}=\left( \frac{\delta V}{\delta T} \right)_{P}=\left( \frac{\delta}{\delta T}-\delta V \right)_{P}$$
$$-\left(\frac{\delta S}{\delta P} \right)_{T}=\left( \frac{\delta V}{\delta T} \right)_{P}$$
**Relación de Maxwell**
Medir el volumen respecto la temperatura a presión constante es mucho más sencillo que la otra opción (entropía respecto a presión con temperatura constante).
	Válido para sólido, líquido y gas

La energía libre de Gibbs:
	$G(T,P)$ es válido para *sistemas cerrados*
	$G(T,P,n)$ -> Sistemas variables en composición
$$dG=\left( \frac{\delta G}{\delta T} \right)_{P,n}dT+\left( \frac{\delta G}{\delta P} \right)_{T,n}dP+\left( \frac{\delta G}{\delta n} \right)_{T,P}dn$$
Se expande la ecuación con el último término representando la variación de composición.
	También se le conoce como potencial químico
$$\left( \frac{\delta G}{\delta n} \right)_{T,P}=M\text{ (Potencial químico)}$$
	Representa el cambio en la función de Gibbs (G) cuando varía la composición en una cantidad infinitesimal.
Ahora:
$$dG=-SdT+VdP+Mdn$$

---
**Mezcla binaria**
	Componente 1
	Componente 2
	$dG=-SdT+VdP+M_{1}dn+M_{2}dn$
	$\left( \frac{\delta G}{\delta n_{1}} \right)_{T,P,n_{2}}$
	$\left( \frac{\delta G}{\delta n_{2}} \right)_{T,P,n_{1}}$

Generalizando para buscar el caso de mezclas gaseosas
$$\bar{G}=\left( \frac{\delta G}{\delta n_{i}} \right)_{T,P,n_{j}}$$
$$dG=-SdT+VdP$$
Si S constante
$$dG=VdP$$
$$d\bar{G}=\bar{V}dP$$
Con $\bar{V}=\frac{V}{n}=\frac{RT}{P}$
Agregando esto a la ecuación e integrando
$$\int d\bar{G}=RT\ln \frac{P_{2}}{P_{1}}$$
$$M_{2}-M_{1}=RT\ln \frac{P_{2}}{P_{1}}$$
$$M_{2}=M_{1}+RT\ln \frac{P_{2}}{P_{1}}$$
Definiendo condiciones estándar
	$P_{1}=1\text{atm}\approx 1\text{bar}$
	$M_{1}^0=\text{Potencial químico estándar}$
$$M_{2}=M_{1}^0+RT\ln P_{2}$$
Con esto, $M_{2}$ es directamente proporcional a los cambios de presión
	Si $P_{2}$ aumenta, $M_{2}$ aumenta y viceversa
Los sistemas migran termodinámicamente para disminuir el potencial químico. Se encuentran en equilibrio cuando el externo y el interno son iguales.

**Ley de Dalton**
$$P_{A}=P_{T}\cdot X_{A}$$
$$P_{B}=P_{T}\cdot X_{B}$$
Con 
	$X_{A}=\text{Fracción molar de A}$
	$X_{B}=\text{Fracción molar de B}$
	$P_{T}=\text{Presión total}$
	Igual con las presiones
$$P_{T}=P_{A}+P_{B}$$
$$P_{T}=P_{T}\cdot X_{A}+P_{T}\cdot X_{B}$$
Esto en el contexto de Gibbs
$$M_{A}=M_{A}^0+RT\ln P_{A}$$
$$M_{B}=M_{B}^0+RT\ln P_{B}$$
Centrado en A
$$M_{A}=M_{A}^0+RT\ln (P_{T}\cdot X_{A})$$
$$M_{A}=M_{A}^0+RT\ln P_{T}+RT\ln X_{A}$$
Redefiniendo $M_{A}^0+RT\ln P_{T}=M_{A}(T,P_{T})$ 
$$M_{A}=M_{A}(T,P_{T})+RT\ln X_{A}$$
$$M_{B}=M_{B}(T,P_{T})+RT\ln X_{B}$$
Para estos compuestos
	$0<X_{A}<1$
	$0<X_{B}<1$
Si:
$$X_{A}<1 \Rightarrow \ln X_{A}<0$$
$$X_{B}<1 \Rightarrow \ln X_{B}<0$$
Además, si:
$$\ln X_{A}<0 \Rightarrow \downarrow M_{A}$$
$$X_{A}=1 \Rightarrow \ln X_{A}=0$$
Por lo tanto 
$$M_{A}\text{(mezcla)}<M_{A}\text{(puro)}$$
Esto tiene sentido en función de que al agregar un compuesto extra, aumenta la entropía. Esto se refleja en la disminución del potencial químico.
	Ejemplo: Osmosis
		Solvente con membrana semipermeable
		Agua | Agua + sal
	El agua se moverá hacia la solución con sal, disminuyendo el potencial químico del sistema. El movimiento del agua es espontáneo
El potencial químico es parte fundamental de la termodinámica, gobernando el funcionamiento de las reacciones.