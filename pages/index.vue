<template>
  <div class="pb-8 md:pb-24 lg:pb-48">
    <div
      class="testimonials text-center min-h-full flex flex-col justify-center items-center"
    >
      <h1 class="head-super text-4xl md:text-7xl mb-4">Veřejná karta soudce</h1>
      <cite class="head-alt text-xl md:text-2xl max-w-4xl"
        >„Lze souhlasit, že jistá podoba tzv. karty soudce obsahující kupříkladu
        profesní životopis a anonymizovaná rozhodnutí by mohla mít pozitivní
        vliv na transparentnost systému.“</cite
      >
      <p class="mt-2 text-lg md:text-xl">prof. Pavel Šámal, předseda Nejvyššího soudu</p>
    </div>
    <div class="flex flex-row">
      <no-ssr>
        <aside class="w-1/4 hidden md:block">
          <affix class="toc w-1/4" relative-element-selector="#profile-sections" style="width: 300px">
            <scrollactive>
              <ul class="profile-navbar">
                <li class="profile-navbar-item"><a class="scrollactive-item" href="#personal-data">Osobní údaje</a></li>
                <li class="profile-navbar-item"><a class="scrollactive-item" href="#decision-speed">Rychlost rozhodování</a></li>
                <li class="profile-navbar-item"><a class="scrollactive-item" href="#major-decisions">Významná rozhodnutí</a></li>
                <li class="profile-navbar-item"><a class="scrollactive-item" href="#disciplinary-offenses">Kárná provinění</a></li>
                <li class="profile-navbar-item"><a class="scrollactive-item" href="#other">Další data</a></li>
              </ul>
            </scrollactive>
          </affix>
        </aside>
      </no-ssr>
      <content id="profile-sections" class="md:border-l border-brand-graylight md:pl-8 md:w-3/4">
        <section class="profile-section text-xl" id="personal-data">
          <h1 class="profile-section-headline">Osobní údaje</h1>
          <div class="flex flex-col-reverse lg:flex-row">
            <div class="lg:w-2/3">
              <div class="personal-data-item">
                <div class="personal-data-label">Soudkyně:</div>
                <div class="personal-data-value">JUDr. Helena Králová, nar. 12. 8. 1951</div>
              </div>
              <div class="personal-data-item">
                <div class="personal-data-label">Působiště:</div>
                <div class="personal-data-value">Obvodní soud pro Prahu 1</div>
              </div>
              <div class="personal-data-item">
                <div class="personal-data-label">Funkce:</div>
                <div class="personal-data-value">místopředsedkyně OS Praha 1</div>
              </div>
              <div class="personal-data-item">
                <div class="personal-data-label">Soudkyní je od:</div>
                <div class="personal-data-value">1975 (OS Cheb)</div>
              </div>
              <div class="personal-data-item">
                <div class="personal-data-label">Jmenována:</div>
                <div class="personal-data-value">
                  1990; na návrh ministra JUDr. Richtera (OF), projednala Česká
                  národní rada, <a href="http://www.psp.cz/eknih/1990cnr/tisky/t0072_00.htm" target="_blank" rel="noopener" class="underline">tisk 72</a>
                </div>
              </div>
              <div class="personal-data-item">
                <div class="personal-data-label">Vzdělání:</div>
                <div class="personal-data-value">Právnická fakulta UK v Praze</div>
              </div>
              <div class="personal-data-item">
                <div class="personal-data-label">Politické angažmá:</div>
                <div class="personal-data-value">
                  Před rokem 1989 byla členkou KSČ. Vystoupila v lednu 1990.
                </div>
              </div>
            </div>
            <div class="lg:w-1/3 pb-4 lg:pb-0 lg:pl-4">
              <img src="~/static/img/kralova.jpg" alt="JUDr. Helena Králová" class="rounded">
            </div>
          </div>
        </section>
        <section class="profile-section">
          <h1 class="profile-section-headline" id="decision-speed">Rychlost rozhodování</h1>
        </section>
        <section class="profile-section">
          <h1 class="profile-section-headline" id="major-decisions">Významná rozhodnutí</h1>
          <Decision year="2014" title="Kauza Nagyová – Vojenské zpravodajství – sp. zn. 3 T 35/2014" status="nyní již pravomocně skončeno" statusLink="http://infosoud.justice.cz/InfoSoud/public/list.do?druhVec=T&rocnik=2014&cisloSenatu=3&bcVec=35&kraj=MSPHAAB&org=OSPHA01&poradiUdalosti=171&cisloSenatuLabel=3&typSoudu=os&agendaNc=CIVIL&druhUdalosti=ST_VEC_PUK&idUdalosti=null&druhVecId=T&rocnikId=2014&cisloSenatuId=3&bcVecId=35&orgId=OSPHA01" proceedingsLink="http://infosoud.justice.cz/InfoSoud/public/search.do;jsessionid=FJeq2WGPsLqFODvs7Mqmf_U6UaTIW-sbDMedlzDs.infosoud01?type=spzn&typSoudu=os&krajOrg=MSPHAAB&org=OSPHA01&cisloSenatu=3&druhVec=T&bcVec=35&rocnik=2014&spamQuestion=23&agendaNc=CIVIL">
            <p class="pb-4">Zproštění Nagyové, Páleníka, Kovandy a Pohůnka v kauze obvinění ze zneužití Vojenského zpravodajství k Nečasové</p>
            <ul class="list-disc list-inside">
              <li><a href="https://drive.google.com/file/d/1E1MSX68szzg5wsFIcFMsPrjqJvwwpCdh/view" target="_blank" rel="noopener" class="underline">trestní příkaz OS Praha 1 ze dne 27. 6. 2014</a> (Nagyová)</li>
              <li><a href="https://drive.google.com/file/d/1Tr4GOw8fjfqy4YO7LYFD3H4hY3tP9tBQ/view" target="_blank" rel="noopener" class="underline">usnesení OS Praha 1 o postoupení ze dne 27. 6. 2014</a> (Páleník, Kovanda)</li>
              <li><a href="https://drive.google.com/file/d/1FBhAKlrYWE300x6rGv8TVmpCt0fHTNHc/view" target="_blank" rel="noopener" class="underline">usnesení OS Praha 1 o zastavení trestního stíhání ze dne 27. 6. 2014</a> (Pohůnek)</li>
              <li><a href="https://drive.google.com/file/d/1MJTj20tA6Qs3pREGww_00QVX-njYQIyL/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 3. 9. 2014</a> (Páleník, Kovanda)</li>
              <li><a href="https://drive.google.com/file/d/1kIeytuLKwns6elEmFyMNR08jUP3DPPvc/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 3. 9. 2014</a> (Pohůnek)</li>
              <li><a href="https://drive.google.com/file/d/1Oa0VeGqU0RyHiJ1GvbQ2VRZP6idjNaMM/view?usp=sharing" target="_blank" rel="noopener" class="underline">zprošťující rozsudek OS Praha 1 ze dne 29. 5. 2015</a> (Nagyová, Páleník, Kovanda, Pohůnek)  </li>
              <li><a href="https://drive.google.com/file/d/14P-n_lHfJRm-lkjT8DEUZVNkmW8in3nI/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 30. 3. 2016</a> (Nagyová, Páleník, Kovanda, Pohůnek) </li>
              <li><a href="https://drive.google.com/file/d/17Zo5l_R9JRIzxjixXrkyCWY7XDj5ZC-N/view" target="_blank" rel="noopener" class="underline">zprošťující rozsudek OS Praha 1 ze dne 17. 6. 2016</a> (Nagyová, Páleník, Kovanda, Pohůnek)</li>
              <li><a href="https://drive.google.com/file/d/1oLnLYKarjCf8nwJGjiLIDfL0N8UdFuci/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 23. 12. 2016</a> (Nagyová, Páleník, Kovanda, Pohůnek) &mdash; <strong>rozhodnutí bylo zrušeno jako nezákonné a MS Praha zároveň nařídil, aby byla věc projednána jiným soudcem</strong></li>
            </ul>
          </Decision>
          <Decision year="2014" title="Kauza armádního areálu v Břevnově – sp. zn. 3 T 93/2014">
            <ul class="list-disc list-inside" status="pravomocně skončeno" proceedingsLink="http://infosoud.justice.cz/InfoSoud/public/search.do?type=spzn&typSoudu=os&krajOrg=MSPHAAB&org=OSPHA01&cisloSenatu=3&druhVec=T&bcVec=93&rocnik=2014&spamQuestion=23&agendaNc=CIVIL">
              <li><a href="https://drive.google.com/file/d/18mPFplSAQW9VetWj2wUSvq1cAlgahHpQ/view" target="_blank" rel="noopener" class="underline">rozsudek OS Praha 1 ze dne 21. 8. 2017</a></li>
              <li><a href="https://drive.google.com/file/d/1EWfron9qK8a00t6QVxDGRNVOwy8K5DFi/view" target="_blank" rel="noopener" class="underline">rozsudek MS Praha ze dne 1. 3. 2018</a></li>
            </ul>
          </Decision>
          <Decision year="2012" title="Kauza velvyslance v Austrálii – porušení povinnosti při správě cizího majetku – sp. zn. 3 T 73/2012">
            <ul class="list-disc list-inside" status="pravomocně skončeno" proceedingsLink="http://infosoud.justice.cz/InfoSoud/public/search.do?type=spzn&typSoudu=os&krajOrg=MSPHAAB&org=OSPHA01&cisloSenatu=3&druhVec=T&bcVec=73&rocnik=2012&spamQuestion=23&agendaNc=CIVIL">
              <li><a href="https://drive.google.com/file/d/18QLswUjz1Om5b4NL_26-nC-DR69Dajal/view" target="_blank" rel="noopener" class="underline">zprošťující rozsudek OS Praha 1 ze dne 3. 9. 2013</a> - statní zástupce se neodvolal</li>
            </ul>
          </Decision>
          <Decision year="2011" title="Kauza generálního sekretáře MZV – sp. zn. 3 T 91/2011" status="dosud pravomocně neskončeno" proceedingsLink="http://infosoud.justice.cz/InfoSoud/public/search.do?type=spzn&typSoudu=os&krajOrg=MSPHAAB&org=OSPHA01&cisloSenatu=3&druhVec=T&bcVec=91&rocnik=2011&spamQuestion=23&agendaNc=CIVIL">
            <ul class="list-disc list-inside">
              <li><a href="https://drive.google.com/file/d/1O_EDSvVY36XZCbdzvjHGHTccaGUFEKLm/view" target="_blank" rel="noopener" class="underline">zprošťující rozsudek OS Praha 1 ze dne 13. 11. 2013</a></li>
              <li><a href="https://drive.google.com/file/d/1VEPVzZwVwnFsjkaM36Q033UA7CgQvax-/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 19. 6. 2014</a></li>
              <li><a href="https://drive.google.com/file/d/1LUsScnqH3qRWHsg4bqQlRWft2v2cLPyd/view" target="_blank" rel="noopener" class="underline">zprošťující rozsudek OS Praha 1 ze dne 23. 10. 2014</a></li>
              <li><a href="https://drive.google.com/file/d/1P6sacjfwMHYO7kDJt2-yLO-Kp4v5d1cz/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 15. 4. 2015</a></li>
              <li><a href="https://drive.google.com/file/d/1fh1vOdLiMh3W8CgOTvpEgzsCoIieP2Qt/view" target="_blank" rel="noopener" class="underline">zprošťující rozsudek OS Praha 1 ze dne 26. 8. 2015</a></li>
              <li><a href="https://drive.google.com/file/d/1jcagZWX1F4y9DFHiKAHh5FrntBI-wc9a/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 7. 1. 2016</a> &mdash; Rozhodnutí bylo zrušeno jako nezákonné a MS Praha zároveň nařídil, aby byla věc projednána jiným soudcem</li>
              <li><a href="https://drive.google.com/file/d/1C-palc2yIRh911YZ06qJNiNlgnbMjX3O/view" target="_blank" rel="noopener" class="underline">zprošťující rozsudek OS Praha 1 ze dne 9. 5. 2016</a> (jiný soudce)</li>
              <li><a href="https://drive.google.com/file/d/1jByz7RP5Hum1ocgbovVAv48P_psAItN8/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 27. 7. 2016</a></li>
              <li><a href="https://drive.google.com/file/d/1CpNcl3vvC-5qlR6pzaRiISvQdLOnytH0/view" target="_blank" rel="noopener" class="underline">zprošťující rozsudek OS Praha 1 ze dne 7. 11. 2016</a> (jiný soudce)</li>
              <li><a href="https://drive.google.com/file/d/1wprr-lgcbSmsTpu4j-_7Kdot7RziBQLo/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 8. 6. 2017</a></li>
            </ul>
          </Decision>
          <Decision year="2010" title="Kauza bývalých manažerů ČEPRO – sp. zn. 3 T 41/2010" status="dosud pravomocně neskončeno" proceedingsLink="http://infosoud.justice.cz/InfoSoud/public/search.do?type=spzn&typSoudu=os&krajOrg=MSPHAAB&org=OSPHA01&cisloSenatu=3&druhVec=T&bcVec=41&rocnik=2010&spamQuestion=23&agendaNc=CIVIL">
            <ul class="list-disc list-inside">
              <li><a href="https://drive.google.com/file/d/1yhJs0jP_49GKdxbahauNXyWrk6UJI1y-/view" target="_blank" rel="noopener" class="underline">zastavení trestního stíhání</a> a <a href="https://drive.google.com/file/d/1tX_2n4EnFl-K9GDaPiOZ1kf8Puir1akl/view" target="_blank" rel="noopener" class="underline">zprošťující rozsudek</a> OS Praha 1 ze dne 18. 11. 2013, sp. zn. 3 T 41/2010</li>
              <li>zamítnutí <a href="https://drive.google.com/file/d/1VTu-fLkaqOCzk8EWYC8xKZOgA8MLIFna/view" target="_blank" rel="noopener" class="underline">stížnosti</a> i <a href="https://drive.google.com/file/d/1H9ip1zTJXEswLEnZHYmaC8KM69WQtLz-/view" target="_blank" rel="noopener" class="underline">odvolání</a> státního zástupce MS Praha ze dne 20. 3. 2014</li>
              <li><a href="https://drive.google.com/file/d/1zV9JU2UGZXS3Buj7cGG-Ez4s48Dxsa70/view" target="_blank" rel="noopener" class="underline">zrušující usnesení Nejvyššího soudu ze dne 15. 7. 2015</a></li>
              <li>opětovné <a href="https://drive.google.com/file/d/1FV0SaAM9dy29XmujEI8xE73Qu4_KoALH/view" target="_blank" rel="noopener" class="underline">zastavení trestního stíhání</a> a <a href="https://drive.google.com/file/d/1DEZvw64XRhmbdAUuHmS0yq4une472Ge-/view" target="_blank" rel="noopener" class="underline">zprošťující rozsudek</a> OS Praha 1 ze dne 18. 12. 2015</li>
              <li><a href="https://drive.google.com/file/d/1naa5d6qcgAA1EMQvstnVr4c0YvYY2r85/view" target="_blank" rel="noopener" class="underline">zrušující usnesení o zastavení trestního stíhání</a> a <a href="https://drive.google.com/file/d/1bNZaFBx1PJ7JZcJxEKXTKcXqvloPzN45/view" target="_blank" rel="noopener" class="underline">zrušení zprošťujícího rozsudku</a> MS Praha ze dne 31. 5. 2016</li>
              <li>opětovné <a href="https://drive.google.com/file/d/1L3XbaItrKYUK3t54DRSDnDlp-ZYtcl3D/view" target="_blank" rel="noopener" class="underline">zastavení trestního stíhání</a> a <a href="https://drive.google.com/file/d/1aEziwu-_PfVweQaSx2oE5T9CVaaiIY49/view" target="_blank" rel="noopener" class="underline">zprošťující rozsudek</a> OS Praha 1 ze dne 23. 9. 2016</li>
              <li>opětovné <a href="https://drive.google.com/file/d/1Rw2Mav_W5RxdIoa06uEvnXsu-f9IY45Y/view" target="_blank" rel="noopener" class="underline">zrušující usnesení o zastavení trestního stíhání</a> a <a href="https://drive.google.com/file/d/1xa7mkTm5kYJTLTSeVp8iA4Wl_ZmdPx0P/view" target="_blank" rel="noopener" class="underline">opětovné zrušení zprošťujícího rozsudku</a> MS Praha ze dne 4. 4. 2017 &mdash; Rozhodnutí bylo zrušeno jako nezákonné a MS Praha zároveň nařídil, aby byla věc projednána jiným soudcem</li>
              <li><a href="https://drive.google.com/file/d/15qvroP6CbpekK1-oT1yWEyd_gSnDJZ3Q/view" target="_blank" rel="noopener" class="underline">odsuzující rozsudek</a> OS Praha 1 ze dne 21. 3. 2018 &mdash; rozhodoval jiný soudce</li>
            </ul>
          </Decision>
          <Decision year="1997" title="Případ vydírání ze strany devíti pražských taxikářů v kauze Thorges" status="pravomocně skončeno">
            <ul class="list-disc list-inside">
              <li><a href="https://drive.google.com/file/d/1det8KQxtRhUuQNqDCWWTPk8YUVBPID84/view" target="_blank" rel="noopener" class="underline">odsuzující rozsudek OS Praha 1 ze dne 20. 6. 2002, sp. zn. 8 T 162/97</a> (J. C.)</li>
              <li><a href="https://drive.google.com/file/d/1vQ8q8GfiNGVLURlwp3vm2jMXq7_if4ej/view" target="_blank" rel="noopener" class="underline">odsuzující rozsudek OS Praha 1 ze dne 25. 2. 2004, sp. zn. 3 T 92/2002</a> (J. M.)</li>
              <li><a href="https://drive.google.com/file/d/1drJNuuKvr5CRUTsxdolYCo_1LPf2yrp8/view" target="_blank" rel="noopener" class="underline">odsuzující rozsudek OS Praha 1 ze dne 2. 12. 2004, , sp. zn. 3 T 41/2004</a> (J. S., M. B., J. H.)</li>
              <li><a href="https://drive.google.com/file/d/1hFEG1DEqMdNu_TgLYb977x0PVUAYyMvj/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 11. 5. 2005</a> (J. H., J. S., M. B.)</li>
              <li><a href="https://drive.google.com/file/d/1GaoFzQ52inBotPCF76f2BLTboPzB0SNf/view" target="_blank" rel="noopener" class="underline">odsuzující a zprošťující rozsudek OS Praha 1 ze dne 13. 10. 2005, sp. zn. 3 T 41/2004</a>  (J. S., J. H., M. B.)</li>
              <li><a href="https://drive.google.com/file/d/1LuBJbmerc8ed48wk7Z9Kcox-gszG84aY/view" target="_blank" rel="noopener" class="underline">zrušující usnesení MS Praha ze dne 26. 1. 2006</a> (J. S., J. H.)</li>
              <li><a href="https://drive.google.com/file/d/1-LFKFvgwJOTDxW7diI03MHpdeX9Xw1C9/view" target="_blank" rel="noopener" class="underline">zproštění J. S. a J. H. a odsouzení J. S. rozsudkem OS Praha 1 ze dne 13. 4. 2006, sp. zn. 3 T 34/2006</a></li>
              <li><a href="https://drive.google.com/file/d/1wwEnQvxSz1gtKa6UYnroiPvkJIw05rfQ/view" target="_blank" rel="noopener" class="underline">změňující usnesení MS Praha ze dne 2. 11. 2006 (J. S.)</a> &mdash; snížení trestu</li>
            </ul>
          </Decision>
        </section>
        <section class="profile-section">
          <h1 class="profile-section-headline" id="disciplinary-offenses">Kárná provinění</h1>
          <DisciplinaryOffense year="2018">
            <strong class="head-main text-xl">sp. zn. 16 Kss 7/2017</strong> &mdash; na základě kárné žaloby ministra spravedlnosti JUDr. Roberta Pelikána, Ph.D., uznána Nejvyšším správním soudem vinnou, že z nedbalosti v rozporu se závaznými právními názory odvolacího soudu hodnotila důkazy způsobem jsoucím v extrémním rozporu s rozumným myšlením, za což jí bylo uloženo kárné opatření ve formě snížení platu o 15 % na dobu 1 roku.
          </DisciplinaryOffense>
        </section>
        <section class="profile-section">
          <h1 class="profile-section-headline" id="other">
            Další data, která chceme zveřejnit
          </h1>
          <ul class="list-disc list-inside text-lg">
            <li>Pravidelné hodnocení výkonnosti</li>
            <li>Majetkové přiznání</li>
            <li>Veřejný diář schůzek (týká se stran řízení a jejich zástupců)</li>
          </ul>
        </section>
      </content>
    </div>
  </div>
