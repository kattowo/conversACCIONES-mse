<template>
<section>
    <div class="preguntas">
           <h2>Respondete</h2>
            <div>
                <h3>¿NECESITAS ORGANIZAR IDEAS? ¿CONVERSAR CON ALGUIEN COSAS QUE SIENTES QUE NO PUEDES HABLAR CON NADIE MÁS?</h3>
            </div>
            <div>
                <h3>¿SABES QUE QUIERES CAMBIAR ALGO, PERO AÚN NO SABES QUÉ? Y ADEMÁS NO QUIERES SENTIRTE JUZGADA POR ESO?</h3>
            </div>
            <div>
                <h3>¿QUIZÁS YA SABES QUÉ QUIERES CAMBIAR, PERO NO TIENES CLARO CÓMO HACERLO? </h3>
            </div>
            <div>
                <h3>¿TIENES VARIOS PROYECTOS, PERO NO AVANZAS? ¿Y TE GUSTARÍA ORGANIZARTE?</h3>
            </div>
            <div>
                <h3>¿TE ESTAS CUESTIONANDO ALGUNAS IDEAS PORQUE SIENTES QUE NO ESTÁN RESONANDO CON LO QUE ESTÁS VIVIENDO HOY DÍA? ¿Y TE GUSTARÍA PODER ENCONTRAR OTRA MIRADA A ESAS CREENCIAS? </h3>
            </div>
            <div>
                <h3>TIENES MUCHOS CONOCIMIENTOS Y HERRAMIENTAS PERO AÚN ASÍ ¿SIENTES QUE EN TU VIDA, SE REPITEN UNA Y OTRA VEZ LAS MISMAS SITUACIONES INCÓMODAS CON TU FAMILIA, CON TU PAREJA O EN TU TRABAJO?</h3>
            </div>
    </div>
</section>
</template>

<style scoped>
section{
    width: 100vw;
    height: auto;
    background-color: rgb(245, 229, 245);
    
}
.preguntas{
    color: var(--main-color);
    max-width: 1200px;
    margin: auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    justify-content: center;
    align-items: center;  
    padding: 3rem 0;
}
.preguntas h2{
     font-family: 'Jost', sans-serif;
    grid-column: 1/-1;
    text-transform: uppercase;
    
}

.preguntas h3{  
    font-family: 'Jost', sans-serif;  
    padding: 2rem;
    text-align: left;
    text-transform: uppercase;
  
}

@media screen and (max-width: 850px) {
    .preguntas{
        grid-template-columns: 1fr;
    }
}
</style>