# Die Sprache CQbd (c cubed but funny lol)

## Die Main-Funktion

Ein Programm braucht einen Startpunkt. Dieser, auch Eintrittspunkt genannt, ist
in CQbd die sogenannte `main`-Funktion. Sie wird wie folgt erstellt:

```CQbd
fnc main {
	// ...
}

fnc void main() {
	// ...
}

fnc void main(let vec(string) args) {
	// ...
}

fnc void main(let vec(string) args, let vec(string) env) {
	// ...
}

fnc main(args, env) {

}
```
