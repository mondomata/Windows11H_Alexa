# Windows11H_Alexa🛟

Ezt a "mentőöv"-et azoknak dobom (a riogatást is elhessentve, hogy a Win10 befuccsol<sup> tömeghír, hogy 2025 ősztől nem támogatja a gyártó /ez így nem teljesen igaz)</sup>), akik magyarul beszélnek, akik nem szeretik, hogy <tt>M</tt>á<tt>S</tt> beleszól abba, mit, hogyan csinálnak a saját tulajdonú, SZEMÉLYI számítógépükkel.
Ez a <CODE><b><i>WINDOWS 11 TELEPÍTŐ</i></b></CODE> magyarul beszél, magyar Windows 11 Pro rendszert épít, úgy, hogy semmilyen nyomkövető, vagy reklám program nem települ vele, <b>~50 haszontalan program lett kiiktatva a telepítőből👌, miközben megmaradtak az eredeti Microsoft Windows eredeti jó élményei...</b>. 
Nem igényli a kötelező hardvert/szoftvert, régi (akár 10-15 éves) számítógépre (PC, laptop, notebook) is települ, és stabilan használható. (Ajánlott minimumok: 8 GB RAM, 64 GB tárhely. 64 bit-es proci kell, de ezt már tudják a 10+éves gépek is...)
A "csupasz" Windows használat megkezdése után találsz benne egy mappát, a tartalmát felhasználva könnyedén - megint csak "egyenesen, magyarul" - telepítheted kedvenc programjaidat.
<a href="https://drive.google.com/drive/folders/1PjNjLoUtQdGAW1A2i_0EOtZBQQqCw1Ox?usp=sharing"><tt> 🪟 A Win11H_Alexa.ISO telepítőt ide kattintva töltheted le ❤️ 🪂 </tt></a>

<tt>❗A telepítőhöz használt forrás: Microsoft Windows 11 Pro 24H2.<sup>(eredeti Microsoft kiadás, build: 26100 1742)</sup></tt>
<hr>
#🛠️🛠️🛠️

1. Töltsd le a Balena Etchert: https://etcher.balena.io/ zöld Download Etcher gomb,<sub> vagy közvetlenül: https://github.com/balena-io/etcher/releases/download/v2.1.0/balenaEtcher-2.1.0.Setup.exe | *NE használj helyette ehhez a telepítőhöz ⛔ Rufust!!! Etcher helyett jó a Ventoy - leírása lejjebb* </sub>.

2. Csatolj egy legalább 8 GB-os USB tárolót (pendrive, ne legyen rajta semmi fontos!) a gépedhez, indítsd el a Balena Etcher-t
   
3. Válaszd ki az Etcher-ben a Flash from File-t, tallózd be a fentről letöltött <tt>Win11H_Alexa ISO</tt>-t. A Select Target gombbal válaszd ki írásra az USB tárolód. Flash gombbal indítsd el az ISO kiírását, azaz indítható Windows telepítő készítést az USB-re (kb 3 perc az írás).
   
4. Csatold az USB tárolót ahhoz a géphez, amelyikre Windowst akarsz telepíteni.
   
5. Indítsd el a gépet Boot menü-vel (ez legtöbb gépen a gépgyártó logó megjelenésekor <b><tt>Esc</tt>, <tt>F8</tt>, <tt>F9</tt>, <tt>F10</tt></b> billentyűvel megy, ha mégsem, keress rá a te gépedhez a neten).
   
6. Válaszd ki betöltéshez (boot) az USB tárolót, elindul a Windows 11 telepítő.
    
