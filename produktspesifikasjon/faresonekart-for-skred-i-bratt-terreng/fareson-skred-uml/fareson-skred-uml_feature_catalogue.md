#### Påvirkningsområde

området som kan generere skred inn mot kartleggingsområdet/analyseområdet.<br /><br />English definition:<br />The area that may generate avalanches and/or landslides toward the mapping area/analysis area

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>utførende</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>selskapet eller organisasjonen som har gjennomført utredningen, det vil si skrevet rapporten og gjort vurderingene av naturfare<br /><br />English definition:<br />The company or organization that has carried out the assessment, i.e., prepared the report and conducted the evaluations of natural hazards</td>
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
      <td><strong>rapportURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>URL-lenke til rapport som dokumenterer utredningen av skredfare<br /><br />English definition:<br />URL link to the report documenting the avalanche hazard assessment</td>
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
      <td><strong>geometri</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Registreres geometri</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Surface</td>
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
      <td><strong>påvirkningsområdeID</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>identifikasjon påvirkningsområde<br /><br />English definition<br />Påvirkningsområde identification</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
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
      <td><strong>påvirkningsområdeID.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator av et objekt<br /><br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.<br />Her benyttes UUID som lokalId</td>
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
      <td><strong>påvirkningsområdeID.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br /><br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
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

Relasjoner

**Arv**
FellesegenskaperFaresonekartForSkredIbrattTerreng

#### Skredfaresone

Område med reell skredfare, for angitt skredsannsynlighet og skredtype<br /><br />English definition:<br />An area with actual avalanche and landslide hazard, defined by a specified avalanche/landslide probability and type

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>skredtype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilke skredmasser som er forbundet med skredfaren eller skredhendelsen<br />Merknad: Ulike typer skredmasser som bl.a. stein, snø, fjell, jord og kombinasjoner av disse<br /><br />English definition:<br />Specifies the type of avalanche and/or landslide material associated with the hazard or avalanche event.<br />Note: Different types of avalanche material may include rock, snow, bedrock, soil, or combinations of these</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>SkredtypeDetaljert</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/skredtypedetaljert">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/skredtypedetaljert</a></td>
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
      <td><strong>skredSannsynlighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>statistisk sannsynlighet for at det går et skred i området pr år<br /><br />English definition:<br />The statistical probability of an avalanche occurring in the area per year</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>SkredSannsynlighetBrattTerreng</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/skredsannsynlighetbrattterreng">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/skredsannsynlighetbrattterreng</a></td>
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
      <td><strong>skredfaresoneID</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>skredfaresone identifikasjon<br /><br />English definition:<br />Avalanche and landslide hazard zone identification</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
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
      <td><strong>skredfaresoneID.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator av et objekt<br /><br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.<br />Her benyttes UUID som lokalId</td>
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
      <td><strong>skredfaresoneID.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br /><br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
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
      <td><strong>analyseområdeNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>løpenummer for analyseområdene. Unikt nummer for analyseområdene innenfor de enkelte faretemaene<br /><br />English definition:<br />A sequential number assigned to the analysed areas. This is a unique identifier for each analysis area within the respective hazard themes</td>
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
      <td><strong>geometri</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>registreres geometri</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Surface</td>
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
      <td><strong>hensynTilSkog</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir om skredfaresonen er kartlagt med hensyn til skogens beskyttende effekt mot skredfare.<br />“Ja” betyr at skogens effekt på skredfaren er vurdert slik den var på tidspunktet for kartleggingen.<br />“Nei” betyr at skredfaresonen er kartlagt uten å ta hensyn til skogens effekt.<br /><br />English definition:<br />Indicates whether the avalanche hazard zone has been mapped with consideration of the forest’s protective effect on avalanche hazard.<br />“Yes” means the zone was mapped taking into account the forest’s effect as it was at the time of mapping.<br />“No” means the forest’s effect was not considered in the hazard mapping</td>
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
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/janei">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/janei</a></td>
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
      <td>beskrivelse av kvaliteten på stedfestingen<br />Merknad: Denne er identisk med ..KVALITET i tidligere versjoner av SOSI</td>
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
      <td>metode som ligger til grunn for registrering av posisjon. Kodelista er en utvidelse fra SOSI 5.1 med koden fagligSkjønnstegningPåSkjerm</td>
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
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/malemetode">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/malemetode</a></td>
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
      <td>punktstandardavviket i grunnriss for punkter samt tverravvik for linjer<br /><br />Merknad: Oppgitt i cm</td>
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
FellesegenskaperFaresonekartForSkredIbrattTerreng

