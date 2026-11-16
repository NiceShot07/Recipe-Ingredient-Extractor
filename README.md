# Recipe Ingredient Extractor

Proiect pentru materia Natural Language Processing and Text Mining,
dezvoltat în Python folosind Google Colab.

## Scop

Proiectul urmărește extragerea cantității, unității de măsură și
numelui ingredientului din texte de rețete în limba engleză,
folosind expresii regulate și un model de clasificare.

Exemplu de rezultat dorit:

| Text de intrare | Cantitate | Unitate | Ingredient |
|---|---|---|---|
| 200 g flour | 200 | g | flour |
| 1/2 cup milk | 1/2 | cup | milk |

Aceste rezultate reprezintă obiectivul proiectului.
Extragerea nu este implementată încă.

## Progres

- [x] Crearea primului notebook în Google Colab
- [x] Definirea unor exemple de ingrediente
- [x] Organizarea exemplelor într-un tabel pandas
- [ ] Alegerea și explorarea unui dataset real
- [ ] Preprocesarea textului
- [ ] Extragerea ingredientelor folosind reguli
- [ ] Antrenarea unui model de clasificare
- [ ] Combinarea regulilor cu modelul
- [ ] Evaluarea și demonstrarea sistemului

## Structura proiectului

- `notebooks/01_data_exploration.ipynb` — descrierea proiectului
  și explorarea inițială a unor exemple scrise manual.

Celelalte notebookuri vor fi adăugate pe parcurs.

## Rulare

1. Deschide notebookul din folderul `notebooks`.
2. Apasă pe butonul „Open in Colab”.
3. În Colab, selectează „Runtime → Run all”.

Versiunea actuală afișează cinci exemple de ingrediente și
le organizează într-un tabel. Nu necesită fișiere de date externe.

## Instrumente folosite până acum

- Python
- Google Colab
- pandas
- GitHub
