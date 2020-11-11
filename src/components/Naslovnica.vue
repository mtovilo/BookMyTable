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

      <div class="mt-4">
        <b-card
          id="kartica"
          img-src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fmoneycrashers-sparkchargemedia.netdna-ssl.com%2Fwp-content%2Fuploads%2F2015%2F10%2Ffancy-dinner-restaurant.jpg&f=1&nofb=1"
          img-alt="Hrana"
          img-width="350px"
          img-height="250px"
          img-left
          class="mb-3"
        >
            <b-card-text>
              Kuharstvo podrazumijeva: englesku temeljitost, francusku
              umjetnost, arapsku gostoljubivost... podrazumijeva poznavanje sveg
              voća, začina, umaka... podrazumijeva pažljivost, inventivnost i
              pozornost.<br /><br />
              <b>- John Ruskin</b>
            </b-card-text>
        </b-card>
      </div>
    </b-container>
  </div>
</template>

<style>
#naslovnica {
  opacity: 80%;
  margin-top: 100px;
}
#naslov {
  text-align: center;
  font-family: papyrus;
  font-size: 80px;
}
#o_restoranu {
  font-family: Trattatello;
  font-size: 19px;
  text-align: center;
}
#kartica {
  box-shadow: 5px 5px 5px 5px lightgray;
  text-align: center;
  font-size: 19px;
  font-family: Trattatello;
}
b {
  float: right;
}
</style>

<script>
export default {
  name: "Naslovnica",
};
</script>