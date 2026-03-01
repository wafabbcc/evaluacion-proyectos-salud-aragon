# 📊 Evaluación Proyectos Mejora Calidad - SALUD Aragón

## Sistema de evaluación automatizada de Memorias de Seguimiento y Memorias Finales

---

## 🎯 Propósito

Este repositorio contiene la documentación completa para la evaluación de proyectos de mejora de la calidad asistencial en el Servicio Aragonés de Salud, siguiendo los **criterios oficiales** establecidos por el Programa de Apoyo de Mejora de la Calidad 2022.

## 📚 Contenido

### Documentación Principal
- **[Documentación Completa](github_documentacion_completa.md)** - Guía exhaustiva con rúbricas detalladas, ejemplos y casos especiales

### Secciones Clave
1. **Estructura Oficial** - Campos obligatorios Proyecto Inicial, Memorias Seguimiento y Final
2. **Criterios de Evaluación** - 4 criterios con definiciones oficiales detalladas
3. **Rúbricas 1-10** - Escalas completas para cada criterio
4. **Casos Especiales** - Protocolo para situaciones no estándar
5. **Ejemplos Genéricos** - Proyectos evaluados con justificación
6. **FAQ** - Respuestas a preguntas frecuentes

## 🔑 Criterios de Evaluación

### Memoria Intermedia (Año 1)
| Criterio | Peso |
|----------|------|
| 1. Relevancia de actividades | 25% |
| 2. Resultados Alcance | 20% |
| 3. Resultados Impacto | 40% |
| 4a. Plan Comunicación | 15% |

### Memoria Final (Año 2)
| Criterio | Peso |
|----------|------|
| 1. Relevancia de actividades | 35% |
| 2. Resultados Alcance | 35% |
| 3. Resultados Impacto | 15% |
| 4b. Sostenibilidad y Extensión | 15% |

**Escala:** 1-10 puntos por criterio  
**Tope:** 9.5/10 (regla oro - variabilidad asistencial)

## ⚡ Principios Fundamentales

### 1. Uso de "Nivel de Cumplimiento (0-10)"
- La plataforma oficial **calcula automáticamente** el nivel de cumplimiento de cada indicador
- El evaluador **EXTRAE** estos valores, no los calcula
- Solo aplica ajustes por problemas técnicos o metodológicos

### 2. Distinción Temporal
- **Memoria Intermedia:** Evalúa solo primer año (actividades ≤12 meses)
- **Memoria Final:** Evalúa proyecto completo (24 meses)

### 3. Alcance vs Impacto
- **Alcance:** COBERTURA - ¿Hicimos lo planificado? ¿A cuántos llegamos?
- **Impacto:** RESULTADO - ¿Qué cambió en pacientes o sistema?

### 4. Regla Oro (Tope 9.5)
- Ningún criterio ni nota final puede superar 9.5
- Reconoce variabilidad inherente de la práctica asistencial
- Evita perfeccionismo irreal

## 🚀 Uso Rápido

### Paso 1: Identificar tipo de memoria
```
¿Tiene sección "RESUMEN"? → FINAL
¿Solo "Memoria Seguimiento"? → INTERMEDIA
```

### Paso 2: Extraer datos clave
- Actividades (Realizadas / En marcha / No iniciadas)
- Indicadores Alcance: Num / Denom / **Nivel cumplimiento (0-10)**
- Indicadores Impacto: Num / Denom / **Nivel cumplimiento (0-10)**

### Paso 3: Evaluar 4 criterios
- C1: Relevancia → Pertinencia actividades (coherencia causas, base científica)
- C2: Alcance → Promedio niveles cumplimiento + ajustes
- C3: Impacto → Promedio niveles cumplimiento + validación que miden resultado real
- C4: Comunicación (Intermedia) o Sostenibilidad (Final)

### Paso 4: Calcular nota ponderada
```
Intermedia: (C1×0.25) + (C2×0.20) + (C3×0.40) + (C4a×0.15)
Final:      (C1×0.35) + (C2×0.35) + (C3×0.15) + (C4b×0.15)
```

### Paso 5: Generar informe
- Tabla resumen con 4 notas + nota final
- Justificación breve (1-2 frases por criterio)
- 3 Fortalezas + 3 Recomendaciones prioritarias
- Observaciones técnicas

## 📖 Navegación Documentación

