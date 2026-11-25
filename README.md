# ASIR · Webs estáticas (CV y portfolio)

Sitio web estático de **Jorge Aguado**, estudiante de 2.º de ASIR (Administración de Sistemas Informáticos en Red) en U-tad, con interés en automatización y ciberseguridad.

Contiene dos webs en HTML, CSS y JavaScript, sin base de datos ni código de servidor:

| Carpeta | Contenido |
|---|---|
| [`cv/`](cv/) | Currículum web: perfil, conocimientos técnicos, formación, idiomas y otras experiencias |
| [`portfolio/`](portfolio/) | Portfolio: proyectos **académicos** y **personales** por separado, perfil y contacto |
| [`index.html`](index.html) | Portada con acceso a ambas webs |

## Contexto
Actividad académica de ASIR sobre el alojamiento de varias webs estáticas en un entorno LAMP, sin dominio definido.
Este repositorio guarda el código de las webs, no la configuración del servidor.

## Cómo verlo en local
```bash
python3 -m http.server 8000
```
Después abre `http://localhost:8000/`.

## Estructura
```
.
├── index.html
├── cv/          index · estudios · experiencia · contacto
└── portfolio/   index · proyectos · sobre-mi · contacto
```
Cada web tiene su carpeta `assets/` (CSS, JavaScript y tipografías de iconos). Los ajustes propios están en `assets/css/custom.css` y no modifican los archivos de la plantilla.

## Créditos y licencias
- **CV:** plantilla *Miniport* de [HTML5 UP](https://html5up.net), licencia [CC BY 3.0](https://html5up.net/license).
- **Portfolio:** plantilla *Directive* de [HTML5 UP](https://html5up.net), licencia [CC BY 3.0](https://html5up.net/license).
- Iconos: [Font Awesome Free](https://fontawesome.com). Librerías: jQuery y Responsive Tools.
- Cada carpeta conserva los `LICENSE.txt` y `README.txt` originales de la plantilla.
- Los textos y el contenido personal son de Jorge Aguado.
