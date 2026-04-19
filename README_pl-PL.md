# YourCRT

**YourCRT: Odtwarzanie wideo tak, jak Pan Jezus przykazał w 2009 roku.**

[English](README.md) | [Русский](README_ru-RU.md)

**YourCRT** to natywna kobyła pod YouTube, ulepiona specjalnie dla **Sony Ericssona Xperia X10 Mini (E10i/E10a)** na fabrycznym, przedpotopowym **Androidzie 1.6 (Donut)**.

Żadnych **custom ROM-ów**, **żadnych kerneli** dłubanych przez piwniczaków — po prostu czyste, zapierające dech w piersiach wsparcie dla tego breloczka do kluczy zwanego "Robyn".

# Rekonstrukcja 2009 (czyli powrót do czasów, gdy świat był prostszy)

Prawdziwe odkrywanie: Kolejka ustawiona pod **„Najczęściej oglądane”** i **„Podobne”**. Tak jak w 2009, zanim te wszystkie zjebane algorytmy zaczęły nam wciskać syf, którego nikt nie chce oglądać.

Interfejs bez zbędnych bajerów: Te nowoczesne **„Gwiazdki”** wypierdoliłem za bramę. Zamiast nich masz surowe liczniki **Like/Dislike"**. 

Wygląda to jak 2009, a dane ciągnie z nowoczesnego API. 

Wilka syty i owca cała, kurwa.

Podpis V1 (Jedyny Słuszny): APK podpisany starym dobrym JAR-em (V1). 

Dlaczego? Bo ten uparty menedżer pakietów w **Androidzie 1.6** jest tak zacofany, że nowszych podpisów po prostu nie ogarnia i wywala błąd „Parsowania”, głąb jeden.

Mostek Render (Magia HTTP): Donut ma takie pojęcie o nowoczesnym SSL, jak ja o balecie. 

Dlatego omijamy to gówno przez autorski mostek HTTP na **Renderze**. 

Łączymy się z **YouTube API v3** bez pierdolenia się z certyfikatami.

# Specyfikacja Techniczna (czyli dlaczego to w ogóle dycha)

Klucz API na własność: Architektura **Direct-to-Google**. Wpisujesz swój klucz i masz stabilne połączenie zgodne z regulaminem. Nie bawimy się w jakieś lewe podchody.

Pamięć jak w NASA: Zoptymalizowane pod **karty microSDXC 64GB**. Tak, do **tego grata z 2010 roku wsadziłem 64 giga**. Możesz tam upchać tyle miniatur, że ten telefon szybciej zdechnie ze starości, niż zapełnisz kartę.

Odtwarzanie „Płynne jak masło”: Wymuszone **144p/240p** (itag 17/36). Tylko tyle, bo ten procek **ARMv6 600MHz** przy wyższej rozdzielczości dostałby sraczki i wybuchł w kieszeni.

# Wdrożenie i Rozwój (Produkcja chałupnicza)

Sprzęt dowodzenia: **Xiaomi 22126RN91Y (Redmi 12C)** — bo mój poprzedni telefon **(Huawei FIG-LX1/Huawei P Smart)** dostał ciążenia spożywczego i bateria spuchła jak po świętach u babci.

Zestaw małego chirurga: **MT Manager** (ciężka operacja na otwartym Smali).

Baza: Wypatroszony i wychłostany kod **notPipe**. Wszystkie **skrapery (Invidious, Yt2009, S60Tube itp.)** i opcje pobierania wyjebałem na śmietnik historii, żeby ten build był lekki i stabilny jak polska złotówka w dobrych czasach.

# Licencje

YourCRT: Apache 2.0 License

NNJSON: MIT License

# Credits (czyli komu postawić piwo, a kogo wyśmiać)

Gohoski: zrobił projekt [notPipe](https://github.com/gohoski/notpipe), który teraz muszę prostować, żeby był zgodny z regulaminem **Google** i **YouTube**. Oryginalny projekt łamie te zasady jak przepisy drogowe. Co za niereformowalny debil.

Lyano Community: zrobili sklep [Market Reborn](https://market.lyano.ovh). Dobra robota, chłopaki.

NNJSON: jakaś część kodu używa NNJSON, ale chuj wie która i po co. Ważne, że działa.

# _**Odpierdolone ręcznie, z przekleństwami na ustach, dla społeczności Robyn na Redmi 12C.**_
