<script setup>
// import { RouterLink, RouterView } from "vue-router";
// import HelloWorld from "./components/HelloWorld.vue";
import { MailOutlined, TwitterOutlined } from "@ant-design/icons-vue";
</script>

<template>
  <a-layout class="layout">
    <a-layout-header>
      <!-- <h2 class="headerText">Astrid van den Brandt</h2> -->
    </a-layout-header>
    <a-layout-content>
      <a-row type="flex" justify="space-between" align="middle">
        <a-col :span="7">
          <div style="text-align: center">
            <img src="../astrid.png" width="250" height="250" />
          </div>
        </a-col>
        <a-col :span="16">
          <h2 class="headerText">Astrid van den Brandt</h2>
          <p>
            I am a PhD student in
            <span class="highlightme">Data Visualization</span> at the
            Department of Mathematics and Computer Science of Eindhoven
            University of Technology, and in close collaboration with the
            Bioinformatics Group of Wageningen University, The Netherlands. I am
            advised by Anna Vilanova and Sandra Smit.
          </p>
          <p>
            My research focuses on designing interactive visualizations to
            support genomics experts in their exploratory
            <span class="highlightme">pangenomics</span> analyses. I make use of
            design thinking methodology, collaborative methods and analytics to
            understand complex problems and create effective solutions.
          </p>
          <p>
            I obtained an MSc in Data Science and a BSc in Industrial Design
            from Eindhoven University of Technology. Michel Westenberg mentored
            me on my Master's thesis, and I was a visiting scholar at UC San
            Diego's Computational Ophthalmology Group.
          </p>
        </a-col>
      </a-row>
      <a-divider orientation="left" class="no-border">
        <h4>Contact</h4>
      </a-divider>
      <a-row type="flex" justify="flex-start" align="middle">
        <div style="padding-left: 5%">
          <div
            style="
              display: flex;
              flex-wrap: nowrap;
              justify-content: flex-start;
              align-items: baseline;
            "
          >
            <div style="padding-left: 16px; padding-right: 10px">
              <MailOutlined />
            </div>
            <p style="margin: 0px">a.v.d.brandt[at]tue.nl</p>
          </div>
          <div
            style="
              display: flex;
              flex-wrap: nowrap;
              justify-content: flex-start;
              align-items: baseline;
            "
          >
            <div style="padding-left: 16px; padding-right: 10px">
              <TwitterOutlined />
            </div>
            <p>@astrid_vdbrandt</p>
          </div>
        </div>
      </a-row>
      <a-divider orientation="left">
        <h4>Publications</h4>
      </a-divider>
      <a-row type="flex" justify="space-between" align="top">
        <a-col :span="7">
          <div style="flex">
            <p style="float: right">2022</p>
          </div>
        </a-col>
        <a-col :span="16">
          <div style="flex">
            <p>
              <b>PanVA: Variant Analysis within Pangenomes</b> <br />
              <span class="author">van den Brandt, A.</span>, Jonkheer, E., van
              Workum, D. J., van de Wetering, H., Smit, S., & Vilanova, A.
              <br />
              <i
                >Submitted to IEEE Transactions on Visualization and Computer
                Graphics</i
              ><br />
              <a
                class="orange"
                href="https://www.techrxiv.org/articles/preprint/PanVA_Variant_Analysis_within_Pangenomes/21572433"
                target="_blank"
                >[preprint]</a
              >
              <a
                class="orange"
                href="https://www.bioinformatics.nl/pangenomics/vapp/"
                target="_blank"
                >[website]</a
              >
            </p>
          </div>
        </a-col>
      </a-row>
      <a-row type="flex" justify="space-between" align="top">
        <a-col :span="7">
          <div style="flex">
            <p style="float: right"></p>
          </div>
        </a-col>
        <a-col :span="16">
          <div style="flex">
            <p>
              <b
                >Visual Exploration of Genetic Sequence Variants in
                Pangenomes</b
              >
              <br />
              <span class="author">van den Brandt, A.</span>, Jonkheer, E., van
              Workum, D. J., van de Wetering, H., Smit, S., & Vilanova, A.
              <br />
              <i>Proceedings of EuroVis (Posters), 2022.</i><br />
              <a
                class="orange"
                href="https://diglib.eg.org/handle/10.2312/evp20221112"
                target="_blank"
                >[abstract]</a
              >
              🏆 Best Poster Award at EuroVis 2022
            </p>
          </div>
        </a-col>
      </a-row>
      <a-row type="flex" justify="space-between" align="top">
        <a-col :span="7">
          <div style="flex">
            <p style="float: right"></p>
          </div>
        </a-col>
        <a-col :span="16">
          <div style="flex">
            <p>
              <b
                >Usability and Clinician Acceptance of a Deep Learning- based
                Clinical Decision Support Tool for Predicting Glaucomatous
                Visual Field Progression</b
              >
              <br />
              Jimmy S. Chen, Sally L. Baxter,
              <span class="author">Astrid van den Brandt</span>, Alexander Lieu,
              Andrew S. Camp, Jiun L. Do, Derek S. Welsbie, Sasan Moghimi, Mark
              Christopher, Robert N. Weinreb, Linda Zangwill <br />
              <i>Accepted at Journal of Glaucoma, 2023</i>
            </p>
          </div>
        </a-col>
      </a-row>
      <a-row type="flex" justify="space-between" align="top">
        <a-col :span="7">
          <div style="flex">
            <p style="float: right">2020</p>
          </div>
        </a-col>
        <a-col :span="16">
          <div style="flex">
            <p>
              <b
                >GLANCE : Visual Analytics for Monitoring Glaucoma
                Progression</b
              >
              <br />
              <span class="author">van den Brandt, A.</span>, Christopher, M.,
              Zangwill, L. M., Rezapour, J., Bowd, C., Baxter, S. L., Derek, S.,
              Camp, A., Moghimi, S., Do, J. L., Weinreb, R. N., Snijders, C. C.
              P., & Westenberg, M. A. <br />
              <i
                >Proceedings of EuroGraphics Workshop on Visual Computing for
                Biology & Medicine (VCBM), 2020</i
              ><br />
              <a
                class="orange"
                href="https://diglib.eg.org/handle/10.2312/vcbm20201175"
                target="_blank"
                >[paper]</a
              >
              🏆 Best Full Paper Award at VCBM 2020
            </p>
          </div>
        </a-col>
      </a-row>
      <a-divider orientation="left">
        <h4>Awards</h4>
      </a-divider>
      <a-row type="flex" justify="space-between" align="top">
        <a-col :span="7">
          <div style="flex">
            <p style="float: right">2022</p>
          </div>
        </a-col>
        <a-col :span="16">
          <div style="flex">
            <p>Best Poster Award. EuroVis Conference, Rome, Italy. 2022.</p>
          </div>
        </a-col>
      </a-row>
      <a-row type="flex" justify="space-between" align="top">
        <a-col :span="7">
          <div style="flex">
            <p style="float: right"></p>
          </div>
        </a-col>
        <a-col :span="16">
          <div style="flex">
            <p>
              Best Demo Award. ICT Open Conference, Amsterdam, The Netherlands.
              2022.
            </p>
          </div>
        </a-col>
      </a-row>
      <a-row type="flex" justify="space-between" align="top">
        <a-col :span="7">
          <div style="flex">
            <p style="float: right">2020</p>
          </div>
        </a-col>
        <a-col :span="16">
          <div style="flex">
            <p>Best Paper Award. VCBM Conference, 2020.</p>
          </div>
        </a-col>
      </a-row>
    </a-layout-content>
  </a-layout>
  <a-layout-footer>© 2023 Astrid van den Brandt</a-layout-footer>
</template>

<style scoped>
.ant-layout {
  background: white !important;
  padding: 0 50px;
}

.ant-layout-header {
  height: 63px;
  padding: 0;
  color: rgba(0, 0, 0, 0.85);
  line-height: 64px;
  /* background: rgb(240, 242, 245) !important; */
  background: #fff !important;
  width: 100%;
}

.ant-layout-footer {
  /* background: #fff !important; */
  background: #f8f8f8 !important;
  text-align: center;
}

.headerText {
  font-weight: 600 !important;
}

.no-border {
  border-top-color: rgba(0, 0, 0, 0) !important;
  margin: 0px 0 !important;
}

.author {
  text-decoration: underline;
  margin: 0px;
}

header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

/* @media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;

    padding: 1rem 0;
    margin-top: 1rem;
  }
} */
</style>