#### Analyseområde

området hvor den reelle skredfaren har blitt avklart. Dette kan for eksempel være en eller flere tomter, et område avgrenset av en reguleringsplan eller annet område gitt av oppdragsgiver<br /><br />English definition:<br />The area where the actual avalanche hazard has been clarified. This may, for example, include one or more plots, an area defined by a zoning plan, or another area specified by the client

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>analyseområdeNummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>løpenummer for analyseområdene. Unikt nummer for analyseområdene innenfor de enkelte faretemaene<br /><br />English definition:<br />A sequential number assigned to the analysed areas. This is a unique identifier for each analysis area within the respective hazard themes</td>
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
      <td><strong>oppdragsgiver</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>den som har bestilt utredningen<br />Merknad:<br />Oppdragsgiveren kan være en privatperson, en bedrift, en organisasjon, en kommune, et annet offentlig organ eller staten<br /><br />English definition:<br />The entity that has commissioned the assessment.<br />Note: The client may be a private individual, a company, an organization, a municipality, another public body, or the state</td>
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
      <td><strong>utførende</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>selskapet eller organisasjonen som har gjennomført utredningen, det vil si skrevet rapporten og gjort vurderingene av naturfare<br /><br />English definition:<br />The company or organization that has carried out the assessment, i.e., prepared the report and conducted the evaluations of natural hazards</td>
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
      <td><strong>uavhengigKvalitetssikring</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir om rapporten har gjennomgått en uavhengig kvalitetssikring (UKS). 'Ja' indikerer at uavhengig kvalitetssikring er utført, mens 'Nei' indikerer at det ikke er utført. En uavhengig kvalitetssikring av leveransen sjekker om utredningen følger metodikken i NVEs veiledere for utredning av sikkerhet mot skred i bratt terreng, kvikkleireskred eller flom. Kontrollen utføres av et annet foretak enn det som har utført fareutredningen<br /><br />English definition:<br />Indicates whether the report has undergone independent quality assurance. "Yes" means that independent quality assurance has been conducted, while "No" means it has not. An independent quality assurance of the deliverable verifies whether the assessment follows the methodology outlined in NVE’s guidelines for evaluating safety against avalanches in steep terrain, quick clay landslides, or floods. The review is carried out by a different entity than the one that performed the hazard assessment</td>
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
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/janei">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/janei</a></td>
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
      <td><strong>prosjekttype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir for hvilket formål skredfaren opprinnelig ble utredet for<br /><br />English definition:<br />Indicates the original purpose for which the avalanche hazard was assessed</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Prosjekttype</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/prosjekttype">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/prosjekttype</a></td>
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
      <td><strong>vurdertSkredSannsynlighet</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Lister opp hvilke sannsynligheter som analyseområdet er utredet for, med komma som separator. Det kan være utredet for sannsynligheter som ikke vises som faresone i analyseområdet, hvis utredningen viser at det ikke er en skredfare med en slik sannsynlighet til stede.<br />Eksempel: «≥ 1/100», “≥ 1/100, ≥ 1/1000” eller "≥ 1/100, ≥ 1/1000, ≥ 1/5000"<br /><br />English definition:<br />Lists the probabilities for which the analysis area has been assessed, separated by commas.<br />The area may have been assessed for probabilities that are not represented as hazard zones within the analysis area, if the assessment concludes that no avalanche hazard is present at that probability level.<br />Example: «≥ 1/100», “≥ 1/100, ≥ 1/1000” eller "≥ 1/100, ≥ 1/1000, ≥ 1/5000"</td>
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
      <td><strong>rapportnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>tittel på rapporten<br /><br />English definition:<br />Name of report</td>
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
      <td><strong>rapportURL</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>URL-lenke til rapport som dokumenterer utredningen av skredfare<br /><br />English definition:<br />URL link to the report documenting the avalanche hazard assessment</td>
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
      <td><strong>geometri</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>registreres geometri</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Surface</td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FellesegenskaperFaresonekartForSkredIbrattTerreng

