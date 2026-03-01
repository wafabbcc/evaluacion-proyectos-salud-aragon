# ✅ CHECKLIST VALIDACIÓN TÉCNICA
## Verificaciones Esenciales para Evaluación de Proyectos

---

## 🎯 USO DE ESTE DOCUMENTO

Este checklist ayuda a verificar aspectos técnicos de los proyectos **antes** de asignar notas definitivas.

**Workflow:**
1. Extraer datos del proyecto
2. Ejecutar checklist correspondiente
3. Aplicar ajustes/penalizaciones según hallazgos
4. Calcular nota final

---

## 📋 CHECKLIST 1: IDENTIFICACIÓN TIPO MEMORIA

### ✅ Verificar tipo de memoria

- [ ] ¿Tiene sección "RESUMEN"?
  - SÍ → **MEMORIA FINAL**
  - NO → Siguiente pregunta

- [ ] ¿Tiene campo "Información adicional sobre sostenibilidad"?
  - SÍ → **MEMORIA FINAL**
  - NO → Siguiente pregunta

- [ ] ¿Indicadores comparan vs "Estándar 1ª Memoria" o "Estándar Final"?
  - 1ª Memoria → **MEMORIA INTERMEDIA**
  - Final → **MEMORIA FINAL**

### ✅ Aplicar pesos correctos

**Memoria Intermedia:**
```
C1: 25%
C2: 20%
C3: 40%
C4a (Comunicación): 15%
```

**Memoria Final:**
```
C1: 35%
C2: 35%
C3: 15%
C4b (Sostenibilidad): 15%
```

---

## 📋 CHECKLIST 2: VALIDACIÓN INDICADORES ALCANCE

### ✅ Para cada indicador de Alcance

#### Definición Técnica
- [ ] ¿Numerador está claramente definido?
- [ ] ¿Denominador está claramente definido?
- [ ] ¿Fuente de datos es específica? (OMI-AP, historia, registro...)
  - ❌ Vaga: "Registros", "Bases de datos"
  - ✅ Específica: "OMI-AP módulo diabéticos", "Historia clínica electrónica"

**Penalización si NO:** -0.5 puntos Criterio 2

#### Coherencia Matemática
- [ ] ¿Resultado = Numerador / Denominador?

**Ejemplo:**
```
Numerador: 85
Denominador: 100
Resultado esperado: 85%
Resultado reportado: 85% → ✅ COHERENTE

Si reportado: 75% → ❌ INCOHERENTE → -0.5 puntos
```

#### Nivel de Cumplimiento
- [ ] ¿Existe valor "Nivel de cumplimiento (0-10)"?
  - SÍ → EXTRAER ese valor
  - NO → ¿Es "Sin datos"?

**Si "Sin datos" en Memoria Final:**
```
Penalización: -3.0 puntos por indicador
Si >50% indicadores sin datos: Nota máx C2 = 5.0
```

#### Coherencia Temporal
- [ ] ¿Fechas medición coherentes con periodo evaluado?

**Memoria Intermedia:**
```
Fechas deben estar en primeros 12 meses
Si fecha >12 meses → Señalar incoherencia
```

**Memoria Final:**
```
Fechas deben cubrir periodo completo o ser recientes
```

#### Coherencia con Actividades
- [ ] Si indicador mide "% profesionales formados", ¿hay actividad "Formar profesionales" REALIZADA?

**Si actividad NO INICIADA pero indicador con datos:**
```
→ INCOHERENCIA
→ Señalar en Observaciones
→ Penalizar -0.5 puntos
```

### ✅ Cálculo Nota Criterio 2 (Alcance)

**PASO 1:** Promedio "Nivel cumplimiento" de todos indicadores Alcance

**PASO 2:** Aplicar penalizaciones acumuladas

**PASO 3:** Verificar tope cobertura (solo Memoria Final)
```
Si Resultado <95% sin justificación → Nota máx = 8.0
```

**PASO 4:** Aplicar TOPE 9.5
```
Nota_final = min(promedio_ajustado, 9.5)
```

---

## 📋 CHECKLIST 3: VALIDACIÓN INDICADORES IMPACTO

### ✅ Para cada indicador de Impacto

#### Validación Crítica: ¿Es Realmente Impacto?

**PREGUNTA 1:** ¿Mide resultado en pacientes o sistema?

