<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p Bienvenido. Como verá en adelante, la información es base de desarrollo, con su buen manejo se logran resultados increíbles:
    
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/m2y-4sH8iuA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)       


    .crd.bg_crd_01
      .row.justify-content-center.align-items-center
        .col-auto
          figure
            img(src="@/assets/curso/tema1/t1_01.png", alt="alt", style="width:225px").m-auto
        .col-lg
          p.mb-0 Para la elaboración de este componente, se abordaron varios autores conocidos en #[span.txt--verde información y recolección de datos], de quienes se han citado y referenciado conceptos y ejemplos para los fines educativos de esta materia, en el entendido de que el conocimiento es social y, por lo tanto, es para ser usado por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos aquellos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos de la #[span.txt--azul gestión de empresas pecuarias].   

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
