<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Ofimática

    .row.justify-content-center.mb-5
      .col-lg-4.mb-4.mb-lg-0       
        p.mb-0 #[span.txt--green La ofimática es la respuesta a un mundo cambiante y a un ambiente organizacional cada vez más complejo], adicionando más procesos productivos que se ejecutan de manera simultánea. Las herramientas tecnológicas han permitido mantener el ritmo de los avances empresariales, brindando facilidades para el control, registro y conservación de la información.
      .col-lg-8
        .row
          .col-lg-6.mb-4.mb-lg-0
            .crd.crd--green
              figure
                img(src="@/assets/curso/tema3/t3_01.svg", alt="alt",style="width:300px;").m-auto
          .col-lg-6
            .waves.mb-4           
            p.mb-0 Con la ofimática, es posible mantener el control de innumerables tareas ejecutadas al interior de la empresa. El término es un acrónimo compuesto por las palabras oficina e informático, por lo que se deduce que surge como una herramienta tecnológica que brinda apoyo a tareas administrativas.
     

    .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/t3_02.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Pero esta no se reduce a las herramientas en sí mismas, también incluye los sistemas y métodos necesarios para operarlos, de tal forma que las labores operativas sean paulatinamente reemplazadas por programas automatizados. Al final, los resultados obtenidos deben dirigirse a un procesamiento de datos casi inmediato, una planeación asistida, una programación de tareas, la designación de personal responsable y el seguimiento de los compromisos.

    separador

    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1 Uso 

    .row.justify-content-center
      .col-lg-5
        p Como se ha mencionado previamente, la ofimática busca facilitar el trabajo propio de una oficina, y para ello, ofrece herramientas que ofrecen apoyo para estas tareas. Las siguientes son algunas de las funciones que se desprenden de este concepto:
        figure.mb-4.mb-lg-0
          img(src="@/assets/curso/tema3/t3_03.png", alt="alt", style="width:500px;").m-auto
      .col-lg-7
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta crd--griss")
          div(titulo="Elaboración y procesamiento de documentos")
            p Diseñar documentos y papeles de trabajo cumpliendo con los estándares propuestos por la empresa brinda uniformidad y otorga una identidad característica. Las herramientas más populares para esto son los procesadores de texto y las hojas de cálculo, puesto que cumplen con las tareas típicas de la labor administrativa de una empresa: el diligenciamiento de oficios, y la elaboración de tablas con operaciones aritméticas.
          div(titulo="Registro documental")
            p Otra utilidad fundamental de la ofimática es la de gestionar los documentos y llevar un registro de su trazabilidad con el que sea posible consultar la fecha y hora de su creación y posteriores modificaciones. Esto garantiza el respaldo de los datos a través de diversos mecanismos y mejora la calidad de la supervisión.
          div(titulo="Consulta automatizada")
            p La indización de los documentos permite que su consulta a través de medios electrónicos sea mucho más veloz. Existen softwares con utilidades que permiten consultar a partir de criterios de búsqueda específicos, ya sea por tipo de documento, palabras clave en su nombre o contenido, dimensiones, entre otros.
          div(titulo="Comunicación instantánea")
            p La transmisión oportuna y efectiva de datos es uno de los objetivos de cualquier sistema administrativo. Las organizaciones funcionan como organismos en los que todas las áreas interactúan entre sí, por lo que el poder compartir toda clase de información de forma instantánea, sin importar las distancias o las dimensiones de lo que se desea enviar, aporta nuevas posibilidades para la administración de una empresa.
          div(titulo="Teletrabajo")
            p En los últimos años, esta modalidad de trabajo ha venido tomando más fuerza. El teletrabajo consiste en la ejecución de las labores propias de la relación laboral desde la distancia, haciendo uso de herramientas tecnológicas que permitan acceder a la información de la compañía, de la misma forma en la que garantizan la recepción de los datos producidos por el trabajador. Esta modalidad ofrece grandes ventajas, como la reducción de costos de desplazamiento, o de alquiler de oficinas de gran capacidad, debido a que los trabajadores pueden laborar desde casa. Puede considerarse la evolución lógica del modelo de trabajo tradicional, donde los dispositivos electrónicos empiezan a tomar poco a poco más protagonismo.

    separador

    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2 Herramientas ofimáticas

    .cp.mb-4
      .waves_02
      p Se consideran herramientas ofimáticas los programas informáticos que cumplen con los objetivos descritos previamente. Funcionan a través de aplicativos que permiten desarrollar actividades varias y tan exigentes como el mundo organizacional demanda en la actualidad. A continuación, se relacionan algunas de las herramientas de mayor demanda en ofimática:

    .row.justify-content-center      
      .col-lg-7
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta crd--griss")
          div(titulo="Procesadores de texto")
            p En ellos se elaboran documentos de texto, como cartas, memorandos o comunicados. Su punto fuerte radica en la generación de documentos con contenido alfanumérico, habilitando su modificación casi permanente, en aspectos que van desde la ortografía, presentación o redacción. Con el pasar del tiempo, han adicionado más funcionalidades complementarias, como la evaluación de la redacción o sintaxis, la proposición de sinónimos, la inserción de formas o imágenes, entre otras. 
          div(titulo="Hojas de cálculo")
            p Simulan una hoja de trabajo cuadriculada, puesto que su mecánica se centra en el diligenciamiento de casillas para realizar operaciones matemáticas y análisis estadísticos. Su principal enfoque es el del procesamiento de datos cuantitativos, permitiendo efectuar los cálculos de manera prácticamente instantánea. En la actualidad, incluyen utilidades adicionales, como la elaboración de gráficos o diagramas y el cálculo avanzado de estimaciones o proyecciones.
          div(titulo="Presentación multimedia")
            p Los reproductores de contenido multimedia posibilitan la visualización y escucha de videos, audios, imágenes o fotografías. Son de especial utilidad en casos donde se espera conservar evidencias o generar copias rápidas de documentos físicos. Facilitan el registro de datos diferentes al texto, enriqueciendo el contenido del archivo de la empresa. 
          div(titulo="Bases de datos")
            p Son herramientas destinadas a la conservación de la información según los criterios establecidos por el usuario. Su principal utilidad es la velocidad de búsqueda que ofrecen a documentos de cualquier naturaleza; en ellos se pueden almacenar cantidades significantes de información en ambientes de fácil acceso.
          div(titulo="Programas de mensajería")
            p Los aplicativos pertenecientes a esta categoría permiten la comunicación de forma inmediata o en diferido, así como el envío y recepción de paquetes de información a través de la red. En el presente, es posible enviar casi cualquier tipo de información por alguno de estos sistemas en apenas unos cuantos minutos.
          div(titulo="Utilidades")
            p son aquellos programas que aportan facilidades para tareas más concretas que los anteriores. Suelen ser más ligeros, sencillos y focalizados. Ejemplos de estos son los gestores de notas de audio o texto, calculadoras, agendas, relojes y temporizadores, entre otros. Su objetivo se centra en abordar tareas sencillas de forma más rápida y eficiente que lo que implicaría el uso de los otros sistemas mencionados previamente. 
      .col-lg-5.d-none.d-lg-block        
        figure
          img(src="@/assets/curso/tema3/t3_04.png", alt="alt", style="width:500px;").m-auto

    separador

    #t_3_3.titulo-segundo.color-acento-contenido
      h2 3.3 #[i Softwares] de recolección de datos

    p.mb-4 La recolección de datos es una de las mejoras constantes que se ha hecho en la forma de la información y una de las mejoras notables son los programas software con los que se hace esta gestión desde las TIC, tal como se menciona a continuación:

    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/wsjhQS13OMo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen) 

    p.mb-5 Actualmente, el uso de estas herramientas es tan ampliamente aceptado que, en muchas ocasiones, los usuarios no son siquiera conscientes de su utilidad. En la cotidianidad de la gente, se puede evidenciar el uso de algunas de estas aplicaciones, como las siguientes:

    .bg_waves_01.pb-5
      .row.justify-content-center.mb-5
        .col-lg-5           
          figure
            img(src="@/assets/curso/tema3/t3_05.png", alt="alt", style="505px;").m-auto
        .col-lg-7
          LineaTiempoD.color-secundario
            p(numero="1" titulo="Grabadoras de audio y video") prácticamente, la totalidad de los celulares ofrecidos en la actualidad cuenta con una cámara fotográfica integrada. Con el paso del tiempo, la calidad de los lentes utilizados ha ido mejorando, por lo que hoy día es posible obtener imágenes o videos muy fidedignos con solo un par de acciones. Con ello, la recolección de información en campo ya no demanda grandes inversiones ni una logística compleja, haciendo aún más viables metodologías de recolección de información como la observación y la encuesta.      

            p(numero="2" titulo="Encuestas electrónicas") el sistema tradicional de las encuestas demandaba un trabajo significativo en cuanto a su diseño, impresión, consumo de recursos y el transporte de los documentos hasta la población objeto de estudio; el retorno de estos insumos tras la recolección de información también resultaba costoso, sin contar los riesgos asumidos, como la pérdida de contenido o su deterioro por las condiciones a las que se sometían. Además, una vez recopilados los datos, se hacía necesario transcribirlos en limpio para su posterior tabulación o consolidación, lo que implicaba una gran cantidad de esfuerzo solo organizando la información. 
              br
              br
              |Las encuestas electrónicas solventan una buena porción de las limitantes recientemente descritas, pueden elaborarse y diligenciarse a través de computadoras o dispositivos móviles, ajustándose  a las necesidades de cada usuario, con tamaños y tipos de letra modificables para hacer más cómodo su diligenciamiento. Su conservación suele hacerse en la nube, por lo que los datos pueden ser accedidos desde cualquier ubicación de forma inmediata, y su exportación a hojas de cálculo u otros softwares se hace aún más accesible. Con ello, tanto los costos como el tiempo que se debe destinar se ven reducidos a una mínima porción, lo que abre la posibilidad a encuestas de mayores dimensiones y dirigidas a poblaciones mucho más grandes.

            p(numero="3" titulo="Sistemas modulares integrados") Para ser aplicada de manera estricta, donde se definan las actividades previas y aquellas que pondrán a prueba las afirmaciones estudiadas, de tal forma que se den todas las condiciones necesarias para que el trabajo brinde resultados.

      separador

      #t_3_4.titulo-segundo.color-acento-contenido
        h2 3.4 Licencias

      .cp.mb-5
        .waves_02
        p Los aplicativos informáticos mencionados suelen requerir de autorizaciones por parte del equipo de desarrollo y titular de la propiedad intelectual. Las modalidades disponibles van desde las opciones gratuitas hasta la suscripción de pago por tiempo limitado. Las siguientes son algunas de las alternativas que gozan de mayor popularidad en la actualidad:

      .crd.bg_slider
        SlyderA(tipo="b").p-3.p-lg-4
          .row.justify-content-center.align-items-center
            .col-lg
              h3.txt--azul Software libre
              p Los programas pueden ser usados para cualquier propósito, el acceso al mismo es tan amplio que se pueden hacer todas las modificaciones que el usuario necesite para adaptarlo a sus necesidades. Esto implica que su distribución al público no cuenta con limitaciones, por lo que su desarrollo suele provenir de trabajos colaborativos, donde una comunidad interactúa para mejorar las funcionalidades a partir de un punto base entregado por los desarrolladores.          
            .col-auto
              figure
                img(src='@/assets/curso/tema3/t3_06.png', alt='',style="width:500px;") 

          .row.justify-content-center.align-items-center
            .col-lg
              h3.txt--azul Software semilibre
              p En principio, cuenta con prácticamente las mismas libertades que ofrece el software libre, las limitaciones que lo diferencian del anterior se asocian a aspectos comerciales (puesta a la venta de versiones modificadas) o su vinculación con sistemas operativos libres.          
            .col-auto
              figure
                img(src='@/assets/curso/tema3/t3_07.png', alt='',style="width:500px;")     

          .row.justify-content-center.align-items-center
            .col-lg
              h3.txt--azul Software freeware
              p Los programas pertenecientes a esta categoría siguen siendo de uso gratuito, sin embargo, los usuarios tienen restringido su acceso al código fuente para modificarlo, dado que suele estar protegido con derechos de autor. El ejemplo más común de este tipo de software es la suite de Google, que incluye aplicaciones como Drive, Gmail, calendario u hojas de cálculo. En esta categoría, se pueden implantar ciertas limitaciones de funciones avanzadas o de almacenamiento, que pueden ser desbloqueadas con el pago de una membresía.           
            .col-auto
              figure
                img(src='@/assets/curso/tema3/t3_08.png', alt='',style="width:500px;") 

          .row.justify-content-center.align-items-center
            .col-lg
              h3.txt--azul Software propietario
              p Son aplicativos con limitaciones tanto de uso como de distribución o modificación del código fuente. Estos softwares pueden otorgar ciertos permisos de acceso para modificaciones solo a ciertos usuarios, sin embargo, sin expresa autorización, no podrán ser utilizados por ninguna otra persona.           
            .col-auto
              figure
                img(src='@/assets/curso/tema3/t3_09.png', alt='',style="width:500px;") 

          .row.justify-content-center.align-items-center
            .col-lg
              h3.txt--azul Software comercial
              p Cuentan con toda clase de limitaciones de forma similar al software propietario, pero con la posibilidad de levantar las limitaciones de uso a cambio de un pago. En el campo de la ofimática, el ejemplo más popular es el de la suite de Office, desarrollada por Microsoft. Su acceso está restringido a quien compre la licencia vitalicia de uno de sus programas o pague de forma periódica su suscripción anual, llamada Office 365.           
            .col-auto
              figure
                img(src='@/assets/curso/tema3/t3_10.png', alt='',style="width:500px;")

          .row.justify-content-center.align-items-center
            .col-lg
              h3.txt--azul Demo
              p Son las versiones de prueba de programas que tienen una versión completa y, usualmente, de pago. Para acceder al contenido completo, se hace necesario un desembolso de dinero de forma periódica o a través de la adquisición de una licencia vitalicia. Su propósito es permitir un uso restringido del aplicativo, para otorgarle la oportunidad al usuario de probar si cumple con sus necesidades antes de efectuar el pago          
            .col-auto
              figure
                img(src='@/assets/curso/tema3/t3_11.png', alt='',style="width:500px;")                



      

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
