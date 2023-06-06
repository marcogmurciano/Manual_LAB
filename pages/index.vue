<template>
    <title>Manual de Marca Yelmo</title>
    <div class="app bg-whito">
        <Banner title="Rediseño identidad de Cines Yelmo" banner="mupis.jpg">
            <NuxtLink to="/ManualWeb">
                <Botona>Ver Manual Web</Botona>
            </NuxtLink>
        </Banner>
        <div class="body flex m-auto max-w-[1280px] items-start">
            <Sidebar class="w-25% pt-2 sticky h-auto top-8 w-" :array="array" :subArray="subArray" />
            <div class="flex flex-col gap-24 w-full">
                <div class="sec mt-8 Concepto">
                    <div class="h3">
                        Concepto de marca
                    </div>
                    <Article class="borde article_scrollable" tit="Personalidad de Marca" :img="['mago.jpg']">
                        Se seleccionó el arquetipo del mago. Transforma el mundo, imaginativo y vivaz. Su objetivo es que
                        las cosas se hagan realidad, intentado ser el líder carismático con capacidad de desarrollar una
                        visión y vivir por ella, marcas cuya promesa implícita es transformar a los clientes (Axe, Absolut
                        Vodka)
                    </Article>
                    <Article class="borde article_scrollable" tit="Quienes somos: Mision, Visión y claim"
                        :img="['Logo_logo_logo.png']">
                        <div class="h4">Misión:</div>
                        En Cine Yelmo, nuestra misión es brindar a nuestros espectadores una experiencia única de
                        entretenimiento cinematográfico. Nos esforzamos por ser la opción preferida del público, ofreciendo
                        una selección diversa de películas de calidad, combinada con un servicio excepcional y comodidades
                        modernas en nuestras salas de cine. Buscamos crear momentos inolvidables y compartir la magia del
                        cine con cada uno de nuestros visitantes.
                        <br>
                        <div class="h4">Visión:</div>
                        Nuestra visión es convertirnos en el referente indiscutible del entretenimiento cinematográfico,
                        destacando por nuestra imagen visual fresca, joven y divertida. Nos esforzamos por ser líderes en
                        innovación, brindando a nuestros clientes una experiencia única y memorable en cada visita.
                        Aspiramos a ser reconocidos como un destino de entretenimiento de primera categoría, ofreciendo una
                        amplia gama de películas y eventos especiales que satisfacen los gustos y preferencias de todos los
                        espectadores.
                        <br>
                        <div class="h4">Claim: </div>
                        "Vive el cine en su máxima expresión: Cine Yelmo, donde cada película se convierte en una
                        experiencia inolvidable"
                        <br>
                        En Cine Yelmo, nos enorgullece ser la elección de aquellos que buscan disfrutar del séptimo
                        arte de
                        manera fresca, joven y divertida. Nuestro claim refleja la invitación a sumergirse en la magia del
                        cine y vivir una experiencia cinematográfica inigualable. Con nuestra atención al detalle, nuestro
                        compromiso con la calidad y una amplia variedad de películas, queremos que nuestros espectadores se
                        sumerjan en un mundo de emociones y diversión cada vez que visiten Cine Yelmo.
                    </Article>
                    <Article class="borde article_scrollable" tit="Personalidad y Atributos" :img="['esquema_valores.jpg']">
                        Aquí se recoge una lista con la personalidad de la marca:
                        <br />Pasión
                        <br />Palomitas
                        <br />cosas que explotan al interactuar con ellas
                        <br />Dinámico
                        <br />Explosión
                        <br />Los cubos de palomitas tienen rayas
                        <br />Animaciones
                        <br />Gráfica procedural (Processing)
                        <br />Butacas
                        <br />Ambiente
                        <br />Innovación
                        <br />Tecnología
                        <br />Cultura
                        <br />Oscuridad

                    </Article>
                    <Article class="article_scrollable" tit="Concepto, valores y Atributos" :img="['valores.png']">
                        Los valores extraidos de estos atributos son:
                        <br />Pasión
                        <br />Dinámico
                        <br />Emoción
                        <br />Interacción
                        <br />Innovación
                    </Article>
                </div>
                <div class="sec mt-8 Logo">
                    <div class="h3">
                        Logo
                    </div>
                    <Article class="borde article_scrollable" tit="Isotipo"
                        :img="['logo_isotipo.png', 'logo_isotipo_mono_1.png', 'logo_isotipo_mono_2.png',]">
                        Construido a partir de una retícula de 8x8. <br>

                        Con el cuadrado apuntando en diagonal, el tamaño mínimo del isotipo es de 32px de ancho en pantalla,
                        y de 50mm en impresión.
                        A través de este isotipo, la marca es dotada de dinamismo, ya que puede colocarse orientado o
                        coloreado de
                        cualquiera de las formas recogidas en este manual
                    </Article>
                    <Article class="borde article_scrollable" tit="Logotipo"
                        :img="['logo_logotipo.png', 'logotipo_submarca.png', 'logotipo_submarcas_2.png', 'submarca_alternativa.jpg']">
                        El logotipo consiste en el nombre de la marca en una tipografía geométrica (TT Commons Bold) que
                        siga las mismas
                        líneas y estética que el logo. La marca principal se escribirá en caja baja y un peso bold.
                        Respecto a las submarcas, se admiten las dos versiones adyacentes, estando la primera combinada con
                        el isotipo
                    </Article>
                    <Article class="borde article_scrollable" tit="Isologo" :img="['isologo_col.png', 'isologo_row.png',]">
                        Nace de la combinación del isotipo y el
                        logotipo en las proporciones especificadas en la imagen adyacente.
                    </Article>
                    <Article class=" article_scrollable" tit="Avatares" :img="['logo_avatares.png']">
                        Estos avatares están construidos utilizando la versión monocroma del isotipo.
                    </Article>
                </div>
                <div class="sec mt-8 Color">
                    <div class="h3">
                        Color
                    </div>
                    <Article class="borde article_scrollable" tit="Paleta primaria" :img="['color_principal.png']">
                        La paleta primaria, es decir, los colores utilizados más frecuentemente, serán este negro y este
                        blanco</Article>
                    <Article class="borde article_scrollable" tit="Paleta secundaria" :img="['color_secundario.png']">
                        Los colores secundarios se utilizan exclusivamente para las submarcas.
                    </Article>
                    <Article class="borde article_scrollable" tit="Degradados" :img="['color_degradados.png']">Queda
                        confirmado
                        Los degradados, construidos a partir de los colores secundarios, se utilizan en aplicaciones como
                        carteles, entradas, etcétera, junto con los colores primarios
                    </Article>
                    <Article class="article_scrollable" tit="Paleta extendida: colores de apoyo"
                        :img="['color_apoyo_azul.png', 'color_apoyo_amarillo.png', 'color_apoyo_lila.png', 'color_apoyo_verde.png', 'color_apoyo_cian.png', 'color_apoyo_rojo.png',]">

                    </Article>
                </div>
                <div class="sec mt-8 Tipografía">
                    <div class="h3">
                        Tipografía
                    </div>
                    <Article class="borde article_scrollable" tit="Familia tipográfica" :img="['tipografia_ttcommons.png']">
                        Luis
                        TT Commons es una familia tipográfica con una gran versatilidad al ser una tipografía variable en
                        grosor, anchura e inclinación. Además, ofrece una gran cantidad de glifos y tiene versión outline.

                    </Article>
                    <Article class="borde article_scrollable" tit="Especimen de uso" :img="['tipografia_muestrario.png']">
                        Esta tipografía grotesca y geométrica se complementa con el diseño del Isotipo, también compuesto
                        por formas geométricas básicas o secciones de estas.
                    </Article>
                    <Article class="borde article_scrollable" tit="Jerarquías relacionales"
                        :img="['tipografia_jerarquias_1.png', 'tipografia_jerarquias_2.png',]">
                        Las jerarquías tipográficas y las proporciones entre ellas siguen las proporciones de la retícula
                        del isotipo.
                        Las jerarquías que se muestran a continuación tienen distintos tamaños, pero guardan las mismas
                        proporciones entre sí y van en función de la retícula del isotipo (imagen de arriba).
                    </Article>
                    <Article class="article_scrollable" tit="Uso en el logo y aplicaciones"
                        :img="['tipografia_jerarquias_3.png', 'tipografia_jerarquias_4.png',]">
                        Cuando aparecen los logotipos de la marca y la submarca, la altura de la x de la marca será el doble
                        que la de la submarca.
                        <br>
                        Además aquí quedan definidas las reglas que deben seguirse para utilizar la tipografía en
                        aplicaciones.
                        está definido de manera proporcional, de forma que pueden variar los tamaños dependiendo del formato
                        de la aplicación, pero nunca deben variar las proporciones.
                    </Article>
                </div>
                <div class="sec mt-8 Otros">
                    <div class="h3">
                        Otros elementos del sistema
                    </div>
                    <Article class="borde article_scrollable" tit="Módulo" :img="['modulo_modulo.png']">
                        El módulo o cuarto de circunferencia es un elemento fundamental en esta identidad. Esta se apoya
                        mucho en el módulo para generar aplicaciones y otros elementos del sistema. Como se ve en la imagen,
                        el módulo puede enordar y adelgazar. no se permiten otros usos del módulo que no estén recogidos en
                        este manual
                    </Article>
                    <Article class="borde article_scrollable" tit="Íconos"
                        :img="['picto_caras.png', 'picto_comida.png', 'picto_flechas.png', 'picto_butacas.png',]">
                        Se han generado unos iconos basados en el cuarto de circunferencia. deben utilizarse siempre
                        vectorizados. En orden pueden verse los iconos
                        para el Yelmo Pass, los consumibles, la señalética y los de butaca
                    </Article>
                    <Article class="borde article_scrollable" tit="Tratamiento de la imagen"
                        :img="['tratamiento_good_1.png', 'tratamiento_good_2.png', 'tratamiento_bad.png',]">
                        El tratamiento de imágenes en cine yelmo es muy particular, se basa en el uso del módulo (cuarto de
                        circunferencia)
                        Se admiten dos usos reflejados en la primera y segunda imagen. Respectivamente son 'modulo como
                        contenedor' y 'modulo aplicado' posteriormente se recogen algunos usos incorrectos para claficar el
                        correcto tratamiento de la imagen
                    </Article>
                    <Article class="borde article_scrollable" tit="Patrones"
                        :img="['patrones_1.png', 'patrones_2.png', 'patrones_premium.png', 'patrones_macro.png',]">

                        Los primeros son los llamados 'simples' Basados en la repetición del arco el módulo. Únicamente
                        utilizados en retículas de 4x4. <br>
                        Después aparecen los de 'marca principal'. En estos se utiliza el arco del módulo con distintos
                        juegos de forma y contraforma, generando patrones estáticos. <br>
                        También existe un sistema de patrones referente a las submarcas, basado en la animación del módulo
                        que se utiliza para las microanimaciones y los idents audiovisuales.

                    </Article>
                    <Article class="article_scrollable" tit="Layout"
                        :img="['layout_1x1.png', 'layout_1x2.png', 'layout_2x1.png',]">
                        Aquí se muestran retícula y jerarquías de texto. Cuando sólo aparezca texto, se mostrará en H1,
                        centrado en la pantalla y en caja alta. En orden:
                        <br>-Formato cuadrado
                        <br>-Formato horizontal (1920x1080px)
                        <br>-Formato vertical para stories
                    </Article>
                </div>
                <div class="sec mt-8 Identidad">
                    <div class="h3">
                        Identidad audiovisual
                    </div>
                    <Article class="borde article_scrollable" tit="Tipografía en pantalla"
                        :img="['tipantalla_1.png', 'tipantalla_2.png',]">
                        En una pantalla de 1920x1080, se utilizan los siguientes tamaños tipográficos, manteniendo las
                        proporciones entre unos niveles y otros y respetando las jerarquías y uso establecidos para la
                        identidad de la marca.
                    </Article>
                    <Article class="article_scrollable" tit="Movimiento" :img="[]"
                        :video="['Junior.mp4', '+qcine_2.mp4', 'e-motion5d.mp4', 'Macroxe_2.mp4', 'Luxury.mp4', 'Premium.mp4']">
                        Los logos están
                        animados de esta manera
                    </Article>

                    <Article class="article_scrollable" tit="Idents y explosiones" :img="[]" :video="['idents_1.mp4', 'idents_2.mp4']">
                        Estos idents son los que presentan las submarcas, están basados en el Módulo.
                        cada par de submarcas tiene un tipo de movimiento asignado:<br />
                        <br />  Junior y Más que Cine tienen asignado la generación aleatorio de módulos<br />
                        <br />  Macro XE y e-motion4D tienen asignado el movimiento concéntrico circular<br />
                        <br />  Premium y luxury se muestran con movimiento lineal.<br />
                        <br />También se ven aplicados a una imagen promocional de una película en el segundo video
                    </Article>
                    
                </div>

            </div>
        </div>
    </div>
