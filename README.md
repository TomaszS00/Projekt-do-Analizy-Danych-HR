# Projekt do Analizy Danych HR
Projekt Analizy Danych HR jest realizowany w celu identyfikacji czynników wpływających na decyzje pracowników o rezygnacji z pracy w aktualnej firmie.

Celem biznesowym badania danych tego typu jest przyczynienie się do lepszego funkcjonowania i wydajności firmy oraz jej pracowników poprzez zmniejszenie poziomu rotacji wewnątrz przedsiębiorstwa dzięki trafnym decyzjom biznesowym podejmowanym w oparciu o wcześniej przygotowane analizy danych.

# Źródła danych
Do realizacji projektu wykorzystano zbiór danych The People Analytics Starter Dataset. Zbiór danych zawiera informacje dotyczące pracowników fikcyjnej firmy, takie jak data zatrudnienia, data odejścia, wiek, płeć, wykształcenie, wynagrodzenie, dział, poziom stanowiska, lokacja czy informacje o możliwości pracy zdalnej.
Żródło: [People Analytics Starter](https://www.stevenshoemaker.me/datasets/starter)

# Zakres Projektu
Realizacja projektu obejmuje:
1.	Przygotowanie mechanizmu do ładowania danych
2.	Obróbka zebranych danych
3.	Przygotowanie hurtowni danych w celu przechowywania zgromadzonych danych
4.	Stworzenie profesjonalnego rozwiązania BI w celu prezentacji zgromadzonych danych w sposób przystępny dla użytkownika końcowego
5.	Udostępnienie gotowego rozwiązania klientowi

# Harmonogram Projektu
1.	Pozyskanie danych: 2 tygodnie
2.	Przygotowanie mechanizmu do ładowania danych: 2 tygodnie
3.	Obróbka danych: tydzień
4.	Przygotowanie rozwiązania do przechowywania danych (hurtowni): 2 tygodnie
5.	Stworzenie rozwiązania Business Intelligence: 5 dni roboczych
6.	Niezbędne poprawki w systemie/rozwiązywanie zgłoszonych problemów: 3 dni robocze
7.	Udostępnienie rozwiązania BI grupie docelowej: 1 dzień roboczy

# Wymagania Funkcjonalne
1.	Integracja źródeł danych - aplikacja musi pozwalać na przetwarzanie oraz czyszczenie danych z różnych źródeł w tym z baz danych oraz plików CSV
2.	Aktualizacja danych – wymaganie to powinno zapewnić że, aplikacja wspiera funkcjonalność dotyczącą automatycznej aktualizacji danych w hurtowni w przypadku pojawienia się nowych danych
3.	Przetwarzanie oraz integracja danych – zapewnienie możliwości przetwarzania oraz integracji danych z różnych źródeł tak aby były zgodne z wymaganiami hurtowni danych oraz umożliwiły przeprowadzanie analiz
4.	Obsługa wyjątków – aplikacja powinna umożliwiać obsługę wyjątków czyli pozwolić na wykluczenie rekordów danych z analizy z powodów uzasadnionych biznesowo
5.	Integracja z narzędziami Business Intelligence – wymaganie odnosi się do zapewnienia możliwości integracji hurtowni danych z narzędziami BI takimi jak np. PowerBI w celu prezentacji wyników analizy danych oraz ich raportowania
6.	Generowanie Raportów oraz Wizualizacji – zapewnienie funkcjonalności dotyczącej generowania raportów a także wizualizacji różnego typu zarówno za pomocą wykresów jak i tabeli z danymi (raw data)
7.	Filtrowanie danych w narzędziu Business Intelligence
8.	Analiza danych: aplikacja powinna umożliwiać analizę danych pod kątem wpływu rozmaitych czynników na rotację pracowników

# Wymagania Niefunkcjonalne
1.	Aktualność danych – aplikacja powinna gwarantować dostęp do jak najbardziej aktualnych danych
2.	Przyjazny dla użytkownika interfejs – aplikacja powinna być łatwa w obsłudze dla klientów biznesowych oraz osób nietechnicznych, tak aby mogli oni samodzielnie korzystać z dostarczonych danych oraz wizualizacji
3.	Bezpieczeństwo danych – aplikacja powinna zapewniać, że dane są przechowywane i przetwarzane w sposób bezpieczny zgodnie ze wszelkimi regulacjami dotyczącymi ochrony danych osobowych takich jak RODO czy regulacje GDPR
4.	Skalowalność – w celu umożliwienia dodawanie nowych funkcjonalności w przyszłości oraz łatwe dodawanie dużych wolumenów danych
5.	Wydajność – aplikacja musi zapewnić wydajny sposób działania bez opóźnień i przestojów niezależnie od mocy obliczeniowej czy systemu operacyjnego
6.	Dostępność – aplikacja powinna zapewnić stabilne działanie oraz dostęp do danych przez całą dobę, nie powinna być podatna na awarię czy przerwy techniczne

# Technologie
1.	Microsoft SQL Server Management Studio - narzędzie do zarządzania bazą danych oraz wykonywania zapytań SQL. 
    Umożliwia ono przechowywanie danych w hurtowni danych.
3.	SQL Server Integration Services jest to narzędzie ETL służące do pobierania, przetwarzania oraz ładowania danych.
4.	Power BI – narzędzie typu Business Intelligence służące między innymi do wizualizacji oraz analizy danych

# Autor
Tomasz Sadlik

# Informacje Dodatkowe
Projekt stworzony na potrzeby przedłożenia w Wyższej Szkole Ekonomii i Informatyki w Krakowie
