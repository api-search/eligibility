---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Natural persons who are at least 18 years old and possess full legal capacity.
    type: individual
  - text: The GTC apply exclusively to commercial users of the website ("User"), defined as enterprises and other entities engaging in commercial activities.
    type: business
  minimum_age:
    text: Natural persons who are at least 18 years old and possess full legal capacity.
    value: '18'
  restricted_uses:
  - summary: Consumer use prohibited
    text: Consumers are expressly prohibited from using the Platform (commercial part of the website).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Senken may subject the use of the Platform or individual functions of the Platform, or the extent to which individual functions can be used, to certain conditions, such as verification of registration data, confirmation of commercial status, duration of use, or the submission of certain documents (e.g., identity documents).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Senken
provenance_date: '2026-11-10'
provider_name: Senken
provider_slug: senken
slug: senken-eligibility
source_date: '2026-11-10'
source_filename: senken-eligibility.yml
source_heading: Eligibility
source_page: https://www.senken.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Senken\naid: senken\nurl: https://www.senken.io/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Natural persons who are at least 18 years old and possess full legal capacity.\n- type: business\n  text: The GTC apply exclusively to commercial users of the website (\"User\"), defined as enterprises and other\n    entities engaging in commercial activities.\nrestricted_uses:\n- summary: Consumer use prohibited\n  text: Consumers are expressly prohibited from using the Platform (commercial part of the website).\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Senken may subject the use of the Platform or individual functions of the Platform, or the extent to which\n    individual functions can be used, to certain conditions, such as verification of registration data, confirmation\n    of commercial status, duration of use, or the submission of certain documents (e.g., identity documents).\nminimum_age:\n  value: '18'\n  text: Natural persons who are at least 18 years old and possess full legal capacity.\n"
source_yaml_url: https://artifacts.apis.io/senken/eligibility/senken-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Senken's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Planetary Health
- Carbon Credits
- Carbon Markets
- Carbon Removal
- Sustainability
- Climate
- ESG
---
