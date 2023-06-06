<template>
    <title>Rediseño Web ESD: Manual</title>
    <div class="app bg-whito">
        <Banner title="Rediseño Web ESD" logo="web/logo_ESD_WEB.svg" banner="web/manual_banner.jpg">
            <NuxtLink to="/">
                <Botona>Ver Manual Yelmo</Botona>
            </NuxtLink>
        </Banner>
        <div class="body flex m-auto max-w-[1280px] items-start">
            <Sidebar class="w-25% pt-2 sticky h-auto top-8" :array="array" :subArray="subArray" />
            <div class="flex flex-col gap-24 w-full">
                <div class="sec mt-8 Investigación">
                    <div class="h3">
                        Investigación
                    </div>
                    <Article class="borde article_scrollable" tit="Investigación previa" :img="['web/investigacion.jpg']">
                        Luis
                        Realizamos una investigación concienzuda sobre el funcionamiento de la web e intranet de la ESD y
                        las
                        experiencias de los usuarios con ella. En resumen, las conlcusiones extraidas fueron las siguientes:
                        <br />
                        <div class="h4">Estudiantes:</div>
                        <br />
                        - Descontento general con las aulas virtuales, tanto el moodle como educamadrid funcionan
                        similar<br />
                        - Existen funcionalidades que no se utilizan<br />
                        - En la nueva no hay posibilidad de consultar la sistencia<br />
                        - Mala visualización de comentarios en las entregas, a veces los profesores no se dan cuenta de que
                        hay cosas escritas ahí<br />
                        - Sistema de mensajería mejorable. Algunos profes usan métodos alternativos o externos como
                        Slack<br />
                        <br />
                        <div class="h4">Profesores:</div>
                        <br />
                        - Mejorable visualización del listado de entregas y alumnos. Scroll horizontal problemático<br />
                        - Pueden dejar matriculación abierta o poner una contraseña. En el nuevo la matriculación de los
                        alumnos la hace el TIC pero pueden matricular ellos manualmente a los alumnos, los alumnos no se
                        pueden matricular de forma autónoma en las asignaturas<br />
                        - Piden presupuestos para material y gestionan el material e sus aulas<br />
                        - Evalúan<br />
                        - Seleccionan reparto de aulas vía mail<br />
                        - Tutorías tfg se llevan como una asignatura más del aula<br />
                        - En caso de querer realizar eventos también los gestionan ellos<br />
                        - Creación del plan de estudios<br />
                        <br />
                        <div class="h4">Secretaría:</div>
                        <br />
                        - Gestión de info de alumnos y expedientes a través de una app de la comunidad de madrid<br />
                        - Ejecutan lo que manda jefatura<br />
                        <br />
                        <div class="h4">TIC:</div>
                        <br />
                        - Gestionan alumnos en los espacios virtuales<br />
                        - No pueden gestionar las mismas cosas que los profesores<br />
                        - Gestionan la rama de categorización de los cursos (organizan)<br />
                        - Puede generar actas de evaluación vía gestor de la comunidad de madrid (cam)<br />
                        - Puede modificar las notas<br />
                        - Traslada manualmente las notas de unas plataformas a otras<br />
                        - Utilizan varias plataformas (las dos aulas y el gestor de la cam)<br />
                        <br />
                        <div class="h4">Especialistas:</div>
                        <br />
                        - Sistema manual de gestión de talleres vía mail o google docs<br />
                        - Gestión manual de peticiones de taller, alaborando ellos mismos las listas<br />
                        - Si hay algún problema se comunican con los alumnos vía mail<br />
                        - El alumno cancela la reserva del taller vía mail. Importante la antelación en la notificación, no
                        el mismo día que tenían reservados, para poder avisar a alumnos en lista de espera si los hay, tb
                        vía mail<br />
                    </Article>
                </div>
                <div class="sec mt-8 Diagramación">
                    <div class="h3">
                        Diagramación
                    </div>
                    <Article class="borde article_scrollable" tit="Diagramación" :img="['web/diagramacion.jpg']"> Luis
                        Basándonos en estas conclusiones, decidimos reorganizar las funcionalidades de la web y la intranet.
                        Concluimos que muchas gestiones se realizaban a través de distintos canales, como el presencial, a
                        través de mail
                        a través de la web o de la intranet. En algunos casos, inlcuso, se necesitaban combinar hasta 3 de
                        estos canales
                        para llevar acabo una gestión. Decidimos que lo lógico era que todas las gestiones se realizasen a
                        través de la misma plataforma:
                        la intranet. mientras, la web sería un sitio exclusivamente publicitario, y albergaría algunos
                        formularios para que los alumnos nuevos,
                        los cuales no tienen acceso a la intranet, puedan matricularse en la escuela.
                        <br />
                        Para llevar acabo esta tarea se reorganizaron por completo ambos sitemaps, creando así una
                        arquitectura de la información mucho más
                        coherente y funcional. Para visualizar los sitemap en profundidad se adjuntan los siguientes links:
                        <br />
                        link
                        <br />
                        link
                        <br />

                    </Article>
                </div>
                <div class="sec mt-8 Propuesta">
                    <div class="h3">
                        Propuesta final
                    </div>
                    <Article class="borde article_scrollable" tit="Links propuestas finales"
                        :img="['web/figma_logo.jpg', 'web/netlify_logo.png']"> Luis
                        Decidimos que debido a lo distinto de la naturaleza de cada sitio web sería coherente utilizar
                        un sistema de diseño para cada una. La intranet debía ser limpia y priorizar la usabilidad al
                        máximo, ya que
                        se asemeja más a un software que a otra cosa. La web debía llamar la atención al usuario visitante.
                        Tras
                        numerosas propuestas y varios prototipados se llegó a un diseño final y definitivo para cada una de
                        ellas.
                        Se adjuntan los links de los documentos de Figma y Netlify para poder observar con detenimiento
                        tanto el prototipado como la web en sí. También puede visualizarse a través de los vídeos
                        adyacentes.
                        <br />
                        <br />
                        <a href="https://spectacular-cocada-64d204.netlify.app/">Intranet</a>
                        <br />
                        <br />
                        <a href="https://master--joyful-lebkuchen-e6526d.netlify.app/">Web ESD</a>
                        <br />
                        <br />
                        <a href="https://www.figma.com/file/P3yaH9FNtjDGS298v85He9/WEB-ESD?type=design&node-id=14%3A600&t=CAoKqqVULNgoGCS9-1">Figma</a>
                        
                    </Article>

                    <Article class="borde article_scrollable" tit="Userflow WEB" :img="[]" :video="['WEB/webvideo.mp4']">
                        En este vídeo, un usuario ajeno a la Escuela Superior de Diseño navega por la web para informarse
                        sobre la Escuela
                        y en concreto sobre el grado de diseño gráfico.
                    </Article>

                    <Article class="borde article_scrollable" tit="Userflow alumno Intranet" :img="[]"
                        :video="['Intranet/alumno.mp4']">

                        En este vídeo puede verse como un usuario de tipo ALUMNO, navega a través de la intranet
                        para matricularse en una asignatura y para confirmar asistencia a un taller abierto </Article>

                    <Article class="borde article_scrollable" tit="Userflow técnico Intranet" :img="[]"
                        :video="['Intranet/tecnico.mp4']">
                        Aquí podemos ver como un usuario de tipo TÉCNICO expulsa a un alumno de un taller en el cual había
                        solicitado asistencia </Article>

                    <Article class="article_scrollable" tit="Userflow docente Intranet" :img="[]"
                        :video="['Intranet/docente.mp4']">
                        Por último, en este vídeo se muestra a un usuario de tipo DOCENTE que accede a las entregas de un
                        alumno para calificarla y/o adjuntar un comentario </Article>
                </div>
                <div class="sec mt-8 Web">
                    <div class="h3">
                        Web ESD: Sistema de diseño
                    </div>
                    <Article class="borde article_scrollable" tit="Paleta tipográfica y de espaciados"
                        :img="['web/tipografia_1.jpg', 'web/tipografia_2.jpg', 'espaciados.jpg']"> Se seleccionó la tipografía Poppins para
                        utilizarla en la web por su aspecto amable y su buena legibilidad.
                    </Article>

                    <Article class="borde article_scrollable" tit="Colores" :img="['web/colores.jpg']">
                        Se ha utilizado esta reducida paleta de color para aportar un aspecto serio pero
                        llamativo
                    </Article>

                    <Article class="borde article_scrollable" tit="Radius y Shadow"
                        :img="['web/border_radius.jpg', 'web/shadow.jpg']"> Los bordes redondeados
                        se utilizan exclusivamente para los botones, en valor de 8px. La propiedad shadow se utiliza en las
                        cards y en botones,
                        de dos maneras: una para el estado default, y otra para el estado hover.
                        <br /> en las cards solo se utilizan si estas contienen un fondo del mismo color que el color de
                        fondo
                    </Article>

                    <Article class="borde article_scrollable" tit="Navegación: Componentes" :img="['web/navegacion.jpg']">
                        En la navegación se usan un formulario de búsqueda y una sidebar, además de header y footer, en los
                        que se profundiza más adelante </Article>

                    <Article class="borde article_scrollable" tit="Acciones: Componentes" :img="['web/buttons.jpg']"> Las
                        acciones se realizan a través
                        de componentes tipo botón y tipo link </Article>

                    <Article class="borde article_scrollable" tit="Header y footer: Componentes"
                        :img="['web/Header.jpg', 'web/footer.jpg']"> El header consiste en una barra horizontal fijada en la
                        parte Superior
                        de la web independientemente de en que página se encuentre el usuario </Article>

                    <Article class="borde article_scrollable" tit="Banners: Componentes"
                        :img="['web/banner_home.jpg', 'web/banner_nonhome.jpg']"> Se diseñaron dos banners dinámicos en los
                        que
                        la imagen de fondo cambia. El primero se utiliza exclusivamente en el home y el segundo en el resto
                        de páginas.
                        El primero contiene, además del fondo dinámico y el título, un formulario de búsqueda que sirve de
                        navegación en la página
                    </Article>

                    <Article class=" article_scrollable" tit="Estructura: Componentes"
                        :img="['web/estructura_1.jpg', 'web/estructura_2.jpg', 'web/estructura_3.jpg', 'web/estructura_4.jpg', 'web/estructura_5.jpg',]">
                        En esta sección se recogen el resto de componentes fabricados a partir de los mencionados
                        anteriormente</Article>
                </div>
                <div class="sec mt-8 Intranet">
                    <div class="h3">
                        Intranet ESD: Sistema de diseño
                    </div>
                    <Article class="borde article_scrollable" tit="Paleta tipográfica y de espaciados"
                        :img="['Intranet/tipografia_jerarquias.jpg', 'Intranet/espaciados.jpg']">
                        Se seleccionó la tipografía Poppins para utilizarla en la web por su aspecto amable y su buena
                        legibilidad.
                    </Article>

                    <Article class="borde article_scrollable" tit="Colores" :img="['Intranet/Colores_paleta.jpg']">
                        Se ha utilizado esta reducida paleta de color para aportar un aspecto serio y de fácil navegación.
                        En
                        el caso de esta web, era fundamental este último aspecto, ya que el usuario podría pasar mucho
                        tiempo gestionando
                        distintos temas. Debido a esto es importante que se asemeje a la estética de un software, y por
                        tanto que la paleta sea escueta y descriptiva
                    </Article>

                    <Article class="borde article_scrollable" tit="Radius y Shadow"
                        :img="['Intranet/radius.jpg', 'Intranet/shadow.jpg']">
                        El borde redondeado se utiliza en todos los paneles y componentes en esta web. en concreto se
                        utilizan 8px para casi todos los
                        elementos, exceptuando los más pequeños, contenidos en la sidebar derecha, que tienen un
                        border-radius de 4px.
                        Las sombras se utilizan de forma que los paneles que quedan sobre el main la tienen, y además cuando
                        se hace hover sobre estos, la sombra se acentua</Article>

                    <Article class="borde article_scrollable" tit="Acciones y badges: Componentes"
                        :img="['Intranet/botones.jpg', 'Intranet/badges.jpg',]">
                        Se han planteado una serie de botones con tres jerarquías de importancia, además de unos badges o
                        tags para
                        resaltar información concreta
                    </Article>

                    <Article class="borde article_scrollable" tit="Avatares: Componentes" :img="['Intranet/avatar.jpg',]">
                        Estos avatares se utilizan en los formularios, el perfil del usuario y la sidebar izquierda
                    </Article>

                    <Article class="borde article_scrollable" tit="Calendarios y horarios: Componentes"
                        :img="['Intranet/calendario_1.jpg', 'Intranet/calendario_2.jpg',]"> Luis
                        Debido a que en esta web se gestionan los horarios y calendarios de los distintos usuarios hay un
                        total de
                        3 componentes con uso especificado para distintos casos: el calendario pequeño muestra eventos y
                        entregas a través de un código de color intuitivo
                        el horario semanal mediano se utiliza como panel en la vista de perfil de los usuarios. En él los
                        usuarios pueden ver que eventos tienen programados
                        para cada día ya acceder a una vista detalle más intuitivamente. Por último el calendario grande lo
                        usan exclusivamente los técnicos de taller para comprobar
                        la asistencia que habrá cada uno de los días a su/s taller/es
                    </Article>

                    <Article class="borde article_scrollable" tit="Cards: Componentes"
                        :img="['Intranet/cards_1.jpg', 'Intranet/Cards_2.jpg', 'Intranet/Cards_3.jpg',]"> Se han diseñado
                        tres tipos distintos de cards con
                        funcionalidades distintas: la pequeña muestra gestiones, la cuadrada se utiliza para los talleres
                        abiertos, mientras que la card alargada
                        sirve para visualizar asignaturas, alumnos etc. Cualquier vista listada se vale de la card alargada
                        para construirse
                    </Article>

                    <Article class="borde article_scrollable" tit="Forms y notificaciones: Componentes"
                        :img="['Intranet/Formulario.jpg', 'Intranet/notificaciones.jpg',]"> Existen cuatro tipos de
                        formularios:
                        los 'default' diseñados para introducir una pequeña cantidad de texto, los 'tocho' para grandes
                        textos, los 'dropdown',
                        que se utilizan para seleccionar una de distintas opciones y los 'upload', utilizados para subir
                        documentos.
                        Dentro de las notificaciones existen dos tipos: grande y pequeña
                    </Article>

                    <Article class=" article_scrollable" tit="Navegación: Componentes" :img="['Intranet/Sidebars.jpg',]">
                        La navegación en una web de este tipo debe ser clara y sencilla. Se realiza a través de las
                        disntintas cards que puedan aparecer
                        y a través de la sidebar izquierda</Article>
                </div>
            </div>
        </div>
    </div>
