#### VertikalObjektKomponentPunkt

Egenskaper tilhørende en VertikalObjektKomponent som er et punkt.

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
      <td>det geografiske punktobjektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>href</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>koordinatregistering utført på topp eller bunn av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Høyden målt til foten av objektet<br />- Høyden målt til toppen av objektet<br />- Ukjent – benyttes ikke ved nyregistrering</td>
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
      <td><strong>hrefSystem</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanseflate som er utgangspunktet for høydekoordinat.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferansesystem</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ellipsoide jf. KOORDSYS<br />- Lokal referanseflate<br />- Geoide bestemt av NKG i 1989 – NKG: The Nordic Geodetic Commission - founded in 1953 - is an association of geodesists from Denmark, Finland, Iceland, Norway and Sweden. Its purpose is to give the members possibilities of fruitful gatherings and mutual exchange of professional views and experiences. The NKG is recognized and supported by a number of Nordic  organizations, such as the Director Generals of the Nordic Mapping Authorities. (Kilde: <a href="http://217.152.180.26/nkg/">http://217.152.180.26/nkg/</a>)<br />- Norsk Null av 1954 – Denne er identisk med NN1954<br />- Nord-Norsk Null av 1957 – For nyere data er denne gått ut av bruk. Er erstattet av NN54.<br />- Norsk Null av 2000 – Nytt felles nordisk vertikalt datum, basert på Normaal Amsterdals Peil.</td>
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
      <td><strong>identifikasjonPunkt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>IdentifikasjonPunkt</td>
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
      <td><strong>identifikasjonPunkt.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />Merknad: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>identifikasjonPunkt.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>identifikasjonPunkt.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterer. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />Merknad: Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
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
      <td><strong>kvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av kvaliteten på stedfestingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td>- Terrengmålt – Målt i terrenget<br />- Tatt fra plan – Tatt fra plan eller godkjent tiltak<br />- Annet<br />- Stereoinstrument – Målt i stereoinstrument, uspesifisert instrument<br />- Analytisk plotter – Målt i stereoinstrument, analytisk plotter<br />- Digitalt stereoinstrument – Målt i stereoinstrument, digitalt instrument<br />- Flybåren laserscanner – Målt med laserskanner fra fly<br />- Digitalisert fra ortofoto – Geometri overført fra ortofoto ved hjelp av manuell registrering på skjerm<br />- Digitalisert på skjerm fra satellittbilde – Geometri overført fra satelittbilde ved hjelp av manuell registrering på skjerm<br />- Dig. på skjerm fra scannet samkopi – Geometri overført fra kart ved hjelp av manuell registrering på skjerm, medium skannet kart (raster), samkopi<br />- Genererte data (interpolasjon) – Genererte data, interpolasjonsmetode. Ikke nærmere spesifisert<br />- Frihåndstegning – Digitalisert ut fra frihåndstegning.  Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag<br />- Digitalisert fra krokering på kart – Digitalisert fra krokering på kart, dvs grovt skissert på kart<br />- Direkte innlagt på skjerm – Digitalisert ut fra frihåndstegning (direkte på skjerm). Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag<br />- Ukjent målemetode – Målemetode er ukjent<br />- GPS Kodemåling, relative målinger – Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, relative målinger.<br />- GPS Kodemåling, enkeltmålinger – Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS,
GALILEO): Kodemåling, enkle målinger.</td>
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
      <td>punktstandardavviket i grunnriss for punkter<br /><br />Merknad:<br />Oppgitt i cm</td>
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
      <td><strong>kvalitet.synbarhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvor godt den kartlagte detalj var synbar ved kartleggingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Synbarhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Fullt ut synlig/gjenfinnbar i terrenget – Default<br />- Dårlig gjenfinnbar i terreng – Forøvrig grei å innmåle. (Benyttes bl.a. for innmåling av ledninger på lukket grøft)<br />- Middels synlig i flybilde/modell<br />- Dårlig/ikke synlig i flybilde/modell</td>
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
      <td><strong>kvalitet.målemetodeHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for å måle høyden</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MålemetodeHøyde</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Terrengmålt – Målt i terrenget<br />- Tatt fra plan – Tatt fra plan eller godkjent tiltak<br />- Annet<br />- Stereoinstrument – Målt i stereoinstrument, uspesifisert instrument<br />- Analytisk plotter – Målt i stereoinstrument, analytisk plotter<br />- Digitalt stereoinstrument – Målt i stereoinstrument, digitalt instrument<br />- Flybåren laserscanning – Målt med laserskanner fra fly<br />- Genererte data (interpolasjon) – Genererte data, interpolasjonsmetode. Ikke nærmere spesifisert<br />- Generert i terrengmodell – Genererte data, interpolasjonsmetode, fra terrengmodell<br />- Målt med stigningsmåler<br />- GPS Kodemåling, relative målinger. – Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, relative målinger.<br />- GPS Kodemåling, enkeltpunktbestemmelser – Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS,
GALILEO): Kodemåling, enkle målinger.<br />- Ukjent målemetode</td>
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
      <td><strong>kvalitet.nøyaktighetHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nøyaktighet for høyden i cm</td>
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
VertikalObjektKomponent

#### Supertype_VertikalObjekt (abstrakt)

VertkalObjekt inneholder felles egenskaper for alle VertikalObjektKomponenter som til sammen utgjør et luftfartshinder. Her listes egenskaper som er arvet fra SOSI objekt.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>datafangstdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato da objektet siste gang ble innmålt</td>
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
      <td><strong>endringsflagg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>endringsinformasjon om et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Endringsflagg</td>
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
      <td><strong>endringsflagg.typeEndring</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>endringsstatus for objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TypeEndring</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Endret<br />- Nytt<br />- Slettet</td>
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
      <td><strong>endringsflagg.tidspunktEndring</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tidspunkt for endring av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>gyldigFra</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Tidspunktet når objektet oppstod i den virkelige verden</td>
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
      <td><strong>gyldigTil</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Tidspunktet når objektet opphørte å eksistere i den virkelige verden</td>
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
      <td><strong>informasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>generell opplysning<br /><br />Merknad:<br />mulighet til å legge inn utfyllende informasjon om objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
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
      <td><strong>link</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanse  til et informasjonselement, enten lokalt eller globalt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Link</td>
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
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektdataene<br /><br />Merknad:<br />Oppdateringsdato refererer til en endring av dataene i registeret. Dataene kan dermed endres som følge av en forvaltningsmessig beslutning uten at det virkelige objektet i terrenget er endret.</td>
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
      <td><strong>opphav</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets tilstand, se gyldige koder i kodeliste Status</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Eksisterende (default) – Identisk med tidligere SITSTAT = 3

