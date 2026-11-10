# Lumen changelog

Sabse naya version sabse upar.

## Lumen 1.8 · Earphone mein bhi gaana pehchano

**10 Nov 2026 · build 9 · Android 8.0+**

Song finder ab phone ka apna sound sunta hai, lyrics shabd-dar-shabd chalte hain, aur app ko apne hisaab se rang, font aur bhasha de sakte ho.

### Naya
- **Phone ka sound sunna**: song finder ab seedha phone ke andar ka sound sunta hai, isliye **earphone lage hon tab bhi** kisi bhi app ka gaana pehchan leta hai. Agar koi app apna sound share nahi karta, to Lumen khud mic par chala jaata hai.
- **"Mic (music outside)"** option: laptop, TV ya dukaan mein bajta gaana pehchanne ke liye. Identify mein "Listen to" se chuno.
- **Saaf setup screen**: bubble ke liye har permission alag step mein, kyun chahiye ye likha hua, aur ho jaane par tick. "Restricted setting" aaye to wahin 4 line ka rasta aur "Open App info" button.
- **Lyrics shabd-dar-shabd**: gaane ke saath har shabd roshan hota hai. Jahan source ke paas asli timing hai wahan wahi, baaki mein line ki lambai se andaza.
- **Lyrics ki lipi chuno**: jis gaane ke lyrics Hindi, Roman, Punjabi jaisi kai lipiyon mein hain, wahan upar se chuno. Pasand yaad rehti hai.
- Lyrics na milein to ek **doosre catalogue** se bhi dhoondhta hai.
- **8 rang ke theme**, **6 fonts** aur **4 text size** (Settings → Appearance).
- **12 bhashayein**: हिन्दी, বাংলা, मराठी, ગુજરાતી, ਪੰਜਾਬੀ, தமிழ், తెలుగు, ಕನ್ನಡ, മലയാളം, Español, Français, English. Abhi mukhya shabd (tabs, library, menu, settings) translate hain; baaki English mein hain.

### Tez
- Haal ke gaanon ke lyrics yaad rehte hain, dobara kholne par turant aate hain.

### Safe
- Phone ke sound ke liye Android har baar "Start recording?" poochta hai. Lumen sirf sound leta hai, screen kabhi nahi, aur recording phone se bahar nahi jaati.

**Update:** 1.3 ya usse naye version ke upar seedha install karo, data safe rehta hai.

`SHA-256: 5c88634b3f2fbfbb228f3ba7d015a2abc81bedad447b59b04e448e6c24fc70b9`

## Lumen 1.7 · Song finder pakka, engines naye

**10 Nov 2026 · build 8 · Android 8.0+**

1.6 ke song finder aur cover photo ki galtiyan theek kiin, aur gaane laane wale engines update kiye.

### Theek kiya
- Gaana pehchanne ke baad upar wala card kholte ya band karte waqt **app crash** ho jaata tha, jisse bubble bhi gayab ho jaata tha. Ab nahi hota.
- **"Play in Lumen"** ab sahi chalta hai: gaana turant bajna shuru hota hai aur Lumen player ke saath khulta hai. Agar phone Lumen ko upar aane se roke, to card par "Open Lumen" button aata hai.
- Card ko **✕ ya swipe** (left, right ya upar) se hatao. Sirf card hatta hai, gol bubble agle gaane ke liye rehta hai.
- List par apni photo lagate waqt **"Couldn't open that picture"** aata tha. Ab photo khulti hai aur crop hoti hai.

### Naya
- **Check music sources** (Settings mein): ek tap mein YouTube Music, JioSaavn aur SoundCloud teeno ka search aur asli stream test hota hai, aur batata hai kaunsa chal raha hai.

### Tez aur safe
- YouTube aur SoundCloud wala engine (NewPipe Extractor) naye version 0.27.0 par.
- Networking (OkHttp 5.5.1) aur image (Coil 3.6.3) libraries update.
- Sunna band karte waqt mic ab hamesha saaf tareeke se chhoot'ta hai.

**Update:** 1.3 ya usse naye version ke upar seedha install karo, data safe rehta hai.

