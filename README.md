# Windows11H_Alexa🛟
Ideiglenesen leallítva az ISO letöltési lehetőség karbantartás miatt. Várható élesítés: 2025. május 5-9. között.

Ezt a "mentőöv"-et azoknak dobom (a riogatást is elhessentve, hogy a Win10 befuccsol<sup> tömeghír, hogy 2025 ősztől nem támogatja a gyártó /ez így nem teljesen igaz)</sup>), akik magyarul beszélnek, akik nem szeretik, hogy <tt>M</tt>á<tt>S</tt> beleszól abba, mit, hogyan csinálnak a saját tulajdonú, SZEMÉLYI számítógépükkel.
Ez a <CODE><b><i>WINDOWS 11 TELEPÍTŐ</i></b></CODE> magyarul beszél, magyar Windows 11 Pro rendszert épít, úgy, hogy semmilyen nyomkövető, vagy reklám program nem települ vele, <b>~50 haszontalan program lett kiiktatva a telepítőből👌, miközben megmaradtak az eredeti Microsoft Windows eredeti jó élményei...</b>. 
Nem igényli a kötelező hardvert/szoftvert, régi (akár 10-15 éves) számítógépre (PC, laptop, notebook) is települ, és stabilan használható. (Ajánlott minimumok: 8 GB RAM, 64 GB tárhely. 64 bit-es proci kell, de ezt már tudják a 10+éves gépek is... Persze újabb, vagy extrém jó vason is kiválóan működik.🤗)
A "csupasz" Windows használat megkezdése után találsz benne egy mappát, a tartalmát felhasználva könnyedén - megint csak "egyenesen, magyarul" - telepítheted kedvenc programjaidat. <!--
<a href="https://drive.google.com/drive/folders/1PjNjLoUtQdGAW1A2i_0EOtZBQQqCw1Ox?usp=sharing"><tt> 🪟 A Win11H_Alexa.ISO telepítőt ide kattintva töltheted le ❤️ 🪂 </tt></a>
-->

<tt>❗A telepítőhöz használt forrás: Microsoft Windows 11 Pro 24H2.<sup>(eredeti Microsoft kiadás, build: 26100 1742)</sup></tt>
<hr>
#🛠️🛠️🛠️

1. Töltsd le a Balena Etchert: https://etcher.balena.io/ zöld Download Etcher gomb, vagy közvetlenül: https://github.com/balena-io/etcher/releases/download/v2.1.0/balenaEtcher-2.1.0.Setup.exe | <sub> ⛔ Kivételesen NE használj ehhez a telepítőhöz Rufust, vagy Ventoy-t! ⛔ </sub>.

2. Csatolj egy legalább 8 GB-os USB adattárolót (ne legyen semmi fontos dolog a 'pendrájvon', mert törölve lesz minden🚩) a gépedhez, indítsd el a Balena Etcher-t
   
3. Válaszd ki az Etcher-ben a Flash from File-t, tallózd be a fentről letöltött <tt>Win11H_Alexa ISO</tt>-t. A Select Target gombbal válaszd ki írásra az USB tárolód. Flash gombbal indítsd el az ISO kiírását, azaz indítható Windows telepítő készítést az USB-re (kb 3 perc az írás).
   
4. Csatold az USB tárolót ahhoz a géphez, amelyikre Windowst akarsz telepíteni.
   
5. Indítsd el a gépet Boot menü-vel (ez legtöbb gépen a gépgyártó logó megjelenésekor <b><tt>Esc</tt>, <tt>F8</tt>, <tt>F9</tt>, <tt>F10</tt></b> billentyűvel megy, ha mégsem, keress rá a te gépedhez a neten).
   
6. Válaszd ki betöltéshez (boot) az USB tárolót, elindul a Windows 11 telepítő.
    
7. Haladj végig a magyar nyelvű telepítő egyszerű lépésein (az elején válaszd a "Windows 11 Pro"-t, termékkulcs kéréskor válaszd a "Nincs termékkulcsom" lehetőséget, partíció választásnál pedig ügyelj, hogy mit választasz, ennek nézz utána előtte). KÉSZ.
   Időigény: kb. 20 perc internet kapcsolat nélkül (!), átlagos internet sebesség és régebbi proci + SSD esetén kb. 30 perc. Kábel net vagy wifi nélküli telepítés esetén a telepítőben a kapcsolódásra kérő képernyőn válaszd a "nincs internet"-et. (Természetesen később   kapcsolódhatsz pár kattintással a netedre.)
   

  <b>

*😈 A telepítésből KIMARAD 💩 :*
     
- secureboot, és TPM2 ellenőrzés (a szokványos telepítő ezek nélkül nem működik);
- Windows haszontalanságok: nyomkövető és reklám programok, egyéb "hulladék" ~50 szoftver, lásd a csatolt fájlban; (⛔ emiatt utólag felesleges külső debloating és disable telemetry, meg hasonló parancs programok használata, pl. "neonity xtremeshell", "raphire", "christitus")
- online Microsoft fiók (az "élénk online érdeklődés" elhárítására) - helyette helyi fióknév (rendszergazda) választás és létrehozás történik;
- a telepítőben nincsenek specifikus drivertelepítők /ahogy a MS telpítőben sincs/, erősen ajánlott ezeket a te géped gyártó honlapjáról előre beszerezve szintén az USB-re másolni, majd azonnal telepíteni az első indítás után)
  </b>

*😎 Ami BENNE van 👀 :*
  
- <tt>.Alexa</tt> mappa nagyszerű és/vagy egyszerű programok (pl. Chrome, MS Office, stb) telepítésének lehetőségével az első bejelentkezés után (🥳NEM KÖTELEZ TÉGED semmire!!! Akár törölhető is 1 kattintással).
Ennyi.

*💥Telepítés UTÁN javasolt (.Alexa mappában írtakon kívül):*

Driver Booster - https://www.iobit.com/en/driver-booster.php 
(Egyre jobb, de nem tökéletes a Windows rendszerbe épített "gyári" drivertelepítő...)

<tt>Sikeresen tesztelve az alábbi gépen: intel i3 7.gen CPU, integrált GPU, 16 GB DDR4 RAM, 64 GB SSD tárhely.✅</tt>

<sub>⚠*Bátrabb, tapasztalt felhasználóknak. Meglévő Windows mellé, 2. rendszernek (dual boot) Alexa telepítés menete: az ISO fájlt csatlakoztatva virtuális meghajtóra és egy 8 GB-os erre a célra kreált FAT32 partícióra másolva a teljes tartalmát, a "másolatból" futtatni kell a  <tt>setup.exe</tt> -t . Ezzel elindul az új telepítési folyamat (a régi Windows megtartásával), a telepítőben partícionáláskor zsugorítani kell a meglévő régi Windows partíciót, és az így kreált új (min. ~64 GB) partícióra telepíteni az újat. Gép indításkor 2 Windows között lehet majd választani.</sub>
<hr>

<sub>A szerző nem informatikai szakember, de 30 éve foglalkozik Windows-sal, elkötelezett a "személyreszóló", de "mókolatlan" Windows telepítéshez biztonságos, stabil eszközök és módszerek használatára, ilyen ez a Windows is.</sub>
<sub>(😎A telepítő ingyenes, és az is marad!💝)</sub>
