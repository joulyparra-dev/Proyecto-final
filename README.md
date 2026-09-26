# Automatización de creación y aprobación de contenido

Proyecto de automatización para una empresa de marketing que agiliza la creación y aprobación de contenido.

El flujo comienza con una **idea semilla cargada en Airtable**. Luego, **n8n** envía la información a **OpenAI GPT-5-mini**, que genera un borrador del caption.

El contenido se envía a **Slack** para su revisión y aprobación. Si es aprobado, pasa automáticamente al canal de **contenido publicado**, mientras que el proceso queda registrado en Airtable.

### Tecnologías

* **n8n:** automatización y orquestación.
* **Airtable:** almacenamiento y registro.
* **OpenAI GPT-5-mini:** generación de contenido.
* **Slack:** revisión y aprobación.

**Flujo:** Airtable → n8n → OpenAI → Slack → Aprobación → Publicación.

