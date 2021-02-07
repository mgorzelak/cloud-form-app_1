# cloud-form-app_1
WSB project


Budowa-i-Administracja-Aplikacji-w-Chmurze
Prosty rssSender na zajecia z Budowa i Administracja Aplikacji w Chmurze

Zadaniem aplikacji jest ściąganie zawartości RSS z podanych przez użytkowników linków.

Aplikacja składaa się z klienta (tzw frontend), serwera (tzw. backend) i bazy danych Frontend to prosta strona, na której użytkownik może zapisywać linki RSS przez serwer do bazy danych. Backend oprócz tego, że komunikuje się z bazą danych ma za zadanie stworzyć maila, który będzie zawierał wszystkie artykuły, które znajdują się pod podanymi linkami przez użytkownika.

Frontend zawierający kontrolki: Textbox z możliwością wpisania urla do RSS Przycisk Save zapisujący urla do bazy danych Frame, który będzie pokazywał zbudowanego maila przez backend Przycisk Preview który będzie requestował do backendu o zbudowanie takiego maila

Backend moduł do zapisywania linków do bazy moduł, który buduje maile w formie html'a

Dzialajaca aplikacja: link do dzialajacego sampla na heroku

https://bpwsbapp1.herokuapp.com/

Instrukcja

Aplikacja ma za zadanie wysyłać wiadomości mail rss do adresatów i z linkami zebranymi w bazie. Bazę adresatow i linków można uzupełniać z frontu.

Dla prawidłowego działania wymagane jest skonfigurowanie kilku plików zgodnie z utworzoną bazą oraz samo utworzenie bazy. Szczegóły poniżej



Konfiguracja serwera MySql i tworzenie bazy

Nazwa bazy i uzytkownika podane są jako przykładowe, mogą być dowolne.

a) zaloguj się do https://portal.azure.com/

b) w pasku wyszukiwania wpisz mysql i wybierz „Serwer usługi Azure Database dla MySQL”
