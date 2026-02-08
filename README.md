# 📊Análisis de mercado y riesgo basado en eventos (SQL)

## 📌Descripción

Este proyecto reúne una serie de análisis cuantitativos orientados a eventos de mercado, implementados en SQL, con foco en riesgo sistémico, volatilidad, tendencia y propagación de shocks a nivel industrial y sectorial.

El objetivo es detectar patrones de estrés de mercado a partir de la coincidencia de eventos negativos, reacciones de la volatilidad y comportamiento técnico de los activos.

## 🎯Objetivos del Proyecto

- Identificar tendencias confiables en activos financieros
- Medir el impacto de eventos y noticias negativas
- Detectar acumulación de riesgo a nivel industria
- Analizar la propagación sectorial de la volatilidad
- Transformar datos técnicos en clasificaciones accionables
- Demostrar dominio de SQL aplicado a finanzas cuantitativas

## 🧠Enfoque Analítico

El proyecto combina:
- Indicadores técnicos (ADX, volatilidad histórica)
- Volatilidad implícita como señal anticipatoria
- Análisis pre y post evento
- Métricas de distribución (kurtosis)
- Agregación a nivel activo, industria y sector
- Detección de coincidencia de eventos negativos como proxy de riesgo sistémico

Preguntas clave que aborda el repositorio:
- ¿Qué activos muestran tendencias sostenibles?
- ¿Cómo reaccionan los precios y la volatilidad ante eventos negativos?
- ¿Cuándo un shock deja de ser idiosincrático y pasa a ser industrial?
- ¿Qué sectores amplifican o amortiguan el riesgo?

## 🗂️Contenido del Repositorio

📁 Insights Principales

- Clasificación de Tickers por Robustez de la Tendencia (ADX)
- Segmentación de activos según fuerza de tendencia.
- Clasificación de Eventos por Volatilidad Post-Evento
- Evaluación del impacto de eventos sobre la volatilidad posterior.
- Cobertura de la Volatilidad Sectorial por Eventos
- Análisis del efecto de eventos a nivel sector.
- Cobertura de Noticias y Volatilidad Implícita (Kurtosis)
- Identificación de colas extremas tras eventos informativos.
- Coincidencia de Eventos Negativos en la Industria
- Detección de acumulación de eventos adversos dentro de una misma industria como señal de riesgo sistémico.

Cada insight está implementado como un query SQL independiente, diseñado para responder una hipótesis de mercado específica.

## 🧮Tecnologías Utilizadas

- SQL
- Bases de datos relacionales
- Compatible con PostgreSQL / MySQL / BigQuery

## 🗃️Modelo de Datos (conceptual)

- tickers
- ticker_id
- nombre_empresa
- sector
- industria
- indicadores_tecnicos
- ticker_id
- fecha
- ADX, volatilidad, métricas estadísticas
- eventos / noticias
- ticker_id
- fecha_evento
- tipo_evento
- severidad / sentimiento
- volatilidad_implicita
- ticker_id
- fecha
- métricas implícitas

## 📈Casos de Uso

- Identificación de riesgo sistémico temprano
- Screening de activos bajo estrés industrial
- Análisis event-driven para gestión de riesgo
- Research cuantitativo exploratorio
- Soporte a decisiones de asignación sectorial

## ⚠️Consideraciones

- Los eventos no siempre tienen impacto inmediato
- La coincidencia temporal aumenta la probabilidad de riesgo, no la certeza

Recomendado complementar con:
- análisis macroeconómico
- correlaciones
- backtesting

## 🚀Próximas Extensiones

- Índice de estrés por industria
- Alertas automáticas por acumulación de eventos negativos
- Visualización de contagio sectorial
- Integración con Python / BI

## 👤Autor

Flavia Hepp
Event-Driven Risk Analytics · SQL · Market Research
