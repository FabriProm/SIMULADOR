# Mecánicas medidas — lo que dejaron las dos rondas de prueba

> Las jugadas de prueba (Año 11 el 13/09 y Año 12 el 17/09) se descartaron con el reinicio,
> pero **el simulador es el mismo**. Todo lo marcado como **MEDIDO** salió del panel de
> proyección en vivo de BSG. Lo marcado como **MANUAL** viene de la guía del simulador y
> no se verificó.
>
> Este archivo reemplaza a `BSG-conocimiento.md`, `BSG-Ano12-registro-completo.md` y
> `prompt-Ano12.md` (siguen en el historial de git si hace falta algún detalle).

---

## 1. Cómo se califica

Cinco indicadores, **20% cada uno**. Cada uno se puntúa mitad contra la meta del inversor
y mitad contra la mejor empresa de la industria.

| Meta del inversor | A11 | A12 | A13 | A14 | A15 | A16 |
|---|---|---|---|---|---|---|
| Ganancia por acción (EPS) | $2,50 | $3,00 | $3,50 | $4,00 | $4,50 | $5,25 |
| Rentabilidad sobre el capital (ROE) | 21% | 22% | 23% | 24% | 25% | 26% |
| Precio de la acción | $40 | $50 | $65 | $80 | $100 | $125 |
| Calificación crediticia | B+ | B+ | B+ | A− | A− | A− |
| Calificación de imagen | 70 | 72 | 72 | 75 | 75 | 77 |

Las seis jugadas oficiales son los Años 11 a 16.

**Punto de bonificación por puntería (FIR 3b):** compara lo proyectado con lo real en
ingresos (±5%), EPS (±5% o ±10¢) e imagen (±4 puntos). En la prueba lo perdimos porque el
EPS real quedó 12,3% abajo del proyectado.

---

## 2. Método de carga

### El orden no es el del menú

```
0  Supuestos competitivos (al pie de las pantallas 5 y 6)   → Analista de Datos
6  Mayorista  →  5  Internet                               → Marketing
1  Remuneración  →  3  Instalaciones                       → RRHH, Mant. y Facility
2  Marca propia  →  7  Marca privada  →  4  Distribución   → Operaciones, Logística
8  Famosos  →  9  Ciudadanía                               → Marketing, RSE
10 Finanzas, siempre última                                → Finanzas
```

Se vuelve a 2, 7 y 4 cada vez que cambia la demanda. **MEDIDO:** al subir precios el
requerimiento de producción bajó de 8.800 a 8.000 mil pares; cargar producción primero
habría fabricado 800 mil pares que nadie compraba.

### Las reglas

1. **Calibrar los supuestos competitivos antes de decidir nada.** Es lo que más mueve el
   pronóstico (ver 3.1).
2. **Recorrer las diez pantallas al abrir y anotar el estado real.** En la prueba había
   cinco valores distintos a los del plan escrito tres días antes.
3. **Una variable por vez.** Cuando se cargaron diez cosas juntas, el EPS cayó de $2,43 a
   $2,00 y hubo que separar las causas a mano.
4. **Definir antes qué resultado justifica el cambio, y revertir si no llega.**
5. **Medir cada iniciativa por separado.** Medidas juntas se diluyen y parece que ninguna
   sirve.

---

## 3. Mecánicas verificadas

### 3.1 Los supuestos competitivos mueven el pronóstico más que casi cualquier decisión

Las 10 casillas al pie de las pantallas 5 y 6 no deciden nada nuestro: deciden **contra qué
nos compara el simulador**.

| Mismo set de decisiones, Año 11 de prueba | EPS proyectado | EPS real | Error |
|---|---|---|---|
| Supuestos blandos (los que se cargaron) | $2,83 | $2,48 | −12,3% |
| **Supuestos moderados** | **$2,46** | $2,48 | **+0,8%** |
| Supuestos agresivos | $2,00 | $2,48 | +24,0% |

En el Año 12 de prueba, calibrar los supuestos sin tocar ninguna decisión bajó el EPS
proyectado de $3,00 a $2,52.