`SHA-256: 72a20118361f38b37910d5941d7fa43c89754d00c1a091511c3df853e31e3fa2`

## Lumen 1.6 · Koi bhi gaana pehchano

**9 Nov 2026 · build 7 · Android 8.0+**

Reel ya video mein gaana bajta hai par naam nahi pata? Ab Lumen ka bubble use sunkar naam batata hai aur ek tap mein Lumen mein chala deta hai. Saath mein apni list apne hisaab se lagao, aur har list par apni photo.

### Naya
- **Song finder**: neeche beech mein naya Lumen button. Use dabao, phir Instagram, YouTube ya kisi bhi app mein jao. Lumen ka **floating bubble** upar rahega; gaana baje to bubble dabao, wo naam bata dega.
- Pehchana hua gaana **"Play in Lumen"** se seedha Lumen mein bajta hai, uske baad milte-julte gaane apne aap.
- Bubble ko screen par kahin bhi khiskao. Neeche **✕** par chhodo to band ho jaata hai.
- Liked, Downloads, On this device, Recently played aur har playlist mein gaane ko **halka sa daba ke rakho aur upar-neeche khiskao**. Jo order lagao, wahi save rehta hai.
- Har list par **apni photo** lagao: gallery se koi bhi photo chuno, zoom aur khiska ke square mein set karo. Har list ki alag photo ho sakti hai.

### Safe
- Song finder sirf bubble dabane ke baad sunta hai. Recording phone se bahar nahi jaati; sirf gaane ka chhota sa fingerprint jaata hai, bina account ya location ke.
- Bahar ke apps se aane wale gaane ke links ab pehle jaanche jaate hain, phir chalte hain.
- Aapki list ki photos bhi phone ke backup mein jaati hain.

**Update:** 1.3 ya usse naye version ke upar seedha install karo, data safe rehta hai.

`SHA-256: 198256208a5f6c2e6afa429808a646fd249df6fa3897c3d65c8943d1a403b6a6`

## Lumen 1.5 · Queue jo sach mein kaam kare

**7 Nov 2026 · build 6 · Android 8.0+**

Gaane chalane, queue lagane aur download ka poora system dobara banaya. Ab badi playlist aur sainkdon downloads bhi aaram se chalte hain.

### Theek kiya
- **Add to queue** wala gaana ab current gaane ke turant baad bajta hai. Pehle wo autoplay ke 15–25 gaano ke peeche chala jaata tha.
- Shuffle on hone par bhi queue wala gaana sahi jagah bajta hai, kahin bhi random nahi.
- **Start radio** ke beech mein doosra gaana chalane par purane gaane ka radio ab nayi queue mein nahi ghusta.
- Queue khatam hone ke baad kuch add karo to wo turant bajne lagta hai.
- 500 se badi playlist mein app dobara kholne par ab sahi gaana wahin se chalta hai.
- Playlist mein pehle se maujood gaana dobara add karo to "Already in playlist" batata hai.

### Naya
- Playlist, Liked aur Downloads mein **gaana dhoondho** aur Title, Artist ya Longest se **sort** karo.
- Queue ko ek tap mein **playlist bana ke save** karo.
- **Download liked songs** setting: jo gaana like karo, wo apne aap offline save ho jaaye.
- Playlist par **Play next**, album par **Add to queue**, aur Downloads mein **Stop all**.
- Din mein **2 notifications**, ek din mein aur ek shaam ko. Har baar alag tarah ki: naya release, trending, aapke taste ka naya gaana, mood pick, ya hafte ka report card.

### Safe
- Downloads ab ek list mein save rehte hain. App band ho jaye to agli baar wahin se aage chalte hain, aur fail hone par 3 baar khud try karte hain.

### Tez
- Downloaded gaane seedhe file se bajte hain, na internet lagta hai na extra jagah.
- Hazaron gaano wali playlist chalane par bhi screen nahi atakti.

**Update:** 1.3 ya usse naye version ke upar seedha install karo, data safe rehta hai.

