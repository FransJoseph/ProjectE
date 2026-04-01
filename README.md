# Aplikacja Mobilna GPS i Krokomierz

## Opis projektu

Aplikacja mobilna stworzona w środowisku MIT App Inventor umożliwia śledzenie lokalizacji użytkownika oraz pomiar liczby kroków w określonym przedziale czasu.

Dane zebrane podczas działania aplikacji są zapisywane lokalnie i mogą być przeglądane w formie dziennika

## Funkcjonalności

* Śledzenie lokalizacji GPS
* Zliczanie kroków (krokomierz)
* Rozpoczynanie i zatrzymywanie pomiaru
* Zapisywanie danych do pamięci lokalnej (TinyDB)
* Przeglądanie historii pomiarów (dziennik)
* Rejestrowanie daty i czasu pomiaru

## Wykorzystane technologie

* MIT App Inventor
* LocationSensor (GPS)
* Pedometer (akcelerometr)
* TinyDB (lokalna baza danych)

## Instalacja

1. Pobierz plik `.apk` z repozytorium GitHub
2. Przenieś plik na urządzenie z systemem Android
3. Otwórz plik `.apk`
4. Włącz instalację z nieznanych źródeł (jeśli wymagane)
5. Zainstaluj aplikację

## Instrukcja użytkowania

1. Uruchom aplikację
2. Przyznaj wymagane uprawnienia do lokalizacji
3. Naciśnij **Rozpocznij pomiar**, aby rozpocząć pomiar
4. Poruszaj się – aplikacja zlicza kroki i zapisuje lokalizację
5. Naciśnij **Zatrzymaj pomiar**, aby zakończyć pomiar
6. Sprawdź zapis w dzienniku

## Struktura zapisywanych danych

Każdy zapis zawiera:

* datę
* godzinę
* szerokość geograficzną
* długość geograficzną
* liczbę kroków

## Wymagania systemowe

* Android 8.0 lub nowszy
* Dostęp do GPS
* Akcelerometr
* Wolna pamięć na urządzeniu

## Uwagi

* Dokładność GPS może zależeć od warunków otoczenia
* Krokomierz może być mniej dokładny przy niestandardowych ruchach
* Długotrwałe użycie GPS wpływa na zużycie baterii

## Pliki w repozytorium

* `app.apk` – gotowa aplikacja do instalacji
* `README.md` – dokumentacja projektu