**El riesgo es asimétrico:** con supuestos demasiado pesimistas el panel te empuja a bajar
precios. Con capacidad limitada eso es autolesión. **El error caro es sobrestimar a los
rivales.**

### 3.2 La capacidad es un techo de dos pisos

- 4.000 mil pares en horario regular por planta, más 20% de horas extra: **4.800 por
  planta y 9.600 entre las dos**.
- El techo lo pone la **maquinaria**. Subir la productividad no sube la capacidad: solo
  reduce cuántos trabajadores hacen falta.
- Marca propia y marca privada compiten por la misma capacidad.
- Hay espacio construido sin equipar: **1.000 en Norteamérica y 2.000 en Asia**.
- **MANUAL:** el equipo nuevo cuesta ~$5,0 M por cada 250 mil pares (reacondicionado
  ~$3,6 M) y produce el mismo año. La obra civil nueva recién está disponible al año
  siguiente.

### 3.3 El costo fijo se reparte entre todo lo que produce la planta

La preparación de producción, el mantenimiento y la amortización se reparten entre
**todos** los pares de la planta, de marca propia y privada juntos.

| Pares de marca privada en la planta N.A. (MEDIDO, A11) | 200 | 400 | 745 | 909 |
|---|---|---|---|---|
| Costo de producción por par | $30,03 | $27,05 | $25,51 | $24,98 |
| Margen sobre costos directos | −$0,03 | $2,95 | $4,49 | $5,02 |

**Regla: las dos plantas siempre llenas.** Bajar marca privada sin subir marca propia
(plantas al 92%) costó **−$0,38 de EPS y la calificación de A a A−**.

### 3.4 Pero con la mezcla correcta

La marca propia rindió más que la privada en las cuatro regiones (A12 de prueba):

| $ por par | N.A. | E-A | A-P | L-A |
|---|---|---|---|---|
| Marca propia, mayorista | $8,08 | $5,61 | $11,06 | $6,57 |
| Marca privada | $3,92 | $2,35 | $7,98 | $3,47 |

Correr capacidad de privada a propia, con las plantas llenas, valió **+$0,30 de EPS**. La
marca privada es el relleno que mantiene la planta llena, no el objetivo.

**Tope:** ninguna empresa puede pasar del 25% del mercado de marca privada de una región.

### 3.5 El precio correcto es el que vacía la planta

- **Precio mayorista: +$0,21 de EPS por cada dólar** (A12). Es la palanca más fuerte del
  juego.
- Precio internet: +$0,02 a +$0,03 de EPS por dólar.
- **Lo primero que se mira en la pantalla 6 es el excedente o déficit**, no la cuota. A
  $49 había déficit en las cuatro regiones: demanda que no podíamos abastecer y un dólar
  por par regalado.
- Con 12,7% de sobreoferta en la industria, $10 M de marketing extra movieron 1,6 puntos
  de cuota y **$0,00 de EPS**. Con sobreoferta conviene defender margen.

### 3.6 No perdimos cuota por precio

En el Año 11 de prueba quedamos **últimos en pedidos recibidos** (1.822 contra 2.118 de
promedio) con el precio **por debajo** del promedio. Perdimos en todo lo demás:

| Factor (N.A. mayorista) | Nosotros | Industria | Diferencia |
|---|---|---|---|
| Precio | $49,00 | $49,63 | −1,3% |
| **Calidad S/Q** | **4,0** | **4,3** | **−7,0%** |
| **Modelos** | **200** | **231** | **−13,4%** |
| Rebaja por correo | $4,00 | $4,80 | −16,7% |
| Apoyo al minorista | $4.000 | $4.281 | −6,6% |
| Publicidad | $10.000 | $10.563 | −5,3% |

### 3.7 Los puntos de venta se caen sin que nadie mire

Los locales dispuestos a llevar nuestra marca bajaron de 1.000/1.000/700/700 a
**880/833/610/630**, un 23-28% debajo del promedio. Responden **con un año de retraso** a
la calidad, la cuota, el apoyo al minorista y el plazo de entrega. No se arreglan sobre la
fecha.

