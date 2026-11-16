# Rueda Libre — Alquiler de Bicicletas en Medellín

Sitio web frontend para **Rueda Libre**, un servicio de alquiler de bicicletas y recorridos guiados en Medellín. 

El repositorio contiene **dos versiones completas** del proyecto:
1. **Versión principal con Bootstrap 5.3** (ubicada en la raíz y lista para desplegar en GitHub Pages).
2. **Versión base en HTML5 y CSS3 puro** (ubicada dentro de la carpeta `HTML & CSS/`).

---

## Estructura del Repositorio

```text
/
├── index.html                  # Página de inicio (Versión con Bootstrap 5.3)
├── css/
│   └── styles-bootstrap.css    # Estilos personalizados complementarios a Bootstrap
├── img/                        # Recursos gráficos e imágenes compartidas del sitio
├── paginas/                    # Vistas internas (Versión con Bootstrap 5.3)
│   ├── tarifas-bootstrap.html  # Tabla de precios y recorridos guiados
│   └── reservas-bootstrap.html # Formulario de reserva y horarios de atención
│
└── HTML & CSS/                 # Versión desarrollada únicamente con HTML y CSS puro
    ├── index.html              # Página de inicio (sin Bootstrap)
    ├── bitacora.txt            # Registro de cambios y avances del desarrollo
    ├── css/
    │   └── styles.css          # Hoja de estilos nativa
    └── paginas/                # Vistas internas (sin Bootstrap)
        ├── tarifas.html        # Tabla de precios y recorridos guiados
        └── reservas.html       # Formulario de reserva y horarios de atención
```

---

## Guía de Navegación

### 1. Versión Principal (Bootstrap 5.3)
Es la versión activa del repositorio, configurada para funcionar directamente en **GitHub Pages**.
* **Inicio:** Abre `index.html` en la raíz del proyecto.
* **Tarifas y recorridos:** Accede desde el menú superior o directamente en `paginas/tarifas-bootstrap.html`.
* **Reservas:** Accede desde el menú superior, los botones de la flota o en `paginas/reservas-bootstrap.html`.
* **Estilos:** Las reglas personalizadas y variables de color se encuentran en `css/styles-bootstrap.css`.

### 2. Versión Base (`HTML & CSS/`)
Contiene la maquetación original construida sin frameworks externos.
* **Inicio:** Abre `HTML & CSS/index.html`.
* **Vistas internas:** Navega mediante su menú hacia `HTML & CSS/paginas/tarifas.html` y `HTML & CSS/paginas/reservas.html`.
* **Estilos:** Toda la presentación visual reside en `HTML & CSS/css/styles.css`.
* **Documentación del proceso:** Consulta `HTML & CSS/bitacora.txt` para revisar el historial de decisiones y etapas del proyecto.

---

## Tecnologías Utilizadas
* **HTML5** semántico.
* **CSS3** (Variables CSS, Flexbox, diseño responsivo).
* **Bootstrap 5.3** (vía CDN) en la versión principal.
* **Google Fonts** (`Montserrat` y `Open Sans`).