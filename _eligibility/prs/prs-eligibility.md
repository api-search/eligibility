---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: be a resident of the UK
  entity_types:
  - text: 'To be eligible for and to enter the prize draw you must: a) be 18 years of age or over; b) be a resident of the UK'
    type: individual
  minimum_age:
    text: be 18 years of age or over
    value: '18'
  restricted_uses:
  - summary: Employees excluded
    text: This prize draw is not open to employees of PRS for Music or their families.
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
name: PRS for Music
provenance_date: '2026-11-10'
provider_name: PRS for Music
provider_slug: prs
slug: prs-eligibility
source_date: '2026-11-10'
source_filename: prs-eligibility.yml
source_heading: Eligibility
source_page: https://www.prsformusic.com/legal-policy-hub/terms-conditions-prize-draw
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PRS for Music\naid: prs\nurl: https://www.prsformusic.com/legal-policy-hub/terms-conditions-prize-draw\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: be a resident of the UK\nentity_types:\n- type: individual\n  text: 'To be eligible for and to enter the prize draw you must: a) be 18 years of age or over; b) be a resident\n    of the UK'\nrestricted_uses:\n- summary: Employees excluded\n  text: This prize draw is not open to employees of PRS for Music or their families.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: be 18 years of age or over\n"
source_yaml_url: https://artifacts.apis.io/prs/eligibility/prs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from PRS for Music's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Music
- Royalties
- Licensing
- Rights
---
