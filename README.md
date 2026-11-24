# Practica5_FerArr
Optimización escena VR

Author: Fernando Arribas del Val

Date: 24/11/2026

------------------------------------------------------------------------------------------------------------------

ENTORNO FAB

70s Mafia Barn Asset Pack - Barsh - Licencia estándar

***** IMPORTANTE: Para acceder al entorno o escena dentro de Unreal vamos a la parte de contenido (sistema de carpetas) y abrimos MafiaBarnPack -> Maps -> L_MafiaBarn_Demo. *****

------------------------------------------------------------------------------------------------------------------

TABLAS MÉTRICAS

------------------------------------------------------------------------------------------------------------------

ANTES

------------------------------------------------------------------------------------------------------------------

<img width="887" height="418" alt="Captura de pantalla 2026-11-24 084859" src="https://github.com/user-attachments/assets/e2be134f-f602-4248-aa96-c3608c942c03" />

------------------------------------------------------------------------------------------------------------------

DESPUÉS

------------------------------------------------------------------------------------------------------------------

<img width="905" height="424" alt="Captura de pantalla 2026-11-24 080531" src="https://github.com/user-attachments/assets/1c649835-d936-4178-85bb-6c8dbc06d22e" />

------------------------------------------------------------------------------------------------------------------

AJUSTES

------------------------------------------------------------------------------------------------------------------

1. Descargar escena con la que trabajar
2. Ajustes de iluminación: cambiar opciones de Rendering en Project Settings, poner luces en modo Estático menos una que se pone en modo Estacionaria, creación de un Lightmap, ajuste del Lightmap resolution a 4 y bake de la iluminación de la escena.
3. Ajustes de texturas: cambiar el LOD Bias en niveles 1, 2 y 3 según el tipo de objeto. Ajustar el tamaño máximo de textura para que se corresponda con el LOD Bias correspondiente.
4. Reducción de Draw Calls: combinar objetos de la escena entre sí
5. Configurar LOD: desactivar Nanite, definir un LOD Group para cada uno de los objetos combinados en el punto anterior

------------------------------------------------------------------------------------------------------------------

CAPTURAS

------------------------------------------------------------------------------------------------------------------

ANTES

------------------------------------------------------------------------------------------------------------------

<img width="796" height="353" alt="Captura de pantalla 2026-11-24 093042" src="https://github.com/user-attachments/assets/794c35c8-b283-4101-b212-38cfa35bd1e0" />
<img width="902" height="370" alt="Captura de pantalla 2026-11-24 093000" src="https://github.com/user-attachments/assets/6e83902a-160c-4774-85f4-f56cebe8029a" />
<img width="887" height="395" alt="Captura de pantalla 2026-11-24 092952" src="https://github.com/user-attachments/assets/0b5deb35-0660-4a64-8405-76b4611a6f51" />
<img width="638" height="348" alt="Captura de pantalla 2026-11-24 092934" src="https://github.com/user-attachments/assets/c0c591b1-f6c4-4af8-8ef9-fc1304d5f8ed" />

------------------------------------------------------------------------------------------------------------------

DESPUÉS

------------------------------------------------------------------------------------------------------------------

<img width="521" height="221" alt="Captura de pantalla 2026-11-24 092547" src="https://github.com/user-attachments/assets/d94f741d-c849-45db-a158-300db4a54bda" />
<img width="918" height="381" alt="Captura de pantalla 2026-11-24 092523" src="https://github.com/user-attachments/assets/fca77c0a-b21b-4422-8c40-8f73d7d914d8" />
<img width="938" height="387" alt="Captura de pantalla 2026-11-24 092505" src="https://github.com/user-attachments/assets/50675335-25ff-4d04-ad5b-98de5e6d2bb9" />
<img width="556" height="323" alt="Captura de pantalla 2026-11-24 092434" src="https://github.com/user-attachments/assets/94e9829c-7527-485c-ab63-b2804199fa1b" />

------------------------------------------------------------------------------------------------------------------
