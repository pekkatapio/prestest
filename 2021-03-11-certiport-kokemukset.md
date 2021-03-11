class: center, middle, inverse

# Certiport-testikeskus

pystyttäminen ja kokemukset

.footnote[Tästä pääset suoraan [ohjeisiin](https://github.com/hayo-labra/certiport-testikeskus)]

---

# Testikeskus?

Certiport Authorized Test Center (CATC) on testikeskus, jolle on annettu valtuudet ottaa vastaan Certiportin testejä.

Kuntayhtymällä on sopimus, joka mahdollistaa seuraavien testien vastaanottamisen:

 - Microsoft Technology Associate (MTA)
 - Microsoft Certified Fundamentals (aka Microsoft Technical Certifications)
 - Microsoft Office Specialist (MOS)
 - Microsoft Certified Educator
 
---

# Yksi, kaksi, ... siis kuinka monta?

Testikeskus on varsin laaja käsite.

Organisaatiossa voi olla useampia "testikeskuksia", jotka voivat koostua useammasta työasemasta tai yksittäisestä, mukana kulkevasta kannettavasta.

Käyttöönotossa on kuitenkin syytä huomioida Certiportin [määritykset](https://certiport.pearsonvue.com/Educator-resources/Exam-policies/Administration) tilaan, jossa testit suoritetaan.

---

# Asennuksen check-lista

Jotta voit pystyttää testikeskuksen, niin tarvitset siihen seuraavat palikat:

  - pöytäkone tai -koneet, voi olla myös kannettava (huomioi [laitteistovaatimukset](https://certiport.pearsonvue.com/Support/Technical-requirements.aspx))
  - vähintään Organization Member -tason oikeudet Certiport-palveluun
  - Windowsin asennusmedia (asennustikun voi luoda tällä [skriptillä](https://github.com/hayo-labra/Create-WindowsUSBInstall))
  - Windowsin pääkäyttäjän tunnukset (tärkeää silloin, kun saat koneen esiasennettuna)

---

# Windowsin asennus

MOS-testit ovat tarkkoja koneen kieliasetuksista. Lähtökohtaisesti käyttöjärjestelmä ja siihen asennetut ohjelmat tulee olla samalla kielellä kuin suoritettava testi eli käytännössä **englanniksi**.

Näppäimistöasettelun ja aikavyöhykkeen voit määritellä suomalaisiksi, määrittele muut poikkeuksetta asetuksella English (United States) tai United States.

---

# Windowsin muut asetukset

Nimeä kone järkevästi, koska se näkyy myös testien suorituslistoissa.

Koneen verkkoasetukset voi määritellä joko DHCP:n kautta tai staattisina, Compass toimii kummallakin. 

Lisäksi koneessa tulee olla seuraavat asennettuna:

 - Adobe Acrobat Reader
 - tulostin (Microsoft XPS Document Printer riittää)

---

# Office 365 Apps

Office tulee myös asentaa englannin kielisenä versiona.

Lisäksi Officen versio tulee lukita tiettyyn, Compassin testien kanssa yhteensopivaan versioon. Tämä tapahtuu [tässä dokumentissa](https://certiport.pearsonvue.com/Support/PDFs/MOS-365-Versioning-Three.pdf) olevilla komentorivikomennoilla.

Office-pakettia ei tarvitse aktivoida. Jokainen Office ohjelma tulee kuitenkin avata niin pitkälle, että sovelluksessa on auki tyhjä dokumentti tai työkirja.

---

# Compass

Jos olet tehnyt edellä käsitellyt etukäteisvalmistelut huolella, niin Compass-sovelluksen asennus ja määrittely on hyvin suoraviivainen toimitus.

 1. Lataa ja asenna Compass-sovellus.
 2. Kirjaudu sisään Certiport-tunnuksillasi.
 3. Määrittele seuraavat asetukset:
     - serveriksi Production server,
     - ID:ksi se mitä on tarjolla,
     - kieleksi English,
     - Admin credentials -kohtaan koneen pääkäyttäjän tunnukset,
     - lan settings riippuu siitä, onko testikone yksittäinen kannettava, palvelin vai asiakas,
     - päivitystaajuudeksi Daily ja
     - proxy määrittelemättä.
