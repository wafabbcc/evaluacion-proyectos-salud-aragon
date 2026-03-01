# DOCUMENTACIÓN COMPLETA - EVALUACIÓN PROYECTOS MEJORA CALIDAD
## Servicio Aragonés de Salud

---

## ÍNDICE

1. [Estructura Oficial Proyectos](#estructura-oficial)
2. [Criterios Evaluación Detallados](#criterios-detallados)
3. [Rúbricas Completas 1-10](#rubricas-completas)
4. [Casos Especiales y Protocolo](#casos-especiales)
5. [Ejemplos Genéricos](#ejemplos)
6. [FAQ - Preguntas Frecuentes](#faq)

---

## 1. ESTRUCTURA OFICIAL PROYECTOS {#estructura-oficial}

### FASES DEL PROYECTO

```
AÑO 0: PROYECTO INICIAL
├─ Define problema, objetivos, actividades, indicadores
└─ Establece estándares 1ª Memoria y Memoria Final

AÑO 1: MEMORIA SEGUIMIENTO (Intermedia)
├─ Evalúa primer año
├─ Compara vs Estándar 1ª Memoria
└─ Documento autocontenido

AÑO 2: MEMORIA FINAL
├─ Evalúa proyecto completo (2 años)
├─ Compara vs Estándar Memoria Final
├─ Incluye sección RESUMEN (autogenerada)
└─ Campo adicional: Sostenibilidad
```

### PROYECTO INICIAL - Campos Obligatorios

#### Identificación
- Tipo proyecto
- Sector Sanitario
- Ámbito (AP, Hospitalario, Mixto)
- Centro de Salud / Hospital
- Servicio/Unidad

#### Análisis
- **Situación actual:** Descripción problema, datos basales
- **Análisis de causas:** Causas raíz identificadas (diagrama Ishikawa, 5 porqués, etc.)

#### Objetivos
- **Objetivos SMART:** Específicos, medibles, alcanzables, relevantes, temporales
- Deben incluir cifras concretas (%, nº, plazo)

#### Actividades
Cada actividad tiene:
- Descripción de la actividad
- Fecha Prevista Inicio
- Fecha Prevista Fin
- Responsable
- Aclaraciones (opcional)

**Clasificación temporal:**
- Actividades año 1: Fecha fin ≤ 12 meses
- Actividades año 2: Fecha fin > 12 meses

#### Indicadores de Alcance

**Definición:**
- Numerador (qué se cuenta)
- Denominador (sobre qué población)
- Fuente de datos (específica: OMI-AP, historia clínica, registro adhoc...)
- Observaciones

**Estándares:**
- Estándar 1ª Memoria: Valor desde - Valor hasta (ej. 50.00-75.00%)
- Estándar Memoria Final: Valor desde - Valor hasta (ej. 75.00-100.00%)

**Ejemplos alcance:**
- % profesionales que reciben formación
- % población diana cubierta con nuevo servicio
- % registros cumplimentados en OMI-AP

#### Indicadores de Impacto

**Misma estructura que Alcance**

**Ejemplos impacto:**
- % reducción caídas en residencia
- % pacientes diabéticos con HbA1c <7%
- Puntuación media calidad vida (escala validada)
- % reducción reingresos a 30 días

#### Otros
- Recursos necesarios
- Línea estratégica del centro
- Población diana
- Equipo de trabajo

---

### MEMORIA SEGUIMIENTO - Estructura

#### Actividades
**Clasificación:**
1. **Realizadas:** Fecha Real Inicio / Fecha Real Fin
2. **En marcha:** Fecha Real Inicio / Fecha Prevista Fin
3. **No iniciadas:** Fecha Prevista Inicio / Fecha Prevista Fin
4. **Nuevas:** Actividades añadidas no previstas en Proyecto Inicial

**Información adicional:** Texto libre para explicar desviaciones, barreras, facilitadores

#### Indicadores Alcance
Para cada indicador:
- Numerador (valor numérico)
- Denominador (valor numérico)
- Resultado (calculado o introducido)
- Fecha Inicio medición
- Fecha Fin medición
- **Nivel de cumplimiento (0-10):** CALCULADO AUTOMÁTICAMENTE por plataforma
- Información adicional

**Cálculo automático Nivel cumplimiento:**
```
Nivel = ((Resultado - Valor_desde) / (Valor_hasta - Valor_desde)) × 10

Ejemplos:
- Resultado 82.86%, Estándar 50-100%: ((82.86-50)/(100-50))×10 = 6.6
- Resultado ≥ Valor_hasta: Nivel = 10.0 (tope)
- Resultado < Valor_desde: Nivel = 0.0
- Sin datos: "Sin datos"
```

#### Indicadores Impacto
Misma estructura que Alcance

#### Lecciones Aprendidas
- Texto libre
- ¿Qué ha funcionado bien?
- ¿Qué barreras se han encontrado?
- ¿Qué facilitadores?
- ¿Qué se modificaría para proyectos futuros?

#### Equipo
- Actualización miembros del equipo

---

### MEMORIA FINAL - Estructura

**Igual que Memoria Seguimiento + adicionales:**

#### Campo adicional
**Información adicional sobre sostenibilidad y capacidad de extensión**
- ¿Se pueden seguir monitorizando?
- ¿Se mantendrán los cambios?
- ¿Plan de continuidad?
- ¿Posibilidad de extensión a otros centros?

#### Sección RESUMEN (autogenerada por plataforma)
- Tabla consolidada actividades (marca S-Seguimiento, F-Final)
- Comparativa indicadores Seguimiento vs Final
- Lecciones aprendidas consolidadas
- Equipo

---

## 2. CRITERIOS EVALUACIÓN DETALLADOS {#criterios-detallados}

### CRITERIO 1: RELEVANCIA DE LAS ACTIVIDADES

#### Definición Oficial
> "Impacto potencial en [adecuación de la] práctica clínica, calidad de vida de los pacientes y eficiencia"

#### Concepto Clave
**NO evalúa:**
- Si se hicieron las actividades (eso es Alcance)
- Los resultados obtenidos (eso es Impacto)

**SÍ evalúa:**
- PERTINENCIA: ¿Son las actividades ADECUADAS para resolver el problema?
- COHERENCIA: ¿Hay relación lógica Análisis causas → Actividades elegidas?
- BASE CIENTÍFICA: ¿Hay evidencia que sustenta las actividades?
- POTENCIAL: ¿Pueden mejorar práctica clínica, calidad vida pacientes y eficiencia?

#### Dimensiones a Valorar

**a) Impacto potencial en PRÁCTICA CLÍNICA / ADECUACIÓN TÉCNICA:**
- ¿Mejoran adherencia a guías clínicas?
- ¿Reducen variabilidad no justificada?
- ¿Aumentan seguridad clínica?
- ¿Mejoran coordinación asistencial?

**b) Impacto potencial en CALIDAD DE VIDA DE PACIENTES:**
- ¿Reducen síntomas, dolor, complicaciones?
- ¿Aumentan autonomía, capacidad funcional?
- ¿Mejoran experiencia asistencial?
- ¿Empoderan en autocuidado?

**c) Impacto potencial en EFICIENCIA:**
- ¿Reducen uso inadecuado de recursos?
- ¿Evitan ingresos, reingresos, visitas innecesarias?
- ¿Reducen pruebas redundantes?
- ¿Optimizan uso fármacos, material?

#### Proceso de Evaluación

**PASO 1: Revisar Análisis de Causas (Proyecto Inicial)**
- ¿Están identificadas causas raíz?
- ¿Metodología adecuada? (Ishikawa, 5 porqués, Pareto...)
- ¿Hay datos que sustentan las causas?

**PASO 2: Revisar Actividades Planificadas**
- ¿Cada actividad ataca una causa raíz?
- ¿O son actividades genéricas sin relación?

**PASO 3: Buscar Base Científica**
- ¿Se citan guías clínicas, protocolos, estudios?
- ¿Se mencionan buenas prácticas?
- ¿Hay benchmarking con otros centros?

**PASO 4: Valorar Potencial de Impacto**
- Si se ejecutan bien, ¿pueden mejorar las 3 dimensiones?
- ¿O solo abordan 1-2 dimensiones?
- ¿Impacto alto, medio o bajo?

**PASO 5: Aplicar Rúbrica (ver sección 3)**

#### Ejemplos

**ALTA RELEVANCIA (9-10):**
```
Problema: Alta tasa caídas en residencia (20% residentes/año)
Análisis causas:
- Iluminación insuficiente pasillos (mediciones lux <100)
- Falta valoración riesgo individual (0% valorados)
- Personal sin formación prevención caídas (encuesta conocimientos)

Actividades:
1. Mejorar iluminación pasillos (lux >200)
2. Formar 100% personal (curso acreditado)
3. Valorar riesgo 100% residentes (escala Downton)
4. Implementar medidas personalizadas según riesgo

Base científica: Guía NICE prevención caídas, protocolo SECPAL

Potencial:
- Práctica clínica: Valoración sistemática (↑adecuación)
- Calidad vida: Reducción caídas (↓complicaciones)
- Eficiencia: Prevención > tratamiento fracturas (↓costes)

Coherencia: EXCELENTE (cada actividad → causa raíz)
Relevancia: 9.5/10
```

**RELEVANCIA MEDIA (5-6):**
```
Problema: Pacientes hipertensos mal controlados
Análisis causas: [No se presenta análisis estructurado]

Actividades:
1. Revisar pacientes con TA >140/90
2. Actualizar tratamiento según guías
3. Dar consejos estilo de vida

Base científica: Se menciona "guías" pero no se concretan

Potencial:
- Práctica clínica: Revisión + adherencia guías (potencial medio)
- Calidad vida: Control TA (potencial medio)
- Eficiencia: Prevención complicaciones (potencial medio)

Coherencia: MEDIA (actividades genéricas, no hay análisis causas)
Relevancia: 5.5/10
```

---

### CRITERIO 2: RESULTADOS INDICADORES ALCANCE

#### Definición Oficial
> "El grado de ejecución de las acciones planificadas será valorado a través de indicadores de alcance que miden el grado de extensión de las acciones en la población o los profesionales diana: % profesionales que han recibido formación, frecuentación, población cubierta con el nuevo servicio, etc."

#### Concepto Clave
Alcance = COBERTURA / EJECUCIÓN

**Pregunta:** ¿Hicimos lo planificado? ¿A cuántos llegamos?

**NO es:** Resultado de salud o impacto (eso es Criterio 3)

#### Ejemplos Típicos Alcance
- % profesionales formados
- % población diana incluida en programa
- % registros cumplimentados
- Nº sesiones clínicas realizadas / planificadas
- % espirometrías realizadas a fumadores

#### Proceso de Evaluación

**PASO 1: EXTRAER "Nivel cumplimiento (0-10)" de cada indicador Alcance**
```
Ejemplo Memoria Final:
Indicador Alcance 1: Nivel cumplimiento = 10.0
Indicador Alcance 2: Nivel cumplimiento = 10.0
```

**PASO 2: CALCULAR promedio base**
```
Promedio = (10.0 + 10.0) / 2 = 10.0
```

**PASO 3: VALIDAR coherencia técnica**

a) **Coherencia matemática:**
```
¿Resultado = Numerador / Denominador?
Ejemplo:
Num: 95, Denom: 100 → Resultado esperado: 95%
Si Resultado reportado: 82% → INCOHERENCIA
```

b) **Fuente de datos:**
```
¿Está especificada? (OMI-AP, historia, registro adhoc, base datos...)
Si dice "registros" sin más → Vaga, penalizar -0.5
```

c) **Fechas:**
```
¿Coherentes con periodo evaluado?
Intermedia: Fechas dentro primeros 12 meses
Final: Fechas cubren periodo completo o reciente
```

