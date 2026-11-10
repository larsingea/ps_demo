#### Dataavgrensning

Generell avgrensningslinje, f.eks. mellom datasett med ulik kvalitet, innhold eller detaljering

Geometri:<br />Elementtype: feature<br />Type: geometry-linestring<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-linestring</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### Dekningsområde

Dekningskart for løsmasse detaljert

Geometri:<br />Elementtype: feature<br />Type: geometry-polygon<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-polygon</td>
      <td></td>
    </tr>
    <tr>
      <td>lokalid</td>
      <td>lokalid<br />OGC-rolle: id</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objekttype</td>
      <td>objekttype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database Merknad: Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Tidspunkt for siste endring på objektet Merknad: Oppdateringsdato kan være forskjellig fra datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt Merknad: Det er dataleverendørens ansvar  å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI. Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br />Merknad: Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans).</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>informasjon</td>
      <td>Generell opplysning. Merknad: mulighet til å legge inn utfyllende informasjon om objektet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datasettid</td>
      <td>datasettid</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datasettnavn</td>
      <td>datasettnavn</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>doktema</td>
      <td>doktema</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>dataeier</td>
      <td>Rettighetshaver til datasettet/tjenesten</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>dekningsstatus</td>
      <td>dekningsstatus</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>dekningsinfo</td>
      <td>Utfyllende informasjon om fullstendighet</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>link</td>
      <td>Referanse til et informasjonselement, enten lokalt eller globalt</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### FiktivDelelinje

Linje for å dele opp store flateobjekter<br />Merknad:<br />En del produktspesifikasjoner benytter spesifikke fiktive delelinjer.

Geometri:<br />Elementtype: feature<br />Type: geometry-linestring<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-linestring</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### Kartbladkant

Avgrensningslinje for et kart som dekker et nærmere angitt geografisk område, ofte basert på en offentlig kartbladinndeling

Geometri:<br />Elementtype: feature<br />Type: geometry-linestring<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-linestring</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>karttype</td>
      <td>Type kartbladinndeling</td>
      <td><a href="#kodeliste-karttype">Karttype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### LøsmasseAndrePkt

Diverse kvartærgeologiske punkter

Geometri:<br />Elementtype: feature<br />Type: geometry-point<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-point</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>andre<wbr />Kv<wbr />Symbol</td>
      <td>Kvartærgeologiske symboler som ikke er formelementer</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Horisontalverdi</td>
      <td>Verdi på måling i horisontalplanet (0-360°). Angir stupretning for linjestrukturer og strøkretning (i henhold til høyrehåndsregelen) for planstrukturer.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### LøsmasseFlate

Areal bestående av en løsmassetype (jordart)

Geometri:<br />Elementtype: feature<br />Type: geometry-polygon<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-polygon</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Bjektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>løsmassetype</td>
      <td>Kvartærgeologiske løsmassetyper (jordartstyper)</td>
      <td>string</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>løsmassetype<wbr />Navn</td>
      <td>Kvartærgeologiske løsmassetyper (jordartstyper)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>løsmassetype<wbr />Besk</td>
      <td>Kvartærgeologiske løsmassetyper (jordartstyper)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>infiltrasjon<wbr />Potensial</td>
      <td>Løsmassenes egenskaper til å infiltrere og rense avløpsvann</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>infiltrasjon<wbr />Potensial<wbr />Navn</td>
      <td>Løsmassenes egenskaper til å infiltrere og rense avløpsvann</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>infiltrasjon<wbr />Potensial<wbr />Besk</td>
      <td>Løsmassenes egenskaper til å infiltrere og rense avløpsvann</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>grunnvann<wbr />Potensial</td>
      <td>Løsmassenes potensial til å inneholde grunnvannsressurser</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>grunnvann<wbr />Potensial<wbr />Navn</td>
      <td>Løsmassenes potensial til å inneholde grunnvannsressurser</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>grunnvann<wbr />Potensial<wbr />Besk</td>
      <td>Løsmassenes potensial til å inneholde grunnvannsressurser</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Temajustering</td>
      <td>Justering/endring av en automatisk klassifikasjon av geologisk tema</td>
      <td><a href="#kodeliste-geoltemajustering">Geol<wbr />Temajustering</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### LøsmasseGrense

