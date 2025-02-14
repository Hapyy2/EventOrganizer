# EventOrganizer
SQL database project for an event management application. 

# Organizator Wydarzeń  
  Baza danych dotyczy organizacji wydarzeń na małą skalę. Celem jest pomoc w zorganizowaniu
oraz usystematyzowaniu danych dla sprawniejszego dostępu do poszczególnych informacji o
konkretnych wydarzeniach lub ludzi z nimi związanych.  

Opis tabel:  
- Adresy – tabela zawierające wszystkie dokładne adresy całej bazy
- Uczestnicy – tabela z osobami biorącymi udział w wydarzeniu
- Pracownicy – tabela mająca pełną listę pracowników wydarzeń z podziałami na stanowiska
- Lokale – tabela z miejscami gdzie możliwe jest przeprowadzanie wydarzeń
- Bilety – tabela zawierająca różne rodzaje przepustek oraz ich ceny
- Wydarzenia – tabela z wydarzeniami, ich okresem trwania oraz miejscem
- Pomocnicze tabele: personel_wydarzenia (wiele pracowników dla wielu wydarzeń), kupione_bilety (każdy może mieć wykupione wiele biletów na różne wydarzenia)

Założenia projektu:  
- Ilość pracowników na każdym stanowisku
- Przedstawienie wydarzeń zapisanych na konkretny lokal
- Ilość sprzedanych biletów dla danego wydarzenia
- Ilość dostępnych wolnych miejsc na wydarzenie (Lokale: maks_ludzi – sprzedane bilety)
- Aktualny przychód z biletów na dane wydarzenie (Biorąc pod uwagę różne rodzaje biletów)
- Kalendarz wydarzeń na dany miesiąc (Przedstawienie wszystkich zaplanowanych wydarzeń na dany miesiąc)
<br>

![Screenshot of project diagram.](https://github.com/Hapyy2/EventOrganizer/blob/main/diagram.png)
