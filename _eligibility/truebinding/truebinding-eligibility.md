---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By placing an order through the site, you represent and warrant that you are duly licensed, qualified, and authorized to obtain investigational drugs
    type: individual
  - text: Access to this Site and the ability to purchase products through the Site are strictly limited to licensed physicians, healthcare providers, hospitals, clinics, pharmacies, and other entities legally authorized to obtain and administer investigational drugs
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Investigational use only under FDA expanded access
    text: Products made available through this Site are investigational drugs that have not been approved by the U.S. Food and Drug Administration (FDA) for commercial sale.
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
name: TrueBinding
provenance_date: '2026-11-10'
provider_name: TrueBinding
provider_slug: truebinding
slug: truebinding-eligibility
source_date: '2026-11-10'
source_filename: truebinding-eligibility.yml
source_heading: Eligibility
source_page: https://www.truebinding.com/term-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrueBinding\naid: truebinding\nurl: https://www.truebinding.com/term-and-condition\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By placing an order through the site, you represent and warrant that you are duly licensed, qualified, and\n    authorized to obtain investigational drugs\n- type: business\n  text: Access to this Site and the ability to purchase products through the Site are strictly limited to licensed\n    physicians, healthcare providers, hospitals, clinics, pharmacies, and other entities legally authorized to obtain\n\
  \    and administer investigational drugs\nrestricted_uses:\n- summary: Investigational use only under FDA expanded access\n  text: Products made available through this Site are investigational drugs that have not been approved by the U.S.\n    Food and Drug Administration (FDA) for commercial sale.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/truebinding/eligibility/truebinding-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from TrueBinding's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Life Sciences
- Clinical Trials
- Drug Discovery
- Monoclonal Antibodies
- Neurodegenerative Disease
- CDMO
- Contract Manufacturing
- Healthcare
---
