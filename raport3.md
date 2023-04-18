# Raport 3

1. Pobieram program `psftp.exe` i za jego pomocą loguję się na swoje konto na serwerze zajęciowym. Korzystam z polecenia `open nazwa_hosta`.
2. Tworzę lokalnie plik plik.txt, w którym wpisuję swoje dane: imię nazwisko, nr indeksu, godzinę zajęć oraz zapisuję polskie znaki.
3. Wysyłam utworzony plik na moje konto zajęciowe za pomocą polecenia `put`, muszę wpisać lokalizację pliku, który chcę przesłać
4. Zapisuję lokalnie 3 grafiki
5. Wysyłam je na serwer zajęciowy za pomocą polecenia `mput` pozwala ono na przesłanie kilku plików

![image](https://user-images.githubusercontent.com/130842911/232825709-ac9dea28-bbc3-4c7f-94a6-dd8c0621e361.png)

6. Kopiuję pliki przy pomocy `pscp.exe`

![image](https://user-images.githubusercontent.com/130842911/232830764-c28de82e-10a8-48f3-a9d0-a234e092d551.png)

7. Przy kopiowaniu przez `psftp.exe` logujemy się na serwer zajęciowy i możemy tam wykonać różne rzeczy, jak na przykład przeglądnięcie plików. Natomiast, przy kopiowaniu przez `pscp.exe` musimy się logować przy każdym kopiowaniu.
8. Loguję się na konto zajęciowe i przy pomocy polecenia `scp` kopiuję plik na konto na serwerze student.

![image](https://user-images.githubusercontent.com/130842911/232832892-8c81d87e-2258-4e42-a1fd-385415dd8cdf.png)

9. Pobrałam pliku z serwera do katalogu tmp za pomocą `psftp.exe` i polecenia `get`. Żeby nie wpisywać ścieżek lokalizacji przemieściłam się za pomocą poleceń `cd` i `lcd` do odopwiednich lokalizacji.

![image](https://user-images.githubusercontent.com/130842911/232836617-454255af-a008-4829-b55f-bc558639e899.png)
