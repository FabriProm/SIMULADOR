# BSG — Base de conocimiento · Company H · Industria 5

> Mecánicas verificadas del simulador, correcciones a supuestos que resultaron falsos, y
> el set de decisiones del Año 11 con sus resultados.
>
> **Todo lo marcado como MEDIDO proviene del panel de proyección en vivo de BSG**,
> registrado durante la carga del 13 de septiembre de 2026 (jugada de prueba 1).
> Lo que no está marcado como medido es del manual o de los reportes del Año 10.
>
> **⚠️ ACTUALIZADO TRAS EL AÑO 12.** Varias entradas de este archivo fueron corregidas por
> mediciones posteriores. El registro completo del Año 12 está en
> `BSG-Ano12-registro-completo.md` y tiene precedencia sobre este documento cuando
> se contradigan.

---

## 1. Estado del juego

| | |
|---|---|
| Empresa | Company H · Industria 5 · 8 empresas (A–H) |
| Punto de partida | Año 10, las 8 empresas idénticas |
| Plantas | Norteamérica y Asia-Pacífico. Sin planta en Europa-África ni Latinoamérica |
| Última ronda jugada | Año 11 (prueba 1, no cuenta para la nota) |
| Próxima ronda | Año 12 — **ya cuenta para la nota** |

### Resultado del Año 11

| Indicador | Año 10 | Al abrir A11 | Final A11 | Meta | |
|---|---|---|---|---|---|
| EPS | $2,00 | $2,11 | **$2,83** | $2,50 | ✅ |
| ROE | — | 18,2% | **24,8%** | 21,0% | ✅ |
| Crédito | B | A− | **A** | B+ | ✅ |
| Imagen | 70 | 65 | **71** | 70 | ✅ |
| Precio acción | $30 | — | — | $40 | se conoce con los resultados |

| Concepto ($000s) | Año 10 | Al abrir | Final |
|---|---|---|---|
| Ingresos netos | 432.600 | 446.075 | 468.944 |
| Beneficio neto | 40.000 | 42.155 | 56.535 |
| Caja al cierre | 6.074 | 52.166 | 19.501 |

La caja baja porque se usó: $10,0 M en mejora de maquinaria, $12,7 M en ciudadanía
empresarial y $20,0 M en dividendos. Las tres salidas se decidieron **después** de medir
que la calificación crediticia las aguantaba.

---

## 2. Supuestos que la medición desmintió

Esta sección es la más importante del archivo. Son errores reales que costaron o
casi costaron plata.

### 2.1 La marca privada NO se recorta: se llena

**Lo que suponía:** salir de Europa y Latinoamérica, donde el margen por par era
$0,95 y $0,75, y concentrar en Asia.

**MEDIDO:** al vaciar tres regiones, el costo por par en Norteamérica subió de
$27,05 a $30,03 y el margen se dio vuelta a **negativo**. Sin tocar precio ni
materiales ni salarios.

**Por qué:** los costos fijos de la planta (preparación de producción $4,5 M con
200 modelos, mantenimiento, amortización) se reparten entre **todos** los pares que
la planta fabrica, de marca propia y privada juntos. Los pares que "no valían la pena"
sostenían el costo de todos los demás.

| Pares de marca privada en la planta N.A. | 200 | 400 | 745 | 909 |
|---|---|---|---|---|
| Costo de producción por par | $30,03 | $27,05 | $25,51 | $24,98 |
| Margen sobre costos directos | −$0,03 | $2,95 | $4,49 | $5,02 |

**Regla:** llenar las dos plantas al tope de 4.800 pares brutos cada una. La marca
privada de 800 → 1.442 mil pares netos llevó el margen del canal de $2,0 M a ~$5,7 M
**y además** bajó el costo de la marca propia de $24,07 a $23,55 (N.A.) y de $21,29 a
$21,03 (Asia).

### 2.2 El dividendo NO afecta la calificación crediticia

