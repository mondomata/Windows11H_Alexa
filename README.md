# Windows11H_Alexa🛟
<a href="https://drive.google.com/drive/folders/1PjNjLoUtQdGAW1A2i_0EOtZBQQqCw1Ox?usp=drive_link">*Win11H_Alexa TELEPÍTŐ LETÖLTÉSE🎯*</a> <tt>❗Forrás: Windows 11 Pro 24H2.<sup>(eredeti Microsoft kiadás, build: 26100 1742)</sup></tt>

Ezt a "mentőöv"-et azoknak dobom (a riogatást is elhessentve, hogy a Win10 támogatás befuccsol<sup>tény, hogy 2025.10.15-től nem támogatja a gyártó</sup>), akik magyarul beszélnek, akik nem szeretik, hogy <tt>M</tt>á<tt>S</tt> beleszól abba, mit, hogyan csinálnak a saját tulajdonú, SZEMÉLYI számítógépükkel.
Ez a <CODE><b><i>WINDOWS 11 TELEPÍTŐ</i></b></CODE> magyarul beszél, magyar Windows 11 Pro rendszert épít, úgy, hogy semmilyen haszontalan, kéretlen, nyomkövető, vagy reklám program nem települ vele: <b>~50 program lett kiiktatva a telepítőből👌, miközben megmaradtak az eredeti Microsoft Windows eredeti jó élményei, anélkül, hogy a gyári telepítőn rendszer módosítás lenne...</b>. 
Nem igényli a "kötelező hardvert", régi (akár 10-15 éves) számítógépre (PC, laptop, notebook) is települ, és stabilan használható. (Ajánlott minimumok: 4 GB RAM, 64 GB tárhely. 64 bit-es proci kell❗, de ezt már tudják a 10+éves gépek is... Persze újabb, vagy extrém jó vason is kiválóan működik.🤗)
A "csupasz" Windows használat megkezdése után találsz benne egy mappát, a tartalmát felhasználva könnyedén - megint csak "egyenesen, magyarul" - telepítheted kedvenc programjaidat. <sub>*Ennek a repository-nak nem tárgya, hogy miért, de az tény, hogy bármely Windows 11-t ❗csak UEFI-s gépre érdemes telepíteni (GPT partíciós táblára), a BIOS/MBR kerülendő! BIOS/MBR telepítés esetén együtt kell élni a lassú rendszer indítás mellett a tetemes teljesítmény csökkenéssel rendszer használat közben is, ez nem a Windows hibája.*</sub>

<hr>
#🛠️⚙️

1. Töltsd le a Balena Etchert: https://etcher.balena.io/ webhelyen a zöld *Download Etcher* gombbal, vagy közvetlenül ide kattintva: https://github.com/balena-io/etcher/releases/download/v2.1.0/balenaEtcher-2.1.0.Setup.exe | <sub> ⛔ Kivételesen NE használj ehhez a telepítőhöz Rufust, vagy Ventoy-t! ⛔ </sub>.

2. Csatolj egy legalább 8 GB-os USB adattárolót a gépedhez (ne legyen semmi fontos dolog a 'pendrájvon', mert törölve lesz minden🚩), indítsd el a Balena Etcher-t
   
3. Válaszd ki a *Flash from File*-t, tallózd be a fentről letöltött <tt>Win11H_Alexa ISO</tt>-t. A *Select Target* gombbal válaszd ki írásra az USB tárolód. *Flash* gombbal indítsd el az ISO kiírását, azaz indítható Windows telepítő készítést az USB-re (kb 3 perc az írás).
   
4. Csatold az USB tárolót ahhoz a géphez, amelyikre Windowst akarsz telepíteni.
   
5. Indítsd el a gépet Boot menü-vel (ez legtöbb gépen a gépgyártó logó megjelenésekor <b><tt>Esc</tt>, <tt>F8</tt>, <tt>F9</tt>, <tt>F10</tt></b> billentyűvel megy, ha nem vagy biztos benne, keress rá a neten a Te gépedhez valóra).
   
6. Válaszd ki rendszer betöltéshez (boot) az USB tárolót, elindul a Windows 11 telepítő.
    
