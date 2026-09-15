# Organización de repositorios

Este espacio contiene los desarrollos **GenAI**.

Los repositorios deberán organizarse de forma homogénea para facilitar su identificación, mantenimiento y colaboración entre los distintos equipos de desarrollo.

## Nomenclatura

Todo repositorio deberá identificarse utilizando como referencia el código del proyecto:

`PRJ-XXXX`

Cuando un mismo PRJ incluya **varios servicios o desarrollos diferenciados**, el nombre del repositorio deberá incorporar también la referencia de **KITT y la acción correspondiente**, de forma que permita identificar claramente el alcance del desarrollo.

**Ejemplo:**

`PRJ-0270-Deploy-ApexAI-Iberia-ACT-0528-Naturgy-Fidelizacion`

En caso de duda sobre la nomenclatura aplicable o sobre cómo identificar un PRJ con varios servicios, deberá consultarse con el **EM correspondiente** antes de crear el repositorio.

## Forma de trabajo

Como criterio general:

1. Los cambios deberán realizarse en **ramas específicas**, evitando trabajar directamente sobre la rama principal.
2. La integración de cambios deberá realizarse mediante **Pull Request**.
3. Los commits deberán ser **claros, descriptivos y relacionados con el cambio realizado**.
4. Se deberá mantener el repositorio ordenado y eliminar ramas o recursos obsoletos cuando corresponda.
5. **No deberán almacenarse contraseñas, tokens, certificados, claves privadas ni ningún otro tipo de secreto o información sensible.**

Ante cualquier duda relacionada con la creación, nomenclatura, organización o estructura de un repositorio, consultar con el **EM correspondiente**.

## Contenido mínimo del repositorio

Cada repositorio deberá incluir, como mínimo:

- `README.md` con una breve descripción del **objetivo y alcance del desarrollo**, instrucciones básicas de puesta en marcha y cualquier consideración relevante.
- Código fuente y configuración necesaria para el correcto funcionamiento del proyecto.
- `.gitignore` adaptado a las tecnologías utilizadas.

La documentación específica de cada desarrollo deberá mantenerse dentro de su correspondiente repositorio y actualizarse cuando se produzcan cambios relevantes.

Ejemplo:
# PRJ-XXXX - Nombre del desarrollo

## Descripción

Breve descripción del desarrollo, su objetivo y el problema que resuelve.

## Alcance

Indicar de forma resumida qué incluye este repositorio y, si aplica, qué servicio o acción de KITT representa.

**PRJ:** `PRJ-XXXX`  
**Acción / Servicio:** `ACT-XXXX`  
**Cliente / Proyecto:** `Nombre`  
**EM:** `Nombre o equipo responsable`

## Arquitectura

Breve descripción de los principales componentes del desarrollo.

Por ejemplo:

- API / Backend
- Frontend
- Integraciones
- Servicios GenAI
- Bases de datos
- Servicios externos

## Requisitos

Indicar los requisitos necesarios para ejecutar el proyecto.

Ejemplo:

- Python 3.x
- Node.js
- Docker
- Acceso a servicios internos necesarios

## Puesta en marcha

Pasos mínimos para ejecutar el proyecto en local.

```bash
# Ejemplo
git clone <repository>
cd <repository>

# Instalación de dependencias
...

# Ejecución
...

## Forma de trabajo

Como criterio general:

1. Los cambios deberán realizarse en **ramas específicas**, evitando trabajar directamente sobre la rama principal.
2. La integración de cambios deberá realizarse mediante **Pull Request**.
3. Los commits deberán ser **claros, descriptivos y relacionados con el cambio realizado**.
4. Se deberá mantener el repositorio ordenado y eliminar ramas o recursos obsoletos cuando corresponda.
5. **No deberán almacenarse contraseñas, tokens, certificados, claves privadas ni ningún otro tipo de secreto o información sensible.**

---

Ante cualquier duda relacionada con la creación, nomenclatura, organización o estructura de un repositorio, consultar con el **EM correspondiente**.