7. Haladj végig a magyar nyelvű telepítő egyszerű lépésein. KÉSZ. (Időigény: 20-30 perc átlagos internet sebesség és régebbi proci + SSD esetén,  a <b>telepítéshez online internetkapcsolat - kábel, vagy wifi - erősen ajánlott (hiábavaló a sok ellentétes 5let)</b>. A teljes folyamat ideje net sebesség és géperő függvénye.
   
* Ha ventoy-t használnál Etcher helyett, azt innen töltsd le: https://sourceforge.net/projects/ventoy/files/v1.1.05/ventoy-1.1.05-windows.zip/download , bontsd ki a zip-et, telepítsd (Ventoy2Disk.exe) az útmutató szerint az USB tárolóra, majd egyszerűen másold rá az ISO-t is, és folytasd a 4. ponttól.*


  *A telepítésből KIMARAD:*
- secureboot, és TPM2 ellenőrzés;
- Windows nyomkövető és reklám programok, egyéb "hulladék" ~50 szoftver, lásd a csatolt fájlban; (⛔ emiatt felesleges és instabilitást okozhat utólag külső debloating és disable telemetry, meg hasonló parancs programok használata, pl. "neonity xtremeshell", "raphire", "christitus")
- online Microsoft fiók (az "élénk online érdeklődés" korlátozásához) - helyette helyi fióknév (rendszergazda) választás és létrehozás történik;
- a telepítőben nincsenek specifikus drivertelepítők /ahogy a MS telpítőben sincs/, erősen ajánlott ezeket a te géped gyártó honlapjáról előre beszerezve szintén az USB-re másolni, majd azonnal telepíteni az első indítás után)

  *Ami BENNE van:*
- .Alexa könyvtár nagyszerű és/vagy egyszerű programok telepítésének lehetőségével az első bejelentkezés után (NEM KÖTELEZ TÉGED semmire!!! Törölhető is 1 kattintással).
Ennyi.

   *💥Telepítés UTÁN:*

✝ Update: 

DirectX - https://download.microsoft.com/download/1/7/1/1718ccc4-6315-4d8e-9543-8e28a4e18c4c/dxwebsetup.exe <sup>(ezt 1 klikkel 1-2 másodperc alatt letöltheted a Microsofttól, rákattintva máris futtathatod)</sup> 

Driver Booster - https://www.iobit.com/en/driver-booster.php 

*Erősen javasolt DirctX és Driver Booster update-kkel kezdeni a rendszer telepítés után...* <sub> Gyors, pontos driver telepítéshez, mielőtt aktiválná magát a rendszerbe épített Windows Update és teledobálná hibás driverekkel a Windowst.) ... ha még nem tetted meg, javasolt futtatni a dxdiag.exe -t (jobb klikk a Startmenün - Futtatás - <tt>dxdiag</tt> begépelés - Enter), ellenőrizendő, hogy jelez-e hibát és ugyanezért megnézni az Eszközkezelőt is (jobb klikk a Startmenün, Eszközkezelő).</sub>


<tt>Sikeresen tesztelve az alábbi gépen: intel i3 7.gen CPU, integrált GPU, 16 GB DDR4 RAM, 64 GB SSD tárhely.✅</tt>

<sub>⚠Bátrabb, tapasztalt felhasználók: meglévő Windows rendszeren 2. rendszernek (dual boot) telepíthető úgy is az Alexa, hogy az ISO fájlt csatlakoztatva virt. meghajtóra egy kb. 10 GB-os erre a célra kreált FAT32 partícióra másolva a teljes tartalmát egyszerűen futtatjuk a ISO tartalomban lévő setup.exe -t a meglévő Windows-ból. Ezzel elindul az új telepítési folyamat (a régi Windows megtartásával), a telepítőben zsugorítani kell a meglévő régi Windows partíciót, és az így kreált új, üres partícióra (javasolt min.64GB) telepíteni ezt. Gép indításkor 2 Windows között lehet majd választani.</sub>
<hr>

<sub>A szerző nem informatikai szakember, de 30 éve foglalkozik Windows-sal, elkötelezett a "személyreszóló", de "mókolatlan" Windows telepítéshez biztonságos, stabil eszközök és módszerek használatára, ilyen ez a Windows is.</sub>
<sub>(😎A telepítő ingyenes, és az is marad!💝)</sub>
