# WildRoots – Aplicación Móvil de Turismo Regional – Arequipa, Perú

## 1. Descripción General

La aplicación móvil *WildRoots* complementa la plataforma web permitiendo a los usuarios explorar destinos turísticos regionales desde sus dispositivos móviles. Está pensada para funcionar con conectividad, almacenando datos localmente y sincronizando cambios cuando se restablece la conexión.

Su objetivo es promover el turismo local y sostenible en Arequipa, ofreciendo una herramienta moderna, intuitiva y accesible.

---

## 2. Tecnologías Utilizadas (App Móvil)

### Frontend Móvil
- *React Native* – Framework para desarrollo móvil nativo.
- *Expo* – Herramienta para compilar y ejecutar la app.
- *JavaScript (ES6+)* – Lógica interna y manejo de estados.
- *React Navigation* – Sistema de navegación entre pantallas.

### Backend / Servicios
- *API REST en PHP* – Interfaz entre la app y el sistema web.
- *MySQL* – Base de datos centralizada.
- *Fetch / Axios* – Consumo de la API.

---

## 3. Funcionalidades Principales

### 3.1. Registro e inicio de sesión
- Autenticación mediante credenciales compartidas con la web.
- Validaciones en tiempo real.

### 3.2. Búsqueda y visualización de destinos
- Catálogo de destinos turísticos.
- Filtros por categoría.
- Información completa: fotos, descripción y de acceso.

### 3.3. Publicación y gestión de reseñas
- Publicar y eliminar reseñas.
- Sistema de “me gusta”.

### 3.4. Sistema de calificaciones
- Calificación promedio por destino.
- Calificación personalizada por usuario.

### 3.5. Gestión del perfil del usuario
- Edición de datos personales.
- Preferencias de viaje.
- Historial de destinos y reseñas.

### 3.6. Sincronización en tiempo real
- Los cambios realizados desde la app se reflejan instantáneamente en la plataforma web.

### 3.7. Interfaz intuitiva y moderna
- Diseño limpio y adaptable.
- Navegación simple.
- Compatible con Android.

---

## 4. Requerimientos Funcionales (RF)

1. Registrar y autenticar usuarios.
2. Mostrar lista de destinos turísticos.
3. Buscar y filtrar destinos.
4. Publicar y eliminar reseñas.
5. Reaccionar con “me gusta” a reseñas.
6. Visualizar y actualizar calificaciones.
7. Editar el perfil del usuario.
8. Guardar destinos como favoritos para uso offline.
9. Sincronizar datos con la plataforma web mediante API REST.
---

## 5. Requerimientos No Funcionales

1. *Usabilidad:*  
   Interfaz accesible para usuarios de cualquier nivel tecnológico.

2. *Seguridad:*  
   Autenticación segura con cifrado HTTPS.

3. *Compatibilidad:*  
  Compatible con dispositivos móbiles.

4. *Escalabilidad:*  
   Preparada para integrar nuevas funcionalidades como mapas o geolocalización.

5. * Mantenibilidad:*  
   Código modular basado en componentes reutilizables.

---
