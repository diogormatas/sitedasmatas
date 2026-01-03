---
title: ''
type: landing

sections:
  # HERO / Banner grande com card discreto central + logo + CTA IG
  - block: markdown
    content:
      title: ""
      text: |-
        {{< hero_card >}}

    design:
      columns: "1"
      background:
        image:
          filename: "banner-matas.jpg"
          filters:
            brightness: 0.85
      spacing:
        padding: ["0", "0", "0", "0"]

  # BIG NUMBERS (via shortcode + data)
  - block: markdown
    content:
      title: ""
      text: |-
        {{< big_numbers >}}
    design:
      columns: "1"
      full_width: true
      spacing:
        padding: ["0", "0", "0", "0"]


  - block: markdown
    content:
      title: ""
      text: |-
        {{< rawhtml >}}

        <div class="text-center max-w-3xl mx-auto mb-32 md:mb-32">

          <!-- TEXTO CURTO -->
          <p class="text-2xl md:text-3xl font-semibold leading-snug">
            A aldeia que ninguém conhece.<br/>
            As pessoas que fazem a diferença.<br/>
            <span class="block mt-2 font-bold tracking-wide">
              Das Matas — Para o Mundo
            </span>
          </p>


          <!-- TEXTO LONGO (expansível) -->
          <details class="mt-6 group">
           <summary class="cursor-pointer text-sm font-medium
               text-primary-600 dark:text-primary-400
               hover:text-primary-700 dark:hover:text-primary-300
               transition">
            Ler mais
          </summary>





            <div class="mt-4 text-base leading-relaxed opacity-80">
              <p>
                As Matas é uma aldeia pequena, discreta e muitas vezes confundida com as suas homónimas.
              </p>

              <p class="mt-3">
                Aqui outrora cresceram as grandes raízes da nossa azinheira.<br/>
                A árvore já não está, mas as raízes nunca as perdemos.
              </p>

              <p class="mt-3">
                Este projeto nasce da ligação entre humildade, comunidade e desporto.<br/>
                Entre a aldeia, o padel e os quilómetros corridos, criamos pontes.
              </p>

              <p class="mt-3">
                Quem sabe na esperança de que um dia outra ponte — a das Matas — vos traga até à nossa festa de Agosto,
                com o mesmo orgulho com que vos recebemos.
              </p>
            </div>
          </details>

        </div>

        {{< /rawhtml >}}

  # 3 PILARES — cards editoriais com imagem
  - block: markdown
    content:
      title: "Os 3 pilares"
      text: |-
        {{< rawhtml >}}
        <div class="relative left-1/2 right-1/2 -ml-[50vw] -mr-[50vw] w-screen bg-gray-50 dark:bg-[rgb(17,24,39)]">
        
          <div class="mx-auto max-w-6xl px-4 md:px-10 py-10 md:py-14">
          
            <div class="grid grid-cols-1 md:grid-cols-3 gap-5 md:gap-8">

              <!-- ALDEIA -->
              <a href="/aldeia/" class="group block overflow-hidden rounded-2xl border border-black/10 dark:border-white/10 bg-white/80 dark:bg-white/5 backdrop-blur-md shadow-sm hover:shadow-lg transition">
                <div class="relative aspect-[16/10] overflow-hidden">
                  <img
                    src="/img/pilar-aldeia.jpg"
                    alt="Aldeia Das Matas"
                    class="h-full w-full object-cover transition duration-500 group-hover:scale-[1.03]"
                    loading="lazy"
                  />
                  <div class="pointer-events-none absolute inset-0 bg-gradient-to-t from-black/25 via-black/0 to-black/0"></div>
                </div>

                <div class="p-6 md:p-7">
                  <div class="text-xl font-semibold text-gray-900 dark:text-white">Aldeia</div>
                  <div class="mt-2 text-base text-gray-700 dark:text-gray-200 leading-relaxed">
                    Histórias e memórias partilhadas, com o orgulho simples em ser Das Matas.
                  </div>
                   <div class="mt-4 text-sm font-semibold
                              text-primary-600 dark:text-primary-400
                              group-hover:text-primary-700 dark:group-hover:text-primary-300
                              transition">
                    Explorar →
                  </div>

                </div>
              </a>

              <!-- PADEL -->
              <a href="/padel/" class="group block overflow-hidden rounded-2xl border border-black/10 dark:border-white/10 bg-white/80 dark:bg-white/5 backdrop-blur-md shadow-sm hover:shadow-lg transition">
                <div class="relative aspect-[16/10] overflow-hidden">
                  <img
                    src="/img/pilar-padel.jpg"
                    alt="Padel em comunidade"
                    class="h-full w-full object-cover transition duration-500 group-hover:scale-[1.03]"
                    loading="lazy"
                  />
                  <div class="pointer-events-none absolute inset-0 bg-gradient-to-t from-black/25 via-black/0 to-black/0"></div>
                </div>

                <div class="p-6 md:p-7">
                  <div class="text-xl font-semibold text-gray-900 dark:text-white">Padel</div>
                  <div class="mt-2 text-base text-gray-700 dark:text-gray-200 leading-relaxed">
                    Jogado entre amigos, equipados com rigor… e sempre decidido no 4.º set.
                  </div>
                   <div class="mt-4 text-sm font-semibold
                              text-primary-600 dark:text-primary-400
                              group-hover:text-primary-700 dark:group-hover:text-primary-300
                              transition">
                    Explorar →
                  </div>
                </div>
              </a>

              <!-- RUNNER -->
              <a href="/runner/" class="group block overflow-hidden rounded-2xl border border-black/10 dark:border-white/10 bg-white/80 dark:bg-white/5 backdrop-blur-md shadow-sm hover:shadow-lg transition">
                <div class="relative aspect-[16/10] overflow-hidden">
                  <img
                    src="/img/pilar-runner.jpg"
                    alt="Corridas em grupo"
                    class="h-full w-full object-cover transition duration-500 group-hover:scale-[1.03]"
                    loading="lazy"
                  />
                  <div class="pointer-events-none absolute inset-0 bg-gradient-to-t from-black/25 via-black/0 to-black/0"></div>
                </div>

                <div class="p-6 md:p-7">
                  <div class="text-xl font-semibold text-gray-900 dark:text-white">Runner</div>
                  <div class="mt-2 text-base text-gray-700 dark:text-gray-200 leading-relaxed">
                    Quilómetros somados em grupo, sorrisos pelo caminho e cada um no seu ritmo.
                  </div>
                   <div class="mt-4 text-sm font-semibold
                              text-primary-600 dark:text-primary-400
                              group-hover:text-primary-700 dark:group-hover:text-primary-300
                              transition">
                    Explorar →
                  </div>

                </div>
              </a>

            </div>

          </div>
        </div>
        {{< /rawhtml >}}
    design:
      columns: "1"
      full_width: true
      spacing:
        padding: ["0","0","0","0"]





  # Hot Topics / Recent Posts
  - block: collection
    content:
      title: "Pela Aldeia"
      page_type: blog
      count: 6
      order: desc
    design:
      view: card
---
