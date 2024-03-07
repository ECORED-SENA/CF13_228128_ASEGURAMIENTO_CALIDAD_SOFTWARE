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
              img.mx-auto(src="@/assets/curso/temas/6.svg",style="max-width: 650px;",alt="El diagrama presenta un esquema de las Pruebas funcionales en el desarrollo de software, destacando su naturaleza cíclica e interconectada. Se detallan cinco tipos de pruebas: Prueba de interfaz de compatibilidad, Pruebas de aceptación (UAT), Pruebas de regresión, Prueba de interfaz de usuario (GUI), y Prueba de instalación. Cada una es crucial para asegurar diferentes aspectos de la funcionalidad del software, desde la compatibilidad hasta la satisfacción del usuario y la estabilidad después de actualizaciones o cambios")

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

    TabsB.color-acento-botones.mb-5
      .p-3.fondo-color-sistema-k(titulo="<h4>XUnit.</h4>")
        .row.justify-content-end
          .col-lg-11
            .row
              .col-lg-6.mb-4.mb-lg-0
                h4.mb-4 XUnit.
                p.mb-0 Es una herramienta de pruebas unitarias para el #[em framework] .NET.
              .col-lg-6
                .fondo-color-sistema-g.borde-13.p-3.p-md-5
                  figure
                    img.mx-auto(src="@/assets/curso/temas/11.png",style="max-width: 400px;")
      .p-3.fondo-color-sistema-k(titulo="<h4>Junit.</h4>")
        .row.justify-content-end
          .col-lg-11
            .row
              .col-lg-6.mb-4.mb-lg-0
                h4.mb-4 Junit.
                p.mb-0 Es una herramienta de pruebas de aplicaciones Java.
              .col-lg-6
                .fondo-color-sistema-g.borde-13.p-3.p-md-5
                  figure
                    img.mx-auto(src="@/assets/curso/temas/12.png",style="max-width: 400px;")
      .p-3.fondo-color-sistema-k(titulo="<h4>Nunit.</h4>")
        .row.justify-content-end
          .col-lg-11
            .row
              .col-lg-6.mb-4.mb-lg-0
                h4.mb-4 Nunit.
                p.mb-0 Es una herramienta de pruebas de plataformas .NET.
              .col-lg-6
                .fondo-color-sistema-g.borde-13.p-3.p-md-5
                  figure
                    img.mx-auto(src="@/assets/curso/temas/13.png",style="max-width: 400px;")
      .p-3.fondo-color-sistema-k(titulo="<h4>PhpUnit.</h4>")
        .row.justify-content-end
          .col-lg-11
            .row
              .col-lg-6.mb-4.mb-lg-0
                h4.mb-4 PhpUnit.
                p.mb-0 Es una herramienta de pruebas de programación PHP.
              .col-lg-6
                .fondo-color-sistema-g.borde-13.p-3.p-md-5
                  figure
                    img.mx-auto(src="@/assets/curso/temas/14.png",style="max-width: 400px;")
    
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

    .row.justify-content-center
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
