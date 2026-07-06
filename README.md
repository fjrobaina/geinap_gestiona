🚀 GEINAP – Gestiona Integration

Automatización del procedimiento de gestión y firma electrónica de certificados de asistencia sanitaria mediante la integración entre GEINAP y Gestiona.


📖 Descripción

Este proyecto implementa una plataforma de integración basada en Node-RED que automatiza el ciclo completo de tramitación de certificados de asistencia sanitaria entre GEINAP y Gestiona.

La solución elimina la intervención manual durante el proceso administrativo mediante el uso de:

    API REST de Gestiona
    Bus de Eventos
    Automatización documental
    Sincronización bidireccional
    Gestión automática de expedientes
    Firma electrónica

🎯 Objetivos
    Automatizar la generación de certificados.
    Crear y vincular expedientes automáticamente.
    Enviar documentos al circuito de firma.
    Recuperar automáticamente los documentos firmados.
    Registrar la salida del certificado.
    Sincronizar la información entre ambas plataformas.
    Reducir tiempos de tramitación.
    Mejorar la trazabilidad del procedimiento.

🏗 Arquitectura
                     
                     GEINAP
                     
                        
                        │
                        
                        ▼
                     
                     Node-RED
                        
                        │
        
        REST API + Bus de Eventos
        
                        │
                        
                        ▼
                        
                    Gestiona
                    
                        │
                        
                 Firma electrónica
                 
                        │
                        
                        ▼
                        
                 Registro de salida
                 
                        │
                        
                        ▼
                        
                     GEINAP
                     
                     
🔄 Flujo del procedimiento
      Solicitud
           │
           ▼
      GEINAP
           │
      Generación certificado
           │
           ▼
      Node-RED
           │
      API REST
           │
           ▼
      Gestiona
           │
      Firma electrónica
           │
           ▼
      Bus de Eventos
           │
           ▼
      Documento firmado
           │
      Registro salida
           │
           ▼
      GEINAP
           │
      Actualización estado

⚙ Tecnologías
Node-RED
JavaScript
MQTT
JSON
REST API
HTTP/HTTPS
PostgreSQL
Gestiona API
Bus de Eventos
Firma Electrónica
📂 Estructura del repositorio

    .
    ├── Memoria.pdf
    
    ├── Poster.pdf
    
    └── README.md


✨ Funcionalidades
Generación automática de certificados.
Integración con Gestiona mediante REST.
Consulta periódica del Bus de Eventos.
Gestión automática de expedientes.
Firma electrónica.
Registro de salida.
Sincronización documental.
Gestión de errores y reintentos.
Registro de eventos.
Arquitectura desacoplada.

📊 Beneficios
Eliminación de tareas manuales.
Automatización integral del procedimiento.
Menor tiempo de tramitación.
Mayor trazabilidad.
Integración entre plataformas.
Reducción de errores.
Mejor experiencia para el usuario.

📸 Capturas

Arquitectura
Workflow
Dashboard Node-RED
Póster

Flujo del procedimiento
📚 Documentación
📄 Memoria del proyecto
📑 Póster
📊 Diagramas
📖 Manual de instalación
🔧 Manual de configuración

📈 Estado del proyecto
    Estado	Valor
    Desarrollo	✅ Finalizado
    Documentación	✅ Completa
    Integración	✅ Operativa
    Automatización	✅ Completa

👨‍💻 Autor
    
    Francisco Javier Robaina Pérez
    
    Máster en Ciberseguridad · Ingeniero Informático

📄 Licencia
Este proyecto se publica con fines académicos y de investigación.
No incluye información sensible ni credenciales de producción.

