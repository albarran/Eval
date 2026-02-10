# Guía Rápida de URLs de GitHub Pages

## 🎯 Acceso Rápido

### ¿Cómo encuentro mi evaluación?

**Opción 1: Desde la página principal**
1. Visita: https://albarran.github.io/Eval/
2. Busca tu código de estudiante en la lista
3. Haz clic en el enlace

**Opción 2: URL directa**
Si conoces tu archivo, construye la URL así:
```
https://albarran.github.io/Eval/[TU_CODIGO].html
```

Por ejemplo:
- Archivo: `12344813_RWNK.md` → URL: https://albarran.github.io/Eval/12344813_RWNK.html
- Archivo: `RUBRICA_EVALUACION.md` → URL: https://albarran.github.io/Eval/RUBRICA_EVALUACION.html

## 📁 Estructura del Sitio

```
Repositorio                           →  GitHub Pages URL
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
/                                     →  https://albarran.github.io/Eval/
├── index.md                          →  https://albarran.github.io/Eval/
├── README.md                         →  https://albarran.github.io/Eval/README.html
├── RUBRICA_EVALUACION.md             →  https://albarran.github.io/Eval/RUBRICA_EVALUACION.html
├── 12344813_RWNK.md                  →  https://albarran.github.io/Eval/12344813_RWNK.html
└── 24-25/                            →  https://albarran.github.io/Eval/24-25/
    ├── index.md                      →  https://albarran.github.io/Eval/24-25/
    ├── README.md                     →  https://albarran.github.io/Eval/24-25/README.html
    └── 14313908_WGLR.md              →  https://albarran.github.io/Eval/24-25/14313908_WGLR.html
```

## 📝 Reglas de Conversión

| Tipo de Archivo | Regla de URL |
|-----------------|--------------|
| `archivo.md` | Se convierte a `archivo.html` |
| `index.md` | Se convierte en la página raíz del directorio |
| `README.md` | Se convierte a `README.html` |
| Directorio con `index.md` | Se accede sin `/index.html` |

## 🕐 Tiempo de Actualización

Cuando se hace un cambio en el repositorio:
1. **GitHub Actions** se ejecuta automáticamente (1-2 minutos)
2. **Compilación Jekyll** procesa los archivos Markdown (30 segundos - 1 minuto)
3. **Despliegue** a GitHub Pages (30 segundos - 2 minutos)

**Total:** Espera entre 2-5 minutos después de un push para ver los cambios reflejados.

## ❓ Preguntas Frecuentes

**P: ¿Por qué mi archivo .md se convierte en .html?**  
R: Jekyll (el motor de GitHub Pages) convierte automáticamente todos los archivos Markdown a HTML para que sean visibles en el navegador.

**P: ¿Puedo acceder a los archivos .md directamente?**  
R: No en GitHub Pages. Para ver el archivo original .md, debes ir al repositorio de GitHub: https://github.com/albarran/Eval

**P: ¿Qué pasa con los archivos que están en .gitignore?**  
R: No se publican en GitHub Pages. Solo los archivos versionados en git se despliegan.

**P: ¿Cómo sé si GitHub Pages está funcionando?**  
R: Visita https://github.com/albarran/Eval/actions para ver el estado de los workflows de GitHub Actions.

## 🔗 Enlaces Útiles

- **Página Principal:** https://albarran.github.io/Eval/
- **Curso 24-25:** https://albarran.github.io/Eval/24-25/
- **Rúbrica:** https://albarran.github.io/Eval/RUBRICA_EVALUACION.html
- **Repositorio GitHub:** https://github.com/albarran/Eval
- **GitHub Actions (estado):** https://github.com/albarran/Eval/actions
