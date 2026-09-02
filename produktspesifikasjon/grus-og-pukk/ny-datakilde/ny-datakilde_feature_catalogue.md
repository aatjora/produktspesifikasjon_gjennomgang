#### GeolAvgrLinje

generell avgrensning av geologisk objekt<br /><br /><br />-- Definition --<br />general delimitation of geological object

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>grense</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger overgang mellom ulike fenomener<br /><br />-- Definition --<br />course follwing the transition between different real world phenomena</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
    </tr>
  </tbody>
</table>

#### FelleskomponenterGrusPukk (abstrakt)

abstrakt objekt som bærer en rekke egenskaper som er fagområde-uavhengige og kan benyttes for alle objekttyper<br /><br />Merknad:<br />Spesielt i produktspesifikasjonsarbeid vil en velge egenskaper og av grensningslinjer fra denne klassen.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>datauttaksdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for uttak fra en database<br /><br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DateTime</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av kvaliteten på stedfestingen<br /><br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Posisjonskvalitet</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.målemetode</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Målemetode</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Terrengmålt: Uspesifisert måleinstrument – Målt i terrenget , uspesifisert metode/måleinstrument<br />- Terrengmålt: Totalstasjon – Målt i terrenget med totalstasjon<br />- Terrengmålt: Teodolitt og el avstandsmåler – Målt i terrenget med teodolitt og elektronisk avstandsmåler<br />- Terrengmålt: Teodolitt og målebånd – Målt i terrenget med teodolitt og målebånd<br />- Terrengmålt: Ortogonalmetoden – Målt i terrenget, ortogonalmetoden<br />- Utmål – Punkt beregnet på bakgrunn av måling mot andre punkter, slik som to avstander eller avstand og retning

-- Definition --
Point calculated on the basis of other items, such as two distances or distance + direction.<br />- Tatt fra plan – Tatt fra plan eller godkjent tiltak<br />- Annet  (denne har ingen mening, bør fjernes?) – Annet<br />- Stereoinstrument – Målt i stereoinstrument, uspesifisert instrument<br />- Aerotriangulert – Punkt beregnet ved aerotriangulering

-- Definition --
Point calculated by aerotriangulation<br />- Stereoinstrument: Analytisk plotter – Målt i stereoinstrument, analytisk plotter<br />- Stereoinstrument: Autograf – Målt i stereoinstrument, autograf, analogt instrument<br />- Stereoinstrument: Digitalt – Målt i stereoinstrument, digitalt instrument<br />- Scannet fra kart – Geometri overført fra kart maskinelt ved hjelp av skanner, uspesifisert kartmedium<br />- Skannet fra kart: Blyantoriginal – Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er blyantoriginal<br />- Skannet fra kart: Rissefolie – Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er rissefolie<br />- Skannet fra kart: Transparent folie, god kvalitet – Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er transparent folie av  god kvalitet.<br />- Skannet fra kart: Transparent folie, mindre god kvalitet – Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er transparent folie av mindre god kvalitet<br />- Skannet fra kart: Papirkopi – Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er papirkopi.<br />- Flybåren laserscanner – Målt med laserskanner fra fly<br />- Bilbåren laser – Målt med laserskanner plassert i kjøretøy<br />- Lineær referanse – brukes for objekter som er stedfestet med lineær referanse, enten disse leveres med stedfesting kun som lineære referanser, eller med koordinatgeometri avledet fra lineære referanser<br />- Digitaliseringbord: Ortofoto eller flybilde – Geometri overført fra ortofoto eller flybilde ved hjelp av manuell registrering på et digitaliseringsbord, uspesifisert bildemedium<br />- Digitaliseringbord: Ortofoto, film – Geometri overført fra ortofoto ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er film<br />- Digitaliseringbord: Ortofoto, fotokopi – Geometri overført fra ortofoto ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er fotokopi<br />- Digitaliseringbord: Flybilde, film – Geometri overført fra flybilde ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er film<br />- Digitaliseringbord: Flybilde, fotokopi – Geometri overført fra flybilde ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er fotokopi<br />- Digitalisert på skjerm fra ortofoto – Geometri overført fra ortofoto ved hjelp av manuell registrering på skjerm<br />- Digitalisert på skjerm fra satellittbilde – Geometri overført fra satellittbilde ved hjelp av manuell registrering på skjerm<br />- Digitalisert på skjerm fra andre digitale rasterdata<br />- Digitalisert på skjerm fra tolkning av seismikk<br />- Vektorisering av laserdata – Vektorisering fra laserdata, brukes også der vektoriseringen støttes av ortofoto<br />- Digitaliseringsbord: Kart – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord, medium uspesifisert<br />- Digitaliseringsbord: Kart, blyantoriginal – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er blyantoriginal<br />- Digitaliseringsbord: Kart, rissefoile – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er rissefolie<br />- Digitaliseringsbord: Kart, transparent foile, god kvalitet – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er transparent folie av god kvalitet, samkopi<br />- Digitaliseringsbord: Kart, transparent foile, mindre god kvalitet – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er transparent folie av mindre god kvalitet, samkopi<br />- Digitaliseringsbord: Kart, papirkopi – Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er papirkopi<br />- Digitalisert på skjerm fra skannet kart – Geometri overført fra kart ved hjelp av manuell registrering på skjerm, medium skannet kart (raster), samkopi<br />- Genererte data (interpolasjon) – Genererte data, interpolasjonsmetode. Ikke nærmere spesifisert<br />- Genererte data (interpolasjon): Terrengmodell – Genererte data, interpolasjonsmetode, fra terrengmodell<br />- Genererte data (interpolasjon): Vektet middel – Genererte data, interpolasjonsmetode, vektet middel<br />- Genererte data: Fra annen geometri – Genererte data: Sirkelgeometri, korridor eller annen geometri generert ut fra f.eks et punkt eller en linje (f.eks midtlinje veg)<br />- Genererte data: Generalisering<br />- Genererte data: Sentralpunkt<br />- Genererte data: Sammenknytningspunkt, randpunkt – Genererte data: Sammenknytningspunkt (f.eks mellom ulike kartlegginger), randpunkt (f.eks mellom ulike kilder til kart)<br />- Koordinater hentet fra GAB – Koordinater hentet fra GAB, forløperen til registerdelen av matrikkelen<br />- Koordinater hentet fra JREG – Koordinater hentet fra JREG, jordregisteret<br />- Beregnet – Beregnet, uspesifisert hvordan<br />- Spesielle metoder – Spesielle metoder, uspesifisert<br />- Spesielle metoder: Målt med stikkstang<br />- Spesielle metoder: Målt med waterstang<br />- Spesielle metoder: Målt med målehjul<br />- Spesielle metoder: Målt med stigningsmåler<br />- Fastsatt punkt – Punkt fastsatt ut fra et grunnlag (kart, bilde), f.eks ved partenes enighet ved en oppmålingsforretning<br />- Fastsatt ved dom eller kongelig resolusjon – Geometri fastsatt ved dom, lov, traktat eller kongelig resolusjon<br />- Annet (spesifiseres i filhode) ( bør vel fjernes, blir borte ved overføring mellom systemer) – Annet (spesifiseres i filhode)<br />- Frihåndstegning – Digitalisert ut fra frihåndstegning.  Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag<br />- Frihåndstegning på kart – Digitalisert fra krokering på kart, dvs grovt skissert på kart<br />- Frihåndstegning på skjerm – Digitalisert ut fra frihåndstegning (direkte på skjerm). Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag<br />- Treghetsstedfesting<br />- GNSS: Kodemåling, relative målinger – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, relative målinger.<br />- GNSS: Kodemåling, enkle målinger – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, enkle målinger.<br />- GNSS: Fasemåling, statisk måling – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Fasemåling statisk måling.<br />- GNSS: Fasemåling, andre metoder – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Fasemåling andre metoder.<br />- Kombinasjon av GNSS/Treghet – Kombinasjon av GPS/Treghet<br />- GNSS: Fasemåling RTK – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO).: Fasemåling RTK (realtids kinematisk måling)<br />- GNSS: Fasemåling , float-løsning – Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO). Fasemåling float-løsning<br />- Ukjent målemetode – Målemetode er ukjent</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kvalitet.nøyaktighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br /><br />Merknad:<br />Oppgitt i cm</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

#### PukkUttak

lokalitet hvor pukk tas ut (steinbrudd)

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forekomstobjektets identifikasjonskode<br /><br />Merknad: Består av kommunenummer (4 siffer), og et løpenummer (7 siffer). Ideelt sett består løpenummeret av et område nummer (3 siffer), lokalitetsnummer (2 siffer) og prøvenummer (2 siffer).<br /><br />Eksempel: 17290010101</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forekomstNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik nummerering av forekomsten som råstoffobjektet tilhører<br /><br />Merknad: Benyttes som koplingsnøkkel mellom de ulike objektene i forekomsten. Mange viktige egenskaper finnes kun på områdeobjektet som er hovedobjektet til forekomsten<br /><br />Eks. 1729001</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type råstoff som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MaterialType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Edelmetaller(Au,Ag,PGE)<br />- Jernmetaller (Fe, Mn, Ti)<br />- Jernlegeringsmetaller (Cr, Ni, Co, V, Mo, W)<br />- Basemetaller (Cu, Zn, Pbinkl. Fe-sulfider, As, Sb, Bi, Sn)<br />- Energimetaller (U, Th)<br />- Spesialmetaller (Nb, Ta, Be, Li, Sc, REE)<br />- Andre metaller<br />- Karbonatmineraler<br />- Silika<br />- Talk<br />- Feltspat<br />- Olivin<br />- Grafitt<br />- Fossilt brensel<br />- Nefelinsyenitt<br />- Magnesium mineraler<br />- Zirkon<br />- Beryllium mineraler<br />- Andre industrimineraler<br />- Blokkstein<br />- Skifer<br />- Kvernstein<br />- Brynestein<br />- Murestein<br />- Pukk/knust fjell<br />- Sand og grus<br />- Grus og andre løsmasser<br />- Skred og forvitring<br />- Skjellsand<br />- Steintipp<br />- Leire<br />- Torv<br />- Grunnvann i fjell<br />- Grunnvann i fjell og løsmasser<br />- uspesifisert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>rastoffBetydning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvorvidt forekomsten er av internasjonal, nasjonal, regional, eller kun av lokal betydning (viktighet)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>RastoffBetydning</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Internasjonal betydning – 1.  Metall- og industrimineralforekomster med dokumenterte ressurser som kan gi et signifikant bidrag til internasjonale behov
&lt;i&gt;- herunder forekomster med meget høy dokumentert in situ-verdi basert på kvalitet og tonnasje&lt;/i&gt;
&lt;i&gt;- herunder forekomster med potensial for årsproduksjon som dekker signifikant andel av behov i EU/EØS&lt;/i&gt;

2.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder dokumenterte forekomster av mineraler på EU liste over kritiske råstoffer som utnyttes eller har potensial for framtidig utnyttelse&lt;/i&gt;

3.  Forekomster av byggeråstoffer med verdi eller potensial for eksport på minst 1 millioner tonn årlig
&lt;i&gt;
&lt;/i&gt;<br />- Nasjonal betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig, betydelig fremtidig verdiskapingspotensial
&lt;i&gt;- herunder forekomster med betydelig in-situ verdi&lt;/i&gt;
&lt;i&gt;- herunder byggeråstoffer med betydelig potensial for eksport&lt;/i&gt;

2.  Mineralforekomster som har unike kvaliteter som gjør dem særlig egnet til foredlende industri
&lt;i&gt;- herunder industrimineraler og spesialmetaller av særlig høy kvalitet&lt;/i&gt;

3.  Mineralforekomster som har unike kvaliteter som byggeråstoff
&lt;i&gt;- herunder pukk- og grusforekomster med unike fysiske egenskaper &lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster med unike egenskaper og attraktivitet i det internasjonale markedet&lt;/i&gt;
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til andre viktige samfunnsområder&lt;/i&gt;

4.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til viktige norske samfunnsområder&lt;/i&gt;

5.  Forekomster som er særdeles viktig for Norges nasjonale infrastruktur
&lt;i&gt;- herunder grus- og pukkforekomster som er særlig viktig for forsyninger til større befolkningssentra i Norge&lt;/i&gt;<br />- Regional betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig fremtidig verdiskapingspotensial med in situ-verdi på mellom 100 og 1000 millioner kroner

2.  Mineralforekomster som er særdeles viktig for regional infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er særlig viktig for forsyninger innen en region&lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster som har eller har hatt særlig betydning for byggeskikk og arkitektur i en region&lt;/i&gt;<br />- Lokal betydning – 1.  Mineralforekomster som er viktig for lokal infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er viktig for forsyninger innen en kommune&lt;/i&gt;<br />- Liten lokal betydning – Forekomsten  har liten eller ingen økonomisk betydning<br />- Ikke vurdert – Forekomstens økonomiske betydning er ikke vurdert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>mineralRegistreringType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type mineralforekomst dette er i en økonomisk betraktning<br /><br />-- Definition --<br />The type of mineral occurrence.<br />-- Description --<br />EXAMPLE: prospect, occurrence, mineral deposit, ore deposit.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MineralRegistreringType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- forekomst – en mineralkonsentrasjon i jordskorpen, en anrikning eller en akkumulasjon. Kan brukes om alle typer mineralforekomster.
INSPIRE Description:
A mass of naturally occurring mineral material, e.g. metal ores or non-metallic minerals, usually of economic value, without regard to mode of origin. Accumulations of coal and petroleum may or may not be included.<br />- registrering – en økonomisk interessant malm- eller mineralanrikning
Any ore or economic mineral in any concentration found in bedrock or as float.

INSPIRE Description:<br />- prospekt – område hvor det er utsikter til å finne malm og verdifulle mineraler. Representere områder med høy sannsynlighet for funn av lite eller ikke dokumenterte mineralforekomster.
Er ofte et mulig undersøkelsesområde

INSPIRE Description:
An  area  that  is  a  potential  site  of  mineral  deposits,  based  on  preliminary exploration, previous exploration. A geologic or geophysical anomaly, especially one recommended for additional exploration.<br />- provins – geologisk provins - stort område som er enhetlig med hensyn til opptreden av ulike metaller eller mineraler. Er en områdeavgrensning rundt en eller flere større eller mindre registreringer og/eller observasjoner med potensial for mineralutvinning.



INSPIRE Description:
Geologic provinces classified by mineral resources.<br />- distrikt – geologisk distrikt, karakteristisk for ulike mineralforekomster

INSPIRE Description:
Geologic districts classified by mineral resources.<br />- felt – region eller område karakteristisk for ulike mineralforekomster. Eks Rørosfeltet

INSPIRE Description:
A region or area that possesses or is characterized by a particular mineral resource.<br />- malmsone – mineralforekomst som har form som årer eller ganger i hovedbergarten

INSPIRE Description:
A mineral deposit consisting of a zone of veins, veinlets, disseminations, or planar breccias.<br />- prosjekt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialUndertype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>underinndeling av materialtypene som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navnRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på forekomsten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>lokalNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummerering av lokalitet i forekomsten<br /><br />Merknad: Er en del av FOREKOM_ID: Eks: 1729001(01)01</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>driftForhold</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir driftsforholdene<br /><br />Merknad: Ajour pr. siste oppdatering</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DriftForhold</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ikke satt i drift (mulig fremtidig drift)<br />- I drift<br />- Sporadisk drift<br />- Nedlagt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>stedfestingVerifisert</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir om stedfestingen (koordinatene) er kontrollert og funnet i orden (verifisert)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelseURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lenke (URL) til tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>antallAnalyser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>antallet utførte kjemiske og/eller mekaniske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>typeRastoffVirksomhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir type/status på eventuell aktivitet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TypeRastoffVirksomhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Prospektering<br />- Røsking<br />- Skjerp<br />- Prøvedrift<br />- Gruvedrift<br />- Steinbrudd<br />- Mulig fremtidig uttaksområde<br />- Typelokalitet(er)<br />- Anleggspukkverk<br />- Biprodukt pukk<br />- Grustak (massetak)<br />- Utplanert massetak/endret arealbruk<br />- Observasjonslokalitet<br />- Leirtak<br />- Torvtak<br />- Naturlig grunnvannskilde<br />- Borebrønn<br />- Overvåkingsstasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FelleskomponenterGrusPukk

