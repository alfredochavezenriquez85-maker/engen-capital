# ENTREVISTA SUSCRIPCIÓN LMM — Federico Cantú (Responsable de Riesgo LMM)
## Segunda Entrevista + Análisis de Modelos de Crédito

**Entrevistado:** Federico Cantú, Responsable de Riesgo LMM
**Entrevistador:** Fernando Sánchez (LCG)  
**Fecha:** 18 de marzo de 2026  
**Material de apoyo:** Presentación "Revisión Modelos LMM 2025" (PPT interna de Crédito Engen)  
**Contexto:** Esta fue la segunda entrevista con Federico, enfocada en entender la simplificación de los modelos de crédito y los escenarios para abrir la llave de riesgo. Los hallazgos fueron presentados y discutidos previamente con Juan Pablo Loperena (Director General), Gerardo Biagi (Linzor Capital), y Fernando Garza (Director de Riesgo).

---

## 1. LA TESIS DE FEDERICO: EL PROBLEMA ES LA TUBERÍA, NO LOS MODELOS

### La analogía de la "fábrica de bolillos"

Federico usa repetidamente la metáfora de una panadería para explicar cómo debería funcionar el segmento LMM:

**La fábrica de bolillos (Fast App + Paramétrico):** Operaciones que entran, se evalúan rápido, pasan o no pasan, y si no pasan, a la siguiente. Sin detenerte a "ver si el bolillo quemado se puede rescatar". Volumen alto, decisiones rápidas, fricción mínima.

**La fábrica de baguettes (Estudio Corto):** Operaciones que necesitan más trabajo. Ya sabes que no es un bolillo simple — hay que entrevistar al cliente, hacer cuestionario, validar puntos que brincaron en el modelo. Es un "mini-Core" con expectativa de mayor complejidad.

**La fábrica de pasteles (Estudio Full / Core):** Operaciones grandes y complejas que requieren análisis completo. Estructuras a la medida, Comité de Directores o Consejo.

### El problema actual: "ya no es fábrica de bolillos"

Federico identifica que la iniciativa LMM ha evolucionado de su diseño original (volumen alto, decisiones rápidas, operaciones estándar) hacia un "mini-Core" donde:

- Cuando una oportunidad no pasa el modelo Fast App o Paramétrico, en lugar de descartarla y pasar a la siguiente, el originador la pelea porque **es la única que trae en la bolsa**
- Esto genera que operaciones que debían resolverse en 24 horas se conviertan en ejercicios de crédito de semanas con cuestionarios adicionales, entrevistas, y solicitudes de información complementaria
- El resultado es que el equipo de crédito dedica tiempo desproporcionado a operaciones que originalmente debían ser "pasan o no pasan"

**Cita textual de Federico:**
> "Donde siento yo que estamos teniendo un problema es que no estamos generando el suficiente volumen de oportunidades. Si tú como vendedor traes 10 oportunidades y me rechazan 4 de cada 10, no pasa nada. Donde empieza el problema es cuando la oportunidad que no pasa es la única que traigo en mi bolsa. Entonces ya la empiezas a pelear, aunque esté quemada. Le raspamos, le quitamos, le hacemos — y ya dejó de ser la fábrica de bolillos."

**Cita textual sobre el diagnóstico de fondo:**
> "Fernando Garza [Director de Riesgo] también comulga con esta posición: abrir la llave de los modelos no es la solución. Que te cambie el apalancamiento de 3 a 4, que te diga que el FCC ya no sea de 1 sino de 0.9 — eso no va a ser el breakthrough para que despegue la iniciativa. 200 millones de pesos no me van a mover la aguja. Necesitamos algo más de fondo."

---

## 2. LOS DATOS DUROS: RESOLUCIONES LMM 2023-2025

### Aprobaciones por tipo de modelo (evolución 3 años)

