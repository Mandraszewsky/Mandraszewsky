# 👋 Cześć, jestem Krzysztof!
👩🏻‍💻 Studiowałem na Uniwersytecie w Siedlcach na kierunku Informatyka - osiągając tytuł magister inżynier (mgr-inz-inf) w 2024 roku. <br/>
👩🏻‍🎓 Komercyjną pracę zawodową rozpocząłem już w 2021 roku. <br/>

# 💻 Tech Stack:
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![RabbitMQ](https://img.shields.io/badge/rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white) ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Grafana](https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) ![Styled Components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white) ![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Cisco](https://img.shields.io/badge/cisco-%23049fd9.svg?style=for-the-badge&logo=cisco&logoColor=black) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

# 📊 Projekty Programistyczne:

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
