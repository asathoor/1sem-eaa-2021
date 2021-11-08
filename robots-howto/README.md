# Eksempel: robots.txt

Når du vil anmode søgemaskinger om **IKKE** at registrere din webside, så skal du tilføje denne fil i roden af dit site:

`robots.txt`

Indholdet i filen er:

~~~~
User-agent: *
Disallow: / 
~~~~

Det kan oversættes til "User-agent" er søgemaskiner, og stjernen betyder "alle søgemaskiner". Man kan evt. vælge, hvilke søgemaskiner, der ikke skal indeksere. Disallow / betyder, at alle filer på sitet er omfattet.


I html `<head>` kan du tilføje denne tag:

~~~~
<meta name="robots" content="noindex" />
~~~~

Mere om robots.txt - [se her](https://www.wikihow.com/Block-Search-Engines)
