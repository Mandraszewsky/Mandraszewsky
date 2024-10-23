# 👋 Cześć, jestem Krzysztof!
👩🏻‍💻 Studiowałem na Uniwersytecie w Siedlcach na kierunku Informatyka - osiągając tytuł magister inżynier (mgr-inz-inf) w 2024 roku. <br/>
👩🏻‍💻 Tytuł samego inżyniera (inz-inf) uzyskałem na początku 2021 roku. <br/> <br/>
👩🏻‍🎓 Komercyjną pracę zawodową rozpocząłem w połowie 2021 roku. Jestem programistą .NET i C#, ale mam za sobą również klikumiesięczny projekt jako frontendowiec w React :D <br/>
👩🏻‍🎓 Z ciekawostek o mnie, przez chwilę programowałem komercyjnie (jako fullstack) w PHP i JS.

# 💻 Tech Stack:
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![RabbitMQ](https://img.shields.io/badge/rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) ![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white) ![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Cisco](https://img.shields.io/badge/cisco-%23049fd9.svg?style=for-the-badge&logo=cisco&logoColor=black) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

# 📊 Ciekawsze projekty programistyczne:

## <span style="color: darkblue;">**Computerised Maintenance Management System**</span>  
System zapewniający nadzór nad stanem operacyjnym maszyn i nieplanowanych prac, rozliczaniem kosztów, harmonogramem, a także generujący bieżące oraz predykcyjne raportowanie. <br/> <br/>
Technologie i biblioteki: ASP.NET Core, SQL Server, SignalR, Quartz, MediatR, Identity, FluentValidation, AutoMapper, NLog

### Realizowane zadania (projekt + implementacja):
- Podstawowa struktura relacyjnego modelu bazy danych systemu, a także jej kolejne rozszerzenia.
  
- Mechanizm zgłoszeniowy, polegający na obsłudze całego cyklu życia zgłaszanego zadania (np. inspekcje kontrole, naprawy, wymiany) między maszynami, a użytkownikami systemu.
  
- Mechanizm tworzenia i zarządzania listami kontrolnymi, opcjonalnie przypisywanymi do zgłoszeń (np. indywidualna lista kontrolna dla zgłoszeń inspekcyjnych).

- Mechanizm generowania harmonogramu prac kalendarzowych i przebiegowych, typowane według indywidualnych kryteriów systemowych, rodzajów prac i podziałem czasu na jednorazowe, dzienne, tygodniowe czy nawet roczne plany (uwzględniając m.in. priorytet planu, dni wolne czy zmiany czasowe). 

- Mechanizm powiadomień w czasie rzeczywistym.

- Algorytmy raportowe dot. maszyn operacyjnych: MTBF, MTTR, MTTF, MTTA – mean time between failures, mean time to repair, mean time to failure, mean time to acknowledge.

- Integracja systemu z modułem Identity (zapewniający autoryzację i uwierzytelnienie użytkowników).

---

## <span style="color: darkblue;">**Production Performance Management**</span>  
System odpowiadający za monitorowanie i gromadzenie wiedzy (w czasie rzeczywistym) dot. wydajności produkcyjnej, w celu określania ogólnej efektywności wyposażenia: stanu zamówienia, warunków maszyn, parametrów produktów rejestrowanych przez sterownik PLC (Programmable Logic Controller). System przekazuje natychmiastowe informacje i reakcje z linii produkcyjnej, łącząc parametry konkretnych procesów z konfiguracją maszyn. <br/> <br/>
Technologie i biblioteki: ASP.NET Core, SQL Server, Quartz, Identity, AutoMapper, NLog, OpcUA

### Realizowane zadania (implementacja):
- Implementacja oraz modyfikacja istniejących w projekcie algorytmów OEE (Overall Equipment Effectiveness), które odpowiadały za określenie stopni wykorzystania maszyn w realizowanych przez nich procesach wytwarzania.
  
- Integracja systemu z modułem Identity (zapewniający autoryzację i uwierzytelnienie użytkowników).

---

## <span style="color: darkblue;">**Moduł Identity**</span>  
Moduł zapewniający autoryzację i uwierzytelnienie użytkowników, działający w obrębie pozostałych systemów / modułów dot. środowiska produkcyjnego lub majątkowego (np. CMMS, PPM, EAM). <br/> <br/>
Technologie i biblioteki: ASP.NET Core, SQL Server, SignalR, MediatR, Identity, IdentityModel, Authentication, MailKit, NLog

### Realizowane zadania (projekt + implementacja):
- Projekt i implementacja podstawowej struktury całego modułu, łącznie z mechanizmem roszczeń przypisywanych do konkretnych ról użytkowników, obsługą cyklu życia tokenu JWT (wraz z jego odświeżeniem), powiadomieniami czasu rzeczywistego i integracją samego modułu z pozostałymi systemami.

---

## <span style="color: darkblue;">**Enterprise Asset Management**</span>  
Całkowita obsługa majątku należącego do przedsiębiorstwa przy odwzorowaniu pełnej struktury lokalizacyjnej wraz z pełnym rozliczeniem kosztowym wszystkich składników majątkowych, a także repozytorium dokumentów umożliwiającym przechowywanie dokumentacji. Posiada rozszerzoną funkcjonalność dla ewidencji oraz inwentaryzacji majątku. <br/> <br/>
Technologie i biblioteki: Figma

### Realizowane zadania (projekt):
- Analiza i modelowanie artefaktów fazy projektowej systemu EAM (obiektowe i strukturalne) takie jak: diagramy przypadków użycia, diagramy aktywności, diagramy przepływu danych, diagramy struktury danych i klas, a także modele specyfikacji interfejsów. 

---

## <span style="color: darkblue;">**Aplikacja do kupowania i sprzedaży NFT**</span>  
Technologie i biblioteki: React.js, React-Redux, MUI, HTML, CSS

### Realizowane zadania (implementacja):
- Interfejsy graficzne aplikacji z wykorzystaniem biblioteki komponentów Material UI (MUI), takie jak: panele administratora, panele użytkowników, generyczne tabele czy listy wykorzystywane później w innych interfejsach i funkcjonalnościach (np. tabela z historią sprzedaży).

---

## <span style="color: darkblue;">System integrujący dane między zewnętrznym systemem, a systemem SAP (System Analysis Program Development) </span>  
System zapewniający centralizację dostępu do jednolitych danych. <br/> <br/>
Technologie i biblioteki: ASP.NET Core, SQL Server, Quartz, MediatR, FluentValidation, AutoMapper, NLog

### Realizowane zadania (implementacja):
- Mechanizm importowania i eksportowania danych z systemu do arkuszów kalkulacyjnych lub z arkuszów do systemu, według przyjętych kryteriów i szablonów.

- Algorytmy integrujące dane między systemami i obiektami w aplikacji, z wykorzystaniem złożonych zapytań SQL.

---

# 📊 Projekt Magisterski:
## <span style="color: darkblue;"> Automatyzacja zarządzania infrastrukturą aplikacji Cloud Native w czasie rzeczywistym z wykorzystaniem architektury Service </span>  
Projekt i implementacja aplikacji chmurowej na platformie ASP.NET Core tak, aby zautomatyzować zarządzanie infrastrukturą w czasie jej rzeczywistego działania. Wykorzystana została architektura siatek usług (service mesh), która w podstawowych założeniach opiera się na połączonych ze sobą serwerach pośredniczących. Badanie tak wdrożonego rozwiązania było realizowane poprzez wielokrotne obciążania sieciowe dla różnych algorytmów równoważenia obciążenia, wykazując tym samym wpływ konfiguracyjny na opóźnienie i złożoność operacyjną infrastruktury w czasie rzeczywistym. <br/> <br/>
Technologie i biblioteki: ASP.NET Core, Docker, SQL Server, Redis PostgreSQL, MediatR, RabbitMQ , YARP Reverse Proxy, Grafana Cloud 

<br/>
<div align="center">
  <img src="https://github.com/Mandraszewsky/Images/blob/main/CNAppsWithSSMMP.png" alt="Alt text" />
  <p>Architektura CNApps w oparciu o założenia SSMMP (źródło: opracowanie własne)[^1]</p>
</div>
<br/>

Utworzony został obszar projektowy składający się z szeregu mikroserwisów i usług, odzwierciedlając tym samym strukturę CNApps na platformie ASP.NET Core. Następnie dokonany został podział tego obszaru na warstwy – sterowania i danych, za które odpowiada utworzona instancja Menadżera oraz Agenta. Warstwa danych jest otwarta na potencjalne operacje skalowania, oferując możliwość powielenia swoich własnych instancji, którymi będzie można zdalnie sterować i dowolnie przemieszczać, między kolejnymi węzłami Agentów. Tym samym zleca ona kolejne zadania instancjom, a ich wynik przekazuje innym obszarom (w domyśle Menadżerowi). Węzły dotyczy proces rekonfiguracji, z zachowaniem stałych instancji Agentów. Warstwa sterowania odpowiada za bezpośrednią rekonfigurację struktury oraz bieżące monitorowanie poszczególnych usług i serwisów. Obie warstwy zapewnione mają własne usługi bazodanowe.

<br/>
<div align="center">
  <img src="https://github.com/Mandraszewsky/Images/blob/main/CQRS.png" alt="Alt text" />
  <p>Ogólny widok poleceń we wzoru CQRS (źródło: https://learn.microsoft.com/pl-pl/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/microservice-application-layer-implementation-web-api dostęp – lipiec 2024)[^2]</p>
</div>
<br/>

Obszar danych i sterowania wykorzystuje wzorce CQRS (Command and Query Responsibility Segregation) oraz MediatR, połączenie obu wzorców zaprezentowane. Pierwszy z nich, odpowiedzialny jest za segregację operacji odczytu i zapisu wewnątrz magazynu danych. Aktualizację ogranicza się do konkretnych zadań asynchronicznych, a samemu odczytowi uniemożliwia się dostęp do modyfikacji baz danych. Minimalizuje się w ten sposób niezgodność między danymi operacjami poleceń i zapytań, jednocześnie usprawniając wydajność poszczególnych warstw dostępowych. Modele takich operacji przeważnie izoluje się od siebie, co umożliwia użycie nawet oddzielnych typów baz danych. MediatR natomiast jest wzorcem behawioralnym, ponieważ bierze czynny udział w trakcie procesowania zadań. Wprowadza hermetyzację do komunikacji między obiektami w aplikacji, gdzie staje się pośrednikiem takich „rozmów”, czyli obiekty w takim wzorcu delegują swoje interakcje bezpośrednio do obiektu mediatora. 

<br/>
<div align="center">
  <img src="https://github.com/Mandraszewsky/Images/blob/main/SSMMP.png" alt="Alt text" />
  <p>Simple protocol to automate the executing, scaling, and reconfiguration of Cloud-Native Apps (źródło: https://github.com/sambrosz/SSMMP-a-simple-protocol-for-Service-Mesh-management dostęp - lipiec 2024)[^3]</p>
</div>
<br/>

Ideologia protokołu SSMMP, na którym została oparta infrastruktura pracy badawczej, skupia się na mikroserwisach działających w obrębie natywnego przetwarzania chmurowego (ang. Cloud Native Applications) - aktywnie zaangażowanych w konfigurację własnych sesji komunikacyjnych. Ogranicza się tym samym implementację do jedynie drobnych i bardzo ogólnych zmian bazowego kodu, aby w żaden sposób nie kolidować z logiką biznesową działających w tej architekturze serwisów czy usług. W innym przypadku narażona zostać by mogła cała natywna struktura, powodując przy tym straty proporcjonalne do wielkości zakładanych planów biznesowych. SSMMP wyróżnia 3 głównych aktorów: Menadżera, Agenta oraz wszystkie pozostałe instancje usług działających w przyjmowanej strukturze – można je określić jako instancje związane bezpośrednio z biznesem. Za przykład można tutaj podać bramę API (ang. Application Programming Interface) czy usługę BaaS (ang. Backup as a Service). Protokół również zakłada możliwość skalowania tychże instancji tak, aby jednocześnie mogły być uruchomione wielokrotne wystąpienia tej samej usługi w obrębie jednolitej struktury

<br/>
<div align="center">
  <img src="https://github.com/Mandraszewsky/Images/blob/main/Abstract%20graph%20of%20CNApp.png" alt="Alt text" />
  <p>Abstract graph of CNApp - a simple example (źródło: https://github.com/sambrosz/SSMMP-a-simple-protocol-for-Service-Mesh-management dostęp - lipiec 2024)[^4]</p>
</div>
<br/>

Abstrakcję przedstawić można na przykładzie powyższego grafu. Według tego schematu, krawędź połączenia zdefiniowana jest jako:
(A, (P, S), B)
gdzie A = api gateway, B = service, P = plug, S = socket.
Samo (P, S) determinuje opisywany protokół, dla którego P oznacza wyjście A, a S wejście B. Nazwa docelowego serwisu B nie jest jawnie zawarta w serwisie A, więc Menadżer musi zadeklarować ją jako dodatkowy parametr konfiguracyjny. W tym celu serwis A wyśle żądanie przez swojego własnego Agenta do Menadżera, który dostarczy wszystkich potrzebnych informacji do zestawienia takiego połączenia (głównie numery portów i adresy sieciowe). Autorzy również wnioskują, że każdy serwis zawarty w takim schemacie powinien być generyczny, ponieważ A może zostać użyty jako komponent innego CNApps – (A, (P, S), C), gdzie C jest różne od B. Struktura CNApp, została zdefiniowana jako postać multigrafu skierowanego (zwanego także pseudografem, w którym występują krawędzie wielokrotne):

𝒢:=(𝒱, ℰ)

w którym 𝒱 i ℰ są oznaczeniami wierzchołków (zbiorów usług) oraz krawędzi (zbiorów połączeń). Wierzchołki 𝒱 są bezstanowe – koncentrując się tym samym na operacjach, które mają bezpośredni wpływ na zasoby, a nie ich stany. Podejście to sprawia, że każde żądanie będzie traktowane niezależnie, nie powodując zbędnego procesu przechowania dodatkowych porcji danych. Wymusza się w ten sposób zawarcie wszystkich niezbędnych informacji bezpośrednio w takim komunikacie, aby serwer mógł odpowiednio przeprocesować i zareagować na dane zdarzenie. Wierzchołki dzięki temu zyskują dodatkowy atrybut w postaci skalowalności, a to z kolei oznacza możliwość ich powielenia w taki sposób, aby mogły występować i działać jednocześnie w obrębie tej samej struktury. Może jednak wystąpić sytuacja, w której niektóre z nich będą nieaktywne w danym momencie. Protokół SSMMP zabezpiecza taką sytuację za pośrednictwem dynamicznie przeprowadzanych konfiguracji takich parametrów jak adresy sieciowe czy porty.

