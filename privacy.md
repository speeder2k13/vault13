# Vault13 – Privacy Policy

Effective date: 14 November 2026

Vault13 is a private photo and video vault for iPhone and iPad, made by Speeder2k13.

## The short version
Vault13 does not collect any data. There is no account, no analytics, no advertising and no third-party SDK. The app does not connect to any server of ours. Nothing you store in Vault13 is sent to us.

## Your photos and videos
- Everything you import or shoot is encrypted on your device with AES-256 before it is saved. Thumbnails and album names are encrypted too.
- Information inside a photo or video file (date, camera, location) stays inside the encrypted file. Vault13 only shows it to you, in the details panel.
- If you choose a backup folder, an encrypted copy is stored in your own iCloud Drive, in the folder you picked. iCloud is provided by Apple under Apple's privacy policy. We have no access to it, and the files cannot be opened without your vault key. The vault's files on the device are left out of the iPhone or iPad device backup, so this folder is the only backup.
- If a photo or video already contains a location, Vault13 copies its coordinates into the encrypted album list when you import it, so it can appear on the map in Search. You can remove it at any time (Search > Select > Location). The only time Vault13 reads your current location is the optional intruder log setting described below.
- If you use the same folder on several devices, the encrypted album list also holds a random identifier created by the app for each device. It is used only to keep those devices in sync.

## PINs, vault key and recovery code
- Your PINs, the vault key and the recovery code are stored in the iOS Keychain on your device.
- To let you restore the vault on another device, the backup folder also holds a copy of the vault key, encrypted with your recovery code. It cannot be opened without that code.
- The count of wrong PIN attempts, and any pause that follows them, is kept in the iOS Keychain too.
- We never receive your PINs, your key or your recovery code.

## Camera
Vault13 uses the camera in two cases:
- Private camera: when you tap the camera button, you take photos or record videos that go straight into your encrypted vault. They are never saved to the Photos library.
- Intruder log photo: this option is off by default. If you turn it on, the front camera takes one photo after every third wrong PIN entered on the vault door. The photo is encrypted and kept in the Intruders album of your vault.

Camera photos and videos are never sent anywhere. You can withdraw camera access at any time in iOS Settings > Vault13.

## Microphone
The microphone is used only while you record a video with the private camera. The sound is part of that video, which is stored encrypted in your vault.

## Intruder log
Every wrong PIN entered on the vault door is saved in a log with the date, the time and the digits that were typed. The log is encrypted, stays on your device, holds at most 200 entries and can be cleared in Settings > Intruder Log.

Location on wrong PIN: this option is off by default. If you turn it on and allow location access while using the app, Vault13 reads the device's location once after each wrong PIN and saves the coordinates in the same encrypted log. If an intruder photo is taken, it keeps the same coordinates in the encrypted album list, like any other photo with a location. The coordinates are never sent to us or to anyone else. You can turn the option off in Settings > Intruder Log and withdraw location access in iOS Settings > Vault13.

## Map
The maps in Search and in the intruder log are provided by Apple (MapKit). When you open one, map images for the area on screen are downloaded from Apple. Vault13 does not send your photos or their coordinates; Apple may see which map area is displayed, under Apple's privacy policy.

## Photo library access
Vault13 asks for access to Photos only to import the items you select, to save items back to Photos when you ask, and, if you turn this option on, to delete the originals after import. iOS asks you to confirm every deletion.

## Files, paste and drag and drop
Vault13 reads only the files you pick in the Files app, the photo or video you choose to paste, and the items you drag into an album.

## Motion
While the vault is open, Vault13 reads the device's position to lock the vault when you place it face down. This is processed on the device and is not stored. You can turn it off in Settings > Security.

## Encrypted packages
You can pack photos and videos into a single file protected by a password you choose, and share it yourself (AirDrop, Files). The file is encrypted with AES-256 on your device. Vault13 does not store the password and does not send the file anywhere: you decide where it goes. Anyone who has both the file and the password can open it in Vault13.

## Settings
Your preferences (language, sound, import quality and similar) are stored only on your device.

## Deleting your data
- Settings > Reset > "Erase the vault from this device" removes everything from the device.
- "Erase everything, including the iCloud backup" also deletes the Vault13 backup folder.
- Deleting the app removes all local data. You can also delete the Vault13 folder from iCloud Drive in the Files app.

## Children
Vault13 does not knowingly collect information from anyone, including children, because it does not collect information at all.

## Changes
If this policy changes, the new version will be published on this page with a new effective date.

## Contact
ionut00@gmail.com

---

# Vault13 – Politica de confidențialitate (română)

Data intrării în vigoare: 14 noiembrie 2026

Vault13 este un seif privat pentru poze și clipuri, pentru iPhone și iPad, făcut de Speeder2k13.

## Pe scurt
Vault13 nu colectează date. Nu are cont, analiză statistică, reclame sau SDK-uri externe. Aplicația nu se conectează la niciun server al nostru. Nimic din ce păstrezi în Vault13 nu ajunge la noi.