| Modelo | 2023 | % | 2024 | % | 2025 | % | Tendencia |
|--------|------|---|------|---|------|---|-----------|
| Fast Application | 94 | 38% | 94 | 41% | 88 | 44% | Estable en # pero sube en mix |
| LMM Paramétrico | 89 | 36% | 67 | 29% | **18** | **9%** | **Colapso: de 89 a 18 operaciones** |
| LMM Corto | 39 | 16% | 43 | 19% | 63 | 31% | Crece: absorbe lo que sale de Paramétrico |
| Full Underwriting | 27 | 11% | 25 | 11% | 32 | 16% | Crece: más operaciones complejas |
| **TOTAL** | **249** | **100%** | **229** | **100%** | **201** | **100%** | **-19% en 2 años** |

**Nota:** No incluye Factoraje, MACs y "others".

**Hallazgo clave:** El Paramétrico colapsó de 89 operaciones (36% del mix) en 2023 a solo 18 operaciones (9%) en 2025. Las operaciones que antes se resolvían vía Paramétrico ahora migran a Estudio Corto (de 39 a 63) y Full Underwriting (de 27 a 32), consumiendo exponencialmente más tiempo y recursos de crédito.

### Dictaminaciones y rechazos (2024 vs 2025)

| Concepto | 2024 # | 2024 $MM | 2025 # | 2025 $MM |
|----------|--------|----------|--------|----------|
| Oportunidades aprobadas | 273 | $2,187 | 236 | $2,831 |
| Oportunidades rechazadas/withdrawn | 141 | $1,537 | 119 | $1,525 |
| **TOTAL dictaminadas** | **414** | **$3,724** | **351** | **$4,356** |
| **% Rechazos/Withdrawn** | **34%** | **41%** | **33%** | **35%** |

**Observaciones:**
- El número total de oportunidades dictaminadas cayó de 414 a 351 (-15%), confirmando la tesis de que el problema es la tubería
- El ticket promedio aprobado subió significativamente: $8.01M (2024) → $12.0M (2025)
- Se aprobaron menos operaciones (273 → 236) pero por mayor monto total ($2,187M → $2,831M)

### Rechazos específicos por modelo (solo Fast App + Paramétrico)

**2024:**

| Modelo rechazado | # Operaciones | $ (miles) |
|------------------|--------------|-----------|
| LMM Paramétrico | 30 | $225,496 |
| Fast Application | 29 | $76,649 |
| **Total modelos** | **59** | **$302,145** |

**2025:**

| Modelo rechazado | # Operaciones | $ (miles) |
|------------------|--------------|-----------|
| LMM Paramétrico | 25 | $178,849 |
| Fast Application | 23 | $66,591 |
| **Total modelos** | **48** | **$245,440** |

**Los rechazos por modelo (Fast App + Paramétrico) representan +60% de todos los rechazos.** Esto es el universo de operaciones que se podría "rescatar" si se abriera la llave.

**Pero Federico dimensiona:** "Si yo te abriera la llave — en el mejor de los escenarios son $250MM de pesos más. Y nunca vas a ir por los 250, vas por una parte de eso. ¿$100MM de pesos te van a hacer la diferencia en tu estrategia comercial? No. O sea, $100MM no son malos, pero pensando en el 2x-3x, eso no te mueve la aguja."

---

## 3. MIGRACIÓN DE PARAMÉTRICO A CORTO: 27 OPERACIONES ANALIZADAS

### Las 27 operaciones que cambiaron de carril

27 operaciones por $151MM que originalmente debían resolverse vía Paramétrico acabaron siendo aprobadas bajo Estudio Corto. **100% de estas 27 operaciones están CURRENT (al corriente).**

**Distribución por monto:**
- 11 operaciones < $5MM ($37MM total)
- 4 operaciones entre $5-6MM ($22MM)
- 4 operaciones entre $6-7MM ($25MM)
- 8 operaciones de +$7MM ($67MM)

**Razones de rechazo del modelo paramétrico que forzaron migración a Corto:**
- FCCR < 0.75x (cobertura de flujo insuficiente para el modelo)
- D/E > 4x (apalancamiento excesivo)
- Concentración de clientes
- Días cartera

