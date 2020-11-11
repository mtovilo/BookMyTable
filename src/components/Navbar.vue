<template>
  <div style="box-shadow: 3px 3px 3px 3px White">
    <div>
      <b-navbar toggleable="lg" type="light" variant="light">
        <b-navbar-brand href="#">
          <img
            src="https://freesvg.org/img/chef-restaurant-logo-publicdomainvectors.png"
            width="40px"
            height="40px"
          />
          Restoran Astoria
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="#">Rezerviraj stol</b-nav-item>
            <b-nav-item href="#">Naruči unaprijed</b-nav-item>
            <b-nav-item
              href="https://drive.google.com/file/d/1pFLrr2uYjjy3dLgvk-mZF0hDuLS2Bjbw/view"
              target="_blank"
              style="margin-left: 710px"
              >Vizija</b-nav-item
            >
            <div>
              <b-button v-b-modal.modal-scrollable variant="light">Životopisi</b-button>

              <b-modal id="modal-scrollable" scrollable title="Životopisi">
                <p>
                  Naš projekt je namijenjen restoranima i njihovim gostima. Web
                  aplikacija će služiti za rezervaciju stolova u restoranu
                  'Astoria', a pruža mogućnost i naručivanja hrane unaprijed,
                  ukoliko gost to želi. Korisnici će moći rezervirati stol na
                  određeni datum i vrijeme i s određenim brojem mjesta. Restoran
                  će moći ažurirati svoj cjenik. Cilj ovog projekta je omogućiti
                  korisnicima što jednostavniju rezervaciju, a time bi se
                  smanjile i gužve u restoranu.
                </p>
                <b-row>
                  <b-col>
                    <b-card
                      title="Mihaela Tovilo"
                      tag="article"
                      style="max-width: 20rem"
                      class="mb-2"
                    >
                      <b-card-text>
                        Zovem se Mihaela Tovilo. Imam 20 godina i živim na
                        Kupresu gdje sam završila osnovnu školu i Opću
                        gimnaziju. Studentica sam 3. godine Informatike na
                        Sveučilištu u Mostaru. Studij informatike me privukao iz
                        razloga što smatram da ima dosta zanimljivih smjerova i
                        mogućnosti.<br><br><br>
                      </b-card-text>
                    </b-card>
                  </b-col>
                  <b-col>
                    <b-card
                      title="Valentina Oreč"
                      tag="article"
                      style="max-width: 20rem"
                      class="mb-2"
                    >
                      <b-card-text>
                        Zovem se Valentina Oreč. Imam 21 godinu i živim u
                        Uskoplju gdje sam završila osnovnu i srednju školu.
                        Studentica sam 3. godine Informatike na Sveučilištu u
                        Mostaru. Upisala sam studij informatike jer me oduvijek zanimalo kako određene stvari funkcioniraju i 
                        uvijek se može nešto novo naučiti.
                      </b-card-text>
                    </b-card>
                  </b-col>
                </b-row>
              </b-modal>
            </div>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>