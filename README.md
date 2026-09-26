# SIMULADOR — Company H · Industria 5

Business Strategy Game (BSG) · Administración Estratégica · UTN · 2º cuatrimestre 2026.
Docentes: Leandro Di Matteo y Marcos Barbe.

---

## Dónde estamos

**El juego oficial se reinició en el Año 11.** Las dos jugadas de prueba se descartaron y
las ocho empresas vuelven a arrancar iguales. Lo único que traemos de las pruebas son las
mediciones de `conocimiento/MECANICAS-MEDIDAS.md`.

**Estrategia:** proveedor de mejor costo con alcance global. Ver
`conocimiento/RUMBO-ESTRATEGICO.md`.

| Jugada | Año | Cierre | Estado |
|---|---|---|---|
| **1** | **11** | **26/09** | **cargada el 26/09 · proyecta EPS $3,23 · ROE 26,7% · A · imagen 77** |
| 2 | 12 | 03/10 | |
| 3 | 13 | 10/10 | |
| 4 | 14 | 24/10 | |
| 5 | 15 | 31/10 | |
| 6 | 16 | 07/11 | |

Otras fechas: Quizz 2 (reportes) 28/09 · TP5 Plan estratégico 18/10 · Parcial 03/11 ·
Recuperatorio 10/11 · TP6 Balanced Scorecard 11/11.

---

## Cómo nos califican

Cinco indicadores, 20% cada uno: **EPS, ROE, precio de la acción, calificación crediticia
e imagen**. Cada uno se mide mitad contra la meta del inversor y mitad contra la mejor
empresa de la industria. Todos los integrantes sacan la misma nota.

| Meta | A11 | A12 | A13 | A14 | A15 | A16 |
|---|---|---|---|---|---|---|
| EPS | $2,50 | $3,00 | $3,50 | $4,00 | $4,50 | $5,25 |
| ROE | 21% | 22% | 23% | 24% | 25% | 26% |
| Precio de la acción | $40 | $50 | $65 | $80 | $100 | $125 |
| Crédito | B+ | B+ | B+ | A− | A− | A− |
| Imagen | 70 | 72 | 72 | 75 | 75 | 77 |

---

## Estructura

```
conocimiento/
  RUMBO-ESTRATEGICO.md      la estrategia elegida y cómo medirla
  MECANICAS-MEDIDAS.md      todo lo medido en las pruebas: mecánicas, trampas, umbrales
equipos/
  0-ceo/ … 8-analista-datos/   un LEEME por área: pantalla, lo aprendido, arranque, qué traer
jugadas/
  ano-10-arranque/          informes del Año 10 (PDF y CSV de FIR, CIR y COR)
  ano-11/                   pantallas de decisión del Año 11 (estado inicial)
entregas/                   trabajos prácticos entregados
documentos_de_la_materia/   programa, cronograma, reglamento, guía del simulador, lecturas
```

Por cada jugada se crea `jugadas/ano-XX/` con las entradas cargadas antes del cierre y los
informes del año cerrado.

---

## Equipo

| Área | Integrantes | Pantallas |
|---|---|---|
| CEO | Fabricio Moreno | Coordinación y carga (único con acceso) |
| Analista de Datos | Constanza Villanueva | Supuestos competitivos (pie de 5 y 6) |
| Marketing | Maria Rojas · Leticia Valdez · Gabriel Villar | 6, 5, 8 |
| RRHH | Rodrigo Vilanoba | 1 |
| Mant. y Facility | Diego Zago | 3 |
| Operaciones | Florencia Silguero · Daiana Trila · Jesús Quiroga | 2, 7 |
| Logística | Rocio Torres | 4 |
| RSE | Pau Smircic | 9 |
| Finanzas | Constanza Villanueva | 10 |

---

## Arranque del Año 11 oficial, sin tocar nada

| EPS | ROE | Crédito | Imagen | Ingresos | Beneficio neto | Caja final |
|---|---|---|---|---|---|---|
| $2,28 | 19,6% | A− | 64 | $448.270 mil | $45.682 mil | $53.933 mil |

Si no se cambia nada, perdemos tres de las cinco metas (EPS, ROE e imagen). Hay déficit de
producto en las cuatro regiones, las plantas tienen capacidad libre para marca privada y
el ratio de riesgo de impago está en 4,07, casi en el umbral de 4,00.
