# Mis Finanzas

App web instalable para llevar los ingresos y egresos del hogar, con datos compartidos en Firebase.

- Dirección: https://batchgh.github.io/finanzas/
- Proyecto Firebase: mis-finanzas-hogar-e88b8 (plan Spark, gratis)
- Correos autorizados: richarddarocha21@gmail.com y barbarapaez16@gmail.com

## Primer uso
1. Abre la dirección en el celular.
2. Escribe tu correo autorizado y una contraseña y pulsa "Crear cuenta".
3. Abre el enlace de verificación que llega a tu correo y vuelve a la app: "Ya lo verifiqué".
4. Instálala: en iPhone (Safari) Compartir > "Agregar a inicio"; en Android (Chrome) menú > "Instalar app".

## Archivos
- index.html: la app.
- firebase-config.js: configuración de Firebase y correos permitidos.
- firestore.rules: copia de las reglas publicadas en Firebase (cambiarlas aquí no las aplica; se publican en la consola).
- manifest.webmanifest, sw.js, íconos: para que sea instalable y abra sin conexión.

Para agregar o cambiar un correo: edítalo en firebase-config.js y en las reglas de Firestore (consola de Firebase > Firestore > Reglas > Publicar).
