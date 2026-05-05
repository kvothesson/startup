# startup

Plugin de Claude Code — ecosistema emprendedor argentino.

## Que hace

`/startup` te orienta en el universo emprendedor de Argentina: donde conseguir financiamiento publico (FONTAR, FONSOFT, ANR), como constituir una empresa (SAS, SRL, SA), como estructurar el equity y como armar un pitch para inversores locales.

## Instalacion

```bash
claude --plugin-dir /ruta/a/startup
```

## Comandos y ejemplos

### `/startup fondos`

```
🚀 Financiamiento para Emprendedores — 4 may 2026

FONTAR (Fondo Tecnologico Argentino)
  Que es: subsidios no reembolsables (ANR) y creditos blandos para innovacion tecnologica
  ANR: hasta USD 500.000 aprox. — requiere co-financiamiento propio
  Quien aplica: empresas con proyecto de innovacion tecnologica radicadas en Argentina
  Estado convocatoria: convocatoria permanente (verificar apertura en agencia.gob.ar)
  → https://www.agencia.gob.ar/fontar

FONSOFT (Software y Servicios Informaticos)
  Que es: financiamiento especifico para empresas de software
  ANR de hasta $15M para proyectos de I+D en software
  → https://www.agencia.gob.ar/fonsoft

SEPyME — Creditos PyME
  Lineas para capital de trabajo, inversion, exportacion
  Tasa subsidiada — verificar vigentes en argentina.gob.ar/produccion/sepyme
  → https://www.argentina.gob.ar/produccion/sepyme

ECOSISTEMA PRIVADO (may 2026)
  Aceleradoras activas: Endeavor, NAVES (UCA), Socialab, StartupBoot
  VCs con actividad en AR: Kaszek, ALLVP, Fuel Ventures (buscar vigentes)

🔗 Portal emprender: https://www.argentina.gob.ar/tema/emprender/financiamiento
Fuente: argentina.gob.ar / agencia.gob.ar — 4 may 2026
```

---

### `/startup legal sas`

```
⚖️ Constitucion — SAS (Sociedad por Acciones Simplificada)
   Dato al 4 may 2026

¿Cuando conviene?
  Ideal para emprendedores que arrancan solos o en duo. La mas rapida de constituir.
  Permite clases de acciones, util para estructura de equity con inversores.

Pasos:
  1. Genera el estatuto modelo en TAD (tramitesadistancia.gob.ar) — hay plantilla online
  2. Firma digital de los socios (no requiere escribano)
  3. Presentacion ante el registro de tu provincia via TAD
  4. CUIT en ARCA (arca.gob.ar)
  5. Apertura de cuenta bancaria empresa

Costo aproximado:
  Tasas registrales: varía por provincia (~$50.000–$150.000)
  Sin honorarios notariales si usas el modelo estandar

Tiempo estimado: 3–10 dias habiles (con estatuto estandar)

⚠️ Consulta con un abogado para estatutos personalizados.

🔗 IGJ: https://www.argentina.gob.ar/justicia/igj
🔗 TAD: https://tramitesadistancia.gob.ar
Fuente: IGJ / argentina.gob.ar — 4 may 2026
```

---

### `/startup pitch app de turnos medicos`

```
🎯 Estructura de Pitch — app de turnos medicos
   Dato al 4 may 2026

Slide 1 — PROBLEMA
  Los pacientes pierden en promedio 40 minutos por turno medico gestionado por telefono.

Slide 2 — SOLUCION
  App de turnos instantaneos para clinicas independientes. Agenda en 30 segundos.

Slide 3 — MERCADO
  TAM: 12.000 clinicas y consultorios privados en AMBA
  SAM: 3.000 con facturacion electronica activa
  SOM: 300 primeros clientes en 18 meses

Slide 4 — TRACCION
  150 clinicas en beta, 4.200 turnos gestionados/mes, crecimiento 20% MoM

Slide 5 — MODELO DE NEGOCIO
  SaaS: $25 USD/mes por consultorio.

Slide 6 — EQUIPO
  [nombre] — 8 años en healthtech
  [nombre] — ex producto en empresa de logistica medica

Slide 7 — ASK
  USD 200.000 seed. 12 meses de runway. Meta: 500 clinicas y break-even.

PARA EL ECOSISTEMA ARGENTINO:
  → Precio en USD = proteccion ante inflacion (mostrar)
  → Mencionar potencial de expansion LATAM desde base AR
  → Considerar FONTAR para componente de IA si lo hay

Fuente: sintesis del ecosistema — 4 may 2026
```

## Fuentes

- **FONTAR:** [agencia.gob.ar/fontar](https://www.agencia.gob.ar/fontar)
- **FONSOFT:** [agencia.gob.ar/fonsoft](https://www.agencia.gob.ar/fonsoft)
- **SEPyME:** [argentina.gob.ar/produccion/sepyme](https://www.argentina.gob.ar/produccion/sepyme)
- **Portal emprender:** [argentina.gob.ar/tema/emprender/financiamiento](https://www.argentina.gob.ar/tema/emprender/financiamiento)
- **IGJ / TAD:** [tramitesadistancia.gob.ar](https://tramitesadistancia.gob.ar)

Este plugin no almacena ni transmite informacion del usuario. No constituye asesoramiento legal ni contable.