Avgrensning av ulike typer løsmasser (jordarter)

Geometri:<br />Elementtype: feature<br />Type: geometry-linestring<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-linestring</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>løsmasse<wbr />Avvik<wbr />Kartdata</td>
      <td>Beskriver avvik fra forventet kvalitet i kvartærgeologiske kart innenfor den kartlagte målestokken. Denne egenskapen gir veiledning om hvilke kartdata som skal brukes med varsomhet og sammn med tilleggsinformasjon fra andre datakilder.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### LøsmasseKornstørrelsePkt

Punkter som beskriver kornstørrelse i området som de er plassert innenfor. Punktene har ikke en absolutt plassering, men er kartografisk plassert i det området som beskrives.

Geometri:<br />Elementtype: feature<br />Type: geometry-point<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-point</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>andre<wbr />Kv<wbr />Symbol</td>
      <td>Kvartærgeologiske symboler som ikke er formelementer</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### LøsmasseMarinGrensePkt

Punktobservasjon for marin grense

Geometri:<br />Elementtype: feature<br />Type: geometry-point<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-point</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>marin<wbr />Grense<wbr />Reg<wbr />Type</td>
      <td>Høyeste havnivå etter siste istid</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>marin<wbr />Grense<wbr />Type</td>
      <td>Type avsetning eller landskapsform registreringen er basert på</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>inkl<wbr />Modellering</td>
      <td>Definerer om marin grense-observasjonen er inkludert (Ja) eller ikke (Nei) i modellering av marin grense og tidligere havdekte områder. Ekskludering av marin grense-observasjoner er basert på en regionalgeologisk vurdering.</td>
      <td>boolean</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>høyde</td>
      <td>Et punkts vertikale avstand over en fysisk eller matematisk definert referanseflate [H]</td>
      <td>integer</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>navn</td>
      <td>Ord som noen eller noe kalles ved</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### LøsmasseOverflateEgenskapPkt

Punkter som beskriver overflatens karakter i området som de er plassert innenfor. Punktene har ikke en absolutt plassering, men er kartografisk plassert i det området som beskrives.

Geometri:<br />Elementtype: feature<br />Type: geometry-point<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-point</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>andre<wbr />Kv<wbr />Symbol</td>
      <td>Kvartærgeologiske symboler som ikke er formelementer</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### LøsmasseOverflateformLinje

Observert overflateform med lineær utstrekning<br />Eksempel: Terrassekant, vifte, haug, rygg

Geometri:<br />Elementtype: feature<br />Type: geometry-linestring<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-linestring</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kv<wbr />Form<wbr />Linjetype</td>
      <td>Kvartærgeologiske formelementlinjer</td>
      <td>string</td>
      <td>1..1</td>
    </tr>
  </tbody>
</table>

#### LøsmasseOverflateformPkt

Punktobservasjon av overflateform i løsmassene<br />Eksempel: Dødisgrop, haug

Geometri:<br />Elementtype: feature<br />Type: geometry-point<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-point</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kv<wbr />Form<wbr />Punkttype</td>
      <td>Kvartærgeologiske formelementpunkter</td>
      <td>string</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>løsmassetype</td>
      <td>Kvartærgeologiske løsmassetyper (jordartstyper)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Horisontalverdi</td>
      <td>Verdi på måling i horisontalplanet (0-360°). Angir stupretning for linjestrukturer og strøkretning (i henhold til høyrehåndsregelen) for planstrukturer.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### LøsmasseTypePkt

Små løsmasseavsetninger. Lokalitet for angivelse av løsmassetype som<br />Symbol der utbredelsen er for liten til å registrere den som areal med hensyn til målestokken det er kartlagt i.

Geometri:<br />Elementtype: feature<br />Type: geometry-point<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-point</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>løsmassetype</td>
      <td>Kvartærgeologiske løsmassetyper (jordartstyper)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

