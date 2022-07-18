<template>
  <div id="revista-darc">
    <header class="d-flex justify-content-between container pt-5">
      <div class="astronauta d-flex align-items-center">
        <b-img src="~/assets/img/astronauta-girl-power.svg"></b-img>
        <div>
          <h1 class="p-0 m-0">Vamos viajar?</h1>
          <p class="p-0 m-0">Escolha seu primeiro caminho</p>
        </div>
      </div>
      <div class="logo-sections">
        <LogoSections />
      </div>
    </header>
    <main class="container">
      <section id="menu" class="d-flex mx-auto">
        <div id="menu-mulheres">
          <NuxtLink to="#mulheres-importantes"
            ><div
              class="
                mulheres-importantes
                d-flex
                justify-content-center
                align-items-center">
              <h2 class="text-center">
                MULHERES<br /><span>IMPORTANTES</span>
              </h2>
              <div class="shadow m-shadow position-absolute"></div></div
          ></NuxtLink>
        </div>
        <div id="menu-linha-do-tempo">
          <NuxtLink to="#linha-do-tempo">
          <div
            class="
              linha-do-tempo
              d-flex
              justify-content-center
              align-items-center
            "
          >
            <h2>LINHA DO<span>TEMPO</span></h2>
            <div class="shadow l-shadow position-absolute"></div>
          </div>
          </NuxtLink>
        </div>
        <div id="menu-voce-ja-viu">
          <NuxtLink to="#voce-ja-viu">
            <div
              class="
                voce-ja-viu
                d-flex
                justify-content-center
                align-items-center
              "
            >
              <h2>
                VOCÊ JÁ <br /><span class="d-flex justify-content-center"
                  >VIU?</span
                >
              </h2>
              <div class="shadow v-shadow position-absolute"></div>
            </div>
          </NuxtLink>
        </div>
        <div id="menu-jogo-e-mundo">
          <div
            class="
              jogo-e-mundo
              d-flex
              justify-content-center
              align-items-center
            "
          >
            <h2>JOGO & <span>MUNDO</span></h2>
            <div class="shadow j-shadow position-absolute"></div>
          </div>
        </div>
      </section>
      <BotaoVoltar />

      <section id="mulheres-importantes">
        <div class="header d-flex justify-content-between">
          <LogoSections />
          <b-nav class="menu"> </b-nav>
        </div>
        <Flicking :options="{ circular: true }" :plugins="plugins">
          <div class="mulheres mr-5">
            <b-img src="~/assets/img/joana.svg"></b-img>
            <div class="shadow-foto position-absolute"></div>
          </div>
          <div class="flicking-panel" style="max-width: 300px; height: auto">
            <h1>Joana d'Arc</h1>
            <p class="text-justify mr-5">
              Não existem muitos dados sobre a vida da esposa de Zumbi dos
              Palmares. Sua figura é envolta de incertezas. Dizem que viveu no
              Brasil Colonial e foi descrita como uma guerreira valente, que
              dominava técnicas de capoeira e teria lutado muitas batalhas para
              preservar o Quilombo dos Palmares. Inclusive teria auxiliado Zumbi
              em estratégias e planos de ataque e defesa.
            </p>
            <p class="text-justify mr-5">
              Não existem muitos dados sobre a vida da esposa de Zumbi dos
              Palmares. Sua figura é envolta de incertezas. Dizem que viveu no
              Brasil Colonial e foi descrita como uma guerreira valente, que
              dominava técnicas de capoeira e teria lutado muitas batalhas para
              preservar o Quilombo dos Palmares. Inclusive teria auxiliado Zumbi
              em estratégias e planos de ataque e defesa.
            </p>
            <p class="text-justify mr-5">
              Não existem muitos dados sobre a vida da esposa de Zumbi dos
              Palmares. Sua figura é envolta de incertezas. Dizem que viveu no
              Brasil Colonial e foi descrita como uma guerreira valente, que
              dominava técnicas de capoeira e teria lutado muitas batalhas para
              preservar o Quilombo dos Palmares. Inclusive teria auxiliado Zumbi
              em estratégias e planos de ataque e defesa.
            </p>
          </div>
          <div class="mulheres mr-5">
            <b-img src="~/assets/img/joana.svg"></b-img>
            <div class="shadow-foto position-absolute"></div>
          </div>
          <div class="flicking-panel" style="max-width: 300px; height: auto">
            <h1>Joana d'Arc</h1>
            <p class="text-justify">
              Não existem muitos dados sobre a vida da esposa de Zumbi dos
              Palmares. Sua figura é envolta de incertezas. Dizem que viveu no
              Brasil Colonial e foi descrita como uma guerreira valente, que
              dominava técnicas de capoeira e teria lutado muitas batalhas para
              preservar o Quilombo dos Palmares. Inclusive teria auxiliado Zumbi
              em estratégias e planos de ataque e defesa.
            </p>
          </div>
          <span slot="viewport" class="flicking-arrow-prev is-circle"></span>
          <span slot="viewport" class="flicking-arrow-next is-circle"></span>
        </Flicking>
      </section>
      <BotaoVoltar class="my-5" />
      <section id="voce-ja-viu">
        <div class="header d-flex justify-content-between">
          <LogoSections />
          <b-nav class="menu"> </b-nav>
        </div>
        <h1 class="vc-ja-viu-titulo text-right">
          <span class="bg">Filmes</span> e <span>séries</span> que<br />
          fazem a <span class="circulo">diferença</span>
        </h1>
        <Flicking
          :options="{ circular: true }"
          :plugins="plugins2"
          class="pb-5"
        >
          <div class="conteudo">
            <b-img src="~/assets/img/radioative.png" width="300px"></b-img>
            <div class="shadow shadow-filmes position-absolute"></div>
          </div>
          <div style="max-width: 400px">
            <h1>Radioatividade</h1>
            <p>
              Não existem muitos dados sobre a vida da esposa de Zumbi dos
              Palmares. Sua figura é envolta de incertezas. Dizem que viveu no
              Brasil Colonial e foi descrita como uma guerreira valente, que
              dominava técnicas de capoeira e teria lutado muitas batalhas para
              preservar o Quilombo dos Palmares. Inclusive teria auxiliado Zumbi
              em estratégias e planos de ataque e defesa.
            </p>
          </div>
          <div class="conteudo">
            <b-img src="~/assets/img/radioative.png" width="300px"></b-img>
            <div class="shadow-filmes position-absolute"></div>
          </div>
          <div style="max-width: 400px">
            <h1>Radioatividade</h1>
            <p>
              Não existem muitos dados sobre a vida da esposa de Zumbi dos
              Palmares. Sua figura é envolta de incertezas. Dizem que viveu no
              Brasil Colonial e foi descrita como uma guerreira valente, que
              dominava técnicas de capoeira e teria lutado muitas batalhas para
              preservar o Quilombo dos Palmares. Inclusive teria auxiliado Zumbi
              em estratégias e planos de ataque e defesa.
            </p>
          </div>

          <span slot="viewport" class="flicking-arrow-prev is-circle"></span>
          <span slot="viewport" class="flicking-arrow-next is-circle"></span>
        </Flicking>
        <BotaoVoltar class="my-5" />
        <div class="imagem-fundo-musicas">
          <div class="libras d-flex justify-content-end">
            <b-img src="~/assets/img/libras-estatico.png"></b-img>
          </div>
          <div class="titulo-musica-delas d-flex justify-content-end">
            <h1 class="text-right font-weight-bolder">
              Músicas<br />
              Delas
            </h1>
          </div>
          <div style="width: 600px; margin-inline: auto" class="pb-5">
            <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/0F3K3GsErK9hNB83gXRMzx?utm_source=generator&theme=0" width="100%" height="380" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"></iframe>
          </div>
          <BotaoVoltar class="my-5" />
          <h1 class="pt-5 text-right w-50">
            Artistas que<br />
            inspiram
          </h1>
          <div class="fundo-artistas">
            <Flicking
              class="w-100 mx-auto"
              :options="{ horizontal: false }"
              @ready="updateTransform"
              @move="updateTransform"
            >
              <div class="d-flex mx-auto">
                <div class="foto-artistas">
                  <b-img
                    class="mt-5"
                    src="~/assets/img/artistas-que-inspiram-1.svg"
                  ></b-img>
                </div>
                <div class="shadow shadow-artistas position-absolute"></div>
                <div style="max-width: 300px; margin-inline: 30px">
                  <h1>Joana d’Arc</h1>
                  <p>
                    Não existem muitos dados sobre a vida da esposa de Zumbi dos
                    Palmares. Sua figura é envolta de incertezas. Dizem que
                    viveu no Brasil Colonial e foi descrita como uma guerreira
                    valente, que dominava técnicas de capoeira e teria lutado
                    muitas batalhas para preservar o Quilombo dos Palmares.
                    Inclusive teria auxiliado Zumbi em estratégias e planos de
                    ataque e defesa.
                  </p>
                </div>
              </div>

              <div class="d-flex mx-auto">
                <div class="foto-artistas">
                  <b-img
                    class="mt-5"
                    src="~/assets/img/artistas-que-inspiram-1.svg"
                  ></b-img>
                </div>
                <div class="shadow shadow-artistas position-absolute"></div>
                <div style="max-width: 300px; margin-inline: 30px">
                  <h1>Joana d’Arc</h1>
                  <p>
                    Não existem muitos dados sobre a vida da esposa de Zumbi dos
                    Palmares. Sua figura é envolta de incertezas. Dizem que
                    viveu no Brasil Colonial e foi descrita como uma guerreira
                    valente, que dominava técnicas de capoeira e teria lutado
                    muitas batalhas para preservar o Quilombo dos Palmares.
                    Inclusive teria auxiliado Zumbi em estratégias e planos de
                    ataque e defesa.
                  </p>
                </div>
              </div>
            </Flicking>
            <BotaoVoltar class="ml-1 mt-5" />
            <div class="libras d-flex justify-content-end">
              <b-img src="~/assets/img/libras-estatico.png"></b-img>
            </div>
            <div class="fundo-escritoras">
              <div class="escritoras-seta w-50 ml-5 d-flex mb-5">
                <h1 class="text-left">Escritoras Extraordinárias</h1>
                <svg
                  width="114"
                  height="237"
                  viewBox="0 0 114 237"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <g filter="url(#filter0_d_174_25)">
                    <path
                      d="M6 2C54.7501 2 108.348 26.7948 107.998 81.5575C107.754 119.767 55.0695 127.969 34.6364 99.4931C28.9075 91.509 28.5441 80.6844 41.0113 81.7579C58.1704 83.2354 74.883 98.1882 84.7249 111.116C111.349 146.088 64.666 174.744 51.535 204"
                      stroke="white"
                      stroke-width="3"
                      stroke-linecap="round"
                    />
                    <path
                      d="M41 183C42.2442 193.164 45.315 203.33 46.328 213.362C46.4554 214.624 46.0148 227 46.8307 227C49.6673 227 58.3379 211.851 60 209.778C65.2682 203.209 69.7295 195.543 79 195.543"
                      stroke="white"
                      stroke-width="3"
                      stroke-linecap="round"
                    />
                  </g>
                  <defs>
                    <filter
                      id="filter0_d_174_25"
                      x="0.5"
                      y="0.5"
                      width="113"
                      height="236"
                      filterUnits="userSpaceOnUse"
                      color-interpolation-filters="sRGB"
                    >
                      <feFlood flood-opacity="0" result="BackgroundImageFix" />
                      <feColorMatrix
                        in="SourceAlpha"
                        type="matrix"
                        values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
                        result="hardAlpha"
                      />
                      <feOffset dy="4" />
                      <feGaussianBlur stdDeviation="2" />
                      <feComposite in2="hardAlpha" operator="out" />
                      <feColorMatrix
                        type="matrix"
                        values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
                      />
                      <feBlend
                        mode="normal"
                        in2="BackgroundImageFix"
                        result="effect1_dropShadow_174_25"
                      />
                      <feBlend
                        mode="normal"
                        in="SourceGraphic"
                        in2="effect1_dropShadow_174_25"
                        result="shape"
                      />
                    </filter>
                  </defs>
                </svg>
              </div>
              <Flicking
                :options="{
                  circular: true,
                  horizontal: true,
                  useFractionalSize: true,
                }"
              >
                <div
                  class="
                    shadow
                    d-flex
                    align-items-center
                    justify-content-center
                    mx-auto
                    w-75
                    pb-5
                    overflow-hidden
                  "
                  style="
                    background-color: aliceblue;
                    border-radius: 40px;
                    z-index: 1;
                    position: relative;
                  "
                >
                  <div
                    class=""
                    style="
                      width: 200px;
                      height: 200px;
                      border-radius: 100%;
                      background-color: black;
                    "
                  ></div>
                  <div class="mt-5 ml-4">
                    <h2 style="color: black">Joana D'arc</h2>
                    <b-img
                      src="~/assets/img/capa-livro.png"
                      width="200px"
                    ></b-img>
                  </div>
                </div>
                <div
                  class="
                    shadow
                    d-flex
                    align-items-center
                    justify-content-center
                    mx-auto
                    w-75
                    pb-5
                    overflow-hidden
                  "
                  style="
                    background-color: aliceblue;
                    border-radius: 40px;
                    z-index: 1;
                    position: relative;
                  "
                >
                  <div
                    class=""
                    style="
                      width: 200px;
                      height: 200px;
                      border-radius: 100%;
                      background-color: black;
                    "
                  ></div>
                  <div class="mt-5 ml-4">
                    <h2 style="color: black">Joana D'arc</h2>
                    <b-img
                      src="~/assets/img/capa-livro.png"
                      width="200px"
                    ></b-img>
                  </div>
                </div>
              </Flicking>
              <div
                class="
                  shadow
                  d-flex
                  align-items-center
                  justify-content-center
                  w-75
                  pb-5
                "
                style="
                  background-color: yellow;
                  border-radius: 40px;
                  height: 420px;
                  margin-top: -400px;
                  margin-left: 80px;
                  z-index: 0;
                  position: relative;
                "
              ></div>
              <BotaoVoltar class="mt-5" />
            </div>
          </div>
        </div>
      </section>
      <section id="linha-do-tempo">
        <div class="libras d-flex justify-content-end"><b-img src="~/assets/img/libras-estatico.png"></b-img></div>
        <div>
  <b-tabs content-class="mt-3" justified>
    <b-tab title="1827" active>
       <div
          class="
            shadow
            d-flex
            align-items-center
            justify-content-center
            mx-auto
            w-100
            pb-5
            overflow-hidden
          "
          style="
            background-color: #f7134d;
            border-radius: 40px;
            z-index: 1;
            height: 30rem;
            position: relative;
          "
        >
          <div
            class="ano font-weight-bolder mr-2"
            style="width: 120px; font-size: 80px"
          >
            <p>18<br />27</p>
          </div>
          <div class="texto mr-2" style="max-width: 300px">
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Esse ad
              mollitia fugiat nobis corrupti veritatis provident ratione amet
              nostrum nihil delectus minima, similique eligendi natus beatae
              laborum magnam asperiores aspernatur.
            </p>
          </div>
          <div
            class="imagem"
            style="
              background: black;
              border-radius: 100%;
              width: 200px;
              height: 200px;
            "
          ></div>
        </div>
       <div
          class="
            shadow
            d-flex
            align-items-center
            justify-content-center
            mx-auto
            w-100
            pb-5
            overflow-hidden
          "
          style="
            background-color: #2A0F82;
            border-radius: 40px;
            z-index: 1;
            height: 30rem;
            position: relative;
            margin-top:-100px;
          "
        >
          <div
            class="ano font-weight-bolder mr-2"
            style="width: 120px; font-size: 80px"
          >
            <p>18<br />27</p>
          </div>
          <div class="texto mr-2" style="max-width: 300px">
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Esse ad
              mollitia fugiat nobis corrupti veritatis provident ratione amet
              nostrum nihil delectus minima, similique eligendi natus beatae
              laborum magnam asperiores aspernatur.
            </p>
          </div>
          <div
            class="imagem"
            style="
              background: black;
              border-radius: 100%;
              width: 200px;
              height: 200px;
            "
          ></div>
        </div>
               <div
          class="
            shadow
            d-flex
            align-items-center
            justify-content-center
            mx-auto
            w-100
            pb-5
            overflow-hidden
          "
          style="
            background-color: #FED616;
            border-radius: 40px;
            z-index: 1;
            height: 30rem;
            position: relative;
            margin-top:-100px;
          "
        >
          <div
            class="ano font-weight-bolder mr-2"
            style="width: 120px; font-size: 80px"
          >
            <p>18<br />27</p>
          </div>
          <div class="texto mr-2" style="max-width: 300px">
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Esse ad
              mollitia fugiat nobis corrupti veritatis provident ratione amet
              nostrum nihil delectus minima, similique eligendi natus beatae
              laborum magnam asperiores aspernatur.
            </p>
          </div>
          <div
            class="imagem"
            style="
              background: black;
              border-radius: 100%;
              width: 200px;
              height: 200px;
            "
          ></div>
        </div>
        <div
          class="
            shadow
            d-flex
            align-items-center
            justify-content-center
            mx-auto
            w-100
            pb-5
            overflow-hidden
          "
          style="
            background-color: #4BD4FE;
            border-radius: 40px;
            z-index: 1;
            height: 30rem;
            position: relative;
            margin-top:-100px;
          "
        >
          <div
            class="ano font-weight-bolder mr-2"
            style="width: 120px; font-size: 80px"
          >
            <p>18<br />27</p>
          </div>
          <div class="texto mr-2" style="max-width: 300px">
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Esse ad
              mollitia fugiat nobis corrupti veritatis provident ratione amet
              nostrum nihil delectus minima, similique eligendi natus beatae
              laborum magnam asperiores aspernatur.
            </p>
          </div>
          <div
            class="imagem"
            style="
              background: black;
              border-radius: 100%;
              width: 200px;
              height: 200px;
            "
          ></div>
        </div>
               <div
          class="
            shadow
            d-flex
            align-items-center
            justify-content-center
            mx-auto
            w-100
            pb-5
            overflow-hidden
          "
          style="
            background-color: #2A0F82;
            border-radius: 40px;
            z-index: 1;
            height: 30rem;
            position: relative;
            margin-top:-100px;
          "
        >
          <div
            class="ano font-weight-bolder mr-2"
            style="width: 120px; font-size: 80px"
          >
            <p>18<br />27</p>
          </div>
          <div class="texto mr-2" style="max-width: 300px">
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Esse ad
              mollitia fugiat nobis corrupti veritatis provident ratione amet
              nostrum nihil delectus minima, similique eligendi natus beatae
              laborum magnam asperiores aspernatur.
            </p>
          </div>
          <div
            class="imagem"
            style="
              background: black;
              border-radius: 100%;
              width: 200px;
              height: 200px;
            "
          ></div>
        </div>
    </b-tab>
    <b-tab title="1910"> <div
          class="
            shadow
            d-flex
            align-items-center
            justify-content-center
            mx-auto
            w-100
            pb-5
            overflow-hidden
          "
          style="
            background-color: #f7134d;
            border-radius: 40px;
            z-index: 1;
            height: 30rem;
            position: relative;
          "
        >
          <div
            class="ano font-weight-bolder mr-2"
            style="width: 120px; font-size: 80px"
          >
            <p>18<br />27</p>
          </div>
          <div class="texto mr-2" style="max-width: 300px">
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Esse ad
              mollitia fugiat nobis corrupti veritatis provident ratione amet
              nostrum nihil delectus minima, similique eligendi natus beatae
              laborum magnam asperiores aspernatur.
            </p>
          </div>
          <div
            class="imagem"
            style="
              background: black;
              border-radius: 100%;
              width: 200px;
              height: 200px;
            "
          ></div>
        </div></b-tab>
    <b-tab title="2002"> <div
          class="
            shadow
            d-flex
            align-items-center
            justify-content-center
            mx-auto
            w-100
            pb-5
            overflow-hidden
          "
          style="
            background-color: #f7134d;
            border-radius: 40px;
            z-index: 1;
            height: 30rem;
            position: relative;
          "
        >
          <div
            class="ano font-weight-bolder mr-2"
            style="width: 120px; font-size: 80px"
          >
            <p>18<br />27</p>
          </div>
          <div class="texto mr-2" style="max-width: 300px">
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Esse ad
              mollitia fugiat nobis corrupti veritatis provident ratione amet
              nostrum nihil delectus minima, similique eligendi natus beatae
              laborum magnam asperiores aspernatur.
            </p>
          </div>
          <div
            class="imagem"
            style="
              background: black;
              border-radius: 100%;
              width: 200px;
              height: 200px;
            "
          ></div>
        </div></b-tab>
    <b-tab title="2010"> <div
          class="
            shadow
            d-flex
            align-items-center
            justify-content-center
            mx-auto
            w-100
            pb-5
            overflow-hidden
          "
          style="
            background-color: #f7134d;
            border-radius: 40px;
            z-index: 1;
            height: 30rem;
            position: relative;
          "
        >
          <div
            class="ano font-weight-bolder mr-2"
            style="width: 120px; font-size: 80px"
          >
            <p>18<br />27</p>
          </div>
          <div class="texto mr-2" style="max-width: 300px">
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Esse ad
              mollitia fugiat nobis corrupti veritatis provident ratione amet
              nostrum nihil delectus minima, similique eligendi natus beatae
              laborum magnam asperiores aspernatur.
            </p>
          </div>
          <div
            class="imagem"
            style="
              background: black;
              border-radius: 100%;
              width: 200px;
              height: 200px;
            "
          ></div>
        </div></b-tab>
  </b-tabs>
