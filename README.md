# Windows11H_Alexa![{0BA92C3C-B400-4651-88AF-529E0AB25C0B}](https://github.com/user-attachments/assets/9d658da6-8d6f-4684-b26b-a16613120585)🛟 <sup>5.6.4</sup>

<sup>Az Alexa névnek semmi köze az azonos nevű multihoz. :)</sup>

🖐️🖐️🖐️<b>Van már újabb is a témában: keresd a csatornán a <a href=https://github.com/mondomata/Windows11Long_Alexa>Windows11Long_Alexa</a> leírását.</b><sub> 


Letöltés:

<a href="https://mega.nz/folder/YJZiFRLQ#SVjGnGg5Cu_gCwf6CbPY0w">*Win11H_Alexa TELEPÍTŐ LETÖLTÉSE (![image](https://github.com/user-attachments/assets/d592ce7a-00c7-4448-98a4-e3fe69351b82)MEGA)*</a>


<a href="https://drive.google.com/drive/folders/1PjNjLoUtQdGAW1A2i_0EOtZBQQqCw1Ox?usp=drive_link">*Win11H_Alexa TELEPÍTŐ LETÖLTÉSE (![{2686671A-5383-4004-860A-0D859347DD9C}](https://github.com/user-attachments/assets/9b0ed1e6-0d82-4381-882d-fa5f94f2b6e2)GDrive)*</a> 


<tt>❗Forrás:Windows 11 Pro 24H2.<sup>(eredeti Microsoft kiadás, build: 26100 1742)
😷 ISO fájl eredetiség ellenőrző összeg / SHA256 / 094A317D95FA5A560EFD21378DE44E0A8A8DE651C1523EFD9C567F0C7C709DDF </sup></tt>

Ezt a "mentőövet" azoknak dobom (a riogatást elhessentve, hogy a Win10 támogatás befuccsol<sup>tény, hogy 2025.10.15-től nem támogatja a gyártó</sup>), akik magyarul beszélnek, akik nem szeretik, hogy <tt>M</tt>á<tt>S</tt> beleszól abba, mit, hogyan csinálnak a saját tulajdonú, SZEMÉLYI számítógépükkel.
Ez a <CODE><b><i>WINDOWS 11 TELEPÍTŐ</i></b></CODE> magyarul beszél, magyar Windows 11 Pro rendszert épít, úgy, hogy semmilyen haszontalan, kéretlen, nyomkövető, vagy reklám program nem települ vele: <b>~50 program lett kiiktatva a telepítőből (csak böngészési és MS Store telepítési lehetőség maradt a gyári Win-ből)👌> megmaradtak az eredeti Windows eredeti jó élményei, rendszerszintű módosítás nélkül...</b>. 
Nem igényli a "kötelező hardvert", régi (akár 10+ éves) számítógépre (PC, laptop, notebook) is települ, és stabilan használható. 
A "csupasz" Windows használat megkezdése után találsz benne egy mappát, a tartalmát felhasználva könnyedén - megint csak "egyenesen, magyarul" - telepítheted létfontosságú drivereidet, programjaidat. <sub>*Ennek a repository-nak nem tárgya, hogy miért,❗de csak UEFI-s gépre települ (GPT partíciós táblára) a Windows 11, a BIOS/MBR kerülendő!</sub>

<hr>
#🛠️⚙️

1. Töltsd le fenti linken az <code>iso</code> fájlt (5.3Gb), majd a *Balena Etcher*-t közvetlenül <a href="https://github.com/balena-io/etcher/releases/download/v2.1.0/balenaEtcher-2.1.0.Setup.exe">ide kattintva.</a> | <sub> ⛔ Kivételesen NE használj ehhez a telepítőhöz Rufust! ⛔</sub>.

2. Csatolj egy legalább 8 GB-os USB adattárolót a gépedhez. Ne legyen semmi fontos dolog a 'pendrájvon', mert törölve lesz minden🚩 /telepítés után formázással újra használható/, indítsd el a Balena Etcher-t.
   
3. Válaszd ki a *[Flash from File]*-t, tallózd be a fentről letöltött <tt>Win11H_Alexa ISO</tt>-t. A *[Select Target]* gombbal válaszd ki írásra az USB tárolód. *[Flash]* gombbal indítsd el az ISO kiírását, azaz indítható Windows telepítő készítést az USB-re (5-8 perc az írás).
   
4. Csatold az USB tárolót ahhoz a géphez, amelyikre Windowst akarsz telepíteni.
   
5. Indítsd el a gépet *Boot menü*-vel (ez legtöbb gépen a gépgyártó logó megjelenésekor <b><tt>Esc</tt>,<tt>Del</tt>,<tt>F2</tt>,<tt>F8</tt>,<tt>F9</tt>,<tt>F10</tt>,<tt>F12</tt></b> billentyűvel megy, ha nem vagy biztos benne, keress rá a neten a Tiedre).
   
6. Válaszd ki rendszer betöltéshez (*boot*) az USB tárolót, elindul a Windows 11 telepítő (lehet, hogy a boot menü *Mass Storage* néven mutatja az USB-t).
    
7. Haladj végig a magyar nyelvű telepítő egyszerű lépésein. A telepítés elején: partícionálásnál ügyelj, hogy mit választasz, legjobb *minden partíciót törölni* (*Delete*) a tiszta telepítéshez (előtte ments minden fontos dolgot a lemezről, mert teljes törlés lesz). (Ajánlott legalábbis 64 GB üres hely.) Ezen kívül csak felhasználó nevet kell majd választanod, minden más automatikus. KÉSZ.
   Időigény: kb. 25 perc internet kapcsolat nélkül (igen, ez is lehetséges a gyári telepítőtől eltérően!), átlagos internet sebesség és régebbi proci + SSD esetén + 2-3 perc.
  <b>

*😈 A telepítésből KIMARAD 💩 :*
     
- secureboot, és TPM2 ellenőrzés, RAM minimum ellenőrzés (a gyártói telepítő ezek nélkül nem működik <sup><a href="https://www.microsoft.com/hu-hu/windows/windows-11-specifications">részletek</a></sup>);
- Windows haszontalanságok: nyomkövető és reklám programok, egyéb "hulladék" ~50 szoftver, lásd a csatolt fájlban; (⛔ emiatt utólag felesleges külső debloating és disable telemetry, meg hasonló parancs programok használata)
- online Microsoft fiók (az "élénk online érdeklődés" elhárítására); helyi fióknév (rendszergazda) választás és felhasználó fiók létrehozás történik;
- online kapcsolat követelése (de ha akarod, van lehetőség internet kapcsolattal telepíteni [ajánlott]).
  </b>

*😎 Ami BENNE van 👀 :*
- Windows program: Edge, Jegyzettömb, Microsoft Store.
- <tt>.Alexa</tt> mappa: MS aktivátor és nagyszerű/egyszerű programok (pl. Chrome, VLC, Xnview, MS Office, ChrisTitusTech, stb) telepítésének lehetősége (🥳NEM KÖTELEZ TÉGED semmire! Akár törölhető is 1 kattintással).
- 🥇*intel driver telepítő*, és *AMD driver telepítő*, DirectX telepítő... *💥Telepítés után azonnal ajánlott a procidnak megfelelő driver telepítés.*
<sup>(Az .Alexa mappa külön is megtalálható az iso letöltőhelyen, érdemes letölteni és a benne lévő újabb fájlokat a régiek helyére/mellé beemelni, használni az új vagy régebbi Windowson) </sup>
<tt>✅ Telepítve az alábbi gépen: intel i3 7.gen CPU /elavult/, integrált GPU, 16 GB DDR4 RAM, 64 GB SSD tárhely.✅ Jól funkcionál!</tt>

<sub>⚠*Bátrabb, tapasztalt felhasználóknak. Külön partícióra másolva  az ISO kibontott tartalmát, onnan a setup.exe-vel indítva is működik a telepítés, 2. Windowsként, dual boot módban az 1.-vel.</sub>
<hr>

<sub>💻A szerző nem informatikai szakember, de 30 éve foglalkozik Windows-sal, elkötelezett a "személyreszóló" Windows telepítéshez biztonságos, stabil eszközök és módszerek használatára, ez a Windows ilyen.</sub>
<sub>(😎A telepítő ingyenes, és az is marad!💝)</sub>
