# Devoir 01 - Calcul Formel
## Arithmétique Multiprécision en SageMath

**Auteur :** Diaw Papa Amadou  
**Cours :** Calcul Formel - M1 Cryptographie et Algèbre Appliquée  
**Année :** 2025-2026

## Description

Implémentation complète des algorithmes d'arithmétique 
multiprécision en SageMath dans un notebook JupyterLab.

## Algorithmes implémentés

| Fonction | Description |
|----------|-------------|
| `myentier` | Conversion en entier ZZ |
| `myentier_entmp` | Entier → multiprécision |
| `myentmpcanonique` | Forme canonique |
| `mylongueur` | Longueur d'un entier |
| `myentmp_entier` | Multiprécision → entier |
| `myentmpsmemelongueur` | Même longueur |
| `myADD` | Addition processeur |
| `myalgo321` | Addition multiprécision |
| `myMUL` | Multiplication processeur |
| `myalgo331` | Multiplication chiffre × multiprécision |
| `myalgo333` | Multiplication naïve |
| `myalgo336` | Multiplication coûteuse |
| `myalgo338` | Algorithme de Karatsuba |

## Erreur trouvée et corrigée

**Fonction :** `myentmpcanonique`  
**Problème :** Quand tous les chiffres sont 0, la fonction  
retournait `[0,0,0,0]` au lieu de `[0]`  
**Correction :** Ajout de `if go: return [0]` après la boucle

## Lancer le notebook

```bash
cd devoir01-calcul-formel
jupyter lab
```

Ouvrir le fichier `Diaw_PapaAmadou_devoir01.ipynb`