# Aplikacja Mobilna GPS i Krokomierz

## Opis projektu

Aplikacja mobilna stworzona w środowisku MIT App Inventor umożliwia śledzenie lokalizacji użytkownika oraz pomiar liczby kroków w określonym przedziale czasu (od momentu naciśnięcia przycisku **Start** do **Stop**).

Dane zebrane podczas działania aplikacji są zapisywane lokalnie i mogą być przeglądane w formie dziennika aktywności.

---

## Funkcjonalności

* Śledzenie lokalizacji GPS
* Zliczanie kroków (krokomierz)
* Rozpoczynanie i zatrzymywanie pomiaru (Start / Stop)
* Zapisywanie danych do pamięci lokalnej (TinyDB)
* Przeglądanie historii pomiarów (dziennik)
* Rejestrowanie daty i czasu pomiaru

---

## Wykorzystane technologie

* MIT App Inventor
* LocationSensor (GPS)
* Pedometer (akcelerometr)
* TinyDB (lokalna baza danych)

---

## Instalacja

### Opcja 1 – instalacja aplikacji (APK)

1. Pobierz plik `.apk` z repozytorium GitHub
2. Przenieś plik na urządzenie z systemem Android
3. Otwórz plik `.apk`
4. Włącz instalację z nieznanych źródeł (jeśli wymagane)
5. Zainstaluj aplikację

---

### Opcja 2 – import projektu (.aia)

1. Pobierz plik `.aia` z repozytorium
2. Wejdź na stronę MIT App Inventor
3. Wybierz: **Projects → Import project (.aia)**
4. Zaimportuj plik
5. Uruchom lub edytuj projekt

---

## Instrukcja użytkowania

1. Uruchom aplikację
2. Przyznaj wymagane uprawnienia (GPS, aktywność fizyczna)
3. Naciśnij **Start**, aby rozpocząć pomiar
4. Poruszaj się – aplikacja zlicza kroki i zapisuje lokalizację
5. Naciśnij **Stop**, aby zakończyć pomiar
6. Sprawdź zapis w dzienniku

---

## Struktura zapisywanych danych

Każdy zapis zawiera:

* datę
* godzinę
* szerokość geograficzną
* długość geograficzną
* liczbę kroków

---

## Wymagania systemowe

* Android 8.0 lub nowszy
* Dostęp do GPS
* Akcelerometr
* Wolna pamięć na urządzeniu

---

## Uwagi

* Dokładność GPS może zależeć od warunków otoczenia
* Krokomierz może być mniej dokładny przy niestandardowych ruchach
* Długotrwałe użycie GPS wpływa na zużycie baterii

---

## Pliki w repozytorium

* `app.apk` – gotowa aplikacja do instalacji
* `projekt.aia` – plik projektu MIT App Inventor
* `README.md` – dokumentacja projektu