</div>
       
       
      </section>
    </main>
  </div>
</template>

<script>
import { Flicking } from "@egjs/vue-flicking";
import LogoSections from "~/components/LogoSections.vue";
import BotaoVoltar from "../components/BotaoVoltar.vue";
import { Arrow } from "@egjs/flicking-plugins";
import "@egjs/flicking-plugins/dist/arrow.css";

import { Perspective } from "@egjs/flicking-plugins";

export default {
  components: { LogoSections, BotaoVoltar, Flicking: Flicking },
  methods: {
    updateTransform: (e) => {
      e.currentTarget.panels.forEach((panel) => {
        const rotateVal = -panel.progress * 20;
        const sinRot = Math.sin(Math.abs((rotateVal * Math.PI) / 180));
        const depth = 150 * sinRot * sinRot;
        panel.element.style.transform = `translateZ(-${depth}px) rotateX(${rotateVal}deg)`;
      });
    },
  },
  data() {
    return {
      plugins: [
        new Arrow(),
        new Perspective({ rotate: -1, scale: 2, perspective: 600 }),
      ],
      plugins2: [
        new Arrow(),
        new Perspective({ rotate: -1, scale: 2, perspective: 800 }),
      ],
    };
  },
};
</script>
<style scoped>
@keyframes grow-shrink2 {
  50% {
    transform: scale(1.3);
  }
}

