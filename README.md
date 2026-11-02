# AV Assistant — pagina di lancio

Pagina statica pubblicata su <https://av-assistant.github.io/>: e' il link d'ingresso da condividere per AV Assistant.

- Mostra il bottone "Apri l'assistente" verso l'app (<https://av-assistant-jahevfahcjvxnt7sz5nnwk.streamlit.app/>), passando la lingua (`?lang=IT|EN`).
- L'installazione sul telefono si fa dall'app stessa: un banner "Installa AV Assistant" compare solo quando manifest e icone AV sono pronti (vedi `lib/pwa.py` nel repo dell'app). Cosi' l'app installata e' a schermo intero e con l'icona AV.
- La pagina non dichiara un manifest, cosi' Chrome non propone di installare lei al posto dell'app. `manifest.webmanifest` resta nel repo per chi l'aveva gia' installata dalla prima versione: aperta dall'icona sulla Home (`display-mode: standalone` o `?pwa=1`) reindirizza subito all'app.

L'app vera e' nel repo `francesco-brisacane/av-assistant`. Le icone sono generate li' da `assets/gen_pwa_icons.py` (in `static/`): se cambiano, ricopiale qui.
