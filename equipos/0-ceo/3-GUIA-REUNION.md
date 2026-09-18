# Guía para la reunión de hoy

---

## Cómo deberían ser todas las reuniones de decisión

Explicáselo al equipo al principio: **el orden no es el del menú del simulador.** Las
decisiones están encadenadas y hacerlas en desorden obliga a rehacerlas.

| Orden | Área | Por qué va acá |
|---|---|---|
| **1** | **Analista de Datos** | Estima qué van a hacer los rivales. Define la vara contra la que el simulador nos compara. Sin esto, todos los demás calculan mal |
| **2** | **Marketing** — primero mayorista, después internet | Los precios y la publicidad definen cuánta demanda vamos a tener |
| **3** | **RRHH** y **Mantenimiento** | Fijan la productividad y el techo de cuánto podemos fabricar |
| **4** | **Operaciones** | Recién ahora se sabe cuántos pares hay que producir |
| **5** | **Logística** | Reparte a los almacenes lo que se produjo |
| **6** | **RSE** | Va aparte, no depende de las demás |
| **7** | **Finanzas** | **Siempre última.** Recién ahí se sabe cuánta plata generamos |

**Los pasos 2, 4 y 5 son de ida y vuelta:** cada cambio de precio hace que el simulador
recalcule cuántos pares hacen falta.

### Dos reglas de método

1. **Una variable por vez.** Si se cambian cinco casillas juntas y el resultado empeora, no
   se sabe cuál fue.
2. **Definir antes qué resultado justificaría el cambio.** Si no llega a eso, se vuelve
   atrás sin discutir.

---

## Cómo llevar la de hoy

| Bloque | Qué pasa | Tu rol |
|---|---|---|
| Apertura | Resultado del Año 11 y qué cambió | Hablás vos |
| Ronda de áreas | Cada una presenta | **Escuchás. No opinás todavía** |
| Discusiones | Los tres conflictos de abajo | Moderás |
| Cierre | Ponés tu propuesta sobre la mesa y comparan | Hablás vos |

**Por qué no opinar en la ronda:** si adelantás tu posición, los que hablan después se
acomodan y perdés justo lo que fuiste a buscar.

---

## Qué preguntarle a cada área, y qué decidí yo

### 1. Analista de Datos — Constanza

**Preguntá:** *"¿Contra qué nos va a comparar el simulador este año?"*

**Mi postura:** que la industria baje el precio $1 por la sobreoferta, y que todos suban
el gasto: publicidad +$500, calidad +0,2 estrellas, variedad +20 modelos.

**Por qué:** cuando sobra producto, la pelea se va del precio hacia la diferenciación.

**Ojo:** estimar de más a los rivales es más caro que estimar de menos. Si asumimos que son
muy agresivos, el pronóstico nos empuja a bajar precios que no había que bajar.

---

### 2. Marketing — Maria, Leticia, Gabriel

**Preguntá:** *"Quedamos últimos en pedidos recibidos con el precio por debajo del
promedio. ¿Qué hacemos?"*

**Mi postura:** subir precio a $50 / $56 / $50,50 / $56, subir publicidad $500 en las
cuatro regiones, subir el descuento al cliente de $4 a $5, bajar la entrega de 3 a 2
semanas y subir el apoyo a cada local unos $750.

**Por qué:** a $49 el simulador mostraba déficit en las cuatro regiones — más demanda de
la que podemos fabricar. Y la red de tiendas se cayó 25%, que es lo que explica haber
quedado últimos en pedidos.

**Dónde van a discutir:** van a querer **bajar** el precio por la sobreoferta.
**No les des el argumento.** Pediles que abran la pantalla de distribución y miren el
excedente por región. Van a ver déficit en las cuatro y llegan solos.

---

### 3. RRHH — Rodrigo

**Preguntá:** *"¿Hay algo para mover, o ya está donde tiene que estar?"*

**Mi postura:** bajar el aumento de sueldo en Asia de +5% a +2%. Nada más.

**Por qué:** su área es la mejor gestionada que tenemos. Somos la empresa con mayor
productividad de la industria en Norteamérica, pagando por debajo del promedio.

---

### 4. Mantenimiento y Facility — Diego

**Preguntá:** *"Somos últimos en capacidad y tenemos espacio de planta vacío para 3.000
mil pares. ¿Compramos máquinas?"*

**Mi postura:** **no comprar nada. Cero inversión.**

**Por qué:** medimos que las mejoras de máquina **no rinden nada el año que se compran**.
Instalamos cuatro por $42 millones, no cambió un solo número, y las sacamos. Además ya
sobra producto en la industria.