-- Definition --
Identical with previous SITSTAT = 3<br />- Kondemnert – Ikke lenger et hinder.<br />- Ombygd – Hindret er ombygd (blir vanligvis ikke brukt)<br />- Planlagt – Hindret skal bygges<br />- Under arbeid – Hinderet er under bygging/ombygging<br />- Fjernet – Feilregistrert i registeret, skulle aldri vært der.</td>
    </tr>
  </tbody>
</table>

#### Supertype_VertikalObjektKomponent (abstrakt)

Et luftfartshinder kan bestå av ett eller flere VertikalObjektKomponent. Her listes egenskaper som er arvet fra SOSI-objekt.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>verifiseringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato når dataene er fastslått å være i samsvar med virkeligheten<br /><br />Merknad: Verifiseringsdato er identisk med ..DATO i tidligere versjoner av SOSI</td>
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
      <td><strong>oppdateringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for siste endring på objektdataene<br /><br />Merknad:<br />Oppdateringsdato refererer til en endring av dataene i registeret. Dataene kan dermed endres som følge av en forvaltningsmessig beslutning uten at det virkelige objektet i terrenget er endret.</td>
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
      <td><strong>endringsflagg</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>endringsinformasjon om et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Endringsflagg</td>
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
      <td><strong>endringsflagg.typeEndring</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>endringsstatus for objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>TypeEndring</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Endret<br />- Nytt<br />- Slettet</td>
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
      <td><strong>endringsflagg.tidspunktEndring</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tidspunkt for endring av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>status</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektets tilstand, se gyldige koder i kodeliste Status</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Status</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Eksisterende (default) – Identisk med tidligere SITSTAT = 3

-- Definition --
Identical with previous SITSTAT = 3<br />- Kondemnert – Ikke lenger et hinder.<br />- Ombygd – Hindret er ombygd (blir vanligvis ikke brukt)<br />- Planlagt – Hindret skal bygges<br />- Under arbeid – Hinderet er under bygging/ombygging<br />- Fjernet – Feilregistrert i registeret, skulle aldri vært der.</td>
    </tr>
  </tbody>
</table>

#### VertikalObjekt

VertkalObjekt inneholder felles egenskaper for alle VertikalObjektKomponenter som til sammen utgjør et luftfartshinder. Her listes egenskaper som ikke er arvet fra SOSI objekt.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kommentarVertikalObjektType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvis "Annet" velges på vertikalObjektType skal dette spesifiseres her</td>
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
      <td><strong>vertikalObjektGruppe</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>indikerer om VertikalObjekt er en representant for et antall nært lokaliserte objekter av samme type</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>JaNei</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ja<br />- Nei<br />- Ukjent</td>
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
      <td><strong>vertikalObjektNavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Navn på VertikalObjekt.</td>
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
      <td><strong>vertikalObjektType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>her angis det hvilken type vertikalt objekt dette objektet er, se egen kodeliste</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>VertikalObjektType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Landbruksutstyr – hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode AG_EQUIP<br />- Telemast – mast med radio- og telekommunikasjonsutstyr for sending/mottak av telesignaler

tilsvarer klasse MastTele i Ledningsnett 4.0<br />- Bru – hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode BRIDGE<br />- Bygning – hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode BUILDING<br />- Gondolbane – hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode CABLE_CAR<br />- Kontrolltårn – hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode CONTROL_TOWER<br />- Kjøletårn – hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode COOLING_TOWER<br />- Kran – hentet fra AIXM 5.1 klasse CodeVerticalStructureType

gjelder også heisekrantypene skinnekran/havnekran, tårnkran/byggekran, mobilkran, flytekran<br />- Demning – hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode DAM<br />- Kuppel – hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode DOME<br />- EL_Nettstasjon – stasjon som transformerer elektrisitet fra et høyspentnivå til et lavere

tilsvarer EL_Transformatorstasjon og EL_Nettstasjon i SOSI Ledning 4.5

Merk: Gjelder alle typer transformasjoner. I standarden for luftfartshinder skiller vi ikke mellom ulike typer transformasjoner som for eksempel transformasjon til lavere eller høyere enn 230 V slik det gjøres i SOSI Ledning 4.5.<br />- Gjerde – hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode FENCE<br />- Fyrtårn – hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode LIGHTHOUSE<br />- Monument – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode MONUMENT<br />- Terrengpunkt – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode NATURAL_HIGHPOINT<br />- Navigasjonshjelpemiddel – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode NAVAID

Gjelder kun radio instrumenter som brukes ifm navigasjon for luftfartøy og ikke hjelpemidler til andre form for navigasjon, som for eksempel til sjøs.<br />- Stolpe – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode POLE<br />- Kraftverk – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode POWER_PLANT<br />- Raffineri – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode REFINERY<br />- Oljerigg – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode RIG<br />- Skilt – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode SIGN<br />- Pipe – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode STACK<br />- Tank – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode TANK<br />- Forankret ballong – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode TETHERED_BALLOON<br />- Tårn – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode TOWER<br />- Kraftledning – linje som fører elektrisk kraft over store avstander

tilsvarer klasse LuftledningLH i SOSI Ledningsnett 4.0 og kodene "Høgspentnett" og "Lavspentnett" i kodelista Ledningsnettverkstype i SOSI Ledningsnett 4.5

tilsvarer også kode TRANSMISSION_LINE
hentet fra AIXM 5.1 klasse CodeVerticalStructureType<br />- Tre – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode TREE<br />- Skogsområde – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode VEGETATION

gjelder også klasse lufthavnhinderTregruppe i SOSI Lufthavn 4.1<br />- Vanntårn – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode WATER_TOWER<br />- Vindmølle – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode WINDMILL<br />- Vindmøllepark – hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode WINDMILL_FARMS<br />- Hopptårn – tilsvarer klasse Hoppbakke i SOSI Bygnan 4.0

ikke dommertårnet<br />- Vindmåler – meteorologisk instrument som måler vindhastighet og vindretning<br />- Lysmast – mast brukt for montering av ulike lyskilder<br />- Flaggstang – lang rett stang for heising av flagg

tilsvarer klasse Flaggstang i SOSI Bygnan 4.0<br />- Petroleumsinnretning – innretning, installasjon, anlegg og annet utstyr for petroleumsvirksomhet, likevel ikke forsynings- og hjelpefartøy eller skip som transporterer petroleum i bulk

tilsvarer klasse Petroleumsinnretning i SOSI Petroleum 4.0<br />- Silo – lagringsbygg for fôr og korn som ikke er registrert som bygning i GAB

tilsvarer klasse Silo i SOSI Bygnan 4.0

Merknad: I motsetning til definisjonen av klasse Silo i SOSI Bygnan 4.0 vil dette også gjelde store silobygg<br />- Stolheis – taubane med stoler til persontransport

tilsvarer klasse Stolheis i SOSI Bygnan 4.0<br />- Skitrekk – taubane til å dra skiløper opp bratte bakker