**✅ SÍ (son IMPACTO válido):**
```
- % reducción caídas, úlceras, infecciones
- % pacientes con HbA1c/TA/LDL controlados
- Puntuación escalas calidad vida (SF-12, EQ-5D...)
- % reducción reingresos, estancia media
- % adecuación prescripción (mejora práctica)
- % pacientes autónomos autocuidado
```

**❌ NO (son ALCANCE, reclasificar):**
```
- % profesionales formados
- Nº sesiones educativas realizadas
- % registros OMI-AP cumplimentados
- % protocolos elaborados
- % pacientes incluidos en programa
```

**Acción si NO es impacto:**
1. NO usar su "Nivel cumplimiento" en Criterio 3
2. Incluir en cálculo Criterio 2 (Alcance)
3. Penalizar Criterio 3: -1.0 punto
4. Señalar en Observaciones:
```
"Indicador '[nombre]' clasificado como Impacto mide 
actividad/alcance, no resultado. Se reclasifica."
```

#### Comparativa Pre/Post

- [ ] ¿Hay dato basal (pre-intervención)?

**Dónde buscar:**
```
1. Proyecto Inicial → Sección "Análisis situación"
2. Memoria → "Información adicional"
3. Memoria Seguimiento (si evalúas Final)
```

**Si NO hay dato basal:**
```
→ No se puede atribuir cambio al proyecto
→ Nota máx Criterio 3 = 8.0
→ Señalar: "No se identifica dato basal para indicador [nombre]"
```

**Excepción:** Indicadores vs estándar externo claro (ej. adherencia guía)

#### Nivel de Cumplimiento
- [ ] ¿Existe valor "Nivel de cumplimiento (0-10)"?

**Si "Sin datos" en Memoria Final:**
```
1 indicador sin datos: -3.0 puntos
>50% sin datos: Nota máx = 5.0
100% sin datos: Nota = 0
```

#### Definición Técnica
Igual que Alcance:
- [ ] Numerador claro
- [ ] Denominador claro
- [ ] Fuente específica
- [ ] Coherencia Num/Denom = Resultado

### ✅ Cálculo Nota Criterio 3 (Impacto)

**PASO 1:** Filtrar indicadores VÁLIDOS (descartar reclasificados)

**PASO 2:** Promedio "Nivel cumplimiento" de indicadores válidos

**PASO 3:** Aplicar penalizaciones

**PASO 4:** Verificar comparativa pre/post
```
Si NO hay → Nota máx = 8.0
```

**PASO 5:** Aplicar TOPE 9.5

**CASO ESPECIAL:** Si todos los indicadores son reclasificados (ninguno válido)
```
→ No hay indicadores impacto
→ Nota Criterio 3 = 3.0
→ Observación: "No se identifican indicadores impacto válidos"
```

---

## 📋 CHECKLIST 4: VALIDACIÓN RESULTADOS >100%

### ✅ Cuando un Resultado es >100%

**PASO 1:** Identificar tipo de indicador

- [ ] ¿Es un RATIO? (Numerador NO incluido en Denominador)

**Ejemplos ratios (válido >100%):**
```
- Nº errores medicación / 1000 pacientes-día
- Nº caídas / 100 residentes-año
- Tasa mortalidad / 1000 habitantes
```

→ **VÁLIDO**, no penalizar

- [ ] ¿Es una PROPORCIÓN? (Numerador SÍ incluido en Denominador)

**Ejemplos proporciones (ERROR si >100%):**
```
- % pacientes formados
- % registros cumplimentados
- % protocolos implementados
```

→ **ERROR**

**PASO 2:** Si es error

1. Señalar incoherencia en Observaciones:
```
"Resultado >100% en indicador '[nombre]' (proporción). 
Verificar cálculo Num/Denom."
```

2. No usar "Nivel cumplimiento" de ese indicador

3. Penalizar: -1.0 punto en criterio correspondiente

4. Recomendar: "Verificar cálculo del indicador antes de próxima memoria"

**PASO 3:** Si no está claro si es ratio o proporción

- Buscar explicación en "Información adicional"
- Si no hay explicación → **Asumir error** y proceder como PASO 2

---

## 📋 CHECKLIST 5: VALIDACIÓN ACTIVIDADES

### ✅ Clasificación de Actividades

**Memoria Seguimiento o Final debe clasificar actividades:**

