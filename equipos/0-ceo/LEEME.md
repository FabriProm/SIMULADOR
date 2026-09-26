# CEO — Fabricio Moreno

**Lo que manejás:** la coordinación, la carga en el simulador y el guardado final.
Sos el único con acceso: cada área analiza y recomienda, vos cargás. Si no hay acuerdo,
definís el rumbo (reglamento de la materia).

---

## Cómo llevar cada reunión de decisión

### El orden de las áreas

| Orden | Área | Por qué va acá |
|---|---|---|
| 1 | **Analista de Datos** | Define contra qué nos compara el simulador. Sin esto, todo lo demás calcula mal |
| 2 | **Marketing**: primero mayorista, después internet | Precio y publicidad fijan cuánta demanda tenemos |
| 3 | **RRHH** y **Mant. y Facility** | Fijan la productividad y el techo de producción |
| 4 | **Operaciones** | Recién ahora se sabe cuántos pares fabricar |
| 5 | **Logística** | Reparte lo que se produjo |
| 6 | **Marketing (famosos)** y **RSE** | No dependen del resto |
| 7 | **Finanzas** | Siempre última: recién ahí se sabe cuánta plata hay |

Los pasos 2, 4 y 5 son de ida y vuelta: cada cambio de precio cambia cuántos pares hacen
falta.

### Cómo conducirla

| Bloque | Qué pasa | Tu rol |
|---|---|---|
| Apertura | Resultado de la jugada anterior y qué cambió en la industria | Hablás vos |
| Ronda de áreas | Cada una presenta su propuesta | **Escuchás. No opinás todavía** |
| Discusiones | Los conflictos entre áreas | Moderás |
| Cierre | Ponés tu propuesta al lado y se decide | Decidís |

Si adelantás tu posición en la ronda, los que hablan después se acomodan y perdés justo la
información que fuiste a buscar. Abrí mostrando tus dudas, no tus aciertos.

**Dos reglas para todos:** una variable por vez, y definir antes qué resultado justifica
el cambio. Si no llega, se vuelve atrás sin discutir.

---

## Antes de guardar

- [ ] Excedente o déficit cerca de cero en las cuatro regiones (pantalla 4)
- [ ] Las dos plantas llenas: 4.800 pares brutos cada una (pantallas 2 y 7)
- [ ] Las cuatro casillas "incorporar en proyecciones" en **Sí** (pantalla 7)
- [ ] Internet 40% o más arriba del mayorista (pantalla 5)
- [ ] Envío gratis apagado, salvo decisión expresa (pantalla 5)
- [ ] Ratio de riesgo de impago arriba de 4,00 (pantalla 10)
- [ ] Dividendo y recompra cargados al final, leyendo el ratio (pantalla 10)
- [ ] "Guardar decisiones" apretado y confirmado **recargando la página**
- [ ] PDF de las entradas guardado en `jugadas/ano-XX/`

Dejá unas horas de margen antes del cierre de las 23:59.

---

## Después de cada cierre

1. Bajar los informes del año cerrado (FIR, CIR, COR) a `jugadas/ano-XX/`.
2. Mirar los cuatro indicadores de `conocimiento/RUMBO-ESTRATEGICO.md`: costo por par,
   calidad, utilización y precio contra el sector.
3. Revisar si algún rival ocupó nuestra misma posición.
4. Comparar el EPS real contra el proyectado. Si el error pasa del 5%, recalibrar los
   supuestos.