## Pozele și clipurile tale
- Tot ce imporți sau fotografiezi e criptat AES-256 pe dispozitiv, înainte de salvare. Miniaturile și numele albumelor sunt și ele criptate.
- Informațiile din fișier (data, aparatul, locația) rămân în fișierul criptat. Vault13 doar ți le arată, în fereastra de detalii.
- Dacă alegi un folder de backup, o copie criptată stă în propriul tău iCloud Drive, în folderul ales. iCloud e oferit de Apple, conform politicii Apple. Noi nu avem acces la el, iar fișierele nu pot fi deschise fără cheia seifului. Fișierele seifului de pe dispozitiv nu intră în backup-ul iPhone-ului sau al iPad-ului, deci acest folder e singurul backup.
- Dacă o poză sau un clip conține deja o locație, la import Vault13 copiază coordonatele în lista criptată de albume, ca să poată apărea pe harta din Căutare. Le poți șterge oricând (Căutare > Selectează > Locație). Singura situație în care Vault13 îți citește locația curentă este opțiunea din jurnalul de intruși, descrisă mai jos.
- Dacă folosești același folder pe mai multe dispozitive, lista criptată de albume conține și un identificator aleatoriu, creat de aplicație pentru fiecare dispozitiv. E folosit doar pentru sincronizare.

## PIN-urile, cheia seifului și codul de recuperare
- PIN-urile, cheia seifului și codul de recuperare stau în Keychain-ul iOS de pe dispozitiv.
- Ca să poți restaura seiful pe alt dispozitiv, în folderul de backup stă și o copie a cheii seifului, criptată cu codul tău de recuperare. Nu poate fi deschisă fără acel cod.
- Numărul de PIN-uri greșite și pauza care le urmează stau tot în Keychain-ul iOS.
- Noi nu primim niciodată PIN-urile, cheia sau codul tău de recuperare.

## Camera
Vault13 folosește camera în două situații:
- Camera privată: când apeși butonul cu cameră, faci poze sau filmezi direct în seiful criptat. Ele nu ajung niciodată în aplicația Poze.
- Poza din jurnalul de intruși: opțiunea e oprită implicit. Dacă o pornești, camera frontală face o poză la fiecare a treia încercare greșită de PIN pe ușa seifului. Poza e criptată și păstrată în albumul Intruși din seiful tău.

Pozele și clipurile făcute cu camera nu sunt trimise nicăieri. Poți retrage oricând accesul la cameră din Configurări > Vault13.

## Microfonul
Microfonul e folosit doar cât filmezi cu camera privată. Sunetul face parte din clip, care e păstrat criptat în seif.

## Jurnalul de intruși
Fiecare PIN greșit introdus pe ușa seifului e salvat într-un jurnal, cu data, ora și cifrele tastate. Jurnalul e criptat, rămâne pe dispozitiv, păstrează cel mult 200 de înregistrări și poate fi șters din Setări > Jurnal intruși.

Poziția la PIN greșit: opțiunea e oprită implicit. Dacă o pornești și permiți accesul la locație cât folosești aplicația, Vault13 citește o singură dată poziția dispozitivului după fiecare PIN greșit și salvează coordonatele în același jurnal criptat. Dacă se face și poza de intrus, ea păstrează aceleași coordonate în lista criptată de albume, ca orice poză cu locație. Coordonatele nu sunt trimise niciodată nouă sau altcuiva. Poți opri opțiunea din Setări > Jurnal intruși și poți retrage accesul la locație din Configurări > Vault13.

## Harta
Hărțile din Căutare și din jurnalul de intruși sunt oferite de Apple (MapKit). Când deschizi una, imaginile hărții pentru zona de pe ecran se descarcă de la Apple. Vault13 nu trimite pozele sau coordonatele lor; Apple poate vedea ce zonă a hărții e afișată, conform politicii Apple.

## Accesul la Poze
Vault13 cere acces la Poze doar ca să importe ce alegi tu, să salveze înapoi în Poze la cererea ta și, dacă pornești opțiunea, să șteargă originalele după import. iOS îți cere confirmarea la fiecare ștergere.

## Fișiere, lipire și tragere
Vault13 citește doar fișierele pe care le alegi în aplicația Fișiere, poza sau clipul pe care alegi să le lipești și elementele pe care le tragi într-un album.

## Mișcarea dispozitivului
Cât seiful e deschis, Vault13 citește poziția dispozitivului ca să blocheze seiful când îl așezi cu ecranul în jos. Totul se întâmplă pe dispozitiv și nu se salvează nimic. Poți opri funcția din Setări > Securitate.

## Pachete criptate
Poți pune poze și clipuri într-un singur fișier, protejat cu o parolă aleasă de tine, pe care îl trimiți tu (AirDrop, Fișiere). Fișierul e criptat AES-256 pe dispozitiv. Vault13 nu păstrează parola și nu trimite fișierul nicăieri: tu hotărăști unde ajunge. Cine are și fișierul, și parola îl poate deschide în Vault13.

## Setările
Preferințele tale (limbă, sunet, calitatea importului și altele) stau doar pe dispozitiv.

## Ștergerea datelor
- Setări > Resetare > „Șterge seiful de pe acest dispozitiv” șterge tot de pe dispozitiv.
- „Șterge tot, inclusiv backup-ul din iCloud” șterge și folderul de backup Vault13.
- Ștergerea aplicației șterge toate datele locale. Poți șterge și folderul Vault13 din iCloud Drive, în aplicația Fișiere.

## Copiii
Vault13 nu colectează informații de la nimeni, deci nici de la copii.

## Modificări
Dacă politica se schimbă, noua versiune apare pe această pagină, cu o nouă dată de intrare în vigoare.

## Contact
ionut00@gmail.com
