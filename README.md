# Capolavoro - Che Pizza : 
--- --- --- --- --- --- --- --- --- --- 

## Readme 

### 
<details>

<summary> File :: ReadMe.md </summary>

Continua a scrivere nel readme : 

- [GitHub Docs](https://docs.github.com/en)
- [sintassi basica di formattazione](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-  [iniziare a scrivere sul readme](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)
</details>

--- --- --- --- --- --- --- --- --- --- 

## HTML

### Struttura Base del file HTML 

<details>

<summary> Struttura HTML </summary>

```html
    <!DOCTYPE html>
    <html lang="en">
    <!-- Dentro Tag Head, Inserisci : -->
    <head>
        <!-- Tutti i Meta Tags Utili -->
        <!-- Tag Titolo -->
        <!-- I Tags Link CSS  -->
    </head>
    <!-- Dentro Tag Body, Inserisci : -->
    <body>
        <!-- Header -->
            <!-- Nav -->
        <!-- Main -->
            <!-- Le Varie Sezioni -->
        <!-- Footer -->
        <!-- I Tags Script JS  -->
    </body>
    </html>
```
    
</details >

--- --- --- --- --- --- --- --- --- --- 
## CSS

### Cosa posizionare per primo nel Tag Head, link css di bootstrap o il style.css?
[ Risposta da StackOverFlow](https://stackoverflow.com/questions/23902614/how-to-have-your-own-style-css-and-bootstrap-at-the-same-time)
```HTML
<link rel="stylesheet" href="css/bootstrap.css"> <!-- Sopra Bootstrap -->
<link rel="stylesheet" href="css/style.css"> <!-- Sotto il nostro CSS -->
```

<details> 

<summary> Come usare il :root nel file(style.css) :</summary>

#### dentro il file STYLE.CSS [:root{ --Riga:Da::02-- }](/style/style.css)
1. Scrivere un Nome/Selettore, ricordati di usare i trattini prima del nome 
    ```CSS 
    --nome-O-Selettore . . . 
    ``` 
2. Dopo il Nome/Selettore, scrivi due punti, inserisci il valore utile a lavoro del Selttore
    ```CSS
    . . . : "valore";
    ```
3. Fine del :root 
    ```CSS
    :root{
        --nome-O-Selettore: "valore";
    }
    ```
4. Utilizzo del ROOT, basta utilizzare il var() e dentro il Nome/Selettore
    ```CSS
    :root{ . . . }
    TagHTML/Classe/Id{
        <!-- proprietà: valore; -->
        proprietà: var(--nome-O-Selettore); 
    }
    ```



</details>


--- --- --- --- --- --- --- --- --- --- 