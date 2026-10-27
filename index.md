---
layout: default
title: Prickle Panic - Gizlilik Politikasi / Privacy Policy
---

# Prickle Panic — Gizlilik Politikası

**Son güncelleme:** 28 Ekim 2026
**İletişim:** nezirarslan.dev@gmail.com

> Bu metin oyunun **gerçekte ne yaptığına** bakılarak yazıldı, şablondan değil.
> Aşağıda yazan her madde koddan doğrulandı.

## Kısaca

Prickle Panic'in kendi sunucusu ve kendi hesap sistemi yoktur. Ama oyun **Google Play Oyun
Hizmetleri**'ni kullanır: telefonundaki Google hesabınla otomatik giriş yapar, oyun
ilerlemeni Google'ın bulut kaydında tutar ve Arena rekorunu herkese açık bir sıralamaya
gönderir. Ayarların ve satın alma hakkın yalnızca telefonunda durur. Reklamlar bir üçüncü
taraf tarafından sunulur ve reklam kimliğini işler.

Bulut kaydı ve sıralama istersen kapatılabilir: Play Oyunları girişini reddedersen oyun
tamamen çevrimdışı çalışır, hiçbir şey gönderilmez.

## Google Play Oyun Hizmetleri

Oyunu açtığında Google Play Oyun Hizmetleri'ne **otomatik giriş** denenir. Giriş
penceresini Google gösterir; şifreni oyun görmez. Girişten sonra oyuna ulaşan tek kimlik
bilgisi Play Oyunları **oyuncu kimliğin ve görünen adındır**. E-posta adresin, gerçek adın
ve rehberin bize gelmez.

Giriş başarısız olursa ya da reddedersen oyun çevrimdışı moda düşer: bulut kaydı ve gerçek
sıralama devre dışı kalır, Arena panellerinde "çevrimdışı" uyarısı görünür, oyun oynanmaya
devam eder.

### Bulut kaydı (Saved Games)

Giriş yaptıysan ilerlemen, Google hesabına bağlı bir kayıt dosyasında
(`spike_bounce_progress_v1`) saklanır. Böylece oyunu silip yeniden kurduğunda ya da telefon
değiştirdiğinde ilerlemen geri gelir. Bu dosya Google'ın Play Oyunları altyapısında durur;
**bizim erişebileceğimiz bir kopyası yoktur**, sunucumuz yoktur.

Buluta giden veriler yalnızca oyun ilerlemesidir:

- En yüksek skorların (her mod için ayrı), toplam koşu sayısı, toplam XP, bölüm ilerlemen
- Coin, açtığın toplar, izler, patlamalar, temalar, ses paketleri, unvanlar, petler
- Seçili görünüm tercihlerin (hangi top, hangi tema, hangi ses paketi seçili)
- Görev/başarım ilerlemen, sezon geçişi seviyesi, lig ve turnuva durumun
- Günlük giriş serin, şans çarkı ve günlük ödül için son alma zamanların

Buluta **bilerek gitmeyen** şeyler:

- **Satın alma hakkın** ("Reklamları Kaldır") — bunu Google Play Billing geri yükler
- Reklam kişiselleştirme tercihin ve izin durumun
- Müzik, ses, titreşim, görsel kalite, dil gibi cihaza ait ayarlar

### Sıralama

Arena'daki rekorun, herkese açık **"Arena — En Yüksek Skor"** sıralamasına gönderilir.
Bunun anlamı şudur: skorun ve Play Oyunları'ndaki **görünen adın**, sıralamaya bakan diğer
oyunculara görünür. Aynı şekilde oyun, sıralamanın üst sıralarını ve oradaki oyuncuların
görünen adlarını sana gösterir.

Giriş yapmadıysan Arena'da gerçek oyuncu yoktur; rakipler kendi rekoruna göre cihazında
üretilen botlardır ve oyun bunu ekranda açıkça söyler.

## Yalnızca cihazında kalan veriler

Şunlar Android'in yerel depolama alanında (Unity PlayerPrefs / SharedPreferences) durur ve
**hiçbir yere gönderilmez**, buluta da yazılmaz:

- Ayarların: müzik, ses, titreşim, görsel kalite, dil
- Reklam kişiselleştirme tercihin
- "Reklamları Kaldır" hakkına sahip olup olmadığın

## Skor kartı paylaşımı

