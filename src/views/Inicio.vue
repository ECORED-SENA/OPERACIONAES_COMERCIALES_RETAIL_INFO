<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Técnico en operaciones comerciales en retail
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Técnico en operaciones comerciales en retail
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 632223
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 2208
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 15 meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/QkiGcdt2yEs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Bienvenidos al Técnico de operaciones comerciales en retail, una experiencia de aprendizaje de introducción al mundo comercial del retail, el cual tiene como propósito brindar las herramientas necesarias para que el egresado pueda desempeñarse en el área.
      br
      br
      | Realizando labores de organización, exhibición, demostración, control de inventarios, así como el recibo y asignación de importe a bienes y servicios, de consumo masivo, en almacenes de comercio minorista o mayorista, empleando principios éticos en contextos cambiantes del mercado. 
      br
      br
      | El programa se enfoca en tres aspectos importantes:
      br
      br
      | - Atención al cliente.
      br
      br
      | - Procesamiento del recaudo de caja.
      br
      br
      | - Surtido y técnicas de merchandising.
      br
      br
      | La duración del período total de formación del programa es de cuatro trimestres, equivalente a 2.208 horas de formación incluyendo etapa lectiva y productiva, diseñado para desarrollar competencias y brindar herramientas especializadas complementarias de nivel técnico.
      br
      br
      | El programa está estructurado a partir de varios componentes de formación que contienen el contenido temático, las actividades y los recursos que enriquecerán su experiencia formativa.
      br
      br
      | Su aprendizaje será bajo la modalidad virtual en un entorno digital, con el acompañamiento de compañeros e instructores para construir una comunidad de aprendizaje.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación del programa

    p El consumidor actual está muy enterado de los productos y servicios que existen en un mercado tan globalizado como el que se vive en el siglo XXI. El Sena, cumpliendo con su misión de contribuir al desarrollo social, económico y tecnológico del país oferta el programa de Técnico en operaciones comerciales en retail, con la intención de integrar personal a las empresas del sector retail, personas que se vincularían en el trabajo como mercaderistas o impulsadores en el comercio minorista con asiento en Colombia, la cual es la segunda ocupación que reporta mayor número de vacantes y su tasa de colocación del 93 % (OLO - SENA, 2015), con lo que se demuestra que las probabilidades de inserción laboral para los egresados del programa son positivas. Se suma a ello, el crecimiento del comercio al por menor o retail en Colombia, que en el periodo 2010 a 2015, fue de entre 7 % y 10,9 %, cifras superiores, al índice de inflación de este periodo, lo cual demuestra el auge de las empresas pertenecientes a este sector (Espacios, 2017).
      


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar
    ul.lista-ul
        li 
          i.fas.fa-angle-right
          | 220201501 - Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social.
        li 
          i.fas.fa-angle-right
          | 220601501 - Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
        li 
          i.fas.fa-angle-right
          | 210601020 - Atender clientes de acuerdo con procedimiento de servicio y normativa.
        li 
          i.fas.fa-angle-right
          | 240201524 - Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
        li 
          i.fas.fa-angle-right
          | 210201501 - Ejercer derechos fundamentales del trabajo en el marco de la constitución política y los convenios internacionales.
        li 
          i.fas.fa-angle-right
          | 240201526 - Enrique Low Murtra-Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
        li 
          i.fas.fa-angle-right
          | 230101507 - Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
        li 
          i.fas.fa-angle-right
          | 240201529 - Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos de los contextos productivo y social.
        li 
          i.fas.fa-angle-right
          | 240202501 - Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el marco común europeo de referencia para las lenguas.
        li 
          i.fas.fa-angle-right
          | 210301098 - Procesar el recaudo de caja de acuerdo con normativa y manual técnico.
        li 
          i.fas.fa-angle-right
          | 240201528 - Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
        li 
          i.fas.fa-angle-right
          | 240201530 - Resultado de aprendizaje de la Inducción.
        li 
          i.fas.fa-angle-right
          | 260101062 - Surtir productos según plan y técnicas de merchandising.
        li 
          i.fas.fa-angle-right
          | 220501046 - Utilizar herramientas informáticas de acuerdo con las necesidades de manejo de información.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso

    ul.lista-ul
        li 
          i.fas.fa-angle-right
          | Básica Secundaria.
        li 
          i.fas.fa-angle-right
          | Grado noveno (9) con certificación académica.
        li 
          i.fas.fa-angle-right
          | No requiere formación para el trabajo y desarrollo humano.
        li 
          i.fas.fa-angle-right
          | Edad mínima catorce (14) años.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso
    p El egresado en operaciones comerciales en retail es un talento humano formado integralmente bajo el enfoque por competencias, para desempeñarse en labores de organización, exhibición, demostración, control de inventarios, así como el recibo y asignación de importe a bienes y servicios, de consumo masivo, en almacenes de comercio minorista. empleando principios éticos en contextos cambiantes del mercado.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia metodológica
    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas, en ambientes abiertos y pluritecnológicos, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias.
      br
      br
      |Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul.lista-ul
        li 
          i.fas.fa-angle-right
          | El instructor – Tutor.
        li 
          i.fas.fa-angle-right
          | El entorno.
        li 
          i.fas.fa-angle-right
          | Las TIC.
        li 
          i.fas.fa-angle-right
          | El trabajo colaborativo.

  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