`SHA-256: 6d940a98a4efe1eec6835ab1c68d3a07a5e5b453c64343235ae2d6d96d4559c2`

---

## Lumen 1.4 · Data safe, playlist share, tez shuruaat

**7 Nov 2026 · build 5 · Android 8.0+**

App ki poori jaanch ke baad asli bugs theek kiye, data ko pakka safe banaya, aur bina server ke playlist share karne ka tareeka joda.

### Naya
- **Playlist share code**: playlist WhatsApp par bhejo, koi bhi Lumen ke Search mein paste karke use le sake.
- **Backup aur restore**: poori library ek file mein save karo aur kabhi bhi wapas lao.
- Home ke "Jump back in" gaano par long-press se menu khulta hai.

### Safe
- Phone ka Google backup ab sirf aapki library save karta hai. Pehle downloads ki wajah se 25 MB se upar jaakar poora backup fail ho jaata tha.
- Library ki teen copies rehti hain (abhi ki, har ghante ki, har din ki). Battery khatam ho ya app band ho, file kabhi aadhi nahi likhi jaati.
- Playlist delete karne se pehle app poochta hai, aur delete ke baad **Undo** ka button bhi aata hai.

### Tez
- Gaana tap karte hi uska link dhoondhna shuru. App dobara kholne par haal mein sune gaane turant chalte hain.
- Ghanton autoplay chalne ke baad bhi app dheema nahi hota.

### Theek kiya
- Player ko neeche khinch ke band karne par jhatka nahi lagta, aur lyrics padhte waqt list apne aap nahi bhagti.
- Android ke app band karne ke baad album ya playlist screen ab khud band nahi hoti.
- Studio mein recording ki file gayab ho to app crash nahi hota, saaf message dikhata hai.

`SHA-256: 5ca790915d2688abf9c04a6993c019da474da63cd7a93af2a6b9cdd8e5959711`

---

## Lumen 1.3 · App jo khud sochta hai

**7 Nov 2026 · build 4 · Android 8.0+**

Lumen ko aapke taste ke hisaab se chalne wala, khud ko sambhalne wala app banaya. Sab kuch phone par hi, bina kisi server ke.

### Naya
- **Podcast, lectures aur talks**: YouTube videos search karo aur gaane ki tarah suno.
- Koi bhi YouTube, JioSaavn ya SoundCloud **link paste** karo aur turant chalao.
- Home feed ab aapke taste se banta hai: aapke artists, naye release, aur waqt ke hisaab se mood.
- Mazedaar Hinglish notifications, aapke pasand ke gaano ke saath.

### Safe
- App baar-baar crash ho to agli baar khud ko theek karke khulta hai. Aapki library ko kabhi haath nahi lagata.
- YouTube ya JioSaavn down ho to app doosre source se gaana chala deta hai.
- App ab ek nayi pakki key se sign hota hai, taaki har agla update bina data khoye install ho.

### Tez
- Cache phone ki khaali jagah dekh ke apna size rakhta hai, aur jagah kam ho to khud saaf karta hai.

**1.2 se aa rahe ho?** Nayi key ki wajah se ek baar purana app hatana padega. Uske baad har update seedha install hota hai.

`SHA-256: fa340ba9c653709f6a629a3b3acd4dbfef3cad75375981489d146b9084f5d4bf`

---

## Lumen 1.2 · Jahan se shuru hua

**5 Nov 2026 · build 3 · Android 8.0+**

Sabse purana version jiska record hamare paas hai. Ismein Lumen ki buniyaad thi.

- YouTube Music, JioSaavn aur SoundCloud mein ek saath search.
- Player, lyrics, queue, sleep timer aur picture-in-picture.
- Liked songs, apni playlists, saved albums aur artists.
- Gaane offline download karo, aur phone mein pade gaane bhi chalao.

> Ye version purani key se sign hai. Iske upar 1.3 ya naya version install karne ke liye pehle ise hatana padega. Naye users seedha latest version lein.

`SHA-256: 36635a43f6e24e56b7f75695481f4220944b2bbf61385e407ca94bb397da15fd`

---