**PASO 4: VERIFICAR actividades correspondientes**
```
Si indicador mide "% formados":
¿Hay actividad "Formar profesionales" REALIZADA?
Si actividad NO INICIADA pero indicador con datos → INCOHERENCIA
```

**PASO 5: APLICAR penalizaciones**

| Problema | Penalización |
|----------|--------------|
| "Sin datos" en un indicador (Memoria Final) | -3 puntos |
| >50% indicadores sin datos | Nota máx = 5/10 |
| Actividades "No iniciadas" >20% del total | -1 punto |
| Incoherencia Num/Denom ≠ Resultado | -0.5 puntos |
| Fuente datos vaga/ausente | -0.5 puntos |
| Fechas incoherentes | -0.5 puntos |

**PASO 6: APLICAR TOPE 9.5**
```
Nota_final = min(promedio_ajustado, 9.5)
```

#### Casos Especiales

**a) Indicador "Sin datos" justificado:**
```
Info adicional: "No se pudo medir por [razón externa, COVID, fallo sistema...]"
→ Penalización menor: -1 punto en vez de -3
```

**b) Resultado >100% (ratio):**
```
Indicador: "Nº errores de medicación / 1000 pacientes-día"
Resultado: 2.5 (es ratio, puede ser cualquier valor)
→ VÁLIDO, no penalizar
```

**c) Cobertura <95% en Memoria Final:**
```
Si Resultado <95% y no hay justificación:
Nota máx = 8/10 (no es excelencia sin alta cobertura)
```

---

### CRITERIO 3: RESULTADOS INDICADORES IMPACTO

#### Definición Oficial
> "Los resultados alcanzados de los proyectos se medirán a través de indicadores de impacto. Estos indicadores se centran en demostrar los efectos del proyecto en el sistema sanitario (mejoras en la práctica clínica, eficiencia,...) y en los pacientes en términos de salud, calidad de vida y autoeficacia"

#### Concepto Clave
Impacto = RESULTADO / EFECTO

**Pregunta:** ¿Qué cambió? ¿Mejoraron los pacientes o el sistema?

**NO es:** Actividad realizada (eso es Alcance)

#### Dimensiones del Impacto

**SISTEMA SANITARIO:**
1. Mejoras en práctica clínica:
   - % adherencia a guías clínicas
   - % adecuación prescripción
   - Reducción variabilidad no justificada

2. Eficiencia:
   - % reducción reingresos
   - Reducción estancia media
   - % reducción pruebas redundantes
   - Ahorro costes (farmacia, material...)

**PACIENTES:**
1. Salud (resultados clínicos):
   - % pacientes con control metabólico (HbA1c, TA, LDL...)
   - % reducción caídas, úlceras, infecciones
   - Reducción complicaciones, mortalidad