**Assosiasjoner**
GeolAvgrLinje – rolle: grusPukkObservasjonOgUttakAvgrensning – kardinalitet: 1..*
PukkOmr – rolle: tilhører – kardinalitet: 0..1

#### SandGrusUttak

lokalitet hvor sand og grus tas ut<br /><br />Merknad:  (massetak)

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forekomstobjektets identifikasjonskode<br /><br />Merknad: Består av kommunenummer (4 siffer), og et løpenummer (7 siffer). Ideelt sett består løpenummeret av et område nummer (3 siffer), lokalitetsnummer (2 siffer) og prøvenummer (2 siffer).<br /><br />Eksempel: 17290010101</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forekomstNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik nummerering av forekomsten som råstoffobjektet tilhører<br /><br />Merknad: Benyttes som koplingsnøkkel mellom de ulike objektene i forekomsten. Mange viktige egenskaper finnes kun på områdeobjektet som er hovedobjektet til forekomsten<br /><br />Eks. 1729001</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type råstoff som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MaterialType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Edelmetaller(Au,Ag,PGE)<br />- Jernmetaller (Fe, Mn, Ti)<br />- Jernlegeringsmetaller (Cr, Ni, Co, V, Mo, W)<br />- Basemetaller (Cu, Zn, Pbinkl. Fe-sulfider, As, Sb, Bi, Sn)<br />- Energimetaller (U, Th)<br />- Spesialmetaller (Nb, Ta, Be, Li, Sc, REE)<br />- Andre metaller<br />- Karbonatmineraler<br />- Silika<br />- Talk<br />- Feltspat<br />- Olivin<br />- Grafitt<br />- Fossilt brensel<br />- Nefelinsyenitt<br />- Magnesium mineraler<br />- Zirkon<br />- Beryllium mineraler<br />- Andre industrimineraler<br />- Blokkstein<br />- Skifer<br />- Kvernstein<br />- Brynestein<br />- Murestein<br />- Pukk/knust fjell<br />- Sand og grus<br />- Grus og andre løsmasser<br />- Skred og forvitring<br />- Skjellsand<br />- Steintipp<br />- Leire<br />- Torv<br />- Grunnvann i fjell<br />- Grunnvann i fjell og løsmasser<br />- uspesifisert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>rastoffBetydning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvorvidt forekomsten er av internasjonal, nasjonal, regional, eller kun av lokal betydning (viktighet)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>RastoffBetydning</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Internasjonal betydning – 1.  Metall- og industrimineralforekomster med dokumenterte ressurser som kan gi et signifikant bidrag til internasjonale behov
&lt;i&gt;- herunder forekomster med meget høy dokumentert in situ-verdi basert på kvalitet og tonnasje&lt;/i&gt;
&lt;i&gt;- herunder forekomster med potensial for årsproduksjon som dekker signifikant andel av behov i EU/EØS&lt;/i&gt;

2.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder dokumenterte forekomster av mineraler på EU liste over kritiske råstoffer som utnyttes eller har potensial for framtidig utnyttelse&lt;/i&gt;

3.  Forekomster av byggeråstoffer med verdi eller potensial for eksport på minst 1 millioner tonn årlig
&lt;i&gt;
&lt;/i&gt;<br />- Nasjonal betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig, betydelig fremtidig verdiskapingspotensial
&lt;i&gt;- herunder forekomster med betydelig in-situ verdi&lt;/i&gt;
&lt;i&gt;- herunder byggeråstoffer med betydelig potensial for eksport&lt;/i&gt;

2.  Mineralforekomster som har unike kvaliteter som gjør dem særlig egnet til foredlende industri
&lt;i&gt;- herunder industrimineraler og spesialmetaller av særlig høy kvalitet&lt;/i&gt;

3.  Mineralforekomster som har unike kvaliteter som byggeråstoff
&lt;i&gt;- herunder pukk- og grusforekomster med unike fysiske egenskaper &lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster med unike egenskaper og attraktivitet i det internasjonale markedet&lt;/i&gt;
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til andre viktige samfunnsområder&lt;/i&gt;

4.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til viktige norske samfunnsområder&lt;/i&gt;

5.  Forekomster som er særdeles viktig for Norges nasjonale infrastruktur
&lt;i&gt;- herunder grus- og pukkforekomster som er særlig viktig for forsyninger til større befolkningssentra i Norge&lt;/i&gt;<br />- Regional betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig fremtidig verdiskapingspotensial med in situ-verdi på mellom 100 og 1000 millioner kroner

2.  Mineralforekomster som er særdeles viktig for regional infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er særlig viktig for forsyninger innen en region&lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster som har eller har hatt særlig betydning for byggeskikk og arkitektur i en region&lt;/i&gt;<br />- Lokal betydning – 1.  Mineralforekomster som er viktig for lokal infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er viktig for forsyninger innen en kommune&lt;/i&gt;<br />- Liten lokal betydning – Forekomsten  har liten eller ingen økonomisk betydning<br />- Ikke vurdert – Forekomstens økonomiske betydning er ikke vurdert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>mineralRegistreringType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type mineralforekomst dette er i en økonomisk betraktning<br /><br />-- Definition --<br />The type of mineral occurrence.<br />-- Description --<br />EXAMPLE: prospect, occurrence, mineral deposit, ore deposit.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MineralRegistreringType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- forekomst – en mineralkonsentrasjon i jordskorpen, en anrikning eller en akkumulasjon. Kan brukes om alle typer mineralforekomster.
INSPIRE Description:
A mass of naturally occurring mineral material, e.g. metal ores or non-metallic minerals, usually of economic value, without regard to mode of origin. Accumulations of coal and petroleum may or may not be included.<br />- registrering – en økonomisk interessant malm- eller mineralanrikning
Any ore or economic mineral in any concentration found in bedrock or as float.

INSPIRE Description:<br />- prospekt – område hvor det er utsikter til å finne malm og verdifulle mineraler. Representere områder med høy sannsynlighet for funn av lite eller ikke dokumenterte mineralforekomster.
Er ofte et mulig undersøkelsesområde

INSPIRE Description:
An  area  that  is  a  potential  site  of  mineral  deposits,  based  on  preliminary exploration, previous exploration. A geologic or geophysical anomaly, especially one recommended for additional exploration.<br />- provins – geologisk provins - stort område som er enhetlig med hensyn til opptreden av ulike metaller eller mineraler. Er en områdeavgrensning rundt en eller flere større eller mindre registreringer og/eller observasjoner med potensial for mineralutvinning.



INSPIRE Description:
Geologic provinces classified by mineral resources.<br />- distrikt – geologisk distrikt, karakteristisk for ulike mineralforekomster

INSPIRE Description:
Geologic districts classified by mineral resources.<br />- felt – region eller område karakteristisk for ulike mineralforekomster. Eks Rørosfeltet

INSPIRE Description:
A region or area that possesses or is characterized by a particular mineral resource.<br />- malmsone – mineralforekomst som har form som årer eller ganger i hovedbergarten

