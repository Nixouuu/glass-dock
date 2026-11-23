# 🛡️ Sécurité · Security

[Français](#français) · [English](#english)

## Français

### Analyses VirusTotal

Chaque version de l'installeur est analysée par environ 70 antivirus sur VirusTotal.

| Version | Résultat | Empreinte SHA-256 de `Glass-Dock-Setup.exe` |
|---|---|---|
| 1.2.6 | ✅ [0 détection](https://www.virustotal.com/gui/file/8741c18d6b25a98962c7cb2fc69226c4fdb256936887de0876fc5889f2e80338/detection) | `8741C18D6B25A98962C7CB2FC69226C4FDB256936887DE0876FC5889F2E80338` |
| 1.2.5 | ✅ [0 détection](https://www.virustotal.com/gui/file/686324eb4a8c87490cb3ca7204a77d77431bb1a5f80f357e0f8ead7b2f44ae9d/detection) | `686324EB4A8C87490CB3CA7204A77D77431BB1A5F80F357E0F8EAD7B2F44AE9D` |
| 1.2.4 | ✅ [0 détection](https://www.virustotal.com/gui/file/490328f6a1a14d0d5b93b05a6ee3ff0a9659e643e11398d15d86ab40a5a070fe/detection) | `490328F6A1A14D0D5B93B05A6EE3FF0A9659E643E11398D15D86AB40A5A070FE` |
| 1.2.3 | ✅ [0 détection](https://www.virustotal.com/gui/file/9a733be65dcb3c28bd1ed9f6bb983a7a553a202c7146e81124431f602b118d54/detection) | `9A733BE65DCB3C28BD1ED9F6BB983A7A553A202C7146E81124431F602B118D54` |

**Vérifier ton fichier** : dans PowerShell, tape `Get-FileHash .\Glass-Dock-Setup.exe`. Le résultat doit être exactement l'empreinte ci-dessus. Télécharge Glass Dock seulement depuis la page [Releases](https://github.com/Nixouuu/glass-dock/releases) de ce dépôt.

### Ce que Glass Dock fait

- Il remplace la barre des tâches : il la cache et affiche le dock à la place.
- Il écoute la touche Windows **seule**, pour ouvrir le dock. Il ne lit ni n'enregistre aucune autre touche.
- Il lit, **sur ton PC seulement** : la liste de tes apps et fenêtres ouvertes, les infos de ton téléphone données par Phone Link, et le son de SteelSeries Sonar si tu l'as.
- **Compteur anonyme** : au plus une fois par jour, il envoie un identifiant tiré au hasard (jeté aussitôt), le numéro de version, la langue et la version de Windows, pour savoir combien de personnes utilisent le dock. Aucune donnée personnelle : pas de compte, pas de nom, pas d'adresse IP conservée, pas de liste d'apps, pas de fichiers, aucune frappe clavier.
- Il se lance avec Windows. Tu peux l'enlever dans les réglages du dock.

### Ce que Glass Dock ne fait pas

- **Rien de personnel n'est envoyé** : pas de nom, pas de fichiers, pas de ce que tu tapes, pas de pub. Ses seules connexions Internet sont le compteur anonyme ci-dessus et la vérification des mises à jour sur cette page GitHub.
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
| 1.2.6 | ✅ [0 detections](https://www.virustotal.com/gui/file/8741c18d6b25a98962c7cb2fc69226c4fdb256936887de0876fc5889f2e80338/detection) | `8741C18D6B25A98962C7CB2FC69226C4FDB256936887DE0876FC5889F2E80338` |
| 1.2.5 | ✅ [0 detections](https://www.virustotal.com/gui/file/686324eb4a8c87490cb3ca7204a77d77431bb1a5f80f357e0f8ead7b2f44ae9d/detection) | `686324EB4A8C87490CB3CA7204A77D77431BB1A5F80F357E0F8EAD7B2F44AE9D` |
| 1.2.4 | ✅ [0 detections](https://www.virustotal.com/gui/file/490328f6a1a14d0d5b93b05a6ee3ff0a9659e643e11398d15d86ab40a5a070fe/detection) | `490328F6A1A14D0D5B93B05A6EE3FF0A9659E643E11398D15D86AB40A5A070FE` |
| 1.2.3 | ✅ [0 detections](https://www.virustotal.com/gui/file/9a733be65dcb3c28bd1ed9f6bb983a7a553a202c7146e81124431f602b118d54/detection) | `9A733BE65DCB3C28BD1ED9F6BB983A7A553A202C7146E81124431F602B118D54` |

**Check your file**: in PowerShell, run `Get-FileHash .\Glass-Dock-Setup.exe`. The result must match the hash above exactly. Only download Glass Dock from this repository's [Releases](https://github.com/Nixouuu/glass-dock/releases) page.

### What Glass Dock does

- It replaces the taskbar: it hides it and shows the dock instead.
- It listens for the Windows key **on its own**, to open the dock. It doesn't read or record any other key.
- It reads, **on your PC only**: your apps and open windows, your phone info provided by Phone Link, and SteelSeries Sonar audio if you have it.
- **Anonymous counter**: at most once a day, it sends a random throwaway ID, the version number, the language and the Windows version, to know how many people use the dock. No personal data: no account, no name, no stored IP address, no app list, no files, no keystrokes.
- It starts with Windows. You can turn this off in the dock's settings.

### What Glass Dock doesn't do

- **No personal data sent**: no name, no files, no keystrokes, no ads. Its only internet connections are the anonymous counter above and the update check on this GitHub page.
- **No administrator rights needed**: it installs for your user only.
- It doesn't touch any personal files.

### Uninstall

Settings → Apps → Glass Dock → Uninstall. Your taskbar comes back as before, the startup entry is removed and the settings are deleted.

### Why does Windows show a warning?

Glass Dock doesn't have a code-signing certificate yet, since they're expensive. Windows SmartScreen shows "Windows protected your PC" for new apps with few downloads. Click **More info**, then **Run anyway**.

### Report a problem

Open an [issue](https://github.com/Nixouuu/glass-dock/issues).
