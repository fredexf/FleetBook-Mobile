FleetBook Cloud v2

1. Subir index.html, manifest.webmanifest, sw.js e icon.svg a la raíz del repositorio GitHub Pages.
2. Abrir la URL publicada.
3. Crear cuenta con email y contraseña.
4. Confirmar el email si Supabase lo solicita.
5. Iniciar sesión. La función bootstrap_fleetbook cargará la SW4 inicial.

La URL y la publishable key son públicas por diseño. La seguridad de los datos depende de Supabase Auth y RLS.
Nunca incluir una secret key o service_role en estos archivos.