**Qué pasó después:** Se hicieron reclasificaciones de cuentas tras cuestionario/entrevista con el cliente, con lo que el modelo "salió aprobado". De las 27, 7 pasaron el modelo pero dadas las tendencias observadas se hizo un análisis adicional.

**La lección de Federico:** Este cambio de carril es lo que infla los tiempos. Una operación que debía resolverse en 72 horas (Paramétrico) se convierte en un ejercicio de 7+ días (Corto) porque el originador no la quiere soltar, y crédito tiene que acomodarla por otro camino.

---

## 4. CAUSAS DE RECHAZO 2025: ANÁLISIS MULTIVARIABLE

### Distribución de rechazos por número de variables fallidas (2025)

| # Variables de rechazo | # Oportunidades | % |
|----------------------|----------------|---|
| 1 variable | 7 | 15% |
| 2 variables | 19 | 40% |
| 3 variables | 12 | 25% |
| 4 variables | 8 | 17% |
| 5 variables | 2 | 4% |
| **Total** | **48** | **100%** |

**Hallazgo fundamental: Las razones de rechazo son MULTIFACTORIALES.** El 85% de los rechazos tienen 2 o más variables fallidas. No existe una sola palanca que al moverla desbloquee un volumen significativo.

**Los 7 rechazos por una sola variable fueron todos KOs automáticos:**
- AML (lavado de dinero)
- BILs negativos (Business Information Letters)
- Información no confiable / alterada
- FCC negativo
- Empresa con < 3 años de operación

**Esto significa que no hay un bucket de "casi pasaron" que puedas rescatar fácilmente.** Los que fallaron por una sola variable fallaron por cosas que no puedes flexibilizar (fraude, AML, información falsa).

### Top 5 causas de rechazo (Fast App + Paramétrico, 2025)

| Causa | Incidencia |
|-------|-----------|
| **Flujo insuficiente (FCC < 1)** | **17 casos** |
| Inconsistencia en la información | 7 casos |
| Atrasos en buró | 4 casos |
| Deterioro financiero | 3 casos |
| Destino recursos S&LB / Activo no financiable | 2 cada uno |

### Principales causas de rechazo históricas (2024, 141 casos / $1,537MM)

| Causa | # Hits | $MM afectados |
|-------|--------|---------------|
| FCC < 1 (flujo insuficiente) | 43 | $452 |
| BDC Negativo (buró de crédito) | 23 | $179 |
| D/E > 4x (apalancamiento) | 22 | $232 |
| BDC No Representativo | 13 | $92 |
| Activo Fijo vs Línea | 12 | — |
| Concentración Clientes/Gob | 11 | — |
| Discrepancia Info | 11 | — |
| Fin Perf Neg Trend | 11 | — |
| OR 17 or worse | 8 | — |
| BIL Negativo | 6 | — |

---

## 5. EJERCICIO DE SENSIBILIDAD: ¿QUÉ PASA SI ABRO LA LLAVE?

### Escenarios de flexibilización de variables (Ejercicio 2023, muestra de 27 deals / US$5.9MM rechazados)

| Variable | Target actual | Esc 1 | Esc 2 | Esc 3 | Esc 4 | Esc 5 |
|----------|-------------|-------|-------|-------|-------|-------|
| BDC no Representativo | 25% iniciales BDC PG positivo | Igual | Igual | Igual | Igual | Igual |
| Concentración Clientes (%) | <30% | <50% | <55% | <60% | <65% | <70% |
| FCC (x) | 1.2x – 1.5x | >1.0x | >0.9x | >0.85x | >0.8x | >0.75x |
| Ratio Línea/Activo (x) | 0.5x | 1.0x | 1.5x | 2.0x | 3.0x | 4.0x |
| EBITDA Leverage (x) | 3.0 – 3.25 | 3.5x | 3.75x | 4.0x | 4.25x | 4.5x |

**Resultado de los escenarios:**

| Escenario | # Deals aprobados | US$MM aprobados | % del total rechazado |
|-----------|------------------|----------------|-----------------------|
| Escenario 1 | 3 | $0.3 | 6% |
| Escenario 2 | 4 | $0.4 | 7% |
| Escenario 3 | 6 | $0.95 | 16% |
| Escenario 4 | 9 | $1.62 | 27% |
| **Escenario 5 (máxima apertura)** | **11** | **$1.88** | **32%** |