- [ ] **REALIZADAS:** ¿Tienen fecha real inicio Y fecha real fin?
- [ ] **EN MARCHA:** ¿Tienen fecha real inicio Y fecha prevista fin?
- [ ] **NO INICIADAS:** ¿Tienen fecha prevista inicio Y fecha prevista fin?
- [ ] **NUEVAS:** ¿Actividades no previstas en Proyecto Inicial?

### ✅ Coherencia Temporal (Memoria Intermedia)

**Para cada actividad planificada en Proyecto Inicial:**

- [ ] Si fecha prevista fin ≤ 12 meses → Actividad año 1
- [ ] Si fecha prevista fin > 12 meses → Actividad año 2

**Evaluación en Memoria Intermedia:**
```
Actividades año 1:
- Evaluar normalmente
- Si "No iniciadas" >20% → Penalizar -1 punto Criterio 2

Actividades año 2:
- NO evaluar (aún no debían iniciarse)
- NO penalizar si "No iniciadas"
```

### ✅ Coherencia con Indicadores

**Para cada indicador de Alcance:**

- [ ] ¿Hay actividad correspondiente?
- [ ] ¿Estado actividad coherente con datos indicador?

**Ejemplo incoherencia:**
```
Indicador: "% profesionales formados" → Datos: 85% (Nivel 8.5)
Actividad: "Formar profesionales" → Estado: NO INICIADA

→ INCOHERENTE
→ Señalar en Observaciones
→ Penalizar -0.5 puntos Criterio 2
```

### ✅ Actividades Nuevas

Si hay actividades NO previstas en Proyecto Inicial:

- [ ] ¿Hay justificación en "Información adicional"?
- [ ] ¿Son coherentes con objetivos del proyecto?

**Si justificadas y coherentes:**
```
→ No penalizar
→ Incluso valorar positivamente adaptación
→ Mencionar en Fortalezas si pertinente
```

**Si NO justificadas o incoherentes:**
```
→ Penalizar Criterio 1 (Relevancia): -1.0 punto
→ Señalar: "Actividades nuevas no justificadas"
```

---

## 📋 CHECKLIST 6: VERIFICACIÓN SOSTENIBILIDAD (Solo Memoria Final)

### ✅ Componente A: MONITORIZACIÓN (40%)

- [ ] **Indicadores bien definidos:**
  - ¿Numerador sin ambigüedades?
  - ¿Denominador específico?
  - ¿Fuente concreta? (no "registros" genérico)

- [ ] **Realismo obtención datos post-proyecto:**
  - ¿Integrado OMI-AP / historia clínica?
  - ¿O requiere registro adhoc manual?
  - ¿Depende de personal dedicado? (no realista)

**Nota A: 1-10**

### ✅ Componente B: MANTENIMIENTO (40%)

- [ ] **Plan continuidad explícito:**
  - ¿Hay plan escrito?
  - ¿Responsables asignados?
  - ¿Periodicidad definida?

- [ ] **Integración en práctica:**
  - ¿En agenda habitual?
  - ¿Protocolos actualizados?
  - ¿En plan formación continua?

- [ ] **Independencia recursos:**
  - ¿Funciona con plantilla habitual?
  - ¿Sin financiación especial?
  - ¿Material ya disponible?

**Nota B: 1-10**

### ✅ Componente C: LECCIONES APRENDIDAS (20%)

- [ ] **Campo cumplimentado:**
  - ¿Hay contenido sustancial?
  - ¿O solo frases genéricas?

- [ ] **Identifica barreras:**
  - ¿Técnicas, organizativas, culturales?
  - ¿Específicas y concretas?

- [ ] **Identifica facilitadores:**
  - ¿Qué ayudó?
  - ¿Factores clave éxito?

- [ ] **Propone mejoras:**
  - ¿Qué haría diferente?
  - ¿Aplicable a otros centros?

**Nota C: 1-10**

### ✅ Cálculo Nota Criterio 4b

```
Nota = (A × 0.4) + (B × 0.4) + (C × 0.2)
Aplicar TOPE 9.5
```

---

## 📋 CHECKLIST 7: VERIFICACIÓN COMUNICACIÓN (Solo Memoria Intermedia)

### ✅ Búsqueda Evidencia Plan Comunicación

**NO hay campo explícito. Buscar en:**

- [ ] **"Información adicional actividades"** (texto libre)
  - Menciones: sesiones, presentaciones, difusión, carteles, AMPA, consejo salud...

