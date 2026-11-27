---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This is a US site only.
  entity_types:
  - text: You must be at least 18 years old to use the Website.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Website.
    value: '18'
  restricted_uses:
  - summary: Illegal use or falsifying age
    text: (a) use the Website for any illegal purpose or in violation of any local, state, national, or international law
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
name: Alector
provenance_date: '2026-11-09'
provider_name: Alector
provider_slug: alector
slug: alector-eligibility
source_date: '2026-11-09'
source_filename: alector-eligibility.yml
source_heading: Eligibility
source_page: https://alector.com/terms-of-use-2/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alector\naid: alector\nurl: https://alector.com/terms-of-use-2/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This is a US site only.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Website.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Illegal use or falsifying age\n  text: (a) use the Website for any illegal purpose or in violation of any local,\
  \ state, national, or international\n    law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/alector/eligibility/alector-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Alector's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Life Sciences
- Biotechnology
- Neuroscience
- Neurodegeneration
- Immunology
- Therapeutics
- Drug Development
---
