Workflow de Automatización con n8n

Este proyecto muestra un flujo creado en n8n que automatiza la recepción de datos desde un formulario web y desde correos de Gmail, para registrarlos automáticamente en una hoja de Google Sheets.

Descripción del Workflow

El flujo se compone de:

On Form Submission → Captura datos enviados desde un formulario.

Gmail Trigger (On Email Received) → Detecta nuevos correos en la cuenta configurada.

Workflow Configuration → Unifica y organiza los datos recibidos.

Append to Spreadsheet → Guarda cada registro como una nueva fila en Google Sheets.

Tecnologías

n8n

Gmail API

Google Sheets API

Archivos

workflow.json → Exportación del flujo para importar en n8n.
