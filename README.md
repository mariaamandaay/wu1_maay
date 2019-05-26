# wu1_maay
Project in school
# Utvecklingsprojekt i Webbutveckling 1
*Maria Ay*

## Bakgrund

##### Syftet med uppgiften är att skapa en hemsida, med innehåll av ett CV/portfolio. Hemsidan ska innehålla information om en själv. Information om en själv, ens studier, om man har jobb och vad man vill göra i framtiden.

## Planering
### Innehåll

##### Hemsidan visar 100 ord om mig (profil), mina studier, jobb som jag har haft/har, mina färdigheter, vad jag vill göra i min framtid och kontaktuppgifter. Det är en portfolio som visar information om mig som person och vad jag har gjort, samt vad jag vill göra.

### Layout

##### Under arbetets gång så ändrade jag designen på hemsidan för att göra den mer stilren och fångande. Jag valde först att ha hexagoner som sidan zoomar in på, om man trycker på en. I hexagonen visas en av kategorierna ovan. Men under terminens gång så har tankarna utvecklats. Hemsidan layout är nu på en enstaka sida, med en bar på toppen av sidan, som följer efter skärmen om man scrollar ner eller upp. Hela sidan är indelad i sex olika delar, som man också kan se på själva baren. 
##### [Min skiss](https://progress.thorengruppen.se/api/TIS/schools/tisgot/courses/129356/assignments/92437/files/getSolution/1177156)

### Färgval

##### Bakgrund
###### Användningsområde
###### HEX - #FFFFFF

###### RGB - rgb(255,255,255)

##### Text
###### Användningsområde
###### HEX - #707070

###### RGB - rgb(112,112,112)

##### Profil
###### Användningsområde
###### HEX - #F79F79

###### RGB - rgb(247,159,121)

##### Studier
###### Användningsområde
###### HEX - #F7D08A

###### RGB - rgb(247,208,138)

##### Jobb
###### Användningsområde
###### HEX - #E3F09B

###### RGB - rgb(227,240,155)

##### Färdigheter
###### Användningsområde
###### HEX - #87B6A7

###### RGB - rgb(135,182,167)

##### Framtiden
###### Användningsområde
###### HEX - #A3E6E1

###### RGB - rgb(163,230,225)

##### Kontakt
###### Användningsområde
###### HEX - #5B5941

###### RGB - rgb(91,89,65)

### Typsnitt

##### Rubriker - Roboto Slab

##### Övrigt - Roboto

### Mockup

##### [Min mockup](https://drive.google.com/file/d/1r90AD6idVuV135TCCNCMtpI_4CZX3IBm/view?usp=sharing)

### Tillgänglighet

##### För närvarande endast datorer

## Dokumentation

##### Syftet med uppgiften som tidigare sagt gick ut på att skapa en hemsida, med information om sig själv. Uppgiften visar våra kunskaper om hur man skapar ett CV/portfolio, i form av en hemsida. Man skall även visa hur man kan på bästa möjliga sätt designa och strukturera koden och den slutgiltiga sidan.
##### För att påbörja uppgiften skapade jag skisser för att kunna visuellt se hur den slutgiltiga sidan skulle se ut. Med hjälp av photoshop och även Adobe XD så påbörjade jag den digitala mockupen till min hemsida. För att kunna programmera så använde jag mig av Visual Studio Code Den första designen av hemsidan skulle innehålla hexagoner. Dessa hexagoner skulle leda användaren till exempelvis "Profil" eller "Kontaktuppgifter". Under senare tid så valde jag istället att göra något enklare och fräschare. Jag valde att endast ha en bar på toppen av hemsidan, som hjälpmedel för att komma till olika sidor. Detta berodde på att jag ville göra hemsidan mer personlig, och göra något som är mer utifrån mina "smaklökar".
##### Tanken var att när användaren scrollar ner så ser personen fortfarande baren på toppen av hemsidan. Detta var så att baren ej skulle försvinna och så att man mycket smidigare kan lämna den sidan man är på. Själva hemsidan skulle samt bestå utav en lång sida som man scrollar genom. Resultatet blev istället 6 sidor som täcker skärmen och inget mer. Detta ansåg jag vara en mer lockande design på hemsidan, eftersom sidorna ser mindre ut och inte lika långa och tråkiga. 

#### Fördelar

##### Hemsidan blev personlig och visar vad jag är för slags person. Jag dras mer till det stilrena. Därför valde jag också att ha en enkelt vit bakgrund så att det inte skulle bli alldeles för många färger. Huvudfärgerna jag valde är pastell och mjuka. Funktionaliteten av hemsidan blev också väldigt bra. Den fungerar smidigt och fint.

#### Nackdelar