**Lo que suponía:** el ratio de riesgo de impago es flujo operativo ÷ amortizaciones,
y los dividendos consumen ese flujo. Pagar $1,00 por acción hundiría el ratio y
costaría la calificación.

**MEDIDO:** ratio **4,77 con $0, con $0,50 y con $1,00 por acción**. Idéntico.

Esa inferencia venía de una coincidencia aritmética del Año 10 (utilidad + amortización
− dividendos daba exactamente el flujo reportado). Era casualidad.

**Regla:** el dividendo mejora el ROE (achica el capital promedio) sin costo crediticio.
Se carga al final, después de leer el ratio. En el A11 llevó el ROE de 23,7% a 24,8%.

### 2.3 La inversión de capital sí entraba

**Lo que suponía:** los $10 M de la Mejora A hundirían el ratio de 4,07 a 3,44 y
costarían la A−.

**MEDIDO:** ratio **4,50** con calificación **A**.

**Por qué:** el cálculo partía de un flujo operativo que ya no era el nuestro. Las
mejoras de precio habían agrandado tanto la generación de caja que la inversión
entraba holgada. **El presupuesto de capital se mide contra el panel, no contra una
cuenta hecha antes.**

### 2.4 El rechazo de Asia es maquinaria, no motivación

**Lo que suponía:** el rechazo de 10,1% responde al incentivo por par, que en Asia
era la mitad que en Norteamérica.

**MEDIDO:** incentivo a $0,75 → rechazo 9,8% (−0,3). Incentivo a $0,25 → rechazo
10,4% (+0,6). **Medio dólar por par mueve la tasa apenas 0,6 puntos.**

**Consecuencia:** se revirtió el incentivo a $0,50 y se justificó la Mejora A de
maquinaria ($10 M, rechazo −50%, repago 2,8 años), que ataca la causa real.

### 2.5 La RSE no es gasto puro

**MEDIDO:** comedor y guardería + seguridad e iluminación dan **+100 pares por
trabajador cada una**. Aplicadas a las dos plantas, el ahorro de mano de obra
**superó el costo**: EPS de $2,80 a $2,83 e imagen de 67 a 71.

**CORREGIDO EN EL AÑO 12.** Esta medición estaba diluida: se probaron las dos juntas y
la imagen promedia tres años, así que el efecto del primer año entra a un tercio. Medidas
por separado en el A12:

| Iniciativa | Costo en EPS | Puntos de imagen |
|---|---|---|
| **Eficiencia energética $500** | −$0,01 | **+2** ← nunca se había probado |
| **Código de proveedores** | −$0,05 | **+1** |
| Empaque reciclado | −$0,05 | 0 |
| Contribuciones benéficas $3 M | −$0,22 | 0 |

### 2.6 El estado de las pantallas cambia entre sesiones

**MEDIDO al abrir:** cinco diferencias contra el análisis escrito tres días antes.

| Qué | Según el plan | En la pantalla |
|---|---|---|
| EPS proyectado | $2,28 | **$2,11** (brecha $7,8 M, no $4,3 M) |
| Requerimiento de producción | 8.700 mil pares | **8.800 mil** |
| Envío gratis internet N.A. | Apagado | **Encendido** |
| Salario base Asia | +1% | **+5%** |
| Buscadores N.A. | $5.000 mil | **$6.500 mil** |

**Regla:** todo análisis escrito de antemano describe un estado que ya cambió.
El primer paso de cada carga es recorrer las diez pantallas y anotar el estado real.

---

## 3. Mecánicas verificadas

### 3.1 El panel de proyección es un instrumento de medición

Arriba a la izquierda de cada pantalla: **Proyectado A11 Rendimiento**, con los cinco
indicadores y tres medidas más. Se recalcula con cada casilla que cambia.

No hace falta estimar nada. Se carga, se lee, se sabe. **El simulador premia al que
mide más, no al que predice mejor.**

### 3.2 Los supuestos competitivos mueven el pronóstico sin tocar una decisión

