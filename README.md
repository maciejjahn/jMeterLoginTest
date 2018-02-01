# jMeterLoginTest

Przygtuj zestaw testów jMeter które umożliwią: (3 punkty)
1) zalogowanie do aplikacji www na podstawie danych z pliku excel
2) potwierdzenie, że do aplikacji www może zalogowac się więcej niż 5 osób.
3) sprawdzenie 3 wybranych stron oraz występowania na nich okreslonych wartości. Uzyj Regular Expression Extractor oraz if Controller oraz HTTP Request.
4) W przypadku braku wykycie okreslonych wartości, zapisz wynik jako SMOKE_TEST_FAILED w okreslonym pliku wynikowym. W przyciwnym wypadku zapisz wynik jako SMOKE_TEST_PASSED.
5) Sprawdzą maksymalne dopuszczalne obciążenie serwera i wykażą maksymalną dopuszczalną liczbę 'requestów'
6) Wygeneruje losowo liczbę (Random Variable) i potwierdzi że taka liczba występuje lub nie jako wartośc na stronie.
7) Pokaż rezultaty testów za pomocą: Summary Report oraz View Result Tree

Przygotuj zesataw testów które umożliwiają:(3 punkty)
1) Potwierdzenie ze baza danych jest uruchomiona i działa. W wybranym pliku zewnętrzym zapisze się potwierdzenie: DB_UP_AND_RUNNING. Przeciwnym razie: DB_FAILED. Simple data Writer.
2) odczytanie z pliku CSV wartości i zapytanie o nie bazę danych.
3) zgłosznie alarmu w pliku db_performance_Alert.txt jako "1" w przypadku gdy któreś zapytanie wykona się krócej niż X (określony w parametrze aplikacji). W przeciwnym razie wartośc w pliku wynosi "0".
4) Na podstawie pliku CSV przygotuje i wykona operację INSERT/UPDATE na bazie danych danych.
5) Odpali ten test cyklicznie co 2 minuty przez 10 minut każdego dnia.

Przygotuj test z użyciem trzech komponentów jMeter nie omawianych na zajęciach
