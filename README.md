materiały:

https://drive.google.com/drive/folders/1O1jaZERyK-c5zE4nFmvGiPRq49EBIdP2

wykłady:

https://drive.google.com/drive/folders/1f0UB4lYdH0QKCK58Ne9f_9sxnZvPbHN_



=====================

Schemat:

Pracownik (id_pracownika, imie, nazwisko, zarobki)

Stanowisko (id_stanowiska, specyfikacja, usluga)

Klient (id_klienta, imie, nazwisko, telefon, samochod, email, typ_samochodu)

Usluga (id_uslugi, typ_samochodu, cena, czas, nazwa_uslugi)

Zlecenie (id_zlecenia, id_pracownika, id_klienta, id_uslugi, data, godzina, cena, stan_zlecenia)

Typ_samochodu (id_typu, nazwa)



Usluga(1, 'osobowy', 160.00, 30, 'wymiana opon, alusy')

Klient(1, 'Jan', 'Kowalski', '666 666 666', 'Audi', 'a@a.pl', 'osobowy')

Stanowisko(1, 1, 'osobowe, ciezarowe, autobusy, tramwaje')

Pracownik(1, 'Tomasz', 'Nowak', 10000)

Zlecenie (1, 1, 1, 1, 21.06.2000, 16:00, 999, 'pf')
