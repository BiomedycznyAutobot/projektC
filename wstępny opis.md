# projektC
Program do liczenia sum w koszykarskich zakładach bukmacherskich - aplikacja w konsoli.

Sumy to podstawowe zdarzenie wykorzystywane przez graczy celem wzbogacenia się, 
bądź też przepuszczania pieniędzy. Chodzi oczywiście o sumy punktów rzuconych przez obie drużyny w danym meczu.

Przykładowy zakład to poniżej/powyżej 205 pkt.

Program będzie pobierał dane (z internetu, bądź z pliku tekstowego, zobaczymy, czy damy radę z tym pierwszym :)),
a następnie na ich bazie liczył przewidywaną sumę punktów. Chcemy, aby uwzględniał on dane indywidualnych zawodników,
statystyki meczów u siebie i na wyjeździe, kontuzje, a także uwzględniał kursy bukmacherskie i proponował 
najkorzystniejszy jego zdaniem zakład. Nie znamy dokładnych założeń, które musi spełnić w ramach technologii,
ale będziemy w stanie w ramach potrzeb poszerzyć go o sumy punktów drużyn, przewidywane dokładne wyniki, bądź sumy punktów zawodników.
Na tą chwilę myślimy o lidze NBA, jako że Amerykanie mają bzika na punkcie statystyk, więc łatwo je zdobyć.
Możliwe, że uda nam się na tyle zoptymalizować kod, aby był w stanie liczyć z mniejszą dokładnością dla innych lig, np PLK.

MikołajMąkowski - opracowanie mechanizmów liczących na bazie danych

Maciej Wojciechowski - opracowanie wczytywania danych z Internetu bądź z pliku oraz optymalizacja i przejrzystość programu
