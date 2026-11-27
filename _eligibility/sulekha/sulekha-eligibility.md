---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You confirm that you are of legal age i.e. 18 years to form a legally binding contract with Sulekha
    type: individual
  - text: If you are using our Services on behalf of a business, that business accepts these terms.
    type: business
  minimum_age:
    text: You confirm that you are of legal age i.e. 18 years to form a legally binding contract with Sulekha
    value: '18'
  restricted_uses:
  - summary: Prohibited service offerings
    text: Service offerings that are prohibited by laws, regulations, sanctions and trade restrictions in India or any applicable jurisdiction are strictly forbidden in the Platform.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to provide certain business & government documents that will be used to authenticate your listings.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sulekha
provenance_date: '2026-11-10'
provider_name: Sulekha
provider_slug: sulekha
slug: sulekha-eligibility
source_date: '2026-11-10'
source_filename: sulekha-eligibility.yml
source_heading: Eligibility
source_page: https://www.sulekha.com/collateral/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sulekha\naid: sulekha\nurl: https://www.sulekha.com/collateral/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You confirm that you are of legal age i.e. 18 years to form a legally binding contract with Sulekha\n- type: business\n  text: If you are using our Services on behalf of a business, that business accepts these terms.\nrestricted_uses:\n- summary: Prohibited service offerings\n  text: Service offerings that are prohibited by laws, regulations, sanctions and trade restrictions in India or\n    any applicable\
  \ jurisdiction are strictly forbidden in the Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to provide certain business & government documents that will be used to authenticate\n    your listings.\nminimum_age:\n  value: '18'\n  text: You confirm that you are of legal age i.e. 18 years to form a legally binding contract with Sulekha\n"
source_yaml_url: https://artifacts.apis.io/sulekha/eligibility/sulekha-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Sulekha's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Classifieds
- Local Services
- Consumer
- India
- Directory
---