@keyframes expand2 {
  50% {
    word-spacing: 20px;
  }
}
@keyframes translate2 {
  0% {
    transform: translateX(233px);
  }
  50% {
    transform: translateX(200px);
    transform: translateY(200px);
  }
  100% {
    transform: translateX(283px);
  }
}
@keyframes grow-shrink3 {
  50% {
    transform: scale(1.3);
  }
}

@keyframes expand3 {
  50% {
    word-spacing: 20px;
  }
}
@keyframes translate3 {
  0% {
    transform: translateX(433px);
  }
  50% {
    transform: translateX(500px);
    transform: translateY(10px);
  }
  100% {
    transform: translateX(300px);
  }
}
@keyframes grow-shrink4 {
  50% {
    transform: scale(1.3);
  }
}

@keyframes expand4 {
  50% {
    word-spacing: 20px;
  }
}
@keyframes translate4 {
  0% {
    transform: translateX(103px);
  }
  50% {
    transform: translateX(200px);
    transform: translateY(100px);
  }
  100% {
    transform: translateX(300px);
  }
}
@keyframes grow-shrink {
  50% {
    transform: scale(1.2);
  }
}

@keyframes expand {
  50% {
    word-spacing: 20px;
  }
}
@keyframes translate {
  0% {
    transform: translateX(233px);
  }
  50% {
    transform: translateX(100px);
    transform: translateY(200px);
  }
  100% {
    transform: translateX(233px);
  }
}