#### FellesegenskaperFaresonekartForSkredIbrattTerreng (abstrakt)

abstrakt objekt som bærer fellesegenskaper

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>kommunenavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på kommune<br />Merknad: Her angis den kommune som utgjør det største arealet<br /><br />English definition:<br />Name of municipality</td>
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
      <td><strong>kommunenummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummerering av kommunen i henhold til Statistisk sentralbyrå sin offisielle liste Merknad: Det presiseres at kommune alltid skal ha 4 siffer, dvs. eventuelt med ledende null. Kommune benyttes for kopling mot en rekke andre registre som også benytter 4 siffer<br />Merknad: Her angis den kommune som utgjør det største arealet<br /><br />English definition:<br />Numbering of municipalities according to Statistics Norway’s official list.<br />Note: The municipality number must always consist of four digits, including leading zeros if necessary. Municipality numbers are used for linking to various other registers that also use four-digit codes</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Kommunenummer</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer">https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer</a></td>
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
      <td><strong>fylkesnavn</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navn på fylke<br />Merknad: Her angis det fylket som utgjør det største arealet<br /><br />English definition:<br />Name of county</td>
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
      <td><strong>fylkesnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummerering av fylker i henhold til Statistisk sentralbyrå sin offisielle liste<br />Merknad: Det presiseres at fylkesnummer alltid skal ha 2 sifre, dvs. eventuelt med ledende null. Fylkesnummer benyttes for kopling mot en rekke andre registre som også benytter 2 sifre<br />Merknad: Her angis det fylket som utgjør det største arealet<br /><br />English definition:<br />Numbering of counties according to Statistics Norway’s official list.<br />Note: The county number must always consist of two digits, including a leading zero if necessary. County numbers are used for linking to various other registers that also use two-digit codes</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Fylkesnummer</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/fylkesnummer">https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/fylkesnummer</a></td>
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
      <td>dato for siste endring på objekt-dataene<br /><br />English definition:<br />The date of the most recent change to the object data</td>
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
      <td><strong>publiseringsdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for da rapport og digitale kartdata ble lagt til i det nasjonale DOK-datasettet for kartlegging av skredfare i bratt terreng<br /><br />English definition:<br />The date when the report and digital map data were added to the national DOK dataset for mapping avalanche and landslide hazards in steep terrain</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td><strong>rapportdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato som utførende selskap eller organisasjonen har satt på rapporten for å angi når rapporten ble ferdig utført, eventuelt hvis oppdragsgiver har brukt egen rapportmal med egen rapportdato, så har denne datoen blitt brukt<br /><br />English definition:<br />The date assigned to the report by the executing company or organization to indicate when the report was completed. If the client has used their own report template with a specific report date, that date has been used instead</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>0..1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Date</td>
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
      <td><strong>rapportnummer</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>nummer som utførende selskap eller organisasjon har brukt på rapporten, eventuelt hvis oppdragsgiver har brukt egen rapportmal så har det blitt lagt inn det rapportnummeret som oppdragsgiveren har brukt<br /><br />English definition:<br />The number assigned to the report by the executing company or organization. If the client has used their own report template, the report number specified by the client has been entered instead</td>
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
      <td><strong>analyseområdeID</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>Unik identifikasjon av et objekt i et datasett, forvaltet av den ansvarlige produsent/forvalter, og kan benyttes av eksterne applikasjoner som stabil referanse til objektet.<br /><br />Merknad 1: Denne objektidentifikasjonen må ikke forveksles med en tematisk objektidentifikasjon, slik som f.eks bygningsnummer.<br /><br />Merknad 2: Denne unike identifikatoren vil ikke endres i løpet av objektets levetid, og ikke gjenbrukes i andre objekt</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
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
      <td><strong>analyseområdeID.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator av et objekt<br /><br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.<br />Her benyttes UUID som lokalId</td>
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
      <td><strong>analyseområdeID.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br /><br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
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
      <td><strong>datauttaksdato</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>dato for uttak fra en database<br /><br />Merknad:<br />Skiller seg fra Kopidato ved at en ikke skiller på om det er uttak fra en originaldatabase eller en kopidatabase</td>
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

