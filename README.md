# Directorio
## Descripción

Simple: Vamos a poner en práctica todo lo aprendido en el taller de Git, vamos a implementar una página web muy simple que básicamente es un directorio.

### Estructura de proyecto

- /
  - /js  -> Aquí vamos a guardar archivos .js que cada quién quiera usar en su página.
  - /stylesheets  -> Aquí vamos a agregar los archivos .css para dar formato a nuestras páginas web.
  - /assets -> Aquí vamos a agregar las imágenes y otros assets que ocupemos en las páginas.
  - /pages -> En este directorio vamos a agregar nuestra página personal
  - index.html  -> Esta es nuestra página principal donde vamos a mostrar el listado de todas las personas.


### TO DO
Lo que cada persona vamos a hacer es lo siguiente:
(Vamos a asumir que tienes configurado todo en tu máquina para usar git).

1. Clonar el repositorio.
2. Hacer un nuevo branch llamado "page/[tu-nombre]" desde el branch de develop.
3. Agregar en /pages un .html donde vas a construir tu página de contacto. Ejem: /pages/BillGates.html
4. Codea lo que gustes en tu página personal, conforme hagas cambios agrega tus commits, intenta hacerlo mínimo en 1 commits (Uno para el markup de tu página html, otro para la información y otro para los cambios en contenido que hagas, no hagas todo en un solo commit).
5. Agrega en el archivo index.html un link a tu página con tu nombre.
6. Cuando termines has push de tu nuevo branch al repositorio (la linea de comandos de git te dice como si no lo recuerdas).
7. Una vez que tu branch esté arriba en github, has un Pull Request y después has merge de tu branch con develop, si hay conflictos tienes que resolverlos con git mergetool, hacer commit cuando hayas resuelto los conflictos y hacer push de nuevo, después completar el pull request.
8. Regresa al branch de develop y has un fetch/pull para actualizar tu rama.
9. Tus cambios deben estar visibles en el código independientemente de que alguien más haya hecho commits.