INSPIRE Description:
A mineral deposit consisting of a zone of veins, veinlets, disseminations, or planar breccias.<br />- prosjekt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialUndertype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>underinndeling av materialtypene som kan være/er gjenstand for utvinning<br /><br />Merknad: Er en mer detaljert inndeling av det råstoff som utvinnes (hovedsakelig kjemiske elementer (Cu, Pb, Zn osv.) og mineralnavn)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navnRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på råstoffobjekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>lokalNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummerering av lokalitet i forekomsten<br /><br />Merknad: Er en del av FOREKOM_ID: Eks: 1729001(01)01</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>losmassetype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>kvartærgeologiske løsmassetyper (jordartstyper)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Losmassetype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Morenemateriale, uspesifisert – Materiale plukket opp, transportert og avsatt av isbreer. Det er vanligvis, dårlig sortert og kan inneholde alt fra leir til stein og blokk. Mektighet, morenetype og overflateform kan variere. Benyttes ved kartframstilling i svært små målestokker.<br />- Morenemateriale, sammenhengende dekke, stedvis med stor mektighet – Materiale plukket opp, transportert og avsatt av isbreer, vanligvis hardt sammenpakket, dårlig sortert og kan inneholde alt fra leir til stein og blokk. Moreneavsetninger med tykkelse fra 0,5 m til flere ti-talls meter. Det er få eller ingen fjellblotninger i området.<br />- Morenemateriale, usammenhengende eller tynt dekke over berggrunnen – Materiale plukket opp, transportert og avsatt av isbreer. Det er vanligvis hardt sammenpakket, dårlig sortert og kan inneholde alt fra leir til stein og blokk. Områder med grunnlendte moreneavsetninger/hyppige fjellblotninger. Tykkelsen på avsetningene er normalt mindre enn 0,5 m, men den kan helt lokalt være noe mer.<br />- Moreneleire – Morenemateriale med særlig høyt leir- og siltinnhold, oftest meget kompakt.<br />- Avsmeltningsmorene (Ablasjonsmorene) – Hauger og rygger med løst lagret, delvis vannbehandlet og noe sortert morenemateriale avsatt fra stagnerende breer (dødis). Terrenget er preget av haug- og ryggformer med vekslende orientering.<br />- Randmorene/randmorenebelte – Rygger eller belter av morenemateriale som er skjøvet opp foran brefronten. Materialet er usortert og inneholder alle kornstørrelser fra leir til blokk. Noen steder kan morenematerialet finnes i veksling med breelvmateriale.<br />- Drumlin – Langstrakt, rettlinjet morenerygg dannet langs isbevegelsesretningen i bunnen av en bre. Ofte stor tykkelse, avrundet form og lengden kan være opp til noen km.<br />- Rogenmorene – Rygger av morenemateriale, orientert på tvers av brebevegelsen.<br />- Breelvavsetning (Glasifluvial avsetning) – Materiale transportert og avsatt av breelver. Sedimentet består av sorterte, ofte skråstilte lag av forskjellig kornstørrelse fra fin sand til stein og blokk. Breelvavsetninger har ofte klare overflateformer som terrasser, rygger og vifter. Mektigheten er ofte flere ti-talls meter.<br />- Breelv- og elveavsetning – Materiale transportert og avsatt av elver eller breelver. Sedimentet består av sorterte lag av forskjellig kornstørrelse fra fin sand til grus og stein. Det er ikke skilt mellom breelv- og elveavsetninger. Brukes kun i spesielle tilfeller.<br />- Ryggformet breelvavsetning (Esker) – Sortert og lagdelt materiale, vesentlig sand og grus, avsatt i tunneler eller sprekker i breen. Der avsetningen er stor nok til å danne figur på kartet brukes fargen for breelvavsetninger til å angi utbredelsen og eskersymbolet til å angi ryggformen.<br />- Haugformet breelvavsetning (Kame) – Materiale avsatt av smeltevann i hulrom i breen. Store avsetninger gis fargen for breelvavsetninger i kombinasjon med symbol for kame.<br />- Bresjø-/eller brekammeravsetning (Glasilakustrin avsetning) – Finkornig materiale avsatt i bresjø eller vannfylt brekammer hvor tykkelsen er mer enn 0,5 m og arealdekningen er stor nok til å danne figur på kartet. Mektigheten kan være flere ti-talls meter.<br />- Breelv- og bresjø-/brekammeravsetning (Glasifluvial og glasilakustrin avsetning) – Materiale avsatt av breelv eller i bredemte sjøer/brekammer. Det er ikke skilt mellom breelv- og bresjø-/kammeravsetninger.<br />- Innsjøavsetning (Lakustrin avsetning) – Materiale avsatt i innsjøer hvor tykkelsen er mer enn 0,5 m.<br />- Bresjø-/brekammer og innsjøavsetning (Glasilakustrin og lakustrin avsetning) – Benyttes hvis en ønsker å slå sammen de to avsetningstypene. I tilfelle brukes ikke separate farger for bresjø og innsjø på det samme kartbladet.<br />- Strandavsetning, innsjø og/eller bresjø – Strandvaskede sedimenter med mektighet større enn 0,5 m, dannet ved bølgeaktivitet i ferskvann. Materialet er ofte rundet og godt sortert. Kornstørrelsen varierer, men sand og grus er vanligst.<br />- Hav- og fjordavsetning, uspesifisert – Benyttes ved kartframstilling i svært små målestokker der en ikke skiller etter mektighet.<br />- Hav- og fjordavsetning, sammenhengende dekke, ofte med stor mektighet – Finkornige, marine avsetninger med mektighet fra 0,5 m til flere ti-tall meter. Avsetningstypen omfatter også skredmasser fra kvikkleireskred, ofte angitt med tilleggssymbol. Det er få eller ingen fjellblotninger i området.<br />- Marin strandavsetning, sammenhengende dekke – Marine strandvaskede sedimenter med mektighet større enn 0,5 m, dannet av bølge- og strømaktivitet i strandsonen, stedvis som strandvoller. Materialet er ofte rundet og godt sortert. Kornstørrelsen varierer fra sand til blokk, men sand og grus er vanligst. Strandavsetninger ligger som et forholdsvis tynt dekke over berggrunn eller andre sedimenter.<br />- Hav- og fjordavsetning  og strandavsetning, usammenhengende eller tynt dekke over berggrunnen – Grunnlendte områder/hyppige fjellblotninger. Tykkelsen på avsetningene er normalt mindre enn 0,5 m, men den kan helt lokalt være noe større. Det er ikke skilt mellom hav-, fjord- og strandavsetning. Kornstørrelser angis normalt ikke, men kan være alt fra leir til blokk.<br />- Skjellsand – Avsetning som i stor grad består av knuste skall av kalkutskillende organismer. Er en type av bioklastisk materiale. Kornstørrelse varierer fra nesten hele skall til sand. Det kan være ansamlet store mengder av skjellsand i umiddelbar nærhet av gode skjellvekstområder.<br />- Marin gytje – Avsetning som består av finkornig materiale, silt og leir med høyt organisk innhold. Det organiske materialet er primærprodusert i vannmassene. Marin gytje finnes i områder hvor det er liten materialtransport fra land. Brukes sjelden.<br />- Elve- og bekkeavsetning (Fluvial avsetning) – Materiale som er transportert og avsatt av elver og bekker. De mest typiske formene er elvesletter, terrasser og vifter. Sand og grus dominerer, og materialet er sortert og rundet. Mektigheten varierer fra 0,5 til mer enn 10 m.<br />- Elveavsetning, sammenhengende dekke – Materiale som er transportert og avsatt av elver og bekker. De mest typiske formene er elvesletter, terrasser og vifter. Sand og grus dominerer, og materialet er sortert og rundet. Brukes kun i spesielle tilfeller.<br />- Elveavsetning, usammenhengende/tynt dekke – Grunnlendte områder med elveavsetninger. Brukes kun i spesielle tilfeller.<br />- Flomavsetning (uspesifisert) – Brukes for spesielle sedimenter avsatt ved plutselig uttapning av bresjøer.<br />- Flomavsetning, sammenhengende – Brukes for spesielle sedimenter avsatt ved plutselig uttapning av bresjøer.<br />- Flomavsetning, usammenhengende/tynt – Brukes for spesielle sedimenter avsatt ved plutselig uttapning av bresjøer. Tykkelse mindre enn 0,5 m.<br />- Vindavsetning (Eolisk avsetning) – Flygesand med tykkelse mer enn 0,5 m.<br />- Forvitringsmateriale, ikke inndelt etter mektighet – Løsmasser dannet på stedet ved fysisk eller kjemisk nedbryting av berggrunnen. Gradvis overgang til underliggende fast fjell. Brukes når en ikke skiller mellom sammenhengende og usammenhengende dekke av denne avsetningstypen.<br />- Forvitringsmateriale, sammenhengende dekke – Løsmasser dannet på stedet ved fysisk eller kjemisk nedbryting av berggrunnen. Tykkelsen er mer enn 0,5 m.<br />- Forvitringsmateriale, usammenhengende eller tynt dekke over berggrunnen – Løsmasser dannet på stedet ved fysisk eller kjemisk nedbryting av berggrunnen. Grunnlendt område med tallrike fjellblotninger.<br />- Forvitringsmateriale, stein- og blokkrikt, dannet ved frostsprengning – Blokkhav, oftest i fjellområder.<br />- Skredmateriale, ikke inndelt etter mektighet – Avsetninger dannet ved steinsprang, fjellskred, snø- eller løsmasseskred fra bratte dalsider. Uspesifisert tykkelse.<br />- Skredmateriale, sammenhengende dekke, stedvis med stor mektighet – Avsetninger dannet ved steinsprang, fjellskred, snøskred eller løsmasseskred fra bratte dalsider. Symbol viser dominerende skredtype. Tykkelsen er mer enn 0,5 m og det er få fjellblotninger i området.<br />- Skredmateriale, usammenhengende eller tynt dekke over berggrunnen – Grunnlendte områder med avsetninger fra steinsprang, fjellskred, snø- og løsmasseskred fra bratte dalsider. Symbol viser dominerende skredtype. Tykkelse mindre enn 0,5 m.<br />- Steinbreavsetning – Steinur som inneholder/har inneholdt is og derfor er i bevegelse/har vært i bevegelse som en vanlig bre. Avsetningstypen dannes under permafrostforhold.<br />- Torv og myr (Organisk materiale) – Organisk jord dannet av døde planterester, med mektigheter større enn 0,5 m. Det skilles ikke mellom ulike torvtyper.<br />- Humusdekke/tynt torvdekke over berggrunn – Områder hvor humusdekket ligger rett på berggrunnen. Mektigheten av humusdekket er vanligvis 0,2 - 0,5 m, men kan lokalt være tykkere. Fjellblotninger opptrer hyppig innen slike områder. Fjellblotninger opptrer hyppig innen slike områder.<br />- Usammenhengende eller tynt løsmassedekke over berggrunnen, flere løsmassetyper, uspesifisert – Forskjellige sedimenter som danner et tynt eller usammenhengende dekke over berggrunnen. Denne betegnelsen brukes bare i spesielle tilfeller når en ikke velger å skille mellom ulike typer av løsmasser.<br />- Sammenhengende løsmassedekke av flere jordarter – Vanligvis skredmateriale med morenemateriale, forvitringsmateriale, torv og humus sterkt blanda ved skråningsprosesser. Brukes kun i spesielle tilfeller der det er meget vanskelig å skille mellom opprinnelige løsmassetyper.<br />- Bart fjell/fjell med tynt torvdekke, uspesifisert – Brukes når en ikke velger å skille mellom bart fjell og humusdekke eller tynt torvdekke over berggrunnen.<br />- Fyllmasse (antropogent materiale) – Løsmasser tilført eller sterkt påvirket av menneskers aktivitet, vesentlig i urbane områder.<br />- Steintipp – Tilførte steinmasser.<br />- Menneskepåvirket materiale, ikke nærmere spesifisert – Dominerende stedegne masser, omarbeidet i overflaten.<br />- Bart fjell – Brukes om områder som stort sett mangler løsmasser, mer enn 50 % av arealet er fjell i dagen.<br />- Bart fjell/fjell med usammenhengende eller  tynt løsmassedekke – Brukes på oversiktskart der bart fjell slås sammen med alle typer tynt eller usammenhengende løsmassedekke.<br />- Marin suspensjonsavsetning – Finkornige (leire, silt) sedimenter transportert og avsatt fra suspensjon. Draperer vanligvis underliggende sedimenter eller fjell og er oftest lagdelt.<br />- Marin bunnstrømavsetning – Sedimenter som består av sand og grus transportert og avsatt fra bunnstrømmer. Dekker bunnen av undersjøiske kanaler laget av bunnstrømmer. Har ofte kryss-sjiktet og lentikulær- sjiktet indre struktur.<br />- Glasimarin avsetning – Hovedsakelig finkornige suspensjonsavsetninger (silt, leire) avsatt i nærhet av is/isbreer. Kan være påvirket av bunnstrømmer og utjevner topografien mer enn draperer. Forekommer i mektige lag i områder på kontinentalhyllen langs kysten og i fjorder<br />- Iskontaktavsetning – Sedimenter avsatt i kontakt med is. Kan være morene, glasifluvialt materiale, eller en blanding av glasialt avsatte sedimenter. Kornstørrelsen veksler mellom leire og grus alt etter hvilke prosesser som virket.<br />- Utvaskingslag – Sedimenter bestående av sand, grus og bergartsfragmenter etter at finstoffet er vasket vekk av bølger og strøm. Danner et dekkende lag over morene eller andre jordarter med stor variasjon i kornstørrelser.<br />- Glasifluvial deltaavsetning (marin) – Sedimenter transportert av breelver og avsatt i hav, bresjø eller innsjø.<br />- Fluvial deltaavsetning – Sedimenter avsatt ved utløpet av en elv i en fjord, innsjø eller i havet. Kornstørrelsen er ofte i sandfraksjonen nær elveutløpet og mer finkornig på dypere vann. Har typisk skrålaging med helling i strømretningen.<br />- Tidevannsavsetning – Avsetning dannet i kystnære områder ved tidevannstransport. Sedimentene er sandige til leirholdige med typiske strukturer som sanddyner, rifler, kryss-sjikting, mikro-kryss-sjikting, flasersjikting og lentikulær sjikting.<br />- Estuarin avsetning – Et sediment avsatt i brakkvann i et estuarie. Sedimentet er karakterisert av finkornig materiale (silt, leire) av marin og fluvial opprinnelse blandet med en høy andel rester av terrestrisk organisk materiale.<br />- Levé avsetning (marin) – Avsetning dannet som en forhøyning av sedimenter langs en eller begge sidene  av en undersjøisk kanal (kløft, viftedal eller dyphavskanal). Avsetningen kan ha varierende kornstørrelse, fra finkornig (leir) til nokså grovt materiale (sand).<br />- Grunnmarin avsetning – Sedimenter avsatt i turbulent grunt marint miljø der det fineste materialet er vasket ut og transportert til dypere vann av strømmer og bølger. Består av sand, grus og stein. I områder med mye sand kan sandbølger bygges med en karakteristisk kryss-sjikting og skrålaging.<br />- Konturittavsetning – Klastiske sedimenter transportert og avsatt av kontur-strømmer langs egga kanten. Består av fint, velsortert materiale (silt og leir). Avsetningene har vanligvis horisontal- eller kryss-sjiktning og normal- eller omvendt gradering.<br />- Turbitittavsetning – Avsetninger dannet ved sedimenttransport og utfelling fra en turbidittstrøm.  Består av materiale i kornstørrelse fra leire til sand og er ofte karakterisert ved normalgradert lagning og moderat til dårlig sortering. Finnes oftest ved foten av skråninger med stor mektighet av løse sedimenter (for eksempel langs kontinentalskråningen).<br />- Debrisstrømavsetning – Avsetning fra en flytende masse av stein, jord og slam. Den består av usortert materiale der mer enn halvparten av partiklene er større enn sandstørrelse.<br />- Undersjøisk vifteavsetning – En konisk eller vifteformet avsetning beliggende ved munningen av en undersjøisk kløft. Består for det meste av fine sedimenter (leire, silt). Viften har en finlaget indre struktur med en svak helling av lagene mot dyphavet.<br />- Kanalsavsetning – Sedimenter avsatt i en kanal. Avsetningene vil vanligvis bestå av relativt grove sedimenter (sand, grus)<br />- Dypmarin avsetning – Samlebetegnelse på dyphavssedimenter. Kan være både konturittisk, hemipelagisk, eupelagisk osv. Dette er fine sedimenter bunnfelt utenfor kontinentalmarginen. Består i stor grad av leire og rester av pelagiske organismer.<br />- Bioklastisk avsetning – Sediment som for en stor del består av små partikler av biologisk opprinnelse (skjell, korall). Kornstørrelsen kan variere fra sand til hele skjell eller korallkolonier. Forekommer i begrensete områder der vekstforholdene har vært optimale over lengre tid og mengden av annet klastisk materiale liten.<br />- Vulkanosedimentær avsetning – Avsetning som består av materiale av vulkansk opprinnelse. Alt etter kornstørrelse kan sedimentene deles inn i vulkansk aske, lapilli (2-64 mm) og breksje (&gt;64mm).<br />- Lagdelte sedimenter (&gt;1 m) over debrisstrøm – Lagdelte sedimenter (&gt;1m) over debrisstrømavsetning.<br />- Skredmateriale, dekket av yngre sedimenter<br />- Skredmateriale, delvis dekket av yngre sedimenter<br />- Skredmateriale og hemipelagiske avsetninger – Veksling mellom skredavsetninger og hemipelagiske avsetninger. Hemipelagiske avsetninger består stort sett av finkornet materiale, delvis produsert i vannmassene lokalt, og delvis tilført utenifra.<br />- Uspesifisert marin avsetning – Marin avsetning med ukjent opprinnelse.<br />- Jordskredavsetning, sammenhengende dekke, stedvis med stor mektighet – Avsetning som dannes når løsmasser i bratt terreng løsner og raser nedover. Danner ofte karakteristiske vifte- eller tungelignende former.<br />- Jordskredavsetning, usammenhengende eller tynt dekke – Grunnlendt avsetning som dannes når løsmasser i bratt terreng løsner og raser nedover.<br />- Leirskredavsetning, sammenhengende dekke, stedvis med stor mektighet – Avsetning som dannes når leirholdige sedimenter løsner og glir ut.<br />- Leirskredavsetning, usammenhengende eller tynt dekke over berggrunnen – Avsetning som dannes når leirholdige sedimenter løsner og glir ut.<br />- Fjellskredavsetning, sammenhengende dekke, stedvis med stor mektighet – Dannes når store fjellparti løsner og med kolossal kraft går ned i daler og fjorder. Består mest av kantete blokker.<br />- Fjellskredavsetning, usammenhengende eller tynt dekke – Grunnlendte områder med fjellskredmateriale.<br />- Steinsprangavsetning, sammenhengende dekke, stedvis med stor mektighet – Materiale som har løsnet fra fast fjell og over tid akkumulert som bratte urer ved foten av skråninger. Materialet varierer fra sand til blokk, med økende kornstørrelse nedover skråningen.<br />- Steinsprangavsetning, usammenhengende eller tynt dekke – Grunnlendte områder med steinsprangmateriale.<br />- Snøskredavsetning, sammenhengende dekke, stedvis med stor mektighet – Dannes i områder med gjentatte snøskred og har ofte vifteform.<br />- Snøskredavsetning, usammenhengende eller tynt dekke – Grunnlendte områder med snøskredmateriale.<br />- Fjellskred-/steinsprangavsetning, sammenhengende dekke, stedvis med stor mektighet – Materiale bestående av steinblokker fra større fjellparti som har løsnet og rast ned. Består hovedsakelig av usortert grovt materiale (stein og blokk) og finnes oftest ved foten av skrenter/fjellsider.<br />- Fjellskred-/steinsprangavsetning, usammenhengende eller tynt dekke – Grunnlendte områder med fjellskred-/steinsprangmateriale.<br />- Snø- og jordskredavsetning, sammenhengende dekke – Dannes i områder med vekslende snø- og jordskred.<br />- Snø- og jordskredavsetning, usammenhengende eller tynt dekke – Grunnlendte områder med snøskredmateriale og jordskredmateriale.<br />- Jordskred- og steinsprangavsetning, sammenhengende dekke – Dannes i bratt terreng der både jordskred og steinsprang forekommer.<br />- Jordskred- og steinsprangavsetning, usammenhengende eller tynt dekke – Grunnlendte områder med jordskred- og steinsprangmateriale.<br />- Finkornig organiskholdig sigejord – Sterkt frostpåvirket blandingsmateriale som beveger seg sakte nedover slake skråninger, dannet fra en eller flere opprinnelig finstoffholdige løsmassetyper.<br />- Steinrikt sigende skråningsmateriale – Grovkornig frostpåvirket blandingsmateriale som beveger seg sakte nedover skråninger, dannet fra forvitret fjell, skråningsmateriale eller morenemateriale.</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>driftForhold</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir driftsforholdene<br /><br />Merknad: Ajour pr. siste oppdatering</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>DriftForhold</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ikke satt i drift (mulig fremtidig drift)<br />- I drift<br />- Sporadisk drift<br />- Nedlagt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>stedfestingVerifisert</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir om stedfestingen (koordinatene) er kontrollert og funnet i orden (verifisert)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelseURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lenke (URL) til tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>antallAnalyser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>antallet utførte kjemiske og/eller mekaniske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>typeRastoffVirksomhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir type/status på eventuell aktivitet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TypeRastoffVirksomhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Prospektering<br />- Røsking<br />- Skjerp<br />- Prøvedrift<br />- Gruvedrift<br />- Steinbrudd<br />- Mulig fremtidig uttaksområde<br />- Typelokalitet(er)<br />- Anleggspukkverk<br />- Biprodukt pukk<br />- Grustak (massetak)<br />- Utplanert massetak/endret arealbruk<br />- Observasjonslokalitet<br />- Leirtak<br />- Torvtak<br />- Naturlig grunnvannskilde<br />- Borebrønn<br />- Overvåkingsstasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FelleskomponenterGrusPukk

**Assosiasjoner**
GeolAvgrLinje – rolle: grusPukkObservasjonOgUttakAvgrensning – kardinalitet: 1..*
SandGrusOmr – rolle: tilhører – kardinalitet: 0..1

#### SandGrusObservasjon

lokalitet som gir opplysninger om en sand/grusressurs

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forekomstobjektets identifikasjonskode<br /><br />Merknad: Består av kommunenummer (4 siffer), og et løpenummer (7 siffer). Ideelt sett består løpenummeret av et område nummer (3 siffer), lokalitetsnummer (2 siffer) og prøvenummer (2 siffer).<br /><br />Eksempel: 17290010101</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forekomstNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik nummerering av forekomsten som råstoffobjektet tilhører<br /><br />Merknad: Benyttes som koplingsnøkkel mellom de ulike objektene i forekomsten. Mange viktige egenskaper finnes kun på områdeobjektet som er hovedobjektet til forekomsten<br /><br />Eks. 1729001</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type råstoff som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MaterialType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Edelmetaller(Au,Ag,PGE)<br />- Jernmetaller (Fe, Mn, Ti)<br />- Jernlegeringsmetaller (Cr, Ni, Co, V, Mo, W)<br />- Basemetaller (Cu, Zn, Pbinkl. Fe-sulfider, As, Sb, Bi, Sn)<br />- Energimetaller (U, Th)<br />- Spesialmetaller (Nb, Ta, Be, Li, Sc, REE)<br />- Andre metaller<br />- Karbonatmineraler<br />- Silika<br />- Talk<br />- Feltspat<br />- Olivin<br />- Grafitt<br />- Fossilt brensel<br />- Nefelinsyenitt<br />- Magnesium mineraler<br />- Zirkon<br />- Beryllium mineraler<br />- Andre industrimineraler<br />- Blokkstein<br />- Skifer<br />- Kvernstein<br />- Brynestein<br />- Murestein<br />- Pukk/knust fjell<br />- Sand og grus<br />- Grus og andre løsmasser<br />- Skred og forvitring<br />- Skjellsand<br />- Steintipp<br />- Leire<br />- Torv<br />- Grunnvann i fjell<br />- Grunnvann i fjell og løsmasser<br />- uspesifisert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialUndertype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>underinndeling av materialtypene som kan være/er gjenstand for utvinning<br /><br />Merknad: Er en mer detaljert inndeling av det råstoff som utvinnes (hovedsakelig kjemiske elementer (Cu, Pb, Zn osv.) og mineralnavn)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navnRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på råstoffobjekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelseURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lenke (URL) til tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>antallAnalyser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>antallet utførte kjemiske og/eller mekaniske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FelleskomponenterGrusPukk

**Assosiasjoner**
SandGrusOmr – rolle: tilhører – kardinalitet: 0..1

#### PukkObservasjon

lokalitet som gir opplysninger om en pukksteinressurs

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forekomstobjektets identifikasjonskode<br /><br />Merknad: Består av kommunenummer (4 siffer), og et løpenummer (7 siffer). Ideelt sett består løpenummeret av et område nummer (3 siffer), lokalitetsnummer (2 siffer) og prøvenummer (2 siffer).<br /><br />Eksempel: 17290010101</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forekomstNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik nummerering av forekomsten som råstoffobjektet tilhører<br /><br />Merknad: Benyttes som koplingsnøkkel mellom de ulike objektene i forekomsten. Mange viktige egenskaper finnes kun på områdeobjektet som er hovedobjektet til forekomsten<br /><br />Eks. 1729001</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type råstoff som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MaterialType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Edelmetaller(Au,Ag,PGE)<br />- Jernmetaller (Fe, Mn, Ti)<br />- Jernlegeringsmetaller (Cr, Ni, Co, V, Mo, W)<br />- Basemetaller (Cu, Zn, Pbinkl. Fe-sulfider, As, Sb, Bi, Sn)<br />- Energimetaller (U, Th)<br />- Spesialmetaller (Nb, Ta, Be, Li, Sc, REE)<br />- Andre metaller<br />- Karbonatmineraler<br />- Silika<br />- Talk<br />- Feltspat<br />- Olivin<br />- Grafitt<br />- Fossilt brensel<br />- Nefelinsyenitt<br />- Magnesium mineraler<br />- Zirkon<br />- Beryllium mineraler<br />- Andre industrimineraler<br />- Blokkstein<br />- Skifer<br />- Kvernstein<br />- Brynestein<br />- Murestein<br />- Pukk/knust fjell<br />- Sand og grus<br />- Grus og andre løsmasser<br />- Skred og forvitring<br />- Skjellsand<br />- Steintipp<br />- Leire<br />- Torv<br />- Grunnvann i fjell<br />- Grunnvann i fjell og løsmasser<br />- uspesifisert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navnRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på forekomsten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>stedfestingVerifisert</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir om stedfestingen (koordinatene) er kontrollert og funnet i orden (verifisert)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Boolean</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelseURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lenke (URL) til tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>antallAnalyser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>antallet utførte kjemiske og/eller mekaniske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FelleskomponenterGrusPukk

**Assosiasjoner**
PukkOmr – rolle: tilhører – kardinalitet: 0..1

#### SandGrusOmr

område som antas å inneholde potensielle sand- og grusressurser

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forekomstobjektets identifikasjonskode<br /><br />Merknad: Består av kommunenummer (4 siffer), og et løpenummer (7 siffer). Ideelt sett består løpenummeret av et område nummer (3 siffer), lokalitetsnummer (2 siffer) og prøvenummer (2 siffer).<br /><br />Eksempel: 17290010101</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forekomstNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik nummerering av forekomsten som råstoffobjektet tilhører<br /><br />Merknad: Benyttes som koplingsnøkkel mellom de ulike objektene i forekomsten. Mange viktige egenskaper finnes kun på områdeobjektet som er hovedobjektet til forekomsten<br /><br />Eks. 1729001</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type råstoff som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MaterialType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Edelmetaller(Au,Ag,PGE)<br />- Jernmetaller (Fe, Mn, Ti)<br />- Jernlegeringsmetaller (Cr, Ni, Co, V, Mo, W)<br />- Basemetaller (Cu, Zn, Pbinkl. Fe-sulfider, As, Sb, Bi, Sn)<br />- Energimetaller (U, Th)<br />- Spesialmetaller (Nb, Ta, Be, Li, Sc, REE)<br />- Andre metaller<br />- Karbonatmineraler<br />- Silika<br />- Talk<br />- Feltspat<br />- Olivin<br />- Grafitt<br />- Fossilt brensel<br />- Nefelinsyenitt<br />- Magnesium mineraler<br />- Zirkon<br />- Beryllium mineraler<br />- Andre industrimineraler<br />- Blokkstein<br />- Skifer<br />- Kvernstein<br />- Brynestein<br />- Murestein<br />- Pukk/knust fjell<br />- Sand og grus<br />- Grus og andre løsmasser<br />- Skred og forvitring<br />- Skjellsand<br />- Steintipp<br />- Leire<br />- Torv<br />- Grunnvann i fjell<br />- Grunnvann i fjell og løsmasser<br />- uspesifisert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>rastoffBetydning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvorvidt forekomsten er av internasjonal, nasjonal, regional, eller kun av lokal betydning (viktighet)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>RastoffBetydning</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Internasjonal betydning – 1.  Metall- og industrimineralforekomster med dokumenterte ressurser som kan gi et signifikant bidrag til internasjonale behov
&lt;i&gt;- herunder forekomster med meget høy dokumentert in situ-verdi basert på kvalitet og tonnasje&lt;/i&gt;
&lt;i&gt;- herunder forekomster med potensial for årsproduksjon som dekker signifikant andel av behov i EU/EØS&lt;/i&gt;

2.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder dokumenterte forekomster av mineraler på EU liste over kritiske råstoffer som utnyttes eller har potensial for framtidig utnyttelse&lt;/i&gt;

3.  Forekomster av byggeråstoffer med verdi eller potensial for eksport på minst 1 millioner tonn årlig
&lt;i&gt;
&lt;/i&gt;<br />- Nasjonal betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig, betydelig fremtidig verdiskapingspotensial
&lt;i&gt;- herunder forekomster med betydelig in-situ verdi&lt;/i&gt;
&lt;i&gt;- herunder byggeråstoffer med betydelig potensial for eksport&lt;/i&gt;

2.  Mineralforekomster som har unike kvaliteter som gjør dem særlig egnet til foredlende industri
&lt;i&gt;- herunder industrimineraler og spesialmetaller av særlig høy kvalitet&lt;/i&gt;

3.  Mineralforekomster som har unike kvaliteter som byggeråstoff
&lt;i&gt;- herunder pukk- og grusforekomster med unike fysiske egenskaper &lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster med unike egenskaper og attraktivitet i det internasjonale markedet&lt;/i&gt;
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til andre viktige samfunnsområder&lt;/i&gt;

4.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til viktige norske samfunnsområder&lt;/i&gt;

5.  Forekomster som er særdeles viktig for Norges nasjonale infrastruktur
&lt;i&gt;- herunder grus- og pukkforekomster som er særlig viktig for forsyninger til større befolkningssentra i Norge&lt;/i&gt;<br />- Regional betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig fremtidig verdiskapingspotensial med in situ-verdi på mellom 100 og 1000 millioner kroner

2.  Mineralforekomster som er særdeles viktig for regional infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er særlig viktig for forsyninger innen en region&lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster som har eller har hatt særlig betydning for byggeskikk og arkitektur i en region&lt;/i&gt;<br />- Lokal betydning – 1.  Mineralforekomster som er viktig for lokal infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er viktig for forsyninger innen en kommune&lt;/i&gt;<br />- Liten lokal betydning – Forekomsten  har liten eller ingen økonomisk betydning<br />- Ikke vurdert – Forekomstens økonomiske betydning er ikke vurdert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>mineralRegistreringType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type mineralforekomst dette er i en økonomisk betraktning<br /><br />-- Definition --<br />The type of mineral occurrence.<br />-- Description --<br />EXAMPLE: prospect, occurrence, mineral deposit, ore deposit.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MineralRegistreringType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- forekomst – en mineralkonsentrasjon i jordskorpen, en anrikning eller en akkumulasjon. Kan brukes om alle typer mineralforekomster.
INSPIRE Description:
A mass of naturally occurring mineral material, e.g. metal ores or non-metallic minerals, usually of economic value, without regard to mode of origin. Accumulations of coal and petroleum may or may not be included.<br />- registrering – en økonomisk interessant malm- eller mineralanrikning
Any ore or economic mineral in any concentration found in bedrock or as float.

INSPIRE Description:<br />- prospekt – område hvor det er utsikter til å finne malm og verdifulle mineraler. Representere områder med høy sannsynlighet for funn av lite eller ikke dokumenterte mineralforekomster.
Er ofte et mulig undersøkelsesområde

INSPIRE Description:
An  area  that  is  a  potential  site  of  mineral  deposits,  based  on  preliminary exploration, previous exploration. A geologic or geophysical anomaly, especially one recommended for additional exploration.<br />- provins – geologisk provins - stort område som er enhetlig med hensyn til opptreden av ulike metaller eller mineraler. Er en områdeavgrensning rundt en eller flere større eller mindre registreringer og/eller observasjoner med potensial for mineralutvinning.



INSPIRE Description:
Geologic provinces classified by mineral resources.<br />- distrikt – geologisk distrikt, karakteristisk for ulike mineralforekomster

INSPIRE Description:
Geologic districts classified by mineral resources.<br />- felt – region eller område karakteristisk for ulike mineralforekomster. Eks Rørosfeltet

INSPIRE Description:
A region or area that possesses or is characterized by a particular mineral resource.<br />- malmsone – mineralforekomst som har form som årer eller ganger i hovedbergarten

INSPIRE Description:
A mineral deposit consisting of a zone of veins, veinlets, disseminations, or planar breccias.<br />- prosjekt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navnRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på forekomsten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>typeRastoffVirksomhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir type/status på eventuell aktivitet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TypeRastoffVirksomhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Prospektering<br />- Røsking<br />- Skjerp<br />- Prøvedrift<br />- Gruvedrift<br />- Steinbrudd<br />- Mulig fremtidig uttaksområde<br />- Typelokalitet(er)<br />- Anleggspukkverk<br />- Biprodukt pukk<br />- Grustak (massetak)<br />- Utplanert massetak/endret arealbruk<br />- Observasjonslokalitet<br />- Leirtak<br />- Torvtak<br />- Naturlig grunnvannskilde<br />- Borebrønn<br />- Overvåkingsstasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelseURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lenke (URL) til tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>antallAnalyser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>antallet utførte kjemiske og/eller mekaniske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>avfallType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskriver avfallstypen i et deponi (avfallsområde)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>rastoffVolum</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>gjennomsnittlig volum av råstoffregistreringen eller summen av alle registreringene i råstoffområdet<br /><br />Volumet er målt i m3 og anslått med 50 % sannsynlighet. Angir areal multiplisert med gjennomsnittlig mektighet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>sisteBefaringdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste feltbefaring av forekomsten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FelleskomponenterGrusPukk

**Assosiasjoner**
GeolAvgrLinje – rolle: grusPukkOmråderAvgrensning – kardinalitet: 1..*
SandGrusUttak – rolle: inneholder – kardinalitet: 0..*
SandGrusObservasjon – rolle: inneholder – kardinalitet: 0..*
SandGrusRegistrering – rolle: inneholder – kardinalitet: 0..*
RastoffProvePkt – rolle: inneholder – kardinalitet: 0..*

#### PukkOmr

område som antas å inneholde bergarter som har et potensiale til å kunne utnyttes som pukkråstoff (knust fjell)

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forekomstobjektets identifikasjonskode<br /><br />Merknad: Består av kommunenummer (4 siffer), og et løpenummer (7 siffer). Ideelt sett består løpenummeret av et område nummer (3 siffer), lokalitetsnummer (2 siffer) og prøvenummer (2 siffer).<br /><br />Eksempel: 17290010101</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forekomstNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik nummerering av forekomsten som råstoffobjektet tilhører<br /><br />Merknad: Benyttes som koplingsnøkkel mellom de ulike objektene i forekomsten. Mange viktige egenskaper finnes kun på områdeobjektet som er hovedobjektet til forekomsten<br /><br />Eks. 1729001</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type råstoff som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MaterialType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Edelmetaller(Au,Ag,PGE)<br />- Jernmetaller (Fe, Mn, Ti)<br />- Jernlegeringsmetaller (Cr, Ni, Co, V, Mo, W)<br />- Basemetaller (Cu, Zn, Pbinkl. Fe-sulfider, As, Sb, Bi, Sn)<br />- Energimetaller (U, Th)<br />- Spesialmetaller (Nb, Ta, Be, Li, Sc, REE)<br />- Andre metaller<br />- Karbonatmineraler<br />- Silika<br />- Talk<br />- Feltspat<br />- Olivin<br />- Grafitt<br />- Fossilt brensel<br />- Nefelinsyenitt<br />- Magnesium mineraler<br />- Zirkon<br />- Beryllium mineraler<br />- Andre industrimineraler<br />- Blokkstein<br />- Skifer<br />- Kvernstein<br />- Brynestein<br />- Murestein<br />- Pukk/knust fjell<br />- Sand og grus<br />- Grus og andre løsmasser<br />- Skred og forvitring<br />- Skjellsand<br />- Steintipp<br />- Leire<br />- Torv<br />- Grunnvann i fjell<br />- Grunnvann i fjell og løsmasser<br />- uspesifisert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>rastoffBetydning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvorvidt forekomsten er av internasjonal, nasjonal, regional, eller kun av lokal betydning (viktighet)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>RastoffBetydning</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Internasjonal betydning – 1.  Metall- og industrimineralforekomster med dokumenterte ressurser som kan gi et signifikant bidrag til internasjonale behov
&lt;i&gt;- herunder forekomster med meget høy dokumentert in situ-verdi basert på kvalitet og tonnasje&lt;/i&gt;
&lt;i&gt;- herunder forekomster med potensial for årsproduksjon som dekker signifikant andel av behov i EU/EØS&lt;/i&gt;

2.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder dokumenterte forekomster av mineraler på EU liste over kritiske råstoffer som utnyttes eller har potensial for framtidig utnyttelse&lt;/i&gt;

3.  Forekomster av byggeråstoffer med verdi eller potensial for eksport på minst 1 millioner tonn årlig
&lt;i&gt;
&lt;/i&gt;<br />- Nasjonal betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig, betydelig fremtidig verdiskapingspotensial
&lt;i&gt;- herunder forekomster med betydelig in-situ verdi&lt;/i&gt;
&lt;i&gt;- herunder byggeråstoffer med betydelig potensial for eksport&lt;/i&gt;

2.  Mineralforekomster som har unike kvaliteter som gjør dem særlig egnet til foredlende industri
&lt;i&gt;- herunder industrimineraler og spesialmetaller av særlig høy kvalitet&lt;/i&gt;

3.  Mineralforekomster som har unike kvaliteter som byggeråstoff
&lt;i&gt;- herunder pukk- og grusforekomster med unike fysiske egenskaper &lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster med unike egenskaper og attraktivitet i det internasjonale markedet&lt;/i&gt;
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til andre viktige samfunnsområder&lt;/i&gt;

4.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til viktige norske samfunnsområder&lt;/i&gt;

5.  Forekomster som er særdeles viktig for Norges nasjonale infrastruktur
&lt;i&gt;- herunder grus- og pukkforekomster som er særlig viktig for forsyninger til større befolkningssentra i Norge&lt;/i&gt;<br />- Regional betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig fremtidig verdiskapingspotensial med in situ-verdi på mellom 100 og 1000 millioner kroner