tilsvarer klasse Skitrekk i SOSI Bygnan 4.0<br />- Taubane – innretning hvor tau eller vaiere bærer og eller trekker last over en strekning

tilsvarer klasse Taubane i SOSI Bygnan 4.0<br />- Fornøyelsesparkinnretning – pariserhjul, berg og dal bane og andre høye innretninger i en fornøyelsespark<br />- Annet</td>
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
      <td><strong>identifikasjonObjekt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>IdentifikasjonObjekt</td>
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
      <td><strong>identifikasjonObjekt.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />Merknad: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>identifikasjonObjekt.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>identifikasjonObjekt.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterer. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />Merknad: Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
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
Supertype_VertikalObjekt

**Assosiasjoner**
VertikalObjektKomponentPunkt – rolle: bestårAvVertikalobjKompPunkt – kardinalitet: 0..*
VertikalObjektKomponentLinje – rolle: bestårAvVertikalobjKompLinje – kardinalitet: 0..*

#### VertikalObjektKomponentLinje

Egenskaper tilhørende en VertikalObjektKomponent som er en linje.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>identifikasjonLinje</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>IdentifikasjonLinje</td>
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
      <td><strong>identifikasjonLinje.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />Merknad: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>identifikasjonLinje.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>identifikasjonLinje.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterer. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />Merknad: Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
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
      <td><strong>linjeElement</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>det geografiske linjeobjektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kurve</td>
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
      <td><strong>linjespenn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>informasjon om en VertikalObjektKomponentLinje er et spenn eller ei. Et linjespenn har vertikal utstrekning på 60 m eller høyere eller er av andre årsaker omfattet av merkepålegg fra Luftfartstilsynet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>JaNei</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ja<br />- Nei<br />- Ukjent</td>
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
      <td><strong>lengde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>horisontal avstand mellom start- og sluttpunkt på linjesegment</td>
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
      <td><strong>lengdeMåleenhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>her oppgis måleenheten til lengden av linjesegmentet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Måleenhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- FT – foot<br />- M – meter<br />- CM – centimeter<br />- KM – kilometer</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
VertikalObjektKomponent

**Assosiasjoner**
VertikalObjektKomponentLinjePkt – rolle: avgrensesAvPunkt – kardinalitet: 0..*

#### VertikalObjektKomponent (abstrakt)

Et luftfartshinder kan bestå av ett eller flere VertikalObjektKomponent(er). Her listes egenskaper som ikke er arvet fra SOSI objekt. En VertikalObjektKomponent kan være enten en linje eller et punkt – se VertikalObjektKomponentLinje og VertikalObjektKomponentPunkt.

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>merking</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>samlet informasjon om merking. Gjelder ikke lyssetting. All informasjon om lyssetting ligger under featureType Lyssetting</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Merking</td>
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
      <td><strong>merking.merkingFarge</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>skal brukes hvis merking består av en eller to farger</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..2</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MerkingFarge</td>
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
      <td><strong>merking.merkingFarge.farge</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>farge angis med koder fra definert kodeliste</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Farge</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Svovelgul – RAL 1016 (Sulfur yellow)<br />- Trafikkrød – RAL 3020 (Traffic red)<br />- Lysende rød – RAL 3024 (Luminous red)<br />- Lys grå – RAL 7035 (Light grey)<br />- Agatgrå – RAL 7038 (Agate grey)<br />- Signalhvit – RAL 9003 (Signal white)<br />- Ren hvit – RAL 9010 (Pure white)<br />- Trafikkhvit – RAL 9016 (Traffic white)<br />- Oransje – RAL kode ikke aktuelt, kode er videreført fra gammelt system<br />- Rødt – RAL kode ikke aktuelt, kode er videreført fra gammelt system<br />- Hvitt – RAL kode ikke aktuelt, kode er videreført fra gammelt system<br />- Annet</td>
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
      <td><strong>merking.merkingFarge.annet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvis "annet" velges på attributt farge, må dette spesifiseres her</td>
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
      <td><strong>merking.merkingFarge.fluoriserende</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>om fargemerkingen er fluoriserende (selvlysende)</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>JaNei</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ja<br />- Nei<br />- Ukjent</td>
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
      <td><strong>merking.merkingFarge.reflekterende</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>om fargemerkingen er reflekterende</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>JaNei</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ja<br />- Nei<br />- Ukjent</td>
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
      <td><strong>merking.merkingType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>ulike typer merking spesifiseres her</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MerkingType</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Flagg – kan være ensfarget eller mønstret.<br />- Markør – gjelder også blåser<br />- Plater – Objektet er merket med fargede plater<br />- Ukjent – Merketypen er ukjent<br />- Annet – hvis valgt, kreves utfylling av feltet kommentarMerkingType</td>
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
      <td><strong>merking.kommentarMerkingType</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvis "annet" velges på merkingType skal dette spesifiseres her</td>
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
      <td><strong>merking.merkingMønster</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>mønster til merkingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MerkingMønster</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ensfarget<br />- Rutemønstret<br />- Horisontale bånd – to-fargete alternerende horisontale bånd<br />- Vertikale bånd – to-fargete alternerende vertikale bånd<br />- Ukjent<br />- Annet</td>
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
      <td><strong>merking.kommentarMerkingMønster</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvis "Annet" velges på merkingMønster skal dette spesifiseres her</td>
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
      <td><strong>merking.merkingICAO</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvorvidt merking er ihht. ICAO standard</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>JaNei</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ja<br />- Nei<br />- Ukjent</td>
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
      <td><strong>merking.merkingTilstand</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>informasjon om merkingens tilstand</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MerkingTilstand</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Dårlig – Merkingen er vanskelig å se.<br />- Brukbar – Merkingen er mulig å se, men utydelig.<br />- God – Merkingen er godt synlig.<br />- Veldig god – Merkingen er meget godt synlig.<br />- Ukjent – Tilstanden til merking er ukjent.</td>
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
      <td><strong>vertikalUtstrekning</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>objektkomponentens maksimale høyde over terreng- eller vannoverflate</td>
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
      <td><strong>vertikalUtstrekningMåleenhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>her oppgis måleenheten til den vertikale utstrekningen av objektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Måleenhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- FT – foot<br />- M – meter<br />- CM – centimeter<br />- KM – kilometer</td>
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
      <td><strong>merkeplikt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>informasjon om merkeplikt. Gjelder lyssetting og annen merking.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Merkeplikt</td>
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
      <td><strong>merkeplikt.merkepliktig</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvorvidt hinder er merkepliktig</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>JaNei</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ja<br />- Nei<br />- Ukjent</td>
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
      <td><strong>merkeplikt.merkepliktigIhenholdTil</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>regelverk som pålegger merking</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>RegelverkMerkeplikt</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- BSL E 2 – Merket i henhold til forskrift om Bestemmelser for sivil luftfart nr 2.<br />- BSL E 3 – Merket i henhold til forskrift om Bestemmelser for sivil luftfart nr 3.<br />- Pålagt av LT – merking pålagt spesifikt av Luftfartstilsynet<br />- BSL E 2 aggregerte komponenter – enkeltelementer er ikke merkepliktige i utgangspunktet, men de er merkepliktige hvis de oppfyller visse krav når de er sett som helhet<br />- EASA – Merket i henhold til bestemmelser fra EASA<br />- ICAO – Merket i henhold til bestemmelser fra ICAO</td>
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
      <td><strong>merkeplikt.ansvarligForMerking</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvem har ansvar for merking</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>AnsvarligForMerking</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Eier av hinder<br />- Godkjenningsansvarlig for landingsplass-flyplass</td>
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
      <td><strong>merkeplikt.merkeInformasjon</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>utdypende informasjon om merking</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MerkeInformasjon</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- merket i henhold til forskrift<br />- merket i henhold til dispensasjon<br />- merket utover aktuell forskrift<br />- mangler merking<br />- ukjent</td>
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
      <td><strong>merkeplikt.kommentarMerkeplikt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>utfyllende informasjon om en eller flere av de andre attributtene</td>
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
      <td><strong>eksternReferanse</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanse til et eksternt register</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>ReferanseTilEksterntRegister</td>
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
      <td><strong>eksternReferanse.registernavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn til eksternt register</td>
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
      <td><strong>eksternReferanse.eksternId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>ekstern Id av samme objekt i et annet register</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>komponentsekvensnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir rekkefølge på VertikalObjektKomponent som tilhører samme VertikalObjekt</td>
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
      <td><strong>BSLE-2-1_hinder</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvorvidt dette er et hinder ihht. forskrift BSL E 2-1</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>JaNei</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ja<br />- Nei<br />- Ukjent</td>
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
      <td><strong>lyssetting</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hinderlys til bruk ved merking av luftfartshinder i henhold til vedlegg til forskrift om rapportering, registrering og merking av luftfartshinder, BSL E 2-1. I tillegg er det mulig å velge koder fra gammel NRL</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1..*</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Lystype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Lavintensitet type A – rødt, fast, 10 candela<br />- Lavintensitet type B – rødt, fast, 32 candela<br />- Lavintensitet type C – ikke del av oversikten i vedlegg 2 BSL E 2-1, men tatt fra tabell 6-3 i ICAO annex 14<br />- Lavintensitet type D – ikke del av oversikten i vedlegg 2 BSL E 2-1, men tatt fra tabell 6-3 i ICAO annex 14<br />- Mellomintensitet type A – hvitt, blinkende, 20 000 candela ved bakgrunnsbelysning 50 cd/m ² og over, 2000 candela med bakgrunnsbelysning uneder 50 cd/m ²<br />- Mellomintensitet type B – rødt, blinkende, 2000 candela<br />- Mellomintensitet type C – rødt, fast, 2000 candela<br />- Høyintensitet type A – hvitt, blinkende, 200 000 candela ved bakgrunnsbelysning over 500 cd/m², 20 000 candela ved bakgrunnsbelysning 50-500 cd/m² og 2000 candela ved bakgrunnsbelysning under 50 cd/m²<br />- Høyintensitet type B – hvitt, blinkende, 100 000 candela ved bakgrunnsbelysning over 500 cd/m², 20 000 candela ved bakgrunnsbelysning 50-500 cd/m² og 2000 candela ved bakgrunnsbelysning under 50 cd/m²<br />- Belyst med flomlys – objektet er opplys av lyskastere for å være synlig for luftfarten<br />- Fast rødt – brukes dersom vi ikke vet lysstyrke, men har observert lysfarge rød fast lys<br />- Fast hvitt – brukes dersom vi ikke vet lysstyrke, men har observert lysfarge hvit fast lys<br />- Blinkende hvitt – brukes dersom vi ikke vet lysstyrke, men har observert lysfarge hvitt blinkende lys<br />- Blinkende rødt – brukes dersom vi ikke vet lysstyrke, men har observert lysfarge rødt blinkende lys<br />- Lyssatt – brukes dersom man vet at hinderet har lys, men ikke vet farge og type<br />- Ikke lyssatt<br />- Ukjent – benyttes dersom det er ukjent om hinderet har lys eller ikke.</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
