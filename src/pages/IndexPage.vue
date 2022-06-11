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
      <q-carousel-slide name="style" img-src="~assets/wp3956246.jpg" class="column no-wrap flex-center">
      </q-carousel-slide>
      <q-carousel-slide name="tv" img-src="~assets/giyu-tomioka-shinobu-kocho-demon-slayer-kimetsu-no-yaiba-hashira-0-hd-wallpaper-1920x1080-uhdpaper.com-600.1_c.jpg" class="column no-wrap flex-center">
      </q-carousel-slide>
      <q-carousel-slide name="layers" img-src="~assets/gwen-and-miles-4k-u2-1366x768.jpg" class="column no-wrap flex-center">
      </q-carousel-slide>
    </q-carousel>
  <div class="row justify-between">

    <q-card class="my-card" style="max-width: 100%">
      <q-parallax
        src="~assets/photo_2022-06-01_17-54-489.jpg"
        :height="350">
        <div>
          <h1 class="text-center text-white">Feliz dia dos namorados!!</h1>
          <h5 class="text-white text-center">
            Nosso primeiro Dia dos Namorados e eu queria que fosse especial e único e fiz algo para você em que eu realmente soubesse e entregar com todo o meu amor. Fazer um site só para você e mostrar meu amor, carinho e o quanto me importo contigo. Eu te amo e para sempre vou te amar, vamos esperar os próximos dias dos Namorados juntos...
          </h5>
        </div>
      </q-parallax>
    </q-card>

  </div>
  <div class="q-pa-md" style="max-width: 100%">
    <q-list bordered separator>

      <q-slide-item @top="onTop" @bottom="onBottom">
        <template v-slot:top>
          <iframe width="560" height="200" src="https://www.youtube.com/embed/d14uKw2yLtw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </template>
        <template v-slot:bottom>
          <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/287gGlV3G58XK8qiG2IyLK?utm_source=generator" width="100%" height="80" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"></iframe>
        </template>

        <q-item style="height: 220px">
          <q-item-section class="items-center" avatar>
            <q-avatar color="primary" text-color="white" icon="fingerprint" />
          </q-item-section>
          <q-item-section class="items-center">Arraste para cima ou para baixo.</q-item-section>
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
            Um mês de namoro. Nosso primeiro mês foi muito bom e que jamais vai ser esquecido, ali começamos coisas e que vimos que gostamos(amamos muitoooo) e que só deixou mais próximos e se amando muito. Primeira vez que veio em casa e confesso que estava nervoso e ansioso, trocamos nossos presentes, ficamos a vontade e depois ainda comemos batata frita perto da praia (Ameii o presente amor :) )          </p>
        </div>
      </q-timeline-entry>

      <q-timeline-entry
        title="Apresentção da menina Thays e conhecendo a mãe dela(Minha Sogra Sandra)"
        subtitle="04 de Dezembro, 2021"
        side="left"
      >
        <div>
          <p>
            Dia muito especial, começou indo ver a apresentação da Thays dançando fancy e pude conhecer a mãe dela, Fui para Campo Grande esse dia para ficar o máximo de tempo com ela.(Quase tinha esquecido conheci os amigos dela também kkkkk)          </p>
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
            Tive a oportunidade de passar esse aniversario contigo e dormir aí na sua casa a primeira vez, esse seu aniversário acredito eu que tenha sido bem incomum e inesperado, estarei em muitos e muitos aniversários seus, obrigado pela por me deixar fazer parte disso.          </p>
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
          <p>
            Ano novo foi a primeira vez que você dormiu la em casa e ficou uns dias, já começamos um novo ano juntos e da melhor forma possível, não tinha jeito melhor para começar o ano vendo fogos contigo.          </p>
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
          <p>
            Primeira vez no outback e comemos e bebemos muito kkkkk, foi um fim de semana divertido, pois fomos ficar em um lugar muito especial pela primeira vez(ramada)          </p>
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
          <p>
            Esse dia estávamos muito animados e bem lindos, fomos la starbucks e passeamos bastante no barra shopping.
          </p>
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
          <p>
            Dia muito nervoso meu deusss, tinhamos brigado um dia antes e estamos em um clima muito estranho, a minha família foi apresentada para sua e minha mãe amou todos da sua família, conseguimos nos resolver e ficar de boas e o dia foi maravilhoso.
          </p>
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
          <p>
            Dia em que começamos a usar a aliança e fomos a pria juntinhos e tava um frio danado.
          </p>
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
          Esse dia só o final dele foi meio M kkk, mas que dia perfeito, eu tava tão feliz esse dia que você via na minha cara, obrigado por proporcionar isso amor.
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
          <p>
            Esse dia a gente tava longe, mas mesmo assim não deixamos de fazer nossa comemoração e dar nossos presentes, teve até montagem e vídeos.          </p>
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
          <p>
            Fiquei tão bêbado que misericórdia, e fomos até em uma baladinha de kpop kkkkkk, nunca achei que iria ir em uma vida. Eu mostrei o lado muito bêbado e nosso esse dia foi louco.          </p>
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
          <p>
            Minha primeira vez no zoológico, eu ameii nunca vi tanto animal diferente e foi um dia inteiro em que ficamos de amorzinho, só tava meio deserto e deu um medinho kkkkkkkk.          </p>
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
          <p>
            Filmão que a gente viu e lembro que no começo do relacionamento a gente já tinha visto ir lançar e agora foi no filme, e nossa até passei gel e meu deus esse dia a gente tava de roupa combinandoooo.          </p>
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
        </div>
      </q-timeline-entry>
      <q-timeline-entry
        title="Oitavo mês de namoro"
        subtitle="12 de junho, 2021"
        side="left"
      >
        <div>
          <p>
            Oitavo mês de namoro, caiu junto com o Dia dos Namorados e não tem coisa melhor, e ainda fim de semana, esse dia vai ser muito especial amor, oitavo mês e nossa como passou rápido em, Parabéns para nós meu amor.          </p>
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
          <q-card-section>
            <p>
              Com todo amor Lucas Felipe Da Silva Kristiansen, Obrigado por fazer parte da minha vida.
            </p>
          </q-card-section>
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
      }, 3000)
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
