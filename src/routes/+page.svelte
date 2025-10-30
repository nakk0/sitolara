<script>
  import gallery from '$lib/images/gallery/index.js'
</script>

<div class="bg-gray-50 text-gray-800 font-sans">

  <!-- Main container -->
  <main class="max-w-4xl mx-auto md:my-10 bg-white shadow-lg rounded-2xl p-8 space-y-10">

    <!-- Istruzione -->
    <section id="istruzione">
      <h2 class="text-2xl font-semibold border-b-2 border-gray-200 pb-2 mb-4">Istruzione</h2>
      <p class="font-medium">Conseguimento Diploma di Maturità (a.s. 2023&ndash;2024)</p>
      <p class="text-gray-700 mb-3">Indirizzo: Linguistico<br>Istituto: "Russell-Newton"</p>
      <ul class="list-disc list-inside space-y-1">
        <li>Lingue studiate: Inglese, Francese, Spagnolo</li>
        <li>Soggiorno negli Stati Uniti (2 mesi) &ndash; <em>Drew University</em></li>
        <li>Soggiorno in Spagna &ndash; <em>Arcades del Cid</em></li>
        <li>Certificazioni: livello B1 e B2 in lingua spagnola</li>
      </ul>
    </section>

    <!-- Recitazione -->
    <section id="recitazione">
      <h2 class="text-2xl font-semibold border-b-2 border-gray-200 pb-2 mb-4">Esperienze di Recitazione</h2>
      <ul class="space-y-3">
        <li><span class="font-semibold">2015&ndash;2017:</span> Teatro “Strabiliarte” (Scandicci, FI)<br>
          <span class="text-gray-700">Spettacoli: “Sogno di una notte di mezza estate”, “La bottega delle spezie”</span></li>

        <li><span class="font-semibold">2019&ndash;2023:</span> Scuola di musical “Off Musical” (FI)<br>
          <span class="text-gray-700">Spettacoli: “Elf”, “Mean Girls”, “La sposa cadavere”, “Beetlejuice”, “The Greatest Showman”, “Hercules”, “Encanto”, “Chicago”, “In the Heights”</span></li>

        <li><span class="font-semibold">2021:</span> Corso intensivo di cinematografia &ndash; Scuola “Immagina” (FI)</li>
        <li><span class="font-semibold">2022:</span> Summer Acting Course &ndash; “Drew University” (New Jersey)</li>
        <li><span class="font-semibold">2023&ndash;2024:</span> Corso di bioenergetica (Metodo Meisner), insegnante Cyro Rossi (FI)</li>
        <li><span class="font-semibold">2024:</span> Workshop intensivo di cinematografia con Cyro Rossi, Nicola Scorza e Monica De Feudis</li>
        <li><span class="font-semibold">2024:</span> Aiuto regista &ndash; Compagnia “I Pinguini Theatre”, spettacolo “Se devi dire una bugia dilla grossa”</li>
        <li><span class="font-semibold">2025:</span> Masterclass con regista Stefano Cipani (con Cyro Rossi)</li>
        <li><span class="font-semibold">2025:</span> Masterclass con Mario Pizzuti &ndash; CRC Centro Recitazione Cinematografica</li>
        <li><span class="font-semibold">2025:</span> Corso Teen al Teatro Reims &ndash; Spettacolo “Groovers Corners”</li>
        <li><span class="font-semibold">2025 (in corso):</span> Spettacolo “Mimer” a cura di Antonio Susini</li>
      </ul>
    </section>

    <!-- Sport -->
    <section id="sport">
      <h2 class="text-2xl font-semibold border-b-2 border-gray-200 pb-2 mb-4">Attività Sportive</h2>
      <ul class="grid grid-cols-2 sm:grid-cols-3 gap-y-1 list-disc list-inside">
        <li>Danza moderna</li>
        <li>Hip hop</li>
        <li>Atletica leggera</li>
        <li>Palestra</li>
        <li>Corsa</li>
      </ul>
    </section>

    <!-- Lingue -->
    <section id="lingue">
      <h2 class="text-2xl font-semibold border-b-2 border-gray-200 pb-2 mb-4">Recitazione in Lingua</h2>
      <p class="text-lg font-medium text-gray-700">Inglese &ndash; Spagnolo &ndash; Francese</p>
    </section>

    <section id="arte">
      <h2 class="text-2xl font-semibold border-b-2 border-gray-200 pb-2 mb-4">Arte</h2>

      <span class="font-semibold">Decorazione / Restauro</span>
      <ul class="list-disc list-inside space-y-2 text-gray-700">
        <li>Affreschi in case d'epoca a Firenze (amatoriale)</li>
        <li>Restauratrice presso ditta Mannucci (apprendista)</li>
        <li>Corso di restauro CER (Istituto Restauro Firenze) su supporto tessile e ligneo (2024) &ndash; con attestato</li>
        <li>Restauro e ritocco pittorico su cornice e pavimento in casa con vista su Ponte Vecchio (amatoriale)</li>
        <li>Lavoro di ritocco pittorico in appartamento a Firenze (amatoriale)</li>
      </ul>
      <br>
      <span class="font-semibold">Immagini:</span>
      <div class="grid lg:grid-cols-3 sm:grid-cols-2 grid-cols-1 place-items-center">
          {#each gallery as p}
          <div class="max-w-md m-5">
              <img src="{p.path}" alt="" class="rounded-lg shadow-xl">
          </div>
          {/each}
      </div>
  </section>

    
  
  <!-- Instagram -->
  <section id="instagram">
    <h2 class="text-2xl font-semibold border-b-2 border-gray-200 pb-2 mb-6">Instagram</h2>

    <!-- Link al profilo Instagram -->
    <p class="mb-6 sm:text-center">
        <a href="https://www.instagram.com/_maxxmad_/" target="_blank" class="text-blue-600 hover:underline">
        @_maxxmad_
        </a>
    </p>

    <!-- Placeholder iframe video 1 -->
    <div class="flex justify-center">
        <div class="sm:w-85">
            <iframe src="https://www.instagram.com/p/DFTU_Iygya0/embed" 
                    title="instagram_video",
                    width="100%" height="400" frameborder="0" 
                    class="rounded-lg shadow-md" allowfullscreen>
            </iframe>
        </div>
    </div>
  </section>
  </main>
</div>