2. Calidad de vida:
   - Puntuación escalas validadas (SF-12, EQ-5D...)
   - Reducción dolor (EVA)
   - Mejora capacidad funcional (Barthel, Lawton...)

3. Autoeficacia:
   - % pacientes autónomos autocuidado
   - Adherencia terapéutica
   - Satisfacción con atención

#### Validación Crítica: ¿Es Realmente Impacto?

**✅ VÁLIDOS como indicadores IMPACTO:**
```
- % reducción caídas
- % pacientes diabéticos HbA1c <7%
- Puntuación media calidad vida
- % reducción reingresos 30 días
- % pacientes autónomos manejo insulina
- Reducción estancia media
- % adecuación prescripción antibióticos
```

**❌ NO VÁLIDOS (son ALCANCE, miden actividad):**
```
- % profesionales formados
- Nº sesiones educativas realizadas
- % registros OMI-AP cumplimentados
- % protocolos elaborados
- % pacientes incluidos en programa
```

**⚠️ ZONA GRIS (depende definición):**
```
"% pacientes con espirometría realizada"
→ Si mide ACTIVIDAD: Alcance
→ Si mide "% diagnósticos EPOC por espirometría": Impacto (mejora práctica)
```

#### Proceso de Evaluación

**PASO 1: EXTRAER "Nivel cumplimiento (0-10)" de cada indicador Impacto**

**PASO 2: VALIDAR que miden IMPACTO REAL**
```
Para cada indicador:
a) ¿Mide salud, calidad vida, autoeficacia? → IMPACTO ✅
b) ¿Mide mejora práctica clínica, eficiencia? → IMPACTO ✅
c) ¿Solo mide actividad, registro, formación? → ALCANCE ❌

Si es ALCANCE → RECLASIFICAR:
- No usar su "Nivel cumplimiento" para Criterio 3
- Incluir en cálculo Criterio 2 (Alcance)
- Avisar al usuario en "Observaciones técnicas"
```

**PASO 3: CALCULAR promedio de indicadores VÁLIDOS**

**PASO 4: VERIFICAR comparativa PRE/POST**
```
Buscar en "Información adicional" o "Análisis situación":
- Datos basales (pre-intervención)
- Datos actuales (post-intervención)
- % cambio

Si NO hay comparativa explícita:
→ Nota máx = 8/10 (no se demuestra cambio atribuible)
```

**PASO 5: APLICAR penalizaciones**

| Problema | Penalización |
|----------|--------------|
| 100% indicadores "Sin datos" (Memoria Final) | Nota = 0 |
| >50% indicadores sin datos | Nota máx = 5/10 |
| Sin comparativa pre/post | Nota máx = 8/10 |
| Indicador reclasificado como Alcance | -1 punto |
| Solo mide registro/actividad | Reclasificar + -1 punto |

**PASO 6: APLICAR TOPE 9.5**

#### Ejemplos

**IMPACTO ALTO (9-10):**
```
Indicador: % reducción caídas en residencia
Datos:
- Basal (pre): 20% residentes con ≥1 caída/año
- Actual (post): 7% residentes con ≥1 caída/año
- Reducción: 65%

Nivel cumplimiento (plataforma): 8.5/10

Validación:
✅ Mide resultado salud real (caídas)
✅ Comparativa pre/post clara
✅ Cambio clínicamente significativo

Nota: 8.5 → Aplicar tope 9.5 → Nota final 8.5
```

**IMPACTO BAJO (3-4) - Indicador mal clasificado:**
```
Indicador clasificado como "Impacto": % profesionales formados

Nivel cumplimiento (plataforma): 10.0

Validación:
❌ Solo mide actividad, NO resultado paciente/sistema
→ RECLASIFICAR como Alcance

Acción:
- No usar en Criterio 3
- Incluir en Criterio 2
- Avisar: "Indicador reclasificado de Impacto a Alcance"

Si solo había este indicador de impacto:
Nota Criterio 3 = 3/10 (no hay indicadores impacto válidos)
```

---

### CRITERIO 4a: PLAN DE COMUNICACIÓN (Memoria Intermedia)

#### Definición Oficial
> "Plan dirigido a profesionales de la unidad, de otras unidades, pacientes, población, consejo de salud..."

#### Concepto Clave
Comunicación = DIFUSIÓN del proyecto y sus resultados

**Públicos objetivo (5 grupos):**
1. Profesionales de la unidad
2. Profesionales de otras unidades
3. Pacientes
4. Población general
5. Consejo de salud

#### Problema: NO HAY CAMPO EXPLÍCITO

**Dónde buscar evidencia:**

**a) "Información adicional actividades":**
```
Ejemplo texto libre:
"Se han realizado 3 sesiones clínicas para presentar el proyecto 
al equipo. Se elaboró cartel informativo para sala de espera. 
Se presentó en reunión Consejo de Salud en octubre."
```

**b) Actividades de difusión:**
```
- Actividad: "Sesión formativa equipo" → Público 1 ✓
- Actividad: "Cartel informativo pacientes" → Público 3 ✓
- Actividad: "Presentación consejo salud" → Público 5 ✓
- Actividad: "Difusión intranet sector" → Público 2 ✓
```

**c) "Lecciones aprendidas":**
```
"La difusión del proyecto mejoró tras incluir a enfermería en sesiones..."
```

#### Evaluación

**DIMENSIÓN 1: Nº PÚBLICOS ALCANZADOS (50% de la nota)**

| Públicos | Puntos |
|----------|--------|
| 0 públicos | 0-2 |
| 1 público (solo equipo) | 3-4 |
| 2 públicos | 5-6 |
| 3 públicos | 7-8 |
| 4-5 públicos | 9-10 |

**DIMENSIÓN 2: CANALES UTILIZADOS (30% de la nota)**

| Canales | Puntos |
|---------|--------|
| Ninguno identificable | 0-2 |
| 1 canal (ej. solo oral) | 3-5 |
| 2 canales (ej. oral + escrito) | 6-8 |
| 3+ canales (oral + escrito + digital) | 9-10 |

**Ejemplos canales:**
- Presencial: sesiones clínicas, reuniones, talleres
- Escrito: carteles, trípticos, informes
- Digital: intranet, email, presentaciones

**DIMENSIÓN 3: EVIDENCIA DE EJECUCIÓN (20% de la nota)**

| Evidencia | Puntos |
|-----------|--------|
| Solo plan, sin evidencia ejecución | 0-3 |
| Mención genérica | 4-6 |
| Evidencia clara (fechas, nº asistentes) | 7-10 |

**NOTA FINAL = (Dim1×0.5) + (Dim2×0.3) + (Dim3×0.2)**

#### Rúbrica Integrada

**9-10 EXCELENTE:**
- Plan multi-público (≥4 grupos)
- Canales diversos (presencial + escrito + digital)
- Evidencia clara ejecución (fechas, asistentes, materiales)
- Comunicación bidireccional (feedback recogido)

**7-8 BUENO:**
- ≥3 públicos alcanzados
- ≥2 canales utilizados
- Evidencia suficiente ejecución
- Comunicación planificada

**5-6 ACEPTABLE:**
- 2 públicos (equipo + otro)
- 1-2 canales
- Evidencia básica
- Comunicación reactiva

**3-4 INSUFICIENTE:**
- Solo 1 público (equipo)
- 1 canal
- Mención anecdótica
- Sin planificación

**1-2 AUSENTE:**
- No hay plan de comunicación identificable
- No hay evidencia de difusión