Supertype_VertikalObjektKomponent

#### VertikalObjektKomponentLinjePkt

Egenskaper tilhørende en VertikalObjektKomponent som er et punkt.

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
      <td>det geografiske punktobjektet</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
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
      <td><strong>href</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvorvidt koordinatregistering er utført på topp eller bunn av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferanse</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Høyden målt til foten av objektet<br />- Høyden målt til toppen av objektet<br />- Ukjent – benyttes ikke ved nyregistrering</td>
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
      <td><strong>hrefSystem</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>referanseflate som er utgangspunktet for høydekoordinat.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Høydereferansesystem</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Ellipsoide jf. KOORDSYS<br />- Lokal referanseflate<br />- Geoide bestemt av NKG i 1989 – NKG: The Nordic Geodetic Commission - founded in 1953 - is an association of geodesists from Denmark, Finland, Iceland, Norway and Sweden. Its purpose is to give the members possibilities of fruitful gatherings and mutual exchange of professional views and experiences. The NKG is recognized and supported by a number of Nordic  organizations, such as the Director Generals of the Nordic Mapping Authorities. (Kilde: <a href="http://217.152.180.26/nkg/">http://217.152.180.26/nkg/</a>)<br />- Norsk Null av 1954 – Denne er identisk med NN1954<br />- Nord-Norsk Null av 1957 – For nyere data er denne gått ut av bruk. Er erstattet av NN54.<br />- Norsk Null av 2000 – Nytt felles nordisk vertikalt datum, basert på Normaal Amsterdals Peil.</td>
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
      <td><strong>identifikasjonLinjePkt</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>unik identifikasjon av et objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>IdentifikasjonLinjePkt</td>
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
      <td><strong>identifikasjonLinjePkt.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator, tildelt av dataleverendør/dataforvalter. Den lokale identifikatoren er unik innenfor navnerommet, ingen andre objekter har samme identifikator.<br /><br />Merknad: Det er data leverendørens ansvar å sørge for at denne lokale identifikatoren er unik innenfor navnerommet.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>identifikasjonLinjePkt.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til objektet, starter med to bokstavs kode jfr ISO 3166. Benytter understreking  ("_") dersom data produsenten ikke er assosiert med bare et land.<br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og vil registreres i "INSPIRE external  Object Identifier Namespaces Register"<br /><br />Eksempel: NO for Norge.</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td><strong>identifikasjonLinjePkt.versjonId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon av en spesiell versjon av et geografisk objekt (instans), maksimum lengde på 25 karakterer. Dersom spesifikasjonen av et geografisk objekt med en identifikasjon inkludererer livsløpssyklusinformasjon, benyttes denne versjonId for å skille mellom ulike versjoner av samme objekt. versjonId er en unik  identifikasjon av versjonen.<br /><br />Merknad: Maksimum lengde er valgt for å tillate tidsregistrering i henhold til  ISO 8601, slik som  "2007-02-12T12:12:12+05:30" som versjonId.</td>
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
      <td><strong>kvalitet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>beskrivelse av kvaliteten på stedfestingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
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
      <td>- Terrengmålt – Målt i terrenget<br />- Tatt fra plan – Tatt fra plan eller godkjent tiltak<br />- Annet<br />- Stereoinstrument – Målt i stereoinstrument, uspesifisert instrument<br />- Analytisk plotter – Målt i stereoinstrument, analytisk plotter<br />- Digitalt stereoinstrument – Målt i stereoinstrument, digitalt instrument<br />- Flybåren laserscanner – Målt med laserskanner fra fly<br />- Digitalisert fra ortofoto – Geometri overført fra ortofoto ved hjelp av manuell registrering på skjerm<br />- Digitalisert på skjerm fra satellittbilde – Geometri overført fra satelittbilde ved hjelp av manuell registrering på skjerm<br />- Dig. på skjerm fra scannet samkopi – Geometri overført fra kart ved hjelp av manuell registrering på skjerm, medium skannet kart (raster), samkopi<br />- Genererte data (interpolasjon) – Genererte data, interpolasjonsmetode. Ikke nærmere spesifisert<br />- Frihåndstegning – Digitalisert ut fra frihåndstegning.  Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag<br />- Digitalisert fra krokering på kart – Digitalisert fra krokering på kart, dvs grovt skissert på kart<br />- Direkte innlagt på skjerm – Digitalisert ut fra frihåndstegning (direkte på skjerm). Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag<br />- Ukjent målemetode – Målemetode er ukjent<br />- GPS Kodemåling, relative målinger – Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, relative målinger.<br />- GPS Kodemåling, enkeltmålinger – Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS,
GALILEO): Kodemåling, enkle målinger.</td>
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
      <td>punktstandardavviket i grunnriss for punkter<br /><br />Merknad:<br />Oppgitt i cm</td>
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
      <td><strong>kvalitet.synbarhet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvor godt den kartlagte detalj var synbar ved kartleggingen</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Synbarhet</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Fullt ut synlig/gjenfinnbar i terrenget – Default<br />- Dårlig gjenfinnbar i terreng – Forøvrig grei å innmåle. (Benyttes bl.a. for innmåling av ledninger på lukket grøft)<br />- Middels synlig i flybilde/modell<br />- Dårlig/ikke synlig i flybilde/modell</td>
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
      <td><strong>kvalitet.målemetodeHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>metode for å måle høyden</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>MålemetodeHøyde</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Terrengmålt – Målt i terrenget<br />- Tatt fra plan – Tatt fra plan eller godkjent tiltak<br />- Annet<br />- Stereoinstrument – Målt i stereoinstrument, uspesifisert instrument<br />- Analytisk plotter – Målt i stereoinstrument, analytisk plotter<br />- Digitalt stereoinstrument – Målt i stereoinstrument, digitalt instrument<br />- Flybåren laserscanning – Målt med laserskanner fra fly<br />- Genererte data (interpolasjon) – Genererte data, interpolasjonsmetode. Ikke nærmere spesifisert<br />- Generert i terrengmodell – Genererte data, interpolasjonsmetode, fra terrengmodell<br />- Målt med stigningsmåler<br />- GPS Kodemåling, relative målinger. – Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, relative målinger.<br />- GPS Kodemåling, enkeltpunktbestemmelser – Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS,
