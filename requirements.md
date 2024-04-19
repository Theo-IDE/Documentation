
# Funktionale Anforderungen

## Allgemein
- Portables Buildsystem mit CMake:
	- Linux (X11 / Wayland) (gcc, clang)
	- Windows (msvc)
	- MacOS (clang)
	- Android (Android NDK, Cross-Build)
	- iOS, iPadOS (von macOS aus)
	- WASM (emscripten)

## Backend
- Compiler für Konzeptsprachen:
	- LOOP
	- WHILE
	- GOTO
- Erweiterte Syntax
	- optionales Semikolon
	- Zuweisung von Konstanten
	- Funktionen (Call Syntax, Infix Syntax)
	- include 
- Virtuelle Machine (Stack oder Register)
	- mit step-Funktion zum Debuggen
	- debug-infos (Sourcemaps)

## Frontend
- mit Qt
- Texteditor
	- mehrere Dateien mit Tabs
- grafischen Debugger
	- tabellarische Darstellung von Variablen (zum jeweiligen Zeitpunkt)

# Nicht-Funktionale Anforderungen
- Student im dritten Semester muss in der Lage sein, das Projekt zu installieren
	-> Binaries bereitstellen für alle Plattformen
