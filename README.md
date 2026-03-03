# VoceForm 🎙️🏥

**VoceForm** es un asistente de voz basado en Inteligencia Artificial diseñado para simplificar, agilizar y humanizar el proceso de admisión hospitalaria, con un enfoque especial en pacientes adultos mayores.

Este sistema elimina las barreras tecnológicas para los pacientes al permitirles describir su situación clínica, síntomas e historial médico utilizando lenguaje natural hablado. VoceForm captura el audio, lo transcribe de manera automática y utiliza técnicas avanzadas de Procesamiento del Lenguaje Natural (PLN) para estructurar la información directamente en los campos de un expediente clínico electrónico.

## ✨ Características Principales

* **Interacción por Voz Natural:** Permite a los pacientes hablar libremente sobre su estado de salud sin interactuar con formularios complejos, reduciendo la fricción tecnológica para los adultos mayores.
* **Transcripción de Alta Precisión (Speech-to-Text):** Conversión de audio a texto optimizada para capturar el relato completo del paciente en tiempo real.
* **Reconocimiento de Entidades Médicas (NER):** Identifica, extrae y clasifica términos clínicos clave dentro del discurso no estructurado.
* **Auto-completado de Formularios:** Mapea automáticamente la información detectada a las secciones estándar de admisión:
  * 🤒 **Motivo de consulta y síntomas**
  * 💊 **Medicamentos activos y dosis**
  * 📋 **Antecedentes (alergias, cirugías, enfermedades crónicas)**

## ⚙️ Arquitectura y Flujo de Trabajo

1. **Captura:** El paciente relata su estado a través de un micrófono (ej. *"Vengo porque me duele mucho el pecho desde ayer y tomo aspirina todos los días para la presión"*).
2. **Procesamiento de Voz (STT):** El sistema convierte el audio en una transcripción de texto fiel.
3. **Análisis Clínico (PLN + NER):** El motor extrae entidades: *Síntoma* ("dolor de pecho"), *Duración* ("desde ayer"), *Medicamento* ("aspirina"), *Condición* ("presión