**Conclusión del ejercicio:** Incluso en el escenario más agresivo (Escenario 5), con FCC bajando a 0.75x, concentración de clientes aceptando hasta 70%, apalancamiento hasta 4.5x, y ratio línea/activo hasta 4x, solo rescatas 11 de 27 deals, US$1.88MM. **Ni siquiera llegas al tercio del monto rechazado por modelos.**

---

## 6. CARTERA VENCIDA POR MODELO

### DLQ total Dic-25

**Total DLQ: $234.9MM / 10.2%**

**DLQ ajustado (sin operaciones anteriores a 2021, TIP y operaciones "racionalizadas" — 9 cuentas / $76MM):**
**DLQ ajustado: $158.8MM / 6.9%**

### DLQ del Paramétrico (el modelo en cuestión)

| Aging | # Clientes | $ (MM) | % DLQ |
|-------|-----------|--------|-------|
| DLQ 30 | 5 | $17.5 | 4.8% |
| DLQ 60 | 5 | $24.7 | 6.7% |
| DLQ 90+ | 8 | $24.9 | 6.8% |
| **Total DLQ Paramétrico** | **18** | **$67.1** | **18.3%** |

**DLQ Paramétrico ajustado (sin Health/Care): 15% total / 4.5% 90+**

**Variables que fallaron en la cartera vencida del Paramétrico vs. razones de atraso:**

| Variables fallidas en el modelo original | Razón real de atraso |
|-----------------------------------------|---------------------|
| Concentración Clientes (5 casos) | Caída en ventas con clientes principales / Pérdida de clientes (8 casos) |
| Experiencia Clientes Principales (4) | — |
| Ratio Activo/Monto de Línea (5) | — |
| Experiencia Buró no Representativa (5) | — |
| AR Days (2) | Recuperación de cartera (3) |
| Otros (Industria, Calif PG, Apalancamiento, Gap) | Industria - Gobierno, Hidrocarburos (3) |

**Esto revela que la concentración de clientes y la experiencia crediticia limitada son los predictores más fuertes de deterioro en el Paramétrico.** Las cosechas 2022-2023 concentran la mayoría de los problemas.

### Alivios y Reestructuras (visión de todo el portafolio LMM)

| Período | # Alivios | $ (MM) | % del total acumulado |
|---------|----------|--------|----------------------|
| 2022 | 5 | $39.19 | 7% |
| 2023 | 8 | $65.97 | 11% |
| 2024 | 17 | $127.77 | 24% |
| **2025** | **41** | **$372.34** | **58%** |
| **ACUMULADO** | **71** | **$605.27** | **100%** |

**Los $605MM en alivios representan:**
- 12% del fondeo total acumulado LMM 2022-2025 ($4,932MM)
- 26% del valor del portafolio LMM a Dic-25 ($2,300MM)

**58% de los alivios (41 de 71) se negociaron en 2025.** Esto indica una aceleración significativa del deterioro crediticio.

**Alivios por modelo:**

| Modelo | # Alivios | % |
|--------|----------|---|
| LMM Corto | 23 | 45% |
| LMM Paramétrico | 14 | 27% |
| Small Ticket Paramétrico (Health) | 8 | — |
| Full Underwriting | 8 | 16% |
| Fast Application | 6 | 12% |

**Dato relevante:** 33 de 51 casos revisados por modelos LMM (65%) muestran que la concentración con sus 2 clientes principales era >=50%. **La concentración de clientes es el factor de riesgo número uno en el deterioro del portafolio LMM.**

**Por cosecha:** La mayor concentración de alivios está sobre operaciones fondeadas entre 2020-2023. Las cosechas 2024 y 2025 aún no muestran solicitudes de alivio (buena señal temprana).

### Ticket size pequeño y cartera vencida

