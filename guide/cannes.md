# 🧛 Cannes à Pêche

{% hint style="info" %}
Système de durabilité : Chaque canne a une durabilité maximale personnalisée. La canne se casse une fois épuisée. Les cannes de compétition ne peuvent pas utiliser d'appâts.
{% endhint %}

## Compétition

| Canne | Prix | Durabilité | Effets | Usage |
| --- | --- | --- | --- | --- |
| Canne de Compétition | 200 💲 | 128 | Aucun bonus/malus | Tournois officiels uniquement |

{% hint style="warning" %}
Restrictions Compétition : Pêche uniquement les poissons de tournoi. Aucun déchet, aucun loot jeu de base. Les appâts sont interdits .
{% endhint %}


## Classique

| Canne | Prix | Durabilité | Effets |
| --- | --- | --- | --- |
| Canne en Cuivre | 1 500 💲 | 256 | ★ Argent +2 |
| Canne en Fer | 3 000 💲 | 384 | Attente ×0.95 ★ Argent +4 |
| Canne en Or | 10 000 💲 | 512 | ★ Argent +4 ★★ Or +2 |
| Canne en Diamant | 50 000 💲 | 768 | Attente ×0.85 Difficulté +5 ★ Argent +5 ★★ Or +3 |
| Canne en Netherite | 100 000 💲 | 1 024 | Attente ×0.80 Difficulté +10 ★ Argent +8 ★★ Or +4 |

## Spécialisée — Optimisée par biome

| Canne | Prix | Durabilité | Effets de base | Bonus biome ciblé | Biome optimal |
| --- | --- | --- | --- | --- | --- |
| Canne en Prismarine | 100 000 💲 | 1 024 | Attente ×0.95 ★ Argent +3 | Océan +12 Chaud +6 ★ Argent +8 | Océan (tous types) |
| Canne Sculk | 250 000 💲 | 1 280 | +6s temps jeu | Grotte +20 +10s bonus ★ Argent +6 | Grotte Y<0 / Océan profond |
| Canne Visqueuse | 100 000 💲 | 1 024 | Taille ×1.2 Attente ×0.97 | Marais +20 Taille ×1.6 ★ Argent +5 | Marais |
| Canne en Améthyste | 500 000 💲 | 1 600 | ★ Argent +5 | Océan +20 ★ Argent +15 | Océan froid / Gelé |
| Canne en Corail | 500 000 💲 | 1 600 | Attente ×0.95 ★ Argent +2 | Chaud +20 Attente ×0.75 ★★ Or +2 | Océan chaud / tiède |

## Dimensionnelle — Dimensions hostiles

| Canne | Prix | Durabilité | Effets | Environnement |
| --- | --- | --- | --- | --- |
| Canne du Nether | 500 000 💲 | 1 600 | Pêche en lave ★ Argent +6 | Lave (Nether) |
| Canne de Magma | 750 000 💲 | 2 048 | Pêche en lave ★ Argent +8 ★★ Or +4 | Lave (Nether) |
| Canne de l'End | 1 000 000 💲 | 2 560 | Pêche dans le vide Déchets uniquement hors vide ★★ Or +7 (End uniquement) | Vide (End) |
| Canne en Fusion | 3 000 000 💲 | 4 096 | Pêche en lave Pêche dans le vide Attente ×0.80 ★ Argent +10 ★★ Or +6 | Eau · Lave · Vide |
| Canne en Gemme | 10 000 000 💲 | 6 400 | Pêche dans le vide Trésors +500 Coeur mer +200 Aucun poisson | Eau · Vide (End) |

{% hint style="warning" %}
Canne en Gemme : Ne capture aucun poisson . Exclusivement trésors jeu de base (étiquette, selle, nautile, arc enchanté...) + Coeur de la mer. Idéale pour les trésors en océan et dans l'End.
{% endhint %}


{% hint style="warning" %}
Canne de l'End : Dans l'eau normale, elle ne capture que des déchets (bâton, algues, vêtements...) — tous les poissons sont supprimés. Les poissons du vide (Crevette Biscornue, Poisson Bulle Cramoisi) et le bonus ★★ Or +7 ne s'activent qu'en pêchant dans le vide de l'End .
{% endhint %}


## Référence développement

{% hint style="warning" %}
🔧 Référence développement : Les effets group-mod modifient les poids de tirage par groupe (silver_star, golden_star, ocean, etc.). wait-time-multiplier < 1 = attente plus courte. lava-fishing / void-fishing = capacité exclusive. La difficulté affecte le mini-jeu de pêche (plus difficile = fail plus fréquent mais poissons étoile plus gros si réussi).
{% endhint %}