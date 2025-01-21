---
sidebar_position: 1
---
# Start

## **Cel projektu**
Aplikacja umożliwia uczniom udział w konkursach tworzonych przez administratorów serwisu. Aplikacja oferuje rejestrację, zapis do konkursu oraz możliwość wypełniania pytań przygotowanych przez administratora. Każdy konkurs składa się z testów z pytaniami jednokrotnego wyboru, co umożliwia skuteczną ocenę wiedzy uczestników. Konkursy mogą mieć charakter wieloetapowy.

## **Opis funkcjonalny systemu**
### **System**
- Umożliwia rejestrację nowych użytkowników, weryfikując, czy są uczniami i czy ich szkoła znajduje się na liście szkół.
- Umożliwia logowanie użytkowników do systemu.
- Umożliwia zmianę i resetowanie hasła użytkownika w przypadku jego utraty.
- Pozwala użytkownikowi zapisać się na test.
- Umożliwia użytkownikowi wzięcie udziału w przypisanych do niego testach.
- Umożliwia wgląd w wyniki testów użytkownika.
- Umożliwia porównywanie wyników użytkownika z innymi użytkownikami poprzez anonimowy ranking.
- Pozwala na przegląd wcześniej rozwiązanych testów użytkownika.
- Wspiera przypisywanie użytkowników do konkretnych testów.
- Umożliwia ustawienie widoczności testu jako otwartą lub ograniczoną do zaproszonych użytkowników.
- Pozwala na publikację lub cofnięcie publikacji rankingu testu.

### **Administrator**
- Może dodawać nowych użytkowników do systemu.
- Może anonimizować dane użytkownika.
- Może dodawać nowe szkoły do listy.
- Może edytować dane istniejących szkół.
- Może importować dane szkół z bazy RSPO.
- Może usuwać szkoły z listy.
- Ma możliwość tworzenia nowych testów.
- Może edytować istniejące testy.
- Może ustawić typ testu jako zdalny lub lokalny.
- Może ustawić datę publikacji testu.
- Może wycofać publikację testu.
- Może przeglądać ranking testu.

### **Użytkownik**
- Może zarejestrować się w systemie (po spełnieniu wymagań).
- Może logować się do systemu.
- Może zmienić lub zresetować swoje hasło.
- Może zapisać się na test.
- Może wziąć udział w przypisanych testach.
- Ma dostęp do wyników swoich testów.
- Może porównywać swoje wyniki z innymi użytkownikami w anonimowym rankingu.
- Ma dostęp do przeglądu swoich wcześniej rozwiązanych testów.

## **Opis Technologiczny**
Część backendowa projektu została napisana w PHP z użyciem frameworka:

- **Laravel 11**
Frontend powstał z użyciem następujących technologii:
- **Tailwind CSS**
- **Vue**
- **TypeScript**

Całość komunikacja pomiędzy frontendem i backendem została wykonana z użyciem technologii **inertia.js**.

Dane aplikacji przechowywane są w bazie danych PostgreSQL. Środowisko developerskie oraz produkcyjne zostało wykonane z użyciem Dockera i Nginx. Do obsługi cache wykorzystana została baza danych Redis

## **Instrukcję lokalnego uruchomienia systemu**
1. Zainstaluj na swojej ulubionej dystrybucji Linuxa Dockera, docker-compose i make.
2. Sklonuj repozytorium: git clone [https://github.com/blumilksoftware/environment]
3. Otwórz terminal i przejdź do katalogu, environment.
4. Przygotuj środowisko: **make init**
5. Uruchom środowisko: **make run**
6. Sklonuj repozytorium: git clone [https://github.com/blumilksoftware/interns2024b]
7. Otwórz terminal i przejdź do katalogu interns2024b
8. Stwórz plik .env i dostosuj jego konfigurację: cp .env.example .env
9. Przygotuj aplikację do pracy: **make init**
10. Uruchom projekt: **make dev**
11. Uruchom system kolejek: **make queue**
12. Projekt będzie dostępny pod adresem [http://interns2024b.blumilk.localhost]