</template>


<script setup>
const array = [
    'Investigación',
    'Diagramación',
    'Propuesta final',
    'Web ESD: Sistema de diseño',
    'Intranet ESD: Sistema de diseño',
]
const subArray = [
    [
        'Investigación',
    ],
    [
        'Diagramación',
    ],
    [
        'Links propuestas finales',
        'Userflow WEB',
        'Userflow Alumno Intranet',
        'Userflow Técnico Intranet',
        'Userflow Docente Intranet',
    ],
    [
        'Paleta tipográfica y de espaciados',
        'Colores',
        'Radius y Shadow',
        'Navegación: Componentes',
        'Acciones: Componentes',
        'Header y footer: Componentes',
        'Estructura: Componentes',
    ],
    [
        'Paleta tipográfica y de espaciados',
        'Colores',
        'Radius y Shadow',
        'Acciones y badges: Componentes',
        'Avatares: Componentes',
        'Calendarios y horarios: Componentes',
        'Cards: Componentes',
        'Forms y notificaciones: Componentes',
        'Navegación: Componentes',
    ],
]
</script>


<style lang="sass" scoped>
    .sec
        @apply flex flex-col w-full gap-12 p-8 bg-gray1 rounded-xl ml-8
    .borde
        @apply border-b border-gray2
    a
        @apply text-blue-600 underline
</style>