---

### CRITERIO 4b: SOSTENIBILIDAD Y CAPACIDAD DE EXTENSIÓN (Memoria Final)

#### Definición Oficial (3 Preguntas)

**1. ¿Se pueden MONITORIZAR resultados?**
> "(indicadores claros, bien definidos, el procedimiento de obtención de datos es realista)"

**2. ¿Se MANTENDRÁN cambios una vez finalizado?**
> (Implícito: plan de continuidad, integración en práctica)

**3. ¿Se documentan LECCIONES APRENDIDAS?**
> (Explícito en la definición)

#### Dónde Buscar

**Campo principal:**
"Información adicional sobre sostenibilidad y capacidad de extensión"

**Campo secundario:**
"Lecciones aprendidas"

#### 3 Componentes (Pesos)

**A) MONITORIZACIÓN POST-PROYECTO (40%)**

**Qué evaluar:**
1. **Indicadores bien definidos:**
   - Numerador claro (sin ambigüedades)
   - Denominador específico
   - Fuente de datos concreta (no vaga)

2. **Realismo obtención datos:**
   - ¿Se pueden obtener SIN el proyecto?
   - ¿No dependen de recursos extraordinarios?
   - ¿Están integrados en sistemas rutinarios? (OMI-AP, historia...)

**Rúbrica Componente A:**

| Nota | Criterio |
|------|----------|
| 9-10 | Indicadores muy bien definidos (Num/Denom/Fuente específica). Obtención datos muy realista, integrada en OMI-AP o historia. No depende de registros adhoc ni personal extra |
| 7-8 | Indicadores bien definidos. Obtención realista con pequeño esfuerzo adicional (ej. consulta periódica base datos) |
| 5-6 | Indicadores básicamente definidos. Obtención requiere esfuerzo medio (ej. registro manual periódico) |
| 3-4 | Indicadores vagos. Obtención poco realista (depende personal dedicado, registro complejo) |
| 1-2 | Indicadores mal definidos o ausentes. Obtención no realista (requiere proyecto nuevo) |

**B) MANTENIMIENTO CAMBIOS (40%)**

**Qué evaluar:**
1. **Plan de continuidad explícito:**
   - ¿Hay plan escrito?
   - ¿Responsables asignados?
   - ¿Periodicidad definida?

2. **Integración en práctica habitual:**
   - ¿Actividades integradas en agenda?
   - ¿Protocolos/guías actualizados?
   - ¿Formación incorporada a plan formación continua?

3. **Independencia de recursos extraordinarios:**
   - ¿Funciona con plantilla habitual?
   - ¿No depende de financiación especial?
   - ¿Material/equipamiento ya disponible?

**Rúbrica Componente B:**

| Nota | Criterio |
|------|----------|
| 9-10 | Plan continuidad muy detallado (responsables, periodicidad). Totalmente integrado en rutina (agenda, protocolos actualizados). Independiente de recursos extra |
| 7-8 | Plan continuidad claro. Bien integrado. Mínima dependencia recursos adicionales |
| 5-6 | Plan continuidad básico. Parcialmente integrado. Requiere algunos recursos adicionales |
| 3-4 | Plan vago o incompleto. Baja integración. Alta dependencia recursos extra |
| 1-2 | No hay plan continuidad. No integrado. Totalmente dependiente de recursos extraordinarios |

**C) LECCIONES APRENDIDAS (20%)**

**Qué evaluar:**
1. **Campo cumplimentado con sustancia:**
   - ¿Hay contenido relevante?
   - ¿O solo frases genéricas?

2. **Identifica barreras y facilitadores:**
   - ¿Qué dificultó el proyecto?
   - ¿Qué ayudó?
   - ¿Análisis honesto?

3. **Propone mejoras:**
   - ¿Qué se haría diferente?
   - ¿Recomendaciones para otros centros?
   - ¿Aplicabilidad a otros contextos?

**Rúbrica Componente C:**

| Nota | Criterio |
|------|----------|
| 9-10 | Lecciones muy detalladas, específicas. Identifica claramente barreras (técnicas, organizativas, culturales) y facilitadores. Propone mejoras concretas y aplicables |
| 7-8 | Lecciones claras. Identifica barreras y facilitadores principales. Propone mejoras razonables |
| 5-6 | Lecciones básicas. Menciona algunas barreras/facilitadores. Mejoras genéricas |
| 3-4 | Lecciones vagas o muy breves. Barreras/facilitadores poco específicos. Sin mejoras claras |
| 1-2 | Campo ausente o irrelevante. No hay análisis de barreras. Sin propuestas |

#### NOTA FINAL CRITERIO 4b

**Fórmula:**
```
Nota = (Componente_A × 0.4) + (Componente_B × 0.4) + (Componente_C × 0.2)
```

**Aplicar TOPE 9.5**

#### Ejemplo SOSTENIBILIDAD ALTA (9-10)

```
COMPONENTE A - MONITORIZACIÓN:
"Los indicadores están integrados en OMI-AP:
- Nº caídas: registro obligatorio en historia (apartado 'incidencias')
- Nº residentes: censo actualizado automáticamente
Fuente: Extracción automática OMI-AP mensual
Responsable: Enfermera coordinadora (dentro de sus funciones habituales)"
→ Nota A: 9.5/10

COMPONENTE B - MANTENIMIENTO:
"Plan de continuidad:
- Valoración riesgo caídas: integrada en protocolo ingreso residencia
- Revisión semestral: incluida en agenda enfermería
- Formación personal nuevo: incluida en plan acogida
- Comité caídas: reunión trimestral (ya existente, se añade revisión indicador)
No requiere recursos adicionales (material ya adquirido, personal habitual)"
→ Nota B: 9.5/10

COMPONENTE C - LECCIONES:
"Barreras identificadas:
- Resistencia inicial personal auxiliar a cambiar rutinas iluminación
- Dificultad coordinación con mantenimiento para mejora iluminación

Facilitadores:
- Apoyo dirección residencia (clave para asignar presupuesto)
- Formación presencial (mejor que online para personal auxiliar)
- Implicación familia tras presentación en consejo participación

Mejoras para futuros proyectos:
- Involucrar mantenimiento desde fase inicial
- Sesiones formación más breves y repetidas (vs una larga)
- Extensible a otras residencias del sector si se adapta formación a cada plantilla"
→ Nota C: 9.5/10

NOTA FINAL = (9.5×0.4) + (9.5×0.4) + (9.5×0.2) = 9.5
```

---

## 3. RÚBRICAS COMPLETAS 1-10 {#rubricas-completas}

### CRITERIO 1: RELEVANCIA ACTIVIDADES

| Puntuación | Coherencia Análisis-Actividades | Base Científica | Potencial Impacto 3 Dimensiones |
|------------|--------------------------------|-----------------|--------------------------------|
| **10** | Perfecta: cada actividad ataca causa raíz identificada | Guías clínicas citadas, estudios, benchmarking | Alto potencial en práctica clínica, calidad vida Y eficiencia |
| **9** | Excelente: actividades muy coherentes con análisis | Base científica sólida explícita | Alto potencial en 3 dimensiones |
| **8** | Muy buena: coherencia clara | Base científica clara | Alto potencial en 2-3 dimensiones |
| **7** | Buena: coherencia adecuada | Base adecuada mencionada | Potencial claro en 2 dimensiones |
| **6** | Aceptable: coherencia básica | Base mencionada genéricamente | Potencial en 1-2 dimensiones |
| **5** | Suficiente: algo de coherencia | Poca base explícita | Potencial limitado, 1 dimensión |
| **4** | Insuficiente: poca coherencia | Base ausente o muy vaga | Potencial bajo o poco claro |
| **3** | Deficiente: coherencia muy débil | Sin base identificable | Potencial muy bajo |
| **2** | Muy deficiente: casi sin coherencia | Sin base científica | Potencial casi nulo |
| **1** | Ausente: sin relación análisis-actividades | Sin base | Sin potencial identificable |

