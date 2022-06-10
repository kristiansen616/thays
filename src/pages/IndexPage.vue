<template>
    <q-carousel
      v-model="slide"
      transition-prev="jump-right"
      transition-next="jump-left"
      swipeable
      animated
      control-color="white"
      prev-icon="arrow_left"
      next-icon="arrow_right"
      navigation-icon="radio_button_unchecked"
      navigation
      padding
      arrows
      infinite
      :autoplay="autoplay"
      height="55em"
      class="bg-purple text-white shadow-1 rounded-borders"
    >
      <q-carousel-slide name="style" img-src="~assets/r16_9StoneOceanWallpaper_Lagger01onPatreon.png" class="column no-wrap flex-center">
        <q-icon name="style" size="56px" />
        <div class="q-mt-md text-center">
          {{ lorem }}
        </div>
      </q-carousel-slide>
      <q-carousel-slide name="tv" img-src="~assets/DracoMalfoyWallpaper.png" class="column no-wrap flex-center">
        <q-icon name="live_tv" size="56px" />
        <div class="q-mt-md text-center">
          {{ lorem }}
        </div>
      </q-carousel-slide>
      <q-carousel-slide name="layers" img-src="~assets/article_full@1x.jpg" class="column no-wrap flex-center">
        <q-icon name="layers" size="56px" />
        <div class="q-mt-md text-center">
          {{ lorem }}
        </div>
      </q-carousel-slide>
    </q-carousel>
  <div class="row justify-between">

    <q-card class="my-card">
      <q-parallax
        src="https://cdn.quasar.dev/img/parallax1.jpg"
        :height="150"
      />

      <q-card-section>
        <div class="text-h6">Our Changing Planet</div>
        <div class="text-subtitle2">by John Doe</div>
      </q-card-section>
    </q-card>

  </div>
  <div class="q-pa-md" style="max-width: 100%">
    <q-list bordered separator>

      <q-slide-item @top="onTop" @bottom="onBottom">
        <template v-slot:top>
          <q-icon name="link" />
        </template>
        <template v-slot:bottom>
          <q-icon name="link_off" />
        </template>

        <q-item style="height: 150px">
          <q-item-section avatar>
            <q-avatar color="primary" text-color="white" icon="fingerprint" />
          </q-item-section>
          <q-item-section>Slide vertically</q-item-section>
        </q-item>
      </q-slide-item>

    </q-list>
  </div>
  <div class="row text-center justify-center" style="padding-bottom: 99px">
    <div class="col-md-12 col-sm-10 col-xs-12 col-lg-12">
      <div class="q-pa-md">
        <div class="row no-gutters clients-wrap"
             style="visibility: visible; animation-name: fadeInUp;">
          <div class="col-lg-3 col-md-4 col-xs-6 col-sm-6 col-12">
            <div class="client-logo">
              <q-img src="~assets/photo_2022-06-01_17-52-26.jpg" no-native-menu />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6 col-sm-6 col-12">
            <div class="client-logo">
              <q-img src="~assets/photo_2022-06-01_17-52-57.jpg" no-native-menu />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6 col-sm-6 col-12">
            <div class="client-logo">
              <q-img src="~assets/photo_2022-06-01_17-52-25.jpg" no-native-menu />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6 col-sm-6 col-12">
            <div class="client-logo">
              <q-img src="~assets/photo_2022-06-01_17-52-31.jpg" no-native-menu />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6 col-sm-6 col-12">
            <div class="client-logo">
              <q-img src="~assets/photo_2022-06-01_17-52-35.jpg" no-native-menu />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6 col-sm-6 col-12">
            <div class="client-logo">
              <q-img src="~assets/photo_2022-06-01_17-52-38(2).jpg" no-native-menu />
            </div>
          </div>

          <div class="col-lg-3 col-md-4 col-xs-6 col-sm-6 col-12">
            <div class="client-logo">
              <q-img src="~assets/photo_2022-06-01_17-52-59.jpg" no-native-menu />
            </div>
          </div>
          <div class="col-lg-3 col-md-4 col-xs-6 col-sm-6 col-12">
            <div class="client-logo">
              <q-img src="~assets/photo_2022-06-01_17-54-43.jpg" no-native-menu />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="q-px-lg q-pb-md">
    <q-timeline :layout="layout" color="secondary">
      <q-timeline-entry heading>
        Timeline do nosso namoro
        <br>
        <q-timeline-entry heading>2021</q-timeline-entry>
      </q-timeline-entry>

      <q-timeline-entry
        title="Começo de tudo"
        subtitle="Setembro, 2021"
        side="left"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-06_18-23-13.jpg" no-native-menu />
        </div>
        <br/>
        <div>
          <p>
            Começo de tudo(Começo foi no tinder mas vamos fingir que foi por aqui dlskl)A gente foi tanto de boas no começo, muita conversa e se conheçendo e criando um vinculo
          </p>
        </div>
      </q-timeline-entry>

      <q-timeline-entry
        title="Primeiro encontro"
        subtitle="09 de Outubro, 2021"
        side="right"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-06_18-34-10.jpg" no-native-menu />
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-06_18-34-04.jpg" no-native-menu />
        </div>
        <br/>
        <div>
          <p>
            Nosso primeiro encontro e aonde acendeu a fogo que ta vivo ate hoje, nosso primeiro beijo foi tão incrivel que eu me apaixonei em um único beijo e já sabia que queria sair ou te ver denovo(não tiramos fotos no dia :( )
          </p>
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Começo do namoro(sim, foi no segundo encontro ;) )"
        subtitle="12 de Outubro, 2021"
        side="left"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-01_17-56-43.jpg" no-native-menu />
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-01_17-56-44.jpg" no-native-menu />
        </div>
        <br/>
        <div>
          <p>
            Segundo encontro e foi logo depois do primeiro(para ver como o primeiro foi bom, que a gente correu para se ver)Fui para Campo Grande a primeira vez na vida kkkkk e o uber quebrou no caminho para o Park Shopping, Graças a Deus cheguei são e salvo e para os braços de quem seria a minha namorada. Sái de Campo grande namorando e já estava perdidamente apaixonado em você Thays(Eu tinha feito o pedido de namoro mas ela não escutou kkkkk, ainda bem que ela me pediu logo em seguida, estavamos ná mesma página logo no começo de tudo)
          </p>
        </div>
      </q-timeline-entry>

      <q-timeline-entry
        title="Pausa de Tres semanas(3 semanas sem se ver)"
        subtitle="3 semanas"
        side="right"
      >
      </q-timeline-entry>

      <q-timeline-entry
        title="Ver eternos(bomba de filme)"
        subtitle="February 22, 1986"
        side="left"
        color="orange"
        icon="done_all"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-06_18-56-33.jpg" no-native-menu />
        </div>
      </q-timeline-entry>

      <q-timeline-entry
        title="Primeiro mês de namoro"
        subtitle="12 de Outubro, 2021"
        side="right"
        color="orange"
        icon="done_all"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-01_17-55-26(2).jpg" no-native-menu />
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-01_17-55-27.jpg" no-native-menu />
        </div>
        <br/>
        <div>
          <p>
            Um mês de namoro, Nosso primeiro mês foi muito bom e que jamais vai ser esquecido, ali começamos coisas e que vimos que gostavomos(amamos muitoooo) e que só deixou mais próximos e se amamando muito. Primeira vez que veio em casa e confesso que estava nervoso e ansioso, trocamos nossos presentes, ficamos avontade e depois ainda comemos batata frita perto da praia (Ameii os presentes amor :) )
          </p>
        </div>
      </q-timeline-entry>

      <q-timeline-entry
        title="Apresentção da menina Thays e conhecendo a mãe dela(Minha Sogra Sandra)"
        subtitle="04 de Dezembro, 2021"
        side="left"
      >
        <div>
          <p>
            Dia muito especial, começou indo ver a apresentação da Thays dancando fancy e pude conhecer a mãe dela, Fui para Campo Grande esse dia para ficar o máximo de tempo com ela.(Quase tinha esquecido conheci os amigos dela também kkkkk)
          </p>
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Segundo mês de namoro"
        subtitle="12 de Dezembro, 2021"
        side="right"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-01_17-55-30.jpg" no-native-menu />
        </div>
        <br/>
        <div>
          <p>
            Segundo mês juntos e foi mega especial, minha primeira vez em uma bienal e fui divertido demais, choveu abeça e conheci o restante da família da Thays, Tiramos essa belíssima foto(até postei no insta)
          </p>
        </div>
      </q-timeline-entry>

      <q-timeline-entry
        title="Aniversario Da Thays UHhuuuuuu"
        subtitle="28 de Dezembro, 2021"
        side="left"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/IMG-20211229-WA0001.jpg" no-native-menu />
        </div>
        <div>
          <p>
            Tive a oportunidade de passar esse aniversario contigo e dormir ai na sua casa a primeira vez, esse seu aniversario acredito eu que tenha sido bem incomum e inesperado, estarei em muitos e muitos aniversarios seus, obrigado pela por me deixar fazer parte disso.
          </p>
        </div>
      </q-timeline-entry>
      <q-timeline-entry heading>2022</q-timeline-entry>
      <q-timeline-entry
        title="Ano novo"
        subtitle="01 de Janeiro, 2022"
        side="right"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-01_17-56-11.jpg" no-native-menu />
        </div>
        <br/>
        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>

      <q-timeline-entry
        title="Terceiro mês de namoro"
        subtitle="12 de janeiro, 2021"
        side="left"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/IMG-20220116-WA0004.jpg" no-native-menu />
        </div>
        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Quarto mês de namoro"
        subtitle="12 de Fevereiro, 2021"
        side="right"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/IMG-20220214-WA0024.jpg" no-native-menu />
        </div>

        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Dia que minha mãe conheceu sua familia"
        subtitle="26 de Fevereiro, 2021"
        side="left"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/IMG-20220226-WA0010.jpg" no-native-menu />
        </div>
        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Quinto mês de namoro"
        subtitle="12 de Março, 2021"
        side="right"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/IMG-20220312-WA0008.jpg" no-native-menu />
          <q-img width="300px" height="350px" src="~assets/IMG-20220312-WA0004.jpg" no-native-menu />
        </div>

        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Dia do Parque"
        subtitle="30 de Março, 2021"
        side="left"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/IMG_20220326_181320.jpg" no-native-menu />
        </div>
        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Sexto mês de namoro"
        subtitle="12 de Abril, 2021"
        side="right"
      >
        <div>
        <q-img width="300px" height="350px" src="~assets/IMG-20220412-WA0001.jpg" no-native-menu />
      </div>
        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Dia do Carnaval"
        subtitle="24 de Abril, 2021"
        side="left"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/photo_2022-06-08_20-02-38.jpg" no-native-menu />
        </div>
        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Dia do Bioparque"
        subtitle="30 de Abril, 2021"
        side="right"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/IMG_20220430_130633.jpg" no-native-menu />
        </div>
        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Pré estreia de Doutor Estranho"
        subtitle="04 de Maio, 2021"
        side="left"
      >
        <div>
          <q-img width="300px" height="350px" src="~assets/IMG-20220519-WA0044.jpg" no-native-menu />
        </div>
        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Sétimo mês de namoro"
        subtitle="12 de Maio, 2021"
        side="right"
      >
        <div>
        <q-img width="300px" height="350px" src="~assets/IMG_20220514_175740.jpg" no-native-menu />
      </div>
        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Oitavo mês de namoro"
        subtitle="12 de junho, 2021"
        side="left"
      >
        <div>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Para os proxímos meses"
        subtitle="Todo o sempre"
        side="right"
      >
        <div>
          <p>
            Vou atualizar sempre...
          </p>
        </div>
      </q-timeline-entry>
    </q-timeline>
  </div>
  <div :style="'border-top: 2px solid;'" class="flex flex-center text-white q-pt-lg"
       style="background-color: #295ec7;">
    <q-card class="card-footer" flat style="background-color: #295ec7; padding-top: 100px">
      <q-card-section class="row justify-center">
        <div class="col-12 col-md-12 col-lg-6 col-sx-12 col-sm-12">
          <q-card-section>
            <p class="text-h5">Contato</p>
            <p>labmetro.uerj@gmail.com</p>

            <p>Telefone:0 xx 21 2334-0725 / 0726 / 0727</p>
          </q-card-section>

        </div>
      </q-card-section>
      <hr>
      <div class="q-pa-lg">
        <p class="text-center">© 2021 Thays Cristina Ferreira Moreira dos Santos.</p>
      </div>
    </q-card>
  </div>
