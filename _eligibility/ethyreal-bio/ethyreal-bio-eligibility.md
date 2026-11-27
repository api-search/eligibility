---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website is intended for individuals over the age of 18, who are residents of the United States and its territories.
  entity_types:
  - text: This Website is intended for individuals over the age of 18, who are residents of the United States and its territories.
    type: individual
  minimum_age:
    text: This Website is intended for individuals over the age of 18
    value: '18'
  restricted_uses:
  - summary: Non-commercial informational use only
    text: Ethyreal allows you to view and use the Website according to the Terms for your informational, non-commercial use.
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
name: Ethyreal Bio
provenance_date: '2026-11-09'
provider_name: Ethyreal Bio
provider_slug: ethyreal-bio
slug: ethyreal-bio-eligibility
source_date: '2026-11-09'
source_filename: ethyreal-bio-eligibility.yml
source_heading: Eligibility
source_page: https://www.ethyrealbio.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ethyreal Bio\naid: ethyreal-bio\nurl: https://www.ethyrealbio.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website is intended for individuals over the age of 18, who are residents of the United States and\n    its territories.\nentity_types:\n- type: individual\n  text: This Website is intended for individuals over the age of 18, who are residents of the United States and\n    its territories.\nrestricted_uses:\n- summary: Non-commercial informational use only\n  text: Ethyreal allows you to view and use the Website according to the Terms for your\
  \ informational, non-commercial\n    use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is intended for individuals over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/ethyreal-bio/eligibility/ethyreal-bio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ethyreal Bio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Life Sciences
- Drug Discovery
- Clinical Trials
- Immunology
- Endocrinology
- Antibodies
- Rare Disease
- Health
- Content
---