**Las operaciones de < $3MM MXN representan:**
- 27% de las operaciones aprobadas
- Solo 9% del monto aprobado
- DLQ del segmento: 14%

**Conclusión de Crédito: ELIMINAR OPERACIONES DE < $3MM MXN.** El esfuerzo operativo es desproporcionado al volumen generado y la tasa de deterioro es la más alta del portafolio.

---

## 7. LOS MODELOS DE CRÉDITO: CÓMO FUNCIONAN

### El flujo de decisión

**¿Quién decide por qué camino meter la operación?** Hoy es por monto, estrictamente:
- **Fast Application:** Hasta $150K USD (~$3MM MXN). Viabilidad en 24 horas. Si brinca la viabilidad, >80-90% se aprueba. Primera línea de suscripción aprueba directamente (no sube a comité salvo exposición previa)
- **Paramétrico:** Hasta $500K USD (~$10MM MXN). Ticket promedio del segmento. Similar al Fast pero con estados financieros adicionales y relación patrimonial
- **Estudio Corto:** Hasta $1MM USD (~$20MM MXN). Ya incluye cuestionario de crédito, entrevista con el cliente, validaciones adicionales
- **Estudio Full:** Sin tope. Análisis completo tipo Core

### Documentos requeridos por modelo

**Fast Application — Hand Off 1 (viabilidad):**
- Da Vinci (extracción fiscal vía CIEC — el cliente firma una liga, toma 2-3 minutos)
- Estados de cuenta bancarios
- Buró de crédito (se genera automáticamente con Da Vinci)
- Reporte de visita (formato del originador)
- Pricing Summary y tabla de amortización
- EVAL (evaluación de activos por Asset Management)

**Paramétrico — adicional al Fast:**
- Estados financieros (la diferencia clave vs. Fast Application)
- Todo lo demás igual al Fast

**El "Predictivo" — herramienta de pre-calificación:**
Es un Excel con inputs básicos donde el originador puede meter 5 datos de su entrevista y obtener una señal de semáforo (verde/amarillo/rojo) sobre si la operación tiene patas o no. Se les dio como "First Pass" para que no pierdan tiempo en operaciones que van a fallar.

**Cita de Federico:**
> "Técnicamente consiguiendo estos documentos, hasta lo podría correr el originador, o al menos como un pre para saber qué onda. De hecho, el originador tiene una cosa que le llamamos 'predictivo' — subes 5 cosas de tu entrevista y te dice más o menos si tiene patas o no tiene patas."

### Cuándo cambian de carril

Las operaciones migran de Fast App/Paramétrico a Corto cuando:
- El modelo brinca por apalancamiento alto, falta de garantía personal, o cualquier variable fuera de rango
- El originador quiere pelear la operación: "oye, pero si hablamos con el cliente para preguntarle..." → ya no es 24 horas, ya es agenda cita, cuestionario, entrevista, ida y vuelta
- No es que cambien de ticket o formato — el expediente "evoluciona" agregando documentos adicionales

**Federico sobre la viabilidad del Fast/Paramétrico:**
> "De las operaciones que brincan viabilidad en Fast App y Paramétrico, yo te podría decir que arriba del 90% se termina aprobando. Ya es muy pocas las que brincan viabilidad y luego se caen. Si sí han brincado, sí, pero son muy pocas."

---

## 8. LA POSICIÓN DE LA DIRECCIÓN

### Gerardo Biagi (Linzor Capital — Accionista)
Posición: Hacer un deep dive en las variables. Quiere entender, del portafolio en cartera vencida, cuáles son las variables que realmente están impactando y cuáles no. Pidió una regresión del portafolio para revisitar el modelo y ver si está capturando de más o de menos.

> Gerardo fue más: "oye, pues yo creo que vale hacer un estudio, una regresión del portafolio, y ver pues cuáles son las variables que realmente lo están impactando y cuáles no, para revisitar el modelo y ver si el modelo está capturando todo o si está capturando de más o está capturando de menos."

