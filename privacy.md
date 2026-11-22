# Vault13 – Privacy Policy

Effective date: 22 November 2026

Vault13 is a private vault for photos, videos, PDF documents and passwords, for iPhone and iPad, made by Speeder2k13.

## The short version
Vault13 does not collect any data. There is no account, no analytics, no advertising and no third-party SDK. The app does not connect to any server of ours. Nothing you store in Vault13 is sent to us.

## What you keep in the vault
- Everything you import, shoot, scan or type into Vault13 (photos, videos, PDF documents, password entries) is encrypted on your device with AES-256 before it is saved. Thumbnails, album names, folder names and document names are encrypted too.
- Documents and the password notebook exist only in the real vault, never in the decoy vault.
- Information inside a photo or video file (date, camera, location) stays inside the encrypted file. Vault13 only shows it to you, in the details panel.
- If a photo or video already contains a location, Vault13 copies its coordinates into the encrypted album list when you import it, so it can appear on the map in Browse. The only time Vault13 reads your current location is the optional intruder log setting described below.

## Your iCloud Drive backup
- If you choose a backup folder, an encrypted copy of your photos, videos, documents and password notebook is stored in your own iCloud Drive, in the folder you picked. iCloud is provided by Apple under Apple's privacy policy. We have no access to it, and the files cannot be opened without your vault key. The files there have names that say nothing about their content.
- The vault's files on the device are left out of the iPhone or iPad device backup, so this folder is the only backup.
- If you use the same folder on several devices, Vault13 merges the changes made on each of them automatically. The encrypted lists in the folder also hold a random identifier created by the app for each device and the time of each change. They are used only to keep your devices in sync.
- Your PINs and your settings are not synced: they stay on each device.

## PINs, vault keys and recovery code
- Your PINs are not stored anywhere. Each vault has its own key, kept in the iOS Keychain on your device and locked with that vault's PIN: it unlocks only when you type the PIN.
- The recovery code is kept in the Keychain too, locked with the real vault's key: it can be seen only inside the open real vault.
- To let you restore the vault on another device, the backup folder also holds a copy of the vault keys, encrypted with your recovery code. It cannot be opened without that code.
- The count of wrong PIN attempts, and any pause that follows them, is kept in the iOS Keychain too.
- We never receive your PINs, your keys or your recovery code.

## Passwords and the clipboard
- A password or code you copy from the password notebook is placed on the clipboard of this device only (it does not go to your other devices through Universal Clipboard) and is removed automatically after 2 minutes.
- Magic card: if you turn it on for an entry, that one entry (name, username, password) is kept in the app's memory for 1 minute (2 at most), so you can copy it from the locked vault door. It is never written to disk and disappears when it ends, on any wrong PIN and when the app is closed.
- Vault13 has no AutoFill and does not read passwords from other apps or websites.

## Keyboards
Vault13 allows only the Apple keyboard. Keyboards installed from the App Store do not appear inside the app, so they cannot read your passwords, PINs or recovery code.

## Camera
Vault13 uses the camera in four cases:
- Private camera: when you tap the camera button, you take photos or record videos that go straight into your encrypted vault. They are never saved to the Photos library.
- Document scanning: the iOS document scanner turns the pages you scan into a PDF that is saved encrypted in your vault.
- Intruder log photo: this option is off by default. If you turn it on, the front camera takes one photo after every third wrong PIN entered on the vault door. The photo is encrypted and kept in the Intruders album of your vault, on that device only: this album is not added to the iCloud backup and does not appear on your other devices. A photo you move to another album is backed up and synced like any other.
- QR transfer: when you choose Receive with QR, the camera reads the code shown on your other device. No picture is taken or saved.

Camera photos, videos and scans are never sent anywhere. You can withdraw camera access at any time in iOS Settings > Vault13.

## Microphone
The microphone is used only while you record a video with the private camera. The sound is part of that video, which is stored encrypted in your vault.

## Intruder log
Every wrong PIN entered on the vault door is saved in a log with the date, the time and the digits that were typed. The log is encrypted, can be read only inside the open real vault, stays on your device, holds at most 200 entries and can be cleared in Settings > Intruder Log.