Las 10 casillas al pie de las pantallas 5 y 6 son tu estimación de lo que hará el
promedio de la industria. No deciden nada tuyo — deciden **contra qué te compara**.

**MEDIDO:** con supuestos agresivos (rivales a $47, publicidad +8%, calidad 4,2) la
participación proyectada cayó de 12,5% a 10,0% y el EPS a $2,00. Con supuestos
moderados, **el mismo set de decisiones** daba $2,46.

**El riesgo asimétrico:** supuestos pesimistas te dicen que perdés participación y te
empujan a bajar precios. En una industria limitada por capacidad, eso es autolesión.
**El error caro no es subestimar a los rivales — es sobrestimarlos.**

### 3.3 La capacidad es un techo duro de dos pisos

- 4.000 mil pares en horario regular por planta + 20% de horas extra = **4.800 por planta**
- **9.600 entre las dos**
- El techo lo pone la **maquinaria instalada, no la gente**

Subir la productividad de los trabajadores **no sube la capacidad**: solo reduce
cuántos trabajadores necesitás para alcanzarla. Marca propia y marca privada compiten
por esa misma capacidad.

### 3.4 El costo fijo se reparte entre todo lo que produce la planta

Ver 2.1. Es la mecánica más contraintuitiva y la que más plata mueve.

### 3.5 Hay dos relojes corriendo

| Decisión | Cuándo rinde |
|---|---|
| Mejoras de maquinaria | Año siguiente al pago |
| Celebridades | Año siguiente a la firma — **y ahí arrancan los pagos** |
| Imagen | Promedio de los últimos 3 años |
| RSE productiva (comedor, seguridad) | Inmediato (+100 pares/trabajador) |

**Asimetría aprovechable:** firmar celebridades cuesta **cero** en el año de la firma.
Es la única siembra de largo plazo que no compite con la brecha del año en curso.

### 3.6 Orden de carga

El menú las numera 1–10, pero ese no es el orden correcto:

```
SUPUESTOS →  0  Proyecciones competitivas (al pie de 5 y 6)
DEMANDA   →  6  Mayorista  →  5  Internet      (la 6 primero: la 5 hereda de ella)
CAPACIDAD →  1  Remuneración  →  3  Instalaciones
VOLUMEN   →  2  Marca propia  →  7  Marca privada  →  4  Distribución
SIEMBRA   →  8  Celebridades  →  9  Ciudadanía
CIERRE    → 10  Finanzas
```

**Orden: 6 → 5 → 1 → 3 → 2 → 7 → 4 → 8 → 9 → 10**, volviendo a 2, 7 y 4 cada vez que
cambia la demanda.

**MEDIDO:** al abrir, el simulador pedía 8.800 mil pares. Después de subir precios pedía
8.000. Cargar producción primero habría fabricado 800 mil pares que nadie compraba.

---

## 4. Comportamientos del simulador que hay que vigilar

| Comportamiento | Detalle |
|---|---|
| **Las casillas se resetean** | Poner un envío de marca privada en cero devuelve las cuatro casillas de *Incorporar los resultados previstos* a **No**, sin aviso. Saca $27,6 M de ingresos del pronóstico. Revisarlas cada vez que se toca la pantalla 7. |
| **Los campos no siempre disparan el recálculo** | El valor queda escrito pero la proyección no lo toma. Pasó con el precio mayorista de Latinoamérica. Se arregla reescribiendo y saliendo con tabulador. **Si un cambio no mueve ningún número, sospechar de esto antes que de la economía.** |
| **Solo una celebridad admite prioridad 1** | El campo de prioridad de la segunda oferta vuelve a cero solo. |

---

## 5. Umbrales duros

