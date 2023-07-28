<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1  Fundamentos de los servicios de TI en la nube

    
    .row.bg-tema-1.mb-5.mb-md-0
      .col-lg-12.px-lg-2.px-4.py-4.pb-md-5(data-aos="fade-right")
        .row.align-items-center.justify-content-evenly
          .col-lg-4.col-md-4-col-10.mb-md-0.mb-4.mb-lg-0(data-aos="fade-right")
            img.img-a.img-t(src='@/assets/curso/images/tema1/img_1.svg' alt='Imagen decorativa')
          .col-lg-7.col-md-10.text-white.p-3(data-aos="fade-left")
            p La nube o <i>cloud computing</i>, es una de las soluciones tecnológicas de servicio más  completa, pues, ofrece una alternativa informática basada en internet por medio de un intercambio de servicios. Este servicio en la nube se ha extendido a todos  los sectores, tanto en empresas como en usuarios individuales.

 
    Separador 

    #t_1_1.titulo-segundo
      .h2 1.1	Conceptos, términos y definiciones

    .col-lg-11.mx-auto.d-none.d-lg-block
      .tarjeta.fcs
        .row
          .col-lg-2(data-aos="fade-right")
            img.my-4(src='@/assets/curso/images/tema1/ico_1.svg' alt='' , style="width:115px; display:block; margin:0 auto;").mx-0.mx-md-3
          .col-lg-9(data-aos="fade-left")
            img(src='@/assets/curso/images/tema1/comillasCAC.svg' alt='Cita' style='width:65px;margin: 0 -1rem').mb-2
            h5.aling-14 <b><i>“La computación en la nube es el modelo que permite el acceso a una red bajo demanda de un conjunto de servicios informáticos configurables tales como infraestructura, aplicaciones y almacenamiento.”</i></b>
            .floatRight
              h6.aling-15   Del Vecchio, J. F., Paternina, F. J., & Henriquez Miranda, C. (2015) 
                i.fas.fa-square.cac
      
    .jumbotrom.d-block.d-lg-none
      .row.p-4.py-5.py-md-4
        .col-lg-2 
          img.img-a.img-t(src='@/assets/curso/images/tema1/ico_1.svg' alt='' , style="width:115px; display:block; margin:0 auto;").mx-md-3
        .col-lg-9
          h5.mt-3 <b><i>“La computación en la nube es el modelo que permite el acceso a una red bajo demanda de un conjunto de servicios informáticos configurables tales como infraestructura, aplicaciones y almacenamiento.”</i></b>
          .floatRight
            h6 Del Vecchio, J. F., Paternina, F. J., & Henriquez Miranda, C. (2015) 
              i.fas.fa-square.cac

  .container.bg-white.p-4.p-md-5.fondo-2.mg-top-1.cs

    p.mb-3.p-4 Este tipo de tecnología durante los últimos años ha permitido que las empresas logren tener presencia corporativa en la web y, la adquisición de recursos tecnológicos informáticos en una inversión económica muy cómoda o razonable a manera de pago por servicios, sin la necesidad de adquirir físicamente equipos o infraestructura como antes era requerido por parte de las organizaciones, administración y mantenimiento, como se detalla a continuación:
    
    .row.justify-content-center.mb-md-3.mb-5
      .col-lg-10(data-aos="fade")
        ImagenInfografica.color-secundario
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/images/tema1/infogra.svg')

          .tarjeta.color-primario.p-3.tarjeta--azul_1-1(x="4%" y="50%" numero="")
            .row.space-between.align-items-center.mb-0
              .col-md-10.col-9
                h3 Servicios de infraestructura
              .col-md-2.col-3
                h2.numeroTarjeta.mb-0 01
            p.text-alinear.mb-0.text-small Los servicios de infraestructura en la Nube, conocido como LaaS por sus siglas en inglés; se presentan como aplicaciones de autoservicio creadas para el acceso, control y gestión de infraestructuras remotas.
          .tarjeta.color-primario.p-3.tarjeta-violeta1(x="28%" y="50%" numero="")
            .row.space-between.align-items-center.mb-0
              .col-md-10.col-9
                h3  Plataformas en la nube
              .col-md-2.col-3
                h2.numeroTarjeta.mb-0 02
            p.text-alinear.mb-0.text-small Las Plataformas en la Nube son tan flexibles y versátiles que se usan para desarrollar aplicaciones y sistemas complejos para impulsar los entornos virtuales. De hecho; los sistemas PaaS proporcionan marcos virtuales donde los especialistas desarrollan y personalizan sus sistemas los propietarios y las aplicaciones.
          .tarjeta.color-primario.p-3.tarjeta--azul_1-2(x="51.7%" y="50%" numero="")
            .row.space-between.align-items-center.mb-0
              .col-md-10.col-9
                h3 <i>Software</i> como servicio
              .col-md-2.col-3
                h2.numeroTarjeta.mb-0 03
            p.text-alinear.mb-0.text-small Los Servicios de Aplicaciones en la Nube, o mejor conocidos como <i>Software</i> como Servicio(SaaS) se enfocan en el uso de la web para entregar aplicaciones para todo y todos. Esta es la razón por la cual los SaaS representan el mayor mercado de servicios y sistemas en la Nube.
          .tarjeta.color-primario.p-3.tarjeta-violeta2(x="76%" y="50%" numero="")
            .row.space-between.align-items-center.mb-0
              .col-md-10.col-9
                h3 ¿Para quienes?
              .col-md-2.col-3
                h2.numeroTarjeta.mb-0 04
            p.text-alinear.mb-0.text-small Los LaaS están pensados para ingenieros de sistemas, PaaS para desarrolladores web y SaaS para los consumidores directos.
  
    #menu1.row.justify-content-center
      .col-lg-12(data-aos="fade")
        .contenedor-total1-1
          figure
            img(src='@/assets/curso/images/tema1/img_2.png')
          
          .row.justify-content-center.px-2.py-2.p-md-4
            .col-auto.d-none.d-lg-block
              .contenedor-text-1.mb-0
                p.aling-8.mb-md-4.mb-0 Si bien en la mayoría de las ocasiones no es fácil identificar todas las opciones posibles, cuantas más alternativas se generen es más probable obtener una que resulte significativamente satisfactoria.
            .col-auto.d-block.d-lg-none
              .contenedor-text-1.mb-0
                p.mb-0 Si bien en la mayoría de las ocasiones no es fácil identificar todas las opciones posibles, cuantas más alternativas se generen es más probable obtener una que resulte significativamente satisfactoria.                
      .row.d-none.d-lg-block.mt-3
        .flex-container
          .caja 
            img.my-3(src='@/assets/curso/images/tema1/ico_1_menu.svg' alt='' , style="width:50px; display:block; margin:auto 0;").m-auto
            a(href="#1", title="Redes de datos") <b>Redes de datos</b> 
          a.caja.indicador__container(href="#2", title="Modelos de referencia" @mouseover="mostrarIndicador = false") 
            img.my-3(src='@/assets/curso/images/tema1/ico_2_menu.svg' alt='' , style="width:50px; display:block; margin:auto 0;").m-auto
            <b>Modelos de referencia</b>
            .indicador--click(v-if="mostrarIndicador")
          .caja 
            img.my-3(src='@/assets/curso/images/tema1/ico_3_menu.svg' alt='' , style="width:50px; display:block; margin:auto 0;").m-auto
            a(href="#3", title="Modelo de referencia TCP /IP") <b>Modelo de referencia TCP /IP</b>  
          .caja 
            img.my-3(src='@/assets/curso/images/tema1/ico_4_menu.svg' alt='' , style="width:50px; display:block; margin:auto 0;").m-auto
            a(href="#4", title="Protocolos de comunicación") <b>Protocolos de comunicación</b> 
          .caja 
            img.my-3(src='@/assets/curso/images/tema1/ico_5_menu.svg' alt='' , style="width:50px; display:block; margin:auto 0;").m-auto
            a(href="#5", title="Puertos de comunicación") <b>Puertos de comunicación</b>
          .caja 
            img.my-3(src='@/assets/curso/images/tema1/ico_6_menu.svg' alt='' , style="width:50px; display:block; margin:auto 0;").m-auto
            a(href="#6", title="Medios de transmisión") <b>Medios de transmisión</b>
          .caja 
            img.my-3(src='@/assets/curso/images/tema1/ico_7_menu.svg' alt='' , style="width:50px; display:block; margin:auto 0;").m-auto
            a(href="#7", title="Recursos compartidos") <b>Recursos compartidos</b>

        
      .row.justify-content-center.mb-5.d-lg-none.neg--top
        .col-6.col-md-6.col-lg-4.p-2
          .tarjeta.tarjeta_white-1.p-4.text-center.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3(src='@/assets/curso/images/tema1/ico_1_menu.svg' alt='')
            a(href="#1", title="Redes de datos") <b>Redes de datos</b>
            .indicador--click(v-if="mostrarIndicador")  
        .col-6.col-md-6.col-lg-4.p-2
          .tarjeta.tarjeta_white-1.p-4.text-center.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3(src='@/assets/curso/images/tema1/ico_2_menu.svg' alt='')
            a(href="#2", title="Modelos de referencia") <b>Modelos de referencia</b>
            .indicador--click(v-if="mostrarIndicador")
        .col-6.col-md-6.col-lg-4.p-2
          .tarjeta.tarjeta_white-1.p-4.text-center.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3(src='@/assets/curso/images/tema1/ico_3_menu.svg' alt='')
            a(href="#3", title="Modelo de referencia TCP /IP") <b>Modelo de referencia TCP /IP</b>
            .indicador--click(v-if="mostrarIndicador") 
        .col-6.col-md-6.col-lg-4.p-2
          .tarjeta.tarjeta_white-1.p-3.text-center.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3(src='@/assets/curso/images/tema1/ico_4_menu.svg' alt='')
            a(href="#4", title="Protocolos de comunicación") <b>Protocolos de comunicación</b>
            .indicador--click(v-if="mostrarIndicador") 
        .col-6.col-md-6.col-lg-4.p-2
          .tarjeta.tarjeta_white-1.p-3.text-center.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3(src='@/assets/curso/images/tema1/ico_5_menu.svg' alt='')
            a(href="#5", title="Puertos de comunicación") <b>Puertos de comunicación</b>
            .indicador--click(v-if="mostrarIndicador") 
        .col-6.col-md-6.col-lg-4.p-2
          .tarjeta.tarjeta_white-1.p-4.text-center.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3(src='@/assets/curso/images/tema1/ico_6_menu.svg' alt='')
            a(href="#6", title="Medios de transmisión") <b>Medios de transmisión</b>
            .indicador--click(v-if="mostrarIndicador") 
        .col-6.col-md-6.col-lg-4.p-2
          .tarjeta.tarjeta_white-1.p-3.text-center.h-100
            .row.justify-content-center.mb-3
              .col-8
                img.img-a.img-t.mb-3(src='@/assets/curso/images/tema1/ico_7_menu.svg' alt='')
            a(href="#7", title="Recursos compartidos") <b>Recursos compartidos</b>
            .indicador--click(v-if="mostrarIndicador") 
        
      #1.pRelative
        .backtoTop-6
          a(href="#menu1", title="Redes de datos") 
            img(src='@/assets/curso/images/tema1/flechitaCAC.svg' alt='Volver arriba' style="width:60px; display:block; margin:0 auto;")
    
  .container.bg-white.p-4.p-md-5.container-bottom.mg-top-2
    .row.mb-4.ps-2
      .col-8.col-lg-2.bg-color
        .h3.mb-0.text-white Redes de datos

    .row.justify-content-center.align-items-center.d-block.d-lg-none
      .col-12.col-lg-5.col-xl-5
        img.my-3.img-a(src="@/assets/curso/images/tema1/img_3.svg" alt='Volver arriba' )
      .col-12.col-lg-7.col-xl-7
        p Las redes de datos tienen por función potenciar e incrementar la productividad de las organizaciones al permitir que todos los dispositivos que se encuentran conectados puedan acceder a los recursos que se encuentran compartidos, en los últimos años la tecnología ha entrado a jugar un papel preponderante en el desarrollo y evolución de las organizaciones cada vez está más inmersa en todos los procesos y actividades empresariales, personales y cotidianas.
        .cajon.color-custom.p-3
            p.mb-0 Las redes han permitido que los servicios y el acceso a estos recursos sea cada vez más necesario ya que se requiere tener en todo momento trabajo en equipo, colaborativo y la integración entre los diferentes recursos tecnológicos, esto es lo que conocemos como el <i>Networking</i>. Para que dichas redes pueden interconectarse y trabajar en red se requiere de una serie de componentes desde el punto de vista físico y lógico dentro de los cuales destacamos los siguientes:

    .row.justify-content-center.align-items-center.fondo-25.mb-0
      .col-12.col-lg-5.col-xl-5(data-aos="fade-right")
        img.m-img(src="@/assets/curso/images/tema1/img_3.svg" alt='Volver arriba' style="width:450px; display:block; margin:3rem -1rem;").ma-2
      .col-12.col-md-4.col-lg-6.col-xl-6(data-aos="fade-left")
        p Las redes de datos tienen por función potenciar e incrementar la productividad de las organizaciones al permitir que todos los dispositivos que se encuentran conectados puedan acceder a los recursos que se encuentran compartidos, en los últimos años la tecnología ha entrado a jugar un papel preponderante en el desarrollo y evolución de las organizaciones cada vez está más inmersa en todos los procesos y actividades empresariales, personales y cotidianas.
        .cajon.color-custom.p-3
            p.mb-0 Las redes han permitido que los servicios y el acceso a estos recursos sea cada vez más necesario ya que se requiere tener en todo momento trabajo en equipo, colaborativo y la integración entre los diferentes recursos tecnológicos, esto es lo que conocemos como el <i>Networking</i>. Para que dichas redes pueden interconectarse y trabajar en red se requiere de una serie de componentes desde el punto de vista físico y lógico dentro de los cuales destacamos los siguientes:
    br
    .row.justify-content-center.mt-5.mx-0.align-items-center.mb-5(data-aos="fade")
      .col-6.col-md-6.col-lg-2.p-md-4.d-flex.mb-3
        .tarjeta.tarjeta_white.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/images/tema1/ico_13.svg' alt='')
          h6.text-center.mb-0 Modelos de referencia
      .col-6.col-md-6.col-lg-2.p-md-4.d-flex.mb-3
        .tarjeta.tarjeta_white.p-2
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/images/tema1/ico_14.svg' alt='' style="width:80px; display:block; margin:0 auto;")
          h6.text-center.mb-3 Protocolos de comunicación
      .col-6.col-md-6.col-lg-2.p-md-4.d-flex.mb-3
        .tarjeta.tarjeta_white.p-3
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/images/tema1/ico_15.svg' alt='')
          h6.text-center.mb-0 Puertos de comunicación
      .col-6.col-md-6.col-lg-2.p-md-4.d-flex.mb-3
        .tarjeta.tarjeta_white.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/images/tema1/ico_16.svg' alt='')
          h6.text-center.mb-0 Medios de transmisión
      .col-6.col-md-6.col-lg-2.p-md-4.d-flex.mb-3
        .tarjeta.tarjeta_white.p-4
          .row.justify-content-center.mb-3
            .col-8
              img(src='@/assets/curso/images/tema1/ico_17.svg' alt='')
          h6.text-center.mb-0 Recursos compartidos 
      
    hr
    br
    #2.pRelative
      .backtoTop-3
        a(href="#menu1", title="Modelos de referencia") 
          img(src='@/assets/curso/images/tema1/flechitaCAC.svg' alt='Volver arriba' style="width:60px; display:block; margin:0 auto;")
        
    
      .row.mb-5.ps-2
          .col-8.col-lg-3.bg-color
            h3.mb-0.text-white Modelos de referencia 

    .row.mb-3
      .col-12.col-lg-10.col-xl-10
        p.mb-3 Al inicio del desarrollo de la tecnología y más propiamente de la computación, los diferentes fabricantes construían sus equipos y dispositivos para que fueran compatibles con dispositivos de sus propias marcas lo que no facilitaba la interconexión de equipos y dispositivos de fabricantes distintos.
        
    .row.justify-content-center.align-items-center
      .col-12.col-lg-7.col-xl-7(data-aos="fade-right")
        p.aling-11.mb-3 Esto llevó a la necesidad de estandarizar de manera que se permita la interconexión de una amplia gama de dispositivos sin importar fabricante o tipo de <i>software</i>, para que el intercambio de información sea posible se requiere el establecimiento de una serie de estándares.
        p.mb-3 Estos estándares son construidos por una serie de organizaciones que son las siguientes:
        LineaTiempoD.color-acento-contenido.mb-5
            p(numero="1" titulo="ISO (Organización Internacional de Normas)") ISO definió un modelo de referencia como estándar para posibilitar las comunicaciones electrónicas a nivel global, conocido como el modelo OSI (Interconexión de Sistemas Abiertos).

            p(numero="2" titulo="IEEE (Instituto de Ingenieros Electrónicos y Eléctricos)") Este organismo es encargado de fijar los estándares para los elementos físicos de una red, cables, conectores e interfaces.
            
            p(numero="3" titulo="ANSI (Instituto Nacional Americano de Normalización)") Es una organización sin fines de lucro que supervisa el desarrollo de estándares para productos, servicios, procesos y sistemas en los Estados Unidos.

            p(numero="4" titulo="EIA (Asociación de Industrias Electrónicas)") Es una organización formada por la asociación de las compañías electrónicas y de alta tecnología de los Estados Unidos, cuya misión es promover el desarrollo de mercado y la competitividad de la industria de alta tecnología de los Estados Unidos con esfuerzos locales e internacionales de la política. 

            p(numero="5" titulo="TIA (Asociación de la Industria de las Telecomunicaciones)") Es una asociación comercial acreditada por el Instituto Nacional Estadounidense de Estándares (ANSI), con el fin de desarrollar normas industriales, tanto voluntarias como basadas en el consenso, sobre una amplia variedad de productos de las tecnologías de la información y la comunicación (TIC), y actualmente representa a casi 400 empresas. El Departamento de Estándares y Tecnología de TIA opera doce comités de ingeniería, que desarrollan pautas para equipos de radio privados, antenas celulares, terminales de datos, satélites, equipos de terminales telefónicos, accesibilidad, dispositivos VoIP, cableado estructurado, centros de procesamiento de datos, comunicaciones de dispositivos móviles, multidifusión multimedia, telemática vehicular, TIC utilizadas en el cuidado de la salud, comunicaciones M2M y redes de servicios inteligentes.
            
            p(numero="6" titulo="UIT (Unión Internacional de Telecomunicaciones)") La Unión Internacional de Telecomunicaciones es el organismo especializado en telecomunicaciones de la Organización de las Naciones Unidas, encargado de regular las telecomunicaciones a nivel internacional entre las distintas administraciones y empresas operadoras. Su sede se encuentra en la ciudad de Ginebra.
        
      .col-12.col-md-4.col-lg-5.col-xl-5.mb-5.d-none.d-lg-block
        img.img-a(src="@/assets/curso/images/tema1/img_pc.png")
    
      .col-lg-12.mx-auto.mb-4(data-aos="fade")
        .tema1-1 
          .bloque-texto-a.color-custom-4.md-5.p-3
            .row.m-0.align-items-center
              .col-lg-4.mb-4.mb-lg-0
                figure
                  img(src='@/assets/curso/images/tema1/img_5.png' alt='Volver arriba' style="width:350px; display:block; margin:0 auto;")
              .col-lg-8
                .bloque-texto-a__texto
                  p.mb-0.p-3 #[b Los modelos de referencia se basan en la definición de una serie de capas las cuales tienen cada una sus propias funciones y características que se encargan de resolver un problema diferente en la comunicación, tienen como propósito asistir en la comprensión más clara y sencilla de las funciones y los procesos involucrados en la interconexión de los diferentes dispositivos de red, para ello se establecen una serie de capas con un orden específico y cada una se sustenta en la capa anterior, y más que entrar en los detalles de las especificaciones técnicas requeridas en cada una de ellas, el modelo de referencia ayuda en la comprensión de lo que sucede, ayudándonos a lograr un mejor entendimiento de las funciones y procesos involucrados.]

      
    .container.bg-white.p-4.p-md-5.fondo-19.mg-top-1
      h4.mb-3 El modelo de referencia para las redes de comunicaciones es #[mark.highlight el modelo OSI -Interconexión de Sistemas Abiertos], el cual se explica a continuación, veamos:
        .row.justify-content-center.align-items-center.mb-3
          .col-12.col-lg-6.col-xl-6(data-aos="fade-right")
            ImagenInfografica.color-secundario.mb-5
              template(v-slot:imagen)
                figure
                  img.m-3(src='@/assets/curso/images/tema1/img_6.svg')
              
              .tarjeta.tarjeta-blanca.infog1-perso(x="52%" y="12%" numero="")
                h5.bg-color-2.text-white Física - Señalización y transmisión binaria
                .p-3
                  h5.mb-5 Transmisión binaria: cables, conectores, voltajes, velocidades de datos
                    .pRelative_1
                      .backtoTop_1
                        figure
                          img(src='@/assets/curso/images/tema1/line.svg' alt='' , style="width:7px; display:block; margin:1rem 6.4rem;")
                  p.mt-5 Los protocolos de capa física describen los medios mecánicos, eléctricos,  funcionales y de procedimiento para activar, mantener y desactivar conexiones físicas para la transmisión de <i>bits</i> hacia un dispositivo de red y desde el.

              .tarjeta.tarjeta-blanca(x="52%" y="25%" numero="")
                h5.bg-color-2.text-white Enlace de datos - Direccionamiento físico
                .p-3
                  h5.mb-5 Acceso a los medios
                    .pRelative_1
                      .backtoTop_1
                        figure
                          img(src='@/assets/curso/images/tema1/line.svg' alt='' , style="width:7px; display:block; margin:2.5rem 6.4rem; height: 140px;")
                  p.mt-5 Los productos de capa de enlace de datos describen los métodos para intercambiar tramas de datos entre dispositivos en un medio común.
                
              .tarjeta.tarjeta-blanca(x="52%" y="37%" numero="")
                h5.bg-color-2.text-white Red - Determinación de ruta y direccionamiento lógico
                .p-3  
                  h5.mb-5 Direccionamiento y mejor ruta
                    .pRelative_1
                      .backtoTop_1
                        figure
                          img(src='@/assets/curso/images/tema1/line.svg' alt='' , style="width:7px; display:block; margin:2.5rem 6.4rem; height: 140px;")
                  p.mt-5 La capa de red, proporciona servicios para intercambiar los datos individuales en la red entre dispositivos finales identificados.
                
              .tarjeta.tarjeta-blanca(x="52%" y="48%" numero="")
                h5.bg-color-2.text-white Transporte - Conexión de extremo a extremo y confiabiidad
                .p-3  
                  h5.mb-5  Conexiones de extremo a extremo
                    .pRelative_1
                      .backtoTop_1
                        figure
                          img(src='@/assets/curso/images/tema1/line.svg' alt='' , style="width:7px; display:block; margin:2.5rem 6.4rem; height: 140px;")
                  p.mt-5  La capa de transporte, define los servicios para segmentar, transferir y rearmar los datos para las comunicaciones individuales entre dispositivos finales.

              .tarjeta.tarjeta-blanca(x="52%" y="60%" numero="")
                h5.bg-color-2.text-white Sesión - Comunicación entre dispositivos de red
                .p-3  
                  h5.mb-5 Comunicación entre <i>hosts</i>
                    .pRelative_1
                      .backtoTop_1
                        figure
                          img(src='@/assets/curso/images/tema1/line.svg' alt='' , style="width:7px; display:block; margin:2.5rem 6.4rem; height: 140px;")
                  p.mt-5 La capa de sesión, proporciona servicios a la capa de presentación para organizar su diálogo y administrar el intercambio de datos.
                
              .tarjeta.tarjeta-blanca(x="52%" y="75%" numero="")
                h5.bg-color-2.text-white Presentación - Representación de datos y encriptación
                .p-3  
                  h5.mb-5 Representación de datos
                    .pRelative_1
                      .backtoTop_1
                        figure
                          img(src='@/assets/curso/images/tema1/line.svg' alt='' , style="width:7px; display:block; margin:2.5rem 6.4rem; height: 140px;")
                  p.mt-5 La capa de red, proporciona una representación común de los datos transferidos entre los servicios de la capa de aplicación.

              .tarjeta.tarjeta-blanca(x="52%" y="91%" numero="")
                h5.bg-color-2.text-white Aplicación - Servicios de red a aplicaciones
                .p-3  
                  h5.mb-5 Procesos de red a aplicaciones
                    .pRelative_1
                      .backtoTop_1
                        figure
                          img(src='@/assets/curso/images/tema1/line.svg' alt='' , style="width:7px; display:block; margin:2.5rem 6.4rem; height: 140px;")
                  p.mt-5 La capa de red, proporciona los medios para la conectividad de extremo a extremo entre individuos de la red humana mediante redes de datos.
            
          .col-12.col-md-4.col-lg-3.col-xl-3(data-aos="fade-left")
            img.img-a.img-t(src="@/assets/curso/images/tema1/img_7.svg" alt="")
 
    .container.bg-white.p-4.p-md-5.container-bottom.cs
      
      p.mb-5 Para que los paquetes de datos puedan viajar desde el origen hasta su destino, cada capa del modelo OSI en el origen debe comunicarse con su capa igual en el lugar de destino. Esta forma de comunicación se conoce como comunicaciones de par-a-par en cada uno de estas capas la información cambia de nombre es decir usa un PDU (<i>Protocol Data Unit</i>).

      .row.justify-content-center
        .col-lg-8(data-aos="fade")
          .titulo-sexto.color-acento-contenido
            h5 Tabla 1 
            span Unidades de datos de protocolo por capa

          .tabla-a.color-acento-botones.mb-5 
            table(style="min-width:200px;")
              thead
                tr
                  th.text-center.text_2 <b>Capa Número</b>
                  th.text-center.text_2 <b>Nombre de Capa</b>
                  th.text-center.text_2 <b>PDU</b>
              tbody
                tr
                  td.text-center 7
                  td.text-center Aplicación
                  td.text-center <i>Bits</i>
                tr
                  td.text-center.tp 6
                  td.text-center.tp Presentación
                  td.text-center.tp Tramas
                tr
                  td.text-center  5
                  td.text-center Sesión
                  td.text-center Paquetes
                tr
                  td.text-center.tp 4
                  td.text-center.tp Transporte
                  td.text-center.tp Segmentos
                tr
                  td.text-center 3
                  td.text-center Red
                  td.text-center Datos
                tr
                  td.text-center.tp 2
                  td.text-center.tp Enlace de Datos
                  td.text-center.tp Datos
                tr
                  td.text-center 1
                  td.text-center Física
                  td.text-center Datos

      #3.row.justify-content-center.align-items-center
        .col-lg-12(data-aos="fade")
          .cajon.color-custom.p-4
            p.mb-0 El modelo #[b OSI] es el modelo de referencia de <i>internetwork</i> más conocido. Es utilizado para el diseño de redes de datos, especificaciones de funcionamiento y la resolución de problemas ya que permite ir descartando en cada capa el posible problema. 
                
      hr

      .pRelative
        .backtoTop-4
          a(href="#menu1", title="title") 
            img(src='@/assets/curso/images/tema1/flechitaCAC.svg' alt='Volver arriba' style="width:60px; display:block; margin:0 auto;")
        
        .row.mb-5.ps-2
          .col-8.col-lg-4.bg-color
            h3.mb-0.text-white Modelo de referencia TCP /IP
        .row.justify-content-center.align-items-center
          .col-12.col-lg-5.col-xl-5
            img.img-t.my-3(src="@/assets/curso/images/tema1/img_8.svg")
          .col-12.col-lg-7.col-xl-7.my-3
            p.mb-5 Fue el primer modelo de protocolo en capas para comunicaciones de red. Fue desarrollado a principios de la década de los 70 por el departamento de defensa de los EEUU, y se conoce con el nombre de modelo de Internet, su objetivo fue el de crear una red de comunicaciones que funcionara incluso en condiciones de guerra.
              .cajon.color-custom.aling-13.p-3
                p.mb-3 Aunque el modelo OSI es universalmente reconocido, el estándar histórica y técnicamente reconocido para Internet es el modelo TCP/IP (Protocolo de Control de Transferencia / Protocolo de Internet).

                p Define cuatro categorías de funciones que deben existir para que las comunicaciones sean exitosas. La arquitectura de la suite de protocolos TCP/IP sigue la estructura de este modelo. Por esto, es común que al modelo de Internet se le conozca como modelo TCP/IP.
      .col-lg-10.align-self-end
        .col-lg-10.mb-5.mb-lg-0
            p.mb-5 El modelo consta de cuatro capas como se observa en la figura a continuación:
      
      .row.justify-content-center
        .col-lg-6
          .titulo-sexto.color-acento-contenido
            h5 Figura 1 
            span  Modelo de referencia TCP/IP
      .row.justify-content-center
        .col-lg-6.mb-4(data-aos="fade")
            img.mb-3(src="@/assets/curso/images/tema1/fig_1.svg" alt="", style="width:600px; display:block; margin:auto 0;")
            figcaption 
              p.mb-0 #[b Nota.] Adaptado de https://bit.ly/32BgN6J

      hr 

      #4.pRelative
        .backtoTop
          a(href="#menu1", title="Protocolos de comunicación") 
            img(src='@/assets/curso/images/tema1/flechitaCAC.svg' alt='Volver arriba' style="width:60px; display:block; margin:0 auto;")
    
  .container.bg-white.px-md-5.px-3.py-2.fondo-2.mg-top.mb-0
    .row.mb-5.ps-3.mb-0
      .col-8.col-lg-4.bg-color-3
        .h3.mb-0.text-white Protocolos de comunicación

      p.mt-5 Las comunicaciones en general requieren de una serie de elementos y actores que intervienen dentro de los cuales podemos encontrar:

      .row.justify-content-center.align-items-center
        .col-8.col-lg-6.my-3(data-aos="fade-right")
          img.img-a.img-t.m-1(src="@/assets/curso/images/tema1/img_9.svg").mb-4
        .col-12.col-lg-6.my-3(data-aos="fade-left")
          SlyderF
            .tarjeta.tarjeta--blanca-5.boxShadow.p-5.h-100
              .row.justify-content-center
                .col-md-10.mb-4.mb-md-2.p-0
                  img.mt-3(src='@/assets/curso/images/tema1/ico_18.svg' alt='imagen relacionada' style='width:105px').mx-auto        
                .col-md-10.py-3
                  h3.text-center.mb-3  Emisor
                  p.text-center Origen del mensaje (personas y/o dispositivos).
            .tarjeta.tarjeta--blanca-5.boxShadow.p-5.h-100
              .row.justify-content-center
                .col-md-10.mb-4.mb-md-2.p-0
                  img.mt-3(src='@/assets/curso/images/tema1/ico_19.svg' alt='imagen relacionada' style='width:105px').mx-auto         
                .col-md-10.py-3
                  h3.text-center.mb-3  Destino
                  p.text-center Receptor del mensaje (personas y/o dispositivos).
            .tarjeta.tarjeta--blanca-5.boxShadow.p-5.h-100
              .row.justify-content-center
                .col-md-10.mb-4.mb-md-2.p-0
                  img.mt-3(src='@/assets/curso/images/tema1/ico_20.svg' alt='imagen relacionada' style='width:105px').mx-auto          
                .col-md-10.py-3
                  h3.text-center.mb-3  Canal
                  p.text-center.px-2.px-md-0 Medios por los que el mensaje viaja.
            .tarjeta.tarjeta--blanca-5.boxShadow.p-5.h-100
              .row.justify-content-center
                .col-md-10.mb-4.mb-md-2.p-0
                  img.mt-3(src='@/assets/curso/images/tema1/ico_21.svg' alt='imagen relacionada' style='width:105px').mx-auto        
                .col-md-10.py-3
                  h3.text-center.mb-3  Código
                  p.text-center Lenguaje utilizado para formar el mensaje.
            .tarjeta.tarjeta--blanca-5.boxShadow.p-5.h-100
              .row.justify-content-center
                .col-md-10.mb-4.mb-md-2.p-0
                  img.mt-3(src='@/assets/curso/images/tema1/ico_22.svg' alt='imagen relacionada' style='width:105px').mx-auto         
                .col-md-10.py-3
                  h3.mb-3.text-center Mensaje
                  p.text-center Elemento a transmitir. 

          .cajon.color-custom.p-4.mt-3.mb-4
            p.mb-0 Como se evidencia en la figura, toda comunicación requiere contar con un emisor un mensaje a enviar y un código que permite que el mensaje viaje por un canal, para que ambos actores puedan interactuar requieren contar con un código o lenguaje común, que permita que puedan entenderse, ese estándar o lenguaje común es lo que conocemos como un protocolo de comunicaciones, el cual es un conjunto de normas que están obligadas a cumplir todos los dispositivos, <i>hardware</i> y <i>software</i> que intervienen en una comunicación de datos entre computadoras y demás dispositivos, sin estas reglas o estándares la comunicación resultaría caótica y por tanto imposible.

      .tema1-1.mb-0 
        .bloque-texto-a.color-custom-1.p-md-4
          .row.m-0.align-items-center.justify-content-between
            .col-lg-9(data-aos="fade-right")
              .bloque-texto-a__texto.p-4
                p #[b Dependiendo de los servicios a los cuales accedemos a través de las redes de computadores será el protocolo de comunicación que se deberá emplear en la comunicación entre el usuario que solicita y accede al servicio y el dispositivo quien se lo entrega, en general en la transmisión y recepción de los datos podemos encontrar dos grandes familias de protocolos que se resumen en:]
            .col-lg-3.mb-4.mb-lg-0(data-aos="fade-left")
              figure
                img(src='@/assets/curso/images/tema1/img_10.png')
  .container.bg-white.p-md-5.container-bottom.mt-0.cs.mb-5     
      .row.justify-content-center.mt-0
        .col-lg-12.d-lg-block.mb-4.mt-0(data-aos="fade")  
          .row.justify-content-center.align-items-center.mb-5.tarjeta--blanca-5.p-3(data-aos="fade")
            SlyderA(tipo="b")
              .row.justify-content-center.align-items-center.fondo-slyder-pro
                .col-12.col-lg-8.col-xl-8.mb-0
                  img(src='@/assets/curso/images/tema1/img_banner_pro.png',  alt='imagen relacionada' style='width:1020px')
                .col-11.col-lg-6.col-xl-6.mb-0.neg--left
                  h1.mt-4
                    strong Protocolos orientados #[br]#[.text_re a la conexión]
                  p.mb-3 Estos requieren un modo de comunicación de redes donde se debe establecer una conexión antes de transferir datos. Se identifica el flujo de tráfico con un identificador de conexión en lugar de utilizar explícitamente las direcciones de la fuente y el destino.

                  p.mb-3 Se dice que un servicio de comunicación entre dos dispositivos es orientado a conexión cuando antes de iniciar la comunicación se valida el cumplimiento de ciertas variables como (disponibilidad, alcance, origen, destino, etc.) entre estos dispositivos y se negocian unas credenciales para hacer esta conexión más segura y eficiente.
                  img.mb-4(src='@/assets/curso/images/tema1/img_conexion.svg',  alt='imagen relacionada' style='width:505px') 
              .row.justify-content-center.align-items-end.fondo-slyder-pro
                .col-12.col-lg-8.col-xl-8.mb-0
                  img(src='@/assets/curso/images/tema1/img_banner_pro.png',  alt='imagen relacionada' style='width:755px')
                .col-11.col-lg-6.col-xl-6.mb-0.neg--left
                  h1.mt-4
                    strong Protocolos no orientados #[br]#[.text_re a la conexión]
                  p.mb-4 Sucede cuando una comunicación entre dos puntos finales de una red en los que un mensaje puede ser enviado desde un punto inicial o de origen a otro punto o dispositivo de la red sin acuerdo previo. El dispositivo en un extremo de la comunicación transmite los datos al otro, sin tener que asegurarse de que el receptor esté disponible y listo para recibir los datos. El emisor simplemente envía un mensaje dirigido al receptor.
                  img.mb-4(src='@/assets/curso/images/tema1/img_no_conexion.svg',  alt='imagen relacionada' style='width:505px')                  
    

      p.mb-3 En la figura que se encuentra a continuación, se evidencian algunos ejemplos de los protocolos que son usados en los servicios que normalmente utilizamos en la comunicación entre las redes de datos.

      .row.justify-content-center
        .col-lg-12
          .titulo-sexto.color-acento-contenido
            h5 Figura 2.
            span Ejemplo de protocolos
              

      .row.justify-content-center.align-items-center
        .col-12.col-lg-6.col-xl-6.mb-5(data-aos="fade-right")
          img.img-a.img-t(src="@/assets/curso/images/tema1/fig_2.svg" alt="")
        .col-12.col-lg-6.col-xl-6.mb-5(data-aos="fade-left")
          p.mb-3 Suite de protocolos según el modelo de referencia.
          img.mb-3(src="@/assets/curso/images/tema1/fig_2_1.svg" alt="", style="; display:block; margin:auto 0;")
          figcaption 
            p.mb-0 #[b Nota.] https://interpolados.files.wordpress.com/2017/03/17.png 

      hr.mb-5 

      #5.pRelative
        .backtoTop-5
          a(href="#menu1", title="Puertos de comunicación") 
            img(src='@/assets/curso/images/tema1/flechitaCAC.svg' alt='Volver arriba' style="width:60px; display:block; margin:0 auto;")
        
      .row.mb-3.ps-2
        .col-8.col-lg-3.bg-color-4
          .h3.mb-0.text-white Puertos de comunicación

      p.mb-5 Un puerto de comunicaciones es una interfaz a través de la cual los diferentes dispositivos que intervienen en una comunicación de red pueden enviar y recibir diferentes tipos de datos, los puertos pueden ser de tipo físico (<i>hardware</i>) o lógicos (<i>software</i>), a continuación, se ofrece una breve explicación al respecto:
      
      .row.justify-content-center.align-items-center.mb-3
        .col-lg-9.col-xl-9.mb-5(data-aos="fade")
          ImagenInfografica.color-secundario.mb-5
            template(v-slot:imagen)
              figure
                img(src="@/assets/curso/images/tema1/img_12.svg")
            
            .tarjeta.tarjeta-blanca(x="59.5%" y="65.5%" numero="")
              .head_tar.mt-0.p-2
              .p-3
                h2.mb-3 Puertos  #[BR]#[span.highlight-1 lógicos]
                p.text-alinear.mb-0 Los puertos lógicos son aquellos que utilizan un espacio de la memoria principal del dispositivo (RAM) que se asocia con un puerto físico o un canal de comunicación, y que proporciona un espacio para el almacenamiento temporal de la información que se va a transferir entre la localización de memoria y el canal de comunicación.
                  figure
                    img(src='@/assets/curso/images/tema1/p2.svg' alt='' , style="width:350px")

            .tarjeta.tarjeta-blanca(x="90.5%" y="65.5%" numero="")
              .head_tar.mt-0.p-2
              .p-3
                h2.mb-3 Puertos  #[BR]#[span.highlight-1 físicos]
                p.text-alinear.mb-0 Los productos de capa de enlace de datos describen los métodos para intercambiar tramas de datos entre dispositivos en un medio común.
                  figure
                    img(src='@/assets/curso/images/tema1/p1.svg' alt='' , style="width:350px")
              
            
      .row.justify-content-center.align-items-center
        .col-lg-10.mb-4(data-aos="fade")
          .cajon.color-custom.p-4
            p.mb-0 Para que se establezca una comunicación entre un origen y un destino se requiere entonces que tanto el emisor como el receptor utilicen el mismo protocolo de comunicaciones, pero además se requiere de un puerto de comunicación que facilite que los datos enviados desde el origen vayan por un canal exclusivo.

      hr 
      
      #6.pRelative
        .backtoTop-3
          a(href="#menu1", title="Medios de transmisión") 
            img(src='@/assets/curso/images/tema1/flechitaCAC.svg' alt='Volver arriba' style="width:60px; display:block; margin:0 auto;")
        
      .row.mb-5.ps-2
        .col-8.col-lg-3.bg-color-5
          .h3.mb-0.text-white Medios de transmisión

  .container.bg-white.p-md-2.fondo-3.cs
    .row.justify-content-center.align-items-center.px-5
      .col-12.col-lg-5.col-xl-5
        img.img-a.img-t.m-3(src="@/assets/curso/images/tema1/img_15.svg" alt="")
      .col-12.col-lg-7.col-xl-7
        p.aling-2 Para que la comunicación entre un emisor y un receptor se realice se requiere de un medio que facilite la conexión entre ambos extremos el cual es conocido como el medio de transmisión, este constituye el soporte físico a través del cual emisor y receptor pueden comunicarse en un sistema de transmisión de datos. Los medios de transmisión se pueden categorizar en dos grandes tipos que son los medios guiados y no guiados.
        .cajon.color-custom.p-4.mt-5
          p.mb-3 Los medios guiados conducen (guían) las señales a través de un camino físico, tal como se muestra en la figura 3, dentro de los cuales podemos encontrar:
    
    .row.justify-content-center.align-items-center.my-5.fondo-20_1
      .col-12.col-lg-8
        .row.justify-content-evenly
          .col-lg-6.col-md-6
            .tarjeta.tarjeta_white.h-100.px-0.my-3
              .head_tar.mt-0.p-2
              .row.mb-3.p-3
                .col-lg-8.mb-4
                  h4.text-center.mb-0 
                    strong Fibra óptica
                .col-lg-4.mb-3
                  img.img-a(src='@/assets/curso/images/tema1/icon_1.svg' alt='')
                p.mb-0 Las señales que transportan la fibra óptica corresponden a pulsos de luz, no eléctricos.
              
          .col-lg-6.col-md-6
            .tarjeta.tarjeta_white.h-100.px-0.my-3(data-aos="fade-right")
              .head_tar.mt-0.p-2
              .row.mb-3.p-3
                .col-lg-8.mb-4
                  h4.text-center Cobre (Trenzadoo coaxial)
                .col-lg-4.mb-3(data-aos="fade-left")
                  img.img-a(src='@/assets/curso/images/tema1/icon_2.svg' alt='')
                p.mb-0 Las señales que transportan el cobre son impulsos eléctricos.
        
      .col-12.col-lg-4(data-aos="fade-right")
        .cajon-b.color-primario.p-3.mt-5.mb-5
          p.mb-0  Los medios de transmisión no guiados son aquellos sin cable, transportan ondas electromagnéticas sin usar un conductor físico, sino que se radian a través del aire, por lo que están disponibles para cualquiera que tenga un dispositivo capaz de aceptarlas.

      .row.justify-content-center.mt-5
        .col-lg-12
          .titulo-sexto.color-acento-contenido
            h5 Figura 3.
            span Medios de transmisión guiados

      .row.justify-content-center.align-items-center.mb-5
        .col-12.col-lg-10.col-xl-10.mb-4(data-aos="fade")
          img.my-3(src="@/assets/curso/images/tema1/img_17.svg" alt="")

      p Normalmente utilizan el aire como el medio a través del cual viajan las señales en frecuencias electromagnéticas, por lo que generalmente requieren de una antena que permita transmitir y recibir datos de diferentes tipos.

      .row.justify-content-center.align-items-center.mb-5
        .col-12.col-lg-6.col-xl-6
          .cajon.color-custom.p-3.my-5
            p.mb-0 Dentro de los medios de transmisión no guiados, como se observa en la figura 4, podemos encontrar:
          .titulo-sexto.color-acento-contenido
            h5 Figura 4.
            span Ejemplos de medios de transmisión no guiados 
          img(src="@/assets/curso/images/tema1/img_18.svg" alt="")(data-aos="fade-right")
        .col-12.col-md-4.col-lg-6.col-xl-6.my-3.d-none.d-lg-block
          img(src="@/assets/curso/images/tema1/img_19.svg" alt="")(data-aos="fade-left")

  
        
      hr

      #7.pRelative.pt-4
        .backtoTop-3
          a(href="#menu1", title="Recursos compartidos") 
            img(src='@/assets/curso/images/tema1/flechitaCAC.svg' alt='Volver arriba' style="width:60px; display:block; margin:0 auto;")
  
  
      .row
        .col-8.col-lg-3.bg-color-5
          .h3.mb-0.text-white Recursos compartidos

  .container.bg-white.p-md-4.fondo-20_1  
    .row.mb-5
      .col-lg-7.mb-4.mb-lg-0(data-aos="fade-right")
        p.aling-18.mb-4 Como ya hemos mencionado, las redes de datos facilitan y potencian el trabajo en red entre los diferentes usuarios y dispositivos, de tal manera que se pueda acceder a dispositivos y recursos compartidos, cuando indicamos los recursos, nos referimos a todos esos elementos tanto <i>hardware</i> como <i>software</i> que pueden ser compartidos y utilizados por los diferentes dispositivos conectados, estos recursos pueden ser desde el punto de vista del <i>hardware</i>:
        .row.justify-content-center
          .col-md-4 
            img.img-a.img-t(src='@/assets/curso/images/tema1/1.svg'  alt='')
          .col-md-4
            img.img-a.img-t(src='@/assets/curso/images/tema1/2.svg' alt='imagen relacionada')
          .col-md-4
            img.img-a.img-t(src='@/assets/curso/images/tema1/3.svg' alt='')
      .col-lg-5.d-none.d-lg-block(data-aos="fade-left")
        img.img-a.img-t(src='@/assets/curso/images/tema1/img_23.png',)


    p.text-center.mb-5 Desde el punto de vista lógico podemos compartir recursos como:
    
    .row.justify-content-center.align-items-center(data-aos="fade")

      .col-md-6.my-3
        img.img-a.img-t(src="@/assets/curso/images/tema1/ico_23.svg" alt="")
      .col-md-6.my-3
        img.img-a.img-t(src="@/assets/curso/images/tema1/ico_24.svg" alt="")
      .col-md-6.my-3
        img.img-a.img-t(src="@/assets/curso/images/tema1/ico_25.svg" alt="")
      .col-md-6.my-3
        img.img-a.img-t(src="@/assets/curso/images/tema1/ico_26.svg" alt="")
  
  .container.bg-white.p-4.container-bottom.pt-0
      Separador

      #t_1_2.titulo-segundo
        .h2 1.2 Servicios propietarios

      .row.bg-tema-1-2
        .col-lg-12.px-lg-2.px-4.py-4(data-aos="fade-right")
          .row.align-items-center.justify-content-evenly
            .col-lg-4(data-aos="fade-right")
              img.img-a.img-t(src='@/assets/curso/images/tema1/img_pc_2-1.svg' alt='Imagen decorativa')
            .col-lg-7.col-md-12.text-white.p-3(data-aos="fade-left")
              p Antes de la llegada de la computación en la nube, los servicios, infraestructura, plataformas y en general los recursos de TI debían ser instalados, configurados y administrados en su totalidad por la empresa lo que conlleva varios inconvenientes entre los cuales se pueden mencionar los siguientes:
      
  .container.bg-white.p-md-5.fondo-5
    .row.justify-content-center.align-items-center
      .col-12.col-lg-7.col-xl-7(data-aos="fade-right") 
        LineaTiempoD.linea-tiempo-d
            p(numero="1" titulo="Paso 1") El almacenamiento de los datos se hace de manera local en dispositivos como discos duros y servidores locales, este trae consigo el problema de que si llegase a fallar el servidor se corre el riesgo de la pérdida de información o pérdida de acceso a los servicios.

            p(numero="2" titulo="Paso 2") La administración de los recursos, que se relaciona con: el suministro de energía, aire acondicionado, sistemas de protección UPS y el mantenimiento preventivo y/o correctivo de los dispositivos, sin mencionar el hecho de que la tecnología en cuanto a infraestructura, va perdiendo su valor y se va devaluando rápidamente debido al constante desarrollo y evolución.

            p(numero="3" titulo="Paso 3") A nivel de aplicaciones se tiene el inconveniente de tener que administrarse no solo la aplicación si no la plataforma de desarrollo, adicionalmente si se cuenta con aplicaciones no web sino tipo escritorio se obliga a tener que estar actualizando el servidor y los clientes que acceden a estas, una razón más para disponer de aplicaciones como servicio ofrecidas a través de la nube.

            p(numero="4" titulo="Paso 4") A nivel de conectividad en la mayoría de las ocasiones el acceso a los servicios, aplicaciones y recursos normalmente está restringido a un acceso local, puesto que disponer de estrategias de conexión remotas requiere tener adicionalmente dispositivos de protección perimetral como <i>firewalls</i> y requerirá un nivel adicional de protección y administración desde el punto de vista de la ciberseguridad.
        
      .col-12.col-md-4.col-lg-5.col-xl-5.mb-5.d-none.d-lg-block(data-aos="fade-left")
        img.img-a.img-t(src="@/assets/curso/images/tema1/img_25.png" alt="")
  .container.bg-white.px-4

      Separador 
      #t_1_3.titulo-segundo.color-acento-contenido
        h2 1.3 La evolución de la informática en la nube
  
  .container.bg-white.fondo-3
    .row.justify-content-center.align-items-center.my-5
      .col-11.col-lg-4.col-xl-4.mb-4(data-aos="fade-right") 
        img.img-a.img-t(src="@/assets/curso/images/tema1/img_26.svg" alt="").mb-3
      .col-12.col-lg-8.col-xl-8.my-3(data-aos="fade-left")
        p Si bien la computación en la nube es un término que se popularizó como un nuevo paradigma en el acceso a servicios e infraestructura en los años 2008 y 2009, desde la década del 60 ya se hablaba de este paradigma y, es a John McCarthy a quien se le atribuye la definición y el concepto tanto de cómputo en la nube como el de inteligencia artificial.
        .cajon.color-custom.p-3.mt-5
          p.mb-3 Posteriormente surgen nuevos autores como Joseph Carl Robnett Licklider, quien en sus conceptos siempre hablo de contar con una tecnología que permitiera que todo el mundo estuviera interconectado y que de esta manera  pudiera acceder a la información desde cualquier lugar sin límites de distancias ni fronteras, este sueño dio origen a la computación en la nube, la cual se crea con el propósito de poder descentralizar los recursos de cómputo y almacenamiento para distribuirlos alrededor del mundo y facilitar el acceso a la información cada vez a más personas.
  .container.bg-white.px-4
      .col-lg-12.mx-auto.mb-5
        .tema1-1 
          .bloque-texto-a.color-custom-1.px-4.py-2
            .row.m-0.align-items-center.justify-content-between
              .col-lg-8(data-aos="fade-right") 
                .bloque-texto-a__texto.p-4
                  p.mb-3
                    strong Los orígenes del término “nube”, comúnmente se asocian al término que se derivó de una metáfora que tomaba como base al dibujo de nubes que se utilizaban en el pasado para representar a la red telefónica, y que posteriormente algunos comenzaron a representar al Internet.

                  p 
                    strong Podemos resumir la evolución en las siguientes fases:
              .col-lg-4.mb-0.mb-lg-0.mt-0
                figure
                  img.img-a(src='@/assets/curso/images/tema1/img_10.png' alt='Volver arriba')
  
      .row.justify-content-center.align-items-start.mb-3.fondo-6.px-5
        .col-lg-2.col-md-12.text-center.my-3
          .row.justify-content-center
            .col-lg-2
              p.text_gr.mb-0 
                strong 01
        .col-lg-5.col-md-6.my-3.text-center(data-aos="fade-right") 
          h3.mb-3 Primera Etapa- Década de los 60
          img.img-a.img-t.mb-3.mb-md-0(src="@/assets/curso/images/tema1/img_28.png" alt="", style="width:250px")
        .col-lg-5.col-md-6.my-3(data-aos="fade-left")
          p Joseph Carl Robnett Licklider informático estadunidense, conceptualiza por primera vez la idea y concepto de la computación en la nube.

      .row.justify-content-evenly.align-items-start.mb-3.fondo-7.p-5
        .col-md-12.text-center.my-3
          .row.justify-content-center
            .col-lg-2
              p.text_gr 
                strong 02
        .col-12.col-md-12.mb-4
          .row
            .col-12.col-lg-7.col-xl-7.mb-4(data-aos="fade-right") 
              h3.mb-2 Segunda Etapa- Inicia sobre los 90 y va hasta 2006
              p Empieza y se desarrolla el proceso de masificación del acceso a internet, pasando a ser una tecnología exclusiva, costosa y de acceso limitado para pocos, posteriormente se popularizó, facilitando el acceso cada vez, a más empresas, este mecanismo permitió que a través de internet se originara lo que hoy conocemos con el término de aplicaciones como servicio.
              .cajon.color-custom.p-4.mt-3
                p.mb-0 Dentro de esta etapa podemos destacar como uno de los mayores avances computacionales cuando se afianzó el concepto de virtualización a finales de esa década, nace #[b Salesforce] empresa que desarrolla la primera ola de nube cuando propone ofrecer aplicaciones empresariales a través de un acceso web sencillo y simple.

            .col-12.col-lg-3.col-xl-5.mb-4(data-aos="fade-left")
              img.img-a.mt-5(src="@/assets/curso/images/tema1/img_29.png" alt="", )
          p.mb-0 Si bien en esta etapa no se había consolidado la computación en la nube, la infraestructura, tecnologías y desarrollo tecnológico propio del internet fue fundamental para el crecimiento y evolución a lo que hoy conocemos como computación en la nube.

      .row.justify-content-evenly.fondo-8.align-items-start.p-5
        .col-md-12.text-center.my-3
          .row.justify-content-center
            .col-lg-2(data-aos="fade-left")
              p.text_gr 
                strong 03
        .col-md-12.mb-0
          .row.justify-content-center
            .col-lg-8.col-md-12.my-3
              h3.mb-3 Tercera Etapa – Reconocida históricamente en el 2007
              p.mb-5 Se desarrolla la tecnología de poner “línea” (internet) en toda la plataforma e infraestructura tecnológica requerida por una empresa, incluyendo <i>hardware</i>, <i>software</i> e <i>internetworking.</i>
              .cajon.color-custom.p-4.mb-4
                p.mb-0 Nacen las grandes empresas como Google,  Amazon AWS, Apple Cloud, Microsoft Azure, Alibaba <i>Cloud</i>, que trabajan a partir del uso de internet y de servidores centralizados, con facilidades de acceso a servicios e infraestructura de manera remota, descentralizada y por demanda.              
            .col-lg-4.col-md-5.my-3
                img.img-a.img-t(src="@/assets/curso/images/tema1/img_30.png" alt="", ).mx-3          

            .col-lg-12.col-md-7.my-3
              p.mb-0 La computación en la nube en la última década pasó de ser el servicio que grandes empresas de tecnologías ofrecían como una alternativa tecnológica a sus clientes, para convertirse en un factor preponderante en la transformación digital y adopción de buenas prácticas que toda empresa necesita, la cuarta revolución industrial, la popularización y cada vez más necesaria adopción de tecnologías como IoT, IA, <i>Big Data, Machine Learning </i>entre otros hace necesario que se migre y se adopten estos servicios en la nube, ya no solo desde los servicios tradicionales si no que a medida que se van adoptando estas tecnologías irán surgiendo y desarrollando una nueva oferta de servicios que transforman y mejoran los procesos de negocio.

      Separador

      #t_1_4.titulo-segundo.mb-0
        .h2 1.4 Bloques de creación en la nube
        
      .row.justify-content-center.align-items-center.fondo-9.mb-3
        .col-12.col-md-12.col-lg-7.col-xl-7.my-3(data-aos="fade-right")
          p.mb-3 La computación en la nube permite el uso de recursos y servicios tecnológicos a través de la Red en este caso internet, la nube da la posibilidad de que cada empresa pueda acceder a los servicios requeridos es decir no todos necesitaran o utilizaran los mismos servicios, las tecnologías de la información, y las comunicaciones se han convertido en un factor potenciador y necesario para que las empresas sin importar el tipo, sino que funcionen de una manera eficaz y efectiva de acuerdo a su <i>core</i> de negocio, aunque en general los recursos de TI los podemos clasificar en tres componentes, como se ve en la figura 5.
          .cajon.color-custom.p-4.mb-4
            p.mb-0 Estos componentes de igual manera requieren una serie de tareas asociadas, estas son:
          .row.justify-content-center.mb-3
            .col
              img.img-a.img-t(src='@/assets/curso/images/tema1/img_icon.svg' alt='imagen relacionada')
        .col-12.col-lg-5.col-xl-5.mb-4(data-aos="fade-left")
            img.img-a.img-t(src="@/assets/curso/images/tema1/img_31.png" alt="")

      p.mb-3 Toda organización que requiera implementar cualquier solución de TI requerirá desarrollar las anteriores tareas, si la organización tiene además sus propios desarrollos o procesos de desarrollo <i>in house</i>, se debe agregar las tareas anteriormente mencionadas las plataformas de desarrollo.

      p.mb-5 En general los bloques de creación en la nube los podemos catalogar en 4 niveles que son:
      
      .row.justify-content-center.align-items-center.fondo-10.mb-5.mt-5(data-aos="fade")
        SlyderA(tipo="b")
          .row.justify-content-center.align-items-center.p-md-3
            .col-11.col-lg-5.mb-4.mb-md-0
              figure
                img.img-a.img-t.mb-5(src='@/assets/curso/images/tema1/img_32.svg', alt='')
            .col-10.col-lg-7
              h4.mb-4 Nivel de infraestructura
              p.mb-4 Son los recursos utilizados por la empresa en un servicio en la nube, estos recursos pueden ser: 
              ul.lista-ul--color.px-md-4
                li.mb-1
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | Almacenamiento
                li.mb-1 
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | Procesamiento
                li.mb-1 
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | <i>Networking</i> 
                li.mb-1
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | <i>Software</i> de administración de la infraestructura.

          .row.justify-content-center.align-items-center
            .col-11.col-lg-5.mb-4.mb-md-0
              h4.mb-4 Uso compartido de recursos
              p.mb-4 Normalmente asociados a la consolidación y uso de tecnologías como la virtualización que permite un entorno compartido donde se pueden ejecutar varias máquinas virtuales o contenedores en un mismo servidor, se proporcionan servicios como:
              ul.lista-ul--color.px-md-4
                li.mb-1
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | <i>Software</i>
                li.mb-1 
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | Red  
                li.mb-1 
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | Almacenamiento
            .col-10.col-lg-7
              figure
                img.img-a.img-t(src='@/assets/curso/images/tema1/img_33.svg', alt='imagen ambiental')
            
          .row.justify-content-center.align-items-center
            .col-11.col-lg-5.mb-4.mb-md-0
              figure
                img.img-a.img-t.mb-4(src='@/assets/curso/images/tema1/img_34.svg', alt='')
            .col-10.col-lg-7
              h4.mb-4 Plataformas de desarrollo
              p.mb-4 Esta capa permite a los desarrolladores de <i>software</i> construir aplicaciones a través de las interfaces de programación de aplicaciones (API), esto suministrado por el proveedor de servicios en la nube, a través de las API, el desarrollador puede acceder a servicios de:
              ul.lista-ul--color.px-md-5
                li.mb-1 
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | Autenticación
                li.mb-1 
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | Bases de datos 
                li.mb-1
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | Almacenamiento
                li.mb-1 
                  i.fas.fa-caret-right(style="color: #FF2C9C")
                  | Otros módulos o servicios disponibles.

          .row.justify-content-evenly.align-items-center
            .col-11.col-lg-5.mb-4.mb-md-0
              h4.mb-4 <i>Software</i> de aplicaciones
              p.mb-0 Son todas aquellas aplicaciones desarrolladas <i>in house</i> o adquiridas. Utilizadas por las organizaciones para el cumplimiento de sus procesos misionales, son las aplicaciones que utiliza el usuario final. 
            .col-10.col-lg-7
              figure
                img.img-a.img-t(src='@/assets/curso/images/tema1/img_35.svg', alt='')



  .container.bg-white.fondo-22.mg-top
    p.mb-4 A continuación, se ilustra el modelo de Bloques y sus diferentes niveles.      

    .row.justify-content-center.align-items-center
      .col-12(data-aos="fade")
        figure
          img.img-a.img-t(src='@/assets/curso/images/tema1/img_36.svg', alt='')
  .container.bg-white.px-5.container-bottom.cs
    
    Separador

    #t_1_5.titulo-segundo
      .h2 1.5 Tipos de nubes
    
    p.mb-3 Para acceder a los servicios de computación en la nube existen varios modelos de entrega o despliegue de la nube los cuales pueden ser, veamos:

      .row.justify-content-center.align-items-center.fondo-23
        .col-md-12.col-lg-6.my-3(data-aos="fade-right")
          img.img-a.img-t(src="@/assets/curso/images/tema1/img_38.svg" alt="")
        .col-md-12.col-lg-6.my-3(data-aos="fade-left")
          SlyderF
            .tarjeta.tarjeta--blanca-5.boxShadow.p-5.h-100
              .row.justify-content-center.mb-3
                .col
                  img(src='@/assets/curso/images/tema1/ico_35.svg' alt='imagen relacionada' style='width:105px').mx-auto
              h3.text-center.mb-3  Nube pública
              p.text-center Los servicios e infraestructura son gestionados por un proveedor de tecnológico el cual ofrece estos servicios al público en general. 
            .tarjeta.tarjeta--blanca-5.boxShadow.p-5.h-100
              .row.justify-content-center.mb-3
                .col
                  img(src='@/assets/curso/images/tema1/ico_36.svg' alt='imagen relacionada' style='width:105px').mx-auto
              h3.text-center.mb-3  Nube privada
              p.text-center En este tipo de nube los servicios y la infraestructura es gestionada específicamente por una organización y no se ofrecen estos servicios al público en general.
            .tarjeta.tarjeta--blanca-5.boxShadow.p-5.h-100
              .row.justify-content-center.mb-3
                .col
                  img(src='@/assets/curso/images/tema1/ico_37.svg' alt='imagen relacionada' style='width:105px').mx-auto
              h3.text-center.mb-3  Nube híbrida
              p.text-center Son nubes que combinan las características de dos nubes privadas, las nubes públicas o compartidas, se caracterizan por que permiten el poder compartir servicios e infraestructura entre ambas nubes.
            .tarjeta.tarjeta--blanca-5.boxShadow.p-5.h-100
              .row.justify-content-center.mb-3
                .col
                  img(src='@/assets/curso/images/tema1/ico_38.svg' alt='imagen relacionada' style='width:105px').mx-auto
              h3.text-center.mb-3  Nube comunitaria
              p.text-center Este es un tipo de nube que es creada para un propósito o fin específico donde se accede y comparte servicios e infraestructura entre los integrantes de la nube, normalmente son administradas por alguno de los miembros de la comunidad organizada en la nube.

        Separador

      #t_1_6.titulo-segundo
        .h2 1.6 Principales proveedores de servicios en la nube  

      .contenedor-total.mb-0(data-aos="fade")
        figure
          img(src='@/assets/curso/images/tema1/img_39.png' alt='Imagen ambiental' style='')
        .contenedor-text.neg--top1
          .row.justify-content-center.p-md-5.px-3-py-3
            .col-auto
              p.mb-0 Debido a la masificación y cada vez mayor adopción de tecnologías de <i>cloud computing</i>, han sido muchos los nuevos proveedores que han ido surgiendo y posicionando sus ofertas de servicios, sin embargo, en el mundo occidental podemos mencionar los siguientes como los más grandes y más importantes proveedores de servicios en la nube.

      AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
        .row(titulo="Amazon Web Services (AWS)")
          .col-md-12.col-lg-6(data-aos="fade-right")
            figure
              img.img-a.img-t(src='@/assets/curso/images/tema1/img_amazon.png', alt='')
          .col-md-12.col-lg-6.mb-4.mb-md-0(data-aos="fade-left")
            figure
              img.img-a.img-t(src='@/assets/curso/images/tema1/img_amazon_1.svg', alt='')
            hr 
            p <b>Amazon Web Services (AWS), </b> es quizá el líder en la oferta de varios servicios a través de la nube en este caso pública, esta empresa empezó ofreciendo servicios como el conocido S3, servicio dedicado al almacenamiento de objetos y posteriormente agregó a su oferta los servicios de EC2, la nube de proceso elástico o por demanda donde se puede acceder a máquinas virtuales, contenedores y virtualización en general. 
          .cajon.color-custom-3.p-4.mb-3(data-aos="fade")
            p.mb-0 AWS es quizá la nube más grande con <i>datacenter</i> de alta disponibilidad distribuidos alrededor del mundo proporcionando redundancia y disponibilidad en más de 22 regiones distintas, (figura 7) cada zona de disponibilidad constituye una partición totalmente aislada de la infraestructura de AWS que consta de centros de datos discretos con alimentación, redes y conectividad redundantes.
          .row.justify-content-center
              .col-lg-12
                .titulo-sexto.color-acento-contenido
                  h5 Figura 7 
                  span  Regiones con Centros de Datos AWS
          .row.justify-content-center
            .col-lg-12.mb-4(data-aos="fade")
                img.img-a.img.t(src="@/assets/curso/images/tema1/img_40.svg" alt="")
          
          .row.justify-content-end.fondo-15
            .col-lg-5.my-3
              SlyderF
                .tarjeta.tarjeta--blanca-5.boxShadow.p-4
                  .row.justify-content-center.mb-3
                  h3.text-center.mb-3.bg-color-1.text-white Servicios de procesamiento
                  p Procesamiento a través de máquinas virtuales, contenedores o instancias de diferentes configuraciones las cuales pueden ser alquiladas por horas, días o por un largo tiempo, este servicio es conocido como Ec2.

                .tarjeta.tarjeta--blanca-5.boxShadow.p-4
                  .row.justify-content-center.mb-3
                  h3.text-center.mb-3.bg-color-1.text-white  Servicios de almacenamiento
                  p Es el servicio de almacenamiento que puede ser elástico (EBS) o servicios de almacenamiento simple (S3), incluye almacenamiento de objetos, bases de datos, almacenamiento y recuperación de objetos binarios (BLOB), entre múltiples servicios adicionales relacionados con el almacenamiento de información.

                .tarjeta.tarjeta--blanca-5.boxShadow.p-4
                  .row.justify-content-center.mb-3
                  h3.text-center.mb-3.bg-color-1.text-white  Servicios de redes
                  p En este servicio es muy popular la Ruta 53 de Amazon, la cual ofrece el servicio de interconexión y conectividad entre las diferentes instancias o con otras redes externas, incluye además servicios como Nube privada virtual(VPC), <i>Elastic Load Balancer</i> (EBL).
                
          .row.justify-content-center.d-block.d-lg-none.mb-4
            .col-lg-12
              img(src="@/assets/curso/images/tema1/back.png" alt="")
            .col-lg-6
              SlyderF
                .tarjeta.tarjeta--blanca-5.boxShadow.p-4
                  .row.justify-content-center.mb-3
                  h3.text-center.mb-3.bg-color-1.text-white Servicios de procesamiento
                  p Procesamiento a través de máquinas virtuales, contenedores o instancias de diferentes configuraciones las cuales pueden ser alquiladas por horas, días o por un largo tiempo, este servicio es conocido como Ec2.

                .tarjeta.tarjeta--blanca-5.boxShadow.p-4
                  .row.justify-content-center.mb-3
                  h3.text-center.mb-3.bg-color-1.text-white  Servicios de almacenamiento
                  p Es el servicio de almacenamiento que puede ser elástico (EBS) o servicios de almacenamiento simple (S3), incluye almacenamiento de objetos, bases de datos, almacenamiento y recuperación de objetos binarios (BLOB), entre múltiples servicios adicionales relacionados con el almacenamiento de información.

                .tarjeta.tarjeta--blanca-5.boxShadow.p-4
                  .row.justify-content-center.mb-3
                  h3.text-center.mb-3.bg-color-1.text-white  Servicios de redes
                  p En este servicio es muy popular la Ruta 53 de Amazon, la cual ofrece el servicio de interconexión y conectividad entre las diferentes instancias o con otras redes externas, incluye además servicios como Nube privada virtual(VPC), <i>Elastic Load Balancer</i> (EBL).

        div(titulo="Microsoft Azure")
          .col-lg-12.mx-auto.mb-4
            .tema1-1 
              .bloque-texto-a.color-custom-4.p-3.p-md-2
                .row.m-0.align-items-center.justify-content-between
                  .col-lg-4.mb-4.mb-lg-0
                    figure
                      img.img-a(src='@/assets/curso/images/tema1/img_42.png' alt='Volver arriba')
                  .col-lg-8
                    .bloque-texto-a__texto.p-4
                      p.mb-0 <b>Es la nube de la empresa Microsoft, Azure </b> es quizá la plataforma con crecimiento más rápido en el mercado de <i>Cloud</i>, tiene más de 50 centros de datos distribuidos alrededor de más de 140 países (figura 8) a través de servicios como Azure Stack permite que una organización pueda crear su nube privada y posteriormente integrar a la nube pública de Azure y de esta manera poder interactuar con todas las bondades, características y servicios de Azure.
                  
          .row.justify-content-center
              .col-lg-12
                .titulo-sexto.color-acento-contenido
                  h5 Figura 8
                  span  Regiones con Centros de Datos Microsoft Azure
          .row.justify-content-center
            .col-lg-12.mb-4
                img(src="@/assets/curso/images/tema1/map_azure.svg" alt="")

            .row.justify-content-end.align-items-center.fondo-16
              .col-12.col-md-4.col-lg-6
                SlyderF(columnas="col-12")
                  .tarjeta.tarjeta--blanca.boxShadow.p-5
                    .row.justify-content-center.mb-3
                    h3.text-center.mb-3.bg-color-1.text-white Servicios de procesamiento
                    p En este servicio Azure ofrece: 
                      ul.lista-ul.mt-3
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | Azure <em>Virtual Machines</em> con instancias de distintos tipos, soportando Windows y algunas versiones o distribuciones de Linux
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | <i>Azure Storage</i>

                  .tarjeta.tarjeta--blanca.boxShadow.p-5
                    .row.justify-content-center.mb-3
                    h3.text-center.mb-3.bg-color-1.text-white  Servicios de almacenamiento
                    p El servicio es conocido como Azure Storage este servicio incluye:
                      ul.lista-ul.mt-3
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | <i>Azure blobs</i> para el almacenamiento de objetos binarios grandes <i>(BLOBS)</i>.
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | <i>Azure Tables</i> para el almacenamiento de bases de datos No SQL.
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | <i>Azure File</i> que son servicios de almacenamiento compatibles con Windows (SMB), al igual que ofrece todos los servicios de almacenamiento de bases de datos relacionales a través de <i>Azure SQL Database.</i>

                  .tarjeta.tarjeta--blanca.boxShadow.p-5
                    .row.justify-content-center.mb-3
                    h3.text-center.mb-3.bg-color-1.text-white  Servicios de redes
                    p A través del servicio de Azure virtual network ofrece redes privadas virtuales, ofrece el servicio de Azure Traffic Manager para enrutar y administrar la conectividad y acceso a sus instancias y redes externas.
          
          .row.justify-content-center.d-block.d-lg-none.mb-4 
            .col-lg-12
              img(src="@/assets/curso/images/tema1/back_17.png" alt="")
            .col-lg-4
              SlyderF(columnas="col-12")
                .tarjeta.tarjeta--blanca.boxShadow.p-5
                  .row.justify-content-center.mb-3
                  h3.text-center.mb-3.bg-color-1.text-white Servicios de procesamiento
                  p En este servicio Azure ofrece: 
                    ul.lista-ul.mt-3
                      li 
                        i.fas.fa-caret-right(style="color: #FF2C9C")
                        | Azure <em>Virtual Machines</em> con instancias de distintos tipos, soportando Windows y algunas versiones o distribuciones de Linux
                      li 
                        i.fas.fa-caret-right(style="color: #FF2C9C")
                        | <i>Azure Storage</i>

                .tarjeta.tarjeta--blanca.boxShadow.p-5
                  .row.justify-content-center.mb-3
                  h3.text-center.mb-3.bg-color-1.text-white  Servicios de almacenamiento
                  p El servicio es conocido como Azure Storage este servicio incluye:
                    ul.lista-ul.mt-3
                      li 
                        i.fas.fa-caret-right(style="color: #FF2C9C")
                        | <i>Azure blobs</i> para el almacenamiento de objetos binarios grandes <i>(BLOBS)</i>.
                      li 
                        i.fas.fa-caret-right(style="color: #FF2C9C")
                        | <i>Azure Tables</i> para el almacenamiento de bases de datos No SQL.
                      li 
                        i.fas.fa-caret-right(style="color: #FF2C9C")
                        | <i>Azure File</i> que son servicios de almacenamiento compatibles con Windows (SMB), al igual que ofrece todos los servicios de almacenamiento de bases de datos relacionales a través de <i>Azure SQL Database.</i>

                .tarjeta.tarjeta--blanca.boxShadow.p-5
                  .row.justify-content-center.mb-3
                  h3.text-center.mb-3.bg-color-1.text-white  Servicios de redes
                  p A través del servicio de Azure virtual network ofrece redes privadas virtuales, ofrece el servicio de Azure Traffic Manager para enrutar y administrar la conectividad y acceso a sus instancias y redes externas.
          
        
        div(titulo="Amazon Web Services (AWS)")

          .col-lg-12.mx-auto.mb-5
            .tema1-1 
              .bloque-texto-a.color-custom-4.p-3.p-md-5
                .row.m-0.align-items-center.justify-content-between
                  .col-lg-4.mb-4.mb-lg-0
                    figure
                      img(src='@/assets/curso/images/tema1/img_google_pla.png' alt='Volver arriba' style="width:300px; display:block; margin:0 auto;")
                  .col-lg-8
                    .bloque-texto-a__texto.p-5
                      p.mb-0 Google <i> Cloud Platform </i> (GCP) es una plataforma que ha ido evolucionando en su oferta de servicios como respuesta al crecimiento de sus competidores, Google cuenta con aproximadamente 60 centros de Datos en más de 20 regiones alrededor del mundo, como puede observarse en la figura 9.

            .titulo-sexto.color-acento-contenido
              h5 Figura 9
              span  Regiones de Google <i>Cloud</i>
            img(src="@/assets/curso/images/tema1/fig9.png" alt="")
          
          .row.justify-content-end.align-items-center.fondo-17
              .col-12.col-md-4.col-lg-5.col-xl-5.d-none.d-lg-block
                SlyderF.mt-5(columnas="col-12")
                  .tarjeta.tarjeta--blanca.boxShadow.p-5
                    .row.justify-content-center.mb-3
                    h3.text-center.mb-3.bg-color-1.text-white Servicios de procesamiento
                    p A través de su servicio Google <i> Compute Engine </i> (GCE), ofrece máquinas virtuales e instancias de diferentes tipos con sistema operativo Linux.

                  .tarjeta.tarjeta--blanca.boxShadow.p-5
                    .row.justify-content-center.mb-3
                    h3.text-center.mb-3.bg-color-1.text-white  Servicios de almacenamiento
                    p Google <i>Cloud</i> cuenta con tres servicios de almacenamiento principales: 
                      ul.lista-ul.mt-3
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | Google <i>Cloud Storage</i>, un servicio de almacenamiento de objetos similar a AWS S3 y Azure <i>Blobs</i>. 
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | Google <i>Cloud Datastore</i> es un servicio administrado de almacén de datos NoSQL. 
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | <i>Cloud</i> SQL servicio que proporciona el almacenamiento de bases de datos tradicionales SQL.

                  .tarjeta.tarjeta--blanca.boxShadow.p-5
                    .row.justify-content-center.mb-3
                    h3.text-center.mb-3.bg-color-1.text-white  Servicios de redes
                    p Google ofrece varios productos de red para administrar las conexiones entre los servicios en la nube de Google y el mundo exterior, es decir, el equilibrio de carga, la interconexión y los servicios DNS. Toda la infraestructura de Google es neutral en carbono y sus centros de datos consumen un 50% menos de energía que los centros de datos habituales.
          
          .row.justify-content-center.d-block.d-lg-none.mb-4 
            .col-lg-12
              img(src="@/assets/curso/images/tema1/back_16.png" alt="")
            .col-lg-6
              SlyderF.mt-5(columnas="col-12")
                  .tarjeta.tarjeta--blanca.boxShadow.p-5
                    .row.justify-content-center.mb-3
                    h3.text-center.mb-3.bg-color-1.text-white Servicios de procesamiento
                    p A través de su servicio Google <i> Compute Engine </i> (GCE), ofrece máquinas virtuales e instancias de diferentes tipos con sistema operativo Linux.

                  .tarjeta.tarjeta--blanca.boxShadow.p-5
                    .row.justify-content-center.mb-3
                    h3.text-center.mb-3.bg-color-1.text-white  Servicios de almacenamiento
                    p Google <i>Cloud</i> cuenta con tres servicios de almacenamiento principales: 
                      ul.lista-ul.mt-3
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | Google <i>Cloud Storage</i>, un servicio de almacenamiento de objetos similar a AWS S3 y Azure <i>Blobs</i>. 
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | Google <i>Cloud Datastore</i> es un servicio administrado de almacén de datos NoSQL. 
                        li 
                          i.fas.fa-caret-right(style="color: #FF2C9C")
                          | <i>Cloud</i> SQL servicio que proporciona el almacenamiento de bases de datos tradicionales SQL.

                  .tarjeta.tarjeta--blanca.boxShadow.p-5
                    .row.justify-content-center.mb-3
                    h3.text-center.mb-3.bg-color-1.text-white  Servicios de redes
                    p Google ofrece varios productos de red para administrar las conexiones entre los servicios en la nube de Google y el mundo exterior, es decir, el equilibrio de carga, la interconexión y los servicios DNS. Toda la infraestructura de Google es neutral en carbono y sus centros de datos consumen un 50% menos de energía que los centros de datos habituales.
          

      p.mb-3 A continuación, se muestra una tabla resumen con los principales servicios ofrecidos por cada uno de los proveedores antes mencionados.
      .row.justify-content-center.mb-4
        .col-lg-12
          .titulo-sexto.color-acento-contenido
            h5 Figura 10
            span  Servicios ofrecidos por cada proveedor de <i>Cloud</i>

      .row.justify-content-center
        .col-lg-10.mb-4(data-aos="fade")
            img.img-a.img-t(src="@/assets/curso/images/tema1/img_48.svg" alt="")






    
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    mostrarIndicador: true,
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
