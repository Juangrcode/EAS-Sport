# EAS-Sport

## Ramas GIT
<ul>
<li>Master</li>
  <p>Cuando se inicia un repositorio Git, ser parte de la rama  <strong> master </strong> sobre la que no se trabaja directamente. En ella se mantiene únicamente código estable que se usa para desplegar en producción.</p>
  <li>Develop</li>
  <p>Esta rama es donde estén reflejados los últimos cambios realizados, y que sirve como rama de integración con master. Cuando se decide que se ha llegado a un punto estable y que está listo para ser desplegado, se fusiona con la rama master y se etiqueta incluyendo un comentario que describa la situación. </p>
  <p>Cada fusión en la rama master genera una nueva versión en el proyecto. y por cada version debemos manejar etiquetas.</p>
    <li>Feature</li>
  <p>La rama feature se desarrollan nuevas características del proyecto, partiendo siempre de la rama develop. Incorporando los cambios a la misma, eliminando posteriormente la rama.</p>
  <p>git branch -d feature</p>
      <li>Hotfix</li>
  <p>hotfix se utilizan para corregir errores detectados en el código en producción, por lo que en este caso se parte de la rama master evitando de esta manera incluir cambios realizados en la rama develop que pueden no estar todavía estables.</p>
<li>Realese</li>
  <p>Esta se usa cuando se va a realizar un despliegue de una versión del código en el servidor de producción se abre una rama de este tipo. Una vez abierta se hacen los cambios de configuración relativos al entorno de producción y se sube el código del proyecto al servidor. Cuando el despliegue se completa de forma satisfactoria, la rama release se vuelca a la rama master y se añade una etiqueta con el número de versión correspondiente.</p>
</ul>
# FelipeMG
