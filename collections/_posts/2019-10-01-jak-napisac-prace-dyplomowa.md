---
layout: post
title: "Jak napisać pracę inżynierską?"
date: 2019-10-01T05:22:42Z
authors: ["Paweł Ksieniewicz"]
categories: ["Studia"]
description: "To ani proste, ani trudne zadanie. Masz na nie dokładnie tyle czasu, co potrzeba, to tylko dziekanat Cię niepotrzebnie pogania."
thumbnail: "/assets/images/gen/projects/pracadyplomowa.jpeg"
image: "/assets/images/gen/projects/pracadyplomowa.jpeg"
---

> Poniższy wpis to tzw. niepubl, tj. nieopublikowany tekst, do którego czasami się odnoszę. Aby nie był już niepublem ~ kopiuję go tutaj, żeby (a) więcej już o nim nie myśleć i (b) może się komuś jeszcze przydał. Przydarzyło mi się napisać to w roku 2018 po serii trzech identycznych spotkań z osobami studenckimi. A każdy informatyk wie, że zamiast robić coś ręcznie po raz trzeci ~ lepiej jest napisać odpowiedni skrypt, który w przyszłości zrobi to za nas.

*Niniejszy dokument* stanowi zbiór uwag, które mogą okazać się Państwu przydatne podczas realizacji pracy inżynierskiej. W jego pierwszej części znajduje się proponowana lista rozdziałów pracy i *harmonogram jej realizacji*^1 z wyszczególnieniem punktów kontrolnych, w których wypada informować promotora o postępach. Zaraz za nim znajduje się kilka krótkich wzmianek o narzędziach, w których pracę będzie można zrealizować, a później jej przykładowy podział z zaznaczeniem istotnych wiadomości, które powinny znaleźć miejsce w każdym z rozdziałów. Tekst zamyka kilka końcowych sugestii, dzięki którym łatwiej będzie zadbać o estetykę pracy i spokojniej poradzić sobie z procedurami na uczelni. Zapraszam do krytycznego^2 wykorzystania.

1^ *Harmonogramu należy bezwzględnie przestrzegać, jeśli chcą Państwo przeżyć grudzień tego roku bez wrzodów żołądka będących efektami narastającego stresu. Proszę się nie martwić -- wszystko będzie dobrze.*

2^ Krytyczne wykorzystanie polega na tym, że przyjmuje się uwagi, ale robi się i tak po swojemu.

---

Proszę mieć na względzie, że mówiąc o *pracy inżynierskiej*, nie będziemy mieć na myśli samego projektu, który realizują Państwo na ostatnim semestrze studiów. Podstawą do oceny, która znajdzie się na dyplomie ich ukończenia jest praca jako dokument, który ten projekt opisuje. Dokument ten musi być czytelny, estetyczny, przygotowany z szacunkiem do czytelnika^3 i prezentujący Państwa *osiągnięcie życia uczelnianego* w możliwie uczciwy sposób. Należy w nim więc za wszelką cenę unikać sformułowań, w których projekt wychwalany jest ponad miarę i przedstawiany jako *lek na całe zło tego świata*. Projekt, należycie opisany, będzie bronić się sam, a jego ewentualne małe niedociągnięcia będzie można przedstawić w tekście pracy jako wyniki decyzji projektowych.

3^ *Protip: Brakiem szacunku do czytelnika jest używanie w tekście określeń takich jak "proste" czy "oczywiste". Podobnie szerokich wyjaśnień terminów, które faktycznie są proste i oczywiste. Już lepiej zdecydować się na taktowne niedomówienie.*

# Spis treści

Czytelnym podziałem pracy inżynierskiej jest wyodrębnienie pięciu rozdziałów^4 . W każdym kolejnym wykorzystujemy i rozwijamy pojęcia wprowadzane wcześniej, aby od zupełnych ogólników i początkowych zamiarów powoli podnieść napięcie do niepokojącego maksimum technicznego opisu i zamknąć wszystko nagle wytchnieniem smacznego niedosytu puenty podsumowania.

1. Wstęp
2. Cel i zakres pracy
3. Projekt systemu
4. Implementacja systemu
5. Podsumowanie

4^ *Podział pracy na pięć rozdziałów jest zalecany, ale nie jest wymagany i mogą Państwo swobodnie zastosować inne podejście. Jedynym wymogiem tutaj będzie ograniczenie spisu treści tak, aby mieścił się na jednej stronie.*