### Juan Pablo Loperena (Director General)
Posición: Más radical. Propuso un modelo simplificado que solo use buró de crédito + estados de cuenta bancarios. Su lógica: "si veo sus flujos en el estado de cuenta bancaria y en el buró se porta bien, a lo mejor le puedes hacer algo ahí más rápido."

> "Juan Pablo planteó: ¿por qué no hacemos un modelo en el cual lo tenemos como base únicamente estados de cuenta bancarios y buró? Corre con eso la simulación y dime qué te hubiera aprobado contra lo que actualmente estás aprobando. A lo mejor resulta que con estos documentos me da 95% de confianza y le podría prestar hasta $6MM en 5 minutos."

### Fernando Garza (Director de Riesgo)
Posición: Alineado con Federico. No es un tema de moverle al modelo.

> "Fer está muy claro: abrir la llave de los modelos no es la solución. Que te cambie el apalancamiento de 3 a 4, que el FCC ya no sea de 1 sino de 0.9, que te diga que el buró te lo puedo poner hasta box X — eso no va a ser el breakthrough."

---

## 9. EL ARGUMENTO NUMÉRICO: ¿CUÁNTO VALE ABRIR LA LLAVE?

### El cálculo que importa

| Concepto | 2025 |
|----------|------|
| Total oportunidades dictaminadas | 351 |
| Oportunidades aprobadas | 236 ($2,831MM) |
| Oportunidades rechazadas/withdrawn | 119 ($1,525MM) |
| De las cuales, rechazadas por modelo (Fast + Paramétrico) | **48 ($245MM)** |
| **% que representan los rechazos por modelo vs. total rechazado** | **40% en #, 16% en $** |

### Si abres la llave al máximo (Escenario 5)

Del universo de 48 rechazos por modelo ($245MM):
- **Rescatas ~50% en número** → ~24 operaciones
- **Rescatas ~32% en monto** → ~$78MM
- Pero de esos $78MM, no todos van a fondear (ratio fondeado/aprobado es 55%)
- **Fondeo incremental realista: ~$43MM**

**$43MM adicionales sobre una meta de $1,176MM (LMM Iniciativa 2026) = +3.7%.** Eso no te lleva del 1x al 2x.

### La otra mitad: rechazos por estudio (Corto + Full)

| Concepto | 2025 |
|----------|------|
| Rechazos NO por modelo (Corto + Full + Withdrawn) | ~71 operaciones / ~$1,280MM |
| De estos, ¿cuántos son rechazos de Crédito vs. retiros comerciales? | Mixto — muchos son retiros donde el cliente nunca contestó, perdió interés, o contrató por otro lado |

**Federico:** "Una parte importante de esos rechazos/withdrawn son oportunidades que retiró el equipo comercial. No forzosamente las rechacé yo. Lo que sucede es que se mandó el cuestionario y nunca contestaron, nunca regresaron. No sabemos si el cliente perdió interés o contrató por otro lado."

### La conclusión de Federico sobre la apertura de riesgo

> "O sea, darte una solución única para que dijeras 'oye, si te abro la llave, te hago la puerta más grande, le vamos a dar la vuelta a esto' — no exactamente. Podremos hacer más flexible el modelo en algunos casos, sí. Podemos decir 'oye, te doy que el modelo te apruebe líneas más grandes', también lo puedo hacer. Pero eso no te va a solucionar el problema de fondo."

> "¿Dónde está la carnita? Necesitamos tener un pipeline mucho más robusto. En el prediagnóstico, sí me dio mucho eso: andan bien bajitos en citas, no están usando Salesforce, no está clara la agenda de qué es lo que van a hacer. Es un hecho que hay algo más ahí que tenemos que trabajar."

---

## 10. OPORTUNIDADES IDENTIFICADAS Y PROPUESTAS

### Lo que SÍ se puede hacer con los modelos (quick wins de riesgo)

1. **Subir el tope del Fast Application:** Están haciendo una revisión para llevarlo a un monto más grande. Si el ticket promedio LMM es $12M, tener el Fast App en $3M ($150K USD) deja al 80% de las operaciones fuera del canal más rápido