#### StratigrafiPkt

Lokalitet hvor det er gitt informasjon om sedimenters stratigrafi og kornstørrelse

Geometri:<br />Elementtype: feature<br />Type: geometry-point<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs<br />• <a href="http://www.opengis.net/def/crs/OGC/1.3/CRS84">http://www.opengis.net/def/crs/OGC/1.3/CRS84</a>

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-point</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>stratigrafi<wbr />Info</td>
      <td>Kodet informasjon om mektighet og lagfølge i strategrafipunktet merket x<br />Eks:<br />X  3      - den kartlagte avsetning er 3 m mektig<br />x  &gt;2    - mektigheten til den kartlagte avsetningen er større enn 2 m<br />x  1S/3SG/Fj   - den kartlagte avsetningenbestår av 1 m sand, under er det 3 m sandig grus over fjell<br />X  2/5B/&gt;1M  - den kartlagte avsetningen er 2 m mektig, under er det en 5 m mektig breelvavsetning over morenemateriale som er mer enn 1 m mektig</td>
      <td>string</td>
      <td>1..1</td>
    </tr>
  </tbody>
</table>

#### Temakartavgrensning

Avgrensningslinje for et temakart

Geometri:<br />Elementtype: feature<br />Type: geometry-linestring<br />Lagrings-CRS:<br />• <a href="http://www.opengis.net/def/crs/EPSG/0/25833">http://www.opengis.net/def/crs/EPSG/0/25833</a><br />Koordinatreferansesystem (crs):<br />• #/crs

Egenskaper

<table class="feature-attribute-table">
  <thead>
    <tr>
      <th>Egenskap</th>
      <th>Beskrivelse</th>
      <th>Type</th>
      <th>Multiplisitet</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>Elementtype: feature<br />OGC-rolle: primary-geometry</td>
      <td>geometry-linestring</td>
      <td></td>
    </tr>
    <tr>
      <td>objid</td>
      <td>objid<br />OGC-rolle: id</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>objtype</td>
      <td>objtype</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>identifikasjon</td>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt.</td>
      <td>Identifikasjon<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- lokal<wbr />Id</td>
      <td>Lokal identifikator av et objekt<br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- navnerom</td>
      <td>Navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- versjon<wbr />Id</td>
      <td>Identifikasjon av en spesiell versjon av et geografisk objekt (instans)</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>første<wbr />Digitaliseringsdato</td>
      <td>Dato når en representasjon av objektet i digital form første gang ble etablert<br />Merknad:<br />FørsteDigitaliseringsdato kan skille seg fra førsteDatafangstdato ved at den første datafangsten skjedde analogt og gjort om til digital form senere i en produksjonsprosess.<br />Eventuelt at innlegging i databasen skjedde på et senere tidspunkt enn registreringen /observasjonen / målingen av objektet.<br />OGC-rolle: primary-instant</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>oppdateringsdato</td>
      <td>Dato for siste endring på objektetdataene<br />Merknad:<br />Oppdateringsdato kan være forskjellig fra Datafangsdato ved at data som er registrert kan bufres en kortere eller lengre periode før disse legges inn i datasystemet (databasen).<br />-Definition-<br />Date and time at which this version of the spatial object was inserted or changed in the spatial data set.</td>
      <td>date (string)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>datauttaksdato</td>
      <td>Dato for uttak fra en database<br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase.</td>
      <td>date (string)</td>
      <td>1..1</td>
    </tr>
    <tr>
      <td>temakvalitet</td>
      <td>Kvaliteten på registrering/kartlegging av tema sett i forhold til faktiske forhold i naturen. Ulik tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets økonomi. Med nøyaktighet i denne sammenheng menes hvor korrekt registreringen avspeiler objektets posisjon i naturen og presisjonen i valg av tematisk innhold i forhold til generalisering<br /><br />Merknad: Tematisk oppløsning/generaliseringsgrad kan være styrt av temaets samfunnsmessige betydning, områdets arealmessige betydning eller prosjektets målsetning</td>
      <td><a href="#kodeliste-temakvalitet">Temakvalitet</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>egnet<wbr />Målestokk</td>
      <td>Beskriver det målestokksområdet hvor dataene er best egnet. Egenskapen viser målestokktallet, eksempel: 1:50 000 = 50000.<br />Objekter kan være utvalgt, plassert eller generalisert i forhold til egnet målestokk.<br />Denne egenskapen kan benyttes for å velge hvilke objekter som skal tegnes ut i ulike målestokker.</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td><a href="#kodeliste-geolpåvisningstype">Geol<wbr />Påvisningstype</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>geol<wbr />Påvisningstype<wbr />Navn</td>
      <td>Hvor sikkert et geologisk objekt er påvist i terrenget, eller hvilken metode som ligger til grunn for å påvisningen/registreringen<br />-- Definition -- with what certainty a geological object has been identified in the terrain, or on which method the identification/registration is based</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>opphav</td>
      <td>Referanse til opphavsmaterialet, kildematerialet, organisasjons/publiseringskilde<br /><br />Merknad:<br />Kan også beskrive navn på person og årsak til oppdatering</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>kvalitet</td>
      <td>Beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI.</td>
      <td>Posisjonskvalitet<br />(datatype)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- målemetode<wbr />Navn</td>
      <td>Metode for måling i grunnriss (x,y), og høyde (z) når metoden er den samme som ved måling i grunnriss</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>- nøyaktighet</td>
      <td>Punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br />Merknad:<br />Oppgitt i cm</td>
      <td>integer</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td><a href="#kodeliste-medium">Medium</a><br />(enumerering)</td>
      <td>0..1</td>
    </tr>
    <tr>
      <td>medium<wbr />Navn</td>
      <td>Objektets beliggenhet i forhold til jordoverflaten<br />Eksempel:<br />På bro, i tunnel, inne i et bygningsmessig anlegg, etc.</td>
      <td>string</td>
      <td>0..1</td>
    </tr>
  </tbody>
