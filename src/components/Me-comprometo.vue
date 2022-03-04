<template>
        <section>
            <div class="contenido">
                <div class="imagen-respuesta">

                </div>
                <div class="info-respuesta">

                    <h2>¿A QUÉ ME COMPROMETO?</h2>
                    <p>
                        Voy a establecer, y mantener en el tiempo, una relación de confianza y seguridad.
                    </p>
                    <p>
                        Te sentirás en total comodidad si así me lo permites.
                    </p>
                    <p>
                        Voy a ayudarte a clarificar tu situación actual y tus creencias.
                    </p>
                    <p>
                        Te ayudaré a mantener y establecer tus propósitos claros.
                    </p>
                </div>
            </div>
        </section>   
</template>

<style scoped>
section{
    width: 100vw;
    height:auto;
    background-color: antiquewhite;
    margin: auto;
    overflow: hidden;
}
.contenido{
    font-family: 'Jost', sans-serif;
    max-width: 1200px;
    margin: auto;
    display: grid;
    grid-template-columns: 1fr 1fr;
    justify-content: center;
    align-items: center;
    overflow: hidden;
  
}
.imagen-respuesta{   
 	width: 100%;
	height: 46rem;
	background-image: url(/src/assets/comprometo.jpg);
	filter: brightness(1.35);
	background-size: cover;
	background-repeat: no-repeat;
	background-position-x: 35%;
 
}
.info-respuesta{
    text-align: left;
    margin-left: 1rem;

}
.info-respuesta h2{
    font-weight: 800;
    color: var(--main-color);
    padding: 0.8rem;
    margin-top: 2rem;
}
.info-respuesta p{
    padding: .8rem;
}
.lista{
    display: flex;
    flex-direction: row;   
    justify-content: left;
    align-items: center;
    margin-left: 1rem;    
    gap: .5rem;
}


@media screen and (max-width: 850px) {
    .contenido{
        grid-template-columns: 1fr;
        margin-bottom:3rem ;
    }
    .imagen-respuesta{  
        width: 100%;
                    
        background-size: cover;
        background-position-x:0px ;
        background-position-y: -5.5rem;      
        margin: auto;      
    }
}



</style>