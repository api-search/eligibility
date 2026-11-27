---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Not tailored for HIPAA/FISMA-regulated use
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
  - summary: No use violating GLBA
    text: You may not use the Site in a way that would violate the Gramm- Leach-Bliley Act (GLBA).
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
name: Omnea
provenance_date: '2026-11-10'
provider_name: Omnea
provider_slug: omnea
slug: omnea-eligibility
source_date: '2026-11-10'
source_filename: omnea-eligibility.yml
source_heading: Eligibility
source_page: https://www.omnea.co/documents/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Omnea\naid: omnea\nurl: https://www.omnea.co/documents/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Not tailored for HIPAA/FISMA-regulated use\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability\
  \ and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\n- summary: No use violating GLBA\n  text: You may not use the Site in a way that would violate the Gramm- Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/omnea/eligibility/omnea-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Omnea's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Procurement
- Source-to-Pay
- Supplier Management
- Spend Management
- Agents
- MCP
---
