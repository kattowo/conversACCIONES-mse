<template>
    <section>
        <div class="contenido">    
            <div class="info-respuesta"> 
                        <h2>¿QUÉ PASARÍA SI DECIDES COMENZAR UN CAMINO, Y ME PERMITES ACOMPAÑARTE?</h2>                     
                        <div class="lista">
                                <img src="../assets/correcto.png" width="30px" height="30px"  alt="">
                                <p>
                                    Pasarás de tu versión actual, a una versión más consciente. Eso sí,
                                    no es magia, es aprender a desaprender, y aprender de nuevo.
                                </p>
                        </div>

                        <div class="lista">
                                    <img src="../assets/correcto.png" width="30px" height="30px"  alt="">
                                  
                                <p>
                                    Como tendrás más amplitud en tus creencias y miradas, te vas a
                                    responsabilizar más de ti sin presiones externas.
                                </p>
                        </div>
                                 <div class="lista">
                                    <img src="../assets/correcto.png" width="30px" height="30px"  alt="">                                  
                                <p>
                                    Vas a lograr construir planes y acciones que vayan con tu realidad.
                                </p>
                        </div>
                        <div class="lista">
                                     <img src="../assets/correcto.png" width="30px" height="30px"  alt="">
                                  
                                <p>
                                    Podrás organizar tu agenda, lo haremos ¡juntas!
                                </p>
                        </div>
                        <div class="lista">
                                     <img src="../assets/correcto.png" width="30px" height="30px"  alt="">
                                  
                                <p>
                                    Vas a descubrir tus prioridades, te voy a acompañar para que esto
                                    sea con honestidad.
                                </p>
                        </div>
                        <div class="lista">
                                      <img src="../assets/correcto.png" width="30px" height="30px"  alt="">
                                  
                                <p>
                                    Tendrás nuevas herramientas y recursos, para afrontar esas
                                    situaciones cuando a veces la vida nos sorprende.
                                </p>
                        </div>
                    </div> 

                <div class="imagen-respuesta ">
                    <div class="gradiente">
                        
                    </div>       
                   
                </div>
      </div>
    </section>
</template>

<style scoped>
section{
    width: 100%;
    height:auto;
    background-color: var(--main-color);
    margin: auto;
    overflow: hidden;
}
.contenido{
    font-family: 'Jost', sans-serif;
    max-width: 1200px;
    height: auto;
    margin: auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    justify-content: center;
    align-items: center;
    overflow: hidden;
}
.info-respuesta h2{
    font-weight: 800;
    color: var(--main-color2);
    padding: 0.8rem;
    margin-top: 2rem;
    text-align: left;
}
.info-respuesta p{
    color: var(--main-color2);
    text-align: left;
}
.lista{
    display: flex;   
    justify-content: left;
    align-items: center;
    padding: 1rem 2rem;
    gap: .5rem;
}
.imagen-respuesta{   
 	width: 100%;
	height: 46rem;
	background-size: cover;
	background-image: url(/src/assets/resp2.jpg);
    background-position-x: -12rem;    
}
.gradiente{
    z-index: 5;
    width: 100%;
    height: 100%;

    background: rgb(197,0,80);
    background: -moz-linear-gradient(90deg, rgba(197,0,80,1) 5%, rgba(197,0,80,0) 40%);
    background: -webkit-linear-gradient(90deg, rgba(197,0,80,1) 5%, rgba(197,0,80,0) 40%);
    background: linear-gradient(90deg, rgba(197,0,80,1) 5%, rgba(197,0,80,0) 40%);
    filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#c50050",endColorstr="#c50050",GradientType=1); 
}




















@media screen and (max-width: 850px) {
    .contenido{
        display: flex;
        flex-direction: column-reverse;
    
    }
    .imagen-respuesta{  
        width: 100%;
        height: 500px;             
        background-size: cover;
        background-position-x:0px ;
        background-color: blueviolet; 
        margin: auto;      
    }
}
</style>