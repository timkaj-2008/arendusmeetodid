# arendusmeetodid

## Diagrammid

### Liidestuse skeem (Smart-ID)
![Smart-ID liidestuse skeem](diagrammid.drawio)

```mermaid
<mxGraphModel dx="462" dy="397" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="827" pageHeight="1169" math="0" shadow="0">
  <root>
    <mxCell id="0" />
    <mxCell id="1" parent="0" />
    <mxCell id="Zra6W8XkDagODbvrJweW-4" edge="1" parent="1" source="Zra6W8XkDagODbvrJweW-1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=1;entryDx=0;entryDy=0;" target="Zra6W8XkDagODbvrJweW-2">
      <mxGeometry relative="1" as="geometry">
        <Array as="points">
          <mxPoint x="260" y="490" />
          <mxPoint x="400" y="490" />
        </Array>
      </mxGeometry>
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-1" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="Kasutaja" vertex="1">
      <mxGeometry height="60" width="120" x="200" y="390" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-7" edge="1" parent="1" source="Zra6W8XkDagODbvrJweW-2" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.75;exitY=1;exitDx=0;exitDy=0;entryX=0.75;entryY=1;entryDx=0;entryDy=0;" target="Zra6W8XkDagODbvrJweW-3">
      <mxGeometry relative="1" as="geometry">
        <Array as="points">
          <mxPoint x="430" y="490" />
          <mxPoint x="570" y="490" />
        </Array>
      </mxGeometry>
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-2" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="Teie Süsteem" vertex="1">
      <mxGeometry height="60" width="120" x="340" y="385" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-10" edge="1" parent="1" source="Zra6W8XkDagODbvrJweW-3" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=0;exitDx=0;exitDy=0;entryX=0.5;entryY=0;entryDx=0;entryDy=0;dashed=1;" target="Zra6W8XkDagODbvrJweW-1">
      <mxGeometry relative="1" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-3" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="Smart-ID API" vertex="1">
      <mxGeometry height="60" width="120" x="480" y="390" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-5" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="1)Vajutab &quot;Logi sisse Smart-ID-ga&quot; + isikukood" vertex="1">
      <mxGeometry height="30" width="140" x="260" y="460" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-8" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="2)POST /authentication/pnr (isikukood)" vertex="1">
      <mxGeometry height="30" width="150" x="420" y="460" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-11" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="3) Teavitus telefonis (PIN1) + kontrollkood" vertex="1">
      <mxGeometry height="30" width="135" x="346" y="340" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-13" edge="1" parent="1" source="Zra6W8XkDagODbvrJweW-1" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.25;exitY=0;exitDx=0;exitDy=0;entryX=0.84;entryY=0.005;entryDx=0;entryDy=0;entryPerimeter=0;" target="Zra6W8XkDagODbvrJweW-3">
      <mxGeometry relative="1" as="geometry">
        <Array as="points">
          <mxPoint x="230" y="320" />
          <mxPoint x="580.8" y="320" />
        </Array>
      </mxGeometry>
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-14" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="4)Sisestab PIN1 koodi" vertex="1">
      <mxGeometry height="30" width="100" x="363.5" y="290" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-16" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="" vertex="1">
      <mxGeometry height="270" width="436" x="254" y="540" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-19" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="alt [ Õnnestus vs Veaolukord ]" vertex="1">
      <mxGeometry height="30" width="100" x="255" y="540" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-21" edge="1" parent="1" style="endArrow=none;html=1;rounded=0;exitX=0;exitY=0.75;exitDx=0;exitDy=0;entryX=1;entryY=0.75;entryDx=0;entryDy=0;" target="Zra6W8XkDagODbvrJweW-16" value="">
      <mxGeometry height="50" relative="1" width="50" as="geometry">
        <mxPoint x="254" y="742.5" as="sourcePoint" />
        <mxPoint x="474" y="580" as="targetPoint" />
      </mxGeometry>
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-23" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="(Viga / Ajalõpp &amp;gt; 10 sekundit)" vertex="1">
      <mxGeometry height="20" width="160" x="254" y="740" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-24" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="Kasutaja" vertex="1">
      <mxGeometry height="30" width="90" x="265" y="640" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-34" edge="1" parent="1" source="Zra6W8XkDagODbvrJweW-25" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.25;exitY=1;exitDx=0;exitDy=0;entryX=0;entryY=1;entryDx=0;entryDy=0;dashed=1;" target="Zra6W8XkDagODbvrJweW-24">
      <mxGeometry relative="1" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-25" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="Teie Süsteem" vertex="1">
      <mxGeometry height="30" width="90" x="414" y="640" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-27" edge="1" parent="1" source="Zra6W8XkDagODbvrJweW-26" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=1;entryDx=0;entryDy=0;dashed=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;" target="Zra6W8XkDagODbvrJweW-25">
      <mxGeometry relative="1" x="0.3981" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-26" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="Smart-ID API" vertex="1">
      <mxGeometry height="30" width="90" x="590" y="640" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-29" edge="1" parent="1" source="Zra6W8XkDagODbvrJweW-16" style="endArrow=none;html=1;rounded=0;exitX=0;exitY=0.25;exitDx=0;exitDy=0;entryX=1;entryY=0.25;entryDx=0;entryDy=0;" target="Zra6W8XkDagODbvrJweW-16" value="">
      <mxGeometry height="50" relative="1" width="50" as="geometry">
        <mxPoint x="254" y="608" as="sourcePoint" />
        <mxPoint x="574" y="608" as="targetPoint" />
      </mxGeometry>
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-22" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="(Edu)" vertex="1">
      <mxGeometry height="30" width="60" x="254" y="610" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-31" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="5)200 OK (Nimi, isikukood, kinnitatud: jah)" vertex="1">
      <mxGeometry height="20" width="200" x="450" y="700" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-35" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="6)Sisselogimine õnnestus (Tere tulemast!)" vertex="1">
      <mxGeometry height="30" width="160" x="270" y="695" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-36" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="Kasutaja" vertex="1">
      <mxGeometry height="30" width="90" x="265" y="760" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-41" edge="1" parent="1" source="Zra6W8XkDagODbvrJweW-37" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.25;exitY=1;exitDx=0;exitDy=0;entryX=0.25;entryY=1;entryDx=0;entryDy=0;dashed=1;" target="Zra6W8XkDagODbvrJweW-36">
      <mxGeometry relative="1" as="geometry">
        <Array as="points">
          <mxPoint x="436.5" y="850" />
          <mxPoint x="287.5" y="850" />
        </Array>
      </mxGeometry>
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-37" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="Teie Süsteem" vertex="1">
      <mxGeometry height="30" width="90" x="414" y="760" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-39" edge="1" parent="1" source="Zra6W8XkDagODbvrJweW-38" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;exitX=0.5;exitY=1;exitDx=0;exitDy=0;entryX=0.5;entryY=1;entryDx=0;entryDy=0;dashed=1;" target="Zra6W8XkDagODbvrJweW-37">
      <mxGeometry relative="1" as="geometry">
        <Array as="points">
          <mxPoint x="635" y="850" />
          <mxPoint x="459" y="850" />
        </Array>
      </mxGeometry>
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-38" parent="1" style="rounded=0;whiteSpace=wrap;html=1;" value="Smart-ID API" vertex="1">
      <mxGeometry height="30" width="90" x="590" y="760" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-40" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="7)Timeout &amp;gt; 10s / 500 Viga" vertex="1">
      <mxGeometry height="30" width="120" x="480" y="820" as="geometry" />
    </mxCell>
    <mxCell id="Zra6W8XkDagODbvrJweW-42" parent="1" style="text;html=1;whiteSpace=wrap;strokeColor=none;fillColor=none;align=center;verticalAlign=middle;rounded=0;" value="8)&quot;Smart-ID ei vasta. Palun proovi uuesti või kasuta parooli.&quot;" vertex="1">
      <mxGeometry height="30" width="175" x="270" y="860" as="geometry" />
    </mxCell>
  </root>
</mxGraphModel>

```
## Projekti tüübid