### 3.8 Calidad: cuánto cuesta cada estrella

| Cambio (A12, MEDIDO) | Efecto |
|---|---|
| Material superior N.A. 32% → 40%, con 250 modelos, estilo $20 mil y TQM $1,30 | S/Q 4,0 → 4,4 |
| Estilo por modelo $10 mil → $20 mil | **+3 de imagen, −$0,17 de EPS** (óptimo; $16k, $18k, $22k y $28k rinden peor) |
| Material superior Asia 40% → 54% | +1 de imagen, −$0,08 de EPS |
| Modelos 200 → 250 | Preparación de $4,5 M a $6,0 M por planta |
| Más material superior | Sube un poco el rechazo (N.A. 6,9% → 7,3%) |

### 3.9 El rechazo es un problema de maquinaria, no de motivación

- **MEDIDO:** incentivo por par a $0,75 bajó el rechazo 0,3 puntos; a $0,25 lo subió 0,6.
- La **Opción A** (−50% de rechazo, $10 M) en Asia bajó el rechazo de 10,1% a 5,0% al año
  siguiente.

### 3.10 Las mejoras de equipo rinden cero el año en que se compran

**MEDIDO:** se instalaron cuatro mejoras por $42 M y no cambió **ni un número** del panel.
La Opción B, que promete −50% de preparación, dejó la preparación en $6.000. **El
capital sale ahora y el beneficio arranca al año siguiente.** El prepago de deuda se
comporta igual: prepagar $12 M al 8,2% dio cero efecto en el año.

- El límite es **una vez por opción y por planta** (no "dos por vida útil").
- Ahorro anual que muestra hoy la pantalla 3 del Año 11 oficial:

| Opción | Planta | Capital | Ahorro anual | Relación |
|---|---|---|---|---|
| A — rechazo −50% | **Asia** | $10.000 | $3.547 | **35,5%** |
| C — +1 estrella S/Q | **Asia** | $19.200 | $5.855 | **30,5%** |
| B — preparación −50% | N.A. | $6.400 | $1.860 | 29,1% |
| B — preparación −50% | Asia | $6.400 | $1.860 | 29,1% |
| A — rechazo −50% | N.A. | $10.000 | $2.529 | 25,3% |
| C — +1 estrella S/Q | N.A. | $19.200 | $3.119 | 16,2% |
| D — productividad +50% | N.A. | $57.600 | $7.173 | 12,5% |
| D — productividad +50% | Asia | $57.600 | $1.385 | 2,4% |

El ahorro de cada opción se recalcula según el estado de la planta: se lee en la pantalla,
no se copia de acá.

### 3.11 Remuneración: la palanca es chica

| Prueba (MEDIDO) | Resultado |
|---|---|
| Formación $400, $1.200 y $2.000 | Iguales o peores que **$600** |
| Supervisión 40:1 → 50:1 | $0,00 de ganancia, más riesgo de calidad |
| Salario base Asia +5% → +2% | +$0,01 de EPS |

### 3.12 Imagen: se compra barata o no se compra

La imagen **promedia los últimos tres años**. Lo que se prende tarde entra a un tercio de su
efecto, y lo que se prende en la ronda 4 casi no puntúa.

| Iniciativa (A12, medida por separado) | EPS | Imagen |
|---|---|---|
| **Eficiencia energética $500** | −$0,01 | **+2** |
| **Código de conducta de proveedores** | −$0,05 | **+1** |
| Empaque reciclado | −$0,05 | 0 |
| Contribuciones benéficas $3 M | −$0,22 | 0 |
| Comedor y guardería | se paga sola | +100 pares por trabajador |
| Seguridad, iluminación y ventilación | se paga sola | +100 pares por trabajador |

