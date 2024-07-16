# Projektdokumentation

## Voraussetzungen

Das Projekt ist mit [ConTeXt LMTX](https://wiki.contextgarden.net/Installation) `>= 2023.04.01 09:52`
umgesetzt und getestet. Die Verwendeten Schriftarten sind:

- STIX Two Text
- STIX Two Math
- Inter
- JetBrains Mono

Die Schriftarten müssen auf dem System installiert sein und die
Umgebungsvariable `OSFONTDIR`, die auf das Schriftartenverzeichnis verweist
gesetzt sein. Für Linux sollte `export
OSFONTDIR=$HOME/.local/share/fonts:/usr/share/fonts` zur `.bashrc` hinzugefügt
werden. Die STIX Schriftarten sind bereits in der TeX Distribution enthalten.

```bash
mtxrun --generate
mtxrun --script font --reload
```

## Kompilieren

Ein PDF kann man mit dem folgenden Befehl erzeugen:

```bash
$ context prd_project_documentation.tex
```
