# FM Transfer Notes

Football Manager 27 için oyunun içinde, bir kısayolla açılan transfer ve kadro defteri (BepInEx 6 IL2CPP, macOS ve Windows).
A transfer and squad notebook that lives inside Football Manager 27, one shortcut away (BepInEx 6 IL2CPP, macOS and Windows).

Bu repo yalnızca sürümleri yayınlar; eklenti oyun içinde yeni sürüm çıktığında alt bilgide haber verir.
This repo only hosts releases; the plugin shows a notice in its footer when a newer version is out.

## Türkçe

Her FM oyuncusu bir noktada defteri kalemi ya da bilgisayardaki not defterini açıp transfer planını, taktiğini not etmiştir. FM Transfer Notes bu defteri oyunun içine taşır: küçük bir simgeye tıkla (ya da **Ctrl+Shift+T**), not defteri açılsın; sürükleyip nereye bırakırsan orada kalsın. Oyundan çıkmadan planla.

**Neler var**
- **Alınacak**: mevkiye göre ihtiyaçlar, üç öncelikte (Olmazsa Olmaz, Olsa İyi Olur, Olmasa Da Olur). Her ihtiyaca aday ekle: oyunun takip listesinden, açık profilden ya da elle. Uyruk, yaş ve lig kuralları (yabancı / yerli kotaları) planlarınla birlikte sayılır.
- **Gidecek**: satılacak, kiralanacak, bırakılacak oyuncular. Oyundaki gelişmeyi takip eder; istersen oyunun transfer listesini de günceller (her seferinde sorar).
- **Saha**: bu sezonun ve gelecek sezonun kadrosu ligin dizilişinde. Her kupa için ayrı kayıt planı, kural kural kontrol.
- **Analiz**: sözleşmeler, fazlalıklar, yedekler, derinlik ve A takıma hazır gençler.
- **Ekip**: antrenman, sağlık ve gözlem ekiplerinin kulüp kotasına göre durumu, antrenman başlıklarına göre hocalar, uyarılar ve boş yerlere göre alım planı.
- **Karalama**: her şey için boş bir sayfa.
- Bir oyuncunun profiline baktığında, defterinde nerede olduğunu gösteren küçük bir etiket.
- 8 dil (metinler `lang/*.json` dosyalarında, değiştirilebilir), açık / koyu tema, oyuncu yüzleri.

**CA ve PA sayısı göstermez**
Eklenti oyuncu arama aracı değildir. Oyuncuları yalnızca oyunun kendi takip listelerinden ve senin kadrondan alır; hiçbir yerde CA veya PA sayısı göstermez. Listelerde "Yetkin", "Seçkin" gibi geniş bir seviye etiketi görünür; bu etiket Ayarlar'dan kapatılabilir (Analiz'de kalır). Bazı oyuncularda etiket gözlemci yıldızlarından bir tahmindir (~ ile gösterilir).

**Kurulum**
1. FM27 için BepInEx 6 (IL2CPP) kurulu olmalı.
2. [Releases](../../releases) sayfasından son `FMTransferNotes-vX.Y.Z.zip` dosyasını indir.
3. Zip'in içindeki `BepInEx` klasörünü oyunun BepInEx klasörünün olduğu yere kopyala (`BepInEx/plugins/FMTransferNotes/FMTransferNotes.dll`).
4. Oyunu aç, bir kariyer yükle. Ekrandaki yuvarlak düğmeye tıkla ya da **Ctrl+Shift+T**.

**Güncelleme**
Yeni sürüm çıkınca eklentinin alt bilgisinde "Yeni sürüm" bağlantısı görünür. Zip'i indirip eski DLL'in üzerine kopyalaman yeterli; defterlerin (`<FM27 kullanıcı klasörü>/FMTransferNotes/`) olduğu gibi kalır. Kontrolü Ayarlar'dan kapatabilirsin.

**Güvenlik**
Eklenti oyun dosyalarına ve kayıtlara dokunmaz, yalnızca okur. Notların kayıttan ayrı bir klasörde durur. Tek istisna: sen onayladığında oyuncuyu transfer/kiralık listesine koyup çıkarır.

**Sorun bildir**
Eklentinin alt bilgisindeki *Sorun Bildir* bağlantısını kullan.

## English

At some point every FM player has opened a notebook, or Notepad on the computer, to write down transfer plans and tactics. FM Transfer Notes puts that notebook inside the game: click a small round button (or press **Ctrl+Shift+T**) and it opens; drag it anywhere and it stays there. Plan without leaving the game.

**What it does**
- **Incoming**: needs by position in three priorities (Must have, Nice to have, Could have). Add targets to each: from the game's shortlists, the open profile, or typed. Nationality, age and league rules (foreign / homegrown quotas) are counted together with your plans.
- **Outgoing**: players to sell, loan or release. It follows what happens in the game, and can update the game's transfer list too (it asks every time).
- **Pitch**: this season's and next season's squad on the league's formation. A separate registration plan for every cup, checked rule by rule.
- **Analysis**: contracts, surplus, backups, depth and youngsters ready for the first team.
- **Staff**: coaching, medical and scouting against the club's limits, coaches per training category, alerts and a hiring plan for the free places.
- **Scratchpad**: a blank page for anything.
- On a player's profile, a small tag shows where he is in your notes.
- 8 languages (texts in editable `lang/*.json` files), light / dark theme, player pictures.

**No CA or PA numbers**
It is not a player search tool. Players come only from the game's own shortlists and from your squad, and no CA or PA number is shown anywhere. Lists show a broad level tag such as "Capable" or "Distinguished"; it can be turned off in Settings (the analysis keeps it). For some players the tag is an estimate from the scouts' stars (shown with ~).

**Install**
1. BepInEx 6 (IL2CPP) must be installed for FM27.
2. Download the latest `FMTransferNotes-vX.Y.Z.zip` from [Releases](../../releases).
3. Copy the `BepInEx` folder from the zip next to the game's BepInEx folder (`BepInEx/plugins/FMTransferNotes/FMTransferNotes.dll`).
4. Start the game and load a career. Click the round button, or press **Ctrl+Shift+T**.

**Updating**
When a new version is out, a "New version" link appears in the plugin's footer. Download the zip and copy the DLL over the old one; your notebooks (`<FM27 user-data folder>/FMTransferNotes/`) stay as they are. The check can be turned off in Settings.

**Safety**
The plugin does not change game files or saves; it only reads. Your notes are kept in their own folder, apart from the save. The one exception: when you confirm, it puts players on or off the transfer/loan lists.

**Report a problem**
Use the *Report a problem* link in the plugin's footer.

See [CHANGELOG.md](CHANGELOG.md) for what changed.
