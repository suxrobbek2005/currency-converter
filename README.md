# Currency Converter

Bu loyiha **Currency Converter** dasturini yaratishga bag‘ishlangan. Ushbu dastur real vaqt rejimida valyuta kurslarini [O‘zbekiston Milliy banki](https://nbu.uz/uz/exchange-rates/json/) API orqali olish va valyutalar o‘rtasida konvertatsiya qilish imkonini beradi.

---

## Loyihaning Tavsifi

**Currency Converter** dasturi quyidagi funksiyalarni bajaradi:
- Berilgan API orqali valyuta kurslarini oladi.
- Foydalanuvchidan konvertatsiya qilinadigan summa va valyutalarni kiritishni so‘raydi.
- Turli valyutalar (masalan, USD, EUR, RUB, UZS) o‘rtasida konvertatsiya qiladi.
- Hisoblash natijasini foydalanuvchiga aniq va qulay shaklda ko‘rsatadi.

---

## O‘rganiladigan Maqsadlar

Ushbu loyiha orqali talabalar:
1. Python dasturlash tilida API-lar bilan ishlashni o‘rganadilar.
2. `requests` kutubxonasidan foydalanib, HTTP so‘rovlar qilishni tushunadilar.
3. JSON formatdagi ma’lumotlarni o‘qish va qayta ishlashni o‘zlashtiradilar.
4. Konsolga asoslangan foydalanuvchi interfeyslarini loyihalashtirish amaliyotini oladilar.
5. Muammolarni hal qilish va xatolarni tuzatish bo‘yicha ko‘nikmalarini oshiradilar.

---

## Talablar

Loyihani boshlashdan oldin quyidagilar mavjud bo‘lishi kerak:
- Kompyuteringizda o‘rnatilgan Python 3.
- Python dasturlash asoslari bo‘yicha bilim.
- API orqali ma’lumotlarni olish uchun internet aloqasi.

### Kerakli Kutubxonalar
Kerakli kutubxonani o‘rnatish uchun quyidagi buyruqni ishlating:
```bash
pip install requests
```

---

## Ko‘rsatmalar

1. **Loyihani tayyorlang:**
   - `currency-converter` nomli yangi papka yarating.
   - Papka ichida `converter.py` nomli Python faylini yarating.

2. **API bilan ishlash:**
   - Ushbu URL orqali valyuta kurslarini oling: [https://nbu.uz/uz/exchange-rates/json/](https://nbu.uz/uz/exchange-rates/json/).
   - Python dasturida `json` moduli yordamida APIdan olingan ma’lumotlarni tahlil qiling.

3. **Foydalanuvchi ma’lumotlarini oling:**
   - Foydalanuvchidan quyidagilarni kiritishni so‘rang:
     - Konvertatsiya qilinadigan summa.
     - Qaysi valyutadan konvertatsiya qilinadi.
     - Qaysi valyutaga konvertatsiya qilinadi.

4. **Konvertatsiya amalga oshiring:**
   - Kurs asosida hisob-kitob qiling va natijani oling.

5. **Natijani ko‘rsating:**
   - Foydalanuvchiga hisoblangan natijani aniq va tushunarli formatda chiqaring.

6. **Qo‘shimcha Vazifalar (ixtiyoriy):**
   - Noto‘g‘ri ma’lumot kiritilganda xatoliklarni aniqlang va foydalanuvchiga ogohlantirish bering.
   - Foydalanuvchiga dasturdan chiqmasdan bir nechta konvertatsiya qilish imkonini bering.
   - Konvertatsiya natijalarini faylga saqlash funksiyasini qo‘shing.

---

## Natija Namoyishi

```
Currency Converter dasturiga xush kelibsiz!

Mavjud valyutalar: USD, EUR, RUB, UZS va boshqalar.

Summani kiriting: 100
Qaysi valyutadan konvertatsiya qilmoqchisiz (masalan, USD): USD
Qaysi valyutaga konvertatsiya qilmoqchisiz (masalan, UZS): UZS

Natija: 100 USD = 1,200,000 UZS
```

---

## Topsirish

- `converter.py` faylini topshiring.
- Dastur xatosiz ishlashi va yuqoridagi talablarni bajarishi kerak.

---

## Manbalar

- [Python `requests` kutubxonasi hujjati](https://docs.python-requests.org/en/latest/)
- [Python `json` moduli hujjati](https://docs.python.org/3/library/json.html)
- [Valyuta kurslari API](https://nbu.uz/uz/exchange-rates/json/)

Omad va muvaffaqiyatli dasturlash! 🚀
```
