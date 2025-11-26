# WildRoots – Aplicación Móvil de Turismo Regional – Arequipa, Perú

## 1. Descripción General

La aplicación móvil **WildRoots** complementa la plataforma web permitiendo a los usuarios explorar destinos turísticos regionales desde sus dispositivos móviles. Está pensada para funcionar incluso con conectividad limitada, almacenando datos localmente y sincronizando cambios cuando se restablece la conexión.

Su objetivo es promover el turismo local y sostenible en Arequipa, ofreciendo una herramienta moderna, intuitiva y accesible.

---

## 2. Tecnologías Utilizadas (App Móvil)

### Frontend Móvil
- **React Native** – Framework para desarrollo móvil nativo.
- **Expo** – Herramienta para compilar y ejecutar la app.
- **JavaScript (ES6+)** – Lógica interna y manejo de estados.
- **AsyncStorage** – Almacenamiento local para modo offline.
- **React Navigation** – Sistema de navegación entre pantallas.

### Backend / Servicios
- **API REST en PHP** – Interfaz entre la app y el sistema web.
- **MySQL** – Base de datos centralizada.
- **JWT (JSON Web Tokens)** – Autenticación segura.
- **Fetch / Axios** – Consumo de la API.

---

## 3. Funcionalidades Principales

### 3.1. Registro e inicio de sesión
- Autenticación mediante credenciales compartidas con la web.
- Manejo de sesiones con JWT.
- Validaciones en tiempo real.

### 3.2. Búsqueda y visualización de destinos
- Catálogo de destinos turísticos.
- Filtros por categoría.
- Información completa: fotos, descripción, datos culturales y de acceso.

### 3.3. Publicación y gestión de reseñas
- Publicar, editar y eliminar reseñas.
- Agregar fotos en la reseña.
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

### 3.7. Funcionamiento parcial sin conexión
- Acceso a favoritos sin internet.
- Carga previa de datos esenciales.
- Sincronización automática al recuperar conexión.

### 3.8. Interfaz intuitiva y moderna
- Diseño limpio y adaptable.
- Navegación simple.
- Compatible con Android y iOS.

---

## 4. Requerimientos Funcionales (RF)

1. **RF01:** Registrar y autenticar usuarios.
2. **RF02:** Mostrar lista de destinos turísticos.
3. **RF03:** Buscar y filtrar destinos.
4. **RF04:** Publicar, editar y eliminar reseñas.
5. **RF05:** Reaccionar con “me gusta” a reseñas.
6. **RF06:** Visualizar y actualizar calificaciones.
7. **RF07:** Editar el perfil del usuario.
8. **RF08:** Guardar destinos como favoritos para uso offline.
9. **RF09:** Sincronizar datos con la plataforma web mediante API REST.
10. **RF10:** Mostrar notificaciones internas en la app.

---

## 5. Requerimientos No Funcionales (RNF)

1. **RNF01 – Usabilidad:**  
   Interfaz accesible para usuarios de cualquier nivel tecnológico.

2. **RNF02 – Rendimiento:**  
   Carga de información en menos de 3 segundos con conexión estable.

3. **RNF03 – Seguridad:**  
   Autenticación segura con JWT y cifrado HTTPS.

4. **RNF04 – Compatibilidad:**  
   Soporte para Android 8+ y iOS 12+.

5. **RNF05 – Escalabilidad:**  
   Preparada para integrar nuevas funcionalidades como mapas o geolocalización.

6. **RNF06 – Confiabilidad:**  
   Manejo adecuado de errores, caídas de red y reconexiones.

7. **RNF07 – Mantenibilidad:**  
   Código modular basado en componentes reutilizables.

---