2. **Subir el tope del Paramétrico:** De $500K USD a $600K+ USD para capturar el 80% de los deals en el canal diseñado para el segmento. Hoy la mayoría de las operaciones brincan a Corto no por riesgo, sino por monto

3. **Aceptar MOB 2-3 con explicación:** En los estudios Corto y Full, flexibilizar el criterio de atrasos en buró. Si ves un atraso histórico de 2-3 meses pero con explicación documentada y mitigantes, aceptarlo y señalarlo como riesgo en lugar de rechazar

4. **Eliminar operaciones < $3MM:** Representan 27% de las operaciones pero solo 9% del monto, con DLQ de 14%. No justifican el costo operativo

### Lo que propone Juan Pablo (más disruptivo)

5. **Modelo simplificado Buró + Flujo bancario:** Simular cuántas operaciones se hubieran aprobado con solo buró de crédito y estados de cuenta bancarios. Si el resultado es >90% de coincidencia con el modelo actual, implementar como canal express

### Lo que propone Biagi (más analítico)

6. **Regresión del portafolio:** Análisis estadístico de las variables del modelo vs. la cartera vencida real para identificar cuáles variables son realmente predictivas de deterioro y cuáles agregan fricción sin valor predictivo. **Usar inteligencia artificial para este análisis.**

### La propuesta consolidada para el proyecto LCG

7. **Revisar cuáles son las variables a retar para abrir la llave de riesgo, y medir la influencia de cada variable contra la mora.** Esto es lo que Juan Pablo pidió que se incluya en la propuesta del proyecto.

---

## 11. DATOS ADICIONALES: TICKET SIZE Y PRODUCTIVIDAD DE CRÉDITO

### El debate del ticket size

- Ticket promedio LMM Iniciativa 2025: $8.9M MXN
- Ticket promedio equipo Core (SAC/Eduardo): ~$20M MXN
- Meta 2026: subir a $12M MXN

**Federico sobre la distribución:** "Lo que vimos en 2025 fue que el 50-60-70% de las operaciones está cayendo entre $3M y $6M MXN, y traes unas colas grandes que hacen que el promedio se mueva a $8.9M. Cuando ves el histograma, no es una distribución normal — es una campana cargada a la izquierda con colas a la derecha."

**El equipo SWAT** (estructuraciones grandes a tasas LMM) puede estar influyendo el promedio hacia arriba. Si SWAT está incluido en las estadísticas, el ticket promedio "real" de LMM Iniciativa puro es probablemente menor a $8.9M.

### Productividad del equipo de suscripción

**Equipo de Estudio Corto y Full (Lorena + equipo):**
- ~5 analistas de crédito
- Distribución por nivel de expertise: operaciones más robustas/grandes → Juan Pablo, Fernanda, Angélica. Operaciones más chicas → Andrea y otras más junior
- El % de aprobación/rechazo por analista individual no se mide formalmente ("te podría sacarlo, la información sí está, pero con pocas transacciones cualquier deal grande te mueve mucho el número")
- Federico reconoce que es un análisis que se puede hacer pero que con el volumen actual (~100 operaciones/año entre 5 analistas) no sería estadísticamente robusto

---

## 12. CONTEXTO: LA DISCUSIÓN CON JP Y BIAGI

**¿Cuándo se discutió esto?** Relativamente reciente — principios de 2026. Con Juan Pablo, Gerardo Biagi, Orlando. Maurizzio Piva (Comercial) posiblemente no estuvo presente.

**El saque del estudio fue:** Juan Pablo y Biagi querían entender si se podía abrir la llave para acelerar el crecimiento. El ejercicio demostró que la apertura de modelos genera un upside marginal (~$100-200MM en el mejor caso) que no resuelve el gap del 2x-3x.

**La conclusión compartida por todos los directivos:** El breakthrough no está en los modelos de crédito. Está en la generación de pipeline comercial. Por eso se contrató a LCG.

---

*Documento preparado a partir del transcript de la entrevista y la presentación "Revisión Modelos LMM 2025" de Crédito Engen. Para uso interno del equipo de proyecto ENGEN + LCG.*
