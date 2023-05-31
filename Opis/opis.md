<div style="display: flex;">
    <span> Michał Mękarski </span>
    <span style="text-align: right;flex-grow: 1;"> 
        332747 
    </span>
</div>

------------------------------

<center> 

## Opis Projektu Końcowego

##### Programowanie Obiektowe

------------------------------

</center>

### User Story

Inspiracją do utworzenia tego projektu jest moje lenistwo.

*W jakiej formie?*

Na codzień prowadzę korepetycje i męczy mnie konieczność każdorazowego wpisywania godzin do rozliczenia z klientami i wysyłanie ich mailem.
Uznałem, że napisanie aplikacji ułatwiającej mi pracę będzie wystarczającym motywatorem, aby projekt ten został przeze mnie dowieziony i był odpowiedniej jakości.

### Mechanika Projektu

Aby wszystkim było wygodnie *klienci* będą mieli indywidualne *kalendarze* w których to będą wpisane wszystkie spotkania.
Każdy *klient* będzie miał przypisane konto bankowe, z którego będą wpływały przelewy, a moja aplikacja będzie automatycznie wysyłać prośby o zapłatę i potwierdzenia rozliczenia.

Implementacja finalnej aplikacji (UI) nie została uwzględniona w schemacie, gdyż nie jest istotnym elementem projektu.

Planuję zaimplementować ją jako klasę *AppCLI* dziedziczącą po klasie *App*.

### Pierwsza Iteracja

W pierwszej iteracji klasy 

- *CalendarProvider*
- *TransactionProvider*
- *MailSender*

będą prostymi mockami z zhardcode'owanymi danymi.

### Diagram Klas
![Diagram Klas](MlyCal.drawio.svg)