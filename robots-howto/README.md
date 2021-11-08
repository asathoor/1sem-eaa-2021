# Eksempel: robots.txt

Når du vil anmode søgemaskinger om **IKKE** at registrere din webside, så skal du tilføje denne fil i roden af dit site:

`robots.txt`

Indholdet i filen er:

~~~~
User-agent: *
Disallow: / 
~~~~

Det kan oversættes til "User-agent" er søgemaskiner, og stjernen betyder "alle søgemaskiner". Disallow / betyder, at alle filer på sitet er omfattet.

Mere om robots.txt - [se her](https://www.wikihow.com/Block-Search-Engines)
