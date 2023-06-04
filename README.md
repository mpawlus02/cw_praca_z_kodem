INSTRUKCJA

1.Sklonuj zdalne repozytorium- git clone https://github.com/nazwa_uzytkownika/nazwa_repozytorium.git
2.Przejdz do folderu z repozytorium za pomoca cd /sciezka/do/repozytorium
3.Stworz wirtualne srodowisko: python -m venv nazwa_folderu
4.Aby aktywowac wirtualne srodowisko wykonaj polecenie: nazwa_folder/bin/activate
5.Aby zainstalowac potrzebne rquirementsy uruchom komende za pomoca Makefile:

make install

Aby uruchomic aplikacje flask wykonaj:
make run
Jezeli chcesz wejsc na adres http://127.0.0.1:5000/, nalezy otworzyc 2 terminal i wykonac tam komende curl http://127.0.0.1:5000/

Aby sprawdzic kod za pomoca pylint wykonaj: 
make pylint

Plik README jest bardzo wazny, poniewaz sluzy jako dokumentacja projektu, ktora zawiera jego funkcjonalnosci, instrukcje, sposob uzycia oraz konfiguracji. Jest to miejsce do ktorego potencjalni uzytkownicy powinni zagladnac w pierwszej kolejnosci.
