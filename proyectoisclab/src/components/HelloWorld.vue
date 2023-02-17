<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Laboratorio de sistemas y aplicaciones web
      email contacto@isclab.com.mx
      <a href="" target="_blank" rel="noopener"></a>.
    </p>
    <h3>¿Qué hacemos en isclab?</h3>
    <ul>
      <li><a >Desarrollamos aplicaciones con fines de práctica, investigación y responsabilidad social.</a></li>
      <li> <a> Buscamos el desarrollo de nuestros estudiantes a través de la creación de proyectos que sean útiles a la sociedad. 
        ¿Tienes un proyecto en mente? </a></li>
      <li><a> Compártelo con nosotros y buscaremos la manera de ayudarte.</a></li>
    </ul>
    <h3>¿pueden crear un sitio web gratuito para mi proyecto?</h3>
    <ul>
      <li><a >La respuesta corta es sí.

Claro que necesitamos saber en qué consiste el sitio que necesitas y tu historia para valorar el apoyo gratuito en la creación y publicación de tu sitio.

Averigua las condiciones de un sitio web gratuito para nosotros será un placer apoyarte.</a></li>
    
    </ul>
    <h3>¿Qué clase de proyectos realizamos?</h3>
    <ul>
      <li><a>Nuestro laboratorio está pensado para programadores por lo que los productos que creamos se categorizan como software.

El software puede encajar en alguna de estas posibilidades:</a></li>
      <li><a >Aplicación web</a></li>
      
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #e7eeeb;
}
</style>
