<template>
  <header>

    <div id="kedua">
      <div class="container h-100 background">
        <div class="row align-items-center h-100">
          <div class="col-lg-6 py-3 wow fadeInUp">
            <p id="text"
              class="text-yellow-600 hover:text-yellow-500 text-2xl lg:text-4xl font-medium lg:font-semibold mb-5 lg:leading-normal leading-snug">
              <div id="test">
               Hi, guys    ,,,,,,
               <br/>
               Kenalin
              <br />
              Nama Aku,
              <br />
              Dzaki
              </div>
            </p>
            <p
              class="hidden lg:block text-2xl mb-5">
               Aku mahasiswa Universitas Islam Negeri Sultan Syarif Kasim Riau dengan Prodi Teknik Informatika
            </p>

            <router-link
              to="/about"
              name="fade"
              id="initentang" class="btn btn-outline border text-secondary">
              Tentang
            </router-link>
            <a
              href="https://drive.google.com/file/d/1FaiPHNEKFIXfyp2hhYzmyw0wcfFZuAFY/view?usp=share_link"
              id="ini" class="btn btn-primary btn-split ml-2">
              CV Saya
              <div class="fab"><span class="mai-play"></span></div>
            </a>
          </div>
          <div class="col-lg-6 wow zoomIn">
            <div id="gambarku"
              class="m-3 lg:m-1 p-5 lg:p-5">
            
                <img src="../images/dua.jpg"
                background="transparent"
                style="max-width: 500px; max-height: 500px"
                >
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>

  <section id = "about" class = "py-5">
        <div class = "container">
            <div class = "row gy-lg-5 align-items-center">
                <div class = "col-lg-6 order-lg-1 text-center text-lg-start">
                  
                    <p class = "lead text-muted">Beberapa pengalaman saya di organisasi</p>
                   <br>
                   <br>
                   <br>
                   <br>

                    <p>Foto yang menunjukkan disebelah adalah beberapa diantara keikut sertaan saya dalam organisasi yang ada dikampus yaitu diantaranya di slide pertama menunjukkan bahwa saya ikut kepanitiaan dalam acara seminar nasional yang diadakan di gedung uin, di slide kedua menunjukkan bahwa saya ikut dalam kepanitiaan himpunan mahasiswa yang ada di jurusan saya, dan yang terakhir menunjukkan bahwa saya menjad bagian crew dari suskatv dimana saya menjadi editor</p>
                </div>
                <div id="carouselExampleDark" class="carousel col-lg-6 order-lg-0 slide">
                    <div class="carousel-indicators">
                      <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                      <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="1" aria-label="Slide 2"></button>
                      <button type="button" data-bs-target="#carouselExampleDark" data-bs-slide-to="2" aria-label="Slide 3"></button>
                    </div>
                    <div class="carousel-inner">
                      <div class="carousel-item active" data-bs-interval="10000">
                        <img src="../images/1.jpg" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                          <h5>Panitia Seminas Nasional</h5>
                          <p>Disini saya menjadi kepanitiaan divisi hid.</p>
                      
                        </div>
                      </div>
                      <div class="carousel-item" data-bs-interval="2000">
                        <img src="../images/2.jpg" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                          <h5>Pengurus Himatif</h5>
                          <p>Disini saya bergabung menjadi kepengurusan himatif department infokom.</p>
                        </div>
                      </div>
                      <div class="carousel-item">
                        <img src="../images/3.jpg" class="d-block w-100" alt="...">
                        <div class="carousel-caption d-none d-md-block">
                          <h5>Crew Suskatv</h5>
                          <p>Saya menjadi bagian crew suskatv divisi editor</p>
                        </div>
                      </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleDark" data-bs-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Next</span>
                    </button>
                  </div>
            </div>
        </div>
    </section>

</template>

<script>

</script>

<style>

#about{
  background-color: #FFDE59;
}

#kedua{
  background-image: linear-gradient(60deg, #FFDE59 0%, #FFDE59 100%);
}

#initentang{
background-color: white;
}

#ini{
  background-color: black;
}


#text{ display: inline-block;

}
#test{
  color: black;
  font-size: 2rem;
  letter-spacing: 10px;
  font-family: monospace;
  border-right: 5px solid;
  width: 60%;
  white-space: nowrap;
  overflow: hidden;
  animation: 
           typing 2s steps(8),
           cursor .4s step-end infinite alternate;

}


  @keyframes cursor {
         50% { border-color: transparent}
    
  }

  @keyframes typing {
          from { width:0}
  }
    
 

</style>
