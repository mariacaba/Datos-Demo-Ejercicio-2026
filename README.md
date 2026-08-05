# Datos-Demo-Ejercicio-2026
Importar la base de datos de Damos Demo actualizada al ejercicio 25/26 previo a la importación desde el asistente de empresas


Selecciona la casilla de verificación de que Sage 200c/SDC está cerrado en los equipos y pulsa el botón de Iniciar restauración 


<img width="1236" height="1086" alt="image" src="https://github.com/user-attachments/assets/6ed6c73f-ebb9-4d03-8873-75bbc685d7f4" />



REQUISITOS

- Ejecutar en el servidor configurado en SageSpainERP.config.
- Cerrar Sage 200c /SDC en todos los equipos.
- Usar una cuenta con permisos sobre PathServer.
EJECUCIÓN

1. Extraer todo el contenido del paquete ZIP en una carpeta local.
2. Ejecutar abrir-restauracion-datos-demo.cmd.
3. Seleccionar el archivo DatosDemo_2026_20260804_143521.zip.
4. Pulsar "Verificar de nuevo".
5. Confirmar que Sage 200c /SDC está cerrado en todos los equipos.
6. Marcar la casilla de confirmación.
7. Pulsar "Iniciar restauración" y aceptar la confirmación final.
SEGURIDAD

- La carpeta DatosDemo activa se conserva como DatosDemo_original.
- Si DatosDemo_original ya existe, se conserva con fecha y hora.
- Si el proceso falla, la automatización intenta recuperar la situación anterior.
  
ARCHIVOS PRINCIPALES

- abrir-restauracion-datos-demo.cmd: lanzador.
- restaurar-datos-demo-gui.ps1: formulario.
- restaurar-datos-demo-desde-zip.ps1: proceso de restauración.
- DatosDemo_2026_20260804_143521.zip: copia de los datos.




 


