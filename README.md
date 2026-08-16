# Fag - Visualisering

* **Niveau:** V3
* **Emne:** Grundlæggende PHP og CRUD PHP
* **Website:** Kogebog CMS

---


## Beskrivelse

Velkommen til dette projekt, hvor du skal bygge dit eget **Kogebog CMS** (Content Management System) fra bunden ved hjælp af PHP, MySQL og moderne webteknologier.

I dette forløb kommer du til at arbejde praktisk med ægte back-end-udvikling. Du lærer at oprette forbindelse til en database, hente og vise dynamisk indhold, samt bygge fuld **CRUD-funktionalitet** (Create, Read, Update, Delete), så brugerne kan oprette, redigere, se og slette lækre opskrifter.

Projektet er bygget op som et professionelt udviklingsforløb, hvor du bruger **GitHub Issues** som din opgaveliste og lærer at strukturere din kode, så den følger gængse branchestandarder.

---

## Sådan kommer du i gang med opgaven

Følg disse trin for at sætte dit projekt rigtigt op, før du kaster dig over koden:

### 1. Kopiér websitet via Actions
For at få dit eget eksemplar af projektet og aktivere opgavesystemet, skal du bruge GitHub Actions:
1. Gå til fanen **Actions** i dette repository.
2. I menuen til venstre, klik på det workflow, der hedder "Opret kopi af repository"
3. Klik på **Run workflow** for at starte processen.
4. Indtast dit fornavn, fulde navn, login (de fem cifre) eller noget andet, som identificerer dig (det bliver en del af navnet på dit eget opgave repository)
5. Når actionen er færdig, vil den automatisk oprette et nyt repository til dig, som hedder V3-php-kogebog-'det du indtastede i punkt 4' og en række **Issues** under "Issues"-fanen i dit nye repository. Hvert "Issue" er en opgaver, som du skal løse.

### 2. Tilføj din lærer som Collaborator

For at din lærer kan følge med i dit arbejde og give dig feedback, når du er færdig med en opgave, skal du tilføje vedkommende som samarbejdspartner:

1. Gå ind i dit nye repository under AspIT-Education - Repositories.
2. Klik på **Settings** (Indstillinger) i topmenuen.
3. Vælg **Collaborators** i venstre menu.
4. Klik på **Add people** og indtast din lærers brugernavn eller e-mail, og inviter dem.

### 3. Arbejd med dine opgaver (Issues)

Når du henter dette template-repository, vil der automatisk blive genereret en række opgaver under fanen **Issues**.

* Gå ind under **Issues**-fanen for at se din "to-do"-liste for forløbet.
* Hver issue repræsenterer en opgave, som du skal løse.

### 4. Skriv gode commits og kobl dem til opgaverne

Når du skriver kode og gemmer dine ændringer undervejs, er det vigtigt, at du laver små, præcise commits med gode beskrivelser.

For at koble dine commits direkte sammen med den opgave (issue), du arbejder på, skal du skrive **issue-nummeret** (f.eks. `#1`) i din commit-beskrivelse.

**Eksempel på en god commit-beskrivelse i terminalen:**

```bash
git add .
git commit -m "Opretter databaseforbindelse i config.php #1"
git push

```

Hvis du skriver `closes #1` eller `fixes #1` i din commit-tekst, vil GitHub automatisk lukke opgaven for dig, når du pusher koden!

### 5. Lav en Pull Request, når du er færdig

Når du har løst en opgave eller flere mindre opgaver, skal du oprette en **Pull Request (PR)** for at få feedback fra din lærer:

1. Gå til **Pull Requests**-fanen i dit opgave repository.
2. Klik på **New pull request**.
3. Giv din Pull Request en tydelig titel og en kort beskrivelse af det, du har lavet.
4. Klik på **Create pull request**.

Nu får din lærer besked på mail, kan gennemgå din kode direkte på linjeniveau og give dig værdifuld feedback!

---

* God arbejdslyst med koden!
