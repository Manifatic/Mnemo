# Export du site Hark — QCM de Génétique

Cette archive contient le code côté client récupéré depuis la page publique Hark le 20 octobre 2026.

- `index.html` : version autonome publiée du site, avec le CSS, le JavaScript et les données intégrés.
- `qdata.json` : questions et réponses des QCM extraites du HTML.
- `cdata.json` : cours extraits du HTML.

## Utilisation

Ouvrez `index.html` dans un navigateur. Pour éviter d’éventuelles restrictions liées aux fichiers locaux, vous pouvez aussi lancer un serveur local dans ce dossier :

```bash
python3 -m http.server 8000
```

Puis ouvrez <http://localhost:8000>.

## Limite

Il s’agit du code statique rendu publiquement par Hark. Le projet original dans l’éditeur Hark, son historique, ses réglages et ses fichiers côté serveur ne sont pas inclus s’ils ne sont pas exposés par le lien public.
