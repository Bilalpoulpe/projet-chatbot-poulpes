# Data

## Fichiers produits par le pipeline

| Fichier | Lab | Description |
|---------|-----|-------------|
| `crawler_output.jsonl` | Lab 1 | Pages web crawlées (38 pages, 55k mots) |
| `extracted_knowledge.csv` | Lab 1 | Entités extraites par NER (2 646 entités) |
| `extracted_knowledge_relations.csv` | Lab 1 | Relations sujet-verbe-objet (503 relations) |
| `kb_initial.ttl` | Lab 2 | KB privée initiale (RDF Turtle) |
| `kb_expanded.ttl` | Lab 2 | KB expansée via Wikidata (Turtle) |
| `kb_expanded.nt` | Lab 2 | KB expansée (N-Triples) |
| `alignment_table.csv` | Lab 2 | Alignement entités privées ↔ Wikidata |
| `predicate_alignment.csv` | Lab 2 | Alignement prédicats privés ↔ Wikidata |
| `train.txt` / `valid.txt` / `test.txt` | Lab 3 | Split 80/10/10 pour KGE |

## Taille des fichiers

Les fichiers KB (`*.ttl`, `*.nt`) et les modèles KGE sont trop volumineux pour Git.
Ils sont générés automatiquement en exécutant les notebooks dans l'ordre.

## Samples

Le dossier `samples/` contient des échantillons réduits pour permettre la vérification
sans relancer tout le pipeline.