#### Skreddimensjonerende

Punkt som visuelt angir den dimensjonerende skredtypen for en faresone eller del av faresone. En eller flere skredtyper kan være dimensjonerende i samme område<br /><br />English definition:<br />A point that visually indicates the dimensioning avalanche/landslide type for a hazard zone or part of a hazard zone. One or more avalanche/landslide types may be dimensioning in the same area

Egenskaper

<table class="feature-attribute-table">
  <colgroup>
    <col style="width: 35%;" />
    <col style="width: 65%;" />
  </colgroup>
  <tbody>
    <tr>
      <th scope="row">Navn:</th>
      <td><strong>skreddimensjonerendeID</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>skreddimensjonerende identifikasjon<br /><br /><br />-- Definition --<br />Skreddimensjonerende identification</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>Identifikasjon</td>
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
      <td><strong>skreddimensjonerendeID.lokalId</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>lokal identifikator av et objekt<br /><br />Merknad: Det er dataleverendørens ansvar å sørge for at den lokale identifikatoren er unik innenfor navnerommet.<br />Her benyttes UUID som lokalId</td>
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
      <td><strong>skreddimensjonerendeID.navnerom</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>navnerom som unikt identifiserer datakilden til et objekt, anbefales å være en http-URI<br /><br />Eksempel: <a href="http://data.geonorge.no/SentraltStedsnavnsregister/1.0">http://data.geonorge.no/SentraltStedsnavnsregister/1.0</a><br /><br />Merknad : Verdien for nanverom vil eies av den dataprodusent som har ansvar for de unike identifikatorene og må være registrert i data.geonorge.no eller data.norge.no</td>
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
      <td><strong>skredtype</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>hvilke skredmasser som er forbundet med skredfaren eller skredhendelsen<br />Merknad: Ulike typer skredmasser som bl.a. stein, snø, fjell, jord og kombinasjoner av disse<br /><br />English definition:<br />Specifies the type of avalanche/landslide material associated with the hazard or avalanche event.<br />Note: Different types of avalanche material may include rock, snow, bedrock, soil, or combinations of these</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>SkredtypeDetaljert</td>
    </tr>
    <tr>
      <th scope="row">Tillatte verdier:</th>
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/skredtypedetaljert">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/skredtypedetaljert</a></td>
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
      <td><strong>geometri</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>registreres geometri</td>
    </tr>
    <tr>
      <th scope="row">Multiplisitet:</th>
      <td>1</td>
    </tr>
    <tr>
      <th scope="row">Type:</th>
      <td>GM_Point</td>
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
      <td><strong>hensynTilSkog</strong></td>
    </tr>
    <tr>
      <th scope="row">Definisjon:</th>
      <td>angir om skredfaresonen er kartlagt med hensyn til skogens beskyttende effekt mot skredfare.<br />“Ja” betyr at skogens effekt på skredfaren er vurdert slik den var på tidspunktet for kartleggingen.<br />“Nei” betyr at skredfaresonen er kartlagt uten å ta hensyn til skogens effekt.<br /><br />English definition:<br />Indicates whether the avalanche hazard zone has been mapped with consideration of the forest’s protective effect on avalanche hazard.<br />“Yes” means the zone was mapped taking into account the forest’s effect as it was at the time of mapping.<br />“No” means the forest’s effect was not considered in the hazard mapping</td>
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
      <td>- Kodeliste: <a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/janei">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/janei</a></td>
    </tr>
  </tbody>
