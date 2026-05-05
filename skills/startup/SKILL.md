---
description: Ecosistema emprendedor argentino. Fondos y financiamiento publico (FONTAR, FONSOFT, ANR, SEPyME), constitucion de empresas (SAS, SRL, SA), estructuras de equity y framework de pitch para el contexto local. Usalo para arrancar, financiar o estructurar un emprendimiento en Argentina.
---

# Skill: /startup

## Fecha actual

Antes de cualquier WebSearch que incluya año o mes, confirma la fecha del sistema (`Bash: date` o contexto `currentDate`). Nunca asumas ni hardcodees el año — usa siempre el que reporta el sistema.

Guia del ecosistema emprendedor argentino. Financiamiento, estructura legal, equity y pitch.

## Principios

- **Fuente primaria siempre.** FONTAR, FONSOFT, SEPyME: siempre a los organismos directamente.
- **Sin montos hardcodeados.** Techos de ANR, cuotas y convocatorias cambian: buscalos en tiempo real.
- **Lenguaje llano y orientado a la accion.**
- **Siempre mostra fuente y fecha del dato.**
- **No des asesoramiento legal ni contable.** Para constitucion de empresa y contratos, siempre indicar consultar con profesional matriculado.

---

## Comandos

### `/startup fondos`

Financiamiento publico y privado disponible para emprendimientos y startups en Argentina.

**Paso 1 — Portal oficial:**

WebFetch: `https://www.argentina.gob.ar/tema/emprender/financiamiento`

**Paso 2 — FONTAR y FONSOFT:**

WebSearch: `FONTAR ANR convocatoria [año actual] site:agencia.gob.ar OR site:argentina.gob.ar`

WebSearch: `FONSOFT financiamiento software [año actual] Argentina`

**Paso 3 — Convocatorias abiertas:**

WebSearch: `convocatorias financiamiento startups Argentina [año actual] abiertas`

**Formato:**

```
🚀 Financiamiento para Emprendedores — [fecha de hoy]

FONTAR (Fondo Tecnologico Argentino)
  Que es: subsidios no reembolsables (ANR) y creditos blandos para innovacion tecnologica
  ANR: hasta [monto vigente] — requiere co-financiamiento propio
  Quien aplica: empresas con proyecto de innovacion tecnologica radicadas en Argentina
  Estado convocatoria: [buscar si esta abierta]
  → https://www.agencia.gob.ar/fontar

FONSOFT (Software y Servicios Informaticos)
  Que es: financiamiento especifico para empresas de software
  → https://www.agencia.gob.ar/fonsoft

SEPyME — Creditos PyME
  Lineas para capital de trabajo, inversion, exportacion
  → https://www.argentina.gob.ar/produccion/sepyme

ECOSISTEMA PRIVADO
  [buscar con WebSearch "aceleradoras Argentina [año actual]" y "VCs activos Argentina [año actual]"]
  [presentar los resultados mas relevantes encontrados]

🔗 Portal emprender: https://www.argentina.gob.ar/tema/emprender/financiamiento
Fuente: argentina.gob.ar / agencia.gob.ar — [fecha]
```

---

### `/startup legal [tipo]`

Como constituir una empresa en Argentina. Tipos: `sas`, `srl`, `sa`, o consulta libre.

**Para todos los tipos:**

WebSearch: `constituir [tipo] Argentina [año actual] IGJ requisitos pasos costo`

WebFetch: `https://tramitesadistancia.gob.ar` (para SAS digital)

**Tabla comparativa — mostrarla cuando el usuario no especifica tipo:**

```
Tipo   Socios min.  Capital min.   Ventaja principal
SAS    1            $1             Constitucion 100% digital en dias
SRL    2            $1             Tradicional, amplia jurisprudencia
SA     2            [legal vigente] Para inversores, emision de acciones
```

**Formato por tipo:**

