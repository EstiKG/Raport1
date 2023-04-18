# Raport 2

1. Sprawdzam konfigurację:
- sieciową mojego laptopa, wpisując polecenie `ipconfig` w konsolę CMD

![image](https://user-images.githubusercontent.com/130842911/232762479-1aa86cce-8217-4e15-bfad-f68aa0217ec6.png)

- wyświetla znane sieci bezprzewodowe i kablowe oraz sieć, do której jestem obecnie połączona

- serwera zajęciowego, wpisując `ifconfig` w terminal

![image](https://user-images.githubusercontent.com/130842911/232764650-9f0b20ff-4387-45c0-a8b9-dbbc68358f41.png)

2. Interpretacja terminów:
- [x] `adres fizyczny` to unikalny numer identyfikacyjny przypisany karcie sieciowej urządzenia. Jest unikalny, więc urządzenia komunikujące się ze sobą w sieci mogą się identyfikować. Składa się z 48 bitów
- [x] `serwer DHCP` usługa, która umożliwia podłączonym do sieci komputerom pobieranie adresu IP, maski podsieci, adresu bramy i serwera DNS
- [x] `adres IP` to unikalny numer, który jest nadawany wszystkim urządzeniom elektronicznym podłączonym do sieci komputerowej
- [x] `maska podsieci` jest to liczba służąca do wydzielenia w adresie IP części, któa jest adresem podsieci i części będącej adresem hosta w tej podsieci
- [x] `brama domyślna` maszyna podłączona do sieci komputerowej, dzięki której komputery z sieci lokalnej mogą komunikować się z komputerami w innych sieciach.
- [x] `serwer DNS` to serwer, który szuka adresu IP danej strony na podstawie tego co użytkownik wpisał, czyli jest to tak jakby tłumacz nazw domen dla ludzi na dane liczbowe, które są zrozumiałe dla komputerów.

3. Polecenie `netstat`
- wykonuję badanie stanu komputera lokalnego, wyświetlają się aktywne połączenia, można odczytać rodzaj ich protokołu, adres lokalny, adres, z kórym się łączymy oraz stan połączenia

![image](https://user-images.githubusercontent.com/130842911/232771901-2675bb5c-c834-4b70-a4c2-5b19f19f28d8.png)

-wykonuję badanie serwera zajęciowego

![image](https://user-images.githubusercontent.com/130842911/232771557-8eb32546-3fbd-43ce-8466-a6dc21bd8699.png)

- [x] `-p` wyświetla rodzaj protokołu
- [x] `-t` wyświetla aktualny stan odciążenia połączenia
- [x] `-o` wyświetla identyfikatory PID związane z właścicielami portów
- [x] `-n` wyświetla adresy i numery portów w formie numerycznej
- [x] `-a` wyświetla wszystkie połączenia i porty nasluchujące

4. Polecenie `ping` jest to polecenie używane do diagnozy połączenia sieciowego

- sieci agh:

![image](https://user-images.githubusercontent.com/130842911/232782902-7e360440-d644-4a69-93de-693c0e72357e.png)
![image](https://user-images.githubusercontent.com/130842911/232783070-ee1fa3f1-7e37-478e-8bb7-949b5ae152ff.png)

- popularni dostawcy medialni:

![image](https://user-images.githubusercontent.com/130842911/232783966-0ac5c860-6757-4c11-b543-7cf440e32bfd.png)
![image](https://user-images.githubusercontent.com/130842911/232784516-ff56fe48-fce5-44d5-ac37-735467bf9c35.png)

- serwery w domenach zagranicznych:

![image](https://user-images.githubusercontent.com/130842911/232784904-61cfbe49-2fdd-409d-811d-29f953e81af3.png)
![image](https://user-images.githubusercontent.com/130842911/232785208-d18ddc15-95a1-438b-9adb-8a9c83ebc886.png)

- najszybciej zajęło dotarcie do panelu.agh.pl, tyle samo na strone głowną AGH oraz na rmf24.pl
- najdłuzej zajęło dotarcie na stronę Amazonu
- największą liczbę TTL (czasu żywotności pakietu) ma vogue.pl
- najmniejszą wartość TTL ma Twitter, vogue.com, macys.com, wp.pl

5. Polecenie `nslookup` służy do wyszukania szczegołowych informacji o wybranym adresie internetowym

- sieci agh:

![image](https://user-images.githubusercontent.com/130842911/232789187-d9b43c2d-6934-48c4-88ea-2b648ec4004f.png)

- popularni dostawcy medialni:

![image](https://user-images.githubusercontent.com/130842911/232792648-68c3b81c-af5a-4305-a560-e24c76001202.png)

- serwery w domenach zagranicznych:

![image](https://user-images.githubusercontent.com/130842911/232792315-3339e0be-a9fa-400c-ab0c-592ca9881439.png)

- wydaje mi się, że coś nie do końca działa dobrze, szczególnie przy sieciach agh

6. Polecenie `tracert` to narzędzie służące do śledzenia trasy pakietów IP w sieciach

![image](https://user-images.githubusercontent.com/130842911/232795017-4cd2181a-427d-4b13-a363-1a9de9b64f60.png)

