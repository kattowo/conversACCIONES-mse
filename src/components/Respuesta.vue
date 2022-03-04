<template>
    <section>
        <div class="contenido">
    
        <div class="imagen-respuesta">
            <!-- <img src="../assets/susi4.jpg" alt=""> -->
        </div>
            <div class="info-respuesta"> 
                <h2>
                    SI RESPONDISTE UN SÍ A ALGUNA DE ESTAS PREGUNTAS, ENTONCES TE SERÁ ÚTIL UNA SESIÓN DE convers<span>acciones</span>
                    CONMIGO!
                </h2>   
           
              <div class="lista">
                  <img src="../assets/correcto-red.png" width="30px" height="30px"  alt="">   
                  <p>
                    Primero que nada voy a ayudar para que te sientas cómoda y segura de expresarte, seas o no profesional, coach o terapeuta. Todas indistintamente a nuestros conocimientos y experiencias necesitamos un espacio y un lugar para expresarnos auténticamente.  
                  </p>
              </div> 
                <div class="lista">
                    <img src="../assets/correcto-red.png" width="30px" height="30px"  alt=""> 
                    <p>
                        Te voy a ayudar a indagar, a ordenar ideas y a que encuentres tus herramientas. Todas las personas tenemos puntos ciegos. Y por eso necesitamos quién nos abra caminos.
                    </p> 
              </div> 
                <div class="lista">
                    <img src="../assets/correcto-red.png" width="30px" height="30px"  alt=""> 
                    <p>
                        Te voy a escuchar sin juicio. Y lo digo tan segura, porque comprendo lo necesario que es sentirse tranquila al momento de contar nuestras historias, sucesos o situaciones.
                    </p>
              </div> 
                <div class="lista">
                    <img src="../assets/correcto-red.png" width="30px" height="30px"  alt=""> 
                    <p>
                        Te voy a ayudar a expandir la mirada, podrás observar que creencias te están limitando y cuáles debes fortalecer para seguir avanzando. Es como cuando hacemos un viaje o un paseo, vemos muchísimas imágenes y situaciones que no vemos cotidianamente.
                    </p>
              </div> 
                <div class="lista">
                    <img src="../assets/correcto-red.png" width="30px" height="30px"  alt=""> 
                     <p>
                         Estas convers<span>acciones</span> poderosas, tendrán técnicas de coaching y PNL, las cuales van a ayudar a tener más claro las ideas, el camino y los cambios que deseas. 
                     </p>
              </div> 
                <div class="lista">
                    <img src="../assets/correcto-red.png" width="30px" height="30px"  alt=""> 
                    <p>
                        Y las llamé así, porque son conversaciones con acciones,  integrando las herramientas del coaching y el  para organizar las ideas y los pasos a seguir en el área que plantees. 
                    </p>
              </div>       
                
               
                
                
               
                
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
	height: 100%;
	background-image: url(/src/assets/susi4.jpg);
	filter: brightness(1.35);
	background-size: cover;
	background-repeat: no-repeat;
	background-position-x: 35%;
 
}
.info-respuesta{
    text-align: left;
    margin-bottom: 2rem;
}
.info-respuesta h2{
    font-weight: 800;
    color: var(--main-color);
    padding: 0.8rem;
    margin-top: 2rem;
    text-transform: uppercase;
}
.info-respuesta h2 span {
    text-decoration: underline 5px var(--main-color);
    color: var(--hover-btn);
}
.info-respuesta p{
    color: var(--main-color);
    padding: .8rem;
}
.info-respuesta p span {
    text-decoration: underline 3px var(--main-color);
    text-transform: uppercase;
}
.lista{
    display: flex;
    flex-direction: row;   
    justify-content: flex-start;
    align-items: flex-start;
    margin-left: 1rem;    
    gap: .2rem;
    padding:0;   
}
.lista img{
    margin-top: .8rem;
}
@media screen and (max-width: 850px) {
    .contenido{
        grid-template-columns: 1fr;
    
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