### Por Sección
- **Estructura Oficial** → [github_documentacion_completa.md#estructura-oficial](github_documentacion_completa.md#estructura-oficial)
- **Criterios Detallados** → [github_documentacion_completa.md#criterios-detallados](github_documentacion_completa.md#criterios-detallados)
- **Rúbricas Completas** → [github_documentacion_completa.md#rubricas-completas](github_documentacion_completa.md#rubricas-completas)
- **Casos Especiales** → [github_documentacion_completa.md#casos-especiales](github_documentacion_completa.md#casos-especiales)
- **Ejemplos** → [github_documentacion_completa.md#ejemplos](github_documentacion_completa.md#ejemplos)
- **FAQ** → [github_documentacion_completa.md#faq](github_documentacion_completa.md#faq)

### Por Situación
- ¿Indicador mide actividad, no resultado? → [FAQ P1](github_documentacion_completa.md#faq)
- ¿Falta Proyecto Inicial? → [Caso Especial 1](github_documentacion_completa.md#casos-especiales)
- ¿Todos indicadores "Sin datos"? → [Caso Especial 5](github_documentacion_completa.md#casos-especiales)
- ¿Resultado >100%? → [Caso Especial 4](github_documentacion_completa.md#casos-especiales)
- ¿Población pequeña n<30? → [Caso Especial 9](github_documentacion_completa.md#casos-especiales)

## 🔍 Casos Especiales Frecuentes

| Situación | Protocolo | Referencia |
|-----------|-----------|------------|
| Indicador Impacto mide solo actividad | Reclasificar como Alcance | [FAQ P1](github_documentacion_completa.md#faq) |
| Sin Proyecto Inicial | Evaluar con info Memoria, limitar C1 a 7.0 | [Caso 1](github_documentacion_completa.md#casos-especiales) |
| 100% indicadores "Sin datos" (Final) | C2=3.0, C3=0 | [Caso 5](github_documentacion_completa.md#casos-especiales) |
| Resultado >100% (no ratio) | Señalar error, penalizar -1 | [Caso 4](github_documentacion_completa.md#casos-especiales) |
| Población n<30 | No penalizar, señalar en observaciones | [Caso 9](github_documentacion_completa.md#casos-especiales) |
| Sin comparativa pre/post (Impacto) | Nota máx C3 = 8.0 | [Caso 10](github_documentacion_completa.md#casos-especiales) |

## 💡 Reglas Críticas

### ✅ HACER
- ✅ USAR "Nivel cumplimiento (0-10)" de la plataforma
- ✅ VALIDAR coherencia técnica (Num/Denom = Resultado)
- ✅ RECLASIFICAR indicadores Impacto que miden actividad
- ✅ APLICAR tope 9.5 a todos los criterios y nota final
- ✅ DISTINGUIR entre Memoria Intermedia (año 1) y Final (2 años)
- ✅ SER CONSTRUCTIVO: reconocer esfuerzo, recomendar mejoras accionables

### ❌ NO HACER
- ❌ NO calcular propio "Nivel cumplimiento"
- ❌ NO penalizar centros pequeños por tamaño poblacional
- ❌ NO penalizar actividades año 2 en Memoria Intermedia
- ❌ NO superar 9.5 en ningún criterio ni nota final
- ❌ NO usar lenguaje técnico innecesario
- ❌ NO dar recomendaciones genéricas ("mejorar calidad")

## 📊 Ejemplos Rápidos

### Proyecto Excelente (8.4/10)
```
C1 Relevancia: 9.5 → Análisis causas detallado, base científica citada
C2 Alcance: 7.5 → Promedio niveles 7.5, sin ajustes
C3 Impacto: 6.7 → Reducción caídas 20%→7% demostrada
C4b Sostenibilidad: 9.5 → Integrado OMI-AP, plan continuidad detallado

Nota: (9.5×0.35)+(7.5×0.35)+(6.7×0.15)+(9.5×0.15) = 8.4
```

### Proyecto Insuficiente (2.8/10)
```
C1 Relevancia: 5.5 → Sin análisis causas, actividades genéricas
C2 Alcance: 1.5 → Nivel 2.5, >20% actividades no iniciadas (-1)
C3 Impacto: 0 → 100% indicadores "Sin datos"
C4b Sostenibilidad: 2.0 → Campo vacío, lecciones vagas

Nota: (5.5×0.35)+(1.5×0.35)+(0×0.15)+(2.0×0.15) = 2.8
```

## 🤝 Contribuciones

Este es un repositorio de documentación **oficial** del Servicio Aragonés de Salud. Las actualizaciones son gestionadas por el equipo de Calidad Asistencial.

## 📞 Contacto

Para consultas sobre evaluación de proyectos:
- Unidad de Calidad y Seguridad del Paciente
- Servicio Aragonés de Salud

## 📜 Licencia

Uso interno Servicio Aragonés de Salud  
Programa de Apoyo de Mejora de la Calidad 2022

---

**Versión:** 1.0  
**Actualización:** Marzo 2026  
**Basado en:** Criterios oficiales SALUD Aragón 2022

---    

## 🔗 Enlaces Rápidos

- [Volver a Documentación Completa](github_documentacion_completa.md)
- [Validación Técnica](validacion_tecnica.md)
- [Instrucciones Copilot](copilot_instructions.md)
