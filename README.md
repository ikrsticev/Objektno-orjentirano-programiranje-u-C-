# Objektno-orjentirano-programiranje-u-C-sharpu

Projekt je napravljen u Visual Studio 2012 verziji. Profesori su nam dali neki game engine koji su oni napravili da bismo sa njim napravili igru u kojoj bi primjenili koncepte objektno orjentiranog programiranja.

Specifičnost moje igre je u tome da lik interaktira s bojom , odnosno bojom pozadine. Umjesto detektiranja kolizije spriteova, u ovoj igri također ima i detektiranje boje pozadine, odnosno ako je pozadina crna lik se neće pomaknuti.

Aplikacija učitava sliku i provjerava koordinate slike i koordinate prema kojima bi se lik trebao pomaknuti. Ako se unutar matrice pixela  na kojima bi pixel trebao biti kad se pomakne nalazi ijedan crni pixel ( RGB (0,0,0) ), metoda vraća False i pomak se ne dogodi.U protivnom lik se miče onoliko pixela koliko mu je svojstvo speed.

Aplikacija bi mogla potencijalno biti nadograđena tako da kontrola boje bude apsolutna, odnosno da ne vrijedi samo za pozadinu nego da vrijedi za sve objekte.
