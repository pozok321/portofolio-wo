<template>
  <main>
    <div id="myCarousel" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="0" class="active" aria-current="true"
          aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#myCarousel" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="../assets/image/pintu-masuk.jpg" alt="pelaminan" height="600" class="dblock w-100">
          <div class="container">
            <div class="carousel-caption text-start">
              <h1>Example headline.</h1>
              <p>Some representative placeholder content for the first slide of the carousel.</p>
              <p><a class="btn btn-lg btn-primary" href="#">Sign up today</a></p>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <img src="../assets/image/pelaminan-1.jpg" alt="pelaminan" height="600" class="dblock w-100">
          <div class="container">
            <div class="carousel-caption">
              <h1>Another example headline.</h1>
              <p>Some representative placeholder content for the second slide of the carousel.</p>
              <p><a class="btn btn-lg btn-primary" href="#">Learn more</a></p>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <img src="../assets/image/mp-pelaminan.jpg" alt="pelaminan" height="600" class="dblock w-100">
          <div class="container">
            <div class="carousel-caption text-end">
              <h1>One more for good measure.</h1>
              <p>Some representative placeholder content for the third slide of this carousel.</p>
              <p><a class="btn btn-lg btn-primary" href="#">Browse gallery</a></p>
            </div>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#myCarousel" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#myCarousel" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

