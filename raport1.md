# Raport 1

1. Uruchomiam plik PuTTY i konfiguruję go.
2. Loguję się.
3. Generuję klucze RSA przy pomocy `ssh-keygen`. Znajduję je. Kopiuję je na konto na serwerze student. Pracuję z konsoli mts-a na koncie studenta, korzystjąc z polecenia `ssh`. Znajduję klucz za pomocą polecenia `ls –a`. Pierwsze znajduję .ssh, następnie przeszukuję znaleziony folder, w którym znajdują się moje klucze publiczne. Żeby przejść do konta student, nie muszę się logować, wystarczy, że użyję polecenia `ssh` i podam nazwę mojego konta.

![image](https://user-images.githubusercontent.com/130842911/232226518-3c3ff60d-88fc-421e-8021-c45d7765fa4e.png)

4. Zakładam katalog o nazwie tmp, w tym katalogu tworzę plik tekstowy dane.txt, który zawiera moje imię i nazwisko. Następnie zmieniam uprawnienia pliku.

- [x] `mkdir` - polecenie, które tworzy folder
- [x] `mcedit` - polecenie, które tworzy i umożliwia edycję pliku
- [x] `chmod` - polecenie, które zmienia uprawnienia
 
![image](https://user-images.githubusercontent.com/130842911/232227121-2f441ba4-75ae-466b-acfc-1d1d0f0e2593.png)

5. Wyświetlam procesy

![image](https://user-images.githubusercontent.com/130842911/232230135-30fc98c8-f832-4cc5-8171-966f1d2cbeaa.png)

![image](https://user-images.githubusercontent.com/130842911/232230212-c61d4878-44ff-4b45-8191-c00b5cd6d1a8.png)

![image](https://user-images.githubusercontent.com/130842911/232230313-da4009fd-144c-4c2a-9d8b-0a5f41f3afc1.png)

![image](https://user-images.githubusercontent.com/130842911/232230332-94e5f561-dea4-4ab2-ab63-df0921d45785.png)

- [x] `ps` wyświetla procesy z terminala, w którym się znajdujemy
- [x] `ps -A` wyświetla wszystkie procesy
- [x] `ps aux` wyświetla wszytskie procesy, nawet te, które nie są związane z żadnymi terminalami
- [x] `ps t` nazwa_teminalu wyświetla wszystkie procesy związane z podanym terminalem
- [x] `pstree` wyświetla procesy w formie drzewa
- [x] `top` wyświetla wszystkie procesy i ich stan, jest najbardziej szczegółowy

6.Sprawdzam ile użytkowników jest na serwerze

![image](https://user-images.githubusercontent.com/130842911/232232146-d33c6bef-c100-4a68-b7b1-f2d440bb1c62.png)

- [x] `who` wyświetla listę użytkowników obecnie zalogowanych na serwer
- [x] `wc -l` liczy, ile jest linii w podanym pliku tekstowym

7. Zmiana hasła za pomocą polecenia `passwd`.
8. szukam pliku passwd w systemie

![image](https://user-images.githubusercontent.com/130842911/232232847-0264117a-2154-43b2-b9c9-6b9d60661e7b.png)

- [x] `find / -name '*passwd*' > haslo.txt` wyszukuje w katalogu głównym wszystkie pliki, które zawierają passwd i przekierowuje je do pliku haslo.txt

9. Sprawdzam w jakim katalogu pracuję

![image](https://user-images.githubusercontent.com/130842911/232233786-1373df1d-509b-482d-8783-d631678f0bc8.png)

- [x] `pwd` wyświetla ścięzkę katalogu, w któym obecnie się znajdujemy
- [x] `cd` pozwala na przemieszczanie sie pomiędzy katalogami
- [x] `cd ..` pozwala na przemieszczenie się do katalogu wyżej

10. Tworzę plik z moimi danymi

![image](https://user-images.githubusercontent.com/130842911/232234445-aedc380a-bf54-427e-a9d3-b105a5fb51f7.png)

- [x] `echo` komenda wypisująca tekst
- [x] `>>` dopisuje tekst do pliku
- [x] `>` pisze tekt w pliku, ale usuwa tekst, który był w pliku

11. Usuwam katalog

![image](https://user-images.githubusercontent.com/130842911/232234630-bcddf652-571e-4c7a-af20-1ae25679954e.png)

- [x] `rm` pozwala usunąć plik tekstowy
- [x] `rm -r` pozwala na usunięcie katalogu, który ma zawartość

> 12. Zakładam katalog public_html, który pozwoli na publikowanie strony WWW
> 13. Tworzę plik tmp.txt
> 14. Umieszcam w nim teskt
> 15. Zmieniam nazwę na index.html

> ![image](https://user-images.githubusercontent.com/130842911/232235000-80d79fe7-1c72-48ca-9b66-b81be65117b4.png)


16. Sprawdzam prawa dostępu pliku
17. Usuwam plik tmp.txt
18. Liczę, ile linii ma plik index.html

![image](https://user-images.githubusercontent.com/130842911/232235107-c9334f71-6b7d-4d20-a619-756cebc90ad9.png)

> 19. Sprawdzam moją stronę w przeglądarce internetowej
> 20. Usuwam w pliku html linijkę `<meta charset="UTF-8">`, strona przestaje wyświetlać polskie znaki. Z powrotem dodaję tą linijkę i polskie znaki wracają
> 21. Minimalnymi prawami, żeby strona była wyświetlana jest dla pliku `r--r--r--`, a dla katalogu `r-xr-xr-x`

> ![image](https://user-images.githubusercontent.com/130842911/232237384-cec3b597-20d6-4eb7-b8e3-35097fa94cda.png)

22. Tworzę archiwum

![image](https://user-images.githubusercontent.com/130842911/232236398-5f6eb7c1-510b-424d-962c-c7a46e401dc4.png)

- [x] `tar cfv` polecenie, które tworzy archiwum
- [x] `tar xfv` polecenie, które dekompresuje pliki i katalogi

24. Wprowadzam motyfikację mojej strony

