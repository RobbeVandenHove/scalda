# Hoe kan je de presentatie bekijken?

## Installeer git op je PC

Ga naar <a href="https://git-scm.com/download/win">deze link</a> en installeer git. Let op wanneer je de stappen uitvoert van de git installer. Zorg ervoor dat je de optie <b>Use git from the Windows Command Prompt</b> selecteerd. Zoniet zal je zelf een PATH moeten toevoegen om git via de command prompt te laten werken.

## Installeer nvm (node version manager) op je pc

Ga naar <a href="https://github.com/coreybutler/nvm-windows/releases">deze link</a>. Scroll naar beneden waar je alle downloads ziet. Zorg ervoor dat je <b>nvm-setup.zip</b> installeerd. Open de gedownloade zip-file en voltooi alle stappen van de nvm installer.

## Maak een mapje

Maak op je pc ergens een mapje waarin je de "website/presentatie" wilt opslaan. Open nu dit mapje in de cmd. Voer dit command in, in de cmd.

```
git clone https://github.com/RobbeVandenHove/scalda.git
```

Je zal zien dat er nu een mapje in jou mapje is aangemaakt met de naam presentatie.

Voer daarna deze commando's uit.

```
nvm install --lts
```

```
nvm use --lts
```

## Opstarten

De allereerste keer dat je de presentatie wilt opstarten zal je eerst dit commando moeten uitvoeren.

```
npm install
```

Elke keer dat je de presentatie wilt zien zal je een aantal commando's moeten uitvoeren voordat je de presentatie kan opstarten.

```
git pull
```

```
npm start
```

Ga nu in je browser naar http://localhost:8000 om de presentatie te zien.
