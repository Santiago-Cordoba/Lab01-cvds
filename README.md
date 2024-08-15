# Conflictos al Subir Cambios Simultáneamente

### Conflictos en el Archivo

Cuando se producen conflictos en un archivo debido a cambios simultáneos, Git muestra marcas de conflicto como:


<<<<<<< HEAD
"# Lab01-cvds grupos demjdken  cm dsfm,v m,fv ,v 2v asd asjdjaksdbjkasdjkasdjk" 
=======
"# Lab01-cvds grupos demjdken  cm dsfm,v m,fv ,v 2v asd asjdjaksdbjkasdjkasdjk" 
>>>>>>> 6926a1312d658bcf3ff3f39a9e38f24345714f00


### Primer Laboratorio

**Cvds**  
**profesor:** Óscar Ospina
**Host**: Santiago Córdoba  
**Colaboradores**: Santiago Coronado  
**Fecha**: 08 – 15 -2024

#### 1. ¿Hay una mejor forma de trabajar con Git para no tener conflictos?

Sí, una forma recomendada es el **Git Flow**, que organiza el uso de ramas para una gestión eficiente del desarrollo de software. Git Flow se compone de:

- **Ramas Principales**:
  - **`main`**: Contiene la versión de producción estable.
  - **`develop`**: Contiene la última versión de desarrollo.

- **Ramas de Soporte**:
  - **`feature/*`**: Para desarrollar nuevas características.
  - **`release/*`**: Para preparar una nueva versión de producción.
  - **`hotfix/*`**: Para corregir errores en producción.

#### 2. ¿Qué es y cómo funciona el Pull Request?

- **¿Qué es un Pull Request?**
  
  Un Pull Request es una solicitud para fusionar cambios de una rama a otra en un repositorio de Git. Generalmente se usa para integrar cambios de una rama de desarrollo a una rama principal.

- **¿Cómo Funciona?**
  1. **Crear un Pull Request**: Abre un nuevo PR en la plataforma de gestión de repositorios desde la rama de cambios hacia la rama objetivo.
  2. **Revisión del Código**: Los colaboradores revisan el código, hacen comentarios y sugieren ajustes.
  3. **Fusión de Cambios**: Una vez aprobado, el PR se fusiona en la rama objetivo.
  4. **Cierre del Pull Request**: Después de la fusión, el PR se cierra y la rama de cambios puede eliminarse si ya no es necesaria.

#### 3. Crear y Subir Cambios en Ramas Individuales

Cada miembro del equipo debe crear una rama individual para trabajar en sus cambios y luego subir esas ramas al repositorio para la integración final. 










##### cambio hecho por santiago Córdoba
