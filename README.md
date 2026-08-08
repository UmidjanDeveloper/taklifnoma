# Taklifnoma — Umidjon & Ezoza

## GitHub Pages'ga joylash
1. GitHub'da yangi **public** repo yarating (masalan `taklifnoma`).
2. Shu papkadagi **index.html** va **music.m4a** fayllarini repo ildiziga yuklang (Add file → Upload files → Commit).
3. Settings → Pages → *Source: Deploy from a branch*, *Branch: main / (root)* → Save.
4. 1-2 daqiqadan keyin havola tayyor: `https://<username>.github.io/taklifnoma/`

## Muhim
- `index.html` va `music.m4a` **bir papkada** turishi shart (index.html musiqani `music.m4a` nomi bilan chaqiradi).
- Sozlamalar (ism, sana, manzil, karta) `index.html` ichidagi birinchi skriptdagi `var D={...}` obyektida.
- Musiqani almashtirsangiz, yangi faylni ham `music.m4a` deb nomlang (yoki `<audio ... src="">` qiymatini o'zgartiring).
- Brauzerlar ovozli avtoplayni bloklashi mumkin: bunda musiqa ovozsiz boshlanib, mehmon ekranga birinchi teginishida (yoki surishida) avtomatik ovozga o'tadi.
