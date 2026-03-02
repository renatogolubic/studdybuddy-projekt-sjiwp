![StudyBuddy Banner](/img/banner.jpg)

# StudyBuddy

**Platforma za dijeljenje bilješki i grupno učenje**

## Opis projekta

StudyBuddy je moderna web aplikacija namijenjena srednjoškolcima i studentima koji žele učinkovitije učiti kroz dijeljenje, ocjenjivanje i organizaciju bilješki i materijala. Glavni problem koji rješava je sljedeći: svaki dan tisuće učenika pišu gotovo identične bilješke iz istih udžbenika i predavanja, ali te bilješke ostaju zaključane u njihovim bilježnicama, WhatsApp grupama ili Google Docsovima koji brzo postanu kaotični i nepregledni.

Cilj aplikacije je stvoriti centralizirano, jednostavno i besplatno mjesto gdje korisnici mogu brzo pronaći kvalitetne materijale, podijeliti svoje znanje s drugima, dobiti povratne informacije kroz komentare i ocjene te učiti interaktivno pomoću flashcardsa. 

**Korisnici aplikacije:**
- Srednjoškolci (gimnazije i strukovne škole)
- Studenti fakulteta (posebno prve i druge godine)
- Grupe za učenje i razredne zajednice
- Ciljna dob: 15–25 godina

**Zašto baš ova tema?**
U hrvatskom obrazovnom sustavu nedostaje jednostavna, besplatna i lokalizirana platforma za dijeljenje bilješki. Postojeće aplikacije poput Quizlet, Notion ili Google Classroom su ili previše općenite, ili plaćene, ili nemaju fokus na hrvatske predmete (Matematika, Hrvatski, Fizika, Kemija, Povijest, Engleski itd.). StudyBuddy je zamišljen kao studentski projekt koji rješava upravo taj problem – omogućuje dijeljenje unutar škole ili smjera, a istovremeno motivira korisnike gamifikacijom i real-time povratnim informacijama.

Aplikacija koristi:
- **SolidJS** (JavaScript ES6+) za brzo i reaktivno korisničko sučelje
- **TailwindCSS + DaisyUI** za moderan, responzivan i lijep dizajn
- **Firebase** (Authentication, Firestore, Hosting) za sigurnu pohranu podataka i real-time ažuriranja
- **GitHub**

Studenti će moći kreirati bilješke u Markdown formatu, označiti ih kao privatne ili javne, pretraživati po predmetu ili ključnoj riječi, ocjenjivati tuđe materijale i učiti preko interaktivnih flashcarda.


## Tablica funkcionalnosti

### Osnovne mogućnosti 
- Registracija i prijava (email + Google login)
- Oporavak lozinke
- Kreiranje, uređivanje i brisanje vlastitih bilješki
- Označavanje bilješke kao privatna/javna
- Pretraga i filtriranje bilješki po predmetu, ključnoj riječi i autoru
- Pregled detalja bilješke (Markdown prikaz)
- Korisnički profil (ime, avatar, omiljeni predmeti, popis mojih bilješki)
- Dashboard s najnovijim i najpopularnijim bilješkama

### Napredne mogućnosti (ako ostane vremena)
- Komentari i ocjenjivanje bilješki (1–5 zvjezdica)
- Flashcards mod za učenje (flip kartice)
- Sustav bodova i jednostavna rang-lista
- Spremanje bilješki u favorite
- Filtriranje po ocjeni i broju pregleda

## Scenariji korištenja

1. **Novi korisnik**  
   - Otvori aplikaciju → registrira se emailom ili Google-om → postavi profil i odabere omiljene predmete → odmah vidi dashboard s preporučenim bilješkama.

2. **Kreiranje bilješke**  
   - Prijavljen korisnik klikne „Nova bilješka“ → odabere predmet → upiše naslov i sadržaj u Markdown editoru → označi javno/privatno → objavi.

3. **Traženje materijala**  
   - Korisnik na dashboardu odabere predmet „Matematika“ → upiše „  derivacije“ → otvori najbolje rangiranu bilješku → pročita → da ocjenu i komentar → spremi u favorite.

4. **Učenje flashcardsa**  
   - Otvori bilješku koja sadrži flashcards → klikne „Uči sada“ → pregledava kartice (pitanje ↔ odgovor) i bilježi točnost.

## Tehnologije
- Frontend: SolidJS + Vite
- Stilovi: TailwindCSS + DaisyUI
- Backend: Firebase (Auth + Firestore)
- Hosting: Firebase Hosting
- Verzioniranje: Git + GitHub

---

## Vizualni Prototip
![StudyBuddy Prototip1](/img/image1.jpg)

## FAZA 1 GOTOVA