</table>

### Kodelister

#### <a id="kodeliste-temakvalitet"></a>«Enumeration» Temakvalitet

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
      <td>dårlig</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>god</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>megetGod</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>noeDårlig</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>noksåGod</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>særdelesGod</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### <a id="kodeliste-geolpåvisningstype"></a>«Enumeration» GeolPåvisningstype

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
      <td></td>
      <td></td>
      <td>0</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>1</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>10</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>11</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>12</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>13</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>14</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>2</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>21</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>22</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>23</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>24</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>25</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>26</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>27</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>28</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>29</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>3</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>30</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>31</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>32</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>33</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>4</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>5</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>6</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>7</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>8</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
      <td>9</td>
    </tr>
  </tbody>
</table>

#### <a id="kodeliste-medium"></a>«Enumeration» Medium

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
      <td>alltidIVann</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>iBygning</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>iLuft</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>påIsbre</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>påSjøbunnen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>påTerrenget</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>påVannoverflaten</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>tidvisUnderVann</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>ukjent</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>underIsbre</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>underSjøbunnen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>underTerrenget</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### <a id="kodeliste-karttype"></a>«Enumeration» Karttype

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
      <td>Norge250000ngo1948</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Norge250000utm</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>lokaltNettAsker</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>lokaltNettBergen_Askøy</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>lokaltNettBodø</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>lokaltNettBærum</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>lokaltNettDrammen</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>lokaltNettKristiansund</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>lokaltNettLillehammer</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>lokaltNettOslo</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>lokaltNettTrondheim</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>lokaltNettÅlesund</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>m711euref89</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>m711ngo1948</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>møre56A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>møre56B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>møre64A</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>møre64B</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>turkart50000euref89</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>øk10000euref89</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>øk1000euref89</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>øk1000ngo1948</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>øk20000euref89</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>øk2000euref89</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>øk5000euref89</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>øk5000ngo1948</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>øk500euref89</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>øk500ngo1948</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

#### <a id="kodeliste-geoltemajustering"></a>«Enumeration» GeolTemajustering

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
      <td>ikkeJustertTema</td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>justertTema</td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
