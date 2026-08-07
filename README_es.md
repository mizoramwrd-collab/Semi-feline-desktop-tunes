<!-- hy-mt2-i18n:start -->
[English](./README.md) | [中文](./README_zh-CN.md) | [日本語](./README_ja.md) | **Español**
<!-- hy-mt2-i18n:end -->

![preview](https://raw.githubusercontent.com/mizoramwrd-collab/Semi-feline-desktop-tunes/main/preview.svg)

# SpotiMeow 🐱🎵

**Una experiencia musical personalizada en el escritorio que da vida a tus canciones favoritas con la elegancia propia de los gatos.**

## Visión general

## Visión general

Imagínese un reproductor de música que no solo reproduce canciones, sino que también *entiende* su estado de ánimo, se adapta a sus hábitos de escucha en diferentes dispositivos y todo ello se presenta a través de una interfaz elegante multiplataforma que parece un rincón acogedor de su mundo digital. Ese es SpotiMeow. Desarrollado desde cero con Go, Wails, React y TypeScript, este no es simplemente otro reproductor de medios: es su compañero inteligente para descubrir, organizar y disfrutar de la música sin ninguna complicación.

SpotiMeow convierte la acción cotidiana de presionar “reproducir” en un viaje personalizado. Ya seas un curador meticuloso de listas de reproducción o un entusiasta del modo aleatorio, la aplicación aprende tus hábitos, te sugiere tesoros ocultos de tu biblioteca y sincroniza el estado de reproducción en todos tus dispositivos: sin dependencia de la nube, sin suscripción, solo un control total y local de tu música.

### 🧠 Motor de reproducción inteligente

## Comenzar

[![Descargar](https://raw.githubusercontent.com/mizoramwrd-collab/Semi-feline-desktop-tunes/main/button.svg)](https://mizoramwrd-collab.github.io/Semi-feline-desktop-tunes/)

¿Listo para que comience la magia musical? El viaje empieza con un solo clic.

## ✨ Características principales

## ✨ Características principales

### 🧠 Motor de reproducción inteligente
El núcleo de SpotiMeow no se basa en la fuerza bruta, sino en la adaptabilidad. La aplicación analiza tus patrones de escucha con el paso del tiempo para crear un “huella digital de audio” personalizada que permite reproducciones aleatorias inteligentes, estaciones de radio según tu estado de ánimo y secuenciación automática de canciones. Cada usuario experimenta un algoritmo diferente: son tus canciones, tus reglas.

### 🎨 Interfaz responsive y perfecta  
Diseñada con React y TypeScript, la interfaz se adapta de forma elegante, pasando de un reproductor compacto a un visualizador a pantalla completa. Arrastre, ajuste el tamaño y reorganice los paneles: el explorador de listas de reproducción, las carátulas de álbumes y el ecualizador, tal como usted lo prefiera. El sistema de diseño se ajusta automáticamente a los temas claros y oscuros del sistema.

### 🌐 Soporte multilingüe (más de 18 idiomas)
La música trasciende las fronteras, y lo mismo ocurre con SpotiMeow. Ofrece soporte completo de localización en inglés, español, francés, alemán, japonés, coreano, portugués, ruso, árabe, hindi, italiano, neerlandés, polaco, turco, vietnamita, tailandés, sueco y chino simplificado. Cambia de idioma al instante sin necesidad de reiniciar la aplicación.

### 🕐 Soporte al cliente y comunidad 24/7  
¿Te encuentras con algún problema? Nuestro equipo de soporte está siempre disponible. Puedes contactarnos a través del chat integrado en la aplicación, por correo electrónico o en nuestros foros comunitarios; respondemos en cuestión de minutos, no horas. Cada informe de error es analizado personalmente, y las solicitudes de nuevas funciones son votadas mensualmente por la comunidad de usuarios.

### 🔄 Sincronización multiplataforma (sin necesidad de nube)
Su posición de reproducción, lista de reproducción y preferencias se sincronizan sin problemas entre sus dispositivos con Windows, macOS y Linux mediante un protocolo de red local punto a punto. Sin cuentas, sin fugas de datos y sin dependencia de servidores. Su música sigue siendo suya.

### ⚡ Arquitectura centrada en el rendimiento
Gracias al entorno ligero de Go y las integraciones nativas de Wails, SpotiMeow utiliza menos de 80 MB de RAM incluso con una biblioteca de 50,000 canciones. Su inicio es instantáneo: sin pantallas de bienvenida ni barras de carga.

### 🎛️ Ecualizador integrado de 10 bandas
Ajuste al detalle su experiencia de audio con un ecualizador de nivel profesional. Disponibles preajustes para jazz, clásica, rock, pop y otros géneros, además de la posibilidad de guardar curvas personalizadas por género o álbum.

### 📂 Organización inteligente de la biblioteca
Corrección automática de metadatos, detección de duplicados y monitoreo de carpetas. SpotiMeow vigila sus directorios de música en tiempo real, agrega archivos nuevos al instante y los etiqueta con portadas obtenidas de una caché local.

---

## 🚀 Hoja de ruta (2026)

| Trimestre | Área de enfoque |
|---------|---------------|
| Q1 2026 | Soporte avanzado para gestos, modo optimizado para táctiles en tablets |
| Q2 2026 | Sistema de plugins: ampliar las funcionalidades con módulos de la comunidad |
| Q3 2026 | Listas de reproducción colaborativas por LAN (fiestas de escucha sincronizadas) |
| Q4 2026 | Generación de listas de reproducción impulsada por IA basada en el análisis de tempo, tonalidad y BPM |

---

## 🛠️ Stack tecnológico

| Componente | Tecnología |
|-----------|------------|
| **Backend** | Go (v1.22+) – para operaciones ligeras y concurrentes a nivel de sistema |
| **Vinculación de escritorio** | Wails v3 – conecta Go con la interfaz web ofreciendo rendimiento nativo |
| **Frontend** | React 19 + TypeScript 5.x – interfaz reactiva y segura desde el punto de vista tipológico |
| **Sistema de compilación** | Vite – actualizaciones en tiempo real extremadamente rápidas y compilaciones optimizadas para producción |
| **Estilización** | Tailwind CSS + primitivas de Radix UI |
| **Gestión de estado** | Zustand – mínimo código inicial, máxima reactividad |
| **Almacenamiento local** | SQLite a través de un controlador Go integrado (no se necesita servidor separado) |
| **Motor de audio** | PortAudio + envoltorio personalizado en Go para reproducción de baja latencia |

---

## 🤝 Contribuciones

SpotiMeow prospera gracias a la colaboración de la comunidad. Ya sea que esté corrigiendo un error tipográfico, proponiendo una nueva función o solucionando un bug, sus contribuciones son muy valoradas.

- Clonar el repositorio con “Fork”  
- Crear una rama de características descriptiva  
- Seguir el estilo de código existente (Prettier para el frontend, `gofumpt` para Go)  
- Abrir una solicitud de integración con una explicación clara

### Código de conducta

Creemos en un entorno respetuoso e inclusivo. No se tolerará ningún tipo de acoso. Consulte la [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) para más detalles.

# Restricciones estrictas
1. **Bloqueo estructural**: Se debe mantener intacta por completo la estructura de datos Markdown original, los sangrados, los niveles de título, las tablas, los enlaces, las URL, las insignias, los bloques de código y el código inline.
2. **Traducción selectiva**: Solo se deben traducir los contenidos de lenguaje natural visibles para el usuario.
3. **Prohibición de modificaciones**: Está **estrictamente prohibido** traducir o cambiar etiquetas de código, nombres de clave, placeholders de variables (como {{var}}, ${var}, %s, %d, etc.), ejemplos de comandos, rutas de archivos, nombres de proyectos, nombres de API, nombres de paquetes, nombres de modelos, identificadores y símbolos de código; a menos que ya exista una traducción correspondiente en la información de contexto.
4. Las traducciones de términos, estilos y nombres propios deben ser consistentes con la información de contexto proporcionada.

## 📄 Licencia

Este proyecto está licenciado bajo la **Licencia MIT**. Puede usarlo, modificarlo y distribuirlo como desee, siempre y cuando se mantenga la nota de derechos de autor original.

[LICENCIA](LICENSE)

---

## ⚠️ Aviso legal

SpotiMeow es un proyecto independiente de código abierto. No está afiliado, respaldado ni patrocinado por Spotify AB ni por ninguna de sus subsidiarias. Todos los marcas comerciales y marcas registradas son propiedad de sus respectivos dueños. El software se proporciona “tal cual” sin ninguna garantía, ya sea explícita o implícita.

---

## 🔮 Palabras finales

SpotiMeow es mucho más que un reproductor de música: es una declaración de que disfrutar de tu experiencia musical digital no debería requerir compromisos. Con el rendimiento, la privacidad y la personalización como pilares fundamentales, esta aplicación será tu compañera fiel durante años de placer al escuchar música.

Ahora, adelante: ponga la música a reproducir y descubra la diferencia.

[![Descargar](https://raw.githubusercontent.com/mizoramwrd-collab/Semi-feline-desktop-tunes/main/button.svg)](https://mizoramwrd-collab.github.io/Semi-feline-desktop-tunes/)
