---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  minimum_age:
    text: The Site is intended for users who are at least 16 years old. Persons under the age of 16 are not permitted to use or register for the Site.
    value: '16'
  restricted_uses:
  - summary: Not HIPAA/FISMA-regulated use
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: No GLBA-violating use
    text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
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
name: Savant
provenance_date: '2026-11-10'
provider_name: Savant
provider_slug: savant
slug: savant-eligibility
source_date: '2026-11-10'
source_filename: savant-eligibility.yml
source_heading: Eligibility
source_page: https://heysavant.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Savant\naid: savant\nurl: https://heysavant.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types: []\nrestricted_uses:\n- summary: Not HIPAA/FISMA-regulated use\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA),\
  \ etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: No GLBA-violating use\n  text: You may not use the Site in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Site is intended for users who are at least 16 years old. Persons under the age of 16 are not permitted\n    to use or register for the Site.\n"
source_yaml_url: https://artifacts.apis.io/savant/eligibility/savant-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Savant's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Knowledge Management
- Artificial Intelligence
- AI Agents
- Enterprise Knowledge
- Operational Memory
- Y Combinator
---
