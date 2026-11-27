# MnPlMj_info_indus_tutorial

Projet du cours [Informatique Industrielle avec ROS2](https://yguel.github.io/informatique_industrielle_avec_ROS2/).

📖 **Documentation en ligne : <https://nathan97232.github.io/info_indus_tutorial/>**

La documentation est reconstruite et publiée automatiquement par GitHub Actions
(`.github/workflows/documentation.yml`) à chaque push sur la branche `rolling`.

## Équipe

- Nathan MANUEL
- Laura PAEZ
- Johan MARING

## Construire la documentation en local

```bash
cd doc/sphinx
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
make html
firefox build/html/index.html
```

## Organisation des branches

| Branche     | Rôle                                                        |
|-------------|-------------------------------------------------------------|
| `rolling`   | branche de référence, on n'y commite jamais directement     |
| `<nom>/dev` | branche de travail personnelle, fusionnée par pull request |
| `gh-pages`  | site HTML généré par le workflow, ne pas modifier à la main |
