<p align="center">
Français|<a href="README.md">Anglais</a>
</p>

# Chatbot-Loi sur le Mariage en France

Créez un chatbot français pour répondre aux questions basées sur un document en utilisant Google Colab. Dans notre cas, nous utilisons des données extraites du site Web de la législation française : [Site Web de la Législation Française](https://www.legifrance.gouv.fr/codes/section_lc/LEGITEXT000006070721/LEGISCTA000006117710/#LEGISCTA000006117710)

Le jeu de données extrait du site Web peut être trouvé dans "data.csv".

Deux modèles (basés sur le modèle Camembert) sont utilisés pour créer des réponses :

1. **Modèle de Récupération de Passages Denses** : Ce modèle est utilisé pour récupérer efficacement des passages pertinents du document.

2. **Modèle de Réponse aux Questions** : Ce modèle est utilisé pour répondre aux questions en se basant sur les passages récupérés.

Modèle utilisé pour la réponse aux questions : [Camembert Base SQuAD-FR](https://huggingface.co/etalab-ia/camembert-base-squadFR-fquad-piaf)
