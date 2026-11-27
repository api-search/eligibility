---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only use the Website for Your personal use
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for clinical use
    text: ARE NOT INTENDED, VALIDATED, OR APPROVED FOR ANY CLINICAL USE.
  - summary: No dangerous, malicious or unethical activities
    text: to perform any dangerous, malicious or unethical activities; or for any unlawful purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Profluent
provenance_date: '2026-11-10'
provider_name: Profluent
provider_slug: profluent-bio
slug: profluent-bio-eligibility
source_date: '2026-11-10'
source_filename: profluent-bio-eligibility.yml
source_heading: Eligibility
source_page: https://www.profluent.bio/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Profluent\naid: profluent-bio\nurl: https://www.profluent.bio/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may only use the Website for Your personal use\nrestricted_uses:\n- summary: Not for clinical use\n  text: ARE NOT INTENDED, VALIDATED, OR APPROVED FOR ANY CLINICAL USE.\n- summary: No dangerous, malicious or unethical activities\n  text: to perform any dangerous, malicious or unethical activities; or for any unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/profluent-bio/eligibility/profluent-bio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Profluent's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Protein Design
- Protein Language Models
- Foundation Models
- Generative Biology
- Gene Editing
- CRISPR
- OpenCRISPR
- ProGen
- ProseLM
- Bioinformatics
- Therapeutics
- Agriculture
- Industrial Enzymes
- Open Source Models
---
