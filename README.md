# MediaTagger – HW1 (CS 690F)
Synthetic image+caption dataset (10 classes × 10 images), baseline classifier, and membership inference attacks.

## Quickstart
1) Open in Codespaces  
2) Create venv: `python -m venv .venv && source .venv/bin/activate`  
3) `pip install -r requirements.txt`

## Repo layout
- `data/` — images + `metadata.csv` (filename,class,split,caption,is_member,source,gen_model,prompt,seed,notes)
- `notebooks/` — sanity checks + attack demo plots
- `src/` — data prep, training, MIA attacks
- `prompts/` — class taxonomy + generation prompts
- `slides/` — deck assets for presentation