2.  Mineralforekomster som er særdeles viktig for regional infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er særlig viktig for forsyninger innen en region&lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster som har eller har hatt særlig betydning for byggeskikk og arkitektur i en region&lt;/i&gt;<br />- Lokal betydning – 1.  Mineralforekomster som er viktig for lokal infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er viktig for forsyninger innen en kommune&lt;/i&gt;<br />- Liten lokal betydning – Forekomsten  har liten eller ingen økonomisk betydning<br />- Ikke vurdert – Forekomstens økonomiske betydning er ikke vurdert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>mineralRegistreringType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type mineralforekomst dette er i en økonomisk betraktning<br /><br />-- Definition --<br />The type of mineral occurrence.<br />-- Description --<br />EXAMPLE: prospect, occurrence, mineral deposit, ore deposit.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MineralRegistreringType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- forekomst – en mineralkonsentrasjon i jordskorpen, en anrikning eller en akkumulasjon. Kan brukes om alle typer mineralforekomster.
INSPIRE Description:
A mass of naturally occurring mineral material, e.g. metal ores or non-metallic minerals, usually of economic value, without regard to mode of origin. Accumulations of coal and petroleum may or may not be included.<br />- registrering – en økonomisk interessant malm- eller mineralanrikning
Any ore or economic mineral in any concentration found in bedrock or as float.

INSPIRE Description:<br />- prospekt – område hvor det er utsikter til å finne malm og verdifulle mineraler. Representere områder med høy sannsynlighet for funn av lite eller ikke dokumenterte mineralforekomster.
Er ofte et mulig undersøkelsesområde

INSPIRE Description:
An  area  that  is  a  potential  site  of  mineral  deposits,  based  on  preliminary exploration, previous exploration. A geologic or geophysical anomaly, especially one recommended for additional exploration.<br />- provins – geologisk provins - stort område som er enhetlig med hensyn til opptreden av ulike metaller eller mineraler. Er en områdeavgrensning rundt en eller flere større eller mindre registreringer og/eller observasjoner med potensial for mineralutvinning.



INSPIRE Description:
Geologic provinces classified by mineral resources.<br />- distrikt – geologisk distrikt, karakteristisk for ulike mineralforekomster

INSPIRE Description:
Geologic districts classified by mineral resources.<br />- felt – region eller område karakteristisk for ulike mineralforekomster. Eks Rørosfeltet

INSPIRE Description:
A region or area that possesses or is characterized by a particular mineral resource.<br />- malmsone – mineralforekomst som har form som årer eller ganger i hovedbergarten

INSPIRE Description:
A mineral deposit consisting of a zone of veins, veinlets, disseminations, or planar breccias.<br />- prosjekt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navnRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på forekomsten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>typeRastoffVirksomhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir type/status på eventuell aktivitet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TypeRastoffVirksomhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Prospektering<br />- Røsking<br />- Skjerp<br />- Prøvedrift<br />- Gruvedrift<br />- Steinbrudd<br />- Mulig fremtidig uttaksområde<br />- Typelokalitet(er)<br />- Anleggspukkverk<br />- Biprodukt pukk<br />- Grustak (massetak)<br />- Utplanert massetak/endret arealbruk<br />- Observasjonslokalitet<br />- Leirtak<br />- Torvtak<br />- Naturlig grunnvannskilde<br />- Borebrønn<br />- Overvåkingsstasjon</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelseURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lenke (URL) til tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>antallAnalyser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>antallet utførte kjemiske og/eller mekaniske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>sisteBefaringdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste feltbefaring av forekomsten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FelleskomponenterGrusPukk

**Assosiasjoner**
GeolAvgrLinje – rolle: grusPukkOmråderAvgrensning – kardinalitet: 1..*
PukkUttak – rolle: inneholder – kardinalitet: 0..*
PukkObservasjon – rolle: inneholder – kardinalitet: 0..*
RastoffProvePkt – rolle: inneholder – kardinalitet: 0..*
PukkRegistrering – rolle: inneholder – kardinalitet: 0..*

#### SandGrusRegistrering

avgrensning av areal som inneholder sand- og grusressurs

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forekomstobjektets identifikasjonskode<br /><br />Merknad: Består av kommunenummer (4 siffer), og et løpenummer (7 siffer). Ideelt sett består løpenummeret av et område nummer (3 siffer), lokalitetsnummer (2 siffer) og prøvenummer (2 siffer).<br /><br />Eksempel: 17290010101</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forekomstNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik nummerering av forekomsten som råstoffobjektet tilhører<br /><br />Merknad: Benyttes som koplingsnøkkel mellom de ulike objektene i forekomsten. Mange viktige egenskaper finnes kun på områdeobjektet som er hovedobjektet til forekomsten<br /><br />Eks. 1729001</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type råstoff som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MaterialType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Edelmetaller(Au,Ag,PGE)<br />- Jernmetaller (Fe, Mn, Ti)<br />- Jernlegeringsmetaller (Cr, Ni, Co, V, Mo, W)<br />- Basemetaller (Cu, Zn, Pbinkl. Fe-sulfider, As, Sb, Bi, Sn)<br />- Energimetaller (U, Th)<br />- Spesialmetaller (Nb, Ta, Be, Li, Sc, REE)<br />- Andre metaller<br />- Karbonatmineraler<br />- Silika<br />- Talk<br />- Feltspat<br />- Olivin<br />- Grafitt<br />- Fossilt brensel<br />- Nefelinsyenitt<br />- Magnesium mineraler<br />- Zirkon<br />- Beryllium mineraler<br />- Andre industrimineraler<br />- Blokkstein<br />- Skifer<br />- Kvernstein<br />- Brynestein<br />- Murestein<br />- Pukk/knust fjell<br />- Sand og grus<br />- Grus og andre løsmasser<br />- Skred og forvitring<br />- Skjellsand<br />- Steintipp<br />- Leire<br />- Torv<br />- Grunnvann i fjell<br />- Grunnvann i fjell og løsmasser<br />- uspesifisert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>rastoffBetydning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvorvidt forekomsten er av internasjonal, nasjonal, regional, eller kun av lokal betydning (viktighet)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>RastoffBetydning</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Internasjonal betydning – 1.  Metall- og industrimineralforekomster med dokumenterte ressurser som kan gi et signifikant bidrag til internasjonale behov
&lt;i&gt;- herunder forekomster med meget høy dokumentert in situ-verdi basert på kvalitet og tonnasje&lt;/i&gt;
&lt;i&gt;- herunder forekomster med potensial for årsproduksjon som dekker signifikant andel av behov i EU/EØS&lt;/i&gt;

2.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder dokumenterte forekomster av mineraler på EU liste over kritiske råstoffer som utnyttes eller har potensial for framtidig utnyttelse&lt;/i&gt;

3.  Forekomster av byggeråstoffer med verdi eller potensial for eksport på minst 1 millioner tonn årlig
&lt;i&gt;
&lt;/i&gt;<br />- Nasjonal betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig, betydelig fremtidig verdiskapingspotensial
&lt;i&gt;- herunder forekomster med betydelig in-situ verdi&lt;/i&gt;
&lt;i&gt;- herunder byggeråstoffer med betydelig potensial for eksport&lt;/i&gt;

2.  Mineralforekomster som har unike kvaliteter som gjør dem særlig egnet til foredlende industri
&lt;i&gt;- herunder industrimineraler og spesialmetaller av særlig høy kvalitet&lt;/i&gt;

3.  Mineralforekomster som har unike kvaliteter som byggeråstoff
&lt;i&gt;- herunder pukk- og grusforekomster med unike fysiske egenskaper &lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster med unike egenskaper og attraktivitet i det internasjonale markedet&lt;/i&gt;
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til andre viktige samfunnsområder&lt;/i&gt;

4.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til viktige norske samfunnsområder&lt;/i&gt;

5.  Forekomster som er særdeles viktig for Norges nasjonale infrastruktur
&lt;i&gt;- herunder grus- og pukkforekomster som er særlig viktig for forsyninger til større befolkningssentra i Norge&lt;/i&gt;<br />- Regional betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig fremtidig verdiskapingspotensial med in situ-verdi på mellom 100 og 1000 millioner kroner

2.  Mineralforekomster som er særdeles viktig for regional infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er særlig viktig for forsyninger innen en region&lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster som har eller har hatt særlig betydning for byggeskikk og arkitektur i en region&lt;/i&gt;<br />- Lokal betydning – 1.  Mineralforekomster som er viktig for lokal infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er viktig for forsyninger innen en kommune&lt;/i&gt;<br />- Liten lokal betydning – Forekomsten  har liten eller ingen økonomisk betydning<br />- Ikke vurdert – Forekomstens økonomiske betydning er ikke vurdert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>mineralRegistreringType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type mineralforekomst dette er i en økonomisk betraktning<br /><br />-- Definition --<br />The type of mineral occurrence.<br />-- Description --<br />EXAMPLE: prospect, occurrence, mineral deposit, ore deposit.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MineralRegistreringType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- forekomst – en mineralkonsentrasjon i jordskorpen, en anrikning eller en akkumulasjon. Kan brukes om alle typer mineralforekomster.
INSPIRE Description:
A mass of naturally occurring mineral material, e.g. metal ores or non-metallic minerals, usually of economic value, without regard to mode of origin. Accumulations of coal and petroleum may or may not be included.<br />- registrering – en økonomisk interessant malm- eller mineralanrikning
Any ore or economic mineral in any concentration found in bedrock or as float.

INSPIRE Description:<br />- prospekt – område hvor det er utsikter til å finne malm og verdifulle mineraler. Representere områder med høy sannsynlighet for funn av lite eller ikke dokumenterte mineralforekomster.
Er ofte et mulig undersøkelsesområde

INSPIRE Description:
An  area  that  is  a  potential  site  of  mineral  deposits,  based  on  preliminary exploration, previous exploration. A geologic or geophysical anomaly, especially one recommended for additional exploration.<br />- provins – geologisk provins - stort område som er enhetlig med hensyn til opptreden av ulike metaller eller mineraler. Er en områdeavgrensning rundt en eller flere større eller mindre registreringer og/eller observasjoner med potensial for mineralutvinning.



INSPIRE Description:
Geologic provinces classified by mineral resources.<br />- distrikt – geologisk distrikt, karakteristisk for ulike mineralforekomster

INSPIRE Description:
Geologic districts classified by mineral resources.<br />- felt – region eller område karakteristisk for ulike mineralforekomster. Eks Rørosfeltet

INSPIRE Description:
A region or area that possesses or is characterized by a particular mineral resource.<br />- malmsone – mineralforekomst som har form som årer eller ganger i hovedbergarten

INSPIRE Description:
A mineral deposit consisting of a zone of veins, veinlets, disseminations, or planar breccias.<br />- prosjekt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialUndertype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>underinndeling av materialtypene som kan være/er gjenstand for utvinning<br /><br />Merknad: Er en mer detaljert inndeling av det råstoff som utvinnes (hovedsakelig kjemiske elementer (Cu, Pb, Zn osv.) og mineralnavn)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navnRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på forekomsten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>rastoffVolum</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>gjennomsnittlig volum av råstoffregistreringen eller summen av alle registreringene i råstoffområdet<br /><br />Volumet er målt i m3 og anslått med 50 % sannsynlighet. Angir areal multiplisert med gjennomsnittlig mektighet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>mektighetFemtiProsent</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>gjennomsnittlig mektighetangivelse med 50% sannsynlighet<br /><br />Merknad: Gjennomsnittlig lagtykkelse (angitt i meter) i forekomsten, anslått med 50 % sannsynlighet. I NGUs grus- og pukkdatabase er det også oppgitt en mektighet med 10 % og 90 % sannsynlighet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Real</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelseURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lenke (URL) til tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FelleskomponenterGrusPukk

**Assosiasjoner**
GeolAvgrLinje – rolle: grusPukkRegistreringerAvgrensning – kardinalitet: 1..*
SandGrusOmr – rolle: tilhører – kardinalitet: 0..1

#### PukkRegistrering

avgrensning av areal som inneholder pukksteinressurs

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>område</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets utstrekning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Flate</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forekomstobjektets identifikasjonskode<br /><br />Merknad: Består av kommunenummer (4 siffer), og et løpenummer (7 siffer). Ideelt sett består løpenummeret av et område nummer (3 siffer), lokalitetsnummer (2 siffer) og prøvenummer (2 siffer).<br /><br />Eksempel: 17290010101</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forekomstNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik nummerering av forekomsten som råstoffobjektet tilhører<br /><br />Merknad: Benyttes som koplingsnøkkel mellom de ulike objektene i forekomsten. Mange viktige egenskaper finnes kun på områdeobjektet som er hovedobjektet til forekomsten<br /><br />Eks. 1729001</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type råstoff som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MaterialType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Edelmetaller(Au,Ag,PGE)<br />- Jernmetaller (Fe, Mn, Ti)<br />- Jernlegeringsmetaller (Cr, Ni, Co, V, Mo, W)<br />- Basemetaller (Cu, Zn, Pbinkl. Fe-sulfider, As, Sb, Bi, Sn)<br />- Energimetaller (U, Th)<br />- Spesialmetaller (Nb, Ta, Be, Li, Sc, REE)<br />- Andre metaller<br />- Karbonatmineraler<br />- Silika<br />- Talk<br />- Feltspat<br />- Olivin<br />- Grafitt<br />- Fossilt brensel<br />- Nefelinsyenitt<br />- Magnesium mineraler<br />- Zirkon<br />- Beryllium mineraler<br />- Andre industrimineraler<br />- Blokkstein<br />- Skifer<br />- Kvernstein<br />- Brynestein<br />- Murestein<br />- Pukk/knust fjell<br />- Sand og grus<br />- Grus og andre løsmasser<br />- Skred og forvitring<br />- Skjellsand<br />- Steintipp<br />- Leire<br />- Torv<br />- Grunnvann i fjell<br />- Grunnvann i fjell og løsmasser<br />- uspesifisert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>rastoffBetydning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvorvidt forekomsten er av internasjonal, nasjonal, regional, eller kun av lokal betydning (viktighet)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>RastoffBetydning</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a><br />- Internasjonal betydning – 1.  Metall- og industrimineralforekomster med dokumenterte ressurser som kan gi et signifikant bidrag til internasjonale behov
&lt;i&gt;- herunder forekomster med meget høy dokumentert in situ-verdi basert på kvalitet og tonnasje&lt;/i&gt;
&lt;i&gt;- herunder forekomster med potensial for årsproduksjon som dekker signifikant andel av behov i EU/EØS&lt;/i&gt;

2.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder dokumenterte forekomster av mineraler på EU liste over kritiske råstoffer som utnyttes eller har potensial for framtidig utnyttelse&lt;/i&gt;

3.  Forekomster av byggeråstoffer med verdi eller potensial for eksport på minst 1 millioner tonn årlig
&lt;i&gt;
&lt;/i&gt;<br />- Nasjonal betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig, betydelig fremtidig verdiskapingspotensial
&lt;i&gt;- herunder forekomster med betydelig in-situ verdi&lt;/i&gt;
&lt;i&gt;- herunder byggeråstoffer med betydelig potensial for eksport&lt;/i&gt;

2.  Mineralforekomster som har unike kvaliteter som gjør dem særlig egnet til foredlende industri
&lt;i&gt;- herunder industrimineraler og spesialmetaller av særlig høy kvalitet&lt;/i&gt;

3.  Mineralforekomster som har unike kvaliteter som byggeråstoff
&lt;i&gt;- herunder pukk- og grusforekomster med unike fysiske egenskaper &lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster med unike egenskaper og attraktivitet i det internasjonale markedet&lt;/i&gt;
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til andre viktige samfunnsområder&lt;/i&gt;

4.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til viktige norske samfunnsområder&lt;/i&gt;

5.  Forekomster som er særdeles viktig for Norges nasjonale infrastruktur
&lt;i&gt;- herunder grus- og pukkforekomster som er særlig viktig for forsyninger til større befolkningssentra i Norge&lt;/i&gt;<br />- Regional betydning – 1.  Mineralforekomster som har et bekreftet eller sannsynlig fremtidig verdiskapingspotensial med in situ-verdi på mellom 100 og 1000 millioner kroner

