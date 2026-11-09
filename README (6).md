# question-bank

**English** | [Türkçe](#türkçe)

A prompt that turns lesson, unit or semester content into an **interactive Arabic question bank website** (fully right-to-left, mobile and desktop friendly). It can be used with **Claude, ChatGPT and Gemini**.

## Files

| File | What it is |
|---|---|
| `prompt.md` | The plain prompt (in Arabic). Works with any AI. |
| `SKILL.md` | The same prompt packaged as a Claude skill. |
| `README.md` | This file. |

## What it does

- Analyzes uploaded content (lesson pages, a unit, a textbook, semester files) or course details you type in.
- Organizes the bank as Semester → Unit → Lesson → Skill → Question.
- Writes questions classified by Bloom's taxonomy and by difficulty (basic, intermediate, advanced).
- Builds a site with practice mode, exam mode, an exam generator and an answer key.
- Shows a performance analysis after each exam, by unit, lesson, skill and Bloom level.

## How to use

### Claude
1. Create a folder named `question-bank` and put `SKILL.md` inside it.
2. Zip the folder.
3. Upload the zip in Claude's skill settings.
4. In a new chat, upload your lesson content and ask for a question bank.

### ChatGPT
Open a new chat, paste the contents of `prompt.md`, then upload your lesson content. You can also paste it into the instructions of a custom GPT to reuse it.

### Gemini
Open a new chat, paste the contents of `prompt.md`, then upload your lesson content. You can also paste it into the instructions of a Gem to reuse it.

If the AI returns website code, save it as an `.html` file and open it in your browser. Results may differ between AIs.

## Notes

- The prompt is written in Arabic because the output is an Arabic question bank.
- If you upload a file, questions should be based only on that content. Always review the questions and answers before using them with students.

## Credits

The original prompt was shared on Twitter/X by **هيثم الشريف | Haitham Alshareif**. This repository packages it as a Claude skill and adds the README. Original post: https://x.com/halshareif/status/2119532585219248171

---

## Türkçe

Ders, ünite veya dönem içeriğinden **etkileşimli Arapça soru bankası sitesi** üreten bir prompt. Site baştan sona sağdan sola (RTL) düzenlenir, telefon ve bilgisayarda çalışır. **Claude, ChatGPT ve Gemini** ile kullanılabilir.

### Dosyalar

| Dosya | Ne olduğu |
|---|---|
| `prompt.md` | Düz prompt (Arapça). Her yapay zekâda çalışır. |
| `SKILL.md` | Aynı promptun Claude skill'i olarak paketlenmiş hâli. |
| `README.md` | Bu dosya. |

### Ne yapar?

- Yüklenen içeriği (ders sayfaları, ünite, kitap, dönem dosyaları) ya da yazdığınız ders bilgisini analiz eder.
- Soru bankasını Dönem → Ünite → Ders → Beceri → Soru yapısında kurar.
- Soruları Bloom taksonomisine ve zorluk düzeyine (temel, orta, ileri) göre sınıflandırır.
- Alıştırma modu, sınav modu, sınav oluşturucu ve cevap anahtarı olan bir site hazırlar.
- Her sınavın sonunda ünite, ders, beceri ve Bloom düzeyine göre performans analizi gösterir.

### Nasıl kullanılır?

#### Claude
1. `question-bank` adında bir klasör açın, içine `SKILL.md` dosyasını koyun.
2. Klasörü zip yapın.
3. Claude'daki skill ayarlarından zip'i yükleyin.
4. Yeni bir sohbette ders içeriğinizi yükleyin ve soru bankası isteyin.

#### ChatGPT
Yeni bir sohbet açın, `prompt.md` içeriğini yapıştırın, sonra ders içeriğinizi yükleyin. Tekrar kullanmak için özel bir GPT'nin talimatlar bölümüne de yapıştırabilirsiniz.

#### Gemini
Yeni bir sohbet açın, `prompt.md` içeriğini yapıştırın, sonra ders içeriğinizi yükleyin. Tekrar kullanmak için bir Gem'in talimatlar bölümüne de yapıştırabilirsiniz.

Yapay zekâ site kodu verirse, `.html` dosyası olarak kaydedip tarayıcınızda açın. Sonuçlar yapay zekâlar arasında farklılık gösterebilir.

### Notlar

- Çıktı Arapça soru bankası olduğu için prompt Arapça yazılmıştır.
- Dosya yüklerseniz sorular yalnızca o içerikten üretilmelidir. Öğrencilerle kullanmadan önce soruları ve cevapları mutlaka kontrol edin.

### Kaynak

Orijinal prompt Twitter/X'te **هيثم الشريف | Haitham Alshareif** tarafından paylaşılmıştır. Bu depo, o promptu Claude skill'i olarak paketler ve README'yi ekler. Orijinal paylaşım: https://x.com/halshareif/status/2119532585219248171