```
⚖️ Constitucion — [tipo]
   Dato al [fecha de hoy]

¿Cuando conviene?
  [descripcion en 2 lineas]

Pasos:
  1. [paso con organismo y URL]
  2. [paso]
  3. [paso]

Costo aproximado:
  Honorarios: [rango orientativo]
  Tasas IGJ/Registro: [monto vigente — verificar en igj.gob.ar]

Tiempo estimado: [dias habiles]

⚠️ Consulta con un escribano o abogado para la redaccion del estatuto.

🔗 IGJ: https://www.argentina.gob.ar/justicia/igj
🔗 TAD (tramites digitales): https://tramitesadistancia.gob.ar
Fuente: IGJ / argentina.gob.ar — [fecha]
```

---

### `/startup equity [contexto]`

Estructuras de equity para el contexto argentino: ESOP, vesting, pacto de socios, opciones.

WebSearch: `equity startups Argentina [año actual] ESOP vesting pacto socios`

WebSearch: `SAFE nota convertible startups Argentina [año actual]`

**Formato:**

```
📊 Equity — [contexto]
   Dato al [fecha de hoy]

CONCEPTOS CLAVE ADAPTADOS A ARGENTINA

Vesting:
  Tipico: 4 anos con 1 ano de cliff
  En Argentina: se implementa via pacto de socios o contrato de opciones
  (las cuotas de SRL y acciones de SA no tienen vesting nativo — se estructura contractualmente)

ESOP (opciones para empleados):
  En SAS: mas flexible, permite clases de acciones
  En SRL: se implementa via compromisos de compra futura en pacto de socios
  Consideracion local: inflacion distorsiona el strike price — pactarlo en USD

SAFE / Nota Convertible:
  El SAFE anglosajón no tiene forma juridica directa en AR
  Alternativa: prestamo convertible con documentacion local
  [presentar estructura tipica encontrada]

PACTO DE SOCIOS — clausulas minimas recomendadas:
  → Vesting y cliff de founders
  → Drag-along y tag-along
  → Right of first refusal
  → Anti-dilution (si hay inversores)
  → Clausulas de salida

⚠️ Estructura siempre con un abogado especializado en startups.

Fuente: [fuentes encontradas] — [fecha]
```

---

### `/startup pitch [idea]`

Framework de pitch adaptado al ecosistema inversor argentino.

WebSearch: `pitch startups Argentina inversores [año actual] estructura deck`

**Formato:**

```
🎯 Estructura de Pitch — [idea/sector]
   Dato al [fecha de hoy]

Slide 1 — PROBLEMA
  Una oracion: que dolor resuelves y para quien

Slide 2 — SOLUCION
  Como lo resolves. Diferencial en 2 lineas.

Slide 3 — MERCADO
  TAM / SAM / SOM — en USD si es tech/exportable, en ARS si es local
  Mostrar tamaño del mercado argentino + oportunidad LATAM si aplica

Slide 4 — TRACCION
  Lo que tengas: usuarios, ingresos, crecimiento mes a mes
  En Argentina: prioriza metricas en USD si tenes ingresos dolarizados

Slide 5 — MODELO DE NEGOCIO
  Como ganas plata. Simple, una linea.

Slide 6 — EQUIPO
  Por que ustedes. Experiencia directamente relevante al problema.

Slide 7 — ASK
  Cuanto pides, en que lo usas, que hito te da en 18 meses.

PARA EL ECOSISTEMA ARGENTINO:
  → Ingresos en USD = premium en valoracion (muestra si lo tenes)
  → Plan de retencion de talento (el contexto de migracion es real para los inversores)
  → Si vas a FONTAR/aceleradoras: adapta la narrativa a sus criterios (ver /startup fondos)
  → Inversores activos en AR: [buscar lista vigente con WebSearch]

Fuente: sintesis del ecosistema — [fecha]
```

---

## Manejo de errores

- Si agencia.gob.ar no carga, busca con WebSearch `FONTAR convocatoria [año actual]`.
- Si los montos de ANR tienen mas de 6 meses de antiguedad, avisalo.
- Si el usuario pregunta por aceleradoras privadas especificas, hace WebSearch directamente.
- Nunca des asesoramiento legal ni contable. Para constitucion de empresa y contratos, siempre indicar que consulte con profesional matriculado.

## Tono

Directo, orientado a la accion. El emprendedor quiere saber que hacer hoy, no leer teoria. Usa ejemplos en pesos o dolares segun el contexto. Nunca prometas resultados de convocatorias.