header {
  color: white;
  margin-bottom: 5.125rem;
}
.libras {
  margin-bottom: 8rem;
}

#menu {
  background-image: url("~/assets/img/vamos-viajar.png");
  background-size: contain;
  background-repeat: no-repeat;
  background-position: top;
  height: 22.52125rem;
}
#menu-mulheres,
#menu-jogo-e-mundo,
#menu-linha-do-tempo,
#menu-voce-ja-viu {
  height: 11.25rem;
  width: 11.25rem;
}
.mulheres-importantes {
  height: 11.25rem;
  width: 11.25rem;
  background: #4bd4fe;
  border-radius: 100%;
  animation-name: grow-shrink, expand, translate;
  animation-duration: 8s, 5s, 5s, 10s;
  animation-iteration-count: infinite;
}

a {
  text-decoration: none;
  color: #000000;
}

.m-shadow {
  width: 11.25rem;
  height: 11.25rem;
  border-radius: 100%;
  border-color: #4bd4fe;
  border-style: solid;
  margin-bottom: 1rem;
  margin-right: 0.75rem;
  border-width: 2px;
}

.mulheres-importantes h2 {
  font-size: 20px;
  font-weight: 900;
}
.mulheres-importantes span {
  font-weight: 500;
}
.voce-ja-viu {
  height: 11.25rem;
  width: 11.25rem;
  background: hsla(49, 100%, 53%, 1);
  border-radius: 100%;
  animation-name: grow-shrink2, expand2, translate2;
  animation-duration: 8s, 5s, 5s, 10s;
  animation-iteration-count: infinite;
}
.v-shadow {
  width: 11.25rem;
  height: 11.25rem;
  border-radius: 100%;
  border-color: hsla(49, 100%, 53%, 1);
  border-style: solid;
  margin-bottom: 1rem;
  margin-left: 0.75rem;
  border-width: 2px;
}
.voce-ja-viu h2 {
  font-size: 20px;
}
span {
  font-weight: 900;
}
span.bg {
  background: #2a0f82;
  border-radius: 20px;
  padding: 5px;
}
span.circulo {
  border: #ffffff solid 0.5px;
  font-weight: 600;
  border-radius: 50%;
}
.vc-ja-viu-titulo {
  margin-bottom: 11.0625rem;
}
.shadow-filmes {
  background-color: #4bd4fe;
  width: 18.75rem;
  height: 13.639375rem;
  border-radius: 40px;
  z-index: -1;
  padding-right: 20px;
  top: 10px;
}
.imagem-fundo-musicas {
  height: 116.5rem;
  width: 100%;
  background: url("~/assets/img/fundo-musicas.png");
  background-size: contain;
  background-repeat: no-repeat;
}
.titulo-musica-delas {
  color: #000000;
  margin-right: 12.5rem;
  background: url("~/assets/img/fundo-musica-delas.svg");
  background-repeat: no-repeat;
  background-position: right;
}
#voce-ja-viu {
  z-index: -99;
}
.fundo-artistas {
  width: 100%;
  height: 140.375rem;
  background: url("~/assets/img/fundo-artistas.svg");
}
.fundo-artistas svg:hover path {
  fill: black;
}
.foto-artistas {
  margin-left: 2rem;
  z-index: 99;
}
.shadow-artistas {
  width: 300px;
  height: 300px;
  border-radius: 100%;
  background-color: #ffd310;
  margin-top: -2px;
  margin-left: 1.7rem;
  z-index: -1;
}
.fundo-escritoras {
  background: url("~/assets/img/fundo-escritoras.png");
  background-size: contain;
  background-repeat: no-repeat;
  height: 119rem;
  width: 100%;
}
.escritoras-seta svg:hover path {
  stroke: #ffd310;
}
.jogo-e-mundo {
  height: 11.25rem;
  width: 11.25rem;
  background: #7b07d6 !important;
  border-radius: 100%;
  animation-name: grow-shrink2, expand2, translate2;
  animation-duration: 8s, 5s, 5s, 10s;
  animation-iteration-count: infinite;
}
.jogo-e-mundo h2 {
  font-size: 20px;
}
.j-shadow {
  width: 11.25rem;
  height: 11.25rem;
  border-radius: 100%;
  border-color: #7b07d6;
  border-style: solid;
  margin-top: 1rem;
  margin-left: 0.75rem;
  border-width: 2px;
}
#linha-do-tempo {
  margin-top: 120rem;
}

