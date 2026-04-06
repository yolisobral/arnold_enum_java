Enum Types: Arnold
===================================

Con este proyecto introducimos un nuevo concepto de programación, los **tipos enumerados**, un ejemplo del **patrón singleton**

El **patron singleton** garantiza que una clase tenga una única instancia y proporciona un punto de acceso global a ella. Se implementa haciendo el constructor privado, creando un atributo estático para la instancia y un método estático (getInstance()) que controla la creación

Trata de calcular el peso de una persona en los distintos planetas del Sistema Solar, siguiendo esta fórmula:

$$ Peso \ en \ Superficie = tu \ Masa \times Gravedad \ en \ superficie $$

donde:

$$ Gravedad \ en \ superficie = G \times \frac {Masa \ del \ planeta} {Radio \ del \ planeta \ al \ cuadrado} $$

donde: 

$$ G = 6.67300 \ · e^{-11} \frac {m^3}{kg \ ·s }$$

y 

$$ tu \ masa = \frac{tu \ peso \ en \ la \ Tierra} {gravedad \ superficial \ Tierra} $$

Los valores de masa y radio de cada planeta (en $Kg$ y $m$ respectivamente) son:

```java
MERCURY (3.303e+23, 2.4397e6),     
VENUS   (4.869e+24, 6.0518e6),     
EARTH   (5.976e+24, 6.37814e6),     
MARS    (6.421e+23, 3.3972e6),     
JUPITER (1.9e+27,   7.1492e7),     
SATURN  (5.688e+26, 6.0268e7),     
URANUS  (8.686e+25, 2.5559e7),     
NEPTUNE (1.024e+26, 2.4746e7);      
```
