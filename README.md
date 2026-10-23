# Invitaciones Digitales Interactivas - Presentación de Proyectos UMG Quetzaltenango

Invitación web interactiva, de alto rendimiento (60 FPS) y diseño responsivo (*Mobile-First*) para la **Presentación de Proyectos e Innovación Tecnológica** de la Facultad de Ingeniería en Sistemas de Información y Ciencias de la Computación de la Universidad Mariano Gálvez de Guatemala, Campus Quetzaltenango.

---

## 📁 Estructura del Repositorio

El repositorio está organizado para ser desplegado en dos subdominios independientes:

```text
├── variante-11am/              # 👉 Carpeta lista para desplegar en el Subdominio 1 (Evento a las 11:00 AM)
│   ├── index.html              # Código completo con Vanilla CSS y JS embebidos
│   ├── LOGOUMG.jpg             # Imagen de respaldo
│   └── img/
│       ├── logo-umg.png        # Logo UMG sin fondo blanco (recorte ajustado)
│       └── logo-umg-tight.png
│
├── variante-1pm/               # 👉 Carpeta lista para desplegar en el Subdominio 2 (Evento a la 01:00 PM)
│   ├── index.html              # Código completo con Vanilla CSS y JS embebidos
│   ├── LOGOUMG.jpg
│   └── img/
│       ├── logo-umg.png
│       └── logo-umg-tight.png
│
├── index-11am.html             # Acceso directo raíz a la variante 11:00 AM
├── index-1pm.html              # Acceso directo raíz a la variante 01:00 PM
├── index.html                  # Versión base principal
└── README.md
```

---

## 🌟 Características Principales

1. **Logo Institucional de Gran Impacto**:
   - Escudo oficial de la UMG en primer plano y sin fondo blanco, centrado y con dimensiones destacadas.

2. **Cinemática de Scroll Fluida (GPU Accelerated)**:
   - Los elementos emergen con animación suave y, conforme se avanza el scroll, los cuadros superiores se van desvaneciendo hacia arriba (`fade-up`), permitiendo una lectura armónica sin saltos ni espacios vacíos.

3. **Indicador "Deslice hacia abajo" Inteligente**:
   - Botón flotante centrado en pantalla que aparece únicamente tras **2 segundos de inactividad** sin hacer scroll. Al momento de desplazarse, desaparece de inmediato.

4. **Agendar Automáticamente en el Calendario**:
   - Al llegar a la fecha, la tarjeta realiza una micro-animación de pulsación automática (*auto-press*).
   - Al tocar el botón *"Agendar en mi Calendario"*, genera y descarga automáticamente un archivo universal `.ics` con la hora exacta (11:00 AM o 01:00 PM) y recordatorio previo para iPhone, Android y Outlook.

5. **Ubicación y Navegación Directa**:
   - Integración directa con **Google Maps** (trazando ruta con destino prefijado desde la ubicación actual del usuario) y **Waze** con navegación asistida inmediata hacia *El Rinconcito Español, Museo del Jamón, Quetzaltenango*.

6. **Cambio Automático de Pantalla por Fecha y Hora (100% Autónomo)**:
   - **Antes del 14 de Noviembre**: Muestra la invitación interactiva completa.
   - **Sábado 14 de Noviembre (00:00 a 17:59 hrs)**: Cambia automáticamente a la pantalla de gala con el mensaje **"¡ES HOY!"** y la hora correspondiente a cada variante.
   - **Sábado 14 de Noviembre (18:00 hrs en adelante)**: Cambia automáticamente a la pantalla de agradecimiento: **“Gracias por ser parte de la innovación tecnológica.”**.

---

## 🚀 Despliegue en Subdominios

- **Para el subdominio de las 11:00 AM**: Sube el contenido de la carpeta `variante-11am/` directamente a la raíz de tu primer subdominio (ejemplo: `grupo1.tudominio.com`).
- **Para el subdominio de la 01:00 PM**: Sube el contenido de la carpeta `variante-1pm/` directamente a la raíz de tu segundo subdominio (ejemplo: `grupo2.tudominio.com`).

---

**Facultad de Ingeniería en Sistemas de Información y Ciencias de la Computación**  
*Universidad Mariano Gálvez de Guatemala — Campus Quetzaltenango*