2.  Mineralforekomster som er særdeles viktig for regional infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er særlig viktig for forsyninger innen en region&lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster som har eller har hatt særlig betydning for byggeskikk og arkitektur i en region&lt;/i&gt;<br />- Lokal betydning – 1.  Mineralforekomster som er viktig for lokal infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er viktig for forsyninger innen en kommune&lt;/i&gt;<br />- Liten lokal betydning – Forekomsten  har liten eller ingen økonomisk betydning<br />- Ikke vurdert – Forekomstens økonomiske betydning er ikke vurdert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>mineralRegistreringType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type mineralforekomst dette er i en økonomisk betraktning<br /><br />-- Definition --<br />The type of mineral occurrence.<br />-- Description --<br />EXAMPLE: prospect, occurrence, mineral deposit, ore deposit.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MineralRegistreringType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- forekomst – en mineralkonsentrasjon i jordskorpen, en anrikning eller en akkumulasjon. Kan brukes om alle typer mineralforekomster.
INSPIRE Description:
A mass of naturally occurring mineral material, e.g. metal ores or non-metallic minerals, usually of economic value, without regard to mode of origin. Accumulations of coal and petroleum may or may not be included.<br />- registrering – en økonomisk interessant malm- eller mineralanrikning
Any ore or economic mineral in any concentration found in bedrock or as float.

INSPIRE Description:<br />- prospekt – område hvor det er utsikter til å finne malm og verdifulle mineraler. Representere områder med høy sannsynlighet for funn av lite eller ikke dokumenterte mineralforekomster.
Er ofte et mulig undersøkelsesområde

INSPIRE Description:
An  area  that  is  a  potential  site  of  mineral  deposits,  based  on  preliminary exploration, previous exploration. A geologic or geophysical anomaly, especially one recommended for additional exploration.<br />- provins – geologisk provins - stort område som er enhetlig med hensyn til opptreden av ulike metaller eller mineraler. Er en områdeavgrensning rundt en eller flere større eller mindre registreringer og/eller observasjoner med potensial for mineralutvinning.



INSPIRE Description:
Geologic provinces classified by mineral resources.<br />- distrikt – geologisk distrikt, karakteristisk for ulike mineralforekomster

INSPIRE Description:
Geologic districts classified by mineral resources.<br />- felt – region eller område karakteristisk for ulike mineralforekomster. Eks Rørosfeltet

INSPIRE Description:
A region or area that possesses or is characterized by a particular mineral resource.<br />- malmsone – mineralforekomst som har form som årer eller ganger i hovedbergarten

INSPIRE Description:
A mineral deposit consisting of a zone of veins, veinlets, disseminations, or planar breccias.<br />- prosjekt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navnRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på forekomsten</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelseURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lenke (URL) til tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FelleskomponenterGrusPukk

**Assosiasjoner**
GeolAvgrLinje – rolle: grusPukkRegistreringerAvgrensning – kardinalitet: 1..*
PukkOmr – rolle: tilhører – kardinalitet: 0..1

#### RastoffProvePkt

lokalitet hvor det er tatt (innsamlet) prøve(r) for videre bearbeidelse/analyse

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>posisjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>sted som objektet eksisterer på</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Punkt</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilken type råstoff som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MaterialType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Edelmetaller(Au,Ag,PGE)<br />- Jernmetaller (Fe, Mn, Ti)<br />- Jernlegeringsmetaller (Cr, Ni, Co, V, Mo, W)<br />- Basemetaller (Cu, Zn, Pbinkl. Fe-sulfider, As, Sb, Bi, Sn)<br />- Energimetaller (U, Th)<br />- Spesialmetaller (Nb, Ta, Be, Li, Sc, REE)<br />- Andre metaller<br />- Karbonatmineraler<br />- Silika<br />- Talk<br />- Feltspat<br />- Olivin<br />- Grafitt<br />- Fossilt brensel<br />- Nefelinsyenitt<br />- Magnesium mineraler<br />- Zirkon<br />- Beryllium mineraler<br />- Andre industrimineraler<br />- Blokkstein<br />- Skifer<br />- Kvernstein<br />- Brynestein<br />- Murestein<br />- Pukk/knust fjell<br />- Sand og grus<br />- Grus og andre løsmasser<br />- Skred og forvitring<br />- Skjellsand<br />- Steintipp<br />- Leire<br />- Torv<br />- Grunnvann i fjell<br />- Grunnvann i fjell og løsmasser<br />- uspesifisert</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forekomstobjektets identifikasjonskode<br /><br />Merknad: Består av kommunenummer (4 siffer), og et løpenummer (7 siffer). Ideelt sett består løpenummeret av et område nummer (3 siffer), lokalitetsnummer (2 siffer) og prøvenummer (2 siffer).<br /><br />Eksempel: 17290010101</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>materialUndertype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>underinndeling av materialtypene som kan være/er gjenstand for utvinning</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>forekomstNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik nummerering av forekomsten som råstoffobjektet tilhører<br /><br />Merknad: Benyttes som koplingsnøkkel mellom de ulike objektene i forekomsten. Mange viktige egenskaper finnes kun på områdeobjektet som er hovedobjektet til forekomsten<br /><br />Eks. 1729001</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>navnRastoffobj</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på råstoffobjekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>proveNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummerering av prøvepunkt i forekomsten eller i lokaliteten<br /><br />Merknad: Er en del av FOREKOM_ID: Eks: 172900101(01)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>geolBeskrivelseURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lenke (URL) til tekstlig beskrivelse av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>CharacterString</td>
    </tr>
  </tbody>
</table>

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>antallAnalyser</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>antallet utførte kjemiske og/eller mekaniske analyser</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Integer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FelleskomponenterGrusPukk

**Assosiasjoner**
SandGrusOmr – rolle: tilknyttet – kardinalitet: 0..1
PukkOmr – rolle: tilknyttet – kardinalitet: 0..1

#### Esker

langstrakt, smal og ofte slynget rygg eller ås av lagdelt og sortert sand, grus eller rullestein, dannet ved avsetning fra smeltevannelver i en tunnel under eller inne i en isbre

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>senterlinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>forløp som følger objektets sentrale del</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
    </tr>
  </tbody>
</table>

### Kodelister

#### «Enumeration» Målemetode

**Definisjon:** metode som ligger til grunn for registrering av posisjon


-- Definition - -
method on which registration of position is based

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Terrengmålt: Uspesifisert måleinstrument</td>
      <td>Målt i terrenget , uspesifisert metode/måleinstrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengmålt: Totalstasjon</td>
      <td>Målt i terrenget med totalstasjon</td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengmålt: Teodolitt og el avstandsmåler</td>
      <td>Målt i terrenget med teodolitt og elektronisk avstandsmåler</td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengmålt: Teodolitt og målebånd</td>
      <td>Målt i terrenget med teodolitt og målebånd</td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengmålt: Ortogonalmetoden</td>
      <td>Målt i terrenget, ortogonalmetoden</td>
      <td></td>
    </tr>
    <tr>
      <td>Utmål</td>
      <td>Punkt beregnet på bakgrunn av måling mot andre punkter, slik som to avstander eller avstand og retning

-- Definition --
Point calculated on the basis of other items, such as two distances or distance + direction.</td>
      <td></td>
    </tr>
    <tr>
      <td>Tatt fra plan</td>
      <td>Tatt fra plan eller godkjent tiltak</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet  (denne har ingen mening, bør fjernes?)</td>
      <td>Annet</td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument</td>
      <td>Målt i stereoinstrument, uspesifisert instrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Aerotriangulert</td>
      <td>Punkt beregnet ved aerotriangulering

-- Definition --
Point calculated by aerotriangulation</td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument: Analytisk plotter</td>
      <td>Målt i stereoinstrument, analytisk plotter</td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument: Autograf</td>
      <td>Målt i stereoinstrument, autograf, analogt instrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument: Digitalt</td>
      <td>Målt i stereoinstrument, digitalt instrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Scannet fra kart</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner, uspesifisert kartmedium</td>
      <td></td>
    </tr>
    <tr>
      <td>Skannet fra kart: Blyantoriginal</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er blyantoriginal</td>
      <td></td>
    </tr>
    <tr>
      <td>Skannet fra kart: Rissefolie</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er rissefolie</td>
      <td></td>
    </tr>
    <tr>
      <td>Skannet fra kart: Transparent folie, god kvalitet</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er transparent folie av  god kvalitet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skannet fra kart: Transparent folie, mindre god kvalitet</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er transparent folie av mindre god kvalitet</td>
      <td></td>
    </tr>
    <tr>
      <td>Skannet fra kart: Papirkopi</td>
      <td>Geometri overført fra kart maskinelt ved hjelp av skanner. Kartmedium er papirkopi.</td>
      <td></td>
    </tr>
    <tr>
      <td>Flybåren laserscanner</td>
      <td>Målt med laserskanner fra fly</td>
      <td></td>
    </tr>
    <tr>
      <td>Bilbåren laser</td>
      <td>Målt med laserskanner plassert i kjøretøy</td>
      <td></td>
    </tr>
    <tr>
      <td>Lineær referanse</td>
      <td>brukes for objekter som er stedfestet med lineær referanse, enten disse leveres med stedfesting kun som lineære referanser, eller med koordinatgeometri avledet fra lineære referanser</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringbord: Ortofoto eller flybilde</td>
      <td>Geometri overført fra ortofoto eller flybilde ved hjelp av manuell registrering på et digitaliseringsbord, uspesifisert bildemedium</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringbord: Ortofoto, film</td>
      <td>Geometri overført fra ortofoto ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er film</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringbord: Ortofoto, fotokopi</td>
      <td>Geometri overført fra ortofoto ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er fotokopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringbord: Flybilde, film</td>
      <td>Geometri overført fra flybilde ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er film</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringbord: Flybilde, fotokopi</td>
      <td>Geometri overført fra flybilde ved hjelp av manuell registrering på et digitaliseringsbord. Bildemedium er fotokopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra ortofoto</td>
      <td>Geometri overført fra ortofoto ved hjelp av manuell registrering på skjerm</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra satellittbilde</td>
      <td>Geometri overført fra satellittbilde ved hjelp av manuell registrering på skjerm</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra andre digitale rasterdata</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra tolkning av seismikk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Vektorisering av laserdata</td>
      <td>Vektorisering fra laserdata, brukes også der vektoriseringen støttes av ortofoto</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord, medium uspesifisert</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart, blyantoriginal</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er blyantoriginal</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart, rissefoile</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er rissefolie</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart, transparent foile, god kvalitet</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er transparent folie av god kvalitet, samkopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart, transparent foile, mindre god kvalitet</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er transparent folie av mindre god kvalitet, samkopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitaliseringsbord: Kart, papirkopi</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på et digitaliseringsbord. Kartmedium er papirkopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra skannet kart</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på skjerm, medium skannet kart (raster), samkopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data (interpolasjon)</td>
      <td>Genererte data, interpolasjonsmetode. Ikke nærmere spesifisert</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data (interpolasjon): Terrengmodell</td>
      <td>Genererte data, interpolasjonsmetode, fra terrengmodell</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data (interpolasjon): Vektet middel</td>
      <td>Genererte data, interpolasjonsmetode, vektet middel</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data: Fra annen geometri</td>
      <td>Genererte data: Sirkelgeometri, korridor eller annen geometri generert ut fra f.eks et punkt eller en linje (f.eks midtlinje veg)</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data: Generalisering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data: Sentralpunkt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data: Sammenknytningspunkt, randpunkt</td>
      <td>Genererte data: Sammenknytningspunkt (f.eks mellom ulike kartlegginger), randpunkt (f.eks mellom ulike kilder til kart)</td>
      <td></td>
    </tr>
    <tr>
      <td>Koordinater hentet fra GAB</td>
      <td>Koordinater hentet fra GAB, forløperen til registerdelen av matrikkelen</td>
      <td></td>
    </tr>
    <tr>
      <td>Koordinater hentet fra JREG</td>
      <td>Koordinater hentet fra JREG, jordregisteret</td>
      <td></td>
    </tr>
    <tr>
      <td>Beregnet</td>
      <td>Beregnet, uspesifisert hvordan</td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder</td>
      <td>Spesielle metoder, uspesifisert</td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder: Målt med stikkstang</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder: Målt med waterstang</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder: Målt med målehjul</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spesielle metoder: Målt med stigningsmåler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fastsatt punkt</td>
      <td>Punkt fastsatt ut fra et grunnlag (kart, bilde), f.eks ved partenes enighet ved en oppmålingsforretning</td>
      <td></td>
    </tr>
    <tr>
      <td>Fastsatt ved dom eller kongelig resolusjon</td>
      <td>Geometri fastsatt ved dom, lov, traktat eller kongelig resolusjon</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet (spesifiseres i filhode) ( bør vel fjernes, blir borte ved overføring mellom systemer)</td>
      <td>Annet (spesifiseres i filhode)</td>
      <td></td>
    </tr>
    <tr>
      <td>Frihåndstegning</td>
      <td>Digitalisert ut fra frihåndstegning.  Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag</td>
      <td></td>
    </tr>
    <tr>
      <td>Frihåndstegning på kart</td>
      <td>Digitalisert fra krokering på kart, dvs grovt skissert på kart</td>
      <td></td>
    </tr>
    <tr>
      <td>Frihåndstegning på skjerm</td>
      <td>Digitalisert ut fra frihåndstegning (direkte på skjerm). Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag</td>
      <td></td>
    </tr>
    <tr>
      <td>Treghetsstedfesting</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Kodemåling, relative målinger</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, relative målinger.</td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Kodemåling, enkle målinger</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, enkle målinger.</td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Fasemåling, statisk måling</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Fasemåling statisk måling.</td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Fasemåling, andre metoder</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Fasemåling andre metoder.</td>
      <td></td>
    </tr>
    <tr>
      <td>Kombinasjon av GNSS/Treghet</td>
      <td>Kombinasjon av GPS/Treghet</td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Fasemåling RTK</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO).: Fasemåling RTK (realtids kinematisk måling)</td>
      <td></td>
    </tr>
    <tr>
      <td>GNSS: Fasemåling , float-løsning</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO). Fasemåling float-løsning</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent målemetode</td>
      <td>Målemetode er ukjent</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» MaterialType

**Definisjon:** hvilken type råstoff som kan være/er gjenstand for utvinning

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Edelmetaller(Au,Ag,PGE)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Jernmetaller (Fe, Mn, Ti)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Jernlegeringsmetaller (Cr, Ni, Co, V, Mo, W)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Basemetaller (Cu, Zn, Pbinkl. Fe-sulfider, As, Sb, Bi, Sn)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Energimetaller (U, Th)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Spesialmetaller (Nb, Ta, Be, Li, Sc, REE)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Andre metaller</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Karbonatmineraler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Silika</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Talk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Feltspat</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Olivin</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Grafitt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Fossilt brensel</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nefelinsyenitt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Magnesium mineraler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Zirkon</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Beryllium mineraler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Andre industrimineraler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Blokkstein</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skifer</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Kvernstein</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Brynestein</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Murestein</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Pukk/knust fjell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sand og grus</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Grus og andre løsmasser</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skred og forvitring</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skjellsand</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Steintipp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Leire</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Torv</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Grunnvann i fjell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Grunnvann i fjell og løsmasser</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>uspesifisert</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» RastoffBetydning

**Definisjon:** hvor stor betydning en mineralregistrering har med tanke på mulig økonomisk utnyttelse nå eller for framtiden.  Skal dokumenteres

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Internasjonal betydning</td>
      <td>1.  Metall- og industrimineralforekomster med dokumenterte ressurser som kan gi et signifikant bidrag til internasjonale behov
&lt;i&gt;- herunder forekomster med meget høy dokumentert in situ-verdi basert på kvalitet og tonnasje&lt;/i&gt;
&lt;i&gt;- herunder forekomster med potensial for årsproduksjon som dekker signifikant andel av behov i EU/EØS&lt;/i&gt;

2.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder dokumenterte forekomster av mineraler på EU liste over kritiske råstoffer som utnyttes eller har potensial for framtidig utnyttelse&lt;/i&gt;

3.  Forekomster av byggeråstoffer med verdi eller potensial for eksport på minst 1 millioner tonn årlig
&lt;i&gt;
&lt;/i&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Nasjonal betydning</td>
      <td>1.  Mineralforekomster som har et bekreftet eller sannsynlig, betydelig fremtidig verdiskapingspotensial
