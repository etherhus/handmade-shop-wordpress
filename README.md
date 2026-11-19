# Handmade Shop - sklep WooCommerce z utwardzonym środowiskiem WordPress

Sklep internetowy z rękodziełem: breloczkami, wyrobami szydełkowymi, biżuterią i drobnymi akcesoriami wykonanymi ręcznie. Sklep jest przeznaczony dla osób szukających oryginalnych prezentów oraz dla twórców potrzebujących platformy z charakterem do sprzedaży swoich prac.

Projekt powstaje na WordPressie z WooCommerce w skonteneryzowanym środowisku (Docker Compose, MariaDB).

 - **Autor:** Klaudia Fiedur (grupa Cw1S, nr indeksu: 58486)
 - **Prowadzący:** mgr inż. Przemysław Żarnecki
 - **Uczelnia:** IDEIS, Semestr Zimowy 2026/2027

## Stos technologiczny
- WordPress 7.1.4
- PHP 8.5
- MariaDB 11.8.9
- WooCommerce 11.3.0
- Docker Compose

## Architektura i funkcje
_do uzupełnienia_

## Instrukcja uruchomienia lokalnego
1. Klonowanie repozytorium `git clone https://github.com/etherhus/handmade-shop-wordpress.git`
2. `cp .env.example .env`
3. Uzupełnienie w `.env` czterech zmiennych: nazwa bazy, użytkownika oraz dwa hasła (własne)
4. Uruchomienie środowiska: `docker compose up -d`
5. Dostęp w przeglądarce: `http://localhost:8080/`
6. Przejście instalatora wordpress, zalogowanie się
7. Instalacja wtyczki WooCommerce `Wtyczki -> Dodaj nową`

- _Środowisko startuje z czystymi wolumenami, automatyczny import bazy i wtyczki zostanie dodany w kolejnych etapach_


## Pomiary jakości i audyty
_do uzupełnienia_

## Źródła materiałów
_do uzupełnienia_