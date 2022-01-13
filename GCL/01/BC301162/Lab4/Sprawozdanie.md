# Metodyki DevOps, Zajecia 04, 13.01.2022, Bartlomiej Ciernia
 
Na początku należy uruchomić obrazy DIND oraz jenkins-blueocean. Instrukcja do tego jest w plikach z poprzedniego labu.
https://github.com/InzynieriaOprogramowaniaAGH/MDO2022/blob/BC301162/GCL/01/BC301162/Lab4/Lab4/1.png

Następnie logujemy się do naszego konta jenkins, które stworzyliśmy ostatnio, a następnie tworzymy nowy projekt. Wpisujemy nazwę i wybieramy typ projektu: Pipeline.
https://github.com/InzynieriaOprogramowaniaAGH/MDO2022/blob/BC301162/GCL/01/BC301162/Lab4/Lab4/3.png

W sekcji pipeline, wpisujemy poniższy skrypt.

Skrypt:
https://github.com/InzynieriaOprogramowaniaAGH/MDO2022/blob/BC301162/GCL/01/BC301162/Lab4/Lab4/4.png
Sekcja:
https://github.com/InzynieriaOprogramowaniaAGH/MDO2022/blob/BC301162/GCL/01/BC301162/Lab4/Lab4/5.png

Po wpisaniu uzupełnieniu pól, wciskamy przycisk Save i przechodzimy do projektu.
https://github.com/InzynieriaOprogramowaniaAGH/MDO2022/blob/BC301162/GCL/01/BC301162/Lab4/Lab4/6.png

W widoku projektu, na powyższym screenie, żeby odpalić nasz projekt, wybieramy opcję 

Build now

Po tym, w sekcji poniżej, widzimy jak nasz projekt jest wykonywany i w zależności od tego czy wykona się poprawnie czy nie, otrzymamy stosowny znak przy buildzie projektu.
U mnie udało się go zbudować za 44 razem (liczba iście Mickiewiczowska ;) ), ponieważ przy każdym buildzie znajdowałem błędy w moim skrypcie. 
https://github.com/InzynieriaOprogramowaniaAGH/MDO2022/blob/BC301162/GCL/01/BC301162/Lab4/Lab4/7.png

Aby przejrzeć build i znaleźć np. błędy, wciskamy #Numer buildu który nas interesuje, a następnie wybieramy sekcję 

Console output

https://github.com/InzynieriaOprogramowaniaAGH/MDO2022/blob/BC301162/GCL/01/BC301162/Lab4/Lab4/8.png

Poprawne wykonanie skryptu, pokaże nam komunikat który zamiesciłem poniżej.

https://github.com/InzynieriaOprogramowaniaAGH/MDO2022/blob/BC301162/GCL/01/BC301162/Lab4/Lab4/9.1.png
https://github.com/InzynieriaOprogramowaniaAGH/MDO2022/blob/BC301162/GCL/01/BC301162/Lab4/Lab4/9.2.png
https://github.com/InzynieriaOprogramowaniaAGH/MDO2022/blob/BC301162/GCL/01/BC301162/Lab4/Lab4/9.3.png
