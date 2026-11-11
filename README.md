<div align="center">

# GLMR · OndaPlay

**Modelado de comunicación entre procesos distribuidos**

![UTEQ](https://img.shields.io/badge/UTEQ-Ingenier%C3%ADa%20de%20Software-1f6feb?style=flat-square)
![Asignatura](https://img.shields.io/badge/Aplicaciones%20Distribuidas-ISR--701-8957e5?style=flat-square)
![Actividad](https://img.shields.io/badge/Actividad-GA--TL--02%20FORM-2da44e?style=flat-square)

</div>

---

**Actividad:** GA-TL-02 – FORM – Modelado de Comunicación entre Procesos Distribuidos

**Asignatura:** Aplicaciones Distribuidas (ISR-701) · UTEQ · Séptimo nivel, paralelo A

**Docente:** Gleiston Guerrero Ulloa

**Escenario:** 2 – Plataforma de streaming (OndaPlay)

## Integrantes

| Integrante | Parte del diagrama |
|---|---|
| García Bazurto Kevin Leonel | Acceso, catálogo y licencias |
| Lombeida Escaleras Bryan Humberto | Entrega de video |
| Manotoa Alava Carlos Alexander | Telemetría y recomendaciones |
| Reinoso Vélez Eduardo David | Renovación, pagos y cancelación de suscripciones |

## Contenido del repositorio

| Ruta | Qué contiene |
|---|---|
| `GLMR_OndaPlay MAPA GRUPAL TERMINADO.drawio` | Diagrama principal del grupo (fuente editable en draw.io) |
| `GLMR_OndaPlay.drawio.png` | Exportación en PNG del diagrama principal |
| `notas_presentacion.tex` | Notas de presentación: aporte de cada integrante y preguntas recibidas |
| `notas_presentacion.pdf` | Notas compiladas |
| `APORTES/` | Diagramas individuales (`.drawio`) de cada integrante, que se integraron en el diagrama principal. Incluye el PNG del aporte de Reinoso |
| `MANOTOA ALAVA CARLOS ALEXANDER/Referencias/` | Referencias consultadas por Carlos Manotoa para su parte |

## Cómo abrir el diagrama

1. Entrar a <https://app.diagrams.net> o abrir draw.io Desktop.
2. Abrir `GLMR_OndaPlay MAPA GRUPAL TERMINADO.drawio`.
3. La versión `GLMR_OndaPlay.drawio.png` se ve directamente en GitHub, sin herramientas.

## Cómo compilar las notas

Requisitos: MiKTeX (o TeX Live) con los paquetes `babel` (español), `geometry`, `enumitem`, `url` y `adjustbox`.

Desde la carpeta del repositorio, en una terminal:

```
pdflatex notas_presentacion.tex
pdflatex notas_presentacion.tex
```

Se ejecuta dos veces para resolver referencias internas. El resultado es `notas_presentacion.pdf`. También se compila con TeXstudio (archivo principal `notas_presentacion.tex`, compilador `pdfLaTeX`).