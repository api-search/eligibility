---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended solely for Users who, if they are a natural person, are eighteen (18) years of age or older
    type: individual
  - text: if you are accessing the Service or applying for our products or services on behalf of an LLC, corporation, partnership, trust, or other person or entity, you represent that you have the authority to agree to our Terms of Use on behalf of the entity
    type: business
  minimum_age:
    text: The Service is intended solely for Users who, if they are a natural person, are eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: No unlawful use or account for another person
    text: use an account or the Service for any unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: federal law requires we obtain, verify, and record information that identifies each person who creates a relationship
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kiavi
provenance_date: '2026-11-09'
provider_name: Kiavi
provider_slug: kiavi
slug: kiavi-eligibility
source_date: '2026-11-09'
source_filename: kiavi-eligibility.yml
source_heading: Eligibility
source_page: https://www.kiavi.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kiavi\naid: kiavi\nurl: https://www.kiavi.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is intended solely for Users who, if they are a natural person, are eighteen (18) years of age\n    or older\n- type: business\n  text: if you are accessing the Service or applying for our products or services on behalf of an LLC, corporation,\n    partnership, trust, or other person or entity, you represent that you have the authority to agree to our Terms\n    of Use on behalf of the entity\nrestricted_uses:\n- summary:\
  \ No unlawful use or account for another person\n  text: use an account or the Service for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: federal law requires we obtain, verify, and record information that identifies each person who creates a\n    relationship\nminimum_age:\n  value: '18'\n  text: The Service is intended solely for Users who, if they are a natural person, are eighteen (18) years of age\n    or older\n"
source_yaml_url: https://artifacts.apis.io/kiavi/eligibility/kiavi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Kiavi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Real Estate
- Lending
- Mortgage
- Financial Services
- PropTech
---
