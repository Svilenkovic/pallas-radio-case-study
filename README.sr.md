<a href="https://www.pallasradio.com/"><img src="media/cover.jpg" alt="Pallas Radio, naslovna strana na laptopu i telefonu" width="100%"></a>

# Pallas Radio

Sajt radija na 94,8 MHz: veliki plejer uživo sa pločom koja se okreće samo dok svira, SMS želje i oglasi i stare plejliste koje i dalje rade.

**[pallasradio.com](https://www.pallasradio.com/)** · [Studija slučaja](https://svilenkovic.rs/radovi/pallas-radio) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Pallas production doo</td></tr>
  <tr><td><b>Delatnost</b></td><td>Radio sa domaćom muzikom</td></tr>
  <tr><td><b>Lokacija</b></td><td>Kikinda</td></tr>
  <tr><td><b>Vrsta</b></td><td>Sajt radija (PWA)</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Redizajn, izrada, selidba, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, MariaDB, Redis, nginx, PWA</td></tr>
</table>

## O projektu

Pallas Radio pušta domaću muziku na 94,8 MHz za opštinu Nova Crnja, pod sloganom „Stvarno dobra muzika“. Ovde je program na prvom mestu, pa sam napravio sajt radija, a ne portal vesti. Ko ga otvori, prvo vidi plejer, a odmah ispod SMS želje i oglase.

Sajt radi na istoj platformi kao portali Radija AMI i Ami Naxi Radija, sa svojim rasporedom strana i tamnom noćnom scenom u malina i bordo bojama loga. Naslovna počinje velikim plejerom uživo i gramofonskom pločom koja se okreće samo dok strim svira; na ostalim stranama plejer prelazi u zaglavlje i nastavlja da svira. Slušaoci koji su Pallas podesili u Winampu, VLC-u ili radio aplikaciji preko starih adresa plejlista /play/?pl= nisu morali ništa da menjaju, jer te adrese i dalje vraćaju plejlistu.

## Šta sam uradio

- Veliki plejer uživo na naslovnoj, sa pločom koja se okreće samo dok program svira i koji na ostalim stranama prelazi u zaglavlje
- Strana za SMS oglase i muzičke želje koja kaže šta se kuca, na koji broj se šalje i kada se oglasi čitaju u programu
- Pallas Info sa 209 objava prenetih sa starog sajta, 25 preusmerenja starih adresa i banerom sponzora
- Stare adrese plejlista /play/?pl= sačuvane za spoljne plejere, uz nove liste M3U i PLS
- Kontakt forma preko mog centralnog servisa za forme, veza ka Facebook strani radija, panel za redakciju kao zasebna aplikacija i javni deo kao aplikacija
- Mobilni PageSpeed 98, a pristupačnost, dobre prakse i SEO 100, izmereno 17. oktobra 2026.

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 98 | 100 | 100 | 100 |
| Desktop | 100 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, oktobar 2026. Sigurnosna zaglavlja: 6 od 6. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `BroadcastService`, `NewsMediaOrganization`, `RadioStation`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Pallas Radio, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Pallas Radio, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="SMS želje i oglasi, sa uputstvom za slanje i terminima čitanja">
<sub>SMS želje i oglasi, sa uputstvom za slanje i terminima čitanja</sub>

<img src="media/inner-2.webp" alt="Pallas Info: vesti na svetlim karticama, baner sponzora i plejer sa strane">
<sub>Pallas Info: vesti na svetlim karticama, baner sponzora i plejer sa strane</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
