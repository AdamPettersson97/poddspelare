# WinForms Project

Detta är ett WinForms-projekt utvecklat i Visual Studio 2022.  
Följande filer ingår i projektet:

## 🛠 Krav
- Visual Studio 2022
- .NET (version beroende på projektinställning)
- Windows-miljö

## 📁 Struktur
Projektet innehåller:
- `*.cs` — C#-kod
- `*.Designer.cs` — Autogenererad kod för formulärkomponenter
- `*.resx` — Resursfiler för forms
- `Properties/` — Projektkonfiguration

## 🔧 Git-inställningar
Projektet använder en anpassad `.gitignore` optimerad för WinForms.
Den ignorerar:
- bin/ & obj/
- VS-specifika filer
- temporära & autogenererade byggfiler
- användarspecifika inställningar (`*.user`)

## 🚀 Komma igång
1. Klona projektet:
   ```
   git clone <URL>
   ```
2. Öppna lösningen (`.sln`) i Visual Studio 2022.
3. Kör projektet med **F5**.

## 👥 Samarbete
När flera utvecklare jobbar i WinForms är det viktigt:
- Pusha *alltid* `.Designer.cs`-filer.
- Commita aldrig `.user` eller `.suo`.
- Uppdatera inte `bin/` eller `obj/`.

## 📄 Licens
Valfri licens kan läggas till här.
