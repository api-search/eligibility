---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Website and App are only available for use and download in the United States.
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: individual
  minimum_age:
    text: (a) are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Competitors
    text: are not our competitor, or are not using our Website App, or Services for reasons that are in competition with us
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
name: Alix
provenance_date: '2026-11-09'
provider_name: Alix
provider_slug: alix
slug: alix-eligibility
source_date: '2026-11-09'
source_filename: alix-eligibility.yml
source_heading: Eligibility
source_page: https://www.meetalix.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alix\naid: alix\nurl: https://www.meetalix.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Website and App are only available for use and download in the United States.\nentity_types:\n- type: individual\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such entity\nrestricted_uses:\n- summary: Competitors\n  text: are not our competitor, or are not using our Website App, or Services for reasons that are in competition\n    with us\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (a) are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/alix/eligibility/alix-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Alix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Estate Settlement
- Legal Tech
- Probate
- Estate Administration
- Wealth
- Consumer Finance
---