</template>

<!--MODELO SEC 
    
<div class="sec">
    <div class="h3">
        Identidad
    </div>
    <Article class="borde article_scrollable" tit="" :img=""></Article>
    <Article class="borde article_scrollable" tit="" :img=""></Article>
    <Article tit="" :img=""></Article>
</div> -->


<script setup>

const array = [
    'Concepto de marca',
    'Logo',
    'Color',
    'Tipografía',
    'Otros elementos del sistema',
    'Identidad audiovisual',
]
const subArray = [
    [
        'Personalidad de Marca',
        'Quienes somos: Mision, Visión y claim',
        'Personalidad y Atributos',
        'Concepto, valores y Atributos',
    ],
    [
        'Isotipo',
        'Logotipo',
        'Isologo',
        'Retículas y áreas de respeto',
        'Avatares',
    ],
    [
        'Paleta primaria',
        'Paleta secundaria',
        'Degradados',
        'Paleta extendida: colores de apoyo',
    ],
    [
        'Familia tipográfica',
        'Especimen de uso',
        'Jerarquías relacionales',
        'Fuente de sustitución',
    ],
    [
        'Módulo',
        'Íconos',
        'Tratamiento de la imagen',
        'Patrones',
        'Layout',

    ],
    [
        'Tipografía en pantalla',
        'Movimiento',
        'Idents y explosiones',
        'Cortinillas, Cartelas y explosiones',

    ],
]


</script>

<style lang="sass" scoped>
   
    .sec
        @apply flex flex-col w-full gap-12 p-8 bg-gray1 rounded-xl ml-8
    .borde
        @apply border-b border-gray2

</style>