<!-- Content -->
    <div class="container-fluid">
      <div class="row featurette p-5">
        <div class="col-md-7">
          <h2 class="featurette-heading">Tentang Kami</h2>
          <p class="lead">PakaiKami adalah pelayanan jasa Wedding Organizer yang menyediakan berbagai kebutuhan untuk
            sebuah acara pernikahan dan lamaran</p>
          <p class="lead">Kami mengutamakan jasa pelayanan Wedding Organizer guna memperindah serta memeriahkan sebuah
            acara Pernikahan dan Lamaran yang diinginkan oleh setiap customer kami</p>
          <p class="lead">Karena #weknowourcustomer</p>
        </div>
        <div class="col-md-5">
          <img src="../assets/image/pakaikami.jpeg" alt="pelaminan" height="400" class="dblock w-100 rounded-circle">
        </div>
      </div>
      </div>

      <div class="divider-example"></div>

      <div class="container-fluid">
      <div class="row featurette p-5">
        <div class="col-md-7 order-md-2">
          <h2 class="featurette-heading">Apa yang kami sediakan?</h2>
          <p class="lead">Kami menyediakan tidak hanya service kepada customer, melainkan dekorasi, cathering, sewa
            entertainment dan masih banyak lagi hal yang terkait dengan wedding. Karena kami memiliki vendor yang sudah
            berkecimpung didunia wedding</p>
        </div>
        <div class="col-md-5 order-md-1">
          <img src="../assets/image/pakaikami.jpeg" alt="pelaminan" height="400" class="dblock w-100 rounded-circle">
        </div>
      </div>
    </div>

      <div class="divider-example"></div>

      <div class="container-fluid">
        <div class="px-4 pt-5 my-5 text-center border-bottom">
    <h1 class="display-4 fw-bold">Centered screenshot</h1>
    <div class="col-lg-6 mx-auto">
      <p class="lead mb-4">Quickly design and customize responsive mobile-first sites with Bootstrap, the world’s most popular front-end open source toolkit, featuring Sass variables and mixins, responsive grid system, extensive prebuilt components, and powerful JavaScript plugins.</p>
      <div class="d-grid gap-2 d-sm-flex justify-content-sm-center mb-5">
        <button type="button" class="btn btn-primary btn-lg px-4 me-sm-3">Primary button</button>
        <button type="button" class="btn btn-outline-secondary btn-lg px-4">Secondary</button>
      </div>
    </div>
    <div class="overflow-hidden" style="max-height: 30vh;">
      <div class="container px-5">
        <img src="bootstrap-docs.png" class="img-fluid border rounded-3 shadow-lg mb-4" alt="Example image" width="700" height="500" loading="lazy">
      </div>
    </div>
  </div>
    </div>

      <div class="divider-example"></div>
      <div class="container-fluid">
      <div class="container px-4 py-5" id="custom-cards">
        <h2 class="pb-2">What We Provide</h2>
        <div class="row row-cols-1 row-cols-lg-3 align-items-stretch g-4 py-5">
          <div class="col">
            <div class="card card-cover h-100 overflow-hidden text-white bg-dark rounded-5 shadow-lg"
              style="background-image: url('../assets/image/cathering.jpg');">
              <div class="d-flex flex-column h-100 p-5 pb-3 text-white text-shadow-1">
                <h2 class="pt-3 mt-3 mb-4 display-7 lh-1 fw-bold">Decoration</h2>
                <ul class="d-flex list-unstyled mt-auto">
                  <li class="me-auto">
                    <img src="../assets/image/pakaikami.jpeg" alt="pakaikami" width="32" height="32"
                      class="rounded-circle border border-white"></li>
                  <li class="d-flex align-items-center me-3">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#geo-fill" /></svg>
                    <small>Earth</small>
                  </li>
                  <li class="d-flex align-items-center">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#calendar3" /></svg>
                    <small>3d</small>
                  </li>
                </ul>
              </div>
            </div>
          </div>

          <div class="col">
            <div class="card card-cover h-100 overflow-hidden text-white bg-dark rounded-5 shadow-lg"
              style="background-image: url('../assets/image/cathering.jpg');">
              <div class="d-flex flex-column h-100 p-5 pb-3 text-white text-shadow-1">
                <h2 class="pt-3 mt-3 mb-4 display-7 lh-1 fw-bold">Cathering</h2>
                <ul class="d-flex list-unstyled mt-auto">
                  <li class="me-auto">
                    <img src="../assets/image/pakaikami.jpeg" alt="pakaikami" width="32" height="32"
                      class="rounded-circle border border-white"></li>
                  <li class="d-flex align-items-center me-3">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#geo-fill" /></svg>
                    <small>Pakistan</small>
                  </li>
                  <li class="d-flex align-items-center">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#calendar3" /></svg>
                    <small>4d</small>
                  </li>
                </ul>
              </div>
            </div>
          </div>

          <div class="col">
            <div class="card card-cover h-100 overflow-hidden text-white bg-dark rounded-5 shadow-lg"
              style="background-image: url('unsplash-photo-3.jpg');">
              <div class="d-flex flex-column h-100 p-5 pb-3 text-shadow-1">
                <h2 class="pt-3 mt-3 mb-4 display-7 lh-1 fw-bold">Entertaintment</h2>
                <ul class="d-flex list-unstyled mt-auto">
                  <li class="me-auto">
                    <img src="../assets/image/pakaikami.jpeg" alt="pakaikami" width="32" height="32"
                      class="rounded-circle border border-white"></li>
                  <li class="d-flex align-items-center me-3">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#geo-fill" /></svg>
                    <small>California</small>
                  </li>
                  <li class="d-flex align-items-center">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#calendar3" /></svg>
                    <small>5d</small>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>

        <div class="row row-cols-1 row-cols-lg-3 align-items-stretch g-4 py-5">
          <div class="col">
            <div class="card card-cover h-100 overflow-hidden text-white bg-dark rounded-5 shadow-lg"
              style="background-image: url('unsplash-photo-1.jpg');">
              <div class="d-flex flex-column h-100 p-5 pb-3 text-white text-shadow-1">
                <h2 class="pt-3 mt-3 mb-4 display-7 lh-1 fw-bold">Photographer</h2>
                <ul class="d-flex list-unstyled mt-auto">
                  <li class="me-auto">
                    <img src="../assets/image/pakaikami.jpeg" alt="pakaikami" width="32" height="32"
                      class="rounded-circle border border-white"></li>
                  <li class="d-flex align-items-center me-3">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#geo-fill" /></svg>
                    <small>Earth</small>
                  </li>
                  <li class="d-flex align-items-center">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#calendar3" /></svg>
                    <small>3d</small>
                  </li>
                </ul>
              </div>
            </div>
          </div>

          <div class="col">
            <div class="card card-cover h-100 overflow-hidden text-white bg-dark rounded-5 shadow-lg"
              style="background-image: url('unsplash-photo-2.jpg');">
              <div class="d-flex flex-column h-100 p-5 pb-3 text-white text-shadow-1">
                <h2 class="pt-3 mt-3 mb-4 display-7 lh-1 fw-bold">Event Services</h2>
                <ul class="d-flex list-unstyled mt-auto">
                  <li class="me-auto">
                    <img src="../assets/image/pakaikami.jpeg" alt="pakaikami" width="32" height="32"
                      class="rounded-circle border border-white"></li>
                  <li class="d-flex align-items-center me-3">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#geo-fill" /></svg>
                    <small>Pakistan</small>
                  </li>
                  <li class="d-flex align-items-center">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#calendar3" /></svg>
                    <small>4d</small>
                  </li>
                </ul>
              </div>
            </div>
          </div>

          <div class="col">
            <div class="card card-cover h-100 overflow-hidden text-white bg-dark rounded-5 shadow-lg"
              style="background-image: url('unsplash-photo-3.jpg');">
              <div class="d-flex flex-column h-100 p-5 pb-3 text-shadow-1">
                <h2 class="pt-3 mt-3 mb-4 display-7 lh-1 fw-bold">MC</h2>
                <ul class="d-flex list-unstyled mt-auto">
                  <li class="me-auto">
                    <img src="../assets/image/pakaikami.jpeg" alt="pakaikami" width="32" height="32"
                      class="rounded-circle border border-white">
                  </li>
                  <li class="d-flex align-items-center me-3">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#geo-fill" /></svg>
                    <small>California</small>
                  </li>
                  <li class="d-flex align-items-center">
                    <svg class="bi me-2" width="1em" height="1em">
                      <use xlink:href="#calendar3" /></svg>
                    <small>5d</small>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

      <div class="divider-example"></div>

      <div class="container-fluid">
      <div class="row">
        <div class="col-lg-4">
          <!-- <img src="../assets/image/pale.jpeg" alt="pelaminan" class="dblock w-100 rounded-circle"> -->
          <h2 v-for="user in users" v-bind:key="user.id"></h2>
          <p>{{user.name}}</p>
          <p>{{user.email}}</p>
          <p><a class="btn btn-secondary" href="#">View details &raquo;</a></p>
        </div><!-- /.col-lg-4 -->
      </div><!-- /.row -->
    </div>

  </main>
</template>
<script>
  export default {
    name: "Content-new",
    data() {
      return {
        users: [
          {
            id: 1,
            name: "Valeryan Ramadhan",
            email: "Valeryanr18@gmail.com"
          },
          {
            id: 2,
            name: "Achmad Tabrizi",
            email: "achmadtabrizi@gmail.com"
          },
          {
            id: 3,
            name: "Didit Ardiansyah",
            email: "diditardiansyah@gmail.com"
          }
        ]
      };
    }

  };
</script>
<style>
  .divider-example {
    height: 3rem;
    background-color: rgba(0, 0, 0, .05);
    border: solid rgba(0, 0, 0, .15);
    border-width: 1px 0;
    box-shadow: inset 0 0.5em 1.5em rgb(0 0 0 / 10%), inset 0 0.125em 0.5em rgb(0 0 0 / 15%);
  }
  
  @media (min-width: 992px) {
    .rounded-lg-3 {
      border-radius: .3rem;
    }
  }
</style>