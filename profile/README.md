# Stumble Studios

> Studio privato. Progetto personale di apprendimento — nessuna finalità commerciale.

Benvenuto nello spazio di lavoro di **Stumble Studios**. Qui vive **StumbleVerse**: un progetto
privato con cui, partendo dallo studio di un gioco multiplayer, ci si allena a costruire un
**ecosistema completo** attorno a un gioco — backend, autenticazione, tornei, bot e dashboard.

## La missione

Ricostruire, sulla base della versione **0.73**, un ecosistema **StumbleVerse SDK** completo:
non "clonare meglio" un gioco, ma usare un motore multiplayer come **infrastruttura** su cui
progettare sistemi che nel gioco base non esistono. L'obiettivo vero non è un prodotto: è
**imparare a programmare sistemi reali** — API, servizi, persistenza, anti-cheat, interfacce —
end-to-end.

Ogni pezzo che costruiamo (backend, motore tornei, bot, negozio, dashboard) viene **conservato e
documentato qui**, così che il lavoro sia riproducibile e portabile da una versione del gioco
all'altra.

## Cosa è, e cosa non è

**È:**
- Un progetto **privato** e **personale**, per studio ed esercizio.
- Un modo per imparare architetture reali costruendo cose che funzionano davvero.
- Basato su **valuta di gioco (gems)**, mai denaro reale.

**Non è:**
- Un prodotto commerciale, né qualcosa destinato alla distribuzione.
- Affiliato, sponsorizzato o approvato da terzi. StumbleVerse è un progetto indipendente di
  Stumble Studios.
- Un archivio di codice sorgente di terzi: qui si documentano e si costruiscono **i nostri
  sistemi**; il gioco base è oggetto di studio, non materiale da ripubblicare.

## Cosa trovi nell'organizzazione

| Ambito | Cosa contiene | Stato |
|---|---|---|
| **Documentazione** | `stumbleverse-docs` — architettura, tornei, backend, migrazione, idee | ✅ attivo |
| **Backend** | Cloudflare Worker + D1: auth Discord, tornei, negozio nomi, pannelli admin | ✅ vivo su `api.babsport.com` |
| **Sistema tornei** | Motore bracket, quorum anti-cheat, aggancio Photon/Quantum, UI | ✅ funzionante |
| **Bot Discord** | Annunci tornei, iscrizioni, notifiche, ruoli premio | 🧭 in progettazione |
| **Dashboard web** | Pagine torneo pubbliche, portale giocatore, statistiche | 🧭 in progettazione |

La documentazione tecnica di riferimento è in **[`stumbleverse-docs`](https://github.com/Stumble-Studios/stumbleverse-docs)**.

## Principi di lavoro

- **Privato per default.** I repo sono privati; niente viene esposto pubblicamente senza una ragione.
- **Niente segreti nel codice.** Client secret, JWT secret e token vivono solo in variabili
  d'ambiente / `wrangler secret`, mai committati.
- **Si documentano comportamenti e contratti**, non percorsi di file effimeri: così il lavoro
  sopravvive ai salti di versione del gioco.
- **Solo gems.** Nessuna monetizzazione in denaro reale su questo progetto.
- **Il confine dell'identità** (Stumble Studios / StumbleVerse) va sul **lavoro nostro** — backend,
  bundle, sistemi originali — non sopra codice di studio altrui.

---

*Stumble Studios — spazio di lavoro privato. Ultimo aggiornamento: luglio 2026.*
