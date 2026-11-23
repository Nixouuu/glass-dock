# 🛡️ Sécurité · Security

[Français](#français) · [English](#english)

## Français

### Analyses VirusTotal

Chaque version de l'installeur est analysée par environ 70 antivirus sur VirusTotal.

| Version | Résultat | Empreinte SHA-256 de `Glass-Dock-Setup.exe` |
|---|---|---|
| 1.2.3 | ✅ [0 détection](https://www.virustotal.com/gui/file/9a733be65dcb3c28bd1ed9f6bb983a7a553a202c7146e81124431f602b118d54/detection) | `9A733BE65DCB3C28BD1ED9F6BB983A7A553A202C7146E81124431F602B118D54` |

**Vérifier ton fichier** : dans PowerShell, tape `Get-FileHash .\Glass-Dock-Setup.exe`. Le résultat doit être exactement l'empreinte ci-dessus. Télécharge Glass Dock seulement depuis la page [Releases](https://github.com/Nixouuu/glass-dock/releases) de ce dépôt.

### Ce que Glass Dock fait

- Il remplace la barre des tâches : il la cache et affiche le dock à la place.
- Il écoute la touche Windows **seule**, pour ouvrir le dock. Il ne lit ni n'enregistre aucune autre touche.
- Il lit, **sur ton PC seulement** : la liste de tes apps et fenêtres ouvertes, les infos de ton téléphone données par Phone Link, et le son de SteelSeries Sonar si tu l'as.
- Il se lance avec Windows. Tu peux l'enlever dans les réglages du dock.

### Ce que Glass Dock ne fait pas

- **Aucune donnée envoyée** : pas de compte, pas de statistiques, pas de pub. Sa seule connexion Internet sert à vérifier les mises à jour sur cette page GitHub.
- **Pas besoin d'administrateur** : il s'installe seulement pour ton utilisateur.
- Il ne touche à aucun fichier personnel.

### Désinstaller

Paramètres → Applications → Glass Dock → Désinstaller. Ta barre des tâches revient comme avant, le démarrage automatique est retiré et les réglages sont effacés.

### Pourquoi Windows affiche un avertissement ?

Glass Dock n'a pas encore de certificat de signature, qui coûte cher. Windows SmartScreen affiche donc « Windows a protégé votre ordinateur » pour les nouvelles apps peu téléchargées. Clique sur **Informations complémentaires**, puis **Exécuter quand même**.

### Signaler un problème

Ouvre une [issue](https://github.com/Nixouuu/glass-dock/issues).

---

## English

### VirusTotal scans

Every installer release is scanned by about 70 antivirus engines on VirusTotal.

| Version | Result | SHA-256 of `Glass-Dock-Setup.exe` |
|---|---|---|
| 1.2.3 | ✅ [0 detections](https://www.virustotal.com/gui/file/9a733be65dcb3c28bd1ed9f6bb983a7a553a202c7146e81124431f602b118d54/detection) | `9A733BE65DCB3C28BD1ED9F6BB983A7A553A202C7146E81124431F602B118D54` |

**Check your file**: in PowerShell, run `Get-FileHash .\Glass-Dock-Setup.exe`. The result must match the hash above exactly. Only download Glass Dock from this repository's [Releases](https://github.com/Nixouuu/glass-dock/releases) page.

### What Glass Dock does

- It replaces the taskbar: it hides it and shows the dock instead.
- It listens for the Windows key **on its own**, to open the dock. It doesn't read or record any other key.
- It reads, **on your PC only**: your apps and open windows, your phone info provided by Phone Link, and SteelSeries Sonar audio if you have it.
- It starts with Windows. You can turn this off in the dock's settings.

### What Glass Dock doesn't do

- **No data sent**: no account, no analytics, no ads. Its only internet connection checks for updates on this GitHub page.
- **No administrator rights needed**: it installs for your user only.
- It doesn't touch any personal files.

### Uninstall

Settings → Apps → Glass Dock → Uninstall. Your taskbar comes back as before, the startup entry is removed and the settings are deleted.

### Why does Windows show a warning?

Glass Dock doesn't have a code-signing certificate yet, since they're expensive. Windows SmartScreen shows "Windows protected your PC" for new apps with few downloads. Click **More info**, then **Run anyway**.

### Report a problem

Open an [issue](https://github.com/Nixouuu/glass-dock/issues).