**TOPE: 9.5** (aplicar tras ajustes)

---

### CRITERIO 2: RESULTADOS ALCANCE

**Base: Promedio "Nivel cumplimiento (0-10)" de indicadores Alcance**

| Ajuste | Condición | Modificación |
|--------|-----------|-------------|
| **Penalización datos** | "Sin datos" un indicador (Final) | -3.0 puntos |
| **Penalización datos** | >50% indicadores sin datos | Nota máx = 5.0 |
| **Penalización ejecución** | Actividades "No iniciadas" >20% | -1.0 punto |
| **Penalización técnica** | Incoherencia Num/Denom ≠ Resultado | -0.5 puntos |
| **Penalización técnica** | Fuente datos vaga/ausente | -0.5 puntos |
| **Penalización técnica** | Fechas incoherentes | -0.5 puntos |
| **Tope cobertura** | Resultado <95% sin justificación (Final) | Nota máx = 8.0 |
| **Tope variabilidad** | Siempre | Nota máx = 9.5 |

**Ejemplo cálculo:**
```
Indicador 1: Nivel = 10.0
Indicador 2: Nivel = 8.0
Promedio base = 9.0

Ajustes:
- Incoherencia en Indicador 2: -0.5
Promedio ajustado = 8.5

Tope 9.5: min(8.5, 9.5) = 8.5

NOTA FINAL = 8.5/10
```

---

### CRITERIO 3: RESULTADOS IMPACTO

**Base: Promedio "Nivel cumplimiento (0-10)" de indicadores Impacto VÁLIDOS**

**PASO PREVIO: Validación**

| Tipo de indicador | Acción |
|-------------------|--------|
| Mide salud, calidad vida, autoeficacia | VÁLIDO - usar |
| Mide mejora práctica, eficiencia | VÁLIDO - usar |
| Mide solo actividad, registro, formación | RECLASIFICAR a Alcance |

| Ajuste | Condición | Modificación |
|--------|-----------|-------------|
| **Penalización crítica** | 100% indicadores "Sin datos" (Final) | Nota = 0 |
| **Penalización grave** | >50% indicadores sin datos | Nota máx = 5.0 |
| **Penalización metodológica** | Sin comparativa pre/post | Nota máx = 8.0 |
| **Penalización reclasificación** | Indicador reclasificado como Alcance | -1.0 punto |
| **Tope variabilidad** | Siempre | Nota máx = 9.5 |

**Casos especiales:**

```
Si TODOS los indicadores clasificados como "Impacto" son realmente "Alcance":
→ No hay indicadores impacto válidos
→ Nota = 3.0 (no se demuestra impacto)
→ Avisar: "No se identifican indicadores de impacto válidos. 
           Todos miden actividad/alcance, no resultado."
```

---

### CRITERIO 4a: COMUNICACIÓN (Intermedia)

| Puntuación | Nº Públicos | Canales | Evidencia Ejecución |
|------------|-------------|---------|---------------------|
| **10** | 5 públicos | 3+ canales diversos | Muy detallada (fechas, asistentes, materiales) |
| **9** | 4 públicos | 3 canales | Detallada |
| **8** | 3 públicos | 2-3 canales | Clara |
| **7** | 3 públicos | 2 canales | Suficiente |
| **6** | 2 públicos | 2 canales | Básica |
| **5** | 2 públicos | 1 canal | Mención |
| **4** | 1 público | 1 canal | Anecdótica |
| **3** | 1 público | 1 canal | Muy vaga |
| **2** | Incierto | Incierto | Casi ausente |
| **1** | No identificable | No identificable | Ausente |

**Fórmula:**
```
Nota = (Públicos_puntos × 0.5) + (Canales_puntos × 0.3) + (Evidencia_puntos × 0.2)
```

**TOPE: 9.5**

---

### CRITERIO 4b: SOSTENIBILIDAD (Final)

**3 Componentes independientes, luego combinan**

#### Componente A: MONITORIZACIÓN (40%)

| Puntuación | Definición Indicadores | Realismo Obtención Datos |
|------------|----------------------|--------------------------|
| **10** | Num/Denom/Fuente muy específicos | Integrado OMI-AP/historia, automático |
| **9** | Muy bien definidos | Integrado, extracción sencilla |
| **8** | Bien definidos | Realista, pequeño esfuerzo |
| **7** | Bien definidos | Consulta periódica base datos |
| **6** | Básicamente definidos | Esfuerzo medio (registro manual periódico) |
| **5** | Básicamente definidos | Esfuerzo medio-alto |
| **4** | Algo vagos | Poco realista (personal dedicado) |
| **3** | Vagos | Poco realista (registro complejo) |
| **2** | Muy vagos | No realista (requiere proyecto nuevo) |
| **1** | Ausentes o muy mal definidos | No realista |

#### Componente B: MANTENIMIENTO (40%)

| Puntuación | Plan Continuidad | Integración Práctica | Independencia Recursos |
|------------|------------------|---------------------|----------------------|
| **10** | Muy detallado (responsables, periodicidad, procedimientos) | Total (agenda, protocolos actualizados, formación continua) | Total (plantilla habitual, sin financiación extra) |
| **9** | Muy detallado | Total | Casi total |
| **8** | Detallado | Alta | Alta (mínima dependencia) |
| **7** | Claro | Buena | Buena |
| **6** | Básico | Parcial | Media (algunos recursos adicionales) |
| **5** | Básico | Parcial | Media |
| **4** | Vago | Baja | Baja (alta dependencia) |
| **3** | Muy vago | Baja | Muy alta dependencia |
| **2** | Incompleto | Muy baja | Totalmente dependiente |
| **1** | Ausente | No integrado | Totalmente dependiente |

#### Componente C: LECCIONES APRENDIDAS (20%)

| Puntuación | Cumplimentación | Barreras/Facilitadores | Propuestas Mejora |
|------------|----------------|----------------------|-------------------|
| **10** | Muy detallada, específica | Identifica claramente (técnicas, organizativas, culturales) | Concretas y aplicables |
| **9** | Muy detallada | Identifica claramente | Concretas |
| **8** | Detallada | Identifica bien | Razonables |
| **7** | Clara | Identifica principales | Razonables |
| **6** | Básica | Menciona algunas | Genéricas |
| **5** | Básica | Menciona pocas | Muy genéricas |
| **4** | Vaga | Poco específicos | Poco claras |
| **3** | Muy breve | Muy poco específicos | Ausentes |
| **2** | Casi ausente | Casi ausentes | Ausentes |
| **1** | Ausente | Ausentes | Ausentes |

**Nota Final Criterio 4b:**
```
Nota = (A × 0.4) + (B × 0.4) + (C × 0.2)
Aplicar TOPE 9.5
```

