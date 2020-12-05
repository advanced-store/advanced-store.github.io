<template>
  <main>
        <div class="container-fluid" id="advanded-store">
          <div class="row margin-top align-items-center" style="margin-top: 10%">
            <div class="col-md ">
              <h1 class="text-center"> Advanced Store </h1>
              <p>venimos a dar soluciones a su empresa, poniendo a disposición productos adaptados a sus necesidades y actualizables, 
              por lo que crecen junto con las necesidades de la empresa.</p>
              <p>
              <p class="text-center">
                  <router-link class="btn btn-primary align-middle" to="/sobre">Ver Mas</router-link>
              </p>
            </div>
            <div class="col-sm ">
              <img src="path20.png" alt="" width="100%">
            </div>
          </div>
        </div>
        <div class="container-fluid" id="creadores">
          <div class="row margin-top align-items-center" style="margin-top: 10%">
            <div class="col-sm d-none d-md-block d-lg-block d-xl-block">
              <img src="img2.png" alt="" width="70%">
            </div>
            <div class="col-sm">
              <h1 class="text-center">
                  Creadores de Contenido
              </h1>
              <p>
                 El rol de los creadores de contenido, ahora son la puerta de nuevos productos y diferentes maneras de consumirlos. 
                 Queremos ofrecer soluciones para ellos también. Es por eso que nos estamos embarcando en crear marketplace para ellos, 
                 permitiendo que se profesionalicen. 
                 Nuestra primer incursión es Cooking Beats para aquellos que ofrecen instrumentales.
              </p>
            </div>
            <div class="col-sm d-block d-sm-none">
              <img src="img2.png" alt="" width="100%">
            </div>
          </div>
        </div>
        <div class="container-fluid" id="equipo">
          <div class="row margin-top align-items-center" style="margin-top: 10%">
            <div class="col-sm">
              <h1 class="text-center">Equipo de Trabajo</h1>
              <p>Nuestro equipo es pequeño pero apostamos al trabajo remoto, ya que vemos en esto ventajas competitivas.
               Con la pandemia las empresas tuvieron que adaptarse al trabajo remoto, por lo cual una buena infraestructura informática y 
               organizativa es esencial. Podemos darle nuestras recomendaciones sobre este aspecto.</p>
            </div>
            <div class="col-sm">
              <img src="img3.png" alt="" width="100%">
            </div>
          </div>
        </div>
        <div class="container-fluid">
          <h1 class="text-center">Soluciones</h1>
          <div class="row row-cols-1 row-cols-md-3">
            <div class="col mb-4">
              <div class="card text-center align-middle">
                <img src="Frame 6.png" alt="" width="25%" height="25%" style="margin-left: 38%; margin-top: 10%">
                <div class="card-body">
                  <h5 class="card-title text-bg-color2">Ecommerce</h5>
                  <p class="card-text">contamos con varias soluciones de ecommerce, cada una es más completa que la anterior.</p>
                </div>
                <div class="card-footer">
                  <router-link class="btn btn-primary text-bg-color1" role="button" to="/">Mas Informacion</router-link>
                </div>
              </div>
            </div>
            <div class="col mb-4">
              <div class="card text-center align-middle">
                <img src="Frame 7.png" alt="" width="25%" height="25%" style="margin-left: 38%; margin-top: 10%">
                <div class="card-body">
                  <h5 class="card-title text-bg-color2">Soluciones Empresariales</h5>
                  <p class="card-text">Soluciones pequeñas de  gestión de fichaje, memorandos, y soluciones personalizadas.</p>
                </div>
                <div class="card-footer">
                  <router-link class="btn btn-primary text-bg-color1" role="button" to="/">Mas Informacion</router-link>
                </div>
              </div>
            </div>
            <div class="col mb-4">
              <div class="card text-center align-middle">
                <img src="Frame 8.png" alt="" width="25%" height="25%" style="margin-left: 38%; margin-top: 10%">
                <div class="card-body">
                  <h5 class="card-title text-bg-color2">Creadores de Contenido</h5>
                  <p class="card-text">Esta es la parte mas experimental de Advanced Store, estamos diseñando soluciones para esto, puede sarber mas sobre esto y apollar los proyectos</p>
                </div>
                <div class="card-footer">
                  <router-link class="btn btn-primary text-bg-color1" role="button" to="/">Mas Informacion</router-link>
                </div>
              </div>
            </div>
          </div>
        </div>
        <Footer></Footer>
    </main>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
};
</script>