##### Animationen av pilen till baren fungerade inte så bra, därför var jag tvungen att ta bort den och istället låta den hoppa från en sida till en annan. Tyvärr så har jag inte heller anpassat hemsidan till någon telefon så den fungerar endast på datorer.
##### Tidslinjen blev inte som den skulle. Jag var kluven om jag skulle koda eller bara photoshopa. Jag valde till slut att photoshopa bilden och det ledde till att jag inte så enkelt kunnat lägga in länken till min uppsats "[Internets Historia](C:\Users\tisgot17maray\Downloads\Sociala medier (3).docx)". Detta var för att bilden blev alldeles för stor och jag fick svårigheter med att göra något mer med hemsidan. Min dator kunde inte hantera det och slockna flertalet gånger.

#### Sammanfattning av hela arbetet

##### Uppgiften har hjälpt mig utveckla mina kunskaper inom programmering och webbutveckling. Den gick ut på att man skulle skapa en hemsida om sig själv, vilket jag har gjort. Slutgiltigt blev resultatet bra och hemsidan fungerar som den ska.

### Kod
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Marias Portfolio</title>
    <!-- Imports the web fonts -->
    <link
      href="https://fonts.googleapis.com/css?family=Roboto|Roboto+Slab"
      rel="stylesheet"
    />

    <!-- Imports css -->
    <link rel="stylesheet" href="./index.css" />
    <link rel="stylesheet" href="./colors.css" />

    <!-- Imports bootstrap -->
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css"
      integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T"
      crossorigin="anonymous"
    />
  </head>
  <body>
    <nav class="container-fluid">
      <ul class="nav nav-fill">
        <li class="nav-item" id="profile">
          <div>
            <img src="images/010-worker.svg" />
            <a>Profile</a>
            <div class="bottom-bar dark-orange"></div>
            <canvas
              class="arrow"
              id="profile-arrow"
              width="100px"
              height="100px"
            ></canvas>
          </div>
        </li>
        <li class="nav-item">
          <div id="studies">
            <img src="images/006-student.svg" />
            <a>Studies</a>
            <div class="bottom-bar light-orange"></div>
            <canvas
              class="arrow"
              id="studies-arrow"
              width="100px"
              height="100px"
            ></canvas>
          </div>
        </li>
        <li class="nav-item">
          <div id="jobs">
            <img src="images/008-bag.svg" />
            <a>Jobs</a>
            <div class="bottom-bar lime-green"></div>
            <canvas
              class="arrow"
              id="jobs-arrow"
              width="100px"
              height="100px"
            ></canvas>
          </div>
        </li>
        <li class="nav-item">
          <div id="skills">
            <img src="images/009-wrench-1.svg" />
            <a>Skills</a>
            <div class="bottom-bar dark-green"></div>
            <canvas
              class="arrow"
              id="skills-arrow"
              width="100px"
              height="100px"
            ></canvas>
          </div>
        </li>
        <li class="nav-item">
          <div id="future">
            <img src="images/007-smart-glasses-1.svg" />
            <a>Future</a>
            <div class="bottom-bar baby-blue"></div>
            <canvas
              class="arrow"
              id="future-arrow"
              width="100px"
              height="100px"
            ></canvas>
          </div>
        </li>
        <li class="nav-item">
          <div id="contact">
            <img src="images/card.svg" />
            <a>Contact</a>
            <div class="bottom-bar black"></div>
            <canvas
              class="arrow"
              id="contact-arrow"
              width="100px"
              height="100px"
            ></canvas>
          </div>
        </li>
      </ul>
    </nav>
    <main class="container-fluid">
      <div id="profile-content" class="row align-items-center content">
        <div class="col-8">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque
          interdum sed leo ut pharetra. Donec interdum ex in libero varius, nec
          rhoncus lacus finibus. Praesent vitae urna fermentum, ullamcorper sem
          id, consectetur enim. Curabitur tristique, leo sed placerat faucibus,
          sem risus egestas massa, in interdum ligula erat ut sem. Donec sed
          dictum justo, id lobortis quam. Aliquam vestibulum odio et mauris
          accumsan rutrum. Vivamus pulvinar velit a nulla tempor ultrices. Orci
          varius natoque penatibus et magnis dis parturient montes, nascetur
          ridiculus mus. In eget varius odio. Integer et blandit risus. Donec
          est nisl, ornare at vestibulum eu, dapibus non justo. Duis augue ex,
          imperdiet at arcu sit amet, finibus viverra libero. Morbi purus neque,
          laoreet sed pellentesque placerat, sagittis et ligula. Sed blandit
          mauris id dui efficitur mattis id ac augue. Ut nec fringilla ipsum.
          Donec sed enim erat. Proin nec magna et orci blandit ullamcorper.
          Nullam viverra sed lacus ut ultrices. Nunc in purus a nibh ultricies
          tincidunt. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
          Pellentesque interdum sed leo ut pharetra. Donec interdum ex in libero
          varius, nec rhoncus lacus finibus. Praesent vitae urna fermentum,
          ullamcorper sem id, consectetur enim. Curabitur tristique, leo sed
          placerat faucibus, sem risus egestas massa, in interdum ligula erat ut
          sem. Donec sed dictum justo, id lobortis quam. Aliquam vestibulum odio
          et mauris accumsan rutrum. Vivamus pulvinar velit a nulla tempor
          ultrices. Orci varius natoque penatibus et magnis dis parturient
          montes, nascetur ridiculus mus. In eget varius odio. Integer et
          blandit
        </div>
        <div class="col-4">
          <img src="./images/001-employee.svg" />
        </div>
      </div>
      <div id="studies-content" class="row align-items-center content">
        <img src="./images/Tidslinje.jpg" />
      </div>
      <div id="jobs-content" class="row align-items-center content">
        <div class="col-4">
          <img src="./images/cashier-machine.svg" />
          <div class="mt-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Pellentesque interdum sed leo ut pharetra. Donec interdum ex in
            libero varius, nec rhoncus lacus finibus. Praesent vitae urna
            fermentum, ullamcorper sem id, consectetur enim. Curabitur
            tristique, leo sed placerat faucibus, sem risus egestas massa, in
            interdum ligula erat ut sem. Donec sed dictum justo, id lobortis
            quam. Aliquam vestibulum odio et mauris accumsan rutrum. Vivamus
            pulvinar velit a nulla tempor ultrices. Orci varius natoque
            penatibus et magnis dis parturient montes, nascetur ridiculus mus.
            In eget varius odio. Integer et blandit risus. Donec est nisl,
            ornare at vestibulum eu, dapibus non justo. Duis augue ex, imperdiet
            at arcu sit amet, finibus viverra libero.
          </div>
        </div>
        <div class="col-4">
          <img src="./images/salesman.svg" />
          <div class="mt-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Pellentesque interdum sed leo ut pharetra. Donec interdum ex in
            libero varius, nec rhoncus lacus finibus. Praesent vitae urna
            fermentum, ullamcorper sem id, consectetur enim. Curabitur
            tristique, leo sed placerat faucibus, sem risus egestas massa, in
            interdum ligula erat ut sem. Donec sed dictum justo, id lobortis
            quam. Aliquam vestibulum odio et mauris accumsan rutrum. Vivamus
            pulvinar velit a nulla tempor ultrices. Orci varius natoque
            penatibus et magnis dis parturient montes, nascetur ridiculus mus.
            In eget varius odio. Integer et blandit risus. Donec est nisl,
            ornare at vestibulum eu, dapibus non justo. Duis augue ex, imperdiet
            at arcu sit amet, finibus viverra libero.
          </div>
        </div>
        <div class="col-4">
          <img src="./images/warehouse.svg" />
          <div class="mt-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Pellentesque interdum sed leo ut pharetra. Donec interdum ex in
            libero varius, nec rhoncus lacus finibus. Praesent vitae urna
            fermentum, ullamcorper sem id, consectetur enim. Curabitur
            tristique, leo sed placerat faucibus, sem risus egestas massa, in
            interdum ligula erat ut sem. Donec sed dictum justo, id lobortis
            quam. Aliquam vestibulum odio et mauris accumsan rutrum. Vivamus
            pulvinar velit a nulla tempor ultrices. Orci varius natoque
            penatibus et magnis dis parturient montes, nascetur ridiculus mus.
            In eget varius odio. Integer et blandit risus. Donec est nisl,
            ornare at vestibulum eu, dapibus non justo. Duis augue ex, imperdiet
            at arcu sit amet, finibus viverra libero.
          </div>
        </div>
      </div>
      <div id="skills-content" class="row align-items-center content">
        <div class="col-6">
          <img src="./images/skill.svg" />
        </div>
        <div class="col-6">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque
          interdum sed leo ut pharetra. Donec interdum ex in libero varius, nec
          rhoncus lacus finibus. Praesent vitae urna fermentum, ullamcorper sem
          id, consectetur enim. Curabitur tristique, leo sed placerat faucibus,
          sem risus egestas massa, in interdum ligula erat ut sem. Donec sed
          dictum justo, id lobortis quam. Aliquam vestibulum odio et mauris
          accumsan rutrum. Vivamus pulvinar velit a nulla tempor ultrices. Orci
          varius natoque penatibus et magnis dis parturient montes, nascetur
          ridiculus mus. In eget varius odio. Integer et blandit risus. Donec
          est nisl, ornare at vestibulum eu, dapibus non justo. Duis augue ex,
          imperdiet at arcu sit amet, finibus viverra libero. Lorem ipsum dolor
          sit amet, consectetur adipiscing elit. Pellentesque interdum sed leo
          ut pharetra. Donec interdum ex in libero varius, nec rhoncus lacus
          finibus. Praesent vitae urna fermentum, ullamcorper sem id,
          consectetur enim. Curabitur tristique, leo sed placerat faucibus, sem
          risus egestas massa, in interdum ligula erat ut sem. Donec sed dictum
          justo, id lobortis quam. Aliquam vestibulum odio et mauris accumsan
          rutrum. Vivamus pulvinar velit a nulla tempor ultrices. Orci varius
          natoque penatibus et magnis dis parturient montes, nascetur ridiculus
          mus. In eget varius odio. Integer et blandit risus. Donec est nisl,
          ornare at vestibulum eu, dapibus non justo. Duis augue ex, imperdiet
          at arcu sit amet, finibus viverra libero. Lorem ipsum dolor sit amet,
          consectetur adipiscing elit. Pellentesque interdum sed leo ut
          pharetra. Donec interdum ex in libero varius, nec rhoncus lacus
          finibus. Praesent vitae urna fermentum, ullamcorper sem id,
          consectetur enim. Curabitur tristique, leo sed placerat faucibus, sem
          risus egestas massa, in interdum ligula erat ut sem. Donec sed dictum
          justo, id lobortis quam. Aliquam vestibulum odio et mauris accumsan
          rutrum. Vivamus pulvinar velit a nulla tempor ultrices. Orci varius
          natoque penatibus et magnis dis parturient montes, nascetur ridiculus
          mus. In eget varius odio. Integer et blandit risus. Donec est nisl,
          ornare at vestibulum eu, dapibus non justo. Duis augue ex, imperdiet
          at arcu sit amet, finibus viverra libero.
        </div>
      </div>
      <div id="future-content" class="row align-items-center content">
        <div class="col-3 col-centered">
          <img src="./images/planet-earth.svg" width="290px" height="290px" />
        </div>
        <div class="col-5 col-centered">
          <div class="mb-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            Pellentesque interdum sed leo ut pharetra. Donec interdum ex in
            libero varius, nec rhoncus lacus finibus. Praesent vitae urna
            fermentum, ullamcorper sem id, consectetur enim. Curabitur
            tristique, leo sed placerat faucibus, sem risus egestas massa, in
            interdum ligula erat ut sem. Donec sed dictum justo, id lobortis
            quam. Aliquam vestibulum odio et mauris accumsan rutrum. Vivamus
            pulvinar velit a nulla tempor ultrices. Orci varius natoque
            penatibus et magnis dis parturient montes, nascetur ridiculus mus.
            In eget varius odio. Integer et blandit risus. Donec est nisl,
            ornare at vestibulum eu, dapibus non justo. Duis augue ex, imperdiet
            at arcu sit amet, finibus viverra libero.
          </div>
          <div class="row align-items-center">
            <div class="col-8 col-centered">
              <img src="./images/mars.svg" width="236px" height="236px" />
            </div>
            <div class="col-4 col-centered">
              <img src="./images/spaceship.svg" width="99px" height="99px" />
            </div>
          </div>
        </div>
        <div class="col-4 col-centered">
          <img src="./images/jupiter.svg" width="487px" height="487px" />
        </div>
      </div>
      <div id="contact-content" class="row align-items-center content">
        <div class="col-4 col-centered">
          <img src="./images/IMG_4076.jpg" id="profile-pic" />
          <div class="mt-5">
            <h2>Contact Me</h2>
            <form
              action="mailto:maria.ay01@hotmail.com"
              method="POST"
              enctype="text/plain"
              class="form-group"
            >
              <label for="firstname">First name:</label>
              <input
                class="form-control"
                type="text"
                name="firstname"
                placeholder="First name"
              /><br />
              <label for="lastname">Last name:</label>
              <input
                class="form-control"
                type="text"
                name="lastname"
                placeholder="Last name"
              /><br />
              <label for="email">E mail:</label>
              <input
                class="form-control"
                type="email"
                name="email"
                placeholder="E mail"
              /><br />
              <label for="message">Message:</label>
              <textarea class="form-control" name="message" rows="3"></textarea
              ><br />
              <input
                class="form-control"
                class="btn-success mt-5"
                type="submit"
                value="Send"
              />
            </form>
          </div>
        </div>
      </div>
    </main>
    <script
      src="https://code.jquery.com/jquery-3.3.1.slim.min.js"
      integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"
      integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"
      integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM"
      crossorigin="anonymous"
    ></script>
    <script src="./index.js"></script>
  </body>
</html>

