#  Discord Pokémon Botu

Discord için geliştirilmiş bu eğlenceli **Pokémon Savaş Botu**, kullanıcılara rastgele Pokémon (veya özel sınıflar: 🧙 Wizard, 🥋 Fighter, 🗡️ Assasin) vererek savaşma, geliştirme ve bilgi alma imkanı tanır!
---

## ⚔️ Oyun Özeti

- `!go` komutuyla bir Pokémon (ya da özel sınıf) elde edin.
- `!attack @kullanici` komutuyla savaşa girin.
- `!info` komutuyla Pokémon bilgilerinizi görüntüleyin.
- `!feed` komutuyla Pokemonunuzun sağlığını yenileye bilirsiniz.
- Her Pokémon’un kendine özel **güç** ve **sağlık** değerleri vardır.
- Özel sınıfların özel saldırı mekanikleri vardır.

---

## Özellikler

| Özellik                  | Açıklama |
|--------------------------|----------|
| 🎲 Rastgele Pokémon      | `!go` komutu ile 1-1000 arası rastgele Pokémon |
| 🧙 Wizard                | Bazen saldırıları kalkanla engeller |
| 🥋 Fighter               | Saldırıda ek güç kazanır |
| 🗡️ Assasin              | Kritik çarpanla saldırır |
| 🍗 Besleme sistemi      | HP yenilemek için `feed()` |
| 📸 Görsel desteği        | Pokémon resmi otomatik gösterilir |
| 🌐 API kullanımı         | [PokeAPI](https://pokeapi.co/) üzerinden bilgi alınır |

---

## 🚀 Kurulum

```bash
git clone https://github.com/yourusername/discord-pokemon-botu.git
cd discord-pokemon-botu
pip install -r requirements.txt
