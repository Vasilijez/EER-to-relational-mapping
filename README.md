# Opis projekta
Svrha projekta predstavlja prevođenje iz EER (*extended-entity relationship*) modela podataka (konceptualni) u relacioni model podataka (implementacioni). Tema projekata je Železnički informacioni sistem. Korišćen je [Oracle SQL Developer Data Modeler](https://github.com/Vasilijez/EER-to-relational-mapping/tree/main/projekat_data_modeler) kao alat za prevođenje. 

Projekat se sastoji iz nekoliko etapa.  
* U prvoj etapi se vrši specificiranje statičke strukture realnog sistema kroz [EER model](https://github.com/Vasilijez/EER-to-relational-mapping/blob/main/EER.png) uz [dokumentovanje](https://github.com/Vasilijez/EER-to-relational-mapping/blob/main/specifikacija.docx) iste.
* U drugoj etapi se vrši prevođenje u relacioni model podataka, [analitički](https://github.com/Vasilijez/EER-to-relational-mapping/blob/main/prevo%C4%91enje_analiti%C4%8Dki.pdf).
* U trećoj etapi se pomoću odgovarajućeg alata vrši kreiranje [logičkog modela](https://github.com/Vasilijez/EER-to-relational-mapping/blob/main/logi%C4%8Dki_model.pdf) u odabranom alatu uz poštovanje prethodnih koraka.
* U četvrtoj etapi se generiše [relacioni model](https://github.com/Vasilijez/EER-to-relational-mapping/blob/main/relacioni_model.pdf) u odabranom alatu - ovaj postupak se obavlja automatski.
* U petoj etapi se vrše određene korekcije [relacionog modela](https://github.com/Vasilijez/EER-to-relational-mapping/blob/main/relacioni_model.pdf), ukoliko je to potrebno, i generišu se DDL naredbe u skladu sa odgovarajućom verzijom baze podataka.
* U šestoj etapi se koriste izgenerisane DDL naredbe kako bi se kreirala šema baze podataka, i nakon toga se eventualno baza podataka popunjava podacima uz mogućnost kreiranja upita. [Skriptovi](https://github.com/Vasilijez/EER-to-relational-mapping/blob/main/skriptovi.txt)

**Napomena:** Moguće je da se u zavisnosti od odabranog CASE alata koraci razlikuju.