Öldüğün ekrandaki paylaş butonuna basarsan oyun bir skor görseli üretir, telefonunun
geçici klasörüne yazar ve **senin seçtiğin** uygulamaya (WhatsApp, Instagram vb.) verir.
Görsel bize gönderilmez; ne olduğu, paylaştığın uygulamanın kendi gizlilik politikasına
tabidir.

## Analitik

Oyunun içinde oynanış sayaçları tutulur (hangi modun kaç kez oynandığı, ölüm sebepleri
gibi). Bunlar **dengeleme için cihazda** hesaplanır ve dışarı çıkmaz. Bağlı bir analitik
sağlayıcı yoktur.

## Reklamlar

Oyun ücretsizdir ve reklam gösterir. Reklamları **Unity LevelPlay** (ironSource) sağlar.
LevelPlay bir *aracı* platformdur: reklamı kendisi göstermeyebilir, anlaşmalı reklam
ağlarına yönlendirir. Bu ağlar da aşağıdaki verileri işleyebilir.

Reklam gösterebilmek için sağlayıcı şunları işleyebilir:

- Android Reklam Kimliği (Advertising ID)
- IP adresin ve yaklaşık (şehir düzeyinde) konumun
- Cihaz modeli, işletim sistemi sürümü, dil
- Reklamı görüp görmediğin, tıklayıp tıklamadığın

Oyunu ilk açtığında **kişiselleştirilmiş reklamlara izin verip vermeyeceğini** sorarız.
Reddedersen yine reklam görürsün ama içeriği ilgi alanlarına göre seçilmez. Bu tercihini
istediğin zaman Ayarlar'dan değiştirebilirsin.

Reklam sağlayıcısının kendi gizlilik politikası:
https://unity.com/legal/privacy-policy

## Satın almalar

Oyunda tek bir isteğe bağlı satın alma vardır: **Reklamları Kaldır**. Tur sonlarında
çıkan reklamları kalıcı olarak kapatır. Ödül karşılığı izlenen reklamlar senin seçimin
olarak kalır.

Ödeme tamamen **Google Play** üzerinden yapılır. Kart bilgin, adın ya da fatura bilgin
bize ulaşmaz; bunları göremeyiz ve saklamayız. Google Play bize yalnızca satın almanın
gerçekleşip gerçekleşmediğini bildirir. Satın aldığın bilgisi telefonunda saklanır ve
cihaz değiştirdiğinde Google Play tarafından geri yüklenir.

Ödeme işlemine ilişkin Google'ın gizlilik politikası:
https://policies.google.com/privacy

## Çocuklar

Prickle Panic özellikle 13 yaş altı çocuklara yönelik değildir ve bilerek onlardan veri
toplamayız. Play Oyunları girişi Google'ın kendi yaş ve ebeveyn denetimi kurallarına
tabidir. Çocuğunuzun veri paylaştığını düşünüyorsanız yukarıdaki adresten bize ulaşın.

## Haklarınız ve verini silmek

**Cihazındaki veriler:** uygulamayı kaldırmak, telefonda tutulan her şeyi (ayarlar, yerel
ilerleme, tercihler) kalıcı olarak siler.

**Buluttaki oyun kaydın ve sıralama skorun:** bunlar Google hesabına bağlıdır, silme
denetimi Google'dadır:

- Play Oyunları uygulaması → Profil → Ayarlar → **Play Oyunları hesabını ve verileri sil**
  bölümünden, tek tek oyun bazında ya da tamamen silebilirsin. Bu işlem hem bulut kaydını
  hem de sıralamadaki skorunu kaldırır.
- Silmekte sorun yaşarsan yukarıdaki adresten bize yaz; elimizden geleni yaparız.

**Reklam kimliği:** Android Ayarlar → Gizlilik → Reklamlar bölümünden sıfırlayabilir veya
kişiselleştirmeyi tamamen kapatabilirsin.

**Hiç göndermemek:** açılıştaki Play Oyunları girişini reddedersen bulut kaydı ve sıralama
hiç devreye girmez.

## Değişiklikler

Bu politika değişirse yukarıdaki tarih güncellenir. Önemli bir değişiklik olursa oyun
içinde bildiririz.

---

# Prickle Panic — Privacy Policy

**Last updated:** 28 October 2026
**Contact:** nezirarslan.dev@gmail.com

## In short

Prickle Panic has no server and no account system of its own. But the game does use
**Google Play Games Services**: it signs you in automatically with the Google account on
your phone, keeps your progress in Google's cloud save, and submits your Arena record to a
public leaderboard. Your settings and your purchase entitlement stay only on your phone.
Ads are served by a third party, which processes your advertising ID.

