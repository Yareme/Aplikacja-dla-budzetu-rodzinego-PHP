<div align="center">

# 💰 Finans

**Bazodanowa aplikacja webowa do prowadzenia budżetu rodzinnego**

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Smarty](https://img.shields.io/badge/Smarty-F7DF1E?style=for-the-badge&logoColor=black)
![Medoo](https://img.shields.io/badge/Medoo-0F172A?style=for-the-badge)

</div>

---

## 📖 O projekcie

**Finans** to aplikacja webowa wspierająca prowadzenie budżetu rodzinnego. Dane finansowe są przechowywane w relacyjnej bazie danych, a całość pomaga uporządkować domowe wydatki w jednym miejscu.

Projekt powstał jako aplikacja zaliczeniowa. Zrealizowałem go samodzielnie, aby w praktyce poznać budowę aplikacji webowej opartej na PHP, frameworku, szablonach i warstwie dostępu do bazy danych.

## 🛠️ Technologie

| Warstwa | Technologia |
|---|---|
| Język | PHP |
| Framework | [Amelia](https://amelia-framework.eu) |
| Szablony | [Smarty](https://www.smarty.net) |
| Dostęp do bazy danych | [Medoo](https://medoo.in) |
| Baza danych | Relacyjna baza danych SQL |

## 🏗️ Architektura

Aplikacja jest zbudowana w oparciu o framework **Amelia**. Widoki są generowane przez szablony **Smarty**, dzięki czemu logika aplikacji jest oddzielona od warstwy prezentacji. Zapytania do bazy danych obsługuje lekka biblioteka **Medoo**, która upraszcza pracę z SQL i zabezpiecza zapytania przed typowymi błędami.

## 🚀 Uruchomienie lokalnie

**Wymagania:** PHP, serwer WWW (Apache, Nginx lub wbudowany serwer PHP) oraz relacyjna baza danych.

1. Sklonuj repozytorium:
   ```bash
   git clone https://github.com/Yareme/Aplikacja-dla-budzetu-rodzinego-PHP.git
   cd Aplikacja-dla-budzetu-rodzinego-PHP
   ```
2. Utwórz bazę danych i skonfiguruj dane połączenia w pliku konfiguracyjnym projektu.
3. Uruchom aplikację na lokalnym serwerze WWW z obsługą PHP.

## 🎯 Czego się nauczyłem

- Budowanie aplikacji webowej w PHP z użyciem frameworka
- Oddzielanie logiki od widoku dzięki szablonom Smarty
- Praca z bazą danych przez bibliotekę Medoo
- Projektowanie struktury bazy dla danych finansowych

## 👤 Autor

**Valentyn Yaremenko**

[GitHub](https://github.com/Yareme) · [LinkedIn](https://linkedin.com/in/valentyn-yaremenko)
