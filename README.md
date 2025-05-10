# SIGIE

SIGIE, SIstema de Gestión Inteligente de Enlaces es un intento por diseñar un sistema que gestione el contenido de enlaces guardados en un servicio agregador de enlaces online como Pocket o Raindrop.io y que utilice un sistema de inteligencia artificial para clasificar, organizar y obtener conocimiento a partir de ellos.

## Objetivos

El sistema debe:
- Conectarse a un servicio de agregador de enlaces online como Pocket o Raindrop.io y obtener los enlaces guardados por el usuario.
- Ser capaz de obtener el contenido de los enlaces guardados y extraer la información de ellos
- Debe utilizar inteligencia artificial para clasificar y organizar los enlaces guardados por el usuario.
- Debe proveer lo necesario para que se pueda chatear con el sistema.
- Debe ser capaz de obtener los enlaces proactivamente cuando se añaden al agregador.

### Sistemas:

1. **Agregator Handler**: obtiene los enlaces guardados por el usuario y los envía al extractor.
2. **Extractor**: procesa los enlaces y extrae la información de ellos.
3. **Classifier**: clasifica y organiza los enlaces guardados por el usuario.
4. **Chatbot**: permite al usuario chatear con el sistema y obtener información sobre los enlaces guardados.