| Umbral | Valor | Consecuencia de cruzarlo |
|---|---|---|
| Ratio de riesgo de impago | **4,00** | Por debajo se pierde la A− |
| Diferencia internet sobre mayorista | **40%** | Por debajo, los detallistas dejan de pedir mercadería el año siguiente. Se marca en rojo |
| Calidad mínima marca privada | 3,0 estrellas | Requisito de la licitación |
| Precio marca privada | ≥ $10 por debajo del mayorista promedio regional | Requisito |
| Índice de celebridades | satura en **300** por región | Más allá no suma |
| Mejoras de equipo | **Una vez por opción y por planta** (no "2 por vida útil") | Usada solo la A de Asia. **Quedan 7 comprables** — corregido en el A12 |
| Patrimonio mínimo | $100 M | Proyectado $255,7 M |

---

## 6. Set final del Año 11

### Pantalla 1 — Remuneración y formación
| Campo | N.A. | Asia |
|---|---|---|
| Salario base | +1% ($34.340) | +5% ($12.600) |
| Incentivo por par | $1,00 | $0,50 |
| Prestaciones | $3.000 | $1.500 |
| **Formación** | **$600** | **$600** ← subido |
| Supervisión | 40:1 | 40:1 |
| Remuneración supervisores | 0% | 0% |

### Pantalla 2 — Producción de marca propia
| Campo | N.A. | Asia |
|---|---|---|
| Material estándar / superior | 68% / 32% | 46% / 54% |
| Modelos | 200 | 200 |
| Estilo por modelo | $10 mil | $10 mil |
| TQM / 6-Sigma | $1,00 | $0,90 |
| **Pares a fabricar** | **3.891** | **4.139** |
| Costo por par resultante | $23,55 | $21,03 |

Total 8.030 contra requerimiento de 8.000. Excedente cero.

### Pantalla 3 — Instalaciones
Maquinaria nueva/reacondicionada: 0 · Venta: 0 · Obra civil: 0
**Mejora A en Asia (rechazo −50%): $10.000 mil.** Repago 2,8 años. Rinde desde el Año 12.

### Pantalla 4 — Distribución (miles de pares)
| Origen → Destino | Pares |
|---|---|
| Planta N.A. → almacén N.A. | 2.377 |
| Planta N.A. → almacén Europa-África | 1.242 |
| Planta Asia → almacén Europa-África | 700 |
| Planta Asia → almacén Asia-Pacífico | 1.560 |
| Planta Asia → almacén Latinoamérica | 1.461 |

Liquidación de inventario viejo: 0%. **Excedente/déficit: 0 en las cuatro regiones.**

### Pantalla 5 — Marketing en internet
| Campo | N.A. | E-A | A-P | L-A |
|---|---|---|---|---|
| Precio online | $69 | $77 | $69 | $77 |
| Diferencia sobre mayorista | 41% | 40% | 41% | 44% |
| Buscadores ($000s) | 6.500 | 4.500 | 4.000 | 3.500 |
| Envío gratis | No | No | No | No |

### Pantalla 6 — Marketing mayorista
| Campo | N.A. | E-A | A-P | L-A |
|---|---|---|---|---|
| Precio al detallista | $49 | $55 | $49 | $55 |
| Publicidad ($000s) | 10.000 | 9.000 | 8.000 | 6.500 |
| Rebaja por correo | $4 | $4 | $4 | $4 |
| Tiempo de entrega | 3 sem | 3 sem | 3 sem | 3 sem |
| Soporte por local | $4.000 | $4.000 | $2.750 | $2.750 |

### Pantalla 0 — Proyecciones competitivas
Precios de la industria sostenidos en $48/$53 mayorista y $67/$72 internet.
Calidad 4,0 y 200 modelos, planos. Publicidad, buscadores y soporte **+2,5%**.
Rebaja $5, entrega 3 semanas, envío gratis No.

### Pantalla 7 — Marca privada
| Campo | N.A. | E-A | A-P | L-A |
|---|---|---|---|---|
| Pares netos en venta | 423 | 424 | 297 | 298 |
| Precio de oferta | $31 | $37 | $31 | $37 |
| Incorporar en proyecciones | Sí | Sí | Sí | Sí |
| Margen resultante por par | $5,02 | $3,02 | $7,09 | $2,09 |

