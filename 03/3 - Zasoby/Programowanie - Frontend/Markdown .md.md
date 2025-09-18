## Podstawowe formatowanie tekstu

- **Nagłówki**: Użyj symbolu `#` na początku linii. Im więcej `#`, tym niższy poziom nagłówka.
    
    - `# Nagłówek Poziomu 1`
        
    - `## Nagłówek Poziomu 2`
        
    - `### Nagłówek Poziomu 3`
        
- **Pogrubienie**: Otocz tekst podwójnymi gwiazdkami `**tekst**` lub podwójnymi podkreśleniami `__tekst__`.
    
    - **To jest pogrubiony tekst.**
        
- **Kursywa**: Otocz tekst pojedynczymi gwiazdkami `*tekst*` lub pojedynczymi podkreśleniami `_tekst_`.
    
    - _To jest tekst w kursywie._
        
- **Pogrubienie i kursywa**: Połącz poprzednie metody: `***tekst***`.
    
    - **_To jest pogrubiony i kursywny tekst._**
        
- **Przekreślenie**: Otocz tekst podwójnymi tyldami `~~tekst~~`.
    
    - ~~To jest przekreślony tekst.~~
        

---

## Listy

- **Listy nieuporządkowane**: Użyj gwiazdki `*`, myślnika `-` lub plusa `+` na początku linii.
    
    - `* Element listy 1`
        
    - `- Element listy 2`
        
    - `+ Element listy 3`
        
- **Listy uporządkowane**: Użyj cyfr z kropką na początku linii. Kolejność cyfr nie ma znaczenia dla renderowania, ale pomaga w czytelności.
    
    - `1. Pierwszy element`
        
    - `2. Drugi element`
        
    - `3. Trzeci element`
        
- **Zagnieżdżanie list**: Wciśnij spację (zazwyczaj 2 lub 4), aby stworzyć zagnieżdżoną listę.
    
    - `1. Element nadrzędny`
        
        - `* Zagnieżdżony element 1`
            
        - `* Zagnieżdżony element 2`
            
    - `2. Kolejny element nadrzędny`
        

---

## Linki i obrazy

- **Linki wewnętrzne**: Linkuj do innych notatek w swoim skarbcu Obsidian. Użyj podwójnych nawiasów kwadratowych `[[nazwa_notatki]]`.
    
    - `[[Moja notatka o Git]]`
        
    - Możesz też dodać alias: `[[Moja notatka o Git|Więcej o Git]]`
        
- **Linki zewnętrzne**: Użyj pojedynczych nawiasów kwadratowych dla adresu URL i podwójnych dla tekstu linku: `[tekst linku](adres_URL)`.
    
    - `[Oficjalna strona Markdown](https://daringfireball.net/projects/markdown/)`
        
- **Obrazy**: Podobna składnia jak do linków zewnętrznych, ale poprzedzona wykrzyknikiem `!`.
    
    - `![Tekst alternatywny obrazka](ścieżka_do_obrazka.jpg)`
        
    - Możesz też linkować obrazy z innych notatek.
        

---

## Cytaty blokowe i bloki kodu

- **Cytaty blokowe**: Użyj symbolu `>` na początku linii.
    
    - `> To jest cytat blokowy.`
        
- **Bloki kodu**: Otocz kod potrójnymi backtickami (````` ``` ````). Możesz też określić język programowania dla podświetlania składni.
    
    JavaScript
    
    ```
    function greet(name) {
      console.log("Hello, " + name + "!");
    }
    greet("World");
    ```
    
- **Kod liniowy**: Użyj pojedynczych backticków `` ` `` wokół fragmentu kodu.
    
    - Wywołaj funkcję `greet("User")`.
        

---

## Inne formatowanie

- ## **Poziome linie**: Użyj trzech lub więcej myślników `-`, gwiazdek `*` lub podkreśleń `_` na osobnej linii.
    
- **Listy zadań**: Użyj listy nieuporządkowanej z nawiasami kwadratowymi `[ ]` dla pustego pola lub `[x]` dla zaznaczonego.
    
    - `- [ ] Zadanie do wykonania`
        
    - `- [x] Zadanie zakończone`