</template>

<script>
import { defineComponent, ref, computed, onBeforeUnmount } from 'vue'
import { useQuasar } from 'quasar'

export default defineComponent({
  name: 'IndexPage',
  setup () {
    const $q = useQuasar()
    const step = ref(1)
    const done1 = ref(false)
    const done2 = ref(false)
    const done3 = ref(false)
    let timer

    function finalize (reset) {
      timer = setTimeout(() => {
        reset()
      }, 1000)
    }

    onBeforeUnmount(() => {
      clearTimeout(timer)
    })
    return {
      onTop ({ reset }) {
        finalize(reset)
      },

      onBottom ({ reset }) {
        finalize(reset)
      },
      autoplay: ref(true),
      layout: computed(() => {
        return $q.screen.lt.sm ? 'dense' : ($q.screen.lt.md ? 'comfortable' : 'loose')
      }),
      step,
      done1,
      done2,
      done3,
      slide: ref('style'),
      lorem: 'Lorem ipsum dolor, sit amet consectetur adipisicing elit. Itaque voluptatem totam, architecto cupiditate officia rerum, error dignissimos praesentium libero ab nemo.'
    }
  }
})
</script>

<style lang="sass">
.menu-active
  background-color: #27acce
.my-header
  width: 200px
  top: 0
  height: 45px
  color: black
  background-color: rgba(255, 255, 255, 0.8)
  text-transform: uppercase
  text-align: center
  font-size: 17px
  margin: 20px 0 0 68px
  padding: 25px

.card-footer
  height: 100%
  width: 100%
  max-width: 1000px

.custom_tab
  width: 130px

.style-customer
  width: 120px !important
  min-height: auto !important
  color: #000000
.my-card
  width: 100%
  max-width: 500px
.logo-marca
  border-right: 3px solid red

</style>
