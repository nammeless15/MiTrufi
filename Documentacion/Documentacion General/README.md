# Proyecto MiTrufi - Documentación Técnica / Académica

Este repositorio contiene la estructura base para la redacción y gestión de la documentación del proyecto **MiTrufi**, organizada mediante una plantilla modular en **LaTeX**.

---

## 📁 Estructura del Directorio

```plaintext
Documentacion/
│
└── Documentacion General/
    ├── principal.tex       # Documento raíz de LaTeX (Normas APA, portada y llamadas)
    ├── principal.pdf       # Documento PDF compilado (12 páginas)
    │
    ├── secciones/          # Capítulos y apartados modulares (.tex)
    │   └── capitulo_01/
    │       ├── capitulo_01.tex                         # Archivo maestro del Capítulo 1
    │       ├── 01_introduccion_origen.tex              # 1. Introducción, motivación y caso Calamuchita-Tarija
    │       ├── 02_diagnostico_problematica.tex         # 2. Diagnóstico del problema y matriz comparativa APA
    │       ├── 03_definicion_solucion_plataformas.tex  # 3. Propuesta de valor, separación Web/Móvil y alcance
    │       ├── 04_funcionalidades_clave.tex            # 4. Levantar mano virtual, GPS, cupo y diagramas TikZ
    │       ├── 05_objetivos_proyecto.tex               # 5. Objetivo general y objetivos específicos
    │       └── 06_justificacion_impacto.tex            # 6. Justificación social, económica y viabilidad
    │
    ├── imagenes/           # Recursos gráficos y capturas
    └── documentos/         # Anexos y referencias de apoyo
```

---

## 🎯 Resumen del Proyecto

**Mi Trufi** es una solución integral orientada a modernizar el transporte en rutas interurbanas y urbanas (ejemplo: línea Calamuchita – Tarija con salidas cada 15 minutos). La distribución de plataformas se define según el rol operativo:
- **Secretaría / Administradora:** Plataforma Web de escritorio para despacho, asignación de turnos cada 15 minutos y supervisión de la flota activa.
- **Choferes y Pasajeros:** Aplicación Móvil para consulta y reporte en tiempo real (seguimiento GPS, capacidad de asientos y función **<<Levantar la mano virtual>>**).

---

## 👥 Equipo y Autores

- **Josue Elias Castro Flores** — Desarrollador
- **Cesar Alfredo Mendoza Alarcon** — Desarrollador

---

## 🚀 Estado de Avance

- [x] Configuración del documento bajo **Normas APA (7ma edición)**:
  - Tipografía **Times New Roman 12 pt**.
  - Márgenes de **2.54 cm** en todos los lados.
  - Interlineado **1.5** y sangría de **1.27 cm** en la primera línea.
  - Numeración superior derecha en todo el documento (`fancyhdr`).
  - Sin recuadros ornamentales, con tablas (`booktabs`) y figuras sobrias según APA.
- [x] **Portada formal bajo Normas APA 7ma Edición** en `principal.tex`:
  - Numeración en esquina superior derecha (página 1).
  - Título centrado en negrita, autores, afiliación institucional, descripción y fecha.
- [x] **Índices Formales integrados (`tocloft`)**:
  - **Índice General** (Tabla de contenidos con hipervínculos interactivos y líneas de puntos).
  - **Índice de Figuras** y **Índice de Tablas** con formato APA.
- [x] Desarrollo modular completo del **Capítulo 1: Concepción e Idea del Proyecto**:
  - `01_introduccion_origen.tex`: Motivación y caso real Calamuchita – Tarija (turnos de 15 min).
  - `02_diagnostico_problematica.tex`: Problemas por actor y matriz comparativa tradicional vs. Mi Trufi.
  - `03_definicion_solucion_plataformas.tex`: Propuesta de valor, delimitación y separación Web (Secretaría) y Móvil (Chofer/Pasajero).
  - `04_funcionalidades_clave.tex`: Función «Levantar la mano virtual», GPS, indicador de cupo y diagramas de flujo TikZ.
  - `05_objetivos_proyecto.tex`: Objetivo general y 5 objetivos específicos detallados.
  - `06_justificacion_impacto.tex`: Justificación social, económica, operativa y viabilidad preliminar.
- [x] Compilación exitosa y limpia en `principal.pdf` (**14 páginas** generadas).

