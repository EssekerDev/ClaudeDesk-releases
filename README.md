# ClaudeDesk-releases
Binary releases (macOS app and firmware) for ClaudeDesk. No source code.

<!-- claudedesk-app-install:start -->
## Installer l’app ClaudeDesk sur le Mac

1. Télécharge `ClaudeDesk-X.Y.Z.dmg` dans la dernière release
   [`app-v…`](../../releases) (Mac Apple Silicon, macOS 14 ou plus récent).
2. Ouvre le `.dmg` et glisse **ClaudeDesk** dans **Applications**.
3. L’app n’est pas signée par Apple : au premier lancement, ouvre le dossier
   **Applications**, fais un **clic droit** (ou Contrôle-clic) sur ClaudeDesk,
   puis choisis **Ouvrir**, et confirme **Ouvrir** dans la fenêtre de macOS.
   Les lancements suivants se font normalement.
4. Sur macOS 15 ou plus récent, si macOS dit encore que l’app ne peut pas être
   ouverte : **Réglages Système** → **Confidentialité et sécurité**, en bas de
   la page, bouton **Ouvrir quand même** à côté de « ClaudeDesk », puis
   confirme.

Vérifier le fichier (facultatif) : `shasum -a 256 ClaudeDesk-X.Y.Z.dmg` doit
donner la valeur du fichier `.sha256` publié à côté.

### Install the ClaudeDesk app (English)

Download the `.dmg` from the latest `app-v…` release, drag ClaudeDesk to
Applications. The app is not notarized: the first time, **right-click** it in
Applications and choose **Open**, then **Open** again. On macOS 15 and later, if
it is still blocked: System Settings → Privacy & Security → **Open Anyway**.
<!-- claudedesk-app-install:end -->
