# Cosa è Kotlin
Kotlin è un linguaggio di programmazione NON C-LIKE, staticamente tipizzato e multi-paradigma basato sulla JVM di Java. Pertanto, tutte le classi e librerie di Java sono interoperabili con Kotlin.

***
***
> E' possibile cominciare a scrivere in Kotlin anche senza installere un jdk, visto che Intellij dorebbe gestire tutto con il suo runtime integrato. Tuttavia, è consigliabile installare comunque un JDK nel caso in cui poi, in futuro, volessimo invece passare da un IDE come Intellij IDEA a qualcosa come [**VSCode**](https://code.visualstudio.com/download)
***

***
# Come installare Kotlin (Linux)


## · Arch Linux:
- **Aggiorna il sistema**: `utente@hostname$: sudo pacman -Syu`
- **Verifica versione java**: `utente@hostname$: java -version`
> Se l'output è negativo

- **Installa java**: `utente@hostname$: sudo pacman -S jdk-openjdk`
**Installa una versione specifica**: `utente@hostname$: sudo pacman -S jdk17-openjdk`

- **Installa Intellij Idea dalla AUR**: `utente@hostname$: yay -S intellij-idea-community-edition-no-jre`
> Puoi sostituire "*yay*" con qualsiasi altro AUR manager

> Sostituire il 17 con la versione desiderata del jdk

> Su derivarte come EndeavourOS e Manjaro, l'IDE potrebbe essere disponibile direttamente dalle repo ufficiali

## · Ubuntu/Debian:
- Installa [**Flatpak**](https://flatpak.org/setup/)

- **Verifica versione java**: `utente@hostname$: java -version`
> Se l'output è negativo:

- **Installa Java**: `utente@hostname$: sudo apt install openjdk-17-jre-headless`

> Sostituire il 17 con la versione desiderata del jdk

- **Installa Intellij**: `utente@hostname$: flaptak install com.jetbrains.IntelliJ-IDEA-Community `

***
***
## · Windows
- **Installa [Java dal sito ufficiale](https://www.oracle.com/java/technologies/downloads/#jdk20-windows)**

- **Installa [Intellij Idea](https://www.jetbrains.com/idea/download/?section=windows)**

> Scorri in basso per quello community!

***
***
## · Macos

- **Installa [Intellij Idea](https://www.jetbrains.com/idea/download/?section=windows)**

(Opzionale) Puoi anche installarlo tramite Brew