---

## 4. CASOS ESPECIALES Y PROTOCOLO {#casos-especiales}

### CASO 1: Falta Proyecto Inicial

**Situación:** Solo se dispone de Memoria (Seguimiento o Final)

**Protocolo:**
1. **Criterio 1 (Relevancia):**
   - Evaluar con info disponible en Memoria
   - Buscar "Análisis situación" o contexto en info adicional
   - Limitar nota máx = 7.0 (sin análisis causas formal)
   - Señalar en "Observaciones": "Evaluación limitada por ausencia Proyecto Inicial"

2. **Criterios 2 y 3 (Alcance/Impacto):**
   - Evaluar normalmente con datos Memoria
   - No afecta (indicadores están en Memoria)

3. **Criterio 4:**
   - Evaluar normalmente

**Nota global:** Procede normalmente pero señalar limitación

---

### CASO 2: Sin Memoria Seguimiento (solo Proyecto + Final)

**Situación:** Proyecto de 1 año o solo se entregó Memoria Final

**Protocolo:**
1. Evaluar como Memoria Final normal
2. Para contexto, revisar Proyecto Inicial
3. Comparar directamente planificación inicial vs resultados finales
4. No afecta criterios de evaluación

---

### CASO 3: Indicadores sin definir o muy vagos

**Situación:**
```
Indicador: "Mejora del control"
Numerador: -
Denominador: -
Fuente: "Registros"
```

**Protocolo:**
1. **Si es único indicador:**
   - Criterio 2 o 3: Nota = 3.0
   - Razón: No se puede evaluar sin definición clara

2. **Si hay otros indicadores bien definidos:**
   - No incluir el vago en promedio
   - Penalizar: -1 punto en criterio correspondiente
   - Señalar: "Indicador [nombre] excluido por definición vaga"

3. **Recomendar:**
   - Definir Num/Denom/Fuente específica
   - Revisar metodología construcción indicadores

---

### CASO 4: Resultados >100% sin ser ratio

**Situación:**
```
Indicador: % pacientes formados
Resultado: 120%
Tipo: Proporción (debería ser ≤100%)
```

**Protocolo:**
1. **Verificar si es realmente ratio:**
   - Si Denominador NO incluye Numerador → Es ratio (válido >100%)
   - Si Denominador SÍ incluye Numerador → Es proporción (error)

2. **Si es error:**
   - Señalar incoherencia
   - No usar "Nivel cumplimiento" de ese indicador
   - Penalizar: -1 punto
   - Recomendar: "Verificar cálculo Indicador [nombre]. Resultado >100% en proporción indica error."

3. **Si no se puede determinar:**
   - Buscar explicación en "Información adicional"
   - Si no hay → Asumir error y proceder como paso 2

---

### CASO 5: "Sin datos" en todos los indicadores (Final)

**Situación:** Memoria Final con todos indicadores "Sin datos"

**Protocolo:**

**Alcance:**
```
Nota Criterio 2 = 3.0
Razón: No se puede evaluar grado de ejecución
Observación: "No se aportan datos de indicadores de alcance en Memoria Final"
```

**Impacto:**
```
Nota Criterio 3 = 0.0
Razón: No se demuestra impacto
Observación: "No se aportan datos de impacto. No se puede valorar efectividad del proyecto."
```

**Nota global:**
```
Muy afectada (Alcance 35% + Impacto 15% = 50% de la nota con valores bajos)
Probable nota global <5.0
Recomendar: Completar indicadores antes de cerrar proyecto
```

---

### CASO 6: Proyecto extendido >2 años

**Situación:** Proyecto con extensión a 3º año o más

**Protocolo:**
1. Evaluar Memoria Final del año 2 normalmente
2. Si hay "Memoria Extensión" año 3:
   - Revisar para contexto
   - Puede reforzar Sostenibilidad (si hay datos continuidad)
   - Pero evaluar formalmente solo año 2
3. Señalar en observaciones: "Proyecto con extensión a [X] años"

---

### CASO 7: Contradicciones entre Proyecto Inicial y Memoria

**Situación:**
```
Proyecto Inicial: Objetivo "Reducir caídas 30%"
Memoria Final: Objetivo modificado "Reducir caídas 20%"
```

**Protocolo:**
1. **Prioridad:** Usar dato más reciente (Memoria)
2. **Señalar contradicción:**
   - Observaciones: "Objetivo modificado durante ejecución (inicial 30%, final 20%)"
3. **Buscar justificación:**
   - ¿Hay explicación en "Información adicional"?
   - Si sí → Aceptar cambio, no penalizar
   - Si no → Señalar pero no penalizar mucho (-0.5 puntos Relevancia)
4. **Recomendar:**
   - Documentar modificaciones de objetivos en Memoria Seguimiento
   - Justificar cambios metodológicos

---

### CASO 8: Actividades "Nuevas" no previstas

**Situación:** Memoria incluye actividades no planificadas en Proyecto Inicial

**Protocolo:**
1. **Es aceptable:** Proyectos vivos pueden requerir ajustes
2. **Evaluar:**
   - ¿Hay justificación en "Información adicional"?
   - ¿Son coherentes con objetivos?
3. **Criterio 1 (Relevancia):**
   - Si son coherentes y justificadas → No penalizar, incluso valorar positivamente adaptación
   - Si no coherentes → Penalizar -1 punto
4. **Criterio 2 (Alcance):**
   - Incluir en evaluación de ejecución normalmente
5. **Señalar:** "Proyecto incluye [X] actividades nuevas no previstas inicialmente"

---

### CASO 9: Población diana muy pequeña (n<30)

**Situación:**
```
Indicador: % residentes con valoración riesgo caídas
Denominador: 15 residentes
```

**Protocolo:**
1. **NO penalizar por tamaño muestral**
   - Centros pequeños / poblaciones específicas son realidad
   - Regla Oro: reconocer variabilidad asistencial
2. **Verificar:**
   - ¿Denominador = población diana completa?
   - Si sí → Válido
   - Si es muestra → Verificar representatividad
3. **Interpretar resultados con cautela:**
   - Señalar en observaciones: "Población pequeña (n=15), resultados orientativos"
   - No afecta nota si metodología correcta
4. **Valorar positivamente:**
   - Proyectos centros pequeños que hacen seguimiento sistemático

---

### CASO 10: Falta comparativa pre/post en Impacto

**Situación:**
```
Indicador Impacto: % pacientes HbA1c <7%
Memoria Final: Resultado 65%
No hay dato basal
```

**Protocolo:**
1. **Buscar dato basal:**
   - ¿En Proyecto Inicial sección "Análisis situación"?
   - ¿En "Información adicional" Memoria?
   - ¿En Memoria Seguimiento?

2. **Si se encuentra dato basal:**
   - Calcular cambio (ej. basal 40% → final 65% = +25 puntos porcentuales)
   - Evaluar normalmente

3. **Si NO se encuentra:**
   - Aplicar penalización: Nota máx Criterio 3 = 8.0
   - Razón: No se puede atribuir cambio sin comparativa
   - Señalar: "No se identifica dato basal para indicador [nombre]. No se puede evaluar cambio atribuible al proyecto."
   - Recomendar: "Incluir datos basales en futuros proyectos para evaluar impacto real"

4. **Excepción:**
   - Si indicador es de "mejora práctica" y hay estándar externo claro (ej. adherencia guía)
   - Evaluar vs estándar, no vs basal

