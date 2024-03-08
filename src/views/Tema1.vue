<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Realización de pruebas de #[em Software]

    .d-flex.flex-wrap.flex-lg-nowrap.align-items-center.fondo-color-sistema-i.p-4.mb-4
      figure.mb-4.mb-lg-0.position-relative.figura-deco-1(data-aos="fade-right")
        img.mx-auto(src="@/assets/curso/temas/2.png",style="max-width: 289px;")
      .p-4.p-lg-5.cont_1_1(data-aos="fade-left")
        p.mb-0 Para realizar las pruebas de #[em software], es necesario establecer qué tipos de pruebas serán requeridas por el producto. Esto se debe a que no es necesario utilizar todos los tipos de pruebas existentes, sino más bien aquellas que sean necesarias para cada caso específico. Por esta razón, es crucial que el QA o el líder de pruebas determine qué tipos de prueba se adaptan mejor al proyecto en evaluación. A continuación, se especifican y describen los tipos de pruebas que se pueden utilizar.
    
    .fondo-gradiente-1.posicion-1
      Separador

      #t_1_1.titulo-segundo.color-acento-contenido
        h2 1.1 Tipos de pruebas

      p.mb-4 Las pruebas de #[em software] se pueden clasificar principalmente en dos categorías: pruebas funcionales y pruebas no funcionales. Considerando los diversos aspectos y componentes de un producto de #[em software], se requerirán distintos tipos de pruebas, como pruebas unitarias, pruebas de integración, pruebas de estrés, pruebas de rendimiento, pruebas de escalabilidad, entre otras. Cada uno de estos tipos de pruebas determina la calidad de la aplicación, desde el código fuente hasta la interacción y experiencia del usuario.

      .row.justify-content-center
        .col-lg-10
          .tarjeta.color-secundario.p-3.mb-5.borde-8
            .row.justify-content-around.align-items-center
              .col-auto
                img(src="@/assets/curso/temas/3.svg").img65
              .col
                .row.justify-content-between.align-items-center
                  .col.mb-3.mb-sm-0
                    h4.mb-1 Pruebas y calidad de software
                    p.mb-0.text-small Les invitamos a explorar el video y  descubrir los diferentes tipos de pruebas y enriquecer su conocimiento en esta área clave del desarrollo de #[em software].
                  .col-sm-auto
                    a.boton.color-acento-botones(href="https://www.youtube.com/watch?v=TLs-a1Cok-w" target="_blank")
                      span(style="color: #12263F") Abrir video
                      i.fas.fa-file-video(style="color: #12263F")

      p.mb-4 Algunos de los tipos de pruebas más comunes se describen en los siguientes puntos.

      .cont-titulo-decorativo.p-2.mt-5.mb-4
        .row
          .col-auto.pe-0
            figure
              img(src="@/assets/curso/temas/4.svg")
          .col.align-self-end
            h3.mt-3.mb-0.me-2 Pruebas funcionales

      p.mb-5 Se realizan para verificar las características cruciales para el negocio, incluyendo la funcionalidad y la usabilidad del #[em software]. Estas pruebas aseguran que las funcionalidades y características del #[em software] funcionen y se comporten conforme a lo esperado, sin inconvenientes. Validan la aplicación completa de acuerdo con las especificaciones detalladas en el Documento de Requisitos del #[em Software] (SRS, por sus siglas en inglés). Dentro de este conjunto de pruebas se incluyen las pruebas unitarias, pruebas de regresión, pruebas de interfaz, entre otras.

      .row.justify-content-center.mb-5
        .col-lg-9
          .fondo-color-sistema-j.borde-20.p-4
            .row.align-items-center
              .col-md-6
                figure.mb-4.mb-lg-0
                  img.mx-auto(src="@/assets/curso/temas/5.png",style="max-width: 474px;")
              .col-md-6
                p.mb-0 IBM (2021) plantea que estas pruebas se basan en la ejecución y revisión de las funciones y en su interoperabilidad con sistemas específicos, se llevan a cabo en todos los niveles de prueba, buscan evaluar cada una de las opciones con las que cuenta el paquete informático, principalmente en el comportamiento externo del producto o aplicativo, también se las identifica como de tipo caja negra.
      
      .row.justify-content-center
        .col-lg-8
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 1.] Tipos de pruebas funcionales.
          .fondo-color-sistema-k.borde-20.p-4
            figure.mb-4.mb-lg-0
              img.mx-auto(src="@/assets/curso/temas/6.svg",style="max-width: 540px;",alt="El diagrama presenta un esquema de las Pruebas funcionales en el desarrollo de software, destacando su naturaleza cíclica e interconectada. Se detallan cinco tipos de pruebas: Prueba de interfaz de compatibilidad, Pruebas de aceptación (UAT), Pruebas de regresión, Prueba de interfaz de usuario (GUI), y Prueba de instalación. Cada una es crucial para asegurar diferentes aspectos de la funcionalidad del software, desde la compatibilidad hasta la satisfacción del usuario y la estabilidad después de actualizaciones o cambios")

    .cont-titulo-decorativo.p-2.mt-5.mb-4
      .row
        .col-auto.pe-0
          figure
            img(src="@/assets/curso/temas/4.svg")
        .col.align-self-end
          h3.mt-3.mb-0.me-2 Pruebas unitarias 

    .row.align-items-center.mb-5
      .col-lg-8
        p.mb-4 Estas pruebas se centran en validar elementos como componentes, unidades o piezas de forma individual e independiente dentro de un producto de #[em software], siguiendo el principio del Ciclo de Vida del Desarrollo de #[em Software] (SDLC, por sus siglas en inglés). Cualquier bloque de código, ya sea un procedimiento, función, método, constructor, clase o módulo, puede ser considerado una unidad y, por lo tanto, debe ser objeto de pruebas unitarias. Esto permite determinar su comportamiento y validar si los resultados obtenidos se alinean con los esperados. Las pruebas unitarias deben ser las primeras en realizarse durante la fase de desarrollo y deben ser implementadas por los desarrolladores.

        .p-4.borde-16.fondo-color-sistema-j
          .row.align-items-center
            .col-sm-2
              figure.mb-4.mb-lg-0
                img.mx-auto(src="@/assets/curso/temas/7.svg",style="max-width: 57px;")
            .col-sm-10
              p.mb-0.fw-bold De acuerdo a Mera (2016) también se las conoce como #[em unit testing] son pequeños #[em tests] en los cuales se revisa que el comportamiento de un objeto y su lógica funcione adecuadamente.
      .col-lg-4.order-first.order-lg-last
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/temas/8.png",style="max-width: 388px;")

    p.mb-4 Generalmente, se llevan a cabo durante la fase de desarrollo de las aplicaciones o software. Esta tarea es ejecutada por los programadores, aunque los aseguradores de calidad también pueden participar en su realización. Las razones para desarrollar este tipo de pruebas incluyen:

    .row.justify-content-center.mb-4
      .col-lg-8
        .fondo-color-sistema-k.p-4.borde-20
          .row.align-items-center
            .col-lg-3.col-md-3
              figure.mb-4.mb-lg-0
                img.mx-auto(src="@/assets/curso/temas/9.svg",style="max-width: 141px;")
            .col-lg-9.col-md-9
              ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                li
                  i.fas.fa-circle
                  span Son rápidas de ejecutar, lo que permite realizarlas en gran cantidad.
                li 
                  i.fas.fa-circle
                  span Funcionan como documentación de apoyo para el proyecto.
                li 
                  i.fas.fa-circle
                  span Demuestran que la lógica del código funciona correctamente en todos los casos.
                li 
                  i.fas.fa-circle
                  span Facilitan a los programadores el entendimiento profundo del código base, permitiendo realizar cambios de manera oportuna.
                li 
                  i.fas.fa-circle
                  span Contribuyen a obtener un código de alta calidad.

    p.mb-5 En algunos casos, las pruebas pueden realizarse de manera manual, pero es preferible utilizar herramientas que permitan ejecutar el servicio de la mejor manera posible. Existen muchas herramientas disponibles en el mercado, y estas varían en función del lenguaje de programación que se esté utilizando. A continuación, mencionaremos algunas de las más conocidas:

    .row.mb-5.seccion-tarjetas
      .col-sm-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta--boton.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/11.png')

          h4.text-center XUnit.
          p Es una herramienta de pruebas unitarias para el #[em framework] .NET.

      .col-sm-6.col-lg-3.mb-4.mb-lg-0
        .tarjeta--boton.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/12.png')

          h4.text-center Nunit.
          p Es una herramienta de pruebas de plataformas .NET.

      .col-sm-6.col-lg-3.mb-4.mb-sm-0
        .tarjeta--boton.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/13.png')

          h4.text-center Junit.
          p Es una herramienta de pruebas de aplicaciones Java.

      .col-sm-6.col-lg-3
        .tarjeta--boton.p-4.h-100
          .row.justify-content-center.mb-3
            .col-7
              figure
                img(src='@/assets/curso/temas/14.png')

          h4.text-center PhpUnit.
          p Es una herramienta de pruebas de programación PHP.

    p.mb-4 Para realizar las pruebas unitarias, se deben tener en cuenta los siguientes criterios:

    .row.justify-content-center.mb-4
      .col-lg-8
        .fondo-color-sistema-k.p-4.borde-20
          .row.align-items-center
            .col-lg-3.col-md-3
              figure.mb-4.mb-lg-0
                img.mx-auto(src="@/assets/curso/temas/15.png",style="max-width: 115px;")
            .col-lg-9.col-md-9
              ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                li
                  span.dec-lista A.
                  span Se debe probar un sólo código a la vez.
                li 
                  span.dec-lista B.
                  span Hay que realizar pruebas frecuentemente mientras se programa.
                li 
                  span.dec-lista C.
                  span Se debe corregir los #[em bugs] identificados en las pruebas antes de continuar.
                li 
                  span.dec-lista D.
                  span Cualquier cambio que se realice también debe pasar el #[em test].
      
    .cont-titulo-decorativo.p-2.mt-5.mb-4
      .row
        .col-auto.pe-0
          figure
            img(src="@/assets/curso/temas/4.svg")
        .col.align-self-end
          h3.mt-3.mb-0.me-2 Pruebas de integración
    .fondo-gradiente-2.posicion-1
      .row.align-items-center.mb-5
        .col-lg-4
          figure.mb-4.mb-lg-0
            img.mx-auto(src="@/assets/curso/temas/16.png",style="max-width: 400px;")
        .col-lg-8
          p.mb-4 Estas pruebas se centran en validar distintos módulos o componentes de un producto de #[em software] de tal forma que se verifique su funcionamiento como grupo funcional. Productos como aplicaciones de #[em software], sistemas de información o aplicaciones web están compuestos por diversos componentes, módulos y submódulos distribuidos en distintos niveles y capas, que colaboran y se coordinan para habilitar diferentes funcionalidades.

          .p-3.fondo-float-1.posicion-1.mb-4
            p.mb-0 #[b El objetivo de estas pruebas es asegurar que la integración entre estos componentes sea adecuada y detectar posibles problemas o errores relacionados con la sinergia y comunicación entre ellos.]
          
          .p-4.fondo-color-sistema-j.borde-16
            .row.align-items-center
              .col-md-2
                figure.mb-4.mb-md-0
                  img.mx-auto(src="@/assets/curso/temas/17.svg",style="max-width: 70px;")
              .col-md-10
                p.mb-0 #[b Según Mera  (2016) #[em “Las pruebas de integración se encargan de probar las interfaces entre los componentes o módulos; por ejemplo, el componente validación de usuario con el sistema operativo, el sistema de archivos en integración con el hardware”]]

      p.mb-4 De acuerdo con lo anterior, es importante tener en cuenta los siguientes objetos típicos de prueba:

      .row.justify-content-center.mb-4
        .col-lg-8
          .fondo-color-sistema-k.p-4.borde-20
            .row.align-items-center
              .col-lg-3.col-md-3
                figure.mb-4.mb-lg-0
                  img.mx-auto(src="@/assets/curso/temas/15.png",style="max-width: 115px;")
              .col-lg-9.col-md-9
                ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                  li
                    i.far.fa-check-square
                    span Bases de datos de subsistemas
                  li
                    i.far.fa-check-square
                    span Datos de configuración
                  li
                    i.far.fa-check-square
                    span Configuración del sistema
                  li
                    i.far.fa-check-square
                    span Infraestructura
                  li
                    i.far.fa-check-square
                    span Interfaces

      .cont-titulo-decorativo.p-2.mt-5.mb-4
        .row
          .col-auto.pe-0
            figure
              img(src="@/assets/curso/temas/4.svg")
          .col.align-self-end
            h3.mt-3.mb-0.me-2 Pruebas no funcionales
      
      p.mb-4 Estas pruebas, similares a las pruebas funcionales, se diferencian en que se realizan bajo condiciones de carga de rendimiento para evaluar aspectos como #[b la fiabilidad, usabilidad, escalabilidad, instalación, confiabilidad y seguridad del software]. Generalmente, se llevan a cabo mediante herramientas o soluciones automatizadas.

      .row.justify-content-center.mb-5
        .col-lg-8
          .fondo-color-sistema-j.borde-16.p-3.ps-5
            p.ms-md-5.mb-0 #[b #[em Según Mera (2016) en este tipo de pruebas se comprueban los requisitos basados en la operación de un software. Para verificar la carga que resiste el producto software, identificando si su rendimiento es el adecuado o si es estable a nivel de contacto con el servidor.]]
      
      p.mb-5 Algunos aspectos, como el rendimiento de una aplicación, pueden ser complejos; sin embargo, esta prueba permite evaluar la calidad del #[em software] a probar. La calidad se basa principalmente en factores como el tiempo, la precisión, la estabilidad, la corrección y la durabilidad del producto bajo diversas circunstancias adversas. A partir de estos criterios de calidad, es posible explorar distintos tipos de pruebas no funcionales, tales como:

      SlyderF.estilo-slyder(columnas="col-lg-6 col-xl-4")
        .tarjeta.color-secundario.p-4
          figure.mb-4
            img.mx-auto(src="@/assets/curso/temas/18.svg",style="max-width: 124px;")
          p.mb-4 #[b Pruebas de carga]
          p.mb-0 Simulan la demanda esperada que puede tener una aplicación y mide el resultado.
        .tarjeta.color-secundario.p-4
          figure.mb-4
            img.mx-auto(src="@/assets/curso/temas/19.svg",style="max-width: 124px;")
          p.mb-4 #[b Pruebas de rendimiento]
          p.mb-0 Se calcula la respuesta del programa con diferentes medidas de peticiones del usuario.
        .tarjeta.color-secundario.p-4
          figure.mb-4
            img.mx-auto(src="@/assets/curso/temas/20.svg",style="max-width: 124px;")
          p.mb-4 #[b Pruebas de estrés]
          p.mb-0 Nos permite saber cuántos usuarios o peticiones puede soportar el programa, con esta prueba determinamos si el sistema es estable. 
        .tarjeta.color-secundario.p-4
          figure.mb-4
            img.mx-auto(src="@/assets/curso/temas/21.svg",style="max-width: 124px;")
          p.mb-4 #[b Pruebas de volumen]
          p.mb-0 Consiste en probar el funcionamiento del programa con ciertos volúmenes de datos.
        .tarjeta.color-secundario.p-4
          figure.mb-4
            img.mx-auto(src="@/assets/curso/temas/22.svg",style="max-width: 124px;")
          p.mb-4 #[b Pruebas de usabilidad]
          p.mb-0 Se centran en validar que tan fácil se utiliza el programa en cuanto a facilidad de aprendizaje, eficiencia, memorización, errores y satisfacción.
        .tarjeta.color-secundario.p-4
          figure.mb-4
            img.mx-auto(src="@/assets/curso/temas/23.svg",style="max-width: 124px;")
          p.mb-4 #[b Pruebas de robustez]
          p.mb-0 Son las encargadas de verificar la capacidad del programa para soportar entradas o instrucciones incorrectas. Una de sus características principales es implementar mecanismos de software de detección de errores en el hardware.

      .cont-titulo-decorativo.p-2.mt-5.mb-4
        .row
          .col-auto.pe-0
            figure
              img(src="@/assets/curso/temas/4.svg")
          .col.align-self-end
            h3.mt-3.mb-0.me-2 Pruebas de rendimiento

      .row.align-items-center.mb-4
        .col-lg-8
          p.mb-4 Las pruebas de rendimiento son un tipo de pruebas no funcionales realizadas con el propósito de determinar la estabilidad, escalabilidad y velocidad de una funcionalidad específica en el producto de #[em software]. El objetivo de estas pruebas es evaluar el comportamiento de la aplicación considerando diferentes parámetros de referencia del sistema y de la red, como #[b la capacidad de la CPU, la velocidad de renderizado o carga de páginas, el manejo del tráfico, la concurrencia, el consumo de recursos del servidor], entre otros. Dentro de esta categoría, podemos distinguir las pruebas de carga y las pruebas de estrés.

          .p-3.fondo-color-sistema-j.borde-16
            .row.align-items-center
              .col-md-2
                figure.mb-4.mb-md-0
                  img.mx-auto(src="@/assets/curso/temas/24.svg",style="max-width: 61px;")
              .col-md-10
                p.mb-0 #[b #[em Según IBM (2021) estas pruebas sirven para evaluar lo rápido que el programa realiza una tarea en condiciones específicas de trabajo, también evalúa la escalabilidad, fiabilidad y uso de los recursos.]]

        .col-lg-4.order-first.order-lg-last
          figure.mb-4.mb-lg-0
            img.mx-auto(src="@/assets/curso/temas/25.png",style="max-width: 400px;")

      p.mb-4 El mismo autor expresa que los objetivos de estas pruebas son:

      .tarjeta--container.row.mb-5
        .col-md.tarjeta.fondo-color-sistema-k.p-5
          .row.justify-content-center.mb-4
            .col-6
              figure
                img.mx-auto(src='@/assets/curso/temas/26.svg',style="max-width: 142px;")
          
          h3.text-center Identificar y localizar problemas de rendimiento.
          p Es permitir encontrar un fallo en el rendimiento, y también ayudar a localizar en que parte está ese problema para poder solucionarlo.
        .col-md.tarjeta.fondo-color-sistema-m.p-5
          .row.justify-content-center.mb-4
            .col-6
              figure
                img.mx-auto(src='@/assets/curso/temas/27.svg',style="max-width: 142px;")
            
          h3.text-center Verificar el cumplimiento de los SLA (Acuerdos de Nivel de Servicio).

          p Se utiliza para medir los tiempos de respuesta del #[em software] en condiciones y tiempos específicos.
        .col-md.tarjeta.fondo-color-sistema-k.p-5
          .row.justify-content-center.mb-4
            .col-6
              figure
                img.mx-auto(src='@/assets/curso/temas/28.svg',style="max-width: 142px;")
            
          h3.text-center Localizar cuellos de botella.

          p Ayudar a detallar en qué lugar se generan estos cuellos de botellas si se debe a problemas de hardware como CPU, memoria, o es el ancho de banda.

      .cont-titulo-decorativo.p-2.mt-5.mb-4
        .row
          .col-auto.pe-0
            figure
              img(src="@/assets/curso/temas/4.svg")
          .col.align-self-end
            h3.mt-3.mb-0.me-2 Ventajas y desventajas de los tipos de pruebas.

    p.mb-4 Aplicar los distintos tipos de pruebas puede asegurar que el #[em software] funcione conforme a lo esperado en todo momento, garantizando así su calidad. Por lo tanto, es esencial, para su aplicación, identificar las ventajas y desventajas de cada uno, con el fin de determinar las diferencias entre ellos. Podemos observar las ventajas de estos tipos de pruebas en el siguiente recurso.

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta no-border-radius tarjeta--azul")
      .row.contenedor-cuerpo-acordion-a.align-items-center(titulo="Pruebas de rendimiento")
        .col-md-6.mb-4.mb-md-0
          ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
            li
              i.far.fa-check-square
              span Evalúa la velocidad y escalabilidad de la aplicación.
            li
              i.far.fa-check-square
              span Determina los cuellos de botella para las mejoras de rendimiento.
            li
              i.far.fa-check-square
              span Detecta errores que se pasan por alto en las pruebas funcionales.
            li
              i.far.fa-check-square
              span Mejoras de características y optimización del sistema.

            li
              i.far.fa-check-square
              span Garantiza la fiabilidad de la aplicación web bajo una gran carga.
      
        .col-md-6
          figure
            img.mx-auto(src="@/assets/curso/temas/29.png",style="max-width: 400px;")
      .row.contenedor-cuerpo-acordion-a.align-items-center(titulo="Pruebas funcionales")
        .col-md-6.mb-4.mb-md-0
          ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
            li
              i.far.fa-check-square
              span Se asegura de que la aplicación esté libre de defectos.
            li
              i.far.fa-check-square
              span Garantiza el comportamiento requerido de las funcionalidades.
            li
              i.far.fa-check-square
              span Verifica que la arquitectura sea la correcta con la seguridad requerida.
            li
              i.far.fa-check-square
              span Mejora las funcionalidades generales y la calidad.
        .col-md-6
          figure
            img.mx-auto(src="@/assets/curso/temas/30.png",style="max-width: 400px;")
      .row.contenedor-cuerpo-acordion-a.align-items-center(titulo="Pruebas de integración")
        .col-md-6.mb-4.mb-md-0
          ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
            li
              i.far.fa-check-square
              span Asegura de que en la aplicación todos los módulos se encuentren bien integrados y funcionen juntos según lo requerido.

            li
              i.far.fa-check-square
              span Detecta conflictos y problemas interconectados para solucionarlos antes de crear un problema más grande. 
            li
              i.far.fa-check-square
              span Verifica la fiabilidad, estabilidad y funcionalidad entre módulos diferentes.
       
        .col-md-6
          figure
            img.mx-auto(src="@/assets/curso/temas/31.png",style="max-width: 400px;")
      .row.contenedor-cuerpo-acordion-a.align-items-center(titulo="Pruebas unitarias")
        .col-md-6.mb-4.mb-md-0
          ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
            li
              i.far.fa-check-square
              span Detecta errores en las nuevas funcionalidades desarrolladas de manera temprana.

            li
              i.far.fa-check-square
              span Detecta problemas desde el inicio, esto permite reducir los costos de las pruebas.
            li
              i.far.fa-check-square
              span Con una mejor refactorización del código mejora la calidad del código.
            li
              i.far.fa-check-square
              span Permite una buena documentación y simplifica la integración.

       
        .col-md-6
          figure
            img.mx-auto(src="@/assets/curso/temas/32.png",style="max-width: 400px;")

    .cont-titulo-decorativo.p-2.mt-5.mb-5
      .row
        .col-auto.pe-0
          figure
            img(src="@/assets/curso/temas/4.svg")
        .col.align-self-end
          h3.mt-3.mb-0.me-2 Desventajas de los tipos de pruebas

    .row.align-items-center.justify-content-center.mb-5
      .col-md-5.col-sm-6.col-lg-3
        .mb-4.mb-lg-0.fondo-color-sistema-k.borde-8.p-2
          figure
            img.mx-auto(src="@/assets/curso/temas/34.svg",style="max-width: 94px;")
      .col-lg-9
        p.mb-0 Todos los tipos de pruebas mejoran la experiencia del usuario, las funcionalidades y garantizan la calidad del #[em software]. Esto significa que, más que desventajas, lo que encontramos son ventajas en su aplicación. Sin embargo, el tiempo y el costo asociados a la realización de pruebas de #[em software] podrían considerarse como desventajas. Llevar a cabo pruebas demanda recursos y esfuerzos, y existe el riesgo de obtener resultados inexactos. No obstante, omitir las pruebas en las aplicaciones podría acarrear problemas serios al producto.

    .fondo-gradiente-1.posicion-2
      .cont-titulo-decorativo.p-2.mt-5.mb-5
        .row
          .col-auto.pe-0
            figure
              img(src="@/assets/curso/temas/4.svg")
          .col.align-self-end
            h3.mt-3.mb-0.me-2 Documentos de caso de pruebas

      .row.align-items-center.justify-content-center.mb-5
        .col-md-5.col-sm-6.col-lg-3.order-first.order-lg-last
          .mb-4.mb-lg-0.fondo-color-sistema-k.borde-8.p-2
            figure
              img.mx-auto(src="@/assets/curso/temas/35.svg",style="max-width: 94px;")
        .col-lg-9
          p.mb-0 Los productos derivados del proceso de desarrollo de #[em software] son conocidos como artefactos; entre ellos se incluyen el código fuente, los defectos identificados, el plan de pruebas, los casos de prueba y los scripts de prueba. El aseguramiento de la calidad del #[em software] (SQA, por sus siglas en inglés) involucra artefactos específicos que se generan en las distintas fases del proceso de SQA, los cuales se detallan a continuación:

      .row.justify-content-center.mb-4
        .col-lg-4.col-md-6.mb-4
          .tarjeta-personalizada-1.tarjeta-personalizada-1--color-1.h-100
            .figura-flecha.mb-4.me-4
              h4.figura-flecha__titulo.mb-0 Planificación
              figure.figura-flecha__fig
                img.mx-auto(src="@/assets/curso/temas/36.png",style="max-width: 228px;")
            p.px-3.pb-4 En esta etapa se realiza el plan de pruebas como documento que describe un enfoque sistemático para probar un sistema, así como el informe de resultados de pruebas que organiza y presenta un análisis resumido de los resultados de las pruebas para su auditoría y evaluación.
        .col-lg-4.col-md-6.mb-4
          .tarjeta-personalizada-1.tarjeta-personalizada-1--color-2.h-100
            .figura-flecha.mb-4.me-4.ps-2
              h4.figura-flecha__titulo.mb-0 Construcción
              figure.figura-flecha__fig
                img.mx-auto(src="@/assets/curso/temas/37.png",style="max-width: 228px;")
            p.px-3.pb-4 En esta etapa se encuentran los casos y script de prueba como conjunto de condiciones con las cuales un tester debe determinar si un sistema funciona según lo requerido.
        .col-lg-4.col-md-6.mb-4
          .tarjeta-personalizada-1.tarjeta-personalizada-1--color-1.h-100
            .figura-flecha.mb-4.me-4
              h4.figura-flecha__titulo.mb-0 Ejecución
              figure.figura-flecha__fig
                img.mx-auto(src="@/assets/curso/temas/36.png",style="max-width: 228px;")
            p.px-3.pb-4 En esta etapa se obtiene el resultado de la ejecución de pruebas, recopilando la información relacionada con los resultados de la ejecución de cada script de prueba.

      .row.mb-4
        .col-lg-8.mb-4.mb-lg-0
          p.mb-4 En el diseño de las pruebas de #[em software], es crucial identificar y describir los casos de prueba. Para documentar un caso de prueba, es necesario comprender que este incluye un conjunto de variables o condiciones bajo las cuales un probador determina si un sistema funciona de acuerdo con lo esperado. Asimismo, es importante destacar que la documentación de un caso de prueba se convierte en una tarea manejable si se dispone de la información necesaria para su elaboración. Al momento de probar un #[em software], la documentación de casos de prueba es de gran utilidad, ya que se transforma en una herramienta esencial en el proceso de registro, seguimiento y control.
          p.mb-0 A continuación, se nombran los elementos principales que debe tener un caso de prueba.
        .col-lg-4
          .fondo-color-sistema-k.borde-8
            figure
              img.mx-auto(src="@/assets/curso/temas/39.svg",style="max-width: 183px;")

      .titulo-sexto.color-acento-contenido
        p.mb-0 #[b Tabla 1.] Elementos de un caso de prueba.

      .tabla-a.color-acento-contenido.mb-5.bg-white
        table
          thead
            tr
              th Elemento 
              th Caso de prueba
          tbody
            tr
              td Identificador
              td Identificador	Puede ser alfanumérico o numérico.
            tr
              td Nombre
              td Nombre	Nombre del caso de prueba de manera concisa.
            tr
              td Descripción 
              td Objetivo del caso de prueba, también describe que probara, en ciertas ocasiones se incluye el ambiente de pruebas.
            tr
              td Número de orden Ejecución
              td Orden en la cual se ejecuta el caso de prueba, en la situación de que se tengan múltiples casos de prueba.
            tr
              td Requerimiento asociado
              td Si se plantea un caso de prueba se debe saber a qué requerimiento va asociado para mantener la trazabilidad.
            tr
              td Precondición
              td Estado en la cual se debe encontrar el sistema antes de comenzar la prueba.
            tr
              td Postcondición
              td El estado en que debe encontrarse el sistema luego de ejecutar la prueba.
            tr
              td Resultado esperado
              td Objetivo que debe ser alcanzado posterior a ejecutarse la prueba.

    p Identificar, describir y documentar casos de prueba facilita el trabajo cuando es necesario evaluar y comparar las modificaciones a los requerimientos inicialmente definidos por el cliente a lo largo del tiempo. Este seguimiento permite verificar que los resultados obtenidos estén acordes con lo requerido o solicitado, logrando así la satisfacción del cliente. Esto convierte a los casos de prueba en un aliado principal al momento de garantizar la calidad del #[em software].

    .cont-titulo-decorativo.p-2.mt-5.mb-4
      .row
        .col-auto.pe-0
          figure
            img(src="@/assets/curso/temas/4.svg")
        .col.align-self-end
          h3.mt-3.mb-0.me-2 Ejecución de las pruebas.

    .row.align-items-center.mb-4
      .col-lg-8
        p.mb-0 La ejecución de pruebas comienza con la creación de los datos de prueba necesarios para llevar a cabo los casos de prueba establecidos. Esta ejecución puede ser tanto automatizada como manual; en ambos casos, es fundamental registrar y documentar los fallos detectados en el sistema, así como sus correcciones posteriores. En la siguiente figura se ilustra el flujo de actividades relacionadas con la ejecución de pruebas.
      .col-lg-4
        figure.mb-4.mb-lg-0
          img.mx-auto(src="@/assets/curso/temas/40.png",style="max-width: 400px;")

    .titulo-sexto.color-acento-contenido
      p.mb-0 #[b Figura 2.] Diagrama Actividades
    
    .fondo-color-sistema-k.borde-18.p-lg-5.p-md-4.p-3.mb-5
      figure
        img.mx-auto(src="@/assets/curso/temas/41.svg",style="max-width: 1030px;",alt="La figura muestra un flujo de trabajo para la gestión de pruebas en el desarrollo de software, comenzando con inicio y concluyendo con fin. Se inicia con la especificación de casos de prueba que alimenta un plan de pruebas, seguido de planificar calendario de ejecución, que conduce a verificar entorno de pruebas. Luego se procede a ingresar datos de prueba, seguido de evaluar criterios de entrada, que lleva a ejecutar pruebas. Paralelamente, cualquier incidencia reportada retroalimenta el proceso de ingresar datos de prueba. Después de ejecutar las pruebas, se pueden gestionar incidencias que a su vez pueden afectar la ejecución de las pruebas. Finalmente, se genera un informe de pruebas, que completa el ciclo.")

    .fondo-gradiente-3.posicion-1
      p.mb-5 El diagrama de actividades mencionado anteriormente detalla el flujo que debe considerarse al momento de ejecutar las pruebas de #[em software]. Por esta razón, a continuación se describen cada una de las actividades implicadas.

      .row.justify-content-center
        .col-lg-4.col-md-6.mb-4
          .d-flex.w-100.flex-column.h-100
            .p-1.px-5(style="min-height:53px;display:flex;justify-content: center;align-items:center;background-color: #602492;border-top-left-radius: 8px;border-top-right-radius: 8px;")
              p.mb-0.text-white.text-center #[b Planificar calendario detallado de ejecución:]
            .fondo-color-sistema-k.p-3.h-100
              ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                li
                  i.far.fa-check-circle
                  span Definir el calendario que especifique la ejecución de los casos de prueba, teniendo en cuenta el plan y los casos de prueba.
        .col-lg-4.col-md-6.mb-4
          .d-flex.w-100.flex-column.h-100
            .p-1.px-5(style="min-height:53px;display:flex;justify-content: center;align-items:center;background-color: #773238;border-top-left-radius: 8px;border-top-right-radius: 8px;")
              p.mb-0.text-white.text-center #[b Verificar entorno de pruebas:]
            .fondo-color-sistema-k.p-3.h-100
              ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                li
                  i.far.fa-check-circle
                  span Verificar que el ambiente de pruebas tenga un funcionamiento correcto.
        .col-lg-4.col-md-6.mb-4
          .d-flex.w-100.flex-column.h-100
            .p-1.px-5(style="min-height:53px;display:flex;justify-content: center;align-items:center;background-color: #4D6828;border-top-left-radius: 8px;border-top-right-radius: 8px;")
              p.mb-0.text-white.text-center #[b Integrar los datos de pruebas:]
            .fondo-color-sistema-k.p-3.h-100
              ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                li
                  i.far.fa-check-circle
                  span Realizar una recolección de los datos de prueba a utilizar en la ejecución de pruebas.
        .col-lg-4.col-md-6.mb-4
          .d-flex.w-100.flex-column.h-100
            .p-1.px-5(style="min-height:53px;display:flex;justify-content: center;align-items:center;background-color: #3B6D75;border-top-left-radius: 8px;border-top-right-radius: 8px;")
              p.mb-0.text-white.text-center #[b Evaluar criterios de entrada:]
            .fondo-color-sistema-k.p-3.h-100
              ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                li
                  i.far.fa-check-circle
                  span Analizar los criterios de entrada contenidos en el plan de pruebas, de tal forma que se pueda verificar la ejecución de las pruebas.

        .col-lg-4.col-md-6.mb-4
          .d-flex.w-100.flex-column.h-100
            .p-1.px-5(style="min-height:53px;display:flex;justify-content: center;align-items:center;background-color: #A86E2F;border-top-left-radius: 8px;border-top-right-radius: 8px;")
              p.mb-0.text-white.text-center #[b Ejecutar las pruebas:]
            .fondo-color-sistema-k.p-3.h-100
              ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                li
                  i.far.fa-check-circle
                  span Se incluyen las siguientes actividades:
                li
                  i.far.fa-check-circle
                  span Ejecutar casos y script de prueba.
                li
                  i.far.fa-check-circle
                  span Ejecutar casos y script de prueba.

      Separador

      #t_1_2.titulo-segundo.color-acento-contenido
        h2 1.2 #[em Agile Testing]

      .row.align-items-center.mb-5
        .col-lg-5
          figure.mb-4.mb-lg-0
            img.mx-auto(src="@/assets/curso/temas/42.png",style="max-width: 429px;")
        .col-lg-7
          p.mb-5 Las metodologías ágiles proporcionan un conjunto de directrices y principios diseñados para agilizar y priorizar la entrega de productos sobre la documentación exhaustiva, simplificando los procesos e involucrando al cliente final desde las etapas iniciales del proyecto. Es importante destacar que una metodología ágil se compone de iteraciones o #[em sprints], cada uno de duración relativamente corta, generalmente de dos a cuatro semanas. Al finalizar cada iteración, se disponen de funcionalidades del #[em software] que pueden ser entregadas y utilizadas por el cliente.
          p.mb-0 Recordando las metodologías ágiles, se puede especificar que las pruebas ágiles (#[em Agile Testing]) son una práctica que se lleva a cabo en cada iteración. Existen dos tipos de planificaciones: la planificación de #[b lanzamiento/entrega], que se refiere a las entregas frecuentes al cliente, es decir, la puesta en producción de nuevas versiones del producto; y la planificación de #[b sprint/iteración], que indica que un proyecto se ejecuta en bloques temporales cortos y fijos. Sin embargo, estas planificaciones pueden coincidir en un mismo momento, es decir, puede haber una sola planificación que incluya actividades tanto de lanzamiento como de #[em sprint], tal como se muestra en la siguiente figura:

      .row.justify-content-center.mb-5
        .col-lg-10
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 3.] Actividades #[em Sprints Reléase]
          .fondo-color-sistema-k.borde-18.p-3.p-md-4.pt-4.pb-4
            figure
              img.mx-auto.d-none.d-lg-block(src="@/assets/curso/temas/43.png",style="max-width: 820px;",alt="La figura muestra un diagrama que representa la estructura de los sprints en un marco de trabajo Agile. Cada sprint está dividido en dos semanas y sigue un flujo de trabajo consistente. Comienza con la fase de Requisitos, seguida por la fase de Diseño/Implementación, luego viene la fase de Agile Testing, y termina con la fase de Release/Entrega. El diagrama repite esta estructura para Sprint 1, Sprint 2, y así sucesivamente hasta Sprint n, indicando que es un proceso iterativo y escalable que se aplica a través de múltiples sprints.")
              img.mx-auto.d-lg-none(src="@/assets/curso/temas/44.png",style="max-width: 270px;",alt="La figura muestra un diagrama que representa la estructura de los sprints en un marco de trabajo Agile. Cada sprint está dividido en dos semanas y sigue un flujo de trabajo consistente. Comienza con la fase de Requisitos, seguida por la fase de Diseño/Implementación, luego viene la fase de Agile Testing, y termina con la fase de Release/Entrega. El diagrama repite esta estructura para Sprint 1, Sprint 2, y así sucesivamente hasta Sprint n, indicando que es un proceso iterativo y escalable que se aplica a través de múltiples sprints.")

      .row.align-items-center.mb-5
        .col-lg-7
          p.mb-4 Por otro lado, es importante considerar que la metodología de desarrollo de #[em software] tradicional, conocida como cascada, emplea diferentes tipos de pruebas de #[em software] que evalúan tanto los requerimientos funcionales como los no funcionales de manera secuencial. Sin embargo, en las metodologías ágiles, y específicamente en las pruebas ágiles, también se contemplan diversos tipos de pruebas. La diferencia radica en que en las metodologías ágiles se utilizan #[em sprints] o iteraciones cortas y hay una interacción continua entre los equipos de desarrollo, diseño y pruebas.

          .fondo-color-sistema-p.borde-13.p-3
            .row.align-items-center
              .col-lg-2.col-md-2
                figure.mb-4.mb-md-0
                  img.mx-auto(src="@/assets/curso/temas/45.png",style="max-width: 73px;")
              .col-lg-10.col-md-10
                p.mb-0 Las pruebas ágiles se basan en principios que se alinean con el desarrollo ágil de #[em software]. Además, existen ciertos cuadrantes que se deben tener en cuenta al momento de planificarlas.

        .col-lg-5
          figure.mb-4.mb-lg-0
            img.mx-auto(src="@/assets/curso/temas/46.png",style="max-width: 505px;")

    p.pt-5.mb-0 A continuación, se describen tanto los principios como los cuadrantes:

    .cont-titulo-decorativo.p-2.mt-5.mb-4
      .row
        .col-auto.pe-0
          figure
            img(src="@/assets/curso/temas/4.svg")
        .col.align-self-end
          h3.mt-3.mb-0.me-2 Principios de las pruebas agiles (#[em Agile Testing])

    p.mb-5 El Agile Testing se fundamenta en los siguientes principios, aplicables a un desarrollo de software exitoso:

    .fondo-gradiente-1
      TabsB.color-acento-botones.mb-5
        .p-3.fondo-color-sistema-k(titulo="<h4>Integración continua</h4>")
          .row.justify-content-center.mb-5.mt-4
            .col-lg-11
              .row.align-items-center
                .col-lg-6.mb-4.mb-lg-0
                  p.mb-4.fw-bold Integración continua
                  p.mb-0 Los equipos de diseño y desarrollo ejecutan pruebas continuamente, puesto que es una forma de asegurar el avance continuo del producto.
                .col-lg-6.order-last.order-lg-first
                  figure
                    img.mx-auto(src="@/assets/curso/temas/48.png",style="max-width: 400px;")
        .p-3.fondo-color-sistema-k(titulo="<h4>Entrega continua</h4>")
          .row.justify-content-center.mb-5.mt-4
            .col-lg-11
              .row.align-items-center
                .col-lg-6.mb-4.mb-lg-0
                  p.mb-4.fw-bold Entrega continua
                  p.mb-0 Se soporta en la integración continua, en este punto los desarrolladores realizan un control y la cantidad de veces que se realiza la entrega continua.
                .col-lg-6
                  figure
                    img.mx-auto(src="@/assets/curso/temas/49.png",style="max-width: 400px;")
        .p-3.fondo-color-sistema-k(titulo="<h4>Elaborar menos documentación</h4>")
          .row.justify-content-center.mb-5.mt-4
            .col-lg-11
              .row.align-items-center
                .col-lg-6.mb-4.mb-lg-0
                  p.mb-4.fw-bold Elaborar menos documentación
                  p.mb-0 Los participantes de los equipos en metodologías agiles pueden crear listas y tomar notas para centrarse en probar el software, lo que permite no enfocarse en detalles secundarios que tomarían mucho tiempo.
                .col-lg-6.order-last.order-lg-first
                  figure
                    img.mx-auto(src="@/assets/curso/temas/50.png",style="max-width: 400px;")
        .p-3.fondo-color-sistema-k(titulo="<h4>Responder con velocidad a la retroalimentación</h4>")
          .row.justify-content-center.mb-5.mt-4
            .col-lg-11
              .row.align-items-center
                .col-lg-6.mb-4.mb-lg-0
                  p.mb-4.fw-bold Responder con velocidad a la retroalimentación
                  p.mb-0 Los involucrados en el negocio del producto están estrechamente conectados con las interacciones del producto, además el tiempo de respuesta se reduce debido a la realimentación continua en cada parte de la interacción.
                .col-lg-6
                  figure
                    img.mx-auto(src="@/assets/curso/temas/51.png",style="max-width: 400px;")
        .p-3.fondo-color-sistema-k(titulo="<h4>Proporcionar retroalimentación constante</h4>")
          .row.justify-content-center.mb-5.mt-4
            .col-lg-11
              .row.align-items-center
                .col-lg-6.mb-4.mb-lg-0
                  p.mb-4.fw-bold Proporcionar retroalimentación constante
                  p.mb-0 En las pruebas agiles la retroalimentación es continua de modo que el diseño del producto logre los propósitos del negocio requeridos.
                .col-lg-6.order-last.order-lg-first
                  figure
                    img.mx-auto(src="@/assets/curso/temas/52.png",style="max-width: 400px;")

      .cont-titulo-decorativo.p-2.mt-5.mb-4
        .row
          .col-auto.pe-0
            figure
              img(src="@/assets/curso/temas/4.svg")
          .col.align-self-end
            h3.mt-3.mb-0.me-2 Cuadrantes de las pruebas agiles #[em (Agile Testing)]

      .row.align-items-center.mb-5
        .col-lg-8
          p.mb-4 Para planificar las pruebas ágiles, podemos basarnos en los cuadrantes de #[em Agile Testing], que proporcionan una biblioteca de tipos de pruebas aplicables para satisfacer los requerimientos. Estos cuatro cuadrantes ofrecen una clasificación útil para la planificación de las pruebas ágiles, asegurando que se consideren los métodos y recursos necesarios para lograr productos de #[em software] de alta calidad.
          p.mb-0 Las pruebas definidas por los cuadrantes se centran en brindar apoyo al equipo de desarrollo a lo largo del proceso de creación del producto, ya que guían el desarrollo de la funcionalidad. Posteriormente, facilitan la introducción de nuevo código y la refactorización, asegurando que no se produzcan resultados inesperados en el comportamiento del sistema. En la siguiente figura, se pueden observar los cuadrantes de las pruebas ágiles, los cuales se organizan en torno a dos ejes principales: #[b las pruebas que apoyan al equipo y las tecnologías que facilitan el proceso.]
        .col-lg-4
          figure.mb-4.mb-lg-0.order-first.order-lg-last
            img.mx-auto(src="@/assets/curso/temas/53.png",style="max-width: 400px;")

      .row.justify-content-center.pb-5
        .col-lg-8
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 4.] Cuadrantes pruebas ágiles
          figure
            img.mx-auto(src="@/assets/curso/temas/54.svg",style="max-width: 800px;",alt="La figura es un diagrama que clasifica las pruebas de software en cuatro cuadrantes basados en si son más técnicas o dirigidas al negocio y si son manuales o automatizadas. Incluye pruebas funcionales, exploratorias, unitarias y de componentes, así como pruebas de rendimiento, carga y seguridad. Además, menciona la crítica del producto y las herramientas utilizadas en las pruebas. Este diagrama ayuda a los equipos a seleccionar y organizar las pruebas durante el ciclo de desarrollo del software.")

    p.mt-5.mb-4 A continuación, se realizará una exploración de los diferentes cuadrantes expuestos:

    .py-4.fondo-float-2
      .cont_2_3.p-3
        figure.fig-flotante(style="left: 0;top: -140px;max-width:118px;")
          img(src="@/assets/curso/temas/55.svg",style="max-width:118px;")
        figure.fig-flotante(style="z-index: 1;right: 10px;top: 10px;max-width:88px;")
          img(src="@/assets/curso/temas/56.svg",style="max-width:88px;")
        figure.fig-flotante(style="right: -70px;top: -115px;max-width:173px;")
          img(src="@/assets/curso/temas/57.svg",style="max-width:173px;")
        figure.fig-flotante(style="left: 35%;bottom: -160px;max-width:227px;")
          img(src="@/assets/curso/temas/58.svg",style="max-width:227px;")

        SlyderA(tipo="b")
          .row.justify-content-center
            .col-lg-10
              .row.align-items-center
                .col-lg-6
                  h4.mb-4 Pruebas de cara al negocio #[em (Business Facing)]

                  p.mb-0 Son pruebas del Q2 y Q3, pruebas funcionales y pruebas UAT, se enfoca en realizar pruebas manuales y criticando al producto con las pruebas de aceptación.

                .col-lg-6.order-first.order-lg-last
                  .bg-white.borde-9.p-2.py-5.mb-4.mb-lg-0
                    figure
                      img.mx-auto(src='@/assets/curso/temas/59.svg',style="max-width: 470px;")
          .row.justify-content-center
            .col-lg-10
              .row.align-items-center
                .col-lg-6
                  h4.mb-4 Pruebas de cara a la tecnología #[em (Technology Facing)]

                  p.mb-0 Pueden ser automatizadas y utilizando herramientas, incluye el Q1 y Q4.

                .col-lg-6.order-first.order-lg-last
                  .bg-white.borde-9.p-2.py-5.mb-4.mb-lg-0
                    figure
                      img.mx-auto(src='@/assets/curso/temas/60.svg',style="max-width: 470px;")
          .row.justify-content-center
            .col-lg-10
              .row.align-items-center
                .col-lg-6
                  h4.mb-4 Pruebas soportando la programación o soporte del equipo #[em (Supporting the Team)]

                  p.mb-0 Comprenden pruebas automatizadas y manuales del cuadrante Q2 y Q1 donde se realizan pruebas unitarias y de componentes y pruebas funcionales con prototipos y simuladores.

                .col-lg-6.order-first.order-lg-last
                  .bg-white.borde-9.p-2.py-5.mb-4.mb-lg-0
                    figure
                      img.mx-auto(src='@/assets/curso/temas/61.svg',style="max-width: 300px;")
          .row.justify-content-center
            .col-lg-10
              .row.align-items-center
                .col-lg-6
                  h4.mb-4 Pruebas de críticas al producto #[em (Critique the Product)]

                  p.mb-0 Estas pruebas pueden tener un carácter positivo, puesto que a partir de ellas se pueden sugerir o realizar mejoras. Cuando se ejecutan estas pruebas, la idea es simular lo más que se pueda un ambiente real en el cual serán ejecutadas, así mismo estas pruebas frecuentemente son realizadas por los usuarios finales como pruebas de aceptación (UAT).

                .col-lg-6.order-first.order-lg-last
                  .bg-white.borde-9.p-2.py-5.mb-4.mb-lg-0
                    figure
                      img.mx-auto(src='@/assets/curso/temas/62.svg',style="max-width: 300px;")
          .row.justify-content-center
            .col-lg-10
              .row.align-items-center
                .col-lg-6
                  h4.mb-4 El primer cuadrante (Q1)

                  ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                    li 
                      span El primer cuadrante (Q1) contiene los siguientes tipos de pruebas:
                    li 
                      i.fas.fa-cog
                      span Pruebas unitarias.
                    li
                      i.fas.fa-cog
                      span Pruebas de componente.

                .col-lg-6.order-first.order-lg-last
                  .bg-white.borde-9.p-2.py-5.mb-4.mb-lg-0
                    figure
                      img.mx-auto(src='@/assets/curso/temas/63.svg',style="max-width: 295px;")
          .row.justify-content-center
            .col-lg-10
              .row.align-items-center
                .col-lg-6
                  h4.mb-4 El segundo cuadrante (Q2)

                  ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                    li 
                      span El segundo cuadrante (Q2) definen las funcionalidades que el cliente solicita:
                    li 
                      i.fas.fa-cog
                      span Pruebas funcionales.
                    li
                      i.fas.fa-cog
                      span Pruebas de historias.
                    li
                      i.fas.fa-cog
                      span Pruebas de Prototipos y simulaciones.

                .col-lg-6.order-first.order-lg-last
                  .bg-white.borde-9.p-2.py-5.mb-4.mb-lg-0
                    figure
                      img.mx-auto(src='@/assets/curso/temas/64.svg',style="max-width: 280px;")
          .row.justify-content-center
            .col-lg-10
              .row.align-items-center
                .col-lg-6
                  h4.mb-4 El tercer cuadrante (Q3)

                  ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                    li 
                      span El tercer cuadrante (Q3) contiene los siguientes tipos de pruebas:
                    li 
                      i.fas.fa-cog
                      span Pruebas exploratorias.
                    li
                      i.fas.fa-cog
                      span Pruebas de usabilidad.
                    li
                      i.fas.fa-cog
                      span Pruebas de escenarios.
                    li
                      i.fas.fa-cog
                      span Pruebas de aceptación de usuario.

                .col-lg-6.order-first.order-lg-last
                  .bg-white.borde-9.p-2.py-5.mb-4.mb-lg-0
                    figure
                      img.mx-auto(src='@/assets/curso/temas/65.svg',style="max-width: 345px;")
          .row.justify-content-center
            .col-lg-10
              .row.align-items-center
                .col-lg-6
                  h4.mb-4 El cuarto cuadrante (Q4)

                  ul.lista-ul.lista-tipo-1.fa-ul.mb-0.ms-0
                    li 
                      span El cuarto cuadrante (Q4) contiene pruebas técnicas. Relacionadas con los requerimientos no funcionales, por lo que validan el cumplimiento de estos, analizando la seguridad, el desempeño y la robustez.

                    li 
                      i.fas.fa-cog
                      span Pruebas de rendimiento y de estrés.
                    li
                      i.fas.fa-cog
                      span Pruebas de seguridad.
                    li
                      i.fas.fa-cog
                      span Pruebas de robustez. 

                .col-lg-6.order-first.order-lg-last
                  .bg-white.borde-9.p-2.py-5.mb-4.mb-lg-0
                    figure
                      img.mx-auto(src='@/assets/curso/temas/66.svg',style="max-width: 322px;")
          
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