Jeśli chodzi o dalszy etap organizacji pracy, czyli podrozdziały, pod-podrozdziały i sekcje, to bardzo złe wrażenie pozostawiają prace poszatkowane, w których każdy podrozdział zawiera jedynie po jednym akapicie tekstu. Wypada więc unikać rozdrobnienia strukturalnego. 

Z drugiej strony podobnie źle wyglądają wielkie bloki tekstu i zdania, które ciągną się na dziesięć i więcej linii. Wypada też dzielić duże akapity na mniejsze, o różnej długości tak, aby nie zanudzić czytelnika monotonnością.

# Harmonogram pracy

*Okres pracy nad tekstem dokumentu* rozpinamy na przedział od spotkania organizacyjnego do dnia złożenia pracy w systemie antyplagiatowym pierwszego dnia sesji, dzieląc go na cztery fazy.

**Faza przeglądowa** to okres, w którym skupiają się Państwo głównie na przeglądzie literatury dotyczącej przedmiotu pracy i precyzowaniem celu zawartego w jej temacie. Wraz z jej końcem powinien zostać zamknięty spis wykorzystanej literatury^5, całość rozdziału zawierającego wstęp do pracy i większa część rozdziału poświęconemu celowi i zakresowi projektu. Najwięcej pożytku piszącemu przynosi wtedy drukowanie na potęgę tekstów źródłowych, zaznaczanie w nich interesujących fragmentów i maniakalne notowanie na marginesach^6.

5^ *O spisie literatury wspomnimy jeszcze później.*

6^ *Tak, wiem, że to nieprzesadnie ekologiczne, ale nauka czasem wymaga poświęceń.*

**Faza projektowa** to czas, w którym odkładają Państwo na bok literaturę przedmiotu i skupiają się już na własnym projekcie. Należy przeglądać go krok po kroku, rozrysowywać schematy jego konstrukcji, zapisywać pseudokody wykorzystywanych algorytmów, notować stosowane reprezentacje danych i odnajdywać zastosowane w nim wzorce projektowe. To najdłuższe trzy tygodnie pracy, w których dokumentują Państwo to, co w projekcie się znalazło, przydzielając każdą znalezioną informację do jednej z trzech grup:

- **Celu** — dla najbardziej ogólnych informacji,
- **Projektu** — dla ogólnych relacji pomiędzy informacjami,
- **Implementacji** — dla wszystkich detali.

Informacje z kolejnych grup zamieszczają Państwo, z możliwie precyzyjnym opisem, w odpowiednich rozdziałach pracy. 

**Faza redakcyjna** to moment w którym zaczynają Państwo pracować już jedynie z własnym tekstem. W pierwszej kolejności, na końcu wstępu dodany zostaje krótki opis wszystkich rozdziałów. Dalej weryfikacji podlegają wszystkie wykorzystane odniesienia do literatury, a każdy z rozdziałów zostaje wyposażony w krótki wstęp opisujący to co faktycznie się w nim znalazło. Wreszcie wszyscy w Państwa najbliższym kręgu rodziny i znajomych czytają linia po linii dopieszczany dokument w poszukiwaniu najmniejszych błędów językowych i literówek. Na koniec upewniają się Państwo, że pojęcia wprowadzone w pierwszych dwóch rozdziałach są stosowane w całej pracy w tym samym brzmieniu -- a po tym wszystkim -- dopisują podsumowanie pracy dyplomowej.

Zgodnie z planem, wybranego przez dziekanat grudniowego dnia najcięższego w życiu roku mają Państwo w rękach wydrukowany egzemplarz pracy inżynierskiej i z poczuciem dobrze spełnionej misji przynoszą go promotorowi do oceny. Nie jest to jednak jego pierwszy kontakt z tekstem, bo podczas realizacji mamy jeszcze kilka *kroków milowych*, w których *wypada* przesłać promotorowi aktualny tekst pracy w formie dokumentu `pdf`.

| Data    | Postępy |
| -------- | ------- |
| *początek listopada*  | Wstęp i większa część celu i zakresu pracy.    |
| *połowa listopada* | Pełen cel i zakres pracy oraz zalążek opisu projektu.     |
| *koniec listopada*    | Postęp w opisie projektu i implementacji.    |
| *początek grudnia*   | Gotowa praca.    |