GALILEO): Kodemåling, enkle målinger.<br />- Ukjent målemetode</td>
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
      <td><strong>kvalitet.nøyaktighetHøyde</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nøyaktighet for høyden i cm</td>
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
VertikalObjektKomponent

**Assosiasjoner**
VertikalObjektKomponentLinje – rolle: avgrenserLinje – kardinalitet: 0..*

### Kodelister

#### «Enumeration» Høydereferanse

**Definisjon:** koordinatregistering utført på topp eller bunn av et objekt

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
      <td>Høyden målt til foten av objektet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Høyden målt til toppen av objektet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>benyttes ikke ved nyregistrering</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Høydereferansesystem

**Definisjon:** referanseflate som er utgangspunktet for høydekoordinat.

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
      <td>Ellipsoide jf. KOORDSYS</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Lokal referanseflate</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Geoide bestemt av NKG i 1989</td>
      <td>NKG: The Nordic Geodetic Commission - founded in 1953 - is an association of geodesists from Denmark, Finland, Iceland, Norway and Sweden. Its purpose is to give the members possibilities of fruitful gatherings and mutual exchange of professional views and experiences. The NKG is recognized and supported by a number of Nordic  organizations, such as the Director Generals of the Nordic Mapping Authorities. (Kilde: <a href="http://217.152.180.26/nkg/">http://217.152.180.26/nkg/</a>)</td>
      <td></td>
    </tr>
    <tr>
      <td>Norsk Null av 1954</td>
      <td>Denne er identisk med NN1954</td>
      <td></td>
    </tr>
    <tr>
      <td>Nord-Norsk Null av 1957</td>
      <td>For nyere data er denne gått ut av bruk. Er erstattet av NN54.</td>
      <td></td>
    </tr>
    <tr>
      <td>Norsk Null av 2000</td>
      <td>Nytt felles nordisk vertikalt datum, basert på Normaal Amsterdals Peil.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Målemetode

**Definisjon:** metode som ligger til grunn for registrering av posisjon

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
      <td>Terrengmålt</td>
      <td>Målt i terrenget</td>
      <td></td>
    </tr>
    <tr>
      <td>Tatt fra plan</td>
      <td>Tatt fra plan eller godkjent tiltak</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument</td>
      <td>Målt i stereoinstrument, uspesifisert instrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Analytisk plotter</td>
      <td>Målt i stereoinstrument, analytisk plotter</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalt stereoinstrument</td>
      <td>Målt i stereoinstrument, digitalt instrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Flybåren laserscanner</td>
      <td>Målt med laserskanner fra fly</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert fra ortofoto</td>
      <td>Geometri overført fra ortofoto ved hjelp av manuell registrering på skjerm</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert på skjerm fra satellittbilde</td>
      <td>Geometri overført fra satelittbilde ved hjelp av manuell registrering på skjerm</td>
      <td></td>
    </tr>
    <tr>
      <td>Dig. på skjerm fra scannet samkopi</td>
      <td>Geometri overført fra kart ved hjelp av manuell registrering på skjerm, medium skannet kart (raster), samkopi</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data (interpolasjon)</td>
      <td>Genererte data, interpolasjonsmetode. Ikke nærmere spesifisert</td>
      <td></td>
    </tr>
    <tr>
      <td>Frihåndstegning</td>
      <td>Digitalisert ut fra frihåndstegning.  Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalisert fra krokering på kart</td>
      <td>Digitalisert fra krokering på kart, dvs grovt skissert på kart</td>
      <td></td>
    </tr>
    <tr>
      <td>Direkte innlagt på skjerm</td>
      <td>Digitalisert ut fra frihåndstegning (direkte på skjerm). Frihåndstegning er basert på svært grovt grunnlag eller ikke noe grunnlag</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent målemetode</td>
      <td>Målemetode er ukjent</td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Kodemåling, relative målinger</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, relative målinger.</td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Kodemåling, enkeltmålinger</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS,
GALILEO): Kodemåling, enkle målinger.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Synbarhet

