# Raport 2

1. Sprawdzam konfigurację:
- sieciową mojego laptopa, wpisując polecenie `ipconfig` w konsolę CMD

![image](https://user-images.githubusercontent.com/130842911/232762479-1aa86cce-8217-4e15-bfad-f68aa0217ec6.png)

- serwera zajęciowego, wpisując `ifconfig` w terminal

![image](https://user-images.githubusercontent.com/130842911/232764650-9f0b20ff-4387-45c0-a8b9-dbbc68358f41.png)

2. Interpretacja terminów:
- [x] `adres fizyczny` to unikalny numer identyfikacyjny przypisany karcie sieciowej urządzenia. Jest unikalny, więc urządzenia komunikujące się ze sobą w sieci mogą się identyfikować. Składa się z 48 bitów
- [x] `serwer DHCP` usługa, która umożliwia podłączonym do sieci komputerom pobieranie adresu IP, maski podsieci, adresu bramy i serwera DNS
- [x] `adres IP` to unikalny numer, który jest nadawany wszystkim urządzeniom elektronicznym podłączonym do sieci komputerowej
- [x] `maska podsieci` jest to liczba służąca do wydzielenia w adresie IP części, któa jest adresem podsieci i części będącej adresem hosta w tej podsieci
- [x] `brama domyślna` maszyna podłączona do sieci komputerowej, dzięki której komputery z sieci lokalnej mogą komunikować się z komputerami w innych sieciach.
- [x] `serwer DNS` to serwer, który szuka adresu IP danej strony na podstawie tego co użytkownik wpisał, czyli jest to tak jakby tłumacz nazw domen dla ludzi na dane liczbowe, które są zrozumiałe dla komputerów.

3.Polecenie `netstat`
- wykonuję badanie stanu komputera lokalnego, wyświetlają się aktywne połączenia, można odczytać rodzaj ich protokołu, adres lokalny, adres, z kórym się łączymy oraz stan połączenia

![image](https://user-images.githubusercontent.com/130842911/232771901-2675bb5c-c834-4b70-a4c2-5b19f19f28d8.png)

-wykonuję badanie serwera zajęciowego

![image](https://user-images.githubusercontent.com/130842911/232771557-8eb32546-3fbd-43ce-8466-a6dc21bd8699.png)

- [x] `-p` wyświetla rodzaj protokołu
- [x] `-t` wyświetla aktualny stan odciążenia połączenia
- [x] `-o` wyświetla identyfikatory PID związane z właścicielami portów
- [x] `-n` wyświetla adresy i numery portów w formie numerycznej
- [x] `-a` wyświetla wszystkie połączenia i porty nasluchujące

