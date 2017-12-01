+++
date = "2017-11-29T10:30:00+02:00"
title = "Meetup #4 - Utisci"
description = "Treći NišJS meetup je protekao uz jako zanimljive teme, u Deli prostoru, gde se"
tags = ["meetup", "news"]
image = "meetup-4/icon.jpg"
+++

# NišJS Meetup 4 - Async i Extreme Performance JS

Četvrti NišJS meetup, posle duge letnje pauze, je uspešno prošao! Čuli smo dva vrlo interesantna predavanja na meetup-u koji se održao u StartUp Centru na Elektronskom Fakultetu, gde se okupilo 80-tak ljudi. Oba predavanja je održao Miloš Žikić iz kompanije Frame, koja je i bila sponzor ovog meetup-a.

![NišJS meetup 4](/images/meetup-4/meetup.jpg)

## Async approaches: Promises VS Callbacks

![NišJS talk](/images/meetup-4/talk1.jpg)

<a target="_blank" href="/slides/frame-promises-callbacks.pdf" class="button">Slajdovi</a>
<a target="_blank" href="https://youtu.be/waeahOdYzNI" class="button">Video</a>

Žile je na prvom predavanju pričao o sinhronom i asinhronom toku programa. Poseban fokus je bio na callback hell-u, odnosno, kako ga izbegnuti. Tu, na scenu nastupaju Promise-i. Čuli smo da je Promise samo wrapper oko asinhronih operacija i videli na koji način sekvencijalnim chainovanjem Promise-a izbegavamo callback hell. Takođe smo videli i ES7 način kontrole asinhronog toka sa async / await pattern-om koji čini da se naš asinhroni tok programa ponaša i izgleda kao sinhroni.

## Extreme JS Performance

![NišJS talk](/images/meetup-4/talk2.jpg)

Posle pauze za kafu Žile je nastavio sa drugim predavanjem. Videli smo da je JavaScript kao jezik izuzetno brz ali da ima i neke nedostatke kada se suoči sa nekim problemima za čije rešavanje nije predviđen (sve osim validacije forme). Videli smo hackove za poboljšanje performansi samog JS-a ali i performanse različitih pristupa poput ASM.js, PNaCl-a i UPW-a. Na kraju naravno smo videli i kako Žiletov tim u Frame-u to radi sa WebAssembly-em - kako od C++-a kroz Emscripten i LLVM dobiti duplo brži JS. Nažalost za ovo predavanje nemamo slajdove zbog NDA ali slobodno cimajte Žileta i Google koji imaju neograničene resurse.

Vidimo se uskoro!