**Definisjon:** hvor godt den kartlagte detalj var synbar ved kartleggingen

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
      <td>Fullt ut synlig/gjenfinnbar i terrenget</td>
      <td>Default</td>
      <td></td>
    </tr>
    <tr>
      <td>Dårlig gjenfinnbar i terreng</td>
      <td>Forøvrig grei å innmåle. (Benyttes bl.a. for innmåling av ledninger på lukket grøft)</td>
      <td></td>
    </tr>
    <tr>
      <td>Middels synlig i flybilde/modell</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Dårlig/ikke synlig i flybilde/modell</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» MålemetodeHøyde

**Definisjon:** metode for å måle objekttypens høydeverdi

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
      <td>Terrengmålt</td>
      <td>Målt i terrenget</td>
      <td></td>
    </tr>
    <tr>
      <td>Tatt fra plan</td>
      <td>Tatt fra plan eller godkjent tiltak</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Stereoinstrument</td>
      <td>Målt i stereoinstrument, uspesifisert instrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Analytisk plotter</td>
      <td>Målt i stereoinstrument, analytisk plotter</td>
      <td></td>
    </tr>
    <tr>
      <td>Digitalt stereoinstrument</td>
      <td>Målt i stereoinstrument, digitalt instrument</td>
      <td></td>
    </tr>
    <tr>
      <td>Flybåren laserscanning</td>
      <td>Målt med laserskanner fra fly</td>
      <td></td>
    </tr>
    <tr>
      <td>Genererte data (interpolasjon)</td>
      <td>Genererte data, interpolasjonsmetode. Ikke nærmere spesifisert</td>
      <td></td>
    </tr>
    <tr>
      <td>Generert i terrengmodell</td>
      <td>Genererte data, interpolasjonsmetode, fra terrengmodell</td>
      <td></td>
    </tr>
    <tr>
      <td>Målt med stigningsmåler</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Kodemåling, relative målinger.</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS, GALILEO): Kodemåling, relative målinger.</td>
      <td></td>
    </tr>
    <tr>
      <td>GPS Kodemåling, enkeltpunktbestemmelser</td>
      <td>Innmålt med satellittbaserte systemer for navigasjon og
posisjonering med global dekning (f.eks GPS, GLONASS,
GALILEO): Kodemåling, enkle målinger.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent målemetode</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» TypeEndring

**Definisjon:** endringsstatus for objektet

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
      <td>Endret</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nytt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Slettet</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Status

**Definisjon:** objektets tilstand

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
      <td>Eksisterende (default)</td>
      <td>Identisk med tidligere SITSTAT = 3

-- Definition --
Identical with previous SITSTAT = 3</td>
      <td></td>
    </tr>
    <tr>
      <td>Kondemnert</td>
      <td>Ikke lenger et hinder.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ombygd</td>
      <td>Hindret er ombygd (blir vanligvis ikke brukt)</td>
      <td></td>
    </tr>
    <tr>
      <td>Planlagt</td>
      <td>Hindret skal bygges</td>
      <td></td>
    </tr>
    <tr>
      <td>Under arbeid</td>
      <td>Hinderet er under bygging/ombygging</td>
      <td></td>
    </tr>
    <tr>
      <td>Fjernet</td>
      <td>Feilregistrert i registeret, skulle aldri vært der.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» JaNei

**Definisjon:** alternativ til å bruke den generelle datatypen Boolean

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
      <td>Ja</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Nei</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» VertikalObjektType

**Definisjon:** ulike typer VertikalObjekter (luftfartshindre).

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
      <td>Landbruksutstyr</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode AG_EQUIP</td>
      <td></td>
    </tr>
    <tr>
      <td>Telemast</td>
      <td>mast med radio- og telekommunikasjonsutstyr for sending/mottak av telesignaler

tilsvarer klasse MastTele i Ledningsnett 4.0</td>
      <td></td>
    </tr>
    <tr>
      <td>Bru</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode BRIDGE</td>
      <td></td>
    </tr>
    <tr>
      <td>Bygning</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode BUILDING</td>
      <td></td>
    </tr>
    <tr>
      <td>Gondolbane</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode CABLE_CAR</td>
      <td></td>
    </tr>
    <tr>
      <td>Kontrolltårn</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode CONTROL_TOWER</td>
      <td></td>
    </tr>
    <tr>
      <td>Kjøletårn</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode COOLING_TOWER</td>
      <td></td>
    </tr>
    <tr>
      <td>Kran</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType

gjelder også heisekrantypene skinnekran/havnekran, tårnkran/byggekran, mobilkran, flytekran</td>
      <td></td>
    </tr>
    <tr>
      <td>Demning</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode DAM</td>
      <td></td>
    </tr>
    <tr>
      <td>Kuppel</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode DOME</td>
      <td></td>
    </tr>
    <tr>
      <td>EL_Nettstasjon</td>
      <td>stasjon som transformerer elektrisitet fra et høyspentnivå til et lavere

tilsvarer EL_Transformatorstasjon og EL_Nettstasjon i SOSI Ledning 4.5

Merk: Gjelder alle typer transformasjoner. I standarden for luftfartshinder skiller vi ikke mellom ulike typer transformasjoner som for eksempel transformasjon til lavere eller høyere enn 230 V slik det gjøres i SOSI Ledning 4.5.</td>
      <td></td>
    </tr>
    <tr>
      <td>Gjerde</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode FENCE</td>
      <td></td>
    </tr>
    <tr>
      <td>Fyrtårn</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType kode LIGHTHOUSE</td>
      <td></td>
    </tr>
    <tr>
      <td>Monument</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode MONUMENT</td>
      <td></td>
    </tr>
    <tr>
      <td>Terrengpunkt</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode NATURAL_HIGHPOINT</td>
      <td></td>
    </tr>
    <tr>
      <td>Navigasjonshjelpemiddel</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode NAVAID

