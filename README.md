# FLEXBOX UYGULAMA ÖDEVİ

## Servis Kartları Sayfası

---

## 🎯 Ödevin Amacı

Bu proje ile öğrenciler:

- Flex Container ve Flex Item mantığını kavrayacak
- Container özelliklerini aktif olarak kullanacak
- Item özellikleri ile esnek boyutlandırma ve hizalama yapacak
- Responsive (alt satıra düşebilen) kart yapısı oluşturacak

---

## 🧩 Proje Tanımı

Bir **"Hizmetlerimiz"** bölümü tasarlanacaktır.

Bu bölümde:

- Toplam **6 adet** servis kartı bulunacaktır
- Her kartta:
  - Başlık
  - Kısa açıklama
  - Detay butonu yer alacaktır
- Kartlar `flex-wrap` sayesinde alt satıra düşebilmelidir

---

## ✅ Flex Container Gereklilikleri

Aşağıdaki özellikler **zorunludur**:

`css
display: flex;
flex-direction: row;
flex-wrap: wrap;
justify-content: space-between; /* center veya space-around test edilebilir */
align-items: stretch;           /* center da olabilir */
gap: 20px;
`

---

## ✅ Flex Item Gereklilikleri

Her kart için:

| Özellik        | Açıklama                   |
| -------------- | -------------------------- |
| `flex-basis` | Başlangıç genişliği        |
| `flex-grow`  | Orantılı büyüme            |
| `align-self` | 1 kart farklı hizalanacak  |

## Resim 
<img src="/odev1.png" alt="Ödev Görseli" width="600">
