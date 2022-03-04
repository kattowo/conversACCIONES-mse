<template>
    <section>
        <div class="contenido"> 
            <h2>Paquetes de Sesiones</h2>
            <div class="card">
                <div>
                    <h2><span>1</span></h2>
                    <h2>sesión</h2>
                </div>
                <div class="precio">
                    <h3>Usd 57</h3>
                </div>
            </div>
            <div class="card">
                <div>
                    <h2><span>4</span></h2>
                    <h2>sesiones</h2>
                </div>
                <div class="precio">
                    <h3>Usd 200</h3>
                </div>
            </div>
            <div class="card">
                <div>
                    <h2><span>6</span></h2>
                    <h2>sesiones</h2>
                </div>
                <div class="precio">
                    <h3>Usd 282</h3>
                </div>    
            </div>
        </div>
            <div class="gratis">
                <h2>Gratis</h2>
                <p>video llamada para despejar dudas</p> 
                <a href="https://api.whatsapp.com/send?phone=+56930527200"><button class="btn">Agendar</button></a>                
            </div>
    </section>
</template>

<style scoped>
section{
    width: 100%;   
    font-family: 'Jost', sans-serif;
  
}
.contenido{
    max-width: 1200px;
    margin: auto;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
    justify-content: center;
    align-items: center;  
    
  
}
.contenido h2{
    font-weight: 800;
    color: var(--main-color);
    padding: 0.8rem;
    margin-top: 3rem;
    text-transform: uppercase;
    grid-column: 1/-1;    
    text-align: center;
}
.card{
    width: 80%;     
    display: flex;  
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    border: 5px solid var(--main-color);
    border-radius: 20px;
    margin: auto;
    
}
.card h2{
   margin: 2.6rem;
   padding: 0;
}
.card h2 span{
    font-size: 4rem;
    margin: 1px;
    padding: 1px;
}
.precio{
    width: 100%;
    height: 70px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: var(--main-color);
    color: var(--main-color2);
}
.precio h3{
    text-transform: uppercase;
}
.gratis{
    background-color: var(--main-color);
    display: flex;
    height: 18rem;
    flex-direction: column;
    margin-top: 3rem;
    justify-content: center;
    align-items: center;
    color: #ffffff;
    font-size: x-large;    
}
.gratis h2{
    color: #ffffff;
    text-transform: uppercase;
    font-weight: 800;
    font-size: 3rem;
}
.btn{
  font-family: 'Manrope', sans-serif; 
  font-weight:800;  
  font-size:1.2rem;
  text-transform:uppercase;
  background-color:#ffffff;
  border:none;
  border-radius:25px;
  width:15rem;
  padding:.3rem 1rem;
  z-index:5;
  color:var(--main-color);  
  cursor:pointer;
  border:3px solid var(--main-color);
  transition: ease .3s;
  margin-top: 2rem;
  
}
.btn:hover {
    color: #ffffff;
    background-color: var(--hover-btn);
}


@media screen and (max-width: 850px) {
    .contenido{
        width: 85%;
        display: flex;
        flex-direction: column;
        margin-bottom: 3rem;
    }
}
</style>