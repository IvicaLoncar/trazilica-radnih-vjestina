# Tražilica radnih vještina

![Alt text](/slike/trazilica-pocetna.png?raw=true "Tražilica povezuje")

Zapošljavanje preko oglasa za posao često je sporo i traje tjednima, ponekad i mjesecima.

Tržište se brzo mijenja i ako se na vrijeme ne reagira, ukazana prilika može biti propuštena.

Tražilica radnih vještina je unaprijed pripremljena baza podataka radnih vještina, znanja i sposobnosti fizičkih ili pravnih osoba.

Zbog unaprijed pripremljene baze podataka, kandidati za obavljanje određenog posla mogu biti poznati unutar nekoliko minuta.

Upravo ta brzina omogućuje da se na vrijeme reagira na promjene na tržištu i iskoristi prepoznata prilika.

Preduvjet za tražilicu radnih vještina je da fizičke ili pravne osobe upišu svoje profile radnih vještina, znanja i sposobnosti u bazu podataka tražilice.

Tražilica se može koristiti za sljedeće scenarije ponudi i potražnji:
1. zapošljavanje - na puno ili polovično radno vrijeme, kratkotrajne zadatke, projekte
2. zapošljavanje osoba s invaliditetom - poslovi koji se nude osobama s invaliditetom
3. usavršavanje - projekti/zadaci koji će nekome biti usavršavanje u karijeri
4. prekvalifikacija - promjena karijere
5. događanje - tečajevi, predavanja, seminari, priredbe, sajmovi, ...
5. volontiranje - ponuda i potražnja 
6. pomoć u radu - npr. branje jabuka
7. osnovne škole - npr. suveniri
8. srednje škole - npr. proizvodi iz njihovih radionica ili povezivanje obrtničkih škola s gospodarstvom
9. visoko školstvo - npr. povezivanje s gospodarstvom
10. hobiji - povezivanje ljudi oko hobija
11. zabava - povezivanje oko raznih oblika zabave, npr. restorani, zabavni parkovi
12. sport - nije ponuda poslova za sport nego aktivnosti vezane uz sportske klubove, skupljanje članova, projekti, skupljanje donacija
13. turizam - nije ponuda poslova za turizam, nego turistička ponuda u određenom mjestu uključujući i lokalne prehrambene proizvode
14. ponuda - općenita ponuda koja ne pripada u neku od gornjih kategorija, npr. usluga miješanja boje u prodavaonici boja

Tražilica radnih vještina je jezgra većeg projekta koji se može nazvati web aplikacijom i ima dodatne mogućnosti.

# Prva mogućnost web aplikacije je udruživanje korisnika pod zajednički cilj i dijeljenje podataka. 

U slučaju kad je u poduzeću zaposleno više ljudi, normalno je da oni rade zajedno i dijele zajedničke podatke. 
Ta mogućnost neće biti ograničena samo na poduzeća. Svaka osoba, i fizička i pravna, moći će se udruživati s drugim fizičkim ili pravnim osobama. 
Također, svaka osoba će moći biti istovremeno udružena s više različitih drugih osoba i raditi na više različitih ciljeva.
U scenarijima udruživanja uvijek će jedna osoba biti glavna osoba i ona će biti vlasnik podataka.
Primjer gdje se fizička osoba udružuje s drugom osobom mogao bi biti gradnja kuće kod koje fizička osoba angažira arhitekta kao pridruženog člana da u njegovo ime dogovara poslove oko gradnje kuće, a vlasnik podataka ostaje fizička osoba.
Kod malih poduzeća koja nemaju specijalizirane zaposlenike za zapošljavanje drugih, malo poduzeće može pozvati nezavisnog headhuntera da kao pridruženi član u ime malog poduzeća provodi postupak odabira novih zaposlenika.
Ponekad će malo poduzeće imati potrebu pozvati nezavisnog procjenjitelja projekta kojeg može pozvati da kao pridruženi član radi procjenu u ime malog poduzetnika.
Pozivanje drugih osoba na udruživanje provodi se slanjem pozivnica.

## Organiziranje dijeljenih podataka u grupe i podgrupe

U slučajevima većih poduzeća koje rade s većim količinama podataka, pojavljuje se potreba za organizacijom svih tih podataka radi lakšeg snalaženja.
Web aplikacija podržava grupiranje na dvije razine: grupe i podgrupe. 
Unutar podgrupa nalaziti će se podaci o aktivnostima.

## Prava pristupa grupama i podgrupama

