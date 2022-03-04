<template>
        <section>
            <div class="contenido">
                <div class="info-respuesta">
                    
                    <h2>¿A QUÉ TE COMPROMETES TÚ?</h2>
                    <p>
                        Ser honesta, es súper importante para que realmente puedas vivir y
                        experimentar cada una de las sesiones.
                    </p>
                    <p>
                        Abrirte a la experiencia en cada encuentro. Tu escucha también es
                        importante en este proceso.
                    </p>
                    <p>
                        Es muy importante cumplir con los compromisos adquiridos, las fechas
                        pautadas, las horas. Si se te presenta algún inconveniente debes avisar con
                        tiempo para yo utilizar ese tiempo y no perderlo, y viceversa.
                    </p>
                    <div class="resaltar">
                        <p>
                            Este es un proceso confidencial tanto para ti como para mí. Tanto tú como
                            yo, nos vamos a reservar nuestras conversas, opiniones y las herramientas
                            compartidas. 
                        </p>
                        <p>
                            Si algo no te está satisfaciendo te pido que con toda confianza me
                            indiques, para que podamos explorar nuevas estrategias que me
                            permitan canalizar lo que requieres.
                        </p>
                    </div>
                   
                </div>
                <div class="imagen-respuesta">
        
                </div>
        
                   
            </div>

    <div class="box">

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
  
  
}
.imagen-respuesta{   
 	width: 100%;
	height: 46rem;
	background-image: url(/src/assets/comp1.jpg);
	background-size: cover;
	background-repeat: no-repeat;
	background-position-x: 35%; 
}
.info-respuesta{
  
    text-align: left;
    margin-left: 1rem;
    padding: 0 1rem;
    justify-content: space-evenly;  

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
.resaltar{
    
    color: var(--main-color2);
    margin: 2rem 0 4rem 0;
    justify-content: space-around;     
}
.box{
    width: 100vw;
    height: 17rem;
    background-color: var(--main-color);
    margin-top: -20rem;
    margin-bottom: 0;
}

@media screen and (max-width: 850px) {
    .contenido{
       display: flex;
       flex-direction: column-reverse;
       margin-bottom:3rem;     
    
    }
    .imagen-respuesta{  
        width: 100%;                   
        background-size: cover;
        background-position-x:0px ;
        background-position-y: -1rem;      
        margin: auto;      
    }
    .info-respuesta{
        padding: 0 1rem;
        margin: 0rem;
    }
    .resaltar{
        margin-top: 3rem;
        width: 100vw;
    }
    .box{
        background-color: var(--main-color);
        width: 100vw;
        height: 20rem;
        margin-top: -20rem;
        margin-bottom: 0rem;
    }
}



</style>