- [ ] **Actividades listadas:**
  - "Sesión formativa equipo" → Público 1 ✓
  - "Cartel pacientes" → Público 3 ✓
  - "Presentación consejo salud" → Público 5 ✓
  - "Difusión intranet" → Público 2 ✓

- [ ] **"Lecciones aprendidas":**
  - "La difusión...", "La comunicación...", "Se presentó en..."

### ✅ Evaluación

**Contar públicos alcanzados (máx 5):**
1. Profesionales de la unidad
2. Profesionales de otras unidades
3. Pacientes
4. Población general
5. Consejo de salud

**Contar canales utilizados:**
- Presencial (sesiones, reuniones)
- Escrito (carteles, trípticos, informes)
- Digital (intranet, email, web)

**Verificar evidencia ejecución:**
- ¿Fechas concretas?
- ¿Nº asistentes?
- ¿Materiales elaborados?

### ✅ Cálculo Nota Criterio 4a

```
Públicos_puntos: 0-2 (0 públicos) ... 9-10 (4-5 públicos)
Canales_puntos: 0-2 (0 canales) ... 9-10 (3+ canales)
Evidencia_puntos: 0-3 (sin evidencia) ... 7-10 (detallada)

Nota = (Públicos × 0.5) + (Canales × 0.3) + (Evidencia × 0.2)
Aplicar TOPE 9.5
```

---

## 📋 CHECKLIST 8: VERIFICACIÓN RELEVANCIA

### ✅ Coherencia Análisis → Actividades

**Buscar Proyecto Inicial:**

- [ ] ¿Hay sección "Análisis de causas"?
- [ ] ¿Metodología identificable? (Ishikawa, 5 porqués, Pareto...)
- [ ] ¿Causas raíz claras?

**Para cada actividad planificada:**

- [ ] ¿Ataca una causa raíz específica?
- [ ] ¿O es actividad genérica sin relación?

**Scoring:**
```
Todas las actividades → causas raíz: Coherencia EXCELENTE
Mayoría actividades → causas: Coherencia BUENA
Algunas actividades → causas: Coherencia MEDIA
Pocas/ninguna → causas: Coherencia BAJA
```

### ✅ Base Científica

- [ ] ¿Se citan guías clínicas?
- [ ] ¿Se mencionan protocolos, estudios, evidencia?
- [ ] ¿Hay benchmarking con otros centros?

**Scoring:**
```
Guías citadas + estudios: Base SÓLIDA
Guías mencionadas: Base ADECUADA
"Según guías" sin especificar: Base VAGA
Sin mención: Base AUSENTE
```

### ✅ Potencial Impacto 3 Dimensiones

**Para el conjunto de actividades:**

- [ ] **Práctica clínica:** ¿Pueden mejorar adherencia guías, reducir variabilidad, aumentar seguridad?
- [ ] **Calidad vida pacientes:** ¿Pueden reducir síntomas, aumentar autonomía, mejorar experiencia?
- [ ] **Eficiencia:** ¿Pueden reducir uso inadecuado recursos, evitar ingresos, optimizar fármacos?

**Scoring:**
```
Alto potencial 3 dimensiones: 9-10
Alto potencial 2-3 dimensiones: 7-8
Potencial claro 1-2 dimensiones: 5-6
Potencial bajo/incierto: 3-4
Sin potencial claro: 1-2
```

### ✅ Cálculo Nota Criterio 1

**Integrar:**
- Coherencia análisis-actividades (50%)
- Base científica (30%)
- Potencial impacto (20%)

**Aplicar penalizaciones:**
- Actividades genéricas sin relación causas: -2 puntos
- Sin base científica: -1 punto
- No abordan 3 dimensiones: -0.5 por dimensión ausente

**Aplicar TOPE 9.5**

**Si falta Proyecto Inicial:**
```
→ Evaluar con info disponible en Memoria
→ Nota máx = 7.0
→ Señalar limitación
```

---

## 📋 CHECKLIST 9: VERIFICACIÓN NOTA FINAL

### ✅ Antes de calcular nota ponderada

- [ ] **Todos los criterios evaluados:**
  - C1: 1-10 ✓
  - C2: 0-10 ✓
  - C3: 0-10 ✓
  - C4: 1-10 ✓

- [ ] **Ningún criterio supera 9.5**