Često je slučaj da unutar istog poduzeća svi zaposlenici nemaju pravo pristupati svim podacima.
Kod ove web aplikacije pravo pristupanja dodjeljuje se na razini grupa i podgrupa.
Glavni korisnik i osobe označene kao administratori imaju neograničeni pristup svim grupama i podgrupama.
Dvije su razine pristupa, prva je čitaj i piši, druga je samo čitaj (kod ove razine nije moguće ažurirati podatke u bazi podataka).
Nove grupe mogu dodavati samo glavni korisnik ili pridruženi članovi koji su administratori.
Osim glavnog korisnika i administratora, nove podgrupe mogu dodavati još i pridruženi članovi koji su administratori grupe u koju se dodaje podgrupa.

## Privatni podaci vs. dijeljeni podaci

Svaki korisnik ima svoje privatne podatke koje vidi samo on i nitko više.
Glavni korisnik može u isto vrijeme imati privatne podatke i biti vlasnik dijeljenih podataka.
Isključivo kao vlasnik dijeljenih podataka, glavni korisnik moći će prebacivati podatke između svojih dijeljenih i privatnih podataka u oba smjera.
U slučaju kad korisnik nije vlasnik podataka on neće moći prebaciti dijeljene podatke u svoje privatne podatke.
S druge strane, kad korisnik nije vlasnik podataka on će moći klonirati svoje privatne podatke i prebaciti ih u dijeljene podatke nekog drugog glavnog korisnika.

# Druga mogućnost web aplikacije je popunjavanje profila radnih vještina

Profili radnih vještina su polustrukturirani kroz tri opcionalne razine detaljnosti.
Prva razina je općenita.
Druga razina je srednje detaljno.
Treća razina je detaljno.
Te tri razine su hijerarhijski povezane.
Onaj dio profila radnih vještina koji nije strukturiran je sadržaj kojeg korisnik sam upisuje.
Profile radnih vještina mogu popunjavati glavni korisnik ili pridružen član kojem su dodijeljene administratorske mogućnosti.

# Vrste aktivnosti

Aktivnost je nešto kao samostalni zadatak kojeg se obavlja preko web aplikacije.
Vrste aktivnosti su: 
1. korištenje tražilice - pretražuje se baza podataka radnih vještina, 
2. oglasi - slično oglasima za posao, kandidat koji se prijavljuje mora biti korisnik web aplikacije, 
3. projekti - moguće okupljati druge osobe oko ostvarivanja složenijih ciljeva, 
4. rezervacije događaja - omogućava drugim osobama da se prijave kao sudionik nekog događaja, seminara, tečaja, predavanja
Po potrebi se mogu dodavati i neke druge vrste aktivnosti.

# Anonimizacija

Neki podaci fizičkih osoba koje vrati tražilica biti će anonimizirani tj. modificirani, tako da se neće znati pravo ime, prezime i id kandidata.
Anonimizacija se provodi šifriranjem AES algoritmom na razini aktivnosti, to znači da će isti kandidat imati različite anonimizirane nazive i id-jeve na različitim aktivnostima.
Anonimizacijom se štite osobni podaci fizičkih osoba.
Kad dvije osobe imaju namjeru uspostaviti poslovnu suradnju, normalno je da između njih više ne postoji anonimizacija i da međusobno jedan drugome vide ime, prezime i id u nešifriranom obliku.
Fizička osoba upravlja anonimizacijom i može odlučiti hoće li točno određenom klijentu maknuti anonimizaciju.

# Osobni podaci i GDPR

Koristiti će se samo minimalno potrebni osobni podaci fizičkih osoba kao što su ime i prezime.
Neki podaci biti će u određenim slučajevima anonimizirani.
Korisnik će moći upravljati pristupom svojim osobnim podacima davanjem ili uklanjanjem privola.

# Bilješke

Bilješke su komentari o različitim podacima s kojima se radi unutar web aplikacije. (slično sticky notes)
Jedan način podjele bilješki je prema vlasništvu:
1. privatne bilješke - može ih čitati samo vlasnik
2. dijljene bilješke - može ih čitati vlasnik i pridruženi članovi ovisno o pravima pristupa

