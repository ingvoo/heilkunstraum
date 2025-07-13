<script setup>
useHead({
  htmlAttrs: {
    class: "scroll-smooth",
  },
});
</script>

<template>
  <div class="font-serif text-gray-700" id="top">
    <NuxtRouteAnnouncer />
    <header class="p-6 bg-accent1 shadow-sm fixed top-0 w-full bg-white">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-2xl font-serif">
          <a href="#top"> Heilkunstraum.Berlin </a>
        </h1>
        <nav class="space-x-6 text-sm font-medium">
          <a href="#ich">Raumgebende</a>
          <a href="#menschen">Praktizierende</a>
          <a href="#events">Termine</a>
          <a href="#price">Vermietung</a>
        </nav>
      </div>
    </header>

    <main class="mt-14 bg-white">
      <div class="container mx-auto py-12">
        <img src="/hero.png" alt="" class="mx-auto max-w-72" />
      </div>

      <section class="pb-20 text-center">
        <h1 class="text-4xl font-serif mb-4">
          Willkommen im Heilkunstraum.Berlin
        </h1>
        <div class="max-w-2xl mx-auto text-lg leading-relaxed space-y-3">
          <p>
            Seit 2015 steht dieser Ort all denjenigen zur Verfügung, die den Weg
            dorthin finden… Schön, dass du da bist!
          </p>

          <p>
            Es ist ein Ort an dem du dich zuhause fühlen darfst- Zuhause in dir
            selbst. Loslassen- Ankommen- Gesehen werden- dich kreativ
            ausdrücken… Du bist so willkommen, wie du bist.
          </p>

          <p>
            Eine Handvoll Menschen die im Raum therapeutisch arbeiten können
            dich bei deiner Reise zu dir Selbst begleiten.!
          </p>

          <p>
            Schau dich gerne auf dieser Seite um und finde das richtige Angebot
            für dich!
          </p>

          <p>“Büro für Reisen ins Innere”</p>
        </div>
      </section>

      <section class="py-16 bg-[#EAE6DF] scroll-mt-16" id="ich">
        <div class="container mx-auto px-4 max-w-6xl">
          <div class="grid grid-cols-5 gap-16">
            <div class="col-span-3">
              <img src="/img-01.jpg" alt="" />
            </div>
            <div class="col-span-2 flex flex-col justify-center">
              <h2 class="text-2xl">Raumgebende</h2>
              <div class="mt-4 space-y-3">
                <p>
                  Sarah Kristin Giesen Wandelnd auf einem Pfad zwischen Heilung
                  und Kunst, gestalte ich Räume von bleibendem Wert
                  Selbstverantwortung, Dankbarkeit und kreativer Ausdruck haben
                  für mich einen zentralen Stellenwert.
                </p>

                <p>
                  Wenn du Fragen zur Raumnutzung oder den Angeboten hast,
                  <a
                    href="mailto:heilkunstraum.berlin@gmail.com"
                    class="underline hover:text-blue-700 transition-colors"
                  >
                    melde dich bei mir </a
                  >.
                </p>
                <p>
                  Ich stelle außerdem Keramik her und im Raum aus (siehe
                  Ausstellung).
                </p>
                <ul>
                  <li>Instagram: @sakriskulptur</li>
                  <li>heilkunstraum.berlin@gmail.com</li>
                  <li>Instagram @heilkunstraum.berlin</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="bg-[#DCEBE7] py-16 scroll-mt-16" id="menschen">
        <div class="container mx-auto max-w-6xl">
          <div class="grid grid-cols-5 gap-16">
            <div class="col-span-2 flex flex-col justify-center">
              <h2 class="text-2xl">Praktizierende</h2>
              <ul class="space-y-2 mt-4">
                <li>
                  <a
                    href="https://sebastian-buehner.de"
                    class="underline hover:text-[#5B9A8B]"
                    >Sebastian Bühner</a
                  >
                </li>
                <li>
                  <a
                    href="https://www.gritleutzsch.de"
                    class="underline hover:text-[#5B9A8B]"
                    >Grit Leutzsch</a
                  >
                </li>
                <li>Verena Nobis / Massage</li>
                <li>Velegui Saavedra</li>
                <li>Sabine Schoska / Shiatsu</li>
              </ul>
            </div>

            <div class="col-span-3">
              <img src="/img-03.jpg" alt="" />
            </div>
          </div>
        </div>
      </section>

      <section class="bg-[#FDFCF9] py-16 px-6 scroll-mt-16" id="events">
        <div class="max-w-6xl mx-auto">
          <div class="grid grid-cols-5 gap-16">
            <div class="col-span-3">
              <img src="/ph.jpg" alt="" />
            </div>
            <div class="col-span-2 flex flex-col justify-center">
              <h2 class="text-2xl">Termine</h2>
              <ul class="list-disc pl-5 space-y-1 mt-4">
                <li>2.7. Authentic Movement</li>
                <li>Bewegtes Frauennetz (Anmeldung per E-Mail)</li>
                <li>Keramikausstellung (Sept/Okt)</li>
                <li>Ab Sept freitags – Gruppe Velegui</li>
              </ul>
            </div>
          </div>
        </div>
      </section>

      <section class="bg-[#EAE6DF] py-16 px-6 scroll-mt-16" id="price">
        <div class="max-w-3xl mx-auto">
          <h2 class="text-2xl font-serif mb-4">Vermietung</h2>
          <p class="leading-relaxed mb-4">
            Der Heilkunstraum ist offen für dein Angebot, deine Arbeit mit dir
            selbst und/ oder deinen Klientinnen. Er befindet sich in der ruhigen
            und grünen Fontanepromenade 200m vom U-Bhf Südstern und 400m von der
            Bushaltestelle Geibelstraße.
          </p>
          <p>
            Er teilt sich in einen Raum (ca 20qm) mit Teeküche und
            Sitzgelegenheit sowie WC und einen weiteren (ca 35qm) für
            Körperarbeit und Bewegung auf. Yogakissen, Matten, Decken, Futon und
            Massageliege sind vorhanden.
          </p>
          <ul class="list-disc pl-5 mt-8">
            <li>16 € für 1 Stunde</li>
            <li>28 € für 2 Stunden</li>
            <li>40 € für 3 Stunden</li>
            <li>50 € für 4 Stunden</li>
          </ul>
        </div>
      </section>
    </main>
    <footer class="py-4">
      <div class="container mx-auto max-w-6xl">
        <div class="flex justify-center gap-8 items-center">
          <p>Heilkunstraum ©2025</p>
          <div class="flex items-center justify-between gap-2">
            <a
              href="mailto:heilkunstraum.berlin@gmail.com"
              class="hover:text-blue-700 transition-colors p-1"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.75"
                stroke="currentColor"
                class="h-6 w-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75"
                />
              </svg>
            </a>
            <a
              href="https://www.instagram.com/heilkunstraum.berlin/"
              class="hover:text-blue-700 transition-colors p-1"
            >
              <svg
                role="img"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="currentColor"
              >
                <path
                  d="M7.0301.084c-1.2768.0602-2.1487.264-2.911.5634-.7888.3075-1.4575.72-2.1228 1.3877-.6652.6677-1.075 1.3368-1.3802 2.127-.2954.7638-.4956 1.6365-.552 2.914-.0564 1.2775-.0689 1.6882-.0626 4.947.0062 3.2586.0206 3.6671.0825 4.9473.061 1.2765.264 2.1482.5635 2.9107.308.7889.72 1.4573 1.388 2.1228.6679.6655 1.3365 1.0743 2.1285 1.38.7632.295 1.6361.4961 2.9134.552 1.2773.056 1.6884.069 4.9462.0627 3.2578-.0062 3.668-.0207 4.9478-.0814 1.28-.0607 2.147-.2652 2.9098-.5633.7889-.3086 1.4578-.72 2.1228-1.3881.665-.6682 1.0745-1.3378 1.3795-2.1284.2957-.7632.4966-1.636.552-2.9124.056-1.2809.0692-1.6898.063-4.948-.0063-3.2583-.021-3.6668-.0817-4.9465-.0607-1.2797-.264-2.1487-.5633-2.9117-.3084-.7889-.72-1.4568-1.3876-2.1228C21.2982 1.33 20.628.9208 19.8378.6165 19.074.321 18.2017.1197 16.9244.0645 15.6471.0093 15.236-.005 11.977.0014 8.718.0076 8.31.0215 7.0301.0839m.1402 21.6932c-1.17-.0509-1.8053-.2453-2.2287-.408-.5606-.216-.96-.4771-1.3819-.895-.422-.4178-.6811-.8186-.9-1.378-.1644-.4234-.3624-1.058-.4171-2.228-.0595-1.2645-.072-1.6442-.079-4.848-.007-3.2037.0053-3.583.0607-4.848.05-1.169.2456-1.805.408-2.2282.216-.5613.4762-.96.895-1.3816.4188-.4217.8184-.6814 1.3783-.9003.423-.1651 1.0575-.3614 2.227-.4171 1.2655-.06 1.6447-.072 4.848-.079 3.2033-.007 3.5835.005 4.8495.0608 1.169.0508 1.8053.2445 2.228.408.5608.216.96.4754 1.3816.895.4217.4194.6816.8176.9005 1.3787.1653.4217.3617 1.056.4169 2.2263.0602 1.2655.0739 1.645.0796 4.848.0058 3.203-.0055 3.5834-.061 4.848-.051 1.17-.245 1.8055-.408 2.2294-.216.5604-.4763.96-.8954 1.3814-.419.4215-.8181.6811-1.3783.9-.4224.1649-1.0577.3617-2.2262.4174-1.2656.0595-1.6448.072-4.8493.079-3.2045.007-3.5825-.006-4.848-.0608M16.953 5.5864A1.44 1.44 0 1 0 18.39 4.144a1.44 1.44 0 0 0-1.437 1.4424M5.8385 12.012c.0067 3.4032 2.7706 6.1557 6.173 6.1493 3.4026-.0065 6.157-2.7701 6.1506-6.1733-.0065-3.4032-2.771-6.1565-6.174-6.1498-3.403.0067-6.156 2.771-6.1496 6.1738M8 12.0077a4 4 0 1 1 4.008 3.9921A3.9996 3.9996 0 0 1 8 12.0077"
                />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>