1.442 mil netos (1.570 brutos). Sumados a la marca propia dejan cada planta en 4.800.

### Pantalla 8 — Celebridades
| Celebridad | Oferta anual | Contrato | Índice N.A./E-A/A-P/L-A |
|---|---|---|---|
| **Billy Eyelash** (prioridad 1) | $3.500 mil | 2 años | 100 / 70 / 65 / 75 |
| Taylor Sluggish | $1.200 mil | 2 años | 70 / 100 / 70 / 55 |

Tope de gasto $4.700 mil. Índice combinado 170/170/135/130 contra **cero de las ocho
empresas**. Costo en el Año 11: **cero**.

### Pantalla 9 — Ciudadanía empresarial
| Iniciativa | Estado |
|---|---|
| Comedor y guardería | **Sí** — se paga sola |
| Seguridad e iluminación | **Sí** — se paga sola |
| Formación ética | **Sí** — el punto de imagen más barato |
| Empaque reciclado | No — confirmado en el A12: cero puntos |
| Código de proveedores | No — **el A12 mostró que sí da +1 punto por $0,05** |
| Eficiencia energética / donaciones | $0 |

Desembolso total $12.700 mil ($1,45 por par vendido). Imagen 67 → 71.

### Pantalla 10 — Finanzas
Préstamos 0 · Emisión 0 · Recompra 0 · Pago anticipado 0
**Dividendo $1,00 por acción.**
Ratio de impago **4,77** · cobertura 10,27 · caja al cierre $19.501 mil.

---

## 7. Método de trabajo

1. **Leer la pantalla antes de creerle a cualquier plan.** Recorrer las diez y anotar
   el estado real, buscando específicamente interruptores heredados.
2. **Una variable por vez.** Se rompió una vez en el A11: se cargaron rebaja, publicidad
   y diez supuestos juntos, el EPS cayó de $2,43 a $2,00 y hubo que separar las causas
   a mano.
3. **Cargar en orden de dependencia, no en el del menú.**
4. **Usar las rondas de prueba para comprar información, no para ganar.**
5. **Definir el criterio de éxito antes del experimento y revertir sin discutir.**
   En el A11: "revertir si el rechazo no baja 0,8 puntos". Bajó 0,3. Se revirtió.
6. **Verificar que las casillas no se hayan reseteado solas.**

---

## 8. Checklist antes de guardar

- [ ] Excedente/déficit en **cero** en las cuatro regiones (pantalla 4)
- [ ] Las dos plantas al tope de **4.800 brutos** (pantallas 2 y 7)
- [ ] Las cuatro casillas de *incorporar en proyecciones* en **Sí** (pantalla 7)
- [ ] Diferencia internet sobre mayorista en **40% o más** (pantalla 5)
- [ ] Envío gratis **apagado** salvo decisión expresa (pantalla 5)
- [ ] Producción cargada contra el **requerimiento actual** (pantalla 2)
- [ ] Ratio de impago **por encima de 4,00** (pantalla 10)
- [ ] Dividendo cargado **último** (pantalla 10)
- [ ] Botón **Guardar decisiones** apretado y confirmado

---

## 9. Pendiente de verificar con los resultados del Año 11

1. **¿Cuánto se movieron los rivales?** Todo el pronóstico asumió que la industria
   sostiene precios porque nadie puede abastecer su demanda. El Informe de la Industria
   lo confirma o lo desmiente. **Es el dato más valioso de la ronda.**
2. **¿Ganamos las cuatro licitaciones de marca privada?** El EPS de $2,83 asume que sí.
   La medición más parecida con las casillas apagadas dio **EPS $2,43 y ROE 20,8%** —
   ese es el piso si perdiéramos todas.
3. **¿A qué precio se despejó la subasta de celebridades?** Se ofertó a ciegas con el
   tablero en cero.
