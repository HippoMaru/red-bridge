<template>
    <v-row>
        <Header></Header>
    </v-row>    
    <v-row>
        <Top_nav></Top_nav>
    </v-row>
    <v-row>
        <v-col cols="9">
            <div id="technique-maincontent">
                <h2>Техника</h2>
                <p>Китай, отличающийся своей богатой историей и культурой, давно уже не является только центром производства недорогих товаров. Страна занимает лидирующую позицию во многих индустриальных секторах, и спецтехника из Китая – не исключение.
                    Современный рынок требует высококачественной и инновационной техники, и именно это предлагает Китай. Благодаря интенсивному инвестированию в исследования и разработки, китайские компании стали пионерами в производстве передовой спецтехники, предлагая широкий спектр продукции – от грузовиков и экскаваторов до кранов и специализированной складской техники.
                </p>
                <h3>Преимущества спецтехники из Китая</h3>
                <p>
                    Ответ на этот вопрос вполне очевиден: необходимо изначально, на этапе планирования производства, сделать грамотный выбор производственного оборудования, по возможности остановившись на полном комплексе взаимосвязанных агрегатов (станков) — автоматической технологической линии. Технологическая производственная линия позволяет в автоматическом режиме с наличием неширокого штата работников выпускать продукцию в едином, последовательном производственном цикле конвейерного типа, начиная от загрузки на линию исходного сырья и заканчивая получением на выходе готовой к реализации продукции с возможностью ее автоматической транспортировки до мест временного хранения (складских помещений). Сегодня можно точно сказать, что производственные линии китайского производства уверенно завоевывают спрос, как в нашей стране, так и во всем мире. На это есть несколько причин.
                </p>
                <h3>Почему стоит выбрать спецтехнику из Китая</h3>
                <p>
                    При выборе спецтехники из Китая стоит обратить внимание на сочетание качества, цены и инноваций, которые предлагают китайские производители. Благодаря своему опыту и технологическому прогрессу, спецтехника из Китая становится все более конкурентоспособной на мировом рынке.
                </p>
                <div class="hr"></div>
                <kvadratikiTehnika></kvadratikiTehnika>
            </div>
        </v-col>
        <v-col cols="3">
            <FeedbackForm></FeedbackForm>
        </v-col>
    </v-row>
    <v-row>
        <Footer></Footer>
    </v-row>
</template>

<script setup>
    import Header from "../components/Header.vue"
    import Top_nav from "../components/Top-nav.vue"
    import Footer from "../components/Footer.vue"
    import FeedbackForm from "../components/FeedbackForm.vue"
    import kvadratikiTehnika from "@/components/kvadratiki-tehnika.vue"
</script>

<style>
p{
    text-align: justify;
}

h3{
    margin: 30px 0 30px 0;
    font-size: 24px;
}

#technique-maincontent{
    float: right;
    color: black;
    margin-left: 100px;
    padding-right: 70px;
}

.hr{
    border: solid;
    border-width: 0 0 1px 0;
    margin-bottom: 23px;
    margin-top: 23px;
    border-color:  #d9d9d9;
    width: 100%;
    height: 5px;
}
</style>