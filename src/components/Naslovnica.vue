<template>
  <div>
    <b-container fluid>
      <b-jumbotron id="naslovnica">
        <p id="naslov">Restoran Astoria</p>
        <br />
        <br />
        <br />
        <p id="o_restoranu">
          Bilo da ste u potrazi za kvalitetnim obrokom u vrijeme pauze za ručak
          ili opuštanjem uz večeru, restoran Astoria je odabir za vas. Jednako
          privlačan poslovnim ljudima zbog mogućnosti naručivanja hrane
          unaprijed, obiteljima s djecom i turistima željnima kombinacije okusa
          vrhunskih specijaliteta, očarat će vas svojim uređenjem te opuštenim
          gostima, koji se s razlogom uvijek rado vraćaju.<br />
          Dobrodošli u restoran Astoria!
        </p>
      </b-jumbotron>
    </b-container>
    <div class="opis">
      <img
        src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fbishsdishes.files.wordpress.com%2F2011%2F11%2Fp1040894.jpg&f=1&nofb=1"
        width="400px"
        height="400px"
      />
      <h1>Hrana je naša strast</h1>
      <p>
        Svakoj namirnici pristupamo s posebnom pažnjom, kako bismo<br />
        kreirali najbolji doživljaj za vaše nepce. Uživajte u šarolikoj
        ponudi<br />
        jela i specijaliteta kuće. Vaše zadovoljstvo, naša je nagrada.
      </p>
    </div>
    <div class="kart">
      <img
        src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.stlmag.com%2Fdownloads%2F198707%2Fdownload%2FMichel-Bras-La-Gargouillou-de-jeunes-le%25C3%258C%25C2%2581gumes-graines-et-herbes-lait-de-poul-a%25C3%258C%25C2%2580-la-noisette.jpg%3Fcb%3D661efef72bf057319c35057a9946dd90&f=1&nofb=1"
        width="400px"
        height="400px"
      />
      <p>
        Kuharstvo podrazumijeva: englesku temeljitost,<br />
        francusku umjetnost, arapsku gostoljubivost... <br />podrazumijeva
        poznavanje sveg voća, začina, umaka... <br />podrazumijeva pažljivost,
        inventivnost i pozornost.<br /><br />
        <span>- John Ruskin</span>
      </p>
    </div>
    <div class="prijelaz"></div>
    <div id="galerija">
      <h1>Galerija</h1>
      <br />
      <b-container>
        <b-carousel
          id="carousel-fade"
          style="text-shadow: 0px 0px 2px #000"
          fade
          indicators
          img-width="1024"
          img-height="480"
        >
          <b-carousel-slide
            img-src="https://york.independentlife.co.uk/wp-content/uploads/sites/3/2019/01/12244669_172824903070710_3291839174859070294_o-1024x480.jpg"
          ></b-carousel-slide>
          <b-carousel-slide
            img-src="https://www.eventsource.ca/blog/wp-content/uploads/2017/05/elle-cuisine-header-1024x480.jpg"
          ></b-carousel-slide>
          <b-carousel-slide
            img-src="https://www.christinis.com/wp-content/uploads/2019/03/bestfinediningorlando-1024x480.jpg"
          ></b-carousel-slide>
        </b-carousel>
      </b-container>
    </div>
    <div class="info"> 
      <br><b>Radno vrijeme</b><br>
      <img src="http://restorantagliata.hr/wp-content/uploads/2019/09/decor-2-big-white.png">
      <p>
        <b>Pon-Čet: </b>8:00 - 17:00<br>
        <b>Pet-Ned: </b>8:00 - 23:00
      </p>
    </div>
  </div>
</template>

<style>
.info{
  background-color: darkslategray;
  color: white;
  text-align: center;
  margin-top: 200px;
  height: 150px;
}
#galerija h1 {
  font-family: papyrus;
  color: darkslategray;
  text-align: center;
  font-size: 70px;
  margin-top: 30px;
}
#galerija {
  margin-top: 50px;
  margin-bottom: 10px;
  height: 500px;
}
.prijelaz {
  height: 85px;
  background-color: rgb(165, 36, 31);
  margin-top: 250px;
}
.kart span {
  margin-right: 100px;
  color: lightcoral;
  font-family: papyrus;
  font-size: 20px;
  font-weight: bold;
}
.kart p {
  margin-top: 100px;
  text-align: center;
  font-family: Trattatello;
  font-size: 20px;
  color: darkslategray;
}
.kart img {
  border-radius: 50%;
  margin-bottom: 10px;
  margin-left: 100px;
  float: left;
}
body {
  background-image: url("https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmarukoshi.rs%2Fwp-content%2Fuploads%2Frevslider%2Fnaslovna%2Fs3.jpg&f=1&nofb=1");
  background-repeat: no-repeat;
  background-size: auto;
}
.opis {
  margin-top: 150px;
}
.opis img {
  float: right;
  border-radius: 50%;

  margin-right: 10px;
}
.opis h1 {
  font-family: papyrus;
  color: lightcoral;
  text-align: center;
  margin-top: 250px;
}
.opis p {
  margin-top: 50px;
  font-family: Trattatello;
  text-align: center;
  color: darkslategray;
  font-size: 20px;
}
#naslovnica {
  opacity: 80%;
  margin-top: 150px;
}
#naslov {
  text-align: center;
  font-family: papyrus;
  font-size: 80px;
}
#o_restoranu {
  font-family: Trattatello;
  color: darkslategray;
  font-size: 19px;
  text-align: center;
}
#kartica {
  box-shadow: 5px 5px 5px 5px lightgray;
  text-align: center;
  font-size: 19px;
  font-family: Trattatello;
}
</style>
  

<script>
export default {
  name: "Naslovnica",
  data() {
    return {
      slide: 0,
      sliding: null,
    };
  },
  methods: {
    onSlideStart() {
      this.sliding = true;
    },
    onSlideEnd() {
      this.sliding = false;
    },
  },
};
</script>