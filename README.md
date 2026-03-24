# Mis Propósitos ✨

Aplicación personal para hacer seguimiento de propósitos y hábitos. Funciona como una **PWA (Progressive Web App)** — se instala en el móvil como una app nativa, sin servidores ni suscripciones.

## Funcionalidades

### 🎬 Películas
- Registro de pelis vistas (semanal) y conjuntas (mensual)
- Saga y número en la saga
- Contador anual y total
- Historial con filtros por año y búsqueda
- Detección de duplicados inteligente

### 📚 Lectura
- Seguimiento de libros leídos con formato (físico, digital, audiolibro)
- Biblioteca de libros físicos pendientes
- Sagas con número de entrega (admite decimales tipo 1.5)
- Estadísticas anuales: leídos, pendientes y comprados
- Historial con búsqueda y ordenación por título, autor o saga

### 🎓 Cursos
- Seguimiento de vídeos vistos por curso
- Registro por fecha (para anotar días pasados)
- Modo "hasta el vídeo nº" además de "añadir vídeos"
- Objetivo de 3 días de curso a la semana en el resumen

### ⚖️ Peso y medidas
- Registro semanal de peso, cintura, cadera y pecho
- Historial completo con notas

### 🏃 Deporte
- Objetivo de 3 sesiones semanales
- Registro con actividad, duración, intensidad y fecha (permite fechas pasadas)
- Cuadrícula semanal visual

### 🏠 Resumen
- Vista rápida del estado de todos los propósitos esta semana
- Copia de seguridad: exportar e importar todos los datos en JSON

## Instalación en Android

1. Abre la URL de GitHub Pages en **Chrome**
2. Menú (⋮) → **Añadir a pantalla de inicio**
3. La app se instala y se abre sin barra del navegador

## Datos

Todos los datos se guardan en el **localStorage** del navegador, en el propio dispositivo. No se envía nada a ningún servidor.

Usa el botón **Exportar datos** en la sección Resumen para hacer copias de seguridad antes de limpiar la caché del navegador.

## Tecnología

HTML + CSS + JavaScript puro, en un único fichero `index.html`. Sin frameworks, sin dependencias, sin build.
