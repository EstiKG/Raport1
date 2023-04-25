# Raport 4

1. Zapoznałam się z zawartością dokumentów [RFC 1945],  [RFC 2616] oraz [RFC 7540].
2. Badam działanie protokołu http:
- uruchomiam program putty i ustawiam:
-[x] connection type: `raw`
-[x] Host name: `mts.wibro.agh.edu.pl`
- [x] Port: 80
- [x] Close window on exit: never
- W oknie putty wpisuję polecenia żądania protokołu HTTP:
- [x] `GET /~s416281/ HTTP/1.1`
- [x] naciskam ENTER
- [x] wpisuję `Host: mts.wibro.agh.edu.pl`
- [x] naciskam 2 razy ENTER

![image](https://user-images.githubusercontent.com/130842911/234340047-9a23247d-8c24-4531-956e-8b209979d86c.png)
 
- wyświetla się zawartość mojego pliku index.html tylko bardzo rozrzucona

- sprawdzenie odpowiedzi serwera na:
- [x] błędnie wpisany nagłówek

![image](https://user-images.githubusercontent.com/130842911/234340931-a35f7fde-9310-47e4-bd77-9862ad83c2bd.png)
 
- [x] niepoprawny adres strony

![image](https://user-images.githubusercontent.com/130842911/234342829-c5c5f00f-6905-40a5-b2b4-7a50085d40f6.png)

- [x] niepoprawny adres hosta

![image](https://user-images.githubusercontent.com/130842911/234342209-0739931e-bfd0-4071-9533-dae7e10d1884.png)

- na początku wszystko działało, ale po chwili stało się to co w pozostałych, przestały być aktywne.
3. Sprawdzam szybkość ładowania stron:
- [x] wp.pl - niezaliczone
- [x] amazon.com - zaliczone
- [x] github.com - niezaliczone
- [x] youtube.com - niezaliczone
- [x] instagram.com - niezaliczone
- [x] x-kom.pl - niezaliczone
4. `URL` (Uniform Resource Locator) - służy do lokalizacji plików w sieciach lokalnych i Internecie. 
### https://www.przyklad.com
- [x] `https` – nazwa protokołu
- [x] `www` – nazwa usługi internetowej
- [x] `przyklad` – domena
- [x] `com` – rozszerzenie