</template>

<style lang="postcss">

@import '~/assets/css/headings.css';

.testimonials {
  min-height: calc(100vh - 5rem);
}

.profile-navbar {
  @apply text-right pr-8;
}

.profile-navbar-item {
  @apply head-super text-3xl;
}

.profile-navbar-item:not(:first-child) {
  @apply mt-4;
}

.scrollactive-item {
  @apply text-brand-graysemidark block;

  transition: padding 0.3s ease-in-out;
}

.scrollactive-item.is-active {
  @apply text-brand-blacksemi pb-4;
}

.profile-navbar-item:not(:first-child) .scrollactive-item.is-active {
  @apply pt-4;
}

.profile-section {
  @apply w-full;
}
.profile-section:not(:last-of-type) {
  @apply mb-24;
}

.profile-section-headline {
  @apply head-super text-3xl mb-8;
}

.personal-data-item {
  @apply flex flex-col mb-2;
}

.personal-data-label {
  @apply head-main;
}

@screen md {
  .testimonials {
    min-height: calc(100vh - 7rem);
  }

  .profile-section-headline {
    @apply text-5xl;
  }

  .personal-data-item {
    @apply flex-row;
  }

  .personal-data-label {
    @apply w-1/4;
  }

  .personal-data-value {
    @apply w-3/4;
  }
}

.decision + .decision {
  @apply mt-8;
}
</style>

<script>
import Decision from '~/components/Decision.vue';
import DisciplinaryOffense from '~/components/DisciplinaryOffense.vue';

export default {
  components: {
    Decision,
    DisciplinaryOffense
  }
}
</script>