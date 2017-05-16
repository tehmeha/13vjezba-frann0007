# 13vjezba
## Tehmeha 13. vježba
- na početku napravite “fork” projekta “13vjezba” s GitHub-ovog korisničkog računa "ZDamijan" u svoj Github korisnički račun
- pomoću GitHub Desktop-a napravite "clone" tog projekta na svoje računalo i kreirajte novu mapu "13vjezba-Prezime" i u njoj napišite C++ program “mini-banka.cpp” koji ima niže navedene funkcionalnosti 
- nakon svake implementirane funkcionalnosti napraviti “commit” (u opisu prepisati tekst pod odgovarajućim brojem) 
- na kraju potrebno je sinkronizirati lokalni i udaljeni repozitorij i napraviti "Pull Request" (u opisu napisati 13. vježba, ime prezime) na ishodišni repozitorij na računu "ZDamijan"                                                                                                        
<br/><b>Mini banka</b> - implementirajte sljedeće funkcionalnosti:	
1. Korisniku se prikazuje glavni izbornik (unos nove osoba, ispiši sve podatke, pretraga prema računu, pretraga prema prezimenu i imenu, ispiši sortirano prema prezimenu i imenu).
2. Korisnik unosi novu osobu u banku:
  <br/> - broj racuna - unsigned long long int, pr. 3252455656
  <br/> - prezime i ime - string
  <br/> - saldo - float, pr. 152.48
3. Korisniku se mogu ispisati svi podaci, nesortirani.
4. Korisnik može pretraživati prema broju racuna te mu se ispisuju podaci pronađene osobe ili se ispiše poruka da takva osoba nije pronađena.
5. Korisnik može pretraživati prema prezimenu i imenu osobe te mu se ispisuju podaci pronađenih osoba ili se ispiše poruka da takva osoba nije pronađena.
6. Program nakon što korisnik doda novu osobu sprema te podatke u datoteku “banka.txt”.
7. Kada korisnik pokrene program učitavaju se svi podaci osoba iz datoteke “banka.txt”.
8. Korisnik prema unesenom broju računa može mijenjati saldo osobe ili osobu izbrisati iz baze.
9. Izmijenjeni ili izbrisani podaci moraju biti sinkronizirani s datotekom “banka.txt”.
10. Korisniku se mogu ispisati svi podaci uzlazno sortirani po prezimenu i imenu osobe.