Las dos de condiciones laborales se midieron juntas en el Año 11 de prueba: el ahorro de
mano de obra **superó el costo** (EPS de $2,80 a $2,83) y la imagen subió de 67 a 71.
Formación ética quedó prendida como "el punto más barato", pero nunca se midió sola.

**MANUAL:** desde el Año 14 hay un premio a la empresa que más destina a RSE como porcentaje
de sus ingresos.

### 3.13 Famosos: la única siembra que no cuesta en el año

- Firmar **cuesta cero el año de la firma**; el índice y los pagos arrancan al año
  siguiente.
- Solo una oferta admite prioridad 1 (la segunda vuelve a cero sola).
- El índice satura en **300 por región**.
- En la prueba, con el tablero en cero, ofertamos a ciegas: Billy Eyelash $3.500 (la
  segunda oferta fue $2.799) y Taylor Sluggish $1.200 (la segunda $1.000). **Unos $900 mil
  de sobrepago.** En esta industria el despeje estuvo entre $500 y $3.500.
- Con los dos, el índice fue 170/170/135/130 contra 61/62/64/61 de promedio.

### 3.14 Finanzas

- **El dividendo no afecta la calificación crediticia.** MEDIDO: ratio de impago 4,77 con
  $0, $0,50 y $1,00 por acción. Sube el ROE porque achica el capital: de $1,00 a $1,50 el
  ROE pasó de 22,8% a 23,2%.
- **La recompra de acciones rinde en el año:** 450 mil acciones por $15,5 M dieron +$0,07
  de EPS y +0,6 de ROE. En el Año 11 el máximo es **200 mil**.
- **El presupuesto de capital se mide contra el panel, no contra una cuenta previa.** Se
  temía que $10 M de inversión bajaran el ratio de 4,07 a 3,44; con los aumentos de precio
  quedó en 4,50 con calificación A.

### 3.15 Distribución

- Despachar más no crea demanda: mandar los 893 mil pares de inventario en planta bajó el
  EPS de $3,08 a $3,00 y la imagen de 72 a 70. **El inventario en planta es activo, no
  gasto.**
- Los pares que no se asignan se despachan solos, en proporción a los envíos cargados.
  Revisar "pares pendientes de envío".
- Aranceles: **$6 por par en Europa-África y $10 en Latinoamérica**. Flete: $0,97 dentro de
  la región y $1,94 cruzando.
- **MANUAL:** el inventario del año anterior entra al almacén con 0,3 estrellas menos.

### 3.16 Materiales

El precio de los materiales depende de la utilización de la industria: sube cuando pasa del
110% (A12: $6,42 y $12,12) y baja por debajo del 95%.

---

## 4. Trampas del simulador

| Trampa | Qué hacer |
|---|---|
| **Navegar entre pantallas descarta lo no guardado** | Guardar antes de salir de cada pantalla. El botón guarda las diez juntas y reemplaza lo anterior |
| **Las casillas "incorporar en proyecciones" de marca privada vuelven solas a "No"** cuando un envío pasa por cero. Con A-P en "No" el panel leía $2,23 en vez de $2,91 | Revisar las cuatro después de **cada** cambio en la pantalla 7 |
| **La producción de marca se autolimita** a 4.800 menos la marca privada | Bajar primero marca privada, guardar, y recién ahí subir marca propia |
| **Algunos campos no disparan el recálculo** aunque muestren el valor nuevo | Si un cambio no mueve ningún número, reescribir y salir con tabulador, o guardar y recargar |
| **La casilla "incorporar" queda forzada en "No" en toda región con 0 pares de marca privada** (A11 oficial: se puso Sí, se guardó, se recargó y volvió a No) | Normal: sin pares no hay nada que incorporar. Revisar solo las regiones con pares |
| **Los selectores de prioridad de famosos se insertan al cargar una oferta mayor que 0** y corren los campos siguientes | Verificar cada oferta y prioridad por nombre después de cargarlas |
| En la pantalla 10, la línea "Iniciativas de eficiencia energética" suma **todo** el capital de RSE (energía + comedor + seguridad) | La pantalla 3 lo desglosa bien |
| La rebaja por correo solo admite dólares enteros | — |
| El apoyo al minorista va de 250 en 250 | — |
| La publicidad de marca va de 500 en 500 y los modelos de 50 en 50 | — |
| En los supuestos: calidad sin 4,3 ni 4,5 (salta de a 0,2), modelos de 20 en 20, precios de a $1 y rebaja sin $4,80 | Redondear y anotar hacia qué lado |