Location on wrong PIN: this option is off by default. If you turn it on and allow location access while using the app, Vault13 reads the device's location once after each wrong PIN and saves the coordinates in the same encrypted log. If an intruder photo is taken, it keeps the same coordinates in the encrypted album list, like any other photo with a location. The coordinates are never sent to us or to anyone else. You can turn the option off in Settings > Intruder Log and withdraw location access in iOS Settings > Vault13.

## Map
The maps in Browse and in the intruder log are provided by Apple (MapKit). When you open one, map images for the area on screen are downloaded from Apple. Vault13 does not send your photos or their coordinates; Apple may see which map area is displayed, under Apple's privacy policy.

## Photo library access
Vault13 asks for access to Photos only to import the items you select, to save items back to Photos when you ask, and, if you turn this option on, to delete the originals after import. iOS asks you to confirm every deletion.

## Files, paste and drag and drop
Vault13 reads only the files you pick in the Files app, the photo or video you choose to paste, and the items you drag into an album. Documents you send out of the vault (as files, .zip, package or QR) leave it only when and where you choose.

## Motion
While the vault is open, Vault13 reads the device's position to lock the vault when you place it face down. This is processed on the device and is not stored. You can turn it off in Settings > Security.

## Encrypted packages
You can pack photos, videos or documents into a single file protected by a password you choose, and share it yourself (AirDrop, Files). The file is encrypted with AES-256 on your device. Vault13 does not store the password and does not send the file anywhere: you decide where it goes. Anyone who has both the file and the password can open it in Vault13. The name of the package file can be seen without the password. Passwords from the notebook are never put in a package.

## QR transfer over Wi-Fi
You can send photos, videos or documents directly to another device that runs Vault13. One device shows a QR code and the other scans it. The items are packed into an encrypted file (AES-256) with a one-time key that exists only in that QR code, and they travel directly between the two devices over your local Wi-Fi network. They do not pass through any server, ours or anyone else's. iOS asks for Local Network access the first time you use it; you can withdraw it at any time in iOS Settings > Vault13.

## Settings
Your preferences (language, sound, import quality and similar) are stored only on your device.

## Deleting your data
- Settings > Reset > "Erase the vault from this device" removes everything from the device.
- "Erase everything, including the iCloud backup" also deletes the Vault13 backup folder.
- Deleting the app removes all local data. You can also delete the Vault13 folder from iCloud Drive in the Files app.
- A document or password entry you delete is deleted from all your devices and from the iCloud backup.

## Children
Vault13 does not knowingly collect information from anyone, including children, because it does not collect information at all.

## Changes
If this policy changes, the new version will be published on this page with a new effective date.

## Contact
ionut00@gmail.com

---

# Vault13 – Politica de confidențialitate (română)

Data intrării în vigoare: 22 noiembrie 2026

Vault13 este un seif privat pentru poze, clipuri, documente PDF și parole, pentru iPhone și iPad, făcut de Speeder2k13.

## Pe scurt
Vault13 nu colectează date. Nu are cont, analiză statistică, reclame sau SDK-uri externe. Aplicația nu se conectează la niciun server al nostru. Nimic din ce păstrezi în Vault13 nu ajunge la noi.

## Ce ții în seif
- Tot ce imporți, fotografiezi, scanezi sau scrii în Vault13 (poze, clipuri, documente PDF, intrări din carnetul de parole) e criptat AES-256 pe dispozitiv, înainte de salvare. Miniaturile și numele albumelor, ale dosarelor și ale documentelor sunt și ele criptate.
- Documentele și carnetul de parole există doar în seiful real, niciodată în seiful decoy.
- Informațiile din fișier (data, aparatul, locația) rămân în fișierul criptat. Vault13 doar ți le arată, în fereastra de detalii.
- Dacă o poză sau un clip conține deja o locație, la import Vault13 copiază coordonatele în lista criptată de albume, ca să poată apărea pe harta din Răsfoiește. Singura situație în care Vault13 îți citește locația curentă este opțiunea din jurnalul de intruși, descrisă mai jos.

