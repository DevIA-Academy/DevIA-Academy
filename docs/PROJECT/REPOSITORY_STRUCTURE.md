# REPOSITORY STRUCTURE

Documento: DOC-006

Estado: Approved

Versión: 1.0

---

# Objetivo

Definir oficialmente la arquitectura del repositorio DevIA Academy.

La estructura únicamente podrá modificarse mediante una ADR aprobada.

---

# Nivel raíz

DevIA-Academy/

academy/

docs/

content/

.gitignore

LICENSE

README.md

---

# academy/

Contiene el contenido académico.

Cada academia es independiente.

Ejemplo

Academia-00-Fundamentos

src/

DevIA.Store/

---

# docs/

Documentación permanente del proyecto.

Brand

DAPS

Decisions

DesignSystem

Project

---

# content/

Producción audiovisual.

templates/

VIDEO-001/

VIDEO-002/

...

---

# Regla General

El código pertenece a academy.

La documentación pertenece a docs.

La producción pertenece a content.

Nunca deberán mezclarse responsabilidades.

---

# Convenciones

Markdown

UPPER_SNAKE_CASE

Carpetas

PascalCase

Assets

kebab-case

Videos

VIDEO-001

VIDEO-002

...

---

# Evolución

Toda modificación deberá documentarse mediante una ADR.