&lt;i&gt;- herunder forekomster med betydelig in-situ verdi&lt;/i&gt;
&lt;i&gt;- herunder byggeråstoffer med betydelig potensial for eksport&lt;/i&gt;

2.  Mineralforekomster som har unike kvaliteter som gjør dem særlig egnet til foredlende industri
&lt;i&gt;- herunder industrimineraler og spesialmetaller av særlig høy kvalitet&lt;/i&gt;

3.  Mineralforekomster som har unike kvaliteter som byggeråstoff
&lt;i&gt;- herunder pukk- og grusforekomster med unike fysiske egenskaper &lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster med unike egenskaper og attraktivitet i det internasjonale markedet&lt;/i&gt;
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til andre viktige samfunnsområder&lt;/i&gt;

4.  Forekomster av strategisk viktige eller ”kritiske” råstoff
&lt;i&gt;- herunder forekomster av metaller og industrimineraler som har dokumentert eller sannsynlig framtidig betydning som råstoff til viktige norske samfunnsområder&lt;/i&gt;

5.  Forekomster som er særdeles viktig for Norges nasjonale infrastruktur
&lt;i&gt;- herunder grus- og pukkforekomster som er særlig viktig for forsyninger til større befolkningssentra i Norge&lt;/i&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Regional betydning</td>
      <td>1.  Mineralforekomster som har et bekreftet eller sannsynlig fremtidig verdiskapingspotensial med in situ-verdi på mellom 100 og 1000 millioner kroner

2.  Mineralforekomster som er særdeles viktig for regional infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er særlig viktig for forsyninger innen en region&lt;/i&gt;
&lt;i&gt;- herunder natursteinsforekomster som har eller har hatt særlig betydning for byggeskikk og arkitektur i en region&lt;/i&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Lokal betydning</td>
      <td>1.  Mineralforekomster som er viktig for lokal infrastruktur
&lt;i&gt;- herunder industrimineral-, naturstein-, grus- og pukkforekomster som er viktig for forsyninger innen en kommune&lt;/i&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Liten lokal betydning</td>
      <td>Forekomsten  har liten eller ingen økonomisk betydning</td>
      <td></td>
    </tr>
    <tr>
      <td>Ikke vurdert</td>
      <td>Forekomstens økonomiske betydning er ikke vurdert</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» MineralRegistreringType

**Definisjon:** hvilken type mineralforekomst dette er i en økonomisk betraktning

-- Definition --
The type of mineral occurrence.
-- Description --
EXAMPLE: prospect, occurrence, mineral deposit, ore deposit.

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>false</td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>forekomst</td>
      <td>en mineralkonsentrasjon i jordskorpen, en anrikning eller en akkumulasjon. Kan brukes om alle typer mineralforekomster.
INSPIRE Description:
A mass of naturally occurring mineral material, e.g. metal ores or non-metallic minerals, usually of economic value, without regard to mode of origin. Accumulations of coal and petroleum may or may not be included.</td>
      <td></td>
    </tr>
    <tr>
      <td>registrering</td>
      <td>en økonomisk interessant malm- eller mineralanrikning
Any ore or economic mineral in any concentration found in bedrock or as float.

INSPIRE Description:</td>
      <td></td>
    </tr>
    <tr>
      <td>prospekt</td>
      <td>område hvor det er utsikter til å finne malm og verdifulle mineraler. Representere områder med høy sannsynlighet for funn av lite eller ikke dokumenterte mineralforekomster.
Er ofte et mulig undersøkelsesområde

INSPIRE Description:
An  area  that  is  a  potential  site  of  mineral  deposits,  based  on  preliminary exploration, previous exploration. A geologic or geophysical anomaly, especially one recommended for additional exploration.</td>
      <td></td>
    </tr>
    <tr>
      <td>provins</td>
      <td>geologisk provins - stort område som er enhetlig med hensyn til opptreden av ulike metaller eller mineraler. Er en områdeavgrensning rundt en eller flere større eller mindre registreringer og/eller observasjoner med potensial for mineralutvinning.



INSPIRE Description:
Geologic provinces classified by mineral resources.</td>
      <td></td>
    </tr>
    <tr>
      <td>distrikt</td>
      <td>geologisk distrikt, karakteristisk for ulike mineralforekomster

INSPIRE Description:
Geologic districts classified by mineral resources.</td>
      <td></td>
    </tr>
    <tr>
      <td>felt</td>
      <td>region eller område karakteristisk for ulike mineralforekomster. Eks Rørosfeltet

INSPIRE Description:
A region or area that possesses or is characterized by a particular mineral resource.</td>
      <td></td>
    </tr>
    <tr>
      <td>malmsone</td>
      <td>mineralforekomst som har form som årer eller ganger i hovedbergarten

INSPIRE Description:
A mineral deposit consisting of a zone of veins, veinlets, disseminations, or planar breccias.</td>
      <td></td>
    </tr>
    <tr>
      <td>prosjekt</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» DriftForhold

**Definisjon:** angir driftsforholdene

Merknad: À jour pr. siste oppdatering

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ikke satt i drift (mulig fremtidig drift)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>I drift</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Sporadisk drift</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nedlagt</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» TypeRastoffVirksomhet

**Definisjon:** angir type/status på eventuell aktivitet

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Prospektering</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Røsking</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skjerp</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Prøvedrift</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Gruvedrift</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Steinbrudd</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Mulig fremtidig uttaksområde</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Typelokalitet(er)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Anleggspukkverk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Biprodukt pukk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Grustak (massetak)</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Utplanert massetak/endret arealbruk</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Observasjonslokalitet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Leirtak</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Torvtak</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Naturlig grunnvannskilde</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Borebrønn</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Overvåkingsstasjon</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Losmassetype

**Definisjon:** kvartærgeologiske løsmassetyper (jordartstyper)

Merknad: Nærmere forklaring til definisjoner og dannelsesmåte er å finne i heftet; Kvartærgeologisk kart over Norge, 1:1 mill., tema jordarter (Thoresen M, Norges geologiske undersøkelse, 1991) og i NGU intern-rapport 2001.018 (Bergstrøm m.fl.).

Profilparametre i tagged values

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">asDictionary</th>
      <td>true</td>
    </tr>
    <tr>
      <th scope="row">codeList</th>
      <td><a href="http://skjema.geonorge.no/legg_inn_riktig_url">http://skjema.geonorge.no/legg_inn_riktig_url</a></td>
    </tr>
  </tbody>
</table>

Koder

