# Blog Sayt

Django yordamida yaratilgan oddiy blog sayt.

## Imkoniyatlar

- Postlarni bosh sahifada kartochkalar ko'rinishida ko'rsatish
- Har bir post uchun alohida sahifa
- Saytdan post qo'shish formasi
- Admin panel orqali postlarni boshqarish
- Bootstrap 5 bilan zamonaviy dizayn

## Texnologiyalar

- Python 3
- Django
- Bootstrap 5
- SQLite

## O'rnatish

1. Repozitoriyni yuklab oling:

```
git clone https://github.com/cyber0017/blog_sayt.git
cd blog_sayt
```

2. Virtual muhit yarating va ishga tushiring:

```
python -m venv .venv
.venv\Scripts\activate
```

3. Django o'rnating:

```
pip install django
```

4. Migratsiyalarni bajaring va admin yarating:

```
python manage.py migrate
python manage.py createsuperuser
```

5. Serverni ishga tushiring:

```
python manage.py runserver
```

Sayt `http://127.0.0.1:8000/` manzilida ochiladi, admin panel esa `/admin/` da.

## Muallif

[cyber0017](https://github.com/cyber0017)