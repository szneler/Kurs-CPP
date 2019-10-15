# Kurs-CPP
i
Materials from C++ Course at Coders School (January 2019 - March 2019)

<<<<<<< HEAD
## 14.01.2019 Narzędzia programisty (scrum, kompilacja, systemy budowania)

### Pre-work
- [X] Zapoznaj się pobieżnie ze [standardem kodowania Google](https://google.github.io/styleguide/cppguide.html) oraz [standardem kodowania LLVM](https://llvm.org/docs/CodingStandards.html). Możesz je porównać i wychwycić podobieństwa i różnice.
- [X] Poszukaj samemu informacji o tym, czym jest Makefile
- [X] Poszukaj samemu informacji o tym, czym jest Scrum
- [X] Koniecznie utwórz Pull Requesta (PR), aby powiadomić mnie o statusie Twojej pracy domowej, najlepiej gdy wykonasz wszystko. PR możesz potem aktualizować.

### Materials
- [Ściągawka - Niektóre opcje kompilacji](sciaga_opcje_kompilacji.pdf)
- [Ściągawka - Scrum](sciaga_scrum.pdf)
- [Scrum Framework](ScrumFramework.pdf)
- [Cmake documentation](https://cmake.org/cmake/help/v3.13/manual/cmake-commands.7.html)
- Foto z zajęć: <img src="kompilacja.jpg" width="250px"> <img src="zasady_kodowania.jpg" width="250px">
  <img src="tablica0.jpg" width="250px"> <img src="tablica1.jpg" width="250px">

### Post-work (deadline: 20.01.2019)
- [ ] Sforkuj [repozytorium modern_cpp](https://github.com/LordLukin/modern_cpp) (przycisk Fork na GitHub). Spowoduje to skopiowanie projektu na twoje konto GitHuba. Napisz poprawny Makefile do tego projektu, który wykorzystuje zmienne. Wkomituj go i udostępnij na GitHubie, zrób Pull Requesta. [Przydatny link](http://mrbook.org/blog/tutorials/make/)
- [ ] Posłuchaj [podcastu o Scrumie](http://mariuszchrapko.com/jak-scrum-wplywa-na-efektywnosci-zespolu/)
- [ ] Zrób [test Narzędzia programisty](https://goo.gl/forms/EQurphnqBaOG20U32)

### Pre-work for the next lesson (deadline 15.01.2019)
- [X] Obejrzyj [wideo jak działa alokacja pamięci](https://www.youtube.com/watch?v=CSVRA4_xOkw)
- [X] Obejrzyj [wideo o tym, jak działają wskaźniki](https://www.youtube.com/watch?v=W0aE-w61Cb8)
- [X] Wpisz poniżej 3 rzeczy, które wg siebie najmniej rozumiesz w C++ i zrób Pull Request :)
  - szablony
  - funkcje wirtualne(teorie rozumiem ale nigdy nie uzylem w kodzie)
  - konwersje



## 15.01.2019 Podstawy C++

### Pre-work 
- [X] Obejrzyj [wideo jak działa alokacja pamięci](https://www.youtube.com/watch?v=CSVRA4_xOkw)
- [X] Obejrzyj [wideo o tym, jak działają wskaźniki](https://www.youtube.com/watch?v=W0aE-w61Cb8)
- [X] Wpisz poniżej 3 rzeczy, które wg siebie najmniej rozumiesz w C++ i zrób Pull Request :)
  - szablony
  - funkcje wirtualne(teorie rozumiem ale nigdy nie uzylem w kodzie)
  - konwersje


### Materials
- [C++ keywords on cppreference.com](https://en.cppreference.com/w/cpp/keyword)
- [C++ operators on cppreference.com](https://en.cppreference.com/w/cpp/language/expressions#Operators)

### Post-work (deadline: 20.01.2019)
- [ ] Zrób [test Podstawy C++](https://goo.gl/forms/SkTtLHKSW6mWHYE13)
- [ ] **W grupach 2-3 osobowych napiszcie program, który będzie przechowywał dane o studentach.**
  Wymagania:
  - System budowania (preferowany CMake, ewentualnie Makefile)
  - Przechowywanie rekordów o strukturze: Imię, nazwisko, nr indeksu.
  - Wpisywanie nowych danych
  - Sortowanie po numerze indeksu
  - Usuwanie po numerze indeksu
  
  UWAGA: Tutaj nacisk kładziemy na pracę grupową. Każda osoba z grupy musi coś wkomitować.
  Program będzie dalej rozwijany w przyszłości. Teraz najważniejsze będzie zorganizowanie się, podzielenie pracy i commitowanie do wspólnego repozytorium
  Pamiętajcie o [MVP (Minimal Viable Product)](https://goo.gl/images/D3Jeam)
  **Podajcie linka do projektu na Discordzie, ale już w momencie jego utworzenia, a nie ukończenia!**
- [ ] Zrób ściągawkę na jeden z poniższych tematów do wyboru. Obowiązkowo daj w niej przykłady kodu:
  - stos i sterta
  - przekazywanie parametrów - kopia, wskaźnik, referencja
  - konwersje jawne i niejasne, operatory konwersji, konstruktory konwertujące, rodzaje konwersji (static, dynamic, const, reinterpret, C-style)
  - operatory (porównania, strumienia, arytmetyczne, ...)
  - słówka kluczowe - static, extern, inline, explicit, register, friend, volatile, virtual, mutable
  - wyjątki
  
  Wybrany temat **zaznacz pogrubieniem**
  Ściągę wrzuć na Discorda podziel się nią z grupą. Reszta grupy da komentarze, czy wszystko jest jasne czy nie. **Termin: 29.01.2019**.

### Pre-work for the next week (deadline: 21.01.2019)
- [ ] Zapoznaj sie bardzo ogólnie z dokumentacja C++: http://en.cppreference.com/w/
- [ ] Przeczytaj artykuł mojego kolegi Marcina Pietraszka o złożoności obliczeniowej: http://www.samouczekprogramisty.pl/podstawy-zlozonosci-obliczeniowej/
- [ ] Zapoznaj sie dokładniej z opisem kontenerów: http://en.cppreference.com/w/cpp/container
- [ ] Playlista na YT odnośnie STLa: https://www.youtube.com/playlist?list=PL5jc9xFGsL8G3y3ywuFSvOuNm3GjBwdkb - obejrzyj ile mozesz :)
=======
## 08.01.2019 [L01 - linux, git, vim](L01-linux,git,vim)
## 14.01.2019 [L02 - compilation, make, cmake, formatting](L02-compilation,make,cmake)
## 15.01.2019 [L03 - C++ fundamentals](L03-cpp-fundamentals)
## 21.01.2019 [L04 - computational complexity, STL containers](L04-stl-containers)
## 22.01.2019 [L05 - STL iterators, functor, lambdas, algorithms](L05-stl-itertors,functors,lambdas,algorithms)
## 04.02.2019 [L06 - STL algorithms, intro to testing](L06-algorithms,testing)
## 05.02.2019 [L07 - Objective C++](L07-objective-cpp)
## 11.02.2019 [L08 - Testing](L08-testing)
## 12.02.2019 [L09 - Memory Management](L09-memory-management)
## 19.02.2019 [L10 - Memory Management and Modern C++](L10-memory,modern-cpp)
## 26.02.2019 [L11 - Modern C++](L11-modern-cpp)
## 05.03.2019 [L12 - Good Programming Practices](L12-good-practices)
## 12.03.2019 [L13 - Templates, Design Patterns, Repetition](L13-templates,patterns,repetition)
## 18.03.2019 [L14 - Design Patterns, Repetition, Recruitment](L14-patterns,repetition,recruitment)
## 26.03.2019 [L15 - Design Patterns, Repetition, Recruitment](L15-patterns,repetition,recruitment)

## [Test końcowy](https://goo.gl/forms/kL6KUj7u55UbCX4x2)
Do zrobienia do niedzieli 24.03.2019 do 23:59 - obowiązkowo dla wszystkich. Jest to warunek uzyskania certyfikatu.
## Projekt grupowy [Logical Images](https://github.com/LordLukin/LogicalImages) lub [Bowling](https://github.com/LordLukin/Bowling)
Musisz mieć przynajmniej 1 dostarczone zadanie. Jest to warunek uzyskania certyfikatu.
>>>>>>> bff39e40403c8c9b25b9c84151994300ab2db1b1

