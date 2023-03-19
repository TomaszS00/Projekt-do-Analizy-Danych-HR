# Projekt do Analizy Danych HR
Projekt Analizy Danych HR jest realizowany w celu identyfikacji czynników wpływających na decyzje pracowników o rezygnacji z pracy w aktualnej firmie. 

Celem biznesowym badania danych tego typu jest przyczynienie się do lepszego funkcjonowania i wydajności firmy oraz jej pracowników poprzez zmniejszenie poziomu rotacji wewnątrz przedsiębiorstwa dzięki trafnym decyzjom biznesowym podejmowanym w oparciu o wcześniej przygotowane analizy danych. 
# Źródła danych
Do realizacji projektu wykorzystano zbiór danych The People Analytics Starter Dataset.
Zbiór danych zawiera informacje dotyczące pracowników fikcyjnej firmy, takie jak data zatrudnienia, data odejścia, wiek, płeć, wykształcenie, wynagrodzenie, dział, poziom stanowiska, lokacja czy informacje o możliwości pracy zdalnej.
Żródło: [People Analytics Starter](https://www.stevenshoemaker.me/datasets/starter)
# Wymagania Funkcjonalne
1.	System musi pozwalać na przetwarzanie danych z baz danych oraz plików CSV
2.	System powinien wspierać funkcjonalność dotyczącą automatycznej aktualizacji danych w hurtowni w przypadku pojawienia się nowych danych
3.	System powinien umożliwiać przetwarzanie oraz integrację danych z różnych źródeł tak aby nadawały się do dalszej analizy
4.	System musi umożliwiać użytkownikom obsługę wyjątków czyli pozwolić na wykluczenie rekordów danych z analizy z powodów uzasadnionych biznesowo
5.	Hurtownia danych powinna umożliwiać integrację z narzędziami Business Inteligence np. PowerBi w celu prezentacji wyników analizy danych oraz ich raportowania
6.	System powinien umożliwiać analizę oraz wizualizacje danych pod kątem wpływu rozmaitych czynników na decyzję pracowników o zmianie miejsca zatrudnienia
# Wymagania Niefunkcjonalne
1.	System powinien umożliwiać szybką analizę dużych zbiorów danych oraz szeroką dostępność przez całą dobę, nie powinien być również podatny na wszelkie awarie oraz przerwy techniczne
2.	System powinien wspierać odświeżanie źródeł danych w czasie rzeczywistym w celu zapewnienia użytkownikowi końcowemu dostępu do jak najbardziej aktualnych danych a w związku z tym również informacji biznesowych
3.	System powinien być dostosowany dla użytkowników biznesowych, którzy nie posiadają wiedzy technicznej, oraz zapewniać im szybką, intuicyjną obsługę oraz dostęp do odpowiednich danych i analiz
4.	System musi zapewnić odpowiedni poziom bezpieczeństwa na każdym etapie procesowania danych zwłaszcza w przypadku użycia przez użytkownika końcowego (biznes)
5.	System powinien być skalowalny, aby umożliwić dodawanie nowych funkcjonalności w przyszłości oraz łatwe dodawanie dużych wolumenów danych
6.	System musi być dostępny na wszystkich platformach nie zależnie od mocy obliczeniowej czy systemu operacyjnego
# Technologie
1.	Microsoft SQL Server Management Studio - narzędzie do zarządzania bazą danych oraz wykonywania zapytań SQL. 
    Umożliwia ono przechowywanie danych w hurtowni danych.
3.	SQL Server Integration Services jest to narzędzie ETL służące do pobierania, przetwarzania oraz ładowania danych.
4.	Power BI – narzędzie typu Business Intelligence służące między innymi do wizualizacji oraz analizy danych
# Autor
Tomasz Sadlik

# Informacje Dodatkowe
Projekt stworzony na potrzeby przedłożenia w Wyższej Szkole Ekonomii i Informatyki w Krakowie
