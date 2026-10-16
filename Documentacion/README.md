# Proyecto MiTrufi - Documentación Técnica / Académica

Este repositorio contiene la estructura base para la redacción y gestión de la documentación del proyecto **MiTrufi**, organizada mediante una plantilla modular en **LaTeX**.

---

## 📁 Estructura del Directorio

```plaintext
Documentacion/
│
├── principal.tex       # Documento raíz / maestro de LaTeX (preámbulo, portada y llamadas)
├── principal.pdf       # Documento PDF compilado
│
├── secciones/          # Capítulos y apartados modulares (.tex)
│   └── capitulo_01/
│       └── idea_principal.tex  # Idea principal, problemática, actores y diagramas TikZ
│
├── imagenes/           # Recursos gráficos, capturas y figuras externas
└── documentos/         # Anexos y referencias de apoyo
```

---

## 🎯 Resumen del Proyecto

**Mi Trufi** es una plataforma colaborativa (web y móvil) para modernizar el transporte en rutas interurbanas y urbanas (ejemplo: línea Calamuchita – Tarija con salidas cada 15 minutos). Resuelve la incertidumbre de los pasajeros mediante la función **<<Levantar la mano virtual>>** y telemetría GPS en tiempo real, asiste a los choferes en la gestión de asientos y permite a la secretaría el control digital y despacho puntual de las unidades.

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
  - Numeración superior derecha (`fancyhdr`).
  - Eliminación de recuadros y cajas decorativas en favor de un formato académico/formal limpio.
- [x] Diseño y compilación de la **Portada / Carátula formal** en `principal.tex`.
- [x] Redacción del **Capítulo 1 (`secciones/capitulo_01/idea_principal.tex`)**:
  - Contexto operativo de la ruta Calamuchita – Tarija (intervalos de 15 min).
  - Problemática para pasajeros, choferes y secretaría.
  - Módulos del sistema y función «Levantar la mano virtual».
  - Figuras con estilo APA sobrio y numeración formal.
- [x] Compilación exitosa y limpia en `principal.pdf`.