- [ ] **Pesos correctos aplicados:**
  - Intermedia: 25-20-40-15
  - Final: 35-35-15-15

### ✅ Calcular

**Memoria Intermedia:**
```
Nota = (C1×0.25) + (C2×0.20) + (C3×0.40) + (C4a×0.15)
```

**Memoria Final:**
```
Nota = (C1×0.35) + (C2×0.35) + (C3×0.15) + (C4b×0.15)
```

### ✅ Verificar nota final

- [ ] **Redondear a 1 decimal**

- [ ] **Aplicar TOPE 9.5:**
```
Nota_final = min(nota_calculada, 9.5)
```

- [ ] **Verificar coherencia:**
  - Si todos criterios altos (≥8) → Nota debería ser ≥7.5
  - Si algún criterio muy bajo (≤3) → Nota afectada significativamente
  - Si pesos: ¿coincide con cálculo manual?

---

## 📋 CHECKLIST 10: VERIFICACIÓN INFORME

### ✅ Tabla Resumen

- [ ] **Encabezado completo:**
  - Código proyecto
  - Título proyecto
  - Tipo (Intermedia/Final)
  - Centro

- [ ] **4 filas criterios:**
  - Nombre criterio
  - Nota (1 decimal)
  - Peso (%)
  - Ponderado (2 decimales)

- [ ] **Fila nota final:**
  - Suma ponderados
  - 1 decimal

### ✅ Justificación Breve

- [ ] **1-2 frases por criterio** (no más)

- [ ] **Específicas:** Evitar genéricas "Es adecuado", "Cumple objetivos"

- [ ] **Explicativas:** ¿Por qué esa nota?

**Ejemplo bueno:**
```
C1 (9.5): Actividades muy coherentes con análisis causas (iluminación,
formación, valoración), base científica citada (Guía NICE), alto potencial
impacto en práctica, calidad vida y eficiencia.
```

**Ejemplo malo:**
```
C1 (9.5): Las actividades son pertinentes y adecuadas.
```

### ✅ Fortalezas (3 máximo)

- [ ] **Concretas y específicas**

- [ ] **Destacan aspectos sobresalientes**

**Ejemplo:**
```
- Análisis de causas riguroso con mediciones objetivas (lux, encuesta conocimientos)
- Integración sostenible en OMI-AP y protocolos habituales
- Excelente plan comunicación multi-público (5 grupos alcanzados)
```

### ✅ Recomendaciones (3 prioritarias)

- [ ] **Accionables:** El equipo puede implementarlas

- [ ] **Específicas:** No genéricas

- [ ] **Priorizadas:** Las 3 más importantes

**Ejemplo bueno:**
```
1. Completar medición indicadores impacto en próxima memoria
2. Definir Num/Denom/Fuente específica para todos los indicadores
3. Incluir datos basales en futuros proyectos para demostrar cambio atribuible
```

**Ejemplo malo:**
```
1. Mejorar la calidad del proyecto
2. Seguir trabajando
3. Cumplir objetivos
```

### ✅ Observaciones Técnicas

- [ ] **Señalar validaciones realizadas**
- [ ] **Indicar reclasificaciones**
- [ ] **Mencionar datos faltantes**
- [ ] **Destacar limitaciones evaluación** (ej. sin Proyecto Inicial)

---

## ✅ CHECKLIST FINAL RÁPIDO

Antes de entregar evaluación, verificar:

- [ ] ✅ Tipo memoria identificado correctamente
- [ ] ✅ Pesos aplicados correctos (25-20-40-15 / 35-35-15-15)
- [ ] ✅ "Nivel cumplimiento" EXTRAÍDO, no calculado
- [ ] ✅ Indicadores Impacto validados (¿miden resultado?)
- [ ] ✅ Ningún criterio ni nota final >9.5
- [ ] ✅ Coherencias verificadas (Num/Denom, actividades-indicadores)
- [ ] ✅ Penalizaciones aplicadas correctamente
- [ ] ✅ Tabla resumen completa y correcta
- [ ] ✅ Justificaciones específicas (no genéricas)
- [ ] ✅ Recomendaciones accionables (no vagas)
- [ ] ✅ Tono constructivo y respetuoso

---

**FIN CHECKLIST VALIDACIÓN TÉCNICA**

---
**Versión:** 1.0  
**Actualizado:** Marzo 2026  
**Uso:** Complemento a Documentación Completa
