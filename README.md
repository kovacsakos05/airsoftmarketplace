# Airsoft Marketplace

Egy webes alkalmazás, ahol felhasználók airsoft fegyvereket és kiegészítőket tudnak eladni és vásárolni.

---

## Tartalom
- [Projekt Leírás](#projekt-leírás)
- [Funkciók](#funkciók)
- [Telepítés](#telepítés)
- [Fejlesztők](#fejlesztők)

---

## Projekt Leírás
Az Airsoft Marketplace egy teljes stack webalkalmazás (Angular frontend + Laravel backend), amely lehetővé teszi:
- Fegyverek és kiegészítők feltöltését
- Termékek közötti böngészést
- Regisztrációt, bejelentkezést
- Rendelések leadását kiszállítási opcióval
- Profil kezelést (profilkép feltöltés, adatok megjelenítése)

**Backend:** Laravel 10  
**Frontend:** Angular 17

---

## Funkciók
- 👤 Felhasználói regisztráció és bejelentkezés
- 🏢 Saját termékek feltöltése
- 🛒 Rendelés leadás kiszállítással
- 🔍 Termékek szűrése és keresése
- 📤 Profilkép feltöltés
- 🔄 Termék eladás utáni automatikus törlés vagy eladottá állítás

---

## Telepítés

### Kicsomagolás
- Csomagoljuk ki a backend_final.rar -t
- Csomagoljuk ki a node_modules.rar -t
- Csomagoljuk ki a node_modules_reszlet.rar -t a node_modules -ba
- Ezek után helyezzük bele a frontend mappába a node_modules -t

### Backend (Laravel, powershell)
```bash
cd backend_airsoft_marketplace
composer install
php artisan migrate --seed
php artisan serve
```
A backend most elérhető lesz a `http://127.0.0.1:8000` címen.

### Adatbázis feltöltése
- Nyissuk meg a phpmyadmint (xampp control panel -> mysql -> admin)
- Nyissuk meg a database_final.sql -t, majd másoljuk ki az Insert into utasításokat
- Nyissuk meg a phpmyadminban a backend_airsoft_marketplace adatbázist, majd az sql lekérdezéseket (fent a menüsorban SQL)
- Majd ezek után másoljuk be a vágólapon lévő utasításokat és futtasuk le

### Frontend (Angular, cmd)
```bash
cd Frontend
npm install
ng serve
```
A frontend most fut a `http://localhost:4200` alatt.

---

## Fejlesztők
- **Kovács Ákos**
- **Kovács Martin**

---

## Megjegyzés
Ez a projekt oktatási célokból készült. A rendszer egyszerűsített modelleket tartalmaz.

> Köszönjük, hogy megnézted a projektet! 🚀