## Backup-ul din iCloud Drive
- Dacă alegi un folder de backup, o copie criptată a pozelor, clipurilor, documentelor și a carnetului de parole stă în propriul tău iCloud Drive, în folderul ales. iCloud e oferit de Apple, conform politicii Apple. Noi nu avem acces la el, iar fișierele nu pot fi deschise fără cheia seifului. Fișierele de acolo au nume care nu spun nimic despre conținut.
- Fișierele seifului de pe dispozitiv nu intră în backup-ul iPhone-ului sau al iPad-ului, deci acest folder e singurul backup.
- Dacă folosești același folder pe mai multe dispozitive, Vault13 contopește singur schimbările făcute pe fiecare. Listele criptate din folder conțin și un identificator aleatoriu, creat de aplicație pentru fiecare dispozitiv, și ora fiecărei schimbări. Sunt folosite doar pentru sincronizare.
- PIN-urile și setările nu se sincronizează: rămân pe fiecare dispozitiv.

## PIN-urile, cheile seifului și codul de recuperare
- PIN-urile nu sunt păstrate nicăieri. Fiecare seif are cheia lui, ținută în Keychain-ul iOS de pe dispozitiv și încuiată cu PIN-ul acelui seif: se deschide doar când tastezi PIN-ul.
- Codul de recuperare stă tot în Keychain, încuiat cu cheia seifului real: se vede doar din seiful real deschis.
- Ca să poți restaura seiful pe alt dispozitiv, în folderul de backup stă și o copie a cheilor seifului, criptată cu codul tău de recuperare. Nu poate fi deschisă fără acel cod.
- Numărul de PIN-uri greșite și pauza care le urmează stau tot în Keychain-ul iOS.
- Noi nu primim niciodată PIN-urile, cheile sau codul tău de recuperare.

## Parolele și clipboardul
- O parolă sau un cod copiat din carnet ajunge doar în clipboardul acestui dispozitiv (nu trece pe celelalte dispozitive prin Clipboard universal) și dispare singur după 2 minute.
- Cardul magic: dacă îl pornești pentru o intrare, acea singură intrare (nume, utilizator, parolă) stă în memoria aplicației 1 minut (cel mult 2), ca să o poți copia din fața ușii închise. Nu e scrisă niciodată pe disc și dispare când se termină, la orice PIN greșit și când aplicația e închisă.
- Vault13 nu are completare automată și nu citește parole din alte aplicații sau site-uri.

## Tastaturile
În Vault13 merge doar tastatura Apple. Tastaturile instalate din App Store nu apar în aplicație, deci nu pot citi parolele, PIN-urile sau codul de recuperare.

## Camera
Vault13 folosește camera în patru situații:
- Camera privată: când apeși butonul cu cameră, faci poze sau filmezi direct în seiful criptat. Ele nu ajung niciodată în aplicația Poze.
- Scanarea documentelor: scanerul de documente din iOS face din paginile scanate un PDF salvat criptat în seif.
- Poza din jurnalul de intruși: opțiunea e oprită implicit. Dacă o pornești, camera frontală face o poză la fiecare a treia încercare greșită de PIN pe ușa seifului. Poza e criptată și păstrată în albumul Intruși din seiful tău, doar pe acel dispozitiv: acest album nu intră în backup-ul din iCloud și nu apare pe celelalte dispozitive ale tale. O poză mutată în alt album intră în backup și se sincronizează ca oricare alta.
- Transferul cu QR: când alegi Primește cu QR, camera citește codul arătat de celălalt dispozitiv. Nu se face și nu se salvează nicio poză.

Pozele, clipurile și scanările făcute cu camera nu sunt trimise nicăieri. Poți retrage oricând accesul la cameră din Configurări > Vault13.

## Microfonul
Microfonul e folosit doar cât filmezi cu camera privată. Sunetul face parte din clip, care e păstrat criptat în seif.

