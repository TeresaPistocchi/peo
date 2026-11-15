# Estensione della Prompt Engineering Ontology (PEO)

## Punto di partenza

Il progetto parte dalla **versione aggiornata di PEO del 2026**, descritta nell'articolo *PEO: An Ontology to Scaffold Prompt Engineering for Foundation Models* (Barile et al., WOP 2026). L'ontologia rappresenta in modo formale foundation model, task, chat e tecniche di prompting.

## Estensione realizzata

L'obiettivo del lavoro è ampliare PEO modellando quattro tecniche di Prompt Engineering e i passaggi che ne descrivono il funzionamento:

- **Self-Ask:** scomposizione di una domanda in quesiti di approfondimento e risposte intermedie.
- **Self-Refine:** miglioramento iterativo di una risposta attraverso feedback e successive revisioni.
- **Self-Verification:** valutazione di risposte candidate tramite verifica a ritroso, con le modalità *True/False Item Verification* e *Condition Mask Verification*.
- **Rephrase and Respond (RaR):** riformulazione della domanda originale prima della generazione della risposta.

## Realizzazione

L'estensione è stata sviluppata in **Protégé**, utilizzando **OWL 2**. Sono state introdotte classi, proprietà, relazioni e restrizioni logiche, collegate ai concetti già presenti in PEO. Sono inoltre incluse istanze di esempio che rappresentano i passaggi delle tecniche e consentono di interrogare il modello tramite **SPARQL**.


