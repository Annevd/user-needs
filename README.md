> _Fork_ deze leertaak en ga aan de slag. 
Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. 
De instructie vind je in: [docs/INSTRUCTIONS.md](https://github.com/fdnd-task/user-needs/blob/main/docs/INSTRUCTIONS.md)

# User needs: Creative coding
<!-- Geef je project een titel en schrijf in één zin wat het is -->

## Inhoudsopgave

  * [Werkwijze](#werkwijze)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Werkwijze

Je gaat werken op een manier die in scrum een *programming spike* wordt genoemd. Een spike is een taak gericht op het beantwoorden van een vraag of het verzamelen van informatie. In plaats van het produceren van een verzendbaar product. Bij sommige taken kan niet goed ingeschat  worden tot het ontwikkelteam daadwerkelijk wat werk verricht om een technische vraag of ontwerpprobleem op te lossen. De oplossing is dan om een zogenaamde 'spike' te creëren.

> Creative coding is a type of computer programming in which the goal is to create something expressive instead of something functional. - [Wikipedia](https://en.wikipedia.org/wiki/Creative_coding)

Voor de opdracht van de opdrachtgever ontwerp en maak je creatieve oplossingen voor de interface. Nu de website statisch gegenereerd wordt kun je al je skills inzetten om de interface te verrijken. De bedoeling is dat je gebruikers "oooh" en "aaaah" roepen en niet meer kunnen stoppen met klikken! Of Scrollen! Of gooien!

Elke week ontwerp en maak je een creatieve oplossing, welke je op vrijdag gaat testen. Deze sprint ga je in drie *spikes*, 3 experimenten ontwerpen en maken.

## Creative Coding Spike 1: Scroll driven animation
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
**Prompt:** _Mysterious post-apocaliptic scroll driven animation_

- Saturation gaat omlaag hoe verder je scrollt
- Elementen vallen takelen af hoe verder je scrollt
- Cracks verschijnen in de elementen en worden steeds meer en zichtbaarder hoe verder je scrollt
- Planten/klimops zullen steeds meer verschijnen hoe verder je scrollt
<!-- Voeg een mooie poster visual toe 📸 -->
### 0%
<img width=400 src="https://github.com/user-attachments/assets/35f2f4dc-89b0-4f0f-a0ed-ec355694426e">

### 25%
<img width=400 src="https://github.com/user-attachments/assets/2a07366a-1ba7-4b90-9afd-bc40d86841d9">

### 50%
<img width=400 src="https://github.com/user-attachments/assets/5949461a-6d29-4f7f-b0d7-1614ac75d62f">

### 75%
<img width=400 src="https://github.com/user-attachments/assets/324cb9ae-6ca4-418d-81d0-9d916715e208">

### 100%
<img width=400 src="https://github.com/user-attachments/assets/fdb95375-7a1f-4edb-8208-7b90ac3ef978">
<!-- Voeg een link toe naar Github Pages 🌐-->

- [Livelink](https://velvety-crostata-06838d.netlify.app/)

## Creative Coding Spike 2: View transition
<!-- In de Beschrijving staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
**Prompt:** _Crazy retro line art view transition_

Wanneer je naar een nieuwe pagina navigeert, komt er een view transition met een retro line view transition.

![VIEW-TRANSITION-ezgif com-video-to-gif-converter (1)](https://github.com/user-attachments/assets/ba2eef97-9904-4f01-b70b-9ec5c79ac137)

- [Livelink](https://retro-line-view-transition.netlify.app/)

## Creative Coding Spike 3: Kerstsfeer

**Prompt:** _Grunge kerstsfeer met alle toeters en bellen_

- Onderaan de pagina rijdt een trein wanneer je scrolt
- Het sneeuwt op de pagina
  
![Bezigmetopnemen2024-12-18135947-Trim-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/ff220518-e184-4a20-b9e4-0467d68519bc)

- [Livelink](https://grunge-kerstsfeer.netlify.app/)

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->
**Scroll driven animation:**

Voor de scroll driven animations maak ik gebruik van de scroll driven animation API met `scroll()` en `view()`.

**View Transition:**

Voor de view transition gebruik ik de view t ransition API, en maak ik gebruik van `::view-transition-group` om de keyframe animaties af te spelen. Deze zet ik in een `@media (prefers-reduced-motion: no-preference)`. Ook gebruik de `import { onNavigate } from '$app/navigation';` van Svelte.

**Kerstsfeer:**

Om de website kerstig te maken heb ik met WebGL een sneeuw shader toegevoegd. Ook heb ik met een scroll-driven animation de trein laten bewegen.

## Bronnen
- [Link naar mijn scroll driven animation branch](https://github.com/fdnd-agency/buurtcampus-oost/tree/post-apocalyptic-scroll-animation)
- [Link naar ontwerp scroll driven animation](https://www.figma.com/design/QN0rBXQ6Vd38Y6g6zX2jkl/Untitled?node-id=13-229&t=ere02MrOJ84cjzWs-1)
- [Link naar mijn view transititon branch](https://github.com/fdnd-agency/buurtcampus-oost/tree/crazy-retro-line-view-transition)
- [Link naar ontwerp view transition](https://www.figma.com/design/QN0rBXQ6Vd38Y6g6zX2jkl/Creative-Coding?node-id=45-2&t=zmlzRguFkBVEcQJI-1)
- [Link naar mijn kertsfeer branch](https://github.com/fdnd-agency/buurtcampus-oost/tree/grunge-kerstsfeer)
- [Link naar ontwerp kerstsfeer](https://www.figma.com/design/QN0rBXQ6Vd38Y6g6zX2jkl/Creative-Coding?node-id=96-2&t=dowrhtarBQeQAM0D-1)

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