---

## 5. EJEMPLOS GENÉRICOS {#ejemplos}

### EJEMPLO 1: Proyecto Excelente (Nota esperada: 9.0-9.5)

**PROYECTO:** Reducción de caídas en residencia de mayores

#### Proyecto Inicial (resumen)

**Análisis causas:**
- Iluminación insuficiente pasillos (mediciones <100 lux)
- 0% residentes con valoración riesgo caídas
- Personal sin formación específica

**Objetivos SMART:**
- Reducir incidencia caídas de 20% a <8% en 24 meses
- Valorar riesgo 100% residentes en 12 meses
- Formar 100% personal en 6 meses

**Actividades año 1:**
1. Mejorar iluminación (mes 1-3)
2. Formar personal (mes 1-6)
3. Valorar riesgo residentes (mes 4-12)

**Actividades año 2:**
4. Implementar medidas personalizadas (mes 13-18)
5. Reevaluar impacto (mes 19-24)

**Indicadores Alcance:**
- % residentes con valoración riesgo (Estándar 1ª: 70-80%, Final: 90-100%)
- % personal formado (Estándar 1ª: 80-100%, Final: 100%)

**Indicadores Impacto:**
- % residentes con ≥1 caída/año (Estándar 1ª: 12-15%, Final: 5-8%)

#### Memoria Final (resumen)

**Actividades:**
- Todas REALIZADAS ✓

**Indicadores Alcance:**
- % valorados: 95% (Nivel cumplimiento: 5.0/10 en rango 90-100%)
- % formados: 100% (Nivel cumplimiento: 10.0/10)

**Indicadores Impacto:**
- % caídas: 7% (basal 20%) - Reducción 65% (Nivel cumplimiento: 6.7/10 en rango 5-8%)

**Sostenibilidad:**
- Monitorización: Integrado OMI-AP
- Mantenimiento: Valoración en protocolo ingreso, revisión semestral en agenda
- Lecciones: Detalladas (barreras: coordinación mantenimiento; facilitadores: apoyo dirección)

#### Evaluación

**C1. RELEVANCIA: 9.5**
- Coherencia análisis-actividades: Perfecta
- Base científica: Guía NICE citada
- Potencial: Alto en 3 dimensiones

**C2. ALCANCE: 7.5**
- Promedio: (5.0 + 10.0) / 2 = 7.5
- Sin ajustes (todo coherente)
- Tope 9.5: 7.5

**C3. IMPACTO: 6.7**
- Nivel cumplimiento: 6.7
- Validación: Mide resultado salud real ✓
- Comparativa pre/post: 20% → 7% ✓
- Sin ajustes

**C4b. SOSTENIBILIDAD: 9.5**
- Monitorización: 9.5 (integrado OMI-AP)
- Mantenimiento: 9.5 (protocolo, agenda)
- Lecciones: 9.5 (detalladas)
- (9.5×0.4)+(9.5×0.4)+(9.5×0.2) = 9.5

**NOTA FINAL:**
```
(9.5×0.35) + (7.5×0.35) + (6.7×0.15) + (9.5×0.15)
= 3.325 + 2.625 + 1.005 + 1.425
= 8.4
```

**Nota: 8.4/10 - Excelente**

---

### EJEMPLO 2: Proyecto Medio (Nota esperada: 5.0-6.5)

**PROYECTO:** Mejora control hipertensión arterial

#### Proyecto Inicial (resumen)

**Análisis:** Genérico, sin causas raíz

**Objetivos:** "Mejorar control TA en pacientes hipertensos"

**Actividades:**
1. Revisar pacientes con TA >140/90
2. Actualizar tratamiento
3. Dar consejos estilo vida

**Indicadores Alcance:**
- % pacientes revisados (Estándar Final: 70-90%)

**Indicadores Impacto:**
- % pacientes con TA controlada <140/90 (Estándar Final: 50-70%)

#### Memoria Final (resumen)

**Actividades:**
- Actividad 1: REALIZADA (75% revisados)
- Actividad 2: EN MARCHA
- Actividad 3: NO INICIADA

**Indicadores Alcance:**
- % revisados: 75% (Nivel: 2.5/10 en rango 70-90%)

**Indicadores Impacto:**
- % controlados: Sin datos

**Sostenibilidad:**
- Campo vacío

**Lecciones:**
- "Falta de tiempo"

#### Evaluación

**C1. RELEVANCIA: 5.5**
- Coherencia: Débil (sin análisis causas)
- Base: Menciona "guías" pero no concreta
- Potencial: Medio

**C2. ALCANCE: 2.5**
- Nivel cumplimiento: 2.5
- Actividades no iniciadas >20%: -1.0
- Ajustado: 1.5
- Tope: min(1.5, 9.5) = 1.5

**C3. IMPACTO: 0**
- "Sin datos" 100%: Nota = 0

**C4b. SOSTENIBILIDAD: 2.0**
- Monitorización: 3.0 (indicador básico, no claro si sostenible)
- Mantenimiento: 1.0 (campo vacío)
- Lecciones: 2.0 (muy vago)
- (3×0.4)+(1×0.4)+(2×0.2) = 2.0

**NOTA FINAL:**
```
(5.5×0.35) + (1.5×0.35) + (0×0.15) + (2.0×0.15)
= 1.925 + 0.525 + 0 + 0.3
= 2.75
```

**Nota: 2.8/10 - Insuficiente**

---

### EJEMPLO 3: Proyecto Bueno-Alto (Nota esperada: 7.0-8.5)

**PROYECTO:** Formación RCP básica a escolares

#### Proyecto Inicial

**Análisis:**
- España: No formación RCP en currículum escolar
- Población diana: 150 alumnos 5º-6º primaria CRA

**Objetivos:**
- 80% alumnos adquieren conocimientos RCP en 12 meses
- 90% realizan maniobras correctamente

**Actividades:**
1. Sesiones teóricas (mes 1-6)
2. Sesiones prácticas (mes 3-8)
3. Evaluación conocimientos (mes 8)

**Indicadores Alcance:**
- % alumnos reciben formación (Estándar 1ª: 70-90%)

**Indicadores Impacto:**
- % alumnos superan test conocimientos (Estándar 1ª: 70-80%)
- % realizan maniobras correctas (Estándar 1ª: 80-90%)

#### Memoria Intermedia

**Actividades:**
- Todas REALIZADAS

**Indicadores Alcance:**
- % formados: 85% (Nivel: 7.5/10 en rango 70-90%)

**Indicadores Impacto:**
- % test: 78% (Nivel: 8.0/10 en rango 70-80%)
- % maniobras: 87% (Nivel: 7.0/10 en rango 80-90%)

**Comunicación:**
- Sesión claustro profesores ✓
- Reunión AMPA ✓
- Cartel sala espera centro salud ✓
- Artículo web ayuntamiento ✓

#### Evaluación Intermedia

**C1. RELEVANCIA: 8.0**
- Base: Evidencia internacional RCP escolar
- Potencial: Alto salud pública

**C2. ALCANCE: 7.5**
- Nivel: 7.5, sin ajustes

**C3. IMPACTO: 7.5**
- Promedio: (8.0 + 7.0) / 2 = 7.5
- Validación: Miden conocimiento/habilidad adquirida ✓