**Dónde van a discutir:** va a querer comprar, **y puede tener razón.** Su argumento es
fuerte: el espacio ya está construido y pagado, la demanda de Asia crece 10%, y las
máquinas —a diferencia de las mejoras— sí producen el mismo año.

> **Esta es la única decisión mía que no tiene una medición atrás. Es la que más conviene
> que me ganen si el número da.** Pedile cuánto cuesta y dónde queda el ratio de riesgo de
> impago.

---

### 5. Operaciones — Florencia, Daiana, Jesús

**Preguntá:** *"Estamos en 4,0 estrellas contra 4,3 de la industria y 200 modelos contra
231. ¿Cuánto cuesta emparejar?"*

**Mi postura:** subir material superior en Norteamérica de 32% a 40%, subir los modelos de
200 a 250 en las dos plantas, subir la inversión en diseño de $10 mil a $20 mil por modelo,
y llenar las dos plantas al tope. En marca privada, achicar donde rinde poco y ampliar en
Asia: de 454/455/330/331 a **110/110/480/110**.

**Por qué:** la calidad y la variedad son donde perdimos el Año 11. Y los costos fijos de
la planta se reparten entre todo lo que produce: cuantos más pares, más barato sale cada uno.

**Dónde van a discutir:** subir de 200 a 250 modelos encarece la preparación de máquinas
de $4,5 a $6,0 millones por planta. Pueden no querer pagarlo.

---

### 6. Logística — Rocio

**Preguntá:** *"¿Cómo repartimos para que no sobre ni falte en ninguna región?"*

**Mi postura:** sin cambios respecto de lo que está cargado.

**Por qué:** depende de lo que decida Operaciones. Si cambian la producción, esto se
rehace.

**Si menciona que quedan pares sin despachar, prestale atención.** El simulador los
reparte solo, y eso mueve el resultado.

---

### 7. RSE — Pau

**Preguntá:** *"La imagen proyecta 68 y la meta es 72. ¿De dónde salen los 4 puntos?"*

**Mi postura:** prender **eficiencia energética con $500** y el **código de conducta de
proveedores**. Nada más.

**Por qué:** medimos cada iniciativa por separado. La eficiencia energética da **+2 puntos
de imagen por 1 centavo** de ganancia por acción. El código de proveedores, +1 punto por
5 centavos. En cambio las **contribuciones a la caridad cuestan 22 centavos y dan cero
puntos**.

**Dónde van a discutir:** puede querer prender todo. Pedile el número por iniciativa.

---

### 8. Finanzas — Constanza

**Preguntá:** *"Con todo lo demás cargado, ¿qué hacemos con la plata?"*

**Mi postura:** dividendo de **$1,50 por acción** y **recomprar 450 mil acciones propias**
(el máximo permitido). Sin deuda nueva.

**Por qué:** el dividendo mejora la rentabilidad sobre el capital y **no afecta la
calificación crediticia** — lo medimos con $0, $0,50 y $1,00 y el ratio no se movió. Y la
recompra sube la ganancia por acción el mismo año, que es de lo poco que paga en el
ejercicio en curso.

---

## Las tres discusiones que van a aparecer sí o sí

**1. Con sobreoferta, ¿el precio sube o baja?**
Que Operaciones y Logística digan **cuánto se puede producir antes** de que Marketing fije
el precio. El límite físico ordena la discusión solo.

**2. ¿Compramos capacidad?**
Pedí el número concreto: cuántos pares, cuánto cuesta, dónde queda el ratio de crédito.

**3. ¿Alcanza con quedar justo en la meta de imagen?**
Si quedamos clavados en 72, cualquier desvío la pierde. ¿Cuánta ganancia vale un punto de
seguro?

---

## Lo que conviene decir al final

1. **"Corrí una primera pasada para tener una línea de base."** No para cerrar el tema.
2. **"Todavía se puede cambiar: el cierre es hoy a las 23:59."**
3. **"Donde ustedes tengan razón, se carga lo de ustedes."**

Y abrí mostrando **tus dudas, no tus aciertos**: el precio quedó $1,37 arriba de lo que
estimamos de la industria, y no compramos capacidad mientras el líder se expande. Si
arrancás por ahí, la discusión se vuelve genuina.

---

## Un dato que conviene contarles

**Estas dos jugadas son de prueba. Después el juego se reinicia desde cero** y recién ahí
empiezan las seis que cuentan para la nota.

Eso significa que lo que decidamos hoy no afecta la calificación — pero **todo lo que
aprendamos sí**, porque los otros siete equipos arrancan de nuevo igual que nosotros y
nosotros vamos a tener dos rondas de mediciones que ellos capaz no hicieron.
