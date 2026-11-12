# Changelog

## v1.0.2

- **Other mods / skins**: with some other mods installed the plugin read the wrong game data store, so it found no team and the squad, shortlists and rules stayed empty. It now always reads the game's own store, and finds the manager's team another way if a skin hides the usual one.
  Başka modlar kuruluyken eklenti oyunun yanlış veri deposunu okuyordu; takımı bulamıyor, kadro, takip listeleri ve kurallar boş kalıyordu. Artık her zaman oyunun kendi deposunu okuyor; bir skin olağan yolu gizlerse takımı başka bir yoldan buluyor.

## v1.0.0

First full release. / İlk tam sürüm.

- **Ekip / Staff (new tab)**: the coaching, medical and scouting groups against the club's limits; each job with its people, age and contract; the game's rating per training category with the coaches on it; alerts for missing coaches, empty jobs, overloaded coaches and contracts running out; contracts by year; the club's other teams and youth.
  **Ekip (yeni sekme)**: antrenman, sağlık ve gözlem gruplarının kulüp kotasına göre durumu; her görevde kişiler, yaş ve sözleşme; her antrenman başlığında oyunun puanı ve o başlıktaki hocalar; eksik hoca, boş görev, yükü fazla hoca ve biten sözleşme uyarıları; yıllara göre sözleşmeler; diğer takımlar ve altyapı.
- **Hiring plan / Alım Planı**: what to hire first in each group within the free places; one coach for two categories that ask for the same attribute when places are short; when a group is full, whom to replace. One click adds a suggestion to your staff needs.
  Her grupta boş yerlere göre önce kimin alınacağı; yer azsa aynı özelliği isteyen iki başlık tek hocaya; kota doluysa kimin yerine. Tek tıkla ihtiyaçlara eklenir.
- **Scouting coverage / Gözlem kapsamı**: the nations of your watched players that no scout knows.
  Takip ettiğin oyuncuların, hiçbir gözlemcinin bilmediği ülkeleri.
- **Staff needs and notes / Ekip ihtiyaçları ve notlar**: your own list of staff to find, and a note per person.
  Bulmak istediğin personelin listesi ve her kişiye not.
- **Cups / Kupalar**: each cup gets its own pitch and registration plan, checked rule by rule; club- and association-trained players marked; drag players on and off the pitch.
  Her kupanın kendi sahası ve kayıt planı, kural kural kontrol; kulüpte ve ülkede yetişen oyuncular işaretli; oyuncular sahaya sürüklenip çıkarılır.
- **Scratchpad / Karalama**: a blank page for free notes, like a notepad, kept with the career (the pencil tab).
  Serbest notlar için boş bir sayfa, not defteri gibi; kariyerle birlikte saklanır (kalem sekmesi).
- **Analysis / Analiz**: "Youth: ready" also lists the young players your youth staff call ready for the first team.
  "Altyapı: hazır" listesinde altyapı ekibinin A takıma hazır dediği gençler de var.
- **Player levels setting / Oyuncu seviyeleri ayarı**: turn off the level badge (Distinguished, Capable…) in the squad, watch and picking lists; on by default, the analysis always shows it.
  Kadro, takip ve seçim listelerinde seviye rozetini (Seçkin, Yetkin…) kapatabilirsin; varsayılan açık, analizde hep görünür.
- **Language files / Dil dosyaları**: every text is in `BepInEx/plugins/FMTransferNotes/lang/<code>.json` (written on first start). Change a line and it shows in a few seconds; your lines survive updates. A new file (e.g. `ru.json`) with `Language = ru` in the config adds a language.
  Tüm metinler `lang/<kod>.json` dosyalarında (ilk açılışta oluşur). Bir satırı değiştir, birkaç saniyede görünür; senin satırların güncellemede kaybolmaz. Yeni bir dosya (ör. `ru.json`) ve config'de `Language = ru` ile yeni dil eklenir.
- Many smaller fixes to the analysis, menus and the pitch. / Analiz, menüler ve sahada birçok küçük düzeltme.

## v0.95.18 (pre-release / ön sürüm)

First shared pre-release; v1.0.0 will be the first full release. / İlk paylaşılan ön sürüm; v1.0.0 ilk tam sürüm olacak.

- **Gelecek / Incoming**: needs with targets, positions, preferred foot, licence rules and links to an outgoing sale. Candidate rows fold open to show role, personality, warnings and pluses.
- **Gidecek / Outgoing**: sale, loan and release plans that follow the game (sold, loaned, kept).
- **Saha / Pitch**: this season and next season line-ups, auto line-up by level, familiarity and young potential.
- **Analiz / Analysis**: squad advice for contracts, surplus, replacements and depth; next-season view.
- **Lig kuralları / League rules**: foreign and home-grown counts read from the game.
- **Other competitions**: each cup's registration rules, and first choices missing from its list.
- **Free-agent tag**: shortlist players with six months or less left on their contract.
- **New-version notice** in the footer, *Report a problem*, theme and auto squad refresh in Settings.
