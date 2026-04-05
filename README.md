# 📖 Manual de Organización y Buenas Prácticas para Proyectos de Ingeniería

[![Estado](https://img.shields.io/badge/Estado-Finalizado-success)]()
[![Versión](https://img.shields.io/badge/Versión-v1.0-blue)]()

## 📌 Descripción del Proyecto
Este repositorio contiene un manual colaborativo diseñado para estandarizar y optimizar el trabajo en equipo en proyectos académicos. Se establecen normativas claras sobre metodologías ágiles (Scrum), comunicación interna, resolución de conflictos y control de versiones, garantizando la trazabilidad y la calidad técnica en cada fase del ciclo de vida del proyecto.

## 👥 Autores
* **Nelson Peña** * **Jorge Sanchez** ## 🗂️ Estructura del Repositorio
* `/documentos/`: Código fuente del manual principal estructurado en formato Markdown.
* `/imagenes/`: Recursos gráficos de apoyo, esquemas y diagramas.
* `/referencias/`: Enlaces a normativas de estilo (APA 7ma Edición) y documentación oficial.

## 🚀 Instrucciones de Uso
Para hacer uso de este manual y sus metodologías en su entorno local:
1. Clone este repositorio utilizando el comando: 
   `git clone https://github.com/Nelsito/manual-buenas-practicas.git`
2. Navegue al directorio principal: `cd manual-buenas-practicas`
3. Puede visualizar el contenido directamente a través de la interfaz de GitHub o exportar el archivo fuente ubicado en `/documentos/manual.md` a formato PDF utilizando su editor preferido.

## 🛠️ Guía de Contribución y Control de Versiones
Para mantener el rigor, la organización y evitar pérdida de datos, todo colaborador debe apegarse estrictamente al siguiente flujo de trabajo:

### 1. Creación de Ramas (Branches)
Bajo ninguna circunstancia se debe trabajar o hacer commits directos sobre la rama `main`. Para cada nueva sección, corrección o funcionalidad, cree una rama descriptiva:
`git checkout -b feature/nombre-de-su-mejora`

### 2. Estructura de Commits
Asegúrese de que sus mensajes de commit sean descriptivos, profesionales y reflejen exactamente los cambios realizados:
`git commit -m "Añade sección de normativas APA y ejemplos de citación"`

### 3. Fusión y Pull Requests (PR)
1. Suba su rama al repositorio remoto: `git push origin feature/nombre-de-su-mejora`
2. Abra un **Pull Request (PR)** hacia la rama `main` en GitHub, explicando en la caja de comentarios qué aporta su código.
3. **Revisión obligatoria:** Solicite el *Code Review* de al menos un compañero de equipo antes de hacer el merge.
4. En caso de conflictos de fusión (*Merge Conflicts*), no fuerce los cambios. Aísle el conflicto localmente, discútalo con el autor de la otra rama y resuelvan la versión final de manera consensuada.