7. Haladj végig a magyar nyelvű telepítő egyszerű lépésein (a telepítő elején: termékkulcs? válaszd a "Nincs termékkulcsom"-at, majd a felsorolt op.rendszerekből válaszd a "Windows 11 Pro"-t, partíció választásnál pedig ügyelj, hogy mit választasz (ha nincs fontos dolgod a gépen, legjobb minden partíciót törölni a tiszta telepítéshez, de ajánlott legalább 64 GB üres hely), ennek nézz utána előtte guglival, ha nem vagy biztos benne. KÉSZ.
   Időigény: kb. 20 perc internet kapcsolat nélkül (!), átlagos internet sebesség és régebbi proci + SSD esetén kb. 30 perc (mert közben több GB-s rendszer frissítés is történik). *Vezetékes net vagy wifi nélküli telepítés esetén a telepítőben a kapcsolódásra kérő képernyőn válaszd a "nincs internetem"-et. (Természetesen később kapcsolódhatsz pár kattintással a netedre.)*
   

  <b>

*😈 A telepítésből KIMARAD 💩 :*
     
- secureboot, és TPM2 ellenőrzés, valamint a beépített RAM minimum ellenőrzése (a szokványos telepítő ezek nélkül nem működik <sup><a href="https://www.microsoft.com/hu-hu/windows/windows-11-specifications">Lásd részletesebben ide kattintva.</a></sup>);
- Windows haszontalanságok: nyomkövető és reklám programok, egyéb "hulladék" ~50 szoftver, lásd a csatolt fájlban; (⛔ emiatt utólag felesleges külső debloating és disable telemetry, meg hasonló parancs programok használata, pl. "Neonity xtremeshell", "Raphire debloat tool", "ChrisTitusTools" <sup>- ez utóbbi egyéb zseniális funkciói miatt benne van a telepítésben</sup>)
- online Microsoft fiók (az "élénk online érdeklődés" elhárítására) - helyette helyi fióknév (rendszergazda) választás és létrehozás történik;
- a telepítőben nincsenek specifikus drivertelepítők /ahogy a MS telpítőben sincs/, erősen ajánlott ezeket a te géped gyártó honlapjáról előre beszerezve szintén az USB-re másolni, majd azonnal telepíteni az első indítás után)
  </b>

*😎 Ami BENNE van 👀 :*
  
- <tt>.Alexa</tt> mappa nagyszerű és/vagy egyszerű programok (pl. Chrome, VLC, MS Office, ChrisTitusTools, stb) telepítésének lehetőségével az első bejelentkezés után (🥳NEM KÖTELEZ TÉGED semmire!!! Akár törölhető is 1 kattintással).
Ennyi.

*💥Telepítés UTÁN azonnal javasolt (.Alexa mappán kívül):*

Driver Booster - https://www.iobit.com/en/driver-booster.php 
(Egyre jobb, de nem tökéletes a Windows rendszerbe épített "gyári" drivertelepítő... Helyette ajánlott a többszázezer eszköz drivert magába foglaló booster.)

<tt>✅ Sikeresen tesztelve az alábbi gépen: intel i3 7.gen CPU, integrált GPU, 16 GB DDR4 RAM, 64 GB SSD tárhely.✅</tt>

<sub>⚠*Bátrabb, tapasztalt felhasználóknak. Meglévő Windows mellé, 2. rendszernek (dual boot) Alexa telepítés menete: az ISO fájlt csatlakoztatva virtuális meghajtóra és egy 8 GB-os erre a célra kreált FAT32 partícióra másolva a teljes tartalmát, a "másolatból" futtatni kell a  <tt>setup.exe</tt> -t . Ezzel elindul az új telepítési folyamat. A telepítőben partícionáláskor zsugorítani kell a meglévő régi Windows partíciót, és az így kreált új (min. ~64 GB) partícióra telepíteni az újat. Gép indításkor 2 Windows között lehet majd választani.</sub>
<hr>

<sub>A szerző nem informatikai szakember, de 30 éve foglalkozik Windows-sal, elkötelezett a "személyreszóló" Windows telepítéshez biztonságos, stabil eszközök és módszerek használatára, ez a Windows ilyen.</sub>
<sub>(😎A telepítő ingyenes, és az is marad!💝)</sub>
