# Data Card (Synthetic)
- **Use case:** personal media tagging (privacy-relevant)
- **Classes (10):** pets, food, friends, travel, dancing, outdoors, sports_fitness, work_study, celebrations, landmarks
- **Label policy:** see `prompts/classes.yaml` include/exclude rules
- **Generation:** diffusion prompts (+ seeds) recorded in `metadata.csv`
- **Splits/MIA:** `is_member=1` for train (members), `0` for non-members (val/test)
- **Quality checks:** manual verification; no PII, no watermarks/logos
