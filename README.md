# 🗺️ AccesiMap - Sistema de Mapeo Colaborativo de Espacios Accesibles

<div align="center">

![Estado del Proyecto](https://img.shields.io/badge/Estado-Prototipo-blue)
![Tipo](https://img.shields.io/badge/Tipo-Proyecto%20Universitario-green)
![Versión](https://img.shields.io/badge/Versión-1.0-orange)

**Plataforma colaborativa para mapear y calificar espacios deportivos accesibles**

[Ver Demo](#) · [Reportar Bug](#) · [Solicitar Función](#)

</div>

---

## 📖 Tabla de Contenidos

- [Acerca del Proyecto](#-acerca-del-proyecto)
- [Características](#-características)
- [Capturas de Pantalla](#-capturas-de-pantalla)
- [Funcionalidades](#-funcionalidades)
- [Arquitectura](#-arquitectura)
- [Roadmap](#-roadmap)
- [Equipo](#-equipo)
- [Licencia](#-licencia)
- [Contacto](#-contacto)

---

## 🎯 Acerca del Proyecto

**AccesiMap** es un sistema colaborativo diseñado para ayudar a personas con discapacidad motora a encontrar espacios deportivos y recreativos accesibles. La plataforma combina mapeo interactivo, verificación comunitaria y gamificación para mantener información actualizada y confiable.

### 🎓 Contexto Académico

Este proyecto fue desarrollado como prototipo web para [Nombre del Curso/Asignatura] en [Universidad], con el objetivo de demostrar la implementación de una solución tecnológica inclusiva y centrada en el usuario.

### ⚡ Problema que Resuelve

- Dificultad para encontrar espacios accesibles confiables
- Falta de información actualizada sobre accesibilidad
- Ausencia de verificación comunitaria de los datos
- Necesidad de motivar la participación ciudadana

### 💡 Solución Propuesta

Una plataforma que permite a la comunidad:
- 📍 Mapear espacios accesibles colaborativamente
- ⭐ Calificar accesibilidad por categorías específicas
- 📸 Verificar información con fotos reales
- 🏆 Ganar recompensas por contribuir

---

## ✨ Características

### 🗺️ Mapeo Colaborativo
- Mapa interactivo con geolocalización
- Registro comunitario de lugares
- Filtros por tipo y nivel de accesibilidad
- Calificaciones detalladas por categoría

### 🎮 Gamificación
- Sistema de puntos y recompensas
- Misiones semanales
- Insignias y niveles (Bronce, Plata, Oro)
- Ranking mensual de colaboradores

### ✅ Verificación Comunitaria
- Confirmación por múltiples usuarios
- Sistema de votación de calidad
- Reportes de información incorrecta
- Métricas de confiabilidad

### 👤 Gestión de Perfil
- Perfil personalizable
- Historial de aportes
- Sistema de notificaciones
- Estadísticas personales

---

## 📸 Capturas de Pantalla

### Mapa Principal
<!-- Insertar imagen del mapa -->
![Mapa Principal](docs/images/mapa-principal.png)
*Vista principal del mapa con espacios accesibles marcados*

### Registro de Espacio
<!-- Insertar imagen del formulario -->
![Formulario de Registro](docs/images/formulario-registro.png)
*Formulario para añadir nuevos espacios al mapa*

### Sistema de Calificación
<!-- Insertar imagen de calificación -->
![Calificación](docs/images/sistema-calificacion.png)
*Interfaz de calificación por categorías de accesibilidad*

### Perfil de Usuario
<!-- Insertar imagen del perfil -->
![Perfil](docs/images/perfil-usuario.png)
*Perfil del usuario con puntos, insignias y estadísticas*

### Misiones y Gamificación
<!-- Insertar imagen de misiones -->
![Misiones](docs/images/misiones-semanales.png)
*Panel de misiones semanales y sistema de puntos*

### Ranking
<!-- Insertar imagen del ranking -->
![Ranking](docs/images/ranking-mensual.png)
*Tablero de líderes mensuales*

---

## 🚀 Funcionalidades

### 📍 Épica 1: Sistema de Mapeo

#### 1.1 Búsqueda de Espacios
- Visualización en mapa interactivo
- Geolocalización automática
- Filtros múltiples
- Información detallada por marcador

#### 1.2 Registro de Espacios
**Campos incluidos:**
- Nombre del lugar
- Tipo de espacio
- Dirección completa
- Categorías de accesibilidad
- Galería de fotos

#### 1.3 Calificación de Accesibilidad
**Categorías evaluadas:**
| Categoría | Descripción |
|-----------|-------------|
| ♿ Rampas | Acceso sin escaleras |
| 🚻 Baños | Sanitarios adaptados |
| 🅿️ Estacionamiento | Espacios reservados |
| 🏋️ Equipos | Máquinas adaptadas |
| 👥 Personal | Capacitación en atención |

#### 1.4 Galería Fotográfica
- Subida desde cámara o galería
- Compresión automática
- Múltiples fotos por espacio
- Visualización en galería

#### 1.5 Verificación Comunitaria
- Botón de confirmación
- Contador de verificaciones
- Notificaciones al autor
- Actualización de confiabilidad

### 🎮 Épica 2: Gamificación

#### 2.1 Sistema de Puntos
```
Registrar lugar nuevo → 50 puntos
Subir foto → 20 puntos
Confirmar espacio → 10 puntos
Completar misión → 100 puntos
```

#### 2.2 Misiones Semanales
**Ejemplos:**
- 📍 Visitar 3 parques diferentes
- ➕ Registrar 2 nuevos espacios
- ✅ Confirmar 5 espacios
- 📸 Subir 10 fotos

#### 2.3 Insignias y Niveles
**Niveles:**
- 🥉 **Bronce** (0-500 pts)
- 🥈 **Plata** (501-2000 pts)
- 🥇 **Oro** (2001+ pts)

**Insignias especiales:**
- 🏆 Explorador
- 📸 Fotógrafo
- ✅ Verificador
- 🌟 Colaborador del Mes

#### 2.4 Ranking Mensual
- Top 10 usuarios activos
- Reinicio mensual
- Visualización de logros
- Competencia sana

### 👤 Épica 3: Perfil y Comunidad

#### 3.1 Gestión de Perfil
- Registro con email/Google
- Información personalizable
- Historial de contribuciones
- Visualización de logros

#### 3.2 Notificaciones
- 🎯 Nuevas misiones
- ✅ Aportes confirmados
- 🏆 Insignias desbloqueadas
- 📊 Cambios de nivel
- ⚠️ Reportes

### ✅ Épica 4: Validación

#### 4.1 Votación de Calidad
- Sistema de utilidad
- Métricas de confiabilidad
- Penalización por fraude
- Reputación del usuario

#### 4.2 Reportes
- Formulario de reporte
- Adjuntar evidencia
- Revisión por administrador
- Actualización de datos

---

## 🏗️ Arquitectura

### Estructura de Datos (Conceptual)

```
📦 Base de Datos
├── 👥 Usuarios
│   ├── Información personal
│   ├── Puntos y nivel
│   ├── Insignias
│   └── Historial
├── 📍 Lugares
│   ├── Datos básicos
│   ├── Coordenadas
│   ├── Calificaciones
│   ├── Fotos
│   └── Verificaciones
├── ⭐ Calificaciones
│   ├── Usuario
│   ├── Lugar
│   ├── Categorías
│   └── Comentarios
└── 🎮 Gamificación
    ├── Puntos
    ├── Misiones
    ├── Ranking
    └── Logros
```

### Diagrama de Flujo Principal

```
Usuario → Abre App → Geolocalización → Mapa
                                          ↓
                              Ver espacios cercanos
                                          ↓
                              Seleccionar espacio
                                          ↓
                ┌─────────────────────────┼─────────────────────┐
                ↓                         ↓                     ↓
          Ver detalles              Calificar             Confirmar
                ↓                         ↓                     ↓
           Ver fotos              Ganar puntos           Sumar verificación
```

---

## 🛠️ Tecnologías (Prototipo)

### Plataforma de Prototipado
- **Herramienta:** [Especificar: Figma/Adobe XD/Webflow/etc.]
- **Tipo:** Prototipo web interactivo
- **Propósito:** Demostración académica

### Integraciones Conceptuales
- 🗺️ **Mapas:** Google Maps / Mapbox / OpenStreetMap
- 🔐 **Autenticación:** Google Auth / Email
- 📸 **Almacenamiento:** Cloud storage
- 🔔 **Notificaciones:** Firebase Cloud Messaging
- 📊 **Analytics:** Métricas de uso

---

## 📊 Métricas de Éxito

| KPI | Objetivo | Estado |
|-----|----------|--------|
| Espacios mapeados | 100+ lugares | 🎯 |
| Usuarios activos | 50+ mensuales | 🎯 |
| Tasa de verificación | 70%+ confirmados | 🎯 |
| Fotos por espacio | 5+ promedio | 🎯 |
| Satisfacción | 4.5/5 estrellas | 🎯 |

---

## 🗓️ Roadmap

### ✅ Fase 1: Prototipo (Completado)
- [x] Diseño UI/UX
- [x] Wireframes
- [x] Prototipo interactivo
- [x] Pruebas de usabilidad

### 🚧 Fase 2: Desarrollo (Futuro)
- [ ] Desarrollo backend
- [ ] API REST
- [ ] Base de datos
- [ ] Autenticación

### 🔮 Fase 3: Lanzamiento (Futuro)
- [ ] App móvil nativa
- [ ] Beta testing
- [ ] Marketing
- [ ] Lanzamiento público

### 💡 Funcionalidades Futuras
- Chat comunitario
- Rutas accesibles
- Modo offline
- API pública
- Machine Learning para predicción
- Integración con redes sociales

---

## 👥 Equipo

| Rol | Nombre | GitHub |
|-----|--------|--------|
| 🎨 UX/UI Designer | [Tu Nombre] | [@usuario](#) |
| 💻 Developer | [Nombre] | [@usuario](#) |
| 🧪 Tester | [Nombre] | [@usuario](#) |
| 📊 Product Owner | [Nombre] | [@usuario](#) |

---

## 🎓 Contexto Académico

### Institución
**Universidad:** [Nombre de la Universidad]  
**Facultad:** [Facultad/Departamento]  
**Curso:** [Nombre del Curso]  
**Semestre:** [Período Académico]  
**Profesor:** [Nombre del Profesor]

### Objetivos de Aprendizaje
- ✅ Diseño centrado en el usuario
- ✅ Prototipado interactivo
- ✅ Investigación de usuarios
- ✅ Gamificación en aplicaciones
- ✅ Diseño inclusivo y accesible

---

## 📚 Documentación Adicional

- 📖 [Manual de Usuario](docs/manual-usuario.md)
- 🎨 [Guía de Diseño](docs/guia-diseno.md)
- 📊 [Resultados de Pruebas](docs/pruebas-usabilidad.md)
- 📝 [Historias de Usuario](docs/historias-usuario.md)

---

## 🙏 Agradecimientos

Agradecemos especialmente a:
- 👥 Personas con discapacidad motora que participaron en las pruebas
- 👨‍🏫 Profesores y mentores del proyecto
- 🌐 Comunidades de accesibilidad consultadas
- 🏢 [Organizaciones colaboradoras]

---

## 📄 Licencia

Este proyecto es un **prototipo académico** desarrollado para fines educativos.

```
Copyright © 2024 [Tu Nombre/Universidad]
Proyecto Universitario - Todos los derechos reservados
```

---

## 📧 Contacto

**Desarrollador Principal:** [Tu Nombre]

- 📧 Email: [tu.email@ejemplo.com]
- 💼 LinkedIn: [tu-perfil](#)
- 🐙 GitHub: [@tu-usuario](#)

**Repositorio:** [github.com/usuario/accesimap](#)  
**Demo:** [enlace-demo.com](#)  
**Presentación:** [slides.com/presentacion](#)

---

<div align="center">

**⭐ Si este proyecto te resultó útil, considera darle una estrella ⭐**

Hecho con ❤️ para hacer el mundo más accesible

[Volver arriba](#-acesimap---sistema-de-mapeo-colaborativo-de-espacios-accesibles)

</div>