Na podane kroki macie Państwo pełne prawo kompletnie się wypiąć, jeżeli chwilowo będą ponad siły. Krytyczne jest to, żeby zachować zdrowy komfort pracy, a nie dostosowywać się do kogoś *u góry*.

Po złożeniu pracy u promotora następuje ostatnia, **faza poprawkowa**. Otrzymają wtedy Państwo końcowe poprawki do dokumentu, szlifują go ostatecznie i ładują do systemu APD. Najważniejszą sprawą w tym momencie, sprawą która może zablokować możliwość podejścia do egzaminu i którą trzeba później rozwiązywać przez dziekanat jest [losowa zmiana, którą akurat w tym roku ktoś wprowadził w przepisach, aby być *ważnym człowiekiem* i promotor nie ma o niej pojęcia](https://wit.pwr.edu.pl).

Wszystkie kroki milowe i ważne daty wraz z oznaczeniem zakresów pracy, które powinny być realizowane w poszczególnych fazach zostały opisane również na poniższym diagramie.

![](/assets/images/gen/projects/gantt.png)

# W czym to napisać?

Preferowanym narzędziem do redakcji tekstu pracy jest system składu LaTeX^7. Jeśli zdecydują się Państwo na \LaTeX, może być to tak jego lokalna wersja zainstalowana w systemie operacyjnym, jak usługa pozwalająca na kompilację jego źródeł w przeglądarce internetowej^8.

7^ *Najczęściej do kompilacji dokumentów systemu LaTeX wykorzystujemy [pakiet TeXLive](https://www.tug.org/texlive/), jakkolwiek mogą Państwo wykorzystać dowolny edytor tekstu, wliczając w to nawet Worda.*

8^ W tej chwili najpowszechniejszy ~ choć nadal żenujący jak każde rozwiązanie webowe ~ jest [Overleaf](https://www.overleaf.com).

Publicznie dostępna jest klasa systemu LaTeX dedykowana pracom realizowanym przez studentów *Wydziału Elektroniki*^9. Jej bezwzględnym atutem jest to, że pozbawia zmartwień względem poprawności strony tytułowej^10, pozwala na wygenerowanie kopii archiwalnej pracy przy użyciu jednej komendy i sama generuje zgodny z wymaganiami spis literatury na podstawie pliku BibTeX.

9^ Dosyć powszechnie stosowana do realizacji prac dyplomowych na naszym wydziale jest [klasa `mgr` autorstwa Pana doktora Adama Ratajczaka](http://rab.ict.pwr.wroc.pl/~ar/LaTeX/mgr.php).

10^ W wypadku Worda proszę skorzystać ze strony Wydziału i pod żadnym pozorem nie decydować się na żadną radosną twórczość w postaci dodawania tam na przykład opiekuna specjalności.

# Rozdział pierwszy --- Wstęp

Wstęp do pracy powinien być ogólnym wprowadzeniem do jej tematyki, opisującym wszystkie podstawowe pojęcia i wykazującym kompetencje autora do realizacji projektu. Pojęcia nie muszą być opisane szczegółowo, ale należy przestawić wzajemne powiązania pomiędzy nimi i uzasadnić sens powstawania projektu.

*Wstęp możemy rozpocząć od krótkiego opisu tematu.* Znów, bez wchodzenia w detale, budujemy zadanie jak w poniższym przykładzie:

> Tematem niniejszej pracy inżynierskiej jest system wyszukiwania lekarzy specjalistów i rezerwacji wizyt lekarskich. Jest to aplikacja webowa, pozwalająca na wygodne dla pacjenta wyszukiwanie lekarza według miejscowości oraz specjalizacji.

*Po krótkim opisie, wprowadzamy czytelnika bardziej do tematu.* Możemy ukazać go tutaj jak realny problem społeczny, wyzwanie implementacyjne czy ogólny trend w którym aktualnie dąży technika. W skrócie – sensem jest przekazanie istotności podejmowanego problemu. Dobrym przykładem takiego opisu są czarnobiałe wstępy do reklam w *Telezakupach Mango*.

> Rejestracja wizyty lekarskiej bywa dla wielu ludzi wymagającym i stresującym zadaniem. Często pacjent musi osobiście udać się do przychodni lub próbować dodzwonić się do niej czy bezpośrednio do wybranego lekarza. Powszechnie zdarzają się sytuacje, kiedy termin lub miejsce wizyty okazują się dla pacjenta nieodpowiednie. Dodatkowy stres wynika też z przypadków niedostatecznych umiejętności miękkich lekarza.
    	
*Alternatywą jest rys historyczny.* Jeśli zajmujemy się algorytmami cyfrowego przetwarzania obrazów, możemy wskazać na jego początki w amerykańskim programie kosmicznym i zrealizowanych przez sondę [Ranger 7](https://pl.wikipedia.org/wiki/Ranger_7) pierwszych cyfrowych zdjęciach Księżyca, aby pokazać rozwój techniki od wprowadzonego na tę okazję pojęcia piksela^11, przez rozwijające się już od lat sześćdziesiątych metody konwolucji, aż po wysokopoziomowe przetwarzanie pozwalające na odczytywanie ze zdjęć ludzkich emocji i zamiarów.

11^ [https://www.picturecorrect.com/tips/a-brief-history-of-the-pixel/](https://www.picturecorrect.com/tips/a-brief-history-of-the-pixel/)

![O jaka ważna ilustracja dla dziedziny, którą zajmuję się w pracy inżynierskiej.](/assets/images/gen/projects/ranger7.jpg)
O jaka ważna ilustracja dla dziedziny, którą zajmuję się w pracy inżynierskiej.

Jeżeli tematem pracy jest szeroko rozumiane uczenie maszyn, możemy rozpocząć od [Dartmouth workshop](https://en.wikipedia.org/wiki/Dartmouth_workshop), które dało początek badaniom nad sztuczną inteligencją, a później krok po kroku wprowadzić rozróżnienie między uczeniem nadzorowanym i nienadzorowanym, wymienić różne podejścia i algorytmy przetwarzania, wreszcie dochodząc do tych, którymi sami będziemy się w pracy zajmować.
    	
Nic, czym się zajmujemy przecież nie bierze się znikąd, a pokazanie tła rozwoju jakiejś dziedziny techniki da nam lepsze perspektywy do wyciągania późniejszych wniosków. Obserwowania trendów, które są skazane na porażkę i tych, które faktycznie mogą okazać się wartościowe i istotnym byłoby ich poruszenie. Uzasadnienie tego, że wybór tematu był słuszny przestanie być jedynie wynikiem własnej opinii, kiedy będziemy mogli oprzeć się na autorytetach, które już wcześniej dotarły do wartościowych konkluzji. 
      
*Dalej wprowadzamy odrobinę mniej suchą teorię.* Kiedy już osadziliśmy się w jakimś temacie, w jego obrębie pokazujemy dokładny punkt, w którym znajdzie się nasza praca. Czy będzie to aplikacja rozwiązująca zadany problem czy system realizujący określone zadania, pokazujemy czytelnikowi, że nie jest to zadanie trywialne i nie każdy z marszu mógłby się z nim zmierzyć.

> Współczynniki cepstrum melowego [6] są najpowszechniej wykorzystywanym parametrem w systemach rozpoznawania mowy oraz mówców [24]. Przy wytwarzaniu mowy, kształt kanału głosowego znajduje swoje odwzorowanie w obwiedni widma mocy danej głoski.
    
*Analiza rynku* jest koniecznym elementem pracy, jeśli efektem projektu będzie coś, co można spokojnie nazwać produktem. Dowolna aplikacja czy system, z którego docelowo ma korzystać grupa niewykwalifikowanych użytkowników. W takim wypadku należy dokonać nie przeglądu algorytmów rozwiązujących postawiony przed pracą problem a produktów, które już na rynku są dostępne i realizują podobne zadania. 

Warto jest ocenić ich pozycję (np. procentowy udział w rynku), wady i zalety. Być może interesująca byłaby pogłębiona analiza ekonomiczna tego, czy na rynku istnieje jeszcze jakaś nisza, czy któryś z graczy dysponuje [rentą pionierską](https://en.wikipedia.org/wiki/Economic_rent) i jakie są szanse powodzenia nowego produktu w wypadku aktualnego nasycenia rynku, ale co do zasady nie jesteśmy ani ekonomistami ani przedsiębiorcami, więc nikt od nas tego nie będzie wymagać.
 
> Podobne rozwiązanie istnieje również dla lekarzy i pacjentów w Stanach Zjednoczonych --- Zocdoc. Portal ten również pozwala na zdalną rezerwację wizyt lekarskich, choć wyszukiwanie lekarzy różni się od pozostałych podejść tym, iż możliwe jest wyszukiwanie lekarza nie tylko po miejscowości i specjalizacji, ale i po ubezpieczeniu, nazwisku lekarza, opiniach, szpitalach czy języku.

Odpowiedni przegląd rynku nie tylko pokaże, że orientujemy się w nim, ale pozwoli również na [twórczą inspirację](https://pl.wikipedia.org/wiki/Inżynieria_odwrotna) konkurentami w celu ich prześcignięcia w toku naturalnego procesu dyseminacji tak doskonale opisywanego przez [prawo Kopernika-Greshama](https://pl.wikipedia.org/wiki/Prawo_Kopernika-Greshama).

*Domknięciem wstępu jest akapit poświęcony strukturze pracy.* Dopisujemy go w ostatniej fazie redakcji dokumentu, kiedy wszystkie rozdziały mają już swoją zasadniczą treść, którą pokrótce staramy się przybliżyć.

> W kolejnym rozdziale opisano cel i zakres pracy. Znaleźć w nim można m.in. wymagania stawiane projektowi oraz istniejące rozwiązania omawianego problemu. Kolejno, w Rozdziale 3, scharakteryzowane zostało działanie systemu, prezentując zastosowany przepływ danych, podział systemu (tak zewnętrzny, na konkretne moduły, jak i wewnętrzny -- sięgający do struktury kodu), algorytmy uczenia maszyn, wirtualizację oraz wszelkie niezbędne abstrakcje i standardy wymagane do poprawnej interpretacji wyników przetwarzania (...).

# Rozdział drugi — Cel i zakres pracy
 
**Akapit wstępu** Na koniec redakcji **każdego** rozdziału poza podsumowaniem należy dopisać jego początkowy akapit określający, co faktycznie się w nim znalazło (znajdzie)^12. Wprowadza to czytelnika łagodnie w treść, pozwalając mu przygotować się na to, z czym będzie musiał się zmierzyć. Ewentualnie, w wypadku lekkiego lenistwa, pozwoli mu pominąć dany rozdział, uznając, że skoro wstęp do niego jest tak czytelny, to spokojnie może przejść do podsumowania i zaufać, że wszystko poszło perfekcyjnie.

12^ Z jednej strony wygląda to odrobinę na powtarzanie tej samej treści w wielu miejscach pracy. Nic bardziej mylnego. Słuszniej nazywać to utrwalaniem wiedzy.

**Precyzyjnie definiujemy cel.** Zarysowany zgrubnie we wstępie cel projektu, z wykorzystaniem pojęć we wstępie wprowadzonych, rozwijamy w precyzyjny opis naszych zamiarów. Nie wchodzimy jeszcze a żadne aspekty implementacyjne czy projektowe, ale opisujemy projekt jak *czarną skrzynkę*. Informujemy czytelnika o tym, co będzie można do niego wprowadzić, jak będzie się z niego korzystać i co będzie można z niego uzyskać.

> Przedmiotem pracy jest projekt oraz implementacja systemu, w skład którego wchodzić będą moduły `arg` oraz `arm`, przetwarzające plik dźwiękowy z wieloma mówcami na stenogram (transkrypcję z podziałem na mówców). System będzie aplikacją internetową, wykorzystującą do komunikacji protokół HTTP. Aplikacja przyjmować będzie gotowe pliki dźwiękowe w formacie `wav`. Po przetworzeniu danego zestawu plików (tj. próbek osób mówiących w nagraniu oraz nagrania właściwego), użytkownikowi zostanie udostępniony stenogram przesłanej treści.

**Definiujemy wymagania projektowe.** Mają Państwo na studiach całą górę kursów z zarządzania projektami, zarządzania jakością^13, czy projektów zespołowych. To tutaj będzie szansa wykazać się ogromem zdobytej podczas nich wiedzy. Szablony `volere`, diagramy `uml`, przypadki użycia i cała gama innych różnych przydatnych narzędzi tylko czekają na to, żeby je wykorzystać.
    	
13^ Akurat zarządzanie jakością i *Zasady Deminga* to zupełnie interesująca dziedzina, która najpierw pozwoliła Stanom Zjednoczonym na niesamowity rozwój w latach czterdziestych, a później Japonii na gigantyczny skok cywilizacyjny. W razie, gdyby ktoś był zainteresowany tematem i nagle nabrał wolnego czasu, może przeczytać sobie dostępną za darmo książkę mistrza cukierniczego, a przy okazji pierwszego profesora informatyki w historii naszego kraju -- [profesora Andrzeja Blikle](https://www.moznainaczej.com.pl/Download/DoktrynaJakosci/DoktrynaJakości_wydanie_II.pdf).

**Wybór narzędzi realizacji.** Tego punktu nie trzeba przesadnie wyjaśniać. Wymieniają tutaj Państwo listę wszystkich narzędzi (tak środowisk, jak bibliotek), podając uzasadnienie ich wykorzystania w projekcie. Proszę postarać się jednak nie używać jednak argumentu *>>bo tylko to znam<<* albo *>>bo lubię<<*^14. Określeniem–kluczem jest tutaj stwierdzenie, że dane narzędzie *>>dysponuje doskonałą dokumentacją<<* lub *>>wielką społecznością, która je rozwija<<*.

> Z powodu ograniczeń czasowych oraz niskiej dostępności polskich korpusów mowy, wraz z transkrypcjami potrzebnymi do stworzenia własnego modelu języka na potrzeby pracy, została podjęta decyzja o użyciu gotowego modelu języka. Taki model, przeznaczony do zestawu narzędzi Julius, udostępnia twórca grupy programów Skrybot. Model, według jego twórcy, jest profesjonalnej jakości oraz zapewnia współczynnik `wer` na poziomie 13% [25].

14^ Nawet jeżeli to prawda.

![Uzbrojony terenowy Segway policyjny w akcji.](/assets/images/gen/projects/segway.jpeg)

Uzbrojony terenowy Segway policyjny w akcji.

**Segway.** Na końcu **każdego** rozdziału poza wstępem i podsumowaniem należy dopisać akapit, w którym płynnie przechodzimy do kontekstu kolejnej części pracy. Należy postarać się zrobić to w miarę płynnie, na podstawie logicznego ciągu przyczynowo-skutkowego albo chociaż jakiegoś skojarzenia.

> A skoro już o projekcjach astralnych mowa, to może przejdźmy do rozdziału poświęconemu projektowi naszego systemu komunikacyjnego.

# Rozdział trzeci — Projekt systemu 

Tak jak w rozdziale drugim opisujemy projekt jak czarną skrzynkę, w rozdziale trzecim zdejmujemy z niej pokrywkę i pokazujemy co faktycznie znajduje się w środku i w jaką strukturę zostało połączone. Nie opisujemy tego jak dokładnie zbudowany został każdy jej najmniejszy element, a jaką architekturę razem tworzą poszczególne moduły.

Można wspomnieć tu o takich elementach jak:


- Schemat przepływu informacji pokazujący abstrakcyjnie role, jakie będzie spełniać system.
![](/assets/images/gen/projects/pd1.png)
- Techniczny opis każdego z modułów.
- Diagramy, tabele, opis interfejsów programistycznych (API).
- Projekt interfejsu, na przykład w formie tzw. [Wireframes](https://wireframe.cc).
- Model danych, na przykład w formie diagramu ERD^15.
-  Opis stosowanej reprezentacji, czy to jako przykładowe pliki `json` wykorzystywane w komunikacji, czy rodzaj kodowania, którym będą się Państwo posługiwać.
![](/assets/images/gen/projects/pd2.png)
- Architektura systemu, czyli opis poszczególnych jego modułów i wzajemnych zależności.
![](/assets/images/gen/projects/pd3.png)
- Zdefiniowanie stosowanych wzorców projektowych.
- Cała reszta *>>gruzu<<*^16, który tylko jest istotny dla projektu

15^ *Entity-Relationship Diagram*

16^*Ważnych dla autora informacji, bez których według niego opis nie będzie kompletny.

Wszystkie elementy, które znajdują się w tym rozdziale muszą wynikać w jakiś sposób ze zdefiniowanego we wcześniejszej części pracy celu. Ma to być w zasadzie wejście w detal w ramach schematu. Oś pracy inżynierskiej i jej najważniejszy i najbardziej treściwy fragment.

![](/assets/images/gen/projects/IMG_0417.jpg)

# Rozdział czwarty — Implementacja systemu

W rozdziale czwartym jeszcze bardziej zagłębiamy się w detale, skupiając się już na budowie wszystkich poszczególnych modułów systemu. Bardzo mile widziane będzie wskazanie w nim publicznego repozytorium, o które najłatwiej w [Githubie](http://github.com), w ramach którego udostępnimy kod projektu^17. Mogą się tu znaleźć takie elementy jak:

- Wstawki kodu. Broń boże nie cały kod projektu, a jedynie *interesujące* detale implementacyjne, z których są Państwo szczególnie dumni.
![](/assets/images/gen/projects/pd4.png)
- Badanie efektywności systemu, jeśli na przykład realizuje jakieś zadania uczenia maszyn.
- Decyzje projektowe wraz z uzasadnieniami.
- Zrzuty ekranu z interfejsu użytkownika.
- Przykłady wykorzystania aplikacji.
     
17^ *W razie, gdyby ktoś bardzo nie umiał w \textsc{git}-a, tutaj jest [poradnik dla opornych](http://rogerdudler.github.io/git-guide/index.pl.html).

Co do zasady, rozdział ten jest już domknięciem projektu i dowodem na to, że faktycznie został zrealizowany. Mogą się Państwo w nim pożalić na wszelkie problemy implementacyjne, pochwalić wszystkimi [małymi zwycięstwami](https://www.youtube.com/watch?v=87Q5PEjmrCU) i przede wszystkim pokazać, że opisany wcześniej projekt był przemyślany, sensowny i możliwy do realizacji.
    

![](/assets/images/gen/projects/pd1.jpeg)

# Podsumowanie  

Tu nareszcie można odetchnąć. Aby lekko napisać podsumowanie należy na spokojnie przejrzeć cały tekst i z absolutną powagą odpowiedzieć na poniższe pytania.
    
- Co było planowane?
- Co się udało?
- Co się nie udało?
- Dlaczego się nie udało?
- Dlaczego to dobrze, że się nie udało?
- Jakie mam z tego wszystkiego wnioski inne niż to, że *fajnie, że to już koniec*?
- Co może się udać z tym zrobić w przyszłości^18?

18^ Jedynie hipotetycznie ~ spokojnie, swoje już udało Ci się zrobić.

# Spis literatury

Dawniej było tak, że wydziałowa biblioteka przeprowadzała dla dyplomantów szkolenie z opracowywania spisów literatury i należytego cytowania twórczości innych autorów, więc jeśli nic się nie zmieniło, doskonale już Państwo wiedzą, jakie są najważniejsze wytyczne ich opracowywania. Jeśli praca powstawać będzie w systemie LaTeX, wszystkim służę pomocą podczas konsultacji, na tę chwilę wskazując w miarę dobry opis [z Wikipedii](https://pl.wikipedia.org/wiki/BibTeX). Jeśli w Wordzie, chętnie pomógłbym osobiście, ale nie używałem go od wersji 97, więc lepiej będzie mi polecić (zachęcając do tego również tych z Państwa, którzy używają LaTeX-a) poświęcone temu zagadnieniu wpisy z bloga [Warsztat Badacza](http://ekulczycki.pl/warsztat_badacza/menedzer_bibliografii/).

Bardzo przydatnym podczas przeglądu literatury będzie dla Państwa dowolne narzędzie do zarządzania nim. Z własnego doświadczenia, spośród darmowych rozwiązań, mogę polecić [Mendeley](https://www.mendeley.com) i [Zotero](https://www.zotero.org). Oba mam i nie używam.


![](/assets/images/gen/projects/pd2.jpeg)

# Na co jeszcze zwracać uwagę?

- Nikomu nigdy na nic nie przydał się spis ilustracji czy tabel. To tylko zapychacze stron.
- Jeśli mamy dużą, porządnie napisaną dokumentację albo obszerne wyniki badań, ich pełną formę można dodać do pracy jako tzw. *Appendix*. Nie zaburzy głównego tekstu pracy, a solidnie rozszerzy liczbę stron.
- Ilustracje, które przygotowujemy powinny być możliwie proste i schematyczne. Nie warto zakopywać się w gradientach i wodotryskach, bo tylko zaburzą sens przekazu. 
- Za nic w świecie **nigdy, przenigdy** proszę nie dodawać do pracy zrzutów ekranu z kodem, a wprost jego wstawki^19.
- Niby to oczywiste, ale proszę korzystać ze sprawdzania pisowni. Jeśli w tekście pracy pojawi się słowo *powsrać* w miejsce *powstać*, naprawdę obniża to walory estetyczne dokumentu i niweluje chęć jego lektury^20.

19^ *W wypadku systemu \LaTeX wstawki kodowe najłatwiej umieścić z wykorzystaniem paczki `lstlistings`.*

20^ *Oddly specific...*

# Teczka jako sprawa wagi państwowej

Najważniejszą sprawą na świecie po zakończeniu semestru będzie dla Państwa tzw. teczka, oficjalnie nosząca miano *Akt studenta*. Proszę po złożeniu pracy uważnie przeczytać stosowną podstronę na stronie wydziału i opracować *akta studenta* zgodnie z podanym tam schematem.

# Często zadawane pytania

- **Ile stron pracy muszę napisać, żeby było dobrze?**
- Nie ma czegoś takiego jak limit stron pracy inżynierskiej. Ważne jest to, aby znalazły się w niej wszystkie niezbędne informacje oraz to, żeby nie przerażała swoją objętością. Co do zasady, najczęściej jest to 40--60 stron.}
	
- **Kiedy odbędzie się egzamin?**
- Jest to zależne od dwóch czynników. W pierwszej kolejności Dziekan Wydziału wydaje rozporządzenie z ogólnym harmonogramem. Podany jest w nim tydzień, w którym sekretarz komisji obron Państwa specjalności musi wyznaczyć termin obrony. Proszę więc być z góry przygotowanym na pierwszy dzień z tego tygodnia, a najwyżej pozytywnie się Państwo zaskoczą. Daty te nie są jeszcze na tę chwilę znane, ale postaram się dać znać, kiedy zostaną ogłoszone.
	
- **Gdzie dostarczyć akta studenta?**
- Zgodnie ze informacjami ze strony wydziału, należy dostarczyć ją bezpośrednio do sekretarza komisji, ale w rzeczywistości najczęściej należy złożyć ją w sekretariacie jednostki, która prowadzi specjalność studenta. W wypadku specjalności prowadzonych przez Katedrę Systemów i Sieci Komputerowych, jest to sala 16/17 w budynku C3. **Chyba, żeby nie.**

- **Jak długo będzie trwać egzamin?**
- Najczęściej egzamin trwa około dwudziestu minut. W harmonogramie obron, które otrzymają Państwo od sekretarza komisji podana będzie konkretna godzina, w której powinni Państwo do niego przystąpić. Jest to jednak jedynie godzina orientacyjna i należy pojawić się pod salą odpowiednio wcześniej.
	
- **Kto będzie mnie egzaminować?**
- Komisja składa się z trzech osób: przewodniczącego, członka i sekretarza. Dodatkowo podczas obrony może pojawić się promotor. **Chyba, żeby nie**. Jeśli chodzi o obrony organizowane dla specjalności mojej katedry, będę mieć tę informację odpowiednio wcześniej i obiecuję się na nich pojawić. W innych wypadkach, proszę przesłać mi wiadomość, kiedy otrzymają Państwo harmonogram obron w swoich jednostkach, abym mógł się na nich pojawić i również pogratulować sukcesu.
	
- **Ile kopii pracy wydrukować?**
- Co do zasady, wystarczy kopia archiwalna do teczki. Mile widziana jest jednak druga kopia, w twardej oprawie, do wglądu dla komisji egzaminacyjnej. Trzecia jest opcjonalną dla Państwa na pamiątkę. Czwarta może dla rodziców. Jeśli i ja dostanę po obronie wydruk pracy w twardej oprawie, będzie mi szalenie miło, ale oczywiście nie zmuszam.

# To w zasadzie tyle

Mam szczerą nadzieję, że powyższy dokument będzie dla Państwa pomocny w realizacji pracy. Ze swojej strony życzę powodzenia i minimum stresu związanego z jej pisaniem.

dr inż. Paweł Ksieniewicz