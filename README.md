# Windows11H_Alexa🛟

Ezt a "mentőöv"-et azoknak dobom (a riogatást is elhessentve, hogy a Win10 befuccsol<sup>*2025 ősztől nem támogatja a gyártó</sup>), akik magyarul beszélnek, akik nem szeretik, hogy <tt>M</tt>á<tt>S</tt> beleszól abba, mit, hogyan csinálnak a saját tulajdonú, SZEMÉLYI számítógépükkel.
Ez a <CODE><b><i>WINDOWS 11 TELEPÍTŐ</i></b></CODE> magyarul beszél, magyar Windows 11 Pro rendszert épít, úgy, hogy semmilyen nyomkövető, vagy reklám program nem települ vele, <b>~50 haszontalan program lett kiiktatva a telepítőből👌, miközben megmaradtak az eredeti Microsoft Windows eredeti jó élményei...</b>. 
Nem igényli a kötelező hardvert/szoftvert, régi (akár 10-15 éves) számítógépre (PC, laptop, notebook) is települ, és stabilan használható. (Ajánlott minimumok: 8 GB RAM, 64 GB tárhely. 64 bit-es proci kell, de ezt már tudják a 10+éves gépek is...)
A "csupasz" Windows használat megkezdése után találsz benne egy mappát, a tartalmát felhasználva könnyedén - megint csak "egyenesen, magyarul" - telepítheted kedvenc programjaidat.
<a href="https://drive.google.com/drive/folders/1PjNjLoUtQdGAW1A2i_0EOtZBQQqCw1Ox?usp=sharing"><tt>🪟A Win11H_Alexa.ISO telepítőt ide kattintva töltheted le❤️🪂</tt></a>

<hr>
🛠️🛠️🛠️

1. Töltsd le a Balena Etchert (letöltőhely: https://etcher.balena.io/ zöld Download Etcher gomb, vagy közvetlenül: https://github.com/balena-io/etcher/releases/download/v2.1.0/balenaEtcher-2.1.0.Setup.exe <sub>most kivételesen, ha szoktad is, ne használj Rufust, de ha ismered, akkor ajánlott a ventoy progi is*.</sub>).

2. Csatolj egy legalább 8 GB-os USB tárolót (pendrive, ne legyen rajta semmi fontos!) a gépedhez, indítsd el a Balena Etcher-t
   
3. Válaszd ki az Etcher-ben a Flash from File-t, tallózd be a fentről letöltött <tt>Win11H_Alexa ISO</tt>-t. A Select Target gombbal válaszd ki írásra az USB tárolód. Flash gombbal megkezdheted az ISO kiírását, azaz indítható Windows telepítő készítést az USB-re (kb 3 perc).
   
4. Csatold az USB tárolót ahhoz a géphez, amelyikre Windowst akarsz telepíteni.
   
5. Indítsd el a gépet Boot menü-vel (ez legtöbb gépen a gépgyártó logó megjelenésekor <b><tt>Esc</tt>, <tt>F8</tt>, <tt>F9</tt>, <tt>F10</tt></b> billentyűvel megy, ha mégsem, keress rá a te gépedhez a neten).
   
6. Válaszd ki betöltéshez (boot) az USB tárolót, elindul a Windows 11 telepítő.
    
7. Haladj végig a magyar nyelvű telepítő egyszerű lépésein. KÉSZ. (Időigény: 20-30 perc átlagos internet sebesség és régebbi proci + SSD esetén,  a <b>telepítéshez internetkapcsolat - kábel, vagy wifi - kell</b>. A teljes folyamat ideje net sebesség és géperő függvénye.
   
8. Ha ventoy-t használnál Etcher helyett, azt innen töltsd le: https://sourceforge.net/projects/ventoy/files/v1.1.05/ventoy-1.1.05-windows.zip/download , bontsd ki a zip-et, telepítsd (a programfájllal) az útmutató szerint az USB tárolóra, majd egyszerűen másold az ISO-t is ugyanoda, és folytasd a 4. ponttól.

<tt>A telepítőhöz használt forrás: Microsoft Windows 11 Pro 24H2.<sup>(eredeti Microsoft kiadás, build: 26100 1742)</sup></tt>

A telepítésből KIMARAD: 
- secureboot, és TPM2 ellenőrzés;
- Windows nyomkövető és reklám programok, egyéb "hulladék" (~50 szoftver!);
- online Microsoft fiók (a Microsoft "élénk érdeklődésének" korlátozásához) - helyette helyi fióknév (rendszergazda) választás és létrehozás történik;

Ami BENNE van:
- .Alexa könyvtár nagyszerű és/vagy egyszerű programok telepítésének lehetőségével az első bejelentkezés után (NEM KÖTELEZ TÉGED semmire!!! Törölhető is 1 kattintással).
Ennyi.
<sub>(A telepítő ingyenes, és az is marad!)</sub>

<tt>Sikeresen tesztelve az alábbi gépen: intel i3 7.gen CPU, integrált GPU, 16 GB DDR4 RAM, 64 GB SSD tárhely.</tt>
