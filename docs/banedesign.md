# Banedesign – brukarmanual

Banedesign lagar teesign, infoboard og caddybook for ein heil disc golf-bane.
Du legg inn banen éin gong, vel eit design, og appen lagar alle skilta med
same utsjånad – men med kvart hòl sine eigne tal, kart og tekst.

Appen er eit designverktøy, ikkje ein biletgenerator. Tee, kurv, kastelinje og
OB er objekt du plasserer sjølv, så ingenting blir gjetta.

## Slik kjem du i gang

1. **Opprett banen** – *Oversikt → Ny bane*. Vel namn, klubb, kor mange hull og
   kor mange layouts du har.
2. **Fyll inn baneinfo** – *Baneinfo*. Klubbnamn, adresse, logo, reglar og den
   URL-en QR-koden skal peike til. Dette går att på alle skilta.
3. **Legg inn tal** – *Bulk-redigering* gir deg alle hull og layouts i éin
   tabell. Raskaste måten å få inn lengde og par på.
4. **Teikn karta** – *Hull-editor*, eitt hull om gongen.
5. **Vel ein mal** – *Malar*. Trykk **Bruk på alle hull**.
6. **Eksporter** – *Generer alt*, eller *Eksport* om du vil styre formata sjølv.

!!! tip "Logg inn om du vil ha banen på fleire maskiner"
    Appen verkar utan innlogging - alt blir lagra i nettlesaren. Loggar du
    inn, blir banen lagra på serveren i tillegg, og kvar lagring legg igjen ein
    versjon du kan gå tilbake til. Sjå [Ta vare på arbeidet](#ta-vare-pa-arbeidet).

!!! tip "Demoen er der for å utforskast"
    Appen startar med **Kvam Disc Golf Course** ferdig utfylt – 18 hull og fire
    layouts. Klikk deg rundt i den før du lagar din eigen bane, så ser du
    korleis alt heng saman.

## Hullkartet

Gå til *Hull-editor* og vel eit hull.

### Last opp kartet

*Kart*-fana til høgre → **Last opp kart**. PNG, JPG, WEBP, SVG og PDF fungerer.
Flyfoto eller teikna kart – begge delar går fint.

!!! info "Kartet ditt blir aldri endra"
    Alt du teiknar legg seg som eigne lag oppå biletet. Du kan skru av
    bakgrunnen, bytte kartfil eller flytte på objekta utan å øydeleggje noko.

Under same fana justerer du lysstyrke og kontrast om kartet er for mørkt, og
set **utsnittet** – den delen av kartet som faktisk hamnar på skiltet.

### Teikn på kartet

Vel eit verktøy i verktøylinja til venstre og klikk på kartet.

| Type | Slik gjer du |
|---|---|
| Tee, kurv, mando, tre | Eitt klikk plasserer det |
| Kastelinje, OB, vatn, sti | Klikk for kvart punkt, avslutt med **Enter** |

Vil du endre ei linje etterpå, vel **Noder**-verktøyet og dra i punkta. Dra i
dei oransje håndtaka for å forme kurva.

!!! tip "Eitt kart, fire layouts"
    Nye objekt høyrer til den layouten du redigerer – sjå **Redigerer:** øvst.
    Slik kan blå og gull ha kvar sin tee og kvar si kastelinje på det same
    kartet. Vel **Felles** for objekt som gjeld alle, til dømes OB-linja.

    Knappane øvst skrur layouts av og på medan du jobbar, så du slepp å sjå
    fire kastelinjer oppå kvarandre.

### Same objekt på fleire hull

Går ei OB-linje langs ein veg som rører fleire hull? Marker ho og bruk
**Kopier til andre hull** nede i eigenskapspanelet.

## Tal for kvart hull

Nedst i hull-editoren ligg éin boks per layout med **lengde**, **par** og
**høgdeskilnad**. Verdiane er heilt åtskilde – blå kan vere 420 m par 4 medan
raud er 360 m par 3 på det same hòlet.

Skal du fylle inn mange hull, er *Bulk-redigering* raskare. Der kan du òg la
appen **foreslå par** ut frå lengda, og fylle verdiar nedover.

## Vel ein mal

*Malar* i menyen. Kvar mal er eit ferdig design. Trykk **Bruk på alle hull**,
så byter alle skilta utsjånad med ein gong.

| Serie | Uttrykk |
|---|---|
| **Valdres** | Nesten svart botn, farga verdikort per layout, stort gult hulltal |
| **Turnering** | Svart infoskinne til venstre, kartet i full høgd, divisjonskort |
| **Klar** | A4 ståande, reint og ryddig, hulltalet størst |
| **Modern Dark**, **Minimal**, **Classic** m.fl. | Nøytrale utgangspunkt |

Med brytaren **La infoboard og caddybook følgje designet** blir dei to andre
flatene laga i same fargar og fontar automatisk.

### Endre på ein mal

**Rediger** opnar mal-editoren. Dra element dit du vil ha dei, og still inn alt
i panelet til høgre.

Kvart element har ein **modulstil** – ferdige variantar du kan bytte mellom.
Layout-tala kan til dømes visast som verdikort, skrå blokkar, tabell eller
søyler. Du byggjer altså ditt eige design av ferdige delar.

### Anna papirformat

**Sideoppsett** i mal-editoren. Vel A6–A0, Letter eller skiltformat, og snu
retninga. Designet blir skalert med:

- **Tilpass proporsjonalt** – tryggast når du byter mellom ståande og liggjande
- **Strekk** – best når sideforholdet er likt, til dømes A4 → A3

## Når eitt hull treng noko eige

Malen gjeld alle hull. Men treng eitt hull QR-koden ein annan stad, eller eit
felt skjult, går du til *Hull*-fana → **Teesign for dette hullet**. Der flyttar
du enkeltfelt berre for det hòlet. Dei andre hulla står urørte.

## Infoboard og caddybook

**Infoboard** er det store oversiktsskiltet. Under *Rediger banekart* får du
heile kart-editoren for oversiktskartet – last opp banekartet og teikn
hullnummer, stiar, parkering, toalett og klubbhus oppå.

**Caddybook** set saman eit komplett hefte: framside, baneinfo, reglar, alle
hull, scorekort og bakside.

## Til trykkeriet

*Eksport* gir deg full kontroll.

| Format | Når du bruker det |
|---|---|
| **PDF** | Til trykk. Dette er det trykkeriet vil ha |
| **SVG** | Ekte vektor, om nokon skal jobbe vidare i Illustrator |
| **PNG** | 300 dpi til trykk, 150 dpi til skjerm |

For trykk kan du skru på **bleed** og **skjæremerke**. Skal du ha alle 18
skilta, blir dei pakka i éi ZIP-fil.

Forhåndsvisninga i midten viser faktisk papirstorleik, så du ser kva du får.

!!! tip "Har du det travelt?"
    *Generer alt* sjekkar banen for manglar og lagar heile settet – alle
    teesign, infoboard og caddybook – i eitt jafs.

## Ta vare på arbeidet

Arbeidet ditt ligg to stader, og dei har kvar sin jobb.

### I nettlesaren

Prosjektet blir lagra automatisk i nettlesaren medan du jobbar - òg når du er
utan dekning. På *Oversikt* finn du panelet **Lagring og sikkerhetskopi**. Der
ser du om lagringa er varig, kor mykje plass banen brukar, og dei siste
kopiane.

Appen tek ein kopi ved oppstart, kvart tiande minutt, og alltid før du byter
prosjekt. Dei 12 siste blir tekne vare på, og kvar av dei kan hentast tilbake
med eitt klikk - det du har no blir lagra som ein ny kopi først, så du kan
angre.

!!! warning "Kopiane ligg i same nettlesar"
    Dei bergar deg frå ei uheldig endring, men ikkje frå at du tømmer
    nettlesardata eller byter maskin.

### På serveren

Ved sida av ligg panelet **Server**. Loggar du inn, blir banen lagra på
serveren medan du jobbar - og då finst han att på ei anna maskin.

Panelet viser kven som er innlogga, om alt er lagra, og versjonslista. **Kvar
full lagring legg igjen ein versjon**, så du kan gå tilbake til slik banen sto
for ein time sidan. **Lagre versjon** gjer det same med ein gong.

!!! tip "Du treng ikkje logge inn"
    Appen verkar utan. Då ligg banen berre i denne nettlesaren.

    Loggar du inn, er det serveren som hugsar for deg. Set du deg ved ei anna
    maskin, kjem banen du jobba med sist opp av seg sjølv.

Står det at lagringa ikkje gjekk gjennom, ligg arbeidet likevel trygt i
nettlesaren. Neste endring prøver på nytt.

Rekkjefølgja er med vilje: nettlesaren først, serveren etterpå. Du skal kunne
teikne ferdig eit hòl ute på banen utan dekning, og finne det att når du kjem
heim.

### Prosjektfila

**Last ned prosjektfila** med jamne mellomrom. Fila inneheld *alt*: hol, kart,
bilete og malar. **Importer** les ho tilbake. Det er ho du sender til nokon
andre.

## Nyttige triks

- **Ctrl+Z** angrar, òg midt i ei flytting. Heile dratt tel som eitt steg.
- **Hald Shift** medan du dreg for å låse til vassrett eller loddrett.
- **Mellomrom + dra** panorerer kartet. Musehjulet zoomar mot peikaren.
- På nettbrett og telefon: **ein finger** flyttar, **to fingrar** zoomar.
- Set **meter per kartenhet** under *Kart* – då kan du teikne teepads i
  verkelege mål og få rett målestokk på skiltet.
- Lås logo og sponsorfelt i malen (**Lås mot hull-overstyring**), så står dei
  likt på alle skilta uansett kva du gjer seinare.
