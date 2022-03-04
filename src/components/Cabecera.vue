<template>
   <div class="cabecera">
    <div class="presentacion">
      <div class="circulo"><img alt="Vue logo" src="../assets/susi1.jpg"></div>
          <div class="circulo1"><img alt="Vue logo" src="../assets/susi3.jpg"></div>
          <div class="circulo2"></div>
          <div class="circulo3"></div>  
          <div class="cargo">
            <h1>
              ¿QUIERES SABER SI TE SERÍA ÚTIL UNA SESIÓN DE CONVERS<span>ACCIONES</span> PERSONALIZADA CONMIGO?
            </h1>
       
           <!-- <a href="https://api.whatsapp.com/send?phone=+56930527200"><button class="btn">Agendar</button></a>-->
            <div>

            </div>
                <div class="circulo-up">
                  <div class="circulo-wave0"></div>
                  <div class="circulo-wave02"></div>         
                </div>     
          </div>
        
        <div class="waves">        
              <div class="circulo-wave1"></div>
              <div class="circulo-wave2"></div>  
              <div class="circulo-wave3"></div>           
        </div>  
    </div>
    
  </div> 
</template>

<script>
export default {
  name: 'Cabecera'
}
</script>

<style scoped>

.cabecera{
  width: 100%;
  height: 550px;
  display:grid;
  grid-template-columns: 1fr 2fr;
  justify-content: center;
  align-items: center;
  background-image: url(../assets/susi3.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position-y: 30%;
  font-family: 'Manrope', sans-serif; 
  overflow: hidden;

}
.presentacion{
 grid-column: 2/-1;
 overflow: hidden;
}
.circulo-up{
  width: 100%;
  height: 550px;
  overflow: hidden;
  z-index: 1;
  position: absolute;
  top: 0;
  left: 0;
 background: rgb(255,209,255);
background: -moz-linear-gradient(90deg, rgba(255,209,255,0) 47%, rgba(255,209,255,1) 65%, rgba(255,209,255,1) 100%);
background: -webkit-linear-gradient(90deg, rgba(255,209,255,0) 47%, rgba(255,209,255,1) 65%, rgba(255,209,255,1) 100%);
background: linear-gradient(90deg, rgba(255,209,255,0) 47%, rgba(255,209,255,1) 65%, rgba(255,209,255,1) 100%);
filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#ffd1ff",endColorstr="#ffd1ff",GradientType=1); 

}
.circulo-wave0{
        width: 800px;
        height: 550px;
        position: absolute; 
        margin-top: -24rem;
        margin-left: 50%;
        border: #f3f4f5 500px solid;
        transform: rotate(9deg);
        border-radius: 60%;
        z-index: 0;
        opacity: .546;
        animation: circulo-up 10s ease infinite;
} 
.circulo-wave02{
        width: 800px;
        height: 660px;
        position: absolute; 
        margin-top: -30rem;
        margin-left: 50%;
        border: #f3f4f5 430px solid;
        transform: rotate(39deg);
        border-radius: 60%;
        z-index: 0;
        opacity: .332;
        animation: circulo-up 20s ease infinite;
} 
@keyframes circulo-up {
          from{
            transform: rotate(0deg);        
          }
         to {
            transform: rotate(360deg);
          }
 }
.waves{
  display: none;
}

.circulo{
  display: none;
  width: 200px;
  height: 200px;
  border-radius: 10%;  
  border: #f14e8f 15px solid;
 /* outline: #002fff solid 10px;*/
  z-index: 3;
}
.circulo1 img{
  width: 50%;
  display: none;
  z-index: 2;
}
.cargo{
  display:grid; 
  text-align: left;
  margin-left: 2.5rem;
  margin-top: 2rem;
  grid-column: 2/-1;
  grid-row: 1/3;
  justify-content: center;
  align-items: center;
  z-index: 5;
}
.cargo h1{
    font-family: 'Jost', sans-serif;
    color: var(--main-color);
    font-size: 1.82rem;
    line-height: 2rem;
    font-weight: 800;
    z-index: 5;
    position: relative;
    margin-top: 3rem;
    margin-left: 5rem;
    padding: 0 12rem;  
}
.cargo h1 span{
  color: var(--hover-btn); 
  padding: 0px 5px 0 0;
  text-decoration: var(--main-color) underline 5px;
  border-radius:5px ;
}

.cargo h3{
   font-family: 'Jost', sans-serif;
  font-size: 3rem;
  line-height: 2rem;
  z-index: 5;
  position: relative;
  margin-left: 10rem;
  color: var(--main-color);
}
.cargo a {
  z-index:5;
}
 .btn{
  font-family: 'Manrope', sans-serif; 
  font-weight:800;  
  font-size:1.2rem;
  text-transform:uppercase;
  background-color:#c50050;
  border:none;
  border-radius:25px;
  width:15rem;
  padding:.3rem 1rem;
  z-index:5;
  color:#fff;
  margin-top:2rem;
  margin-left: 18rem;
  cursor:pointer;
  border:3px solid var(--main-color);
  transition: ease .3s;
  
}
.btn:hover{
  background-color:var(--hover-btn); 
  border:3px solid var(--hover-btn);
}


.redes{
  display:flex;
  justify-content: flex-start;
  align-items: flex-start;
  margin-top: 1rem;
  z-index: 5;
  margin-left: 10rem;
}
.redes img{
  width: 10%;   
}
.redes-circulo{
  display: flex;
  background: cornsilk;
  width: 35px;
  height: 35px;
  border-radius:50%;
  border: #ff0095 1px solid;
  z-index: 3;
}
.redes-circulo img{
  width: 70%;
  margin: auto;
  z-index: 3;
}

@media screen and (max-width: 850px) {
  
        .presentacion{
            display: flex;
            justify-content: center;
            align-items: center;     
            width: 100%;
            margin: auto;
        }
       .redes{
            display:flex;
            justify-content: center;
            align-items: center;
            margin-top: .3rem;
            margin-left: 0;
          }
       .redes img{
            width: 10%;
            margin-top: .5rem;
            z-index: 3;
          }
        .redes-circulo img{
            width: 70%;
            margin: auto;
        }
        .cabecera{
          /*color:#ecc58b ;*/
          color: #bd8a64;          
          height: 500px;
          display: flex;
          flex-direction:column;
          justify-content: center;
          align-items: center;
          background-image: none;
          box-shadow: 0px 0px 30px #929292;
          /*background: linear-gradient(to left, #ffecd2 0%, #fcb69f 110%);*/
          background-image: linear-gradient(to top, #fad0c4 0%, #ffd1ff 100%);
         z-index: 1;      
        }      

    .circulo-up{
      display: none;
    }
      .circulo{
        display: block;
        width: 150px;
        height: 150px;
        position: absolute;
        border-radius: 50%;
        margin-top: -15rem;
     
      }
      .circulo img{
        width: 110%;
        height: 105%;
        border-radius: 50%;
        margin-top: -2%;
        margin-left: -5%;
        background-color: #fff;
        z-index: 3;
      }
      .circulo1{
        border-radius: 50%;
        display: none;
        border: #ff0095 10px solid;
      }
      .circulo2{
        width: 145px;
        height: 150px;
        position: absolute; 
        border-radius: 50%;
        margin-top: -15rem;
        border: var(--main-color) 10px solid;
        transform: rotate(90deg);
        z-index: 3;
        animation: circulo2 2s ease infinite;
      }
      .circulo3{
        width: 139px;
        height: 160px;
        position: absolute; 
        margin-top: -15rem;
        border:var(--main-color) 10px solid;
        transform: rotate(99deg);
        border-radius: 50%;
        z-index: 3;
        animation: circulo2 8s ease infinite;
   
      }
   
        @keyframes circulo2 {
          from{
            transform: rotate(0deg);        
          }
         to {
            transform: rotate(360deg);
          }
        }
      .cargo{
        margin-top: 16rem;
        text-align: center;
        justify-content: center;
        align-items: center;
        margin: 0rem;      
        z-index:3 ;
        
      }
      .cargo h1{
        font-size: 1.6rem;
        line-height: 2rem;
        margin-top: 12rem;
        margin-left: 0; 
        padding:1rem 3rem;       
      }
      .cargo h3{
        font-size: 2.5rem;
        line-height: 0,2rem;
        margin-left: 0;               
      }

      .btn{
       margin:auto;
      }

            /* ////////////////////////////////////////////// ////////////// */

     
      .waves {      
          display: flex;
          position: absolute;
          height: 500px;
          width: 100%;
          overflow: hidden;
          z-index: 1;
          /* background-color: mediumaquamarine; */
          top: 0px;
          left: 0%;
         
    } 
        .circulo-wave1{
        width: 1200px;
        height: 960px;
        position: absolute; 
        margin-top: -65rem;
        margin-left: -35rem;
        border: #e23178 530px solid;
        transform: rotate(9deg);
         border-radius: 50%;
        z-index: 9;
        opacity: .36;
        animation: circulo2 15s ease infinite;
      } 
       .circulo-wave2{
        width: 1339px;
        height: 760px;
        position: absolute; 
        margin-top: -15.1rem;
        margin-left: -10rem;
        border: #f3f4f5 530px solid;
        transform: rotate(199deg);
         border-radius: 50%;
        z-index: 9;
        opacity: .3;
        animation: circulo2 15s ease infinite;
      } 
       .circulo-wave3{
        width: 539px;
        height: 660px;
        position: absolute; 
        margin-top: -5.1rem;
        border: #f3f4f5 630px solid;
        transform: rotate(299deg);
         border-radius: 50%;
        z-index: 9;
        opacity: .4;
        animation: circulo2 12s ease infinite;
      } 
          .wave {
            display: flex;            
            overflow: hidden; 
            z-index: 1;
            animation: 5s wave ease-in-out infinite alternate;
                       
            /*
            background: url(https://static.platzi.com/media/files/waves_c8551f5d-ecf6-4a81-ae1d-f3a0ad55ba10.png) center bottom no-repeat;
            */
          }
       
          .wave.a {
           animation-delay: .1s;            
           top: 20px;       
           overflow: hidden; 
           position: absolute;          
            
          }
          .wave.b {
            animation-delay: .9s;
            position: absolute;
            top: 175px;        
            overflow: hidden; 
      
          }
          .wave.c {
            animation-delay: 2.2s;
            position: absolute;
            top: 175px;
            left: 0%;
            overflow: hidden; 
          
          }
          @keyframes wave {
            0% {
              transform: translate(-45px , 0px);
            }
            50% {
              transform: translate(-180px, 0px);
            }
            100% {
              transform: translate(-45px, 0px);
            }
          }

 }   
</style>