---

## 5. Umbrales

| Umbral | Valor | Si se cruza |
|---|---|---|
| Ratio de riesgo de impago | **4,00** | Por debajo se pierde la A− (arranca en **4,07**) |
| Internet sobre mayorista | **40%** | Por debajo, los minoristas dejan de pedir el año siguiente |
| Calidad de marca privada | 3,0 estrellas | Requisito de la licitación |
| Precio de marca privada | ≥ $10 debajo del mayorista promedio | Requisito |
| Modelos de marca privada | 100 | Requisito |
| Cuota de marca privada | 25% por región | Tope |
| Índice de famosos | 300 por región | No suma más |
| Patrimonio | $100 M | Mínimo obligatorio |

---

## 6. Lo que ya se jugó desde este mismo arranque

La prueba del Año 11 partió del **mismo estado** que el juego oficial: las ocho empresas
iguales y un EPS proyectado sin tocar nada de **$2,28**.

### El set que se cargó en la prueba

| Pantalla | Decisión |
|---|---|
| 1 | Salario +1% N.A. y +5% Asia · incentivo $1,00 / $0,50 · formación $600 en las dos |
| 2 | Material superior 32% / 54% · 200 modelos · estilo $10 mil · TQM $1,00 / $0,90 |
| 3 | **Opción A en Asia ($10 M)**, nada más |
| 5 | Internet $69 / $77 / $69 / $77 · buscadores 6.500 / 4.500 / 4.000 / 3.500 · sin envío gratis |
| 6 | Mayorista $49 / $55 / $49 / $55 · publicidad 10.000 / 9.000 / 8.000 / 6.500 · **rebaja bajada a $4** · 3 semanas · apoyo 4.000 / 4.000 / 2.750 / 2.750 |
| 7 | Marca privada 1.442 mil netos a $31 / $37 / $31 / $37 · plantas llenas |
| 8 | Billy Eyelash $3.500 (prioridad 1) y Taylor Sluggish $1.200, dos años |
| 9 | Comedor, seguridad y formación ética ($12,7 M) |
| 10 | Dividendo $1,00 · sin deuda |

### Cómo salió

| | Proyectado | Real | Meta |
|---|---|---|---|
| EPS | $2,83 | **$2,48** | $2,50 |
| ROE | 24,8% | **22,1%** | 21,0% |
| Crédito | A | **A−** | B+ |
| Imagen | 71 | **70** | 70 |
| Precio de la acción | — | **$34,44** | $40,00 |

**3° de 8 con 82 puntos.** F 108 · C 92 · H 82 · G 75 · A 74 · E 70 · D 68 · B 66.

- **Salió bien:** ganamos las cuatro licitaciones de marca privada (la facturación más alta
  de la industria, $49 M) y las dos celebridades.
- **Salió mal:** el EPS real quedó 12,3% abajo por supuestos mal calibrados; calidad y
  modelos bajo el promedio; últimos en pedidos recibidos; la peor tasa de rechazo en las dos
  plantas.

### Cómo jugaron los rivales

Son los mismos compañeros y también aprendieron en las pruebas, así que es probable que
repitan o profundicen:

- **F (1°):** precio bajo ($48), calidad baja (3,7), **347 modelos**, capacidad de 11.000
  y planta nueva en Latinoamérica. EPS $4,70, imagen 84.
- **C (2°):** premium. $55, 5,2 estrellas, 249 modelos.
- **D y C** también ampliaron capacidad (9.500 y 9.000). Para el Año 12 la industria quedó
  con **12,7% de sobreoferta**, y nosotros empatados últimos en capacidad con 8.000.