Gjelder kun radio instrumenter som brukes ifm navigasjon for luftfartøy og ikke hjelpemidler til andre form for navigasjon, som for eksempel til sjøs.</td>
      <td></td>
    </tr>
    <tr>
      <td>Stolpe</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode POLE</td>
      <td></td>
    </tr>
    <tr>
      <td>Kraftverk</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode POWER_PLANT</td>
      <td></td>
    </tr>
    <tr>
      <td>Raffineri</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode REFINERY</td>
      <td></td>
    </tr>
    <tr>
      <td>Oljerigg</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode RIG</td>
      <td></td>
    </tr>
    <tr>
      <td>Skilt</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode SIGN</td>
      <td></td>
    </tr>
    <tr>
      <td>Pipe</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode STACK</td>
      <td></td>
    </tr>
    <tr>
      <td>Tank</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode TANK</td>
      <td></td>
    </tr>
    <tr>
      <td>Forankret ballong</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode TETHERED_BALLOON</td>
      <td></td>
    </tr>
    <tr>
      <td>Tårn</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode TOWER</td>
      <td></td>
    </tr>
    <tr>
      <td>Kraftledning</td>
      <td>linje som fører elektrisk kraft over store avstander

tilsvarer klasse LuftledningLH i SOSI Ledningsnett 4.0 og kodene "Høgspentnett" og "Lavspentnett" i kodelista Ledningsnettverkstype i SOSI Ledningsnett 4.5

tilsvarer også kode TRANSMISSION_LINE
hentet fra AIXM 5.1 klasse CodeVerticalStructureType</td>
      <td></td>
    </tr>
    <tr>
      <td>Tre</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode TREE</td>
      <td></td>
    </tr>
    <tr>
      <td>Skogsområde</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode VEGETATION

gjelder også klasse lufthavnhinderTregruppe i SOSI Lufthavn 4.1</td>
      <td></td>
    </tr>
    <tr>
      <td>Vanntårn</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode WATER_TOWER</td>
      <td></td>
    </tr>
    <tr>
      <td>Vindmølle</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode WINDMILL</td>
      <td></td>
    </tr>
    <tr>
      <td>Vindmøllepark</td>
      <td>hentet fra AIXM 5.1 klasse CodeVerticalStructureType, kode WINDMILL_FARMS</td>
      <td></td>
    </tr>
    <tr>
      <td>Hopptårn</td>
      <td>tilsvarer klasse Hoppbakke i SOSI Bygnan 4.0

ikke dommertårnet</td>
      <td></td>
    </tr>
    <tr>
      <td>Vindmåler</td>
      <td>meteorologisk instrument som måler vindhastighet og vindretning</td>
      <td></td>
    </tr>
    <tr>
      <td>Lysmast</td>
      <td>mast brukt for montering av ulike lyskilder</td>
      <td></td>
    </tr>
    <tr>
      <td>Flaggstang</td>
      <td>lang rett stang for heising av flagg

tilsvarer klasse Flaggstang i SOSI Bygnan 4.0</td>
      <td></td>
    </tr>
    <tr>
      <td>Petroleumsinnretning</td>
      <td>innretning, installasjon, anlegg og annet utstyr for petroleumsvirksomhet, likevel ikke forsynings- og hjelpefartøy eller skip som transporterer petroleum i bulk

tilsvarer klasse Petroleumsinnretning i SOSI Petroleum 4.0</td>
      <td></td>
    </tr>
    <tr>
      <td>Silo</td>
      <td>lagringsbygg for fôr og korn som ikke er registrert som bygning i GAB

tilsvarer klasse Silo i SOSI Bygnan 4.0

Merknad: I motsetning til definisjonen av klasse Silo i SOSI Bygnan 4.0 vil dette også gjelde store silobygg</td>
      <td></td>
    </tr>
    <tr>
      <td>Stolheis</td>
      <td>taubane med stoler til persontransport

tilsvarer klasse Stolheis i SOSI Bygnan 4.0</td>
      <td></td>
    </tr>
    <tr>
      <td>Skitrekk</td>
      <td>taubane til å dra skiløper opp bratte bakker

tilsvarer klasse Skitrekk i SOSI Bygnan 4.0</td>
      <td></td>
    </tr>
    <tr>
      <td>Taubane</td>
      <td>innretning hvor tau eller vaiere bærer og eller trekker last over en strekning

tilsvarer klasse Taubane i SOSI Bygnan 4.0</td>
      <td></td>
    </tr>
    <tr>
      <td>Fornøyelsesparkinnretning</td>
      <td>pariserhjul, berg og dal bane og andre høye innretninger i en fornøyelsespark</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Måleenhet

**Definisjon:** kodeliste for måleenheter.

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
      <td>FT</td>
      <td>foot</td>
      <td></td>
    </tr>
    <tr>
      <td>M</td>
      <td>meter</td>
      <td></td>
    </tr>
    <tr>
      <td>CM</td>
      <td>centimeter</td>
      <td></td>
    </tr>
    <tr>
      <td>KM</td>
      <td>kilometer</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Farge

**Definisjon:** kodeliste for merkingens farge. Består hovedsakelig av farger fra Vedlegg 1 til BSL E 2-1. I tillegg er det inkludert en del koder fra gammelt NRL-system.

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
      <td>Svovelgul</td>
      <td>RAL 1016 (Sulfur yellow)</td>
      <td></td>
    </tr>
    <tr>
      <td>Trafikkrød</td>
      <td>RAL 3020 (Traffic red)</td>
      <td></td>
    </tr>
    <tr>
      <td>Lysende rød</td>
      <td>RAL 3024 (Luminous red)</td>
      <td></td>
    </tr>
    <tr>
      <td>Lys grå</td>
      <td>RAL 7035 (Light grey)</td>
      <td></td>
    </tr>
    <tr>
      <td>Agatgrå</td>
      <td>RAL 7038 (Agate grey)</td>
      <td></td>
    </tr>
    <tr>
      <td>Signalhvit</td>
      <td>RAL 9003 (Signal white)</td>
      <td></td>
    </tr>
    <tr>
      <td>Ren hvit</td>
      <td>RAL 9010 (Pure white)</td>
      <td></td>
    </tr>
    <tr>
      <td>Trafikkhvit</td>
      <td>RAL 9016 (Traffic white)</td>
      <td></td>
    </tr>
    <tr>
      <td>Oransje</td>
      <td>RAL kode ikke aktuelt, kode er videreført fra gammelt system</td>
      <td></td>
    </tr>
    <tr>
      <td>Rødt</td>
      <td>RAL kode ikke aktuelt, kode er videreført fra gammelt system</td>
      <td></td>
    </tr>
    <tr>
      <td>Hvitt</td>
      <td>RAL kode ikke aktuelt, kode er videreført fra gammelt system</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» MerkingType