Drugi način podjele bilješki je prema podacima na koje se odnose:
1. općenita bilješka je globalna bilješka kojoj mogu pristupiti samo glavni korisnik ili pridruženi član u ulozi administratora
2. bilješka o tipu profila - odnosi se na jedan od profila, npr. zapošljavanje, volontiranje, prekvalifikaciju, ...
3. bilješka o kategoriji - odnosi se na neku od definiranih kategorija, npr. kod zapošljavanja to može biti Informatika i telekomunikacije
4. istovremeno 2. i 3.
5. bilješka o osobi - to je osoba koja nije anonimizirana nego je poznat njezin naziv ili ime i prezime i id, može se kombinirati sa 2. i/ili 3.
6. bilješka o grupi - bilješka se može odnositi na grupu koja služi za organiziranje aktivnosti, može se kombinirati sa 2. i/ili 3.
7. bilješka o podgrupi - bilješka se može odnositi na podgrupu unutar neke grupe koja služi organiziranju aktivnosti, može se kombinirati sa 2. i/ili 3.
8. bilješka o aktivnosti - samostalni zadatak također može imati bilješke, može se kombinirati sa 2. i/ili 3.
9. bilješka o rezultatu - svaka aktivnost može imati više rezulata, svaki od njih može imati bilješke, može se kombinirati sa 2. i/ili 3.
10. bilješka o kandidatu - u slučaju anonimizacije nije poznat kandidat, pa je ovo način da se pridruži bilješka toj nepoznatoj osobi
     - isti kandidat može biti uključen u različite rezultate, zbog toga nije obavezno odabrati rezulat kojem pripada kandidata, već je dovoljno navesti aktivnost, ali i dalje ostaje opcija da se i rezultat navede u bilješki pa će se onda ta bilješka primjenjivati na točno odabranu aktivnost, rezultat i kandidata
     - moguće je koristiti u kombinacijama sa 2. i/ili 3.
11. bilješka o svojstvu - svojstvo je radna vještina, znanje ili sposobnost u slučaju zapošljavanja
     - svojstvo pripada kandidatu koji je uglavnom anonimiziran i nalazi se na aktivnosti
     - za bilješke svojstva, rezultat kojem pripada kandidat neće se koristiti
     - svojstva mogu biti definirana na tri razine (razine detaljnosti profila) i moguće je za svako svojstvo bez obzira na kojoj razini se nalazi dodijeliti bilješke
     - može se kombinirati sa 2. i/ili 3.

U bilo kojem slučaju pisanje bilješki o različitim objektima u web aplikaciji važan je alat za pohranu stanja, te za komunikaciju u slučaju kad više pridruženih članova radi zajedno. 
U bilješkama se pohranjuje znanje, podaci i informacije o raznim objektima s kojima se radi.


# Slanje poruka prema kandidatima

S odabranim kandidatima moguće je razmjenjivati poruke koje mogu dovesti do novih poslovnih suradnji.

# Responzivni dizajn

Web aplikacija će biti podržana na uređajima ekrana različite veličine, trenutno za mobitel i desktop, u budućnosti će vjerojatno biti dodano i za tablete.

# Slike

## Desktop, uređivanje korisnikovog profila radnih vještina
Tri su stupca za opis radnih vještina, za općeniti opis (lijevo), srednje detaljni opis (sredina) i detaljni opis (desno)
![Alt text](/slike/desktop_uredjivanje_profila.png?raw=true "Desktop uređivanje korisnikovog profila radnih vještina")

## Desktop, pregled vrsta profila koje korisnik može popuniti
Korisnik može popuniti različite vrste profila, na slici se s lijeve strane vidi lista iz koje je moguće odabrati željenu vrstu profila
![Alt text](/slike/desktop_vrste_profila.png?raw=true "Desktop pregled vrsta profila koje korisnikovog može popuniti")

## Desktop, uređivanje pridruženih članova i grupa aktivnosti
U slučaju većih poduzeća ili udruživanja većeg broja ljudi, raditi će se s većim količinama podataka, zato će biti moguće grupirati aktivnosti.
S lijeve strane slike nalazi se lista pridruženih članova koji mogu raditi na zajedničkim projektima, svaka osoba može biti povezana s više drugih osoba istovremeno, ali uvijek je samo jedna osoba glavna osoba i ona je jedini vlasnik tzv. dijeljenih podataka
S desne strane slike nalaze se grupe koje mogu imati podgrupe (organiziranje na dvije razine) i moguće je dodjeljivati prava pristupa grupama i podgrupama i na taj način ograničiti vidljivost i mogućnost uređivanja aktivnosti pridruženim članovima
![Alt text](/slike/desktop_uredjivanje_clanova_i_grupa.png?raw=true "Desktop uređivanje pridruženih članova i grupa aktivnosti")

