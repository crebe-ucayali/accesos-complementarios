# Estructura práctica del repositorio AC

Este repositorio corresponde a **AC = Accesos Complementarios**. Forma parte de un **proyecto personal de desarrollo propio** del **Psicólogo Gabriel Berrospi**, orientado a reunir páginas generales de apoyo que complementan los módulos principales de la plataforma CREBE Ucayali.

## Naturaleza del proyecto

AC se organiza como una iniciativa personal desarrollada con recursos propios, puesta a disposición para uso institucional autorizado del CREBE "Señor de los Milagros" - Ucayali. Su estructura busca facilitar navegación, orientación, contacto, consulta de directorios y acceso a recursos complementarios.

## Criterio de organización

La página raíz `index.html` funciona como portada general de AC.

Por compatibilidad con otros módulos, algunas páginas públicas se conservan en la raíz o en rutas específicas cuando otros repositorios enlazan directamente a esas ubicaciones.

La organización recomendada para el crecimiento del repositorio es:

```text
accesos-complementarios/
├── index.html
├── estilos.css
├── README.md
├── AUTORIA.md
├── assets/
│   └── README.md
├── paginas/
│   ├── README.md
│   ├── contacto.html
│   ├── nosotros.html
│   ├── que-hacemos.html
│   └── lineas-de-accion.html
├── directorios/
│   ├── README.md
│   ├── directorio-ciudadano.html
│   └── directorio-institucional.html
├── recursos/
│   ├── README.md
│   ├── calendario.html
│   └── galeria.html
├── firma-tu-visita/
│   ├── README.md
│   ├── index.html
│   ├── estilos.css
│   └── app.js
└── docs/
    ├── README.md
    ├── estructura-del-proyecto.md
    ├── finalidad-y-funciones.md
    └── criterios-de-mantenimiento.md
```

## Uso de carpetas

- `assets/`: recursos visuales generales, como logo, íconos o imágenes de apoyo.
- `paginas/`: páginas informativas generales de AC.
- `directorios/`: páginas relacionadas con directorios y entidades.
- `recursos/`: páginas de apoyo visual o informativo, como calendario y galería.
- `firma-tu-visita/`: componente específico de registro voluntario de visita.
- `docs/`: documentación del repositorio, autoría, finalidad, estructura y mantenimiento.

## Criterio técnico

- HTML: estructura y contenido.
- CSS: diseño visual en archivos separados.
- JS: funcionamiento o interactividad, solo cuando sea necesario.
- MD: documentación interna de autoría, finalidad, propósito, funciones y mantenimiento.

## Autoría

La organización funcional del repositorio, su estructura y documentación forman parte del **proyecto personal y desarrollo original del Psicólogo Gabriel Berrospi**, con uso institucional autorizado al CREBE "Señor de los Milagros" - Ucayali.

## Nota de compatibilidad

Si una página ya está enlazada desde otros repositorios, puede mantenerse una ruta de compatibilidad para evitar enlaces rotos. Esto aplica especialmente a páginas de contacto o accesos generales ya utilizados por otros módulos.