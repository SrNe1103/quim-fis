Líquidos son una solución = solvente + soluto
En un gráfico del Potencial químico de A vs fracción molar de A vs Potencial químico de B se observan dos líneas que se cruzan
	Eje Y1 -> $P_{A}$
	Eje Y2 -> $P_{B}$
	Eje X  -> $X_{A}$ y $X_{B}$
A medida que el solvente A se acerca a 1, se aplica la ley de Raoult. A medida que el soluto se acerca a 0 se aplica la ley de Henry??
	*me perdí un poco acá*

---
## Volúmenes molares parciales
Volumen total de una mezcla no es igual al volumen de los dos compuestos puros. Esto producto de las interacciones intermoleculares.
$$\bar{X}=\left( \frac{\delta X}{\delta n_{i}} \right)_{T,P,n_{j}}$$
$\bar{X}$ es una propiedad molar
	$\bar{X}=\frac{X}{n}$
El potencial químico también es una propiedad molar
$$M_{i}=\left( \frac{\delta G}{\delta n_{i}} \right)_{T,P,n_{j}}$$
El Volumen molar
$$\bar{V}_{A}=\left( \frac{\delta V}{\delta n_{A}} \right)_{T,P,n_{B}}$$
	Esto quiere decir que cuando se agrega un volumen infinitesimal de A, cambia el volumen del sistema.
Así mismo:
$$\bar{V}_{B}=\left( \frac{\delta V}{\delta n_{B}} \right)_{T,P,n_{A}}$$
Si tenemos una propiedad de estado $Z(x,y)$
	$dZ=\left( \frac{\delta Z}{\delta X} \right)_{Y}dX+\left( \frac{\delta Z}{\delta Y} \right)_{X}dY$
Ahora $$dV=\left( \frac{\delta V}{\delta n_{A}} \right)_{T,P,n_{B}}dn_{A}+\left( \frac{\delta V}{\delta n_{B}} \right)_{T,P,n_{A}}dn_{B}$$
$$dV=\bar{V}_{A}\cdot dn_{A}+\bar{V}_{B}\cdot dn_{B}$$
$$V=\bar{V}_{A}\cdot n_{A}+\bar{V}_{B}\cdot n_{B}$$
Con V una propiedad extensiva. Si diferenciamos
$$dV=\bar{V}_{A}\cdot dn_{A}+n_{A}\cdot d \bar{V}_{A}+\bar{V}_{B}\cdot dn_{B}+n_{B}\cdot d \bar{V}_{B}$$
$$dV=\cancel{\bar{V}_{A}\cdot dn_{A}}+\cancel{\bar{V}_{B}\cdot dn_{B}}=\cancel{\bar{V}_{A}\cdot dn_{A}}+n_{A}\cdot d \bar{V}_{A}+\cancel{\bar{V}_{B}\cdot dn_{B}}+n_{B}\cdot d \bar{V}_{B}=dV$$
**Relación de Gibbs-Duhem**
$$n_{A}\cdot d \bar{V}_{A}+n_{B}\cdot d \bar{V}_{B}=0$$
$$n_{A}\cdot d \bar{V}_{A}=-n_{B}\cdot d \bar{V}_{B}$$
	Esta aplica para cualquier propiedad molar
$$n_{A}\cdot d \bar{X}_{A}+n_{B}\cdot d \bar{X}_{B}=0$$
$$n_{A}\cdot d M_{A}+n_{B}\cdot d M_{B}=0$$![[IMG_20260422_103558009.jpg|430]]
### Método intercepto tangente
![[IMG_20260422_104113357.jpg|431]]
Esta tangente (en rojo) es una la derivada de la curva en ese punto ($X_{\text{etanol}}=0.4$)
$V=\bar{V}_{A}\cdot n_{A}+\bar{V}_{E}\cdot n_{E}$  ahora, dividiendo por $n_{T}$
$\frac{V}{n_{T}}=\bar{V}_{A}\cdot \frac{n_{A}}{n_{T}}+\bar{V}_{E}\cdot \frac{n_{E}}{n_{T}}$
$V_{molar}=\bar{V}_{A}\cdot X_{A}+\bar{V}_{E}\cdot X_{E}$
$V_{molar}=\bar{V}_{A}\cdot (1-X_{E})+\bar{V}_{E}\cdot X_{E}$
$\left( \frac{\delta V}{\delta X_{E}} \right)_{T,P}=-\bar{V}_{A}+\bar{V}_{E}$