Cloud save and the leaderboard are optional: decline the Play Games sign-in and the game
runs fully offline, sending nothing.

## Google Play Games Services

When you open the game it attempts an **automatic sign-in** to Google Play Games Services.
Google shows the sign-in prompt; the game never sees your password. After signing in, the
only identity the game receives is your Play Games **player ID and display name**. Your
email address, real name and contacts do not reach us.

If sign-in fails or you decline, the game falls back to offline mode: cloud save and the
real leaderboard are disabled, the Arena panels show an "offline" notice, and the game
remains fully playable.

### Cloud save (Saved Games)

If you are signed in, your progress is stored in a save file (`spike_bounce_progress_v1`)
tied to your Google account, so that reinstalling the game or changing phones brings your
progress back. The file lives in Google's Play Games infrastructure; **we hold no copy of
it** and we operate no server.

Only game progress goes to the cloud:

- Your best scores (kept separately per mode), total run count, total XP, chapter progress
- Coins, unlocked balls, trails, explosions, themes, sound packs, titles and pets
- Which of those you currently have selected
- Mission and achievement progress, season pass level, league and tournament state
- Daily login streak and the timestamps of your last lucky wheel spin and daily reward

Deliberately **kept out** of the cloud:

- Your purchase entitlement ("Remove Ads") — Google Play Billing restores that instead
- Your ad personalisation choice and consent state
- Device-local settings: music, sound, vibration, visual quality, language

### Leaderboard

Your Arena record is submitted to the public **"Arena — High Score"** leaderboard. That
means your score and your Play Games **display name** are visible to other players looking
at the ranking. Likewise, the game shows you the top of the leaderboard along with those
players' display names.

If you are not signed in there are no real players in the Arena; the rivals are bots
generated on your device from your own record, and the game says so on screen.

## Data that stays only on your device

The following is stored in Android's local storage (Unity PlayerPrefs / SharedPreferences),
is **never transmitted**, and is not written to the cloud:

- Your settings: music, sound, vibration, visual quality, language
- Your ad personalisation choice
- Whether you own "Remove Ads"

## Score card sharing

If you tap the share button on the game-over screen, the game renders a score image,
writes it to your phone's temporary folder and hands it to **the app you choose**
(WhatsApp, Instagram, and so on). The image is not sent to us; what happens next is
governed by that app's own privacy policy.

## Analytics

The game keeps gameplay counters (how often each mode is played, causes of death, and
similar). These are computed **on the device for balancing** and never leave it. No
analytics provider is connected.

## Ads

The game is free and shows ads, provided by **Unity LevelPlay** (ironSource). LevelPlay is
a *mediation* platform: it may not serve the ad itself but route the request to partner ad
networks, which may process the same data.

To serve ads, the provider may process your Android Advertising ID, IP address and
approximate (city-level) location, device model, OS version and language, and whether you
saw or tapped an ad.

When you first open the game we ask whether you consent to **personalised** ads. If you
decline you will still see ads, but they will not be selected based on your interests.
You can change this choice at any time in Settings.

Ad provider's own privacy policy: https://unity.com/legal/privacy-policy

## Purchases

The game offers a single optional purchase: **Remove Ads**. It permanently removes the
ads shown between rounds. Optional rewarded ads remain available by your choice.

Payment is handled entirely by **Google Play**. Your card details, name and billing
information never reach us; we cannot see or store them. Google Play only tells us whether
the purchase completed. The fact that you own it is stored on your phone and restored by
Google Play when you change devices.

Google's privacy policy covering the payment: https://policies.google.com/privacy

## Children

Prickle Panic is not directed at children under 13 and we do not knowingly collect data
from them. Play Games sign-in is subject to Google's own age and parental control rules.
If you believe your child has shared data with us, contact us at the address above.

## Your rights and deleting your data

**Data on your device:** uninstalling the app permanently deletes everything held on the
phone (settings, local progress, preferences).

**Your cloud save and leaderboard score:** these are tied to your Google account and
deletion is controlled by Google:

- Play Games app → Profile → Settings → **Delete Play Games account & data**, either for
  this game alone or entirely. This removes both the cloud save and your leaderboard entry.
- If you have trouble deleting it, write to the address above and we will help.

**Advertising ID:** you can reset it, or turn personalisation off entirely, in Android
Settings → Privacy → Ads.

**Sending nothing at all:** decline the Play Games sign-in at launch and neither cloud save
nor the leaderboard is ever engaged.

## Changes

If this policy changes, the date above is updated. We will notify you inside the game if
the change is significant.