.linha-do-tempo {
  height: 11.25rem;
  width: 11.25rem;
  background: #f7134d;
  border-radius: 100%;
  animation-name: grow-shrink3, expand3, translate3;
  animation-duration: 8s, 5s, 5s, 10s;
  animation-iteration-count: infinite;
}
.jogo-e-mundo{
   height: 11.25rem;
  width: 11.25rem;
  background: #f7134d;
  border-radius: 100%;
  animation-name: grow-shrink4, expand4, translate4;
  animation-duration: 8s, 5s, 5s, 10s;
  animation-iteration-count: infinite;
}

.linha-do-tempo h2 {
  font-size: 20px;
}
.l-shadow {
  width: 11.25rem;
  height: 11.25rem;
  border-radius: 100%;
  border-color: #f7134d;
  border-style: solid;
  margin-top: 1rem;
  margin-left: 0.75rem;
  border-width: 2px;
}
#mulheres-importantes {
  margin-top: 17.15rem;
}

.header {
  margin-bottom: 4.6875rem;
}
.menu {
  width: 263px;
  height: 147.12px;
  background-color: aliceblue;
}
.mulheres {
  top: -20px;
}
/* .shadow-foto {
  position: absolute;
  width: 12.8125rem;
  height: 12.8125rem;
  border-radius: 100%;
  left: 200px;
  top: 70px;
  background: #2a0f82;
  z-index: -1;
} */
.shadow-foto {
  width: 12.8125rem;
  height: 12.8125rem;
  border-radius: 100%;
  background: #7b07d6;
  top: 8px;
  left: -20px;
  z-index: -1;
}
.voce-ja-viu-titulo {
  font-weight: 600;
}

/* ---------------------------------FLICKING STYLE---------------------------------*/

@media only screen and (max-width: 600px) {
  main,
  header {
    max-width: 320px;
    width: auto;
    padding-inline: 1.5rem;
    margin: 0;
  }
  .mulheres-importantes,
  .m-shadow,
  .voce-ja-viu,
  .v-shadow,
  .jogo-e-mundo,
  .j-shadow,
  .linha-do-tempo,
  .l-shadow {
    font-size: 1rem;
    width: 5rem;
    height: 5rem;
  }
}
</style>