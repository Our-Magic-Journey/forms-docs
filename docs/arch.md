---
sidebar_position: 3
---

# Rejestr Decyzji Architektonicznych

### **Wybór Laravel**

**Status**: Zaakceptowany

#### **Kontekst:**

Aby ustanowić solidne fundamenty backendowe, potrzebowaliśmy frameworka, który zapewnia kompleksowe funkcje i wsparcie społeczności.

#### **Decyzja:**

Wybraliśmy **Laravel** ze względu na jego popularność, obszerną ekosystem bibliotek i dobrze napisaną dokumentację. Znajomość Laravel przez zespół backendowy była kluczowym czynnikiem, umożliwiającym szybki rozwój i integrację.

#### **Konsekwencje:**

- **Zalety**: Dostęp do wielu dojrzałych pakietów, silne wsparcie społeczności i obszernie dokumentacja.
- **Wady**: Ścisłe powiązanie z PHP może ograniczać elastyczność, jeśli w przyszłości zajdzie potrzeba zmiany technologii.

### **Wybór PHP**

**Status**: Zaakceptowany

#### **Kontekst:**

Wybór frameworka backendowego Laravel ograniczył nas do określonego języka backendowego.

#### **Decyzja:**

Wybraliśmy **PHP** jako język backendowy z powodu jego kompatybilności z Laravel i istniejącego doświadczenia zespołu.

#### **Konsekwencje:**

- **Zalety**: Znajomość wśród członków zespołu, łatwość integracji z Laravel.
- **Wady**: Potencjalne ograniczenia wydajności w porównaniu do nowszych języków w scenariuszach o dużym obciążeniu.

### **Wybór Tailwind UI**

**Status**: Zaakceptowany

#### **Kontekst:**

Aby stworzyć nowoczesny i responsywny projekt frontendowy, potrzebowaliśmy biblioteki komponentów UI.

#### **Decyzja:**

Wybraliśmy **Tailwind UI** za jego konfigurowalne komponenty i podejście CSS typu utility-first, co umożliwia łatwą modyfikację i responsywność.

#### **Konsekwencje:**

- **Zalety**: Szybkie prototypowanie, spójność projektowa i łatwość dostosowania.
- **Wady**: Krzywa uczenia się dla członków zespołu, którzy nie są zaznajomieni z metodologią utility-first CSS.

### **Wybór Vue.js**

**Status**: Zaakceptowany

#### **Kontekst:**

Aby ułatwić rozwój interaktywnego interfejsu użytkownika, potrzebowaliśmy nowoczesnego frameworka frontendowego.

#### **Decyzja:**

Wybraliśmy **Vue.js** ze względu na jego prostotę, architekturę opartą na komponentach i silną integrację z Laravel za pomocą InertiaJS.

#### **Konsekwencje:**

- **Zalety**: Zwiększona jakość doświadczeń użytkownika, modularna organizacja kodu i wsparcie społeczności.
- **Wady**: Krzywa uczenia się dla członków zespołu, którzy są nowi w tym frameworku.


### **Wybór TypeScript**

**Status**: Zaakceptowany

#### **Kontekst:**

Aby poprawić jakość kodu i utrzymanie, poszukiwaliśmy rozwiązania do statycznego typowania w naszym kodzie JavaScript.

#### **Decyzja:**

Zastosowaliśmy **TypeScript**, aby zapewnić statyczne typowanie, co zwiększa czytelność i pozwala na wcześniejsze wykrywanie błędów podczas rozwoju.

#### **Konsekwencje:**

- **Zalety**: Zwiększona przejrzystość kodu, lepsze wsparcie narzędzi i mniejsze ryzyko błędów w czasie wykonywania.
- **Wady**: Dodatkowy krok kompilacji i potencjalna krzywa uczenia się dla członków zespołu, którzy nie znają TypeScript.

### **Wybór PostgreSQL**

**Status**: Zaakceptowany

#### **Kontekst:**

Dla naszych potrzeb zarządzania danymi potrzebowaliśmy niezawodnego systemu zarządzania relacyjną bazą danych.

#### **Decyzja:**

Wybraliśmy **PostgreSQL** z powodu jego dojrzałości, obszernych funkcji i silnej integracji z Laravel, a także doświadczenia zespołu.

#### **Konsekwencje:**

- **Zalety**: Solidna wydajność, zaawansowane funkcje, takie jak wsparcie dla JSON, i łatwa integracja z istniejącymi narzędziami.
- **Wady**: Wymaga starannego projektowania schematów, aby maksymalizować wydajność.

### **Wybór Mailpit**

**Status**: Zaakceptowany

#### **Kontekst:**

Aby ułatwić testowanie e-maili podczas rozwoju, potrzebowaliśmy narzędzia, które mogłoby łatwo symulować wysyłanie wiadomości.

#### **Decyzja:**

Wybraliśmy **Mailpit** ze względu na jego prostotę w testowaniu i przeglądaniu wysłanych wiadomości e-mail, a także możliwość uruchomienia lokalnie przy użyciu Dockera.

#### **Konsekwencje:**

- **Zalety**: Uproszczony proces testowania e-maili i znajomość podobnych narzędzi, takich jak MailTrap.
- **Wady**: Ograniczone funkcje w porównaniu do pełnoprawnych usług dostarczania e-maili.

### **Wybór Vite**

**Status**: Zaakceptowany

#### **Kontekst:**

Dla procesu budowy frontendowej potrzebowaliśmy szybkiego i nowoczesnego narzędzia, które wspiera współczesny rozwój JavaScriptu.

#### **Decyzja:**

Wybraliśmy **Vite** ze względu na szybki czas uruchamiania, wsparcie dla nowoczesnych technologii i doskonałą integrację z Laravel.

#### **Konsekwencje:**

- **Zalety**: Zwiększona szybkość rozwoju i wydajny proces budowy.
- **Wady**: Potencjalne problemy z kompatybilnością ze starszymi bibliotekami, które nie są zaprojektowane dla nowoczesnych narzędzi.


### **Wybór Docker**

**Status**: Zaakceptowany

#### **Kontekst:**

Aby zapewnić spójne środowiska deweloperskie wśród członków zespołu, potrzebowaliśmy rozwiązania do konteneryzacji.

#### **Decyzja:**

Wybraliśmy **Docker** za jego zdolność do tworzenia izolowanych środowisk deweloperskich, co ułatwia zarządzanie zależnościami i wersjami.

#### **Konsekwencje:**

- **Zalety**: Uproszczona konfiguracja środowiska i zapewnienie spójności w różnych etapach rozwoju.
- **Wady**: Dodatkowe obciążenie w zarządzaniu środowiskami kontenerowymi i potencjalna złożoność dla nowicjuszy.

### **Wybór PHPStorm**

**Status**: Zaakceptowany

#### **Kontekst:**

Aby skutecznie wspierać nasz proces rozwoju, potrzebowaliśmy zaawansowanego IDE dedykowanego dla programistów PHP.

#### **Decyzja:**

Wybraliśmy **PHPStorm** ze względu na jego kompleksowe funkcje, które zwiększają wydajność i wspierają proces tworzenia oprogramowania.

#### **Konsekwencje:**

- **Zalety**: Zaawansowane narzędzia debugowania, zintegrowane zarządzanie wersjami i wsparcie dla rozwoju PHP.
- **Wady**: Jest to płatne narzędzie, co może być istotne dla zespołów z ograniczonym budżetem.

### **Wybór Git**

**Status**: Zaakceptowany

#### **Kontekst:**

Aby efektywnie zarządzać kontrolą wersji, potrzebowaliśmy systemu, który byłby zarówno niezawodny, jak i znany zespołowi.

#### **Decyzja:**

Wybraliśmy **Git** jako nasz system kontroli wersji ze względu na jego powszechne użycie i znajomość wśród członków zespołu.

#### **Konsekwencje:**

- **Zalety**: Ułatwia współpracę, skutecznie śledzi zmiany i wspiera strategię rozgałęziania i łączenia.
- **Wady**: Wymaga zrozumienia przepływów pracy i może być złożony dla nowych użytkowników.