## 🧠 **Humanizer API V2 is live!**

```py
import requests

text = ""
author_id = ""
writing_style = ""
timestamp = "null"

url = f"http://ryzenth.randydev.my.id/v2/fast/ai/r/Ryzenth-Humanize-05-06-2025"

params = {
  "text": text,
  "author_id": author_id,
  "writing_style": writing_style,
  "timestamp":timestamp
}

response = requests.get(url, params=params).json()
print(response)
```
## AI Generated by Ryzenth API

### 🧾 **📚 Daftar `writing_style` + Contoh**

| Writing Style       | Deskripsi                                         | Contoh Kalimat                                                                               |
| ------------------- | ------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| `"santai"`          | Gaya ngobrol sehari-hari, ringan dan chill        | *"Santai aja kali, nggak usah baperan tiap dikritik\~"*                                      |
| `"galak"`           | Tegas, nyolot, kadang terkesan marah              | *"Udah dibilang jangan spam! Susah banget sih ngerti bahasa manusia?!"*                      |
| `"alay"`            | Campuran huruf besar kecil, lebay, penuh ekspresi | *"HehH\~ jGn nAnTiiN aQ lg yaaa 😩💔"*                                                       |
| `"spoken"`          | Kayak ngomong langsung, natural & luwes           | *"Gue rasa sih ini ide yang oke banget, tinggal eksekusi aja."*                              |
| `"narrative"`       | Gaya penceritaan seperti cerita pendek            | *"Waktu itu gue masih inget, sore itu langit mendung dan hati gue hampa..."*                 |
| `"journalistic"`    | Objektif, padat, seperti artikel berita           | *"Pada tanggal 4 Juni 2025, sistem baru resmi dirilis oleh tim pengembang."*                 |
| `"blog-like"`       | Panjang, naratif, personal                        | *"Jadi kemarin gue nyobain sistem ini. Awalnya skeptis sih, tapi lama-lama kerasa bedanya."* |
| `"copywriting"`     | Gaya promosi, persuasif                           | *"Mau hidup lebih simpel dan cepet? Cobain Ryzenth GO API sekarang juga!"*                   |
| `"kode-an"`         | Gaya dev yang ngomong ke sesama dev               | *"Lu tinggal panggil aja function-nya, parsing respons-nya ke dot gitu. Simple."*            |
| `"deep-reflective"` | Dalam, puitis, kayak konten malam-malam           | *"Mungkin, kadang kita cuma perlu diam... biar dunia yang jawab."*                           |
| `"toxic-humor"`     | Satir, dark, kadang sarkas                        | *"Tenang, kalau gagal lagi tinggal nyalahin semesta. Biasa kok."*                            |

---

### 💡 Cara Pakai:

```json
{
  "writing_style": "alay"
}
```