</table>

Relasjoner

**Arv**
FellesegenskaperFaresonekartForSkredIbrattTerreng

### Kodelister

#### «CodeList» SkredtypeDetaljert

**Definisjon:** ulike typer skredmasser som bl.a. stein, snø, fjell, jord og kombinasjoner av disse

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/skredtypedetaljert">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/skredtypedetaljert</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» SkredSannsynlighetBrattTerreng

**Definisjon:** statistisk sannsynlighet for at det går et skred i området pr år

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/skredsannsynlighetbrattterreng">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/skredsannsynlighetbrattterreng</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» JaNei

**Definisjon:** Ja Nei kodeliste

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/janei">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/janei</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Målemetode

**Definisjon:** metode som ligger til grunn for registrering av posisjon. Kodelista er en utvidelse fra SOSI 5.1 med koden fagligSkjønnstegningPåSkjerm

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/malemetode">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/malemetode</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Prosjekttype

**Definisjon:** angir for hvilket formål skredfaren opprinnelig ble utredet for

English definition:
Indicates the original purpose for which the avalanche hazard was assessed

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/prosjekttype">https://register.geonorge.no/sosi-kodelister/samfunnssikkerhet/flom-og-skred/prosjekttype</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Kommunenummer

**Definisjon:** nummerering av kommunen i henhold til Statistisk sentralbyrå sin offisielle liste Merknad: Det presiseres at kommune alltid skal ha 4 siffer, dvs. eventuelt med ledende null. Kommune benyttes for kopling mot en rekke andre registre som også benytter 4 siffer
Merknad: Her angis den kommune som utgjør det største arealet

English definition:
Numbering of municipalities according to Statistics Norway’s official list.
Note: The municipality number must always consist of four digits, including leading zeros if necessary. Municipality numbers are used for linking to various other registers that also use four-digit codes

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer">https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/kommunenummer</a></td>
    </tr>
  </tbody>
</table>

#### «CodeList» Fylkesnummer

**Definisjon:** &lt;font color="#333333"&gt;nummerering av fylker i henhold til Statistisk sentralbyrå sin offisielle liste &lt;/font&gt;
&lt;font color="#333333"&gt;Merknad: Det presiseres at fylkesnummer alltid skal ha 2 sifre, dvs. eventuelt med ledende null. Fylkesnummer benyttes for kopling mot en rekke andre registre som også benytter 2 sifre&lt;/font&gt;
&lt;font color="#333333"&gt;Merknad: Her angis det fylket som utgjør det største arealet&lt;/font&gt;
&lt;font color="#333333"&gt;
&lt;/font&gt;&lt;font color="#333333"&gt;English definition:&lt;/font&gt;
&lt;font color="#333333"&gt;Numbering of counties according to Statistics Norway’s official list. &lt;/font&gt;
&lt;font color="#333333"&gt;Note: The county number must always consist of two digits, including a leading zero if necessary. County numbers are used for linking to various other registers that also use two-digit codes&lt;/font&gt;

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
      <td><a href="https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/fylkesnummer">https://register.geonorge.no/sosi-kodelister/inndelinger/inndelingsbase/fylkesnummer</a></td>
    </tr>
  </tbody>
</table>