<table class="code-list-table">
  <thead>
    <tr>
      <th>Kodenavn:</th>
      <th>Definisjon:</th>
      <th>Kodeverdi:</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Morenemateriale, uspesifisert</td>
      <td>Materiale plukket opp, transportert og avsatt av isbreer. Det er vanligvis, dårlig sortert og kan inneholde alt fra leir til stein og blokk. Mektighet, morenetype og overflateform kan variere. Benyttes ved kartframstilling i svært små målestokker.</td>
      <td></td>
    </tr>
    <tr>
      <td>Morenemateriale, sammenhengende dekke, stedvis med stor mektighet</td>
      <td>Materiale plukket opp, transportert og avsatt av isbreer, vanligvis hardt sammenpakket, dårlig sortert og kan inneholde alt fra leir til stein og blokk. Moreneavsetninger med tykkelse fra 0,5 m til flere ti-talls meter. Det er få eller ingen fjellblotninger i området.</td>
      <td></td>
    </tr>
    <tr>
      <td>Morenemateriale, usammenhengende eller tynt dekke over berggrunnen</td>
      <td>Materiale plukket opp, transportert og avsatt av isbreer. Det er vanligvis hardt sammenpakket, dårlig sortert og kan inneholde alt fra leir til stein og blokk. Områder med grunnlendte moreneavsetninger/hyppige fjellblotninger. Tykkelsen på avsetningene er normalt mindre enn 0,5 m, men den kan helt lokalt være noe mer.</td>
      <td></td>
    </tr>
    <tr>
      <td>Moreneleire</td>
      <td>Morenemateriale med særlig høyt leir- og siltinnhold, oftest meget kompakt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Avsmeltningsmorene (Ablasjonsmorene)</td>
      <td>Hauger og rygger med løst lagret, delvis vannbehandlet og noe sortert morenemateriale avsatt fra stagnerende breer (dødis). Terrenget er preget av haug- og ryggformer med vekslende orientering.</td>
      <td></td>
    </tr>
    <tr>
      <td>Randmorene/randmorenebelte</td>
      <td>Rygger eller belter av morenemateriale som er skjøvet opp foran brefronten. Materialet er usortert og inneholder alle kornstørrelser fra leir til blokk. Noen steder kan morenematerialet finnes i veksling med breelvmateriale.</td>
      <td></td>
    </tr>
    <tr>
      <td>Drumlin</td>
      <td>Langstrakt, rettlinjet morenerygg dannet langs isbevegelsesretningen i bunnen av en bre. Ofte stor tykkelse, avrundet form og lengden kan være opp til noen km.</td>
      <td></td>
    </tr>
    <tr>
      <td>Rogenmorene</td>
      <td>Rygger av morenemateriale, orientert på tvers av brebevegelsen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Breelvavsetning (Glasifluvial avsetning)</td>
      <td>Materiale transportert og avsatt av breelver. Sedimentet består av sorterte, ofte skråstilte lag av forskjellig kornstørrelse fra fin sand til stein og blokk. Breelvavsetninger har ofte klare overflateformer som terrasser, rygger og vifter. Mektigheten er ofte flere ti-talls meter.</td>
      <td></td>
    </tr>
    <tr>
      <td>Breelv- og elveavsetning</td>
      <td>Materiale transportert og avsatt av elver eller breelver. Sedimentet består av sorterte lag av forskjellig kornstørrelse fra fin sand til grus og stein. Det er ikke skilt mellom breelv- og elveavsetninger. Brukes kun i spesielle tilfeller.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ryggformet breelvavsetning (Esker)</td>
      <td>Sortert og lagdelt materiale, vesentlig sand og grus, avsatt i tunneler eller sprekker i breen. Der avsetningen er stor nok til å danne figur på kartet brukes fargen for breelvavsetninger til å angi utbredelsen og eskersymbolet til å angi ryggformen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Haugformet breelvavsetning (Kame)</td>
      <td>Materiale avsatt av smeltevann i hulrom i breen. Store avsetninger gis fargen for breelvavsetninger i kombinasjon med symbol for kame.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bresjø-/eller brekammeravsetning (Glasilakustrin avsetning)</td>
      <td>Finkornig materiale avsatt i bresjø eller vannfylt brekammer hvor tykkelsen er mer enn 0,5 m og arealdekningen er stor nok til å danne figur på kartet. Mektigheten kan være flere ti-talls meter.</td>
      <td></td>
    </tr>
    <tr>
      <td>Breelv- og bresjø-/brekammeravsetning (Glasifluvial og glasilakustrin avsetning)</td>
      <td>Materiale avsatt av breelv eller i bredemte sjøer/brekammer. Det er ikke skilt mellom breelv- og bresjø-/kammeravsetninger.</td>
      <td></td>
    </tr>
    <tr>
      <td>Innsjøavsetning (Lakustrin avsetning)</td>
      <td>Materiale avsatt i innsjøer hvor tykkelsen er mer enn 0,5 m.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bresjø-/brekammer og innsjøavsetning (Glasilakustrin og lakustrin avsetning)</td>
      <td>Benyttes hvis en ønsker å slå sammen de to avsetningstypene. I tilfelle brukes ikke separate farger for bresjø og innsjø på det samme kartbladet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Strandavsetning, innsjø og/eller bresjø</td>
      <td>Strandvaskede sedimenter med mektighet større enn 0,5 m, dannet ved bølgeaktivitet i ferskvann. Materialet er ofte rundet og godt sortert. Kornstørrelsen varierer, men sand og grus er vanligst.</td>
      <td></td>
    </tr>
    <tr>
      <td>Hav- og fjordavsetning, uspesifisert</td>
      <td>Benyttes ved kartframstilling i svært små målestokker der en ikke skiller etter mektighet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Hav- og fjordavsetning, sammenhengende dekke, ofte med stor mektighet</td>
      <td>Finkornige, marine avsetninger med mektighet fra 0,5 m til flere ti-tall meter. Avsetningstypen omfatter også skredmasser fra kvikkleireskred, ofte angitt med tilleggssymbol. Det er få eller ingen fjellblotninger i området.</td>
      <td></td>
    </tr>
    <tr>
      <td>Marin strandavsetning, sammenhengende dekke</td>
      <td>Marine strandvaskede sedimenter med mektighet større enn 0,5 m, dannet av bølge- og strømaktivitet i strandsonen, stedvis som strandvoller. Materialet er ofte rundet og godt sortert. Kornstørrelsen varierer fra sand til blokk, men sand og grus er vanligst. Strandavsetninger ligger som et forholdsvis tynt dekke over berggrunn eller andre sedimenter.</td>
      <td></td>
    </tr>
    <tr>
      <td>Hav- og fjordavsetning  og strandavsetning, usammenhengende eller tynt dekke over berggrunnen</td>
      <td>Grunnlendte områder/hyppige fjellblotninger. Tykkelsen på avsetningene er normalt mindre enn 0,5 m, men den kan helt lokalt være noe større. Det er ikke skilt mellom hav-, fjord- og strandavsetning. Kornstørrelser angis normalt ikke, men kan være alt fra leir til blokk.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skjellsand</td>
      <td>Avsetning som i stor grad består av knuste skall av kalkutskillende organismer. Er en type av bioklastisk materiale. Kornstørrelse varierer fra nesten hele skall til sand. Det kan være ansamlet store mengder av skjellsand i umiddelbar nærhet av gode skjellvekstområder.</td>
      <td></td>
    </tr>
    <tr>
      <td>Marin gytje</td>
      <td>Avsetning som består av finkornig materiale, silt og leir med høyt organisk innhold. Det organiske materialet er primærprodusert i vannmassene. Marin gytje finnes i områder hvor det er liten materialtransport fra land. Brukes sjelden.</td>
      <td></td>
    </tr>
    <tr>
      <td>Elve- og bekkeavsetning (Fluvial avsetning)</td>
      <td>Materiale som er transportert og avsatt av elver og bekker. De mest typiske formene er elvesletter, terrasser og vifter. Sand og grus dominerer, og materialet er sortert og rundet. Mektigheten varierer fra 0,5 til mer enn 10 m.</td>
      <td></td>
    </tr>
    <tr>
      <td>Elveavsetning, sammenhengende dekke</td>
      <td>Materiale som er transportert og avsatt av elver og bekker. De mest typiske formene er elvesletter, terrasser og vifter. Sand og grus dominerer, og materialet er sortert og rundet. Brukes kun i spesielle tilfeller.</td>
      <td></td>
    </tr>
    <tr>
      <td>Elveavsetning, usammenhengende/tynt dekke</td>
      <td>Grunnlendte områder med elveavsetninger. Brukes kun i spesielle tilfeller.</td>
      <td></td>
    </tr>
    <tr>
      <td>Flomavsetning (uspesifisert)</td>
      <td>Brukes for spesielle sedimenter avsatt ved plutselig uttapning av bresjøer.</td>
      <td></td>
    </tr>
    <tr>
      <td>Flomavsetning, sammenhengende</td>
      <td>Brukes for spesielle sedimenter avsatt ved plutselig uttapning av bresjøer.</td>
      <td></td>
    </tr>
    <tr>
      <td>Flomavsetning, usammenhengende/tynt</td>
      <td>Brukes for spesielle sedimenter avsatt ved plutselig uttapning av bresjøer. Tykkelse mindre enn 0,5 m.</td>
      <td></td>
    </tr>
    <tr>
      <td>Vindavsetning (Eolisk avsetning)</td>
      <td>Flygesand med tykkelse mer enn 0,5 m.</td>
      <td></td>
    </tr>
    <tr>
      <td>Forvitringsmateriale, ikke inndelt etter mektighet</td>
      <td>Løsmasser dannet på stedet ved fysisk eller kjemisk nedbryting av berggrunnen. Gradvis overgang til underliggende fast fjell. Brukes når en ikke skiller mellom sammenhengende og usammenhengende dekke av denne avsetningstypen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Forvitringsmateriale, sammenhengende dekke</td>
      <td>Løsmasser dannet på stedet ved fysisk eller kjemisk nedbryting av berggrunnen. Tykkelsen er mer enn 0,5 m.</td>
      <td></td>
    </tr>
    <tr>
      <td>Forvitringsmateriale, usammenhengende eller tynt dekke over berggrunnen</td>
      <td>Løsmasser dannet på stedet ved fysisk eller kjemisk nedbryting av berggrunnen. Grunnlendt område med tallrike fjellblotninger.</td>
      <td></td>
    </tr>
    <tr>
      <td>Forvitringsmateriale, stein- og blokkrikt, dannet ved frostsprengning</td>
      <td>Blokkhav, oftest i fjellområder.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skredmateriale, ikke inndelt etter mektighet</td>
      <td>Avsetninger dannet ved steinsprang, fjellskred, snø- eller løsmasseskred fra bratte dalsider. Uspesifisert tykkelse.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skredmateriale, sammenhengende dekke, stedvis med stor mektighet</td>
      <td>Avsetninger dannet ved steinsprang, fjellskred, snøskred eller løsmasseskred fra bratte dalsider. Symbol viser dominerende skredtype. Tykkelsen er mer enn 0,5 m og det er få fjellblotninger i området.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skredmateriale, usammenhengende eller tynt dekke over berggrunnen</td>
      <td>Grunnlendte områder med avsetninger fra steinsprang, fjellskred, snø- og løsmasseskred fra bratte dalsider. Symbol viser dominerende skredtype. Tykkelse mindre enn 0,5 m.</td>
      <td></td>
    </tr>
    <tr>
      <td>Steinbreavsetning</td>
      <td>Steinur som inneholder/har inneholdt is og derfor er i bevegelse/har vært i bevegelse som en vanlig bre. Avsetningstypen dannes under permafrostforhold.</td>
      <td></td>
    </tr>
    <tr>
      <td>Torv og myr (Organisk materiale)</td>
      <td>Organisk jord dannet av døde planterester, med mektigheter større enn 0,5 m. Det skilles ikke mellom ulike torvtyper.</td>
      <td></td>
    </tr>
    <tr>
      <td>Humusdekke/tynt torvdekke over berggrunn</td>
      <td>Områder hvor humusdekket ligger rett på berggrunnen. Mektigheten av humusdekket er vanligvis 0,2 - 0,5 m, men kan lokalt være tykkere. Fjellblotninger opptrer hyppig innen slike områder. Fjellblotninger opptrer hyppig innen slike områder.</td>
      <td></td>
    </tr>
    <tr>
      <td>Usammenhengende eller tynt løsmassedekke over berggrunnen, flere løsmassetyper, uspesifisert</td>
      <td>Forskjellige sedimenter som danner et tynt eller usammenhengende dekke over berggrunnen. Denne betegnelsen brukes bare i spesielle tilfeller når en ikke velger å skille mellom ulike typer av løsmasser.</td>
      <td></td>
    </tr>
    <tr>
      <td>Sammenhengende løsmassedekke av flere jordarter</td>
      <td>Vanligvis skredmateriale med morenemateriale, forvitringsmateriale, torv og humus sterkt blanda ved skråningsprosesser. Brukes kun i spesielle tilfeller der det er meget vanskelig å skille mellom opprinnelige løsmassetyper.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bart fjell/fjell med tynt torvdekke, uspesifisert</td>
      <td>Brukes når en ikke velger å skille mellom bart fjell og humusdekke eller tynt torvdekke over berggrunnen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fyllmasse (antropogent materiale)</td>
      <td>Løsmasser tilført eller sterkt påvirket av menneskers aktivitet, vesentlig i urbane områder.</td>
      <td></td>
    </tr>
    <tr>
      <td>Steintipp</td>
      <td>Tilførte steinmasser.</td>
      <td></td>
    </tr>
    <tr>
      <td>Menneskepåvirket materiale, ikke nærmere spesifisert</td>
      <td>Dominerende stedegne masser, omarbeidet i overflaten.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bart fjell</td>
      <td>Brukes om områder som stort sett mangler løsmasser, mer enn 50 % av arealet er fjell i dagen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bart fjell/fjell med usammenhengende eller  tynt løsmassedekke</td>
      <td>Brukes på oversiktskart der bart fjell slås sammen med alle typer tynt eller usammenhengende løsmassedekke.</td>
      <td></td>
    </tr>
    <tr>
      <td>Marin suspensjonsavsetning</td>
      <td>Finkornige (leire, silt) sedimenter transportert og avsatt fra suspensjon. Draperer vanligvis underliggende sedimenter eller fjell og er oftest lagdelt.</td>
      <td></td>
    </tr>
    <tr>
      <td>Marin bunnstrømavsetning</td>
      <td>Sedimenter som består av sand og grus transportert og avsatt fra bunnstrømmer. Dekker bunnen av undersjøiske kanaler laget av bunnstrømmer. Har ofte kryss-sjiktet og lentikulær- sjiktet indre struktur.</td>
      <td></td>
    </tr>
    <tr>
      <td>Glasimarin avsetning</td>
      <td>Hovedsakelig finkornige suspensjonsavsetninger (silt, leire) avsatt i nærhet av is/isbreer. Kan være påvirket av bunnstrømmer og utjevner topografien mer enn draperer. Forekommer i mektige lag i områder på kontinentalhyllen langs kysten og i fjorder</td>
      <td></td>
    </tr>
    <tr>
      <td>Iskontaktavsetning</td>
      <td>Sedimenter avsatt i kontakt med is. Kan være morene, glasifluvialt materiale, eller en blanding av glasialt avsatte sedimenter. Kornstørrelsen veksler mellom leire og grus alt etter hvilke prosesser som virket.</td>
      <td></td>
    </tr>
    <tr>
      <td>Utvaskingslag</td>
      <td>Sedimenter bestående av sand, grus og bergartsfragmenter etter at finstoffet er vasket vekk av bølger og strøm. Danner et dekkende lag over morene eller andre jordarter med stor variasjon i kornstørrelser.</td>
      <td></td>
    </tr>
    <tr>
      <td>Glasifluvial deltaavsetning (marin)</td>
      <td>Sedimenter transportert av breelver og avsatt i hav, bresjø eller innsjø.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fluvial deltaavsetning</td>
      <td>Sedimenter avsatt ved utløpet av en elv i en fjord, innsjø eller i havet. Kornstørrelsen er ofte i sandfraksjonen nær elveutløpet og mer finkornig på dypere vann. Har typisk skrålaging med helling i strømretningen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Tidevannsavsetning</td>
      <td>Avsetning dannet i kystnære områder ved tidevannstransport. Sedimentene er sandige til leirholdige med typiske strukturer som sanddyner, rifler, kryss-sjikting, mikro-kryss-sjikting, flasersjikting og lentikulær sjikting.</td>
      <td></td>
    </tr>
    <tr>
      <td>Estuarin avsetning</td>
      <td>Et sediment avsatt i brakkvann i et estuarie. Sedimentet er karakterisert av finkornig materiale (silt, leire) av marin og fluvial opprinnelse blandet med en høy andel rester av terrestrisk organisk materiale.</td>
      <td></td>
    </tr>
    <tr>
      <td>Levé avsetning (marin)</td>
      <td>Avsetning dannet som en forhøyning av sedimenter langs en eller begge sidene  av en undersjøisk kanal (kløft, viftedal eller dyphavskanal). Avsetningen kan ha varierende kornstørrelse, fra finkornig (leir) til nokså grovt materiale (sand).</td>
      <td></td>
    </tr>
    <tr>
      <td>Grunnmarin avsetning</td>
      <td>Sedimenter avsatt i turbulent grunt marint miljø der det fineste materialet er vasket ut og transportert til dypere vann av strømmer og bølger. Består av sand, grus og stein. I områder med mye sand kan sandbølger bygges med en karakteristisk kryss-sjikting og skrålaging.</td>
      <td></td>
    </tr>
    <tr>
      <td>Konturittavsetning</td>
      <td>Klastiske sedimenter transportert og avsatt av kontur-strømmer langs egga kanten. Består av fint, velsortert materiale (silt og leir). Avsetningene har vanligvis horisontal- eller kryss-sjiktning og normal- eller omvendt gradering.</td>
      <td></td>
    </tr>
    <tr>
      <td>Turbitittavsetning</td>
      <td>Avsetninger dannet ved sedimenttransport og utfelling fra en turbidittstrøm.  Består av materiale i kornstørrelse fra leire til sand og er ofte karakterisert ved normalgradert lagning og moderat til dårlig sortering. Finnes oftest ved foten av skråninger med stor mektighet av løse sedimenter (for eksempel langs kontinentalskråningen).</td>
      <td></td>
    </tr>
    <tr>
      <td>Debrisstrømavsetning</td>
      <td>Avsetning fra en flytende masse av stein, jord og slam. Den består av usortert materiale der mer enn halvparten av partiklene er større enn sandstørrelse.</td>
      <td></td>
    </tr>
    <tr>
      <td>Undersjøisk vifteavsetning</td>
      <td>En konisk eller vifteformet avsetning beliggende ved munningen av en undersjøisk kløft. Består for det meste av fine sedimenter (leire, silt). Viften har en finlaget indre struktur med en svak helling av lagene mot dyphavet.</td>
      <td></td>
    </tr>
    <tr>
      <td>Kanalsavsetning</td>
      <td>Sedimenter avsatt i en kanal. Avsetningene vil vanligvis bestå av relativt grove sedimenter (sand, grus)</td>
      <td></td>
    </tr>
    <tr>
      <td>Dypmarin avsetning</td>
      <td>Samlebetegnelse på dyphavssedimenter. Kan være både konturittisk, hemipelagisk, eupelagisk osv. Dette er fine sedimenter bunnfelt utenfor kontinentalmarginen. Består i stor grad av leire og rester av pelagiske organismer.</td>
      <td></td>
    </tr>
    <tr>
      <td>Bioklastisk avsetning</td>
      <td>Sediment som for en stor del består av små partikler av biologisk opprinnelse (skjell, korall). Kornstørrelsen kan variere fra sand til hele skjell eller korallkolonier. Forekommer i begrensete områder der vekstforholdene har vært optimale over lengre tid og mengden av annet klastisk materiale liten.</td>
      <td></td>
    </tr>
    <tr>
      <td>Vulkanosedimentær avsetning</td>
      <td>Avsetning som består av materiale av vulkansk opprinnelse. Alt etter kornstørrelse kan sedimentene deles inn i vulkansk aske, lapilli (2-64 mm) og breksje (&gt;64mm).</td>
      <td></td>
    </tr>
    <tr>
      <td>Lagdelte sedimenter (&gt;1 m) over debrisstrøm</td>
      <td>Lagdelte sedimenter (&gt;1m) over debrisstrømavsetning.</td>
      <td></td>
    </tr>
    <tr>
      <td>Skredmateriale, dekket av yngre sedimenter</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skredmateriale, delvis dekket av yngre sedimenter</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Skredmateriale og hemipelagiske avsetninger</td>
      <td>Veksling mellom skredavsetninger og hemipelagiske avsetninger. Hemipelagiske avsetninger består stort sett av finkornet materiale, delvis produsert i vannmassene lokalt, og delvis tilført utenifra.</td>
      <td></td>
    </tr>
    <tr>
      <td>Uspesifisert marin avsetning</td>
      <td>Marin avsetning med ukjent opprinnelse.</td>
      <td></td>
    </tr>
    <tr>
      <td>Jordskredavsetning, sammenhengende dekke, stedvis med stor mektighet</td>
      <td>Avsetning som dannes når løsmasser i bratt terreng løsner og raser nedover. Danner ofte karakteristiske vifte- eller tungelignende former.</td>
      <td></td>
    </tr>
    <tr>
      <td>Jordskredavsetning, usammenhengende eller tynt dekke</td>
      <td>Grunnlendt avsetning som dannes når løsmasser i bratt terreng løsner og raser nedover.</td>
      <td></td>
    </tr>
    <tr>
      <td>Leirskredavsetning, sammenhengende dekke, stedvis med stor mektighet</td>
      <td>Avsetning som dannes når leirholdige sedimenter løsner og glir ut.</td>
      <td></td>
    </tr>
    <tr>
      <td>Leirskredavsetning, usammenhengende eller tynt dekke over berggrunnen</td>
      <td>Avsetning som dannes når leirholdige sedimenter løsner og glir ut.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjellskredavsetning, sammenhengende dekke, stedvis med stor mektighet</td>
      <td>Dannes når store fjellparti løsner og med kolossal kraft går ned i daler og fjorder. Består mest av kantete blokker.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjellskredavsetning, usammenhengende eller tynt dekke</td>
      <td>Grunnlendte områder med fjellskredmateriale.</td>
      <td></td>
    </tr>
    <tr>
      <td>Steinsprangavsetning, sammenhengende dekke, stedvis med stor mektighet</td>
      <td>Materiale som har løsnet fra fast fjell og over tid akkumulert som bratte urer ved foten av skråninger. Materialet varierer fra sand til blokk, med økende kornstørrelse nedover skråningen.</td>
      <td></td>
    </tr>
    <tr>
      <td>Steinsprangavsetning, usammenhengende eller tynt dekke</td>
      <td>Grunnlendte områder med steinsprangmateriale.</td>
      <td></td>
    </tr>
    <tr>
      <td>Snøskredavsetning, sammenhengende dekke, stedvis med stor mektighet</td>
      <td>Dannes i områder med gjentatte snøskred og har ofte vifteform.</td>
      <td></td>
    </tr>
    <tr>
      <td>Snøskredavsetning, usammenhengende eller tynt dekke</td>
      <td>Grunnlendte områder med snøskredmateriale.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjellskred-/steinsprangavsetning, sammenhengende dekke, stedvis med stor mektighet</td>
      <td>Materiale bestående av steinblokker fra større fjellparti som har løsnet og rast ned. Består hovedsakelig av usortert grovt materiale (stein og blokk) og finnes oftest ved foten av skrenter/fjellsider.</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjellskred-/steinsprangavsetning, usammenhengende eller tynt dekke</td>
      <td>Grunnlendte områder med fjellskred-/steinsprangmateriale.</td>
      <td></td>
    </tr>
    <tr>
      <td>Snø- og jordskredavsetning, sammenhengende dekke</td>
      <td>Dannes i områder med vekslende snø- og jordskred.</td>
      <td></td>
    </tr>
    <tr>
      <td>Snø- og jordskredavsetning, usammenhengende eller tynt dekke</td>
      <td>Grunnlendte områder med snøskredmateriale og jordskredmateriale.</td>
      <td></td>
    </tr>
    <tr>
      <td>Jordskred- og steinsprangavsetning, sammenhengende dekke</td>
      <td>Dannes i bratt terreng der både jordskred og steinsprang forekommer.</td>
      <td></td>
    </tr>
    <tr>
      <td>Jordskred- og steinsprangavsetning, usammenhengende eller tynt dekke</td>
      <td>Grunnlendte områder med jordskred- og steinsprangmateriale.</td>
      <td></td>
    </tr>
    <tr>
      <td>Finkornig organiskholdig sigejord</td>
      <td>Sterkt frostpåvirket blandingsmateriale som beveger seg sakte nedover slake skråninger, dannet fra en eller flere opprinnelig finstoffholdige løsmassetyper.</td>
      <td></td>
    </tr>
    <tr>
      <td>Steinrikt sigende skråningsmateriale</td>
      <td>Grovkornig frostpåvirket blandingsmateriale som beveger seg sakte nedover skråninger, dannet fra forvitret fjell, skråningsmateriale eller morenemateriale.</td>
      <td></td>
    </tr>
  </tbody>
</table>
