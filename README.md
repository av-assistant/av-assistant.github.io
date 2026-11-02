# AV Assistant — pagina di lancio

Pagina statica pubblicata su <https://av-assistant.github.io/>: e' il link da condividere per installare AV Assistant sulla schermata Home del telefono.

- Ha manifest e icone AV direttamente nell'HTML, quindi l'icona installata e' sempre quella AV (anche se l'app Streamlit e' ibernata).
- Aperta dall'icona sulla Home (`display-mode: standalone` o `?pwa=1`) reindirizza subito all'app: <https://av-assistant-jahevfahcjvxnt7sz5nnwk.streamlit.app/>.
- Aperta nel browser mostra il bottone "Apri" e le istruzioni di installazione (IT/EN).

L'app vera e' nel repo `francesco-brisacane/av-assistant`. Le icone sono generate li' da `assets/gen_pwa_icons.py` (in `static/`): se cambiano, ricopiale qui.