## Jurnalul de intruși
Fiecare PIN greșit introdus pe ușa seifului e salvat într-un jurnal, cu data, ora și cifrele tastate. Jurnalul e criptat, poate fi citit doar din seiful real deschis, rămâne pe dispozitiv, păstrează cel mult 200 de înregistrări și poate fi șters din Setări > Jurnal intruși.

Poziția la PIN greșit: opțiunea e oprită implicit. Dacă o pornești și permiți accesul la locație cât folosești aplicația, Vault13 citește o singură dată poziția dispozitivului după fiecare PIN greșit și salvează coordonatele în același jurnal criptat. Dacă se face și poza de intrus, ea păstrează aceleași coordonate în lista criptată de albume, ca orice poză cu locație. Coordonatele nu sunt trimise niciodată nouă sau altcuiva. Poți opri opțiunea din Setări > Jurnal intruși și poți retrage accesul la locație din Configurări > Vault13.

## Harta
Hărțile din Răsfoiește și din jurnalul de intruși sunt oferite de Apple (MapKit). Când deschizi una, imaginile hărții pentru zona de pe ecran se descarcă de la Apple. Vault13 nu trimite pozele sau coordonatele lor; Apple poate vedea ce zonă a hărții e afișată, conform politicii Apple.

## Accesul la Poze
Vault13 cere acces la Poze doar ca să importe ce alegi tu, să salveze înapoi în Poze la cererea ta și, dacă pornești opțiunea, să șteargă originalele după import. iOS îți cere confirmarea la fiecare ștergere.

## Fișiere, lipire și tragere
Vault13 citește doar fișierele pe care le alegi în aplicația Fișiere, poza sau clipul pe care alegi să le lipești și elementele pe care le tragi într-un album. Documentele pe care le trimiți din seif (ca fișiere, .zip, pachet sau QR) ies din el doar când și unde alegi tu.

## Mișcarea dispozitivului
Cât seiful e deschis, Vault13 citește poziția dispozitivului ca să blocheze seiful când îl așezi cu ecranul în jos. Totul se întâmplă pe dispozitiv și nu se salvează nimic. Poți opri funcția din Setări > Securitate.

## Pachete criptate
Poți pune poze, clipuri sau documente într-un singur fișier, protejat cu o parolă aleasă de tine, pe care îl trimiți tu (AirDrop, Fișiere). Fișierul e criptat AES-256 pe dispozitiv. Vault13 nu păstrează parola și nu trimite fișierul nicăieri: tu hotărăști unde ajunge. Cine are și fișierul, și parola îl poate deschide în Vault13. Numele fișierului se vede și fără parolă. Parolele din carnet nu intră niciodată într-un pachet.

## Transfer cu QR prin Wi-Fi
Poți trimite poze, clipuri sau documente direct către alt dispozitiv pe care rulează Vault13. Un dispozitiv arată un cod QR, iar celălalt îl scanează. Elementele sunt puse într-un fișier criptat (AES-256), cu o cheie de unică folosință care există doar în acel cod QR, și trec direct de la un dispozitiv la altul, prin rețeaua ta Wi-Fi locală. Nu trec prin niciun server, nici al nostru, nici al altcuiva. La prima folosire iOS cere acces la Rețea locală; îl poți retrage oricând din Configurări > Vault13.

## Setările
Preferințele tale (limbă, sunet, calitatea importului și altele) stau doar pe dispozitiv.

## Ștergerea datelor
- Setări > Resetare > „Șterge seiful de pe acest dispozitiv” șterge tot de pe dispozitiv.
- „Șterge tot, inclusiv backup-ul din iCloud” șterge și folderul de backup Vault13.
- Ștergerea aplicației șterge toate datele locale. Poți șterge și folderul Vault13 din iCloud Drive, în aplicația Fișiere.
- Un document sau o intrare din carnet pe care o ștergi dispare de pe toate dispozitivele tale și din backup-ul din iCloud.

## Copiii
Vault13 nu colectează informații de la nimeni, deci nici de la copii.

## Modificări
Dacă politica se schimbă, noua versiune apare pe această pagină, cu o nouă dată de intrare în vigoare.

## Contact
ionut00@gmail.com
