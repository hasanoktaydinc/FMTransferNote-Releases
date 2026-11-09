# FM Transfer Notes

Football Manager 27 için transfer defteri eklentisi (BepInEx 6 IL2CPP, macOS ve Windows).
A transfer notebook plugin for Football Manager 27 (BepInEx 6 IL2CPP, macOS and Windows).

Bu repo yalnızca sürümleri yayınlar; eklenti oyun içinde yeni sürüm çıktığında alt bilgide haber verir.
This repo only hosts releases; the plugin shows a notice in its footer when a newer version is out.

## Türkçe

**Kurulum**
1. FM27 için BepInEx 6 (IL2CPP) kurulu olmalı.
2. [Releases](../../releases) sayfasından son `FMTransferNotes-vX.Y.Z.zip` dosyasını indir.
3. Zip'in içindeki `BepInEx` klasörünü oyunun BepInEx klasörünün olduğu yere kopyala (`BepInEx/plugins/FMTransferNotes/FMTransferNotes.dll`).
4. Oyunu aç, bir kariyer yükle. Ekrandaki yuvarlak düğmeye tıkla ya da **Ctrl+Shift+T**.

**Güncelleme**
Yeni sürüm çıkınca eklentinin alt bilgisinde "Yeni sürüm" bağlantısı görünür. Zip'i indirip eski DLL'in üzerine kopyalaman yeterli; defterlerin (`<FM27 kullanıcı klasörü>/FMTransferNotes/`) olduğu gibi kalır. Kontrolü Ayarlar'dan kapatabilirsin.

**Güvenlik**
Eklenti oyun dosyalarına ve kayıtlara dokunmaz, yalnızca okur. Tek istisna: sen onayladığında oyuncuyu transfer/kiralık listesine koyup çıkarır.

**Sorun bildir**
Eklentinin alt bilgisindeki *Sorun Bildir* bağlantısını kullan.

## English

**Install**
1. BepInEx 6 (IL2CPP) must be installed for FM27.
2. Download the latest `FMTransferNotes-vX.Y.Z.zip` from [Releases](../../releases).
3. Copy the `BepInEx` folder from the zip next to the game's BepInEx folder (`BepInEx/plugins/FMTransferNotes/FMTransferNotes.dll`).
4. Start the game and load a career. Click the round button, or press **Ctrl+Shift+T**.

**Updating**
When a new version is out, a "New version" link appears in the plugin's footer. Download the zip and copy the DLL over the old one; your notebooks (`<FM27 user-data folder>/FMTransferNotes/`) stay as they are. The check can be turned off in Settings.

**Safety**
The plugin does not change game files or saves; it only reads. The one exception: when you confirm, it puts players on or off the transfer/loan lists.

**Report a problem**
Use the *Report a problem* link in the plugin's footer.

See [CHANGELOG.md](CHANGELOG.md) for what changed.
