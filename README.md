# Windows11H_Alexa 
![Alexa-ikon](https://github.com/user-attachments/ashttps://drive.google.com/drive/folders/1PjNjLoUtQdGAW1A2i_0EOtZBQQqCw1Ox?usp=sharingsets/bc2fa4d1-9b41-4b69-b087-dc33e3a1bbf6)

Ez azoknak szól, akik magyarul beszélnek, akik nem szeretik, hogy <tt>M</tt>á<tt>S</tt> beleszól abba, mit, hogyan csinálnak a saját, személyi számítógépükkel.
Az itt írt Windows telepítő magyarul beszél, magyar Windows 11 Pro rendszer telepítést tesz lehetővé, úgy, hogy semmilyen MS vagy más nyomkövető, vagy reklám program nem települ vele. 
Nem igényli az egyébként kötelező "secureboot"-ot, vagy "TPM2"-t, régi (akár 10-12 éves) számítógépre (PC, laptop, notebook) is települ, és stabilan használható. (Ajánlott minimumok: 8 GB RAM, 64 GB tárhely. 64 bit-es proci kell, de ezt már tudják a 10+éves gépek is...)
A "csupasz" Windows használat megkezdése után találsz benne egy Alexa mappát, a tartalmát felhasználva könnyedén - magyarul - telepítheted kedvenc programjaidat.
<a href="https://drive.google.com/drive/folders/1PjNjLoUtQdGAW1A2i_0EOtZBQQqCw1Ox?usp=sharing">A Win11H_Alexa.ISO telepítőt ide kattintva töltheted le</a>

<hr>
1. Töltsd le a Balena Etchert (letöltőhely: https://etcher.balena.io/ zöld Download Etcher gomb, vagy közvetlenül: https://github.com/balena-io/etcher/releases/download/v2.1.0/balenaEtcher-2.1.0.Setup.exe ).
2. Csatolj egy legalább 8 GB-os USB tárolót (pendrive) a gépedhez, indítsd el a Balena Etcher-t
3. Válaszd ki az Echer-ben a Flash from File-t, tallózd be a Win11H_Alexa.ISO-t az íráshoz. A Select Target gombbal válaszd ki írásra az USB tárolód. Flash gombbal megkezdheted az ISO kiírását, azaz indítható Windows telepítő készítést az USB-re.
4. Csatold az USB tárolót ahhoz a géphez, amelyikre Windowst akarsz telepíteni.
5. Indítsd el a gépet Boot menü-vel (ez legtöbb gépen a gépgyártó logó megjelenésekor Esc, F8, F9, F10 billentyűvel megy, ha mégsem, keress rá a te gépedhez a neten).
6. Válaszd ki betöltéshez (boot) az USB tárolót, elindul a Windows 11 telepítő.
7. Haladj végig a magyar nyelvű telepítő egyszerű lépésein. KÉSZ. (Időigény: 20-30 perc átlagos internet sebesség és régebbi proci + SSD esetén,  a <b>telepítéshez internetkapcsolat - kábel, vagy wifi - kell</b>.)

A telepítéshez használt forrás: Windows 11 Pro 24H2. (2025.ápr.)
Ami kimarad a telepítésből, annak érdekében, hogy régebbi gépen is működjön és ne legyen tele felesleges nyomkövető és reklám programokkal: 
- secureboot, és TPM2 ellenőrzés;
- Windows nyomkövető és reklám programok kihagyása a telepítésből;
- online Microsoft fiók belépés mellőzése (a Microsoft online "érdeklődésének" korlátozásához), helyi fióknév választás és létrehozás (rendszergazda);
Ami benne van:
- .Alexa könyvtár a rendszeren nagyszerű alap programok telepítésének lehetőségéhez az első bejelentkezés után.
Ennyi.

Tesztelve az alábbi gépen: proci: intel i3 CPU, integrált GPU, 16 GB DDR4 RAM, 64 GB SSD ROM.