**C4a. COMUNICACIÓN: 9.0**
- 4 públicos (profesores, familias, pacientes CS, población)
- 3 canales (presencial, escrito, digital)
- Evidencia clara

**NOTA FINAL:**
```
(8.0×0.25) + (7.5×0.20) + (7.5×0.40) + (9.0×0.15)
= 2.0 + 1.5 + 3.0 + 1.35
= 7.85
```

**Nota: 7.9/10 - Bueno-Alto**

---

## 6. FAQ - PREGUNTAS FRECUENTES {#faq}

### P1: ¿Qué hago si un indicador clasificado como "Impacto" mide solo actividad?

**R:** RECLASIFICAR como Alcance.

**Proceso:**
1. No uses su "Nivel cumplimiento" en Criterio 3 (Impacto)
2. Inclúyelo en promedio de Criterio 2 (Alcance)
3. Penaliza Criterio 3: -1 punto
4. Señala en "Observaciones técnicas":
```
"Indicador '[nombre]' clasificado como Impacto mide actividad/alcance
(ej. % formados), no resultado. Se reclasifica como Alcance."
```

---

### P2: ¿Cómo evalúo Relevancia si no hay Proyecto Inicial?

**R:** Con la información disponible en la Memoria, pero limitando nota máx a 7.0.

**Buscar en Memoria:**
- "Información adicional" (puede haber contexto)
- Coherencia entre actividades y objetivos mencionados
- Base científica citada

**Señalar limitación:**
```
"Evaluación Relevancia limitada por ausencia Proyecto Inicial.
No se dispone de análisis causas formal."
```

---

### P3: ¿Qué pasa si todos los indicadores de Impacto tienen "Sin datos" en Memoria Final?

**R:** Nota Criterio 3 = 0.

**Justificación:**
- No se puede evaluar impacto sin datos
- Es Memoria FINAL (debería haber resultados)

**Observación:**
```
"No se aportan datos de indicadores de impacto en Memoria Final.
No es posible valorar efectividad del proyecto."
```

**Recomendación:**
```
"Completar medición indicadores impacto antes de cerrar proyecto definitivamente."
```

---

### P4: ¿Cómo sé si un proyecto es Memoria Intermedia o Final?

**R:** 3 formas de identificar:

**A) Sección RESUMEN:**
- Si tiene → FINAL
- Si no tiene → INTERMEDIA

**B) Campo Sostenibilidad:**
- Si tiene "Info adicional sostenibilidad y extensión" → FINAL
- Si no → INTERMEDIA

**C) Estándar indicadores:**
- Si compara vs "Estándar 1ª Memoria" → INTERMEDIA
- Si compara vs "Estándar Memoria Final" → FINAL

---

### P5: ¿Penalizo actividades año 2 "No iniciadas" en Memoria Intermedia?

**R:** NO.

**Razón:**
- Memoria Intermedia evalúa solo año 1
- Actividades año 2 no deben haberse iniciado aún

**Criterio:**
```
Actividades año 1 (fecha fin ≤12 meses):
- Evaluar normalmente
- Penalizar si "No iniciadas"

Actividades año 2 (fecha fin >12 meses):
- NO evaluar en Intermedia
- NO penalizar si "No iniciadas"
```

---

### P6: ¿Qué hago con resultados >100% en un indicador?

**R:** Verificar si es ratio o error.

**RATIO (válido >100%):**
```
Ejemplo: "Nº errores medicación / 1000 pacientes-día"
Denominador NO incluye numerador → Puede ser >100%
Acción: Aceptar resultado, no penalizar
```

**PROPORCIÓN (error si >100%):**
```
Ejemplo: "% pacientes formados"
Denominador incluye numerador → NO puede ser >100%
Acción:
- Señalar incoherencia
- No usar "Nivel cumplimiento"
- Penalizar: -1 punto
- Recomendar verificar cálculo
```

**Si no está claro:**
- Buscar explicación en "Información adicional"
- Si no hay → Asumir error

---

### P7: ¿Cómo busco "Plan de Comunicación" si no hay campo explícito?

**R:** 3 lugares:

**1. "Información adicional actividades" (texto libre):**
```
Buscar menciones a: sesiones, presentaciones, difusión, carteles,
comunicación, consejo salud, AMPA, intranet, etc.
```

**2. Actividades:**
```
Revisar si hay actividades como:
- "Sesión formativa equipo"
- "Presentación consejo salud"
- "Cartel informativo pacientes"
- "Difusión resultados intranet"
```

**3. "Lecciones aprendidas":**
```
Buscar menciones: "La difusión...", "La comunicación...", "Se presentó..."
```

**Si no encuentras nada:**
```
Nota Criterio 4a = 2-3/10
Observación: "No se identifica plan de comunicación en la Memoria."
```

---

### P8: ¿Qué es el "Nivel de cumplimiento (0-10)" y cómo se calcula?

**R:** Es una nota AUTOMÁTICA que la plataforma calcula comparando Resultado vs Estándar.

**Fórmula:**
```
Nivel = ((Resultado - Valor_desde) / (Valor_hasta - Valor_desde)) × 10
```

**Ejemplo:**
```
Indicador: % pacientes valorados
Estándar Final: 50.00 - 100.00%
Resultado: 82.86%

Nivel = ((82.86 - 50) / (100 - 50)) × 10
      = (32.86 / 50) × 10
      = 6.572
      ≈ 6.6
```

**Reglas:**
- Resultado ≥ Valor_hasta → Nivel = 10.0 (tope)
- Resultado < Valor_desde → Nivel = 0.0
- Sin datos → "Sin datos"

**IMPORTANTE:**
- NO calcules tu propio "Nivel"
- EXTRAE el que ya existe en la Memoria
- ÚSALO como base para tu evaluación

---

### P9: ¿Qué pasa si hay contradicción entre Proyecto Inicial y Memoria?

**R:** Prioriza dato más reciente (Memoria) y señala la contradicción.

**Ejemplo:**
```
Proyecto: "Reducir caídas 30%"
Memoria Final: "Reducir caídas 20%"

Acción:
1. Usar 20% (dato más reciente)
2. Buscar justificación en "Info adicional"
3. Si hay justificación → No penalizar
4. Si no hay → Señalar en Observaciones, penalizar levemente (-0.5)

Observación:
"Objetivo modificado durante ejecución (inicial 30%, final 20%).
No se identifica justificación del cambio."

Recomendación:
"Documentar modificaciones de objetivos en Memorias."
```

---

### P10: ¿Cómo evalúo proyectos de centros muy pequeños (n<30)?

**R:** NO penalices por tamaño poblacional. Es realidad asistencial.

**Principios:**
1. **Regla Oro:** Reconoce variabilidad inherente
2. **Centros pequeños:** Realidad rural Aragón
3. **Validez:** Si denominador = población diana completa → Válido

**Acción:**
- Evaluar criterios normalmente
- Señalar en observaciones: "Población pequeña (n=[X]), resultados orientativos"
- NO afecta nota si metodología correcta

**Valoración positiva:**
- Proyectos centros pequeños con seguimiento sistemático merecen reconocimiento

---

**FIN DOCUMENTACIÓN COMPLETA**

---
**Repositorio:** https://github.com/evaluacion-proyectos-salud-aragon
**Versión:** 1.0
**Actualizado:** Marzo 2026
**Licencia:** Uso interno Servicio Aragonés de Salud
