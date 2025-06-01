# Windows11H_Alexa🛟 <sup>5.5.31</sup>
<a href="https://drive.google.com/drive/folders/1PjNjLoUtQdGAW1A2i_0EOtZBQQqCw1Ox?usp=drive_link">*Win11H_Alexa TELEPÍTŐ LETÖLTÉSE🎯*</a> <tt>❗Forrás: Windows 11 Pro 24H2.<sup>(eredeti Microsoft kiadás, build: 26100 1742)</sup></tt>

Ezt a "mentőövet" azoknak dobom (a riogatást elhessentve, hogy a Win10 támogatás befuccsol<sup>tény, hogy 2025.10.15-től nem támogatja a gyártó</sup>), akik magyarul beszélnek, akik nem szeretik, hogy <tt>M</tt>á<tt>S</tt> beleszól abba, mit, hogyan csinálnak a saját tulajdonú, SZEMÉLYI számítógépükkel.
Ez a <CODE><b><i>WINDOWS 11 TELEPÍTŐ</i></b></CODE> magyarul beszél, magyar Windows 11 Pro rendszert épít, úgy, hogy semmilyen haszontalan, kéretlen, nyomkövető, vagy reklám program nem települ vele: <b>~50 program lett kiiktatva a telepítőből (csak böngészési és MS Store telepítési lehetőség maradt a gyári Win-ből)👌> megmaradtak az eredeti Microsoft Windows eredeti jó élményei, anélkül, hogy a gyári telepítőn rendszerszintű módosítás lenne...</b>. 
Nem igényli a "kötelező hardvert", régi (akár 10+ éves) számítógépre (PC, laptop, notebook) is települ, és stabilan használható. (Ajánlott minimumok: 4 GB RAM, 64 GB tárhely. 64 bit-es proci kell❗, de ezt már tudják a 10+éves gépek is... Persze újabb, vagy extrém jó vason is kiválóan működik.🤗)
A "csupasz" Windows használat megkezdése után találsz benne egy mappát, a tartalmát felhasználva könnyedén - megint csak "egyenesen, magyarul" - telepítheted létfontosságú drivereidet, kedvenc programjaidat. <sub>*Ennek a repository-nak nem tárgya, hogy miért,❗de csak UEFI-s gépre érdemes telepíteni (GPT partíciós táblára) a Windows 11-et, a BIOS/MBR kerülendő!</sub>

<hr>
#🛠️⚙️

1. Töltsd le a <a href="https://etcher.balena.io/">Balena Etchert innen</a>, a webhelyen a zöld *Download Etcher* gombbal, vagy közvetlenül: <a href="https://github.com/balena-io/etcher/releases/download/v2.1.0/balenaEtcher-2.1.0.Setup.exe">ide kattintva.</a> | <sub> ⛔ Kivételesen NE használj ehhez a telepítőhöz Rufust! ⛔</sub>.

2. Csatolj egy legalább 8 GB-os USB adattárolót a gépedhez (ne legyen semmi fontos dolog a 'pendrájvon', mert törölve lesz minden🚩,  telepítés után formázással újra használható), indítsd el a Balena Etcher-t
   
3. Válaszd ki a *Flash from File*-t, tallózd be a fentről letöltött <tt>Win11H_Alexa ISO</tt>-t. A *Select Target* gombbal válaszd ki írásra az USB tárolód. *Flash* gombbal indítsd el az ISO kiírását, azaz indítható Windows telepítő készítést az USB-re (átlag kb 5-8 perc az írás).
   
4. Csatold az USB tárolót ahhoz a géphez, amelyikre Windowst akarsz telepíteni.
   
5. Indítsd el a gépet Boot menü-vel (ez legtöbb gépen a gépgyártó logó megjelenésekor <b><tt>Esc</tt>,<tt>Del</tt>,<tt>F2</tt>,<tt>F8</tt>,<tt>F9</tt>, <tt>F10</tt>,<tt>F12</tt></b> billentyűvel megy, ha nem vagy biztos benne, keress rá a neten a Tiedre).
   
6. Válaszd ki rendszer betöltéshez (boot) az USB tárolót, elindul a Windows 11 telepítő.
    
7. Haladj végig a magyar nyelvű telepítő egyszerű lépésein. A telepítés elején: partícionálásnál ügyelj, hogy mit választasz, ha nincs fontos dolgod a gépen, legjobb *minden partíciót törölni* (*Delete*) a tiszta telepítéshez, de ajánlott legalábbis 64 GB üres hely, ennek nézz utána előtte guglival, ha nem vagy biztos benne. Ezen kívül csak felhasználó nevet kell választanod, minden más automatikus. KÉSZ.
   Időigény: kb. 25 perc internet kapcsolat nélkül (!), átlagos internet sebesség és régebbi proci + SSD esetén kb. +3 perc. *Vezetékes net vagy wifi nélküli telepítés esetén a telepítőben a kapcsolódásra kérő képernyőn válaszd a "nincs internetem"-et. (Természetesen később kapcsolódhatsz pár kattintással a netedre.)*
 
  <b>

*😈 A telepítésből KIMARAD 💩 :*
     
- secureboot, és TPM2 ellenőrzés, RAM minimum ellenőrzés (a gyártói telepítő ezek nélkül nem működik <sup><a href="https://www.microsoft.com/hu-hu/windows/windows-11-specifications">részletek</a></sup>);
- Windows haszontalanságok: nyomkövető és reklám programok, egyéb "hulladék" ~50 szoftver, lásd a csatolt fájlban; (⛔ emiatt utólag felesleges külső debloating és disable telemetry, meg hasonló parancs programok használata)
- online Microsoft fiók (az "élénk online érdeklődés" elhárítására); helyi fióknév (rendszergazda) választás és felhasználó fiók létrehozás történik;
- online kapcsolat követelése (de ha akarod, van lehetőség internet kapcsolattal telepíteni [ajánlott]).
  </b>

*😎 Ami BENNE van 👀 :*
- Windows prog.: Edge, Jegyzettömb, Microsoft Store.
- <tt>.Alexa</tt> mappa: MS aktivátor és nagyszerű/egyszerű programok (pl. Chrome, VLC, Xnview, MS Office, ChrisTitusTech, stb) telepítésének lehetősége (🥳NEM KÖTELEZ TÉGED semmire! Akár törölhető is 1 kattintással).
- 🥇*intel driver telepítő*, és *AMD driver telepítő*, DirectX telepítő...

*💥Telepítés UTÁN azonnal ajánlott:*

 a procidnak megfelelő driver telepítő futtatása.

<tt>✅ Sikeresen tesztelve az alábbi gépen: intel i3 7.gen CPU, integrált GPU, 16 GB DDR4 RAM, 64 GB SSD tárhely.✅ (*ui.:2025. május 12-től főrendszerként funkcionál tökéletesen)</tt>

<sub>⚠*Bátrabb, tapasztalt felhasználóknak. Külön partícióról az ISO kibontott tartalmát arra másolva, onnan a setup.exe-vel indítva is működik 2. Windowsként, dual boot módban az 1.-vel.</sub>
<hr>

<sub>💻A szerző nem informatikai szakember, de 30 éve foglalkozik Windows-sal, elkötelezett a "személyreszóló" Windows telepítéshez biztonságos, stabil eszközök és módszerek használatára, ez a Windows ilyen.</sub>
<sub>(😎A telepítő ingyenes, és az is marad!💝)</sub>
