# ✈️ Airline Tycoon Deluxe – Čeština 2.0

Kompletní česká lokalizace pro **Airline Tycoon Deluxe**.

Překládá menu, rozhraní, dialogy, dopisy, obchody, nápovědu, kampaně, systémové hlášky a další texty hry. Součástí jsou české fonty s plnou diakritikou a nový grafický instalátor s podporou původní hry i současných komunitních buildů.

---

## 📥 Stažení

Nejnovější verzi najdete v sekci:

**[Releases](https://github.com/LusciousFoxxx/Airline-Tycoon-Deluxe-Cestina/releases/latest)**

Pro běžnou instalaci použijte instalační `.exe`.

---

## ✅ Podporované verze

Čeština 2.0 podporuje:

| Varianta | Podpora |
|---|---|
| Původní / Vanilla Airline Tycoon Deluxe | ✅ |
| Steam verze | ✅ |
| WizzardMaker 1.8.1 Preview | ✅ |
| mertenpopp 1.9.1 | ✅ |

Instalátor automaticky zjistí verzi hry, použitý build i stav české lokalizace.

---

# 🧩 Nový instalátor

Čeština 2.0 používá nový grafický instalátor vytvořený speciálně pro tento projekt.

Umí automaticky:

- najít instalaci Airline Tycoon Deluxe,
- detekovat Steam verzi,
- zjistit použitý komunitní build,
- zjistit stav češtiny,
- nainstalovat Češtinu 2.0,
- aktualizovat Češtinu 1.1,
- opravit poškozenou instalaci,
- aktualizovat podporovaný komunitní build,
- vytvořit bezpečnou zálohu,
- obnovit původní soubory,
- odinstalovat změny provedené instalátorem,
- stáhnout a ověřit komunitní build,
- spustit hru správným způsobem podle typu instalace.

Komunitní buildy **nejsou přibalené v instalátoru**.

Pokud si některý z nich vyberete, instalátor stáhne originální release přímo z GitHubu jeho autora a před instalací ověří jeho integritu.

---

# 🛠️ WizzardMaker 1.8.1 Preview

### Doporučená varianta

Pro většinu hráčů doporučuji **WizzardMaker 1.8.1 Preview**.

Tento komunitní build se zaměřuje především na opravy a lepší kompatibilitu původní hry s moderními počítači.

Přináší například:

- SDL2 renderovací backend,
- opravy blikání grafiky,
- opravy input lagu,
- opravy některých pádů při Alt+Tab,
- windowed režim,
- borderless fullscreen,
- opravy některých pádů hry,
- opravy AI,
- opravy aukcí měst a gatů,
- opravy některých misí,
- další opravy původních herních mechanismů.

Projekt:

https://github.com/WizzardMaker/AirlineTycoon

---

# 🚀 mertenpopp 1.9.1

Pro hráče, kteří chtějí více změn a rozšíření původní hry, je podporován také **mertenpopp 1.9.1**.

Tato větev dále rozšiřuje Airline Tycoon Deluxe například v oblastech:

- AI,
- statistik,
- informačních obrazovek,
- paliva,
- zaměstnanců,
- letadel,
- rychlosti hry,
- klávesového ovládání,
- dalších herních mechanik.

Čeština 2.0 obsahuje vlastní lokalizační variantu určenou přímo pro tento build.

Projekt:

https://github.com/mertenpopp/AirlineTycoon

---

# 🔄 Přechod z Češtiny 1.1

Pokud instalátor najde původní **Češtinu 1.1**, nabídne její aktualizaci na 2.0.

Původní instalátor 1.1 nepoužíval dostatečně spolehlivý systém odinstalace a záloh. Čeština 2.0 proto obsahuje ověřené původní soubory potřebné pro bezpečný návrat lokalizovaných částí hry do původního stavu.

Není tedy nutné nejprve ručně odinstalovávat verzi 1.1.

---

# 💾 Záloha a rollback

Instalátor si vede vlastní záznam o souborech, kterých se dotkl.

Rozlišuje:

- původní soubory,
- přepsané soubory,
- nově přidané soubory,
- build nainstalovaný už před Češtinou 2.0,
- build nainstalovaný samotným instalátorem.

Odinstalace se proto snaží vrátit hru do stavu odpovídajícího situaci před instalací Češtiny 2.0.

---

# 🩺 Oprava instalace

Pokud jsou některé soubory češtiny nebo podporovaného komunitního buildu poškozené, instalátor nabídne možnost:

**Opravit instalaci**

U community buildu se znovu stáhne originální release, ověří se jeho integrita a následně se znovu aplikuje správná varianta Češtiny 2.0.

---

# 🎮 Spuštění hry

Instalátor rozlišuje Steam a samostatnou instalaci.

- **Steam verze** se spouští přes Steam.
- **Ostatní instalace** se spouštějí přímo přes `AT.exe`.

---

# 💾 Savegame

Savegame mezi jednotlivými buildy hry nemusí být vždy vzájemně kompatibilní.

Při změně buildu proto doporučuji ponechat si vlastní kopii důležitých uložených pozic.

---

# ℹ️ mertenpopp a `JAZYK : EN`

U mertenpopp buildu můžete v menu vidět:

`JAZYK : EN`

Hodnota `EN` označuje jazykovou konfiguraci enginu komunitního buildu.

Nejedná se o indikaci toho, zda je česká lokalizace aktivní.

---

# ⚠️ Známé drobnosti

Některé texty původní hry nejsou uložené jako běžné textové řetězce, ale přímo jako grafika.

V této verzi proto mohou zůstat anglicky například:

- `Continue briefing`
- `Cancel briefing`
- zelený `WAIT`

Jejich lokalizace vyžaduje samostatnou úpravu původních grafických assetů.

---

# 📋 Technické informace

Instalátor interně používá SHA-256 kontrolu podporovaných buildů a lokalizačních souborů.

Technické informace se běžnému uživateli nezobrazují, ale jsou zapisovány do instalačního logu.

Log najdete v:

```text
ATD_CZ_Backup\ATD_CZ_Installer.log