### (a) Uus funktsioon: Automaatne tühistamine ja teavitus
- **Tüüp:** olemasoleva süsteemi arendus
- **Mis muutub:** Lisandub uus klass `BookingCancellationService`, täiendatakse klasse `Booking` ja `NotificationService` ning lisatakse teavituse saatmise loogika.
- **Mis jääb samaks:** Olemasolev autentimissüsteem, kasutajate profiilid ja andmebaasi põhistruktuur.
- **Peamine risk:** Automaatse kontrolli (cron-job) valesti seadistatud ajavöönd tühistab broneeringud valel ajal või saadab kasutajatele valeteavitusi.
- **Esimene samm:** Kirjutada automaattestid (unit tests) olemasolevale tühistamisloogikale enne uue koodi kirjutamist.

---

### (b) Üleviimine: PHP 5 + MySQL → Node.js + PostgreSQL
- **Tüüp:** üleviimine uuele platvormile
- **Mis muutub:** Kogu backend-kood kirjutatakse ümber Node.js peale, andmebaas viiakse MySQL-ist PostgreSQL-i.
- **Mis jääb samaks:** Kõik kasutajalood, ekraanid ja äriloogika reeglid.
- **Peamine risk:** Ajalooliste andmete (kasutajad, broneeringud, maksed) migreerimisel tekivad andmetüüpide ühilduvusvead või andmekadu.
- **Esimene samm:** Viia läbi proovimigratsioon (dry-run) viimaste andmete koopia peal ja loendada kirjed enne koodi ümberkirjutamist.

---

### (c) Liidestamine: Smart-ID sisselogimine
- **Tüüp:** liidestamine
- **Mis muutub:** Autentimismoodul `AuthController`, sisselogimise ekraan (UI) ja turvamärkide haldus.
- **Mis jääb samaks:** Tavaline parooliga sisselogimine ja kasutajaprofiili andmemudel.
- **Peamine risk:** Smart-ID välise API katkestuste tõttu ei saa kasutajad sisse logida ja süsteem jääb ootama (timeout).
- **Esimene samm:** Tutvuda Smart-ID API dokumentatsiooniga ja seadistada demo-päring (sandbox environment).
- **Saadame:** Kasutaja isikukood.
- **Saame vastu:** Autentimise staatus (OK/CANCELLED/TIMEOUT), kasutaja ees- ja perekonnanimi.
