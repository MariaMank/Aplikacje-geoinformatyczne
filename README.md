# Programowanie Aplikacji Geoinformacyjnych

Projekt został wykonany grupowo w celu zaliczenia przedmiotu Programowanie Aplikacji Geoinformacyjnych.

Celem pracy było zaimplementowanie aplikacji, która umożliwi zapisanie danych do baz danych typu 
NoSQL, a następnie na ich podstawie umożliwi obliczenie statystyk dla wybranych stacji pomiarowych 
w obrębie wybranego powiatu lub województwa.

Dane do opracowania statystyk zostały pobrane z strony https://dane.imgw.pl/datastore , w aplikacji
dostępny jest wybór zasobu: hydrologicznego lub meteorologicznego.
Dane przestrzenne zostały pobrane z zasobu udostępnionego przez prowadzącego.
Dane astronomiczne zostały obliczone za pomocą biblioteki Astral na podstawie danych przestrzennych
oraz statystycznych.

![image](https://github.com/MariaMank/Aplikacje-geoinformatyczne/assets/92314221/6f9c6740-7256-479d-99bf-97050a726e76)

Aplikacja pobiera dane z linku lub z bazy, które następnie przetwarza i, w zależności od wybranej opcji,
zapisuje do wybranej bazy danych. Wartości obliczonych statystyk - średniej i mediany
dla poszczególnych dni, z podziałem na dane pomierzone w dzień oraz w nocy - prezentowane są 
w postaci wykresów

