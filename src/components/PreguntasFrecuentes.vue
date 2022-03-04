<template>
<section>
    <div class="contenido">
                 <h2>Preguntas Frecuentes</h2>
    
                <div class="izquierda">
                   <div v-on:click="ver1=!ver1" class="show" >                 
                        <h3 >¿Cuántas sesiones se requieren?</h3>
                         <p v-show="ver1">
                            Es una decisión muy personal. Si tienes un tema puntual, una sola sesión
                            te podrá servir.
                        </p>
                    </div>

                     <div v-on:click="ver2=!ver2" class="show" >
                        <h3>
                            ¿Cuántas recomiendas?
                        </h3>
                        <p v-show="ver2">
                            Dependiendo de los temas, 4 o 6. Una por semana u otra frecuencia
                            que acordemos. Luego puedes mantener una cada mes, o cuando así lo
                            requieras.
                        </p>
                    </div>
                   <div v-on:click="ver3=!ver3" class="show" >
                        <h3>
                            ¿A través de qué medio serán las sesiones?
                        </h3>
                         <p v-show="ver3">
                            Son online, vía Zoom, video llamada de WhatsApp, o lo que te sea más
                            cómodo.
                        </p>
                    </div>
                    <div v-on:click="ver4=!ver4" class="show" >
                        <h3>
                            ¿Cuánto dura una sesión?
                        </h3>
                         <p v-show="ver4">
                            Una sesión puede durar 40 minutos, hasta una hora y media. Según lo
                            que estemos trabajando y los acuerdos que pautemos.
                        </p>
                    </div>
                </div>
                <div class="derecha">
                    <div v-on:click="ver6=!ver6" class="show" >  
                        <h3>
                            ¿Esto es terapia?
                        </h3>
                          <p v-show="ver6">
                           No. Son sesiones de coaching a lo que yo he
                           llamado conversaciones con acciones “Convers<span>ACCIONES</span>” 
                           donde están integradas las herramientas del coaching 
                           y el PNL. El coaching pone el objetivo en el aprendizaje,
                            y el desarrollo de la persona, utilizando…. Todo lo demás
                            . Y el PNL trabaja con la comunicación, para posibilitar 
                            a las personas descubrir a través de herramientas, nuevas
                             opciones de decisión

                        </p>
                    </div>
                    <div v-on:click="ver8=!ver8" class="show" >
                        <h3>
                            ¿Estas Certificada como Coach?
                        </h3>
                        <p v-show="ver8">
                            Sí, tengo una certificación como COACH ICC en el International
                            Coaching Community, la cual tiene la validación del Quality Award en el
                            Consulado Europeo. De igual forma avalada también por el Centro
                            Internacional de Actualización Profesional de la Universidad Católica
                            Andrés Bello.
                            También certificada en Formación de PNL para Terapeutas y Coaches en
                            la escuela Crecer PNL de Chile.
                        </p>
                    </div>
                    <div v-on:click="ver7=!ver7" class="show" >
                        <h3>
                            ¿Si luego de haber pagado no pudiera seguir con las sesiones, por cualquier situación, habría devolución del dinero?
                        </h3>
                        <p v-show="ver7">
                            Si, notificas con una semana de anticipación se te devolverá el monto
                            total de las siguientes sesiones que no verás. O conversación previa
                            mantener las sesiones en tiempo de espera coordinado.
                        </p>
                    </div>
                     
                </div>   
                <div class="testimonios">
                    <h2>¿QUÉ DICEN ALGUNAS CLIENTAS?</h2>
                    <p>“Solo tengo palabras de agradecimiento y felicitaciones para ti Susana. Me he
                        permitido observar esas creencias que me tenían paralizada sin saber qué hacer. Eres
                        EXCELENTE! Y siempre tendré mis sesiones contigo” CL</p>
                    <p>“Las sesiones contigo con ¡liberadoras! Puedo decirte lo que pareciera más loco, y tú
                        haces que no sienta vergüenza!” AM</p>
                    <p>“Amo los encuentros contigo, ya no les llamo sesión. Siempre salgo con acciones
                        concretas a realizar” NR</p>
                    <p>“Termine muy clara de mis prioridades en este momento de mi vida, las preguntas
                        que se van generando me permitieron darme cuenta que es lo importante para mí en
                        este momento” MC</p>
                    <p>“Me encantan las sesiones contigo! Tus preguntas hacen que yo me mire con
                        sinceridad” MF</p>
                </div>
    </div>
</section>
</template>


<script>

export default {
 
  data() {
    return {     
     ver1:false,
     ver2:false,
     ver3:false,
     ver4:false,
     ver5:false,
     ver6:false,
     ver7:false,
     ver8:false,
    };
  },  
}


</script>
 
<style scoped>
.mostrar{
    display: none;
    padding: 3rem;
    margin-top: 50rem; 
    transition: ease-in-out 1s;   
}
.texto{
    display: block;
    padding: 0.1rem;
    margin-top: .50rem;
   
}
#text{
    display: block;
}
.show{
    cursor: pointer;
    transition: ease-in-out 0.3s;   
}
.show:hover{
    background-color: var(--main-color);
    border-radius: 20px;

}
section{
    width: 100%;  
    margin: auto;   
    background-color: var(--main-color);
    background-image: url(../assets/preguntasFrecuentes.jpg);
    background-blend-mode:multiply;    
    background-attachment: fixed;   
    background-image: contain;
    background-position: top;
}

.contenido{
    font-family: 'Jost', sans-serif;    
    max-width: 1200px;
    height: auto; 
    margin: auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 200px repeat(2, 1fr);
    gap: 2rem;    
    justify-content: center;
    align-items: start; 
    padding: 0 1rem;   
   
   
}
.contenido h2{
    color: var(--main-color2);
    text-transform: uppercase;
    grid-column: 1/-1;
    justify-content: center;
    align-items: center; 
    margin-top: 6rem; 
}

.izquierda{
    color: var(--main-color2);
    text-align: left;
}
.izquierda h3{
    background-color: #c5004f70;
    border-radius: 15px;
    border: 2px solid var(--main-color2);
    padding: .5rem;
    margin-bottom: 1rem;
    text-transform: uppercase;
}
.izquierda p{
    margin-bottom: 1rem;
    padding: 1rem;
    background-color: var(--main-color);
    border-radius: 20px;
}
.izquierda p span {
    text-decoration: underline 5px #fff;
    color: #fff;
}
.derecha{
    color: var(--main-color2);
    text-align: left;
}
.derecha h3 {
    background-color: #c5004f70;
    border-radius: 15px;
    border: 2px solid var(--main-color2);
    padding: .5rem;
    margin-bottom: 1rem;
    text-transform: uppercase;
}
.derecha p{
    margin-bottom: 1rem;
    padding: 1rem;
    background-color: var(--main-color);
    border-radius: 20px;
}
.derecha p span {
    text-decoration: underline 2px #fff;
    color: #fff;
    text-transform: uppercase;
}
.testimonios{
    color: var(--main-color2);
    width: 60%; 
    margin: auto;
    grid-column: 1/-1;  
    justify-content: center;
    align-items: center;  
    text-align: left;
    margin-top: -2%;
    
}
.testimonios h2{    
    margin: 2rem 0;
    text-align: center;
}
.testimonios p{
    margin-bottom: 2rem;
}

@media screen and (max-width: 850px) {   
section{
  
    background-blend-mode:multiply;    
    background-attachment: fixed;   
    background-image: contain;
    background-position-x:-20rem;
}
    .contenido{
        width: 90%;
        gap: 0;
        margin: auto;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .contenido h2{
        margin-bottom: 4rem;
    }
    .izquierda{
        width: 100%;
  }
  .izquierda h3{
      text-align: center;
  }
  .derecha h3 {
      text-align: center;
  }
  .testimonios{
      width:95%;
      margin-top: 2rem;
  }
}
</style>