# Taller de Python — Plantilla LaTeX Grupal

## Estructura del proyecto

```
taller_python/
├── main.tex                   ← Archivo principal (NO editar salvo configuración)
├── secciones/
│   ├── portada.tex            ← Integrante 3
│   ├── seccion1.tex           ← Integrante 1
│   ├── seccion2.tex           ← Integrante 1
│   ├── seccion3.tex           ← Integrante 2
│   ├── seccion4.tex           ← Integrante 2
│   ├── seccion5.tex           ← Integrante 3
│   └── conclusiones.tex       ← Integrante 3
└── imagenes/                  ← Poner capturas de pantalla aquí
```

## División del trabajo

| Integrante | Archivos a editar                          |
|------------|-------------------------------------------|
| 1          | `seccion1.tex`, `seccion2.tex`            |
| 2          | `seccion3.tex`, `seccion4.tex`            |
| 3          | `portada.tex`, `seccion5.tex`, `conclusiones.tex` |

## Cómo compilar

```bash
pdflatex main.tex
pdflatex main.tex   # segunda vez para la tabla de contenidos
```

O usar **Overleaf**: subir toda la carpeta como ZIP y compilar desde ahí.

## Tips

- Para agregar código Python usar el entorno `lstlisting`.
- Para cajas de respuesta usar el entorno `respuesta`.
- Las imágenes van en la carpeta `imagenes/` y se insertan con `\includegraphics`.
- Cambiar `[Título Sección X]` por el título real de cada ejercicio.