4. **¿Aguantó la elasticidad de precio?** La proyección decía que +$1 en N.A. costaba
   1,8% de volumen.
5. **¿La calificación llegó a A?** Se gastaron $42,7 M con el ratio proyectado en 4,77.

---

## 10. Sembrado para el Año 12

| Qué | Empieza a rendir | Qué esperar |
|---|---|---|
| Mejora A en Asia ($10 M, ya pagada) | Año 12 | Rechazo 10,1% → ~5%. Ahorro $3.571 mil/año, permanente |
| Billy Eyelash + Taylor Sluggish | Año 12 | Índice 170/170/135/130 contra cero de los rivales. Arrancan pagos de $4.700 mil/año |
| Comedor, guardería, seguridad | Ya rinde | +200 pares/trabajador. El reloj de la imagen arrancó |
| Mejoras de equipo | Disponible | **Quedan 7**, no una. Mejores relaciones medidas en el A12: **C en Asia 29,8%**, **B en ambas 29,1%**, **A en N.A. 26,9%**. Comprarlas temprano: rinden cero el año de la compra |
| Reemplazo total de maquinaria | **Año 15** | Toda se compró en el Año 5. Cuatro años para juntar |

### Agenda de carga del Año 12

1. **Leer el Informe de la Industria** antes de tocar una casilla. Los precios y gastos
   reales del A11 son la base de los supuestos del A12 — ahora con datos, no con teoría.
2. Recorrer las diez pantallas anotando el estado real.
3. Cargar **6 → 5**. Con la Mejora A bajando el rechazo va a sobrar producto: hay margen
   para ser más agresivo en precio o volumen.
4. Cargar **1 y 3**. Evaluar la segunda mejora contra el ratio, no contra la intuición.
5. Cargar **2 → 7 → 4**. Llenar las dos plantas al tope. Verificar las cuatro casillas.
6. Cargar **8 y 9**. Escalar solo las iniciativas que puntúen. Tercera celebridad con el
   precio de despeje ya conocido.
7. Cargar **10** último, con el dividendo al final leyendo el ratio.

---

## 11. Equipo

| Área | Integrantes | Decisiones |
|---|---|---|
| CEO | Fabricio Moreno | Coordinación, carga en el sistema, cierre |
| RRHH | Rodrigo Vilanoba | 1 |
| Marketing | Maria Rojas · Leticia Valdez · Gabriel Villar | 5, 6, 8 + proyecciones |
| Operaciones | Florencia Silguero · Daiana Trila · Jesús Quiroga | 2, 7 |
| Mant. y Facility | Diego Zago | 3 |
| Logística | Rocio Torres | 4 |
| Finanzas | Constanza Villanueva | 10 |
| RSE | Pau Smircic | 9 |
| Analista de Datos | Constanza Villanueva | Proyecciones competitivas |

**Solo el CEO tiene acceso al simulador.** Cada área analiza y recomienda; el CEO carga.

> Constanza concentra Finanzas + Analista, que son los dos extremos de la secuencia.
> Rodrigo, Diego y Pau tienen capacidad libre.

---

## 12. Calendario

| Ronda | Cierre | Cuenta |
|---|---|---|
| Prueba 1 | 12/09 | ✅ jugada — no cuenta |
| Prueba 2 | 19/09 | No |
| **Jugada 1 (Año 12)** | **26/09** | **Sí** |
| Jugada 2 | 03/10 | Sí |
| Jugada 3 | 10/10 | Sí |
| Jugada 4 | 24/10 | Sí |
| Jugada 5 | 31/10 | Sí |
| Jugada 6 | 07/11 | Sí |

Quizz 2 (sobre los reportes): 28/09 · Parcial: 03/11 · Recuperatorio: 10/11

---

*Última actualización: 13 de septiembre de 2026, tras la jugada de prueba 1.*
*Fuente: `informes/Informe_BSG_Ano11.pdf` (21 mediciones del panel en vivo),
reportes del Año 10 y Guía del Gerente de BSG.*
