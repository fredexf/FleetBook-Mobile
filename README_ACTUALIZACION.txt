FleetBook Cloud v3.1 — Fotos y audio

Novedades:
- Captura de foto o selección desde galería.
- Grabación de audio desde el teléfono.
- Archivos guardados en el bucket privado fleet-documents.
- Vista previa durante la confirmación.
- Asociación automática del archivo con el mantenimiento confirmado.

No requiere SQL adicional si ya se ejecutó FleetBook_Supabase_Setup_v1.sql.

Actualización:
1. Subir todos los archivos a la raíz de FleetBook-Mobile y reemplazar los existentes.
2. Confirmar el commit.
3. Cerrar completamente la PWA y volver a abrirla.
4. Si permanece la versión anterior, borrar datos del sitio o reinstalar.

Nota:
Esta versión guarda y reproduce audio/fotos. La transcripción automática y la lectura
de facturas/odómetros requerirán una función segura de backend conectada a un modelo de IA.
Nunca debe colocarse una clave secreta de IA dentro de index.html.