**Definisjon:** ulike typer merking spesifiseres her

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
      <td>Flagg</td>
      <td>kan være ensfarget eller mønstret.</td>
      <td></td>
    </tr>
    <tr>
      <td>Markør</td>
      <td>gjelder også blåser</td>
      <td></td>
    </tr>
    <tr>
      <td>Plater</td>
      <td>Objektet er merket med fargede plater</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Merketypen er ukjent</td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td>hvis valgt, kreves utfylling av feltet kommentarMerkingType</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» MerkingMønster

**Definisjon:** ulike mønstertyper for merking.

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
      <td>Ensfarget</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Rutemønstret</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Horisontale bånd</td>
      <td>to-fargete alternerende horisontale bånd</td>
      <td></td>
    </tr>
    <tr>
      <td>Vertikale bånd</td>
      <td>to-fargete alternerende vertikale bånd</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Annet</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» MerkingTilstand

**Definisjon:** Angivelse av merkingens tilstand.

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
      <td>Dårlig</td>
      <td>Merkingen er vanskelig å se.</td>
      <td></td>
    </tr>
    <tr>
      <td>Brukbar</td>
      <td>Merkingen er mulig å se, men utydelig.</td>
      <td></td>
    </tr>
    <tr>
      <td>God</td>
      <td>Merkingen er godt synlig.</td>
      <td></td>
    </tr>
    <tr>
      <td>Veldig god</td>
      <td>Merkingen er meget godt synlig.</td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>Tilstanden til merking er ukjent.</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» RegelverkMerkeplikt

**Definisjon:** hinder er merkepliktig i henhold til

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
      <td>BSL E 2</td>
      <td>Merket i henhold til forskrift om Bestemmelser for sivil luftfart nr 2.</td>
      <td></td>
    </tr>
    <tr>
      <td>BSL E 3</td>
      <td>Merket i henhold til forskrift om Bestemmelser for sivil luftfart nr 3.</td>
      <td></td>
    </tr>
    <tr>
      <td>Pålagt av LT</td>
      <td>merking pålagt spesifikt av Luftfartstilsynet</td>
      <td></td>
    </tr>
    <tr>
      <td>BSL E 2 aggregerte komponenter</td>
      <td>enkeltelementer er ikke merkepliktige i utgangspunktet, men de er merkepliktige hvis de oppfyller visse krav når de er sett som helhet</td>
      <td></td>
    </tr>
    <tr>
      <td>EASA</td>
      <td>Merket i henhold til bestemmelser fra EASA</td>
      <td></td>
    </tr>
    <tr>
      <td>ICAO</td>
      <td>Merket i henhold til bestemmelser fra ICAO</td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» AnsvarligForMerking

**Definisjon:** hvem har ansvar for merking

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
      <td>Eier av hinder</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Godkjenningsansvarlig for landingsplass-flyplass</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» MerkeInformasjon

**Definisjon:** utdypende informasjon om merking

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
      <td>merket i henhold til forskrift</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>merket i henhold til dispensasjon</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>merket utover aktuell forskrift</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>mangler merking</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>ukjent</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### «Enumeration» Lystype

**Definisjon:** hinderlys til bruk ved merking av luftfartshinder i henhold til vedlegg til forskrift om rapportering, registrering og merking av luftfartshinder, BSL E 2-1. &lt;font color="#0f0f0f"&gt;I tillegg er det mulig å velge koder fra gammel NRL&lt;/font&gt;

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
      <td>Lavintensitet type A</td>
      <td>rødt, fast, 10 candela</td>
      <td></td>
    </tr>
    <tr>
      <td>Lavintensitet type B</td>
      <td>rødt, fast, 32 candela</td>
      <td></td>
    </tr>
    <tr>
      <td>Lavintensitet type C</td>
      <td>ikke del av oversikten i vedlegg 2 BSL E 2-1, men tatt fra tabell 6-3 i ICAO annex 14</td>
      <td></td>
    </tr>
    <tr>
      <td>Lavintensitet type D</td>
      <td>ikke del av oversikten i vedlegg 2 BSL E 2-1, men tatt fra tabell 6-3 i ICAO annex 14</td>
      <td></td>
    </tr>
    <tr>
      <td>Mellomintensitet type A</td>
      <td>hvitt, blinkende, 20 000 candela ved bakgrunnsbelysning 50 cd/m ² og over, 2000 candela med bakgrunnsbelysning uneder 50 cd/m ²</td>
      <td></td>
    </tr>
    <tr>
      <td>Mellomintensitet type B</td>
      <td>rødt, blinkende, 2000 candela</td>
      <td></td>
    </tr>
    <tr>
      <td>Mellomintensitet type C</td>
      <td>rødt, fast, 2000 candela</td>
      <td></td>
    </tr>
    <tr>
      <td>Høyintensitet type A</td>
      <td>hvitt, blinkende, 200 000 candela ved bakgrunnsbelysning over 500 cd/m², 20 000 candela ved bakgrunnsbelysning 50-500 cd/m² og 2000 candela ved bakgrunnsbelysning under 50 cd/m²</td>
      <td></td>
    </tr>
    <tr>
      <td>Høyintensitet type B</td>
      <td>hvitt, blinkende, 100 000 candela ved bakgrunnsbelysning over 500 cd/m², 20 000 candela ved bakgrunnsbelysning 50-500 cd/m² og 2000 candela ved bakgrunnsbelysning under 50 cd/m²</td>
      <td></td>
    </tr>
    <tr>
      <td>Belyst med flomlys</td>
      <td>objektet er opplys av lyskastere for å være synlig for luftfarten</td>
      <td></td>
    </tr>
    <tr>
      <td>Fast rødt</td>
      <td>brukes dersom vi ikke vet lysstyrke, men har observert lysfarge rød fast lys</td>
      <td></td>
    </tr>
    <tr>
      <td>Fast hvitt</td>
      <td>brukes dersom vi ikke vet lysstyrke, men har observert lysfarge hvit fast lys</td>
      <td></td>
    </tr>
    <tr>
      <td>Blinkende hvitt</td>
      <td>brukes dersom vi ikke vet lysstyrke, men har observert lysfarge hvitt blinkende lys</td>
      <td></td>
    </tr>
    <tr>
      <td>Blinkende rødt</td>
      <td>brukes dersom vi ikke vet lysstyrke, men har observert lysfarge rødt blinkende lys</td>
      <td></td>
    </tr>
    <tr>
      <td>Lyssatt</td>
      <td>brukes dersom man vet at hinderet har lys, men ikke vet farge og type</td>
      <td></td>
    </tr>
    <tr>
      <td>Ikke lyssatt</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Ukjent</td>
      <td>benyttes dersom det er ukjent om hinderet har lys eller ikke.</td>
      <td></td>
    </tr>
  </tbody>
</table>
