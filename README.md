# Code promo Columbia, recuperation automatique depuis shopilo.fr

Module Python pour la recuperation automatique de **codes promo Columbia** depuis [shopilo.fr](https://shopilo.fr/reductions/columbiasportswear.fr). Renvoie les **coupons Columbia** actifs au format JSON, pret a etre integre dans un bot Telegram, une extension de navigateur ou tout autre outil.

**Page live :** [shopilo-fr.github.io/code-promo-columbiasportswear](https://shopilo-fr.github.io/code-promo-columbiasportswear/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Installation

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-fr/code-promo-columbiasportswear
cd code-promo-columbiasportswear
python fetch.py
```

## Exemple de sortie

```json
[
  {
    "store": "Columbia",
    "code": "SHOPILO20",
    "discount": "20%",
    "description": "20% de reduction sur les vetements de plein air",
    "expires": "2026-10-13",
    "source": "https://shopilo.fr/reductions/columbiasportswear.fr"
  }
]
```

## Coupons Columbia disponibles

| Reduction | Description | Source |
|----------|-----------|-------|
| 20% | 20% de reduction sur les vetements de plein air | [shopilo.fr](https://shopilo.fr/reductions/columbiasportswear.fr) |

Codes actifs : **[shopilo.fr/reductions/columbiasportswear.fr](https://shopilo.fr/reductions/columbiasportswear.fr)**

## Questions frequentes

### Comment utiliser un code promo Columbia ?
Copiez le code depuis le tableau ci-dessus ou depuis [shopilo.fr](https://shopilo.fr/reductions/columbiasportswear.fr), ajoutez les produits a votre panier sur Columbia et saisissez le code au moment du paiement dans le champ prevu.

### Combien de temps durent les coupons Columbia ?
Chaque coupon a une date d'expiration indiquee dans la colonne "Expiration". Le script fetch.py renvoie uniquement les coupons actifs au moment de l'execution.

### Ou trouver les bons de reduction Columbia les plus recents ?
La page [shopilo.fr/reductions/columbiasportswear.fr](https://shopilo.fr/reductions/columbiasportswear.fr) est mise a jour quotidiennement avec les codes promo Columbia, bons de reduction Columbia et coupons promotionnels Columbia les plus recents.

### Le code ne fonctionne pas. Que faire ?
Verifiez la date d'expiration et les conditions (montant minimum de commande, produits eligibles). Certains codes sont valables uniquement sur l'application mobile ou pour la premiere commande.

## A propos de Columbia

Columbia est l'une des boutiques en ligne les plus populaires. Sur [shopilo.fr](https://shopilo.fr/reductions/columbiasportswear.fr), retrouvez les meilleurs codes promo Columbia, coupons Columbia verifies et bons de reduction Columbia actifs, mis a jour chaque jour.

## Installation npm

```bash
npm install code-promo-columbiasportswear
```

```javascript
const { fetchCoupons } = require('code-promo-columbiasportswear');
fetchCoupons().then(data => console.log(data));
```

## Licence

MIT, donnees extraites de [shopilo.fr](https://shopilo.fr)