## Desktop, rad sa aktivnostima, rezultatima, kandidatima i radnim vještinama
Ovo je glavni ekran tražilice radnih vještina preko kojeg je moguće pratiti mnoge indikatore vezane uz odabir kandidata.
Slični ekrani biti će razvijeni i za neke druge vrste aktivnosti kao što su oglasi, projekti, rezervacije događaja, ...
Krajnje lijevi stupac predstavlja filtrirane aktivnosti na kojima osoba želi raditi s kratkim opisom i indikatorima o porukama i bilješkama.
Do njega s lijeve strane je stupac rezultata odabrane aktivnosti. Svaka aktivnost može imati više rezultat i svaki rezultat je zabilježen u bazi podataka, rezultat se sastoji od više predloženih kandidata.
U sredini se nalazi stupac s općenitim podacima nekih kandidata odabrane aktivnosti i odabranog rezultata.
Ono što se može primjetiti je anonimizacija naziva kandidata.
S desne strane nalazi se kolona u kojoj se nalaze podaci o radnim vještinama kandidata s indikatorima iz kojih se vide pojedinačni i agregatni statusi radnih vještina, te indikatori poruka koje se izmjenjuju i bilješki koje su napisane.
S obzirom da ovaj ekran treba prikazati jako velike količine podataka o različitim kanididatima, korištenje indikatora omogućava tzv. strateški pregled nad kompliciranom situacijom.
![Alt text](/slike/desktop_pregled_aktivnosti_i_rezultata.png?raw=true "Desktop rad sa aktivnostima, rezultatima, kandidatima i radnim vještinama")

## Bilješke radnih vještina
Ideja je povezivati bilješke na razne podatke u web aplikaciji slično kao što se sticky notes može lijepiti na raznim mjestima.
Jedno od mjesta za koje će se pisati bilješke su i radne vještine kandidata.
Bilješke mogu biti i privatne u kojem slučaju će ih vidjeti samo osoba koja ih je napisala.
U slučaju rada s više pridruženih članova, jedni drugima će vidjeti napisane bilješke prema pravima pristupa postavljenim na grupe i podrgrupe aktivnosti.
![Alt text](/slike/biljeske_radnih_vjestina.png?raw=true "Bilješke radnih vještina")

## Globalni rad s bilješkama
Globalni rad i pregledavanje bilješki omogućava lakše snalaženje u velikom broju bilješki povezanih na podatke od kojih su mnogi hijerarhijski povezani.
![Alt text](/slike/desktop_biljeske.png?raw=true "Globalni rad s bilješkama")

## Odabir korisnika za kojeg se trenutno radi
Svaki korisnik može biti udružen s više drugih korisnika i u bilo kojem trenutku može odabrati za kojeg korisnika će raditi.
Nakon odabira novog korisnika, slijedi zamjena konteksta koji prvo uključuje čišćenje svih podataka dosadašnjeg korisnika, a zatim učitavanje podataka novo odabranog korisnika.
![Alt text](/slike/desktop_odabir_korisnika.png?raw=true "Odabir korisnika za kojeg se trenutno radi")


## Mobitel, uređivanje korisnikovog profila, općenita razina opisa radnih vještina
![Alt text](/slike/mobile_profil_opceniti_opis.png?raw=true "Mobitel, uređivanje korisnikovog profila, općenita razina opisa radnih vještina")

## Mobitel, uređivanje korisnikovog profila, srednja razina detaljnosti opisa radnih vještina
![Alt text](/slike/mobile_profil_malo_detaljniji_opis.png?raw=true "Mobitel, uređivanje korisnikovog profila, srednja razina detaljnosti opisa radnih vještina")

## Mobitel, uređivanje korisnikovog profila, najdetaljniji opis radnih vještina
![Alt text](/slike/mobile_profil_najdetaljniji_opis.png?raw=true "Mobitel, uređivanje korisnikovog profila, najdetaljniji opis radnih vještina")

## Mobitel, udruživanje korisnika 
![Alt text](/slike/mobile_udruzivanje_s_korisnicima.png?raw=true "Mobitel, udruživanje korisnika")

## Mobitel, uređivanje grupa i prava pristupa
![Alt text](/slike/mobile_uredjivanje_grupa_i_prava_pristupa.png?raw=true "Mobitel, uređivanje grupa i prava pristupa")

## Mobitel, privatne grupe aktivnosti
![Alt text](/slike/mobile_privatne_grupe.png?raw=true "Mobitel, privatne grupe aktivnosti")

## Mobitel, popis aktivnosti
![Alt text](/slike/mobile_popis_aktivnosti.png?raw=true "Mobitel, popis aktivnosti")

## Mobitel, lista rezultata odabrane aktivnosti
![Alt text](/slike/mobile_rezultati_odabrane_aktivnosti.png?raw=true "Mobitel, lista rezulatata odabrane aktivnosti")

## Mobitel, podaci kandidata
![Alt text](/slike/mobile_podaci_kandidata.png?raw=true "Mobitel, podaci kandidata")

## Mobitel, radne vještine kandidata
![Alt text](/slike/mobile_radne_vjestine_kandidata.png?raw=true "Mobitel, radne vještine kandidata")

