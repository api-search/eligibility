---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service, as applicable.
    type: business
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
    value: '18'
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
name: Revalia Bio
provenance_date: '2026-11-10'
provider_name: Revalia Bio
provider_slug: revalia-bio
slug: revalia-bio-eligibility
source_date: '2026-11-10'
source_filename: revalia-bio-eligibility.yml
source_heading: Eligibility
source_page: https://revaliabio.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Revalia Bio\naid: revalia-bio\nurl: https://revaliabio.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service, as applicable.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18\
  \ to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/revalia-bio/eligibility/revalia-bio-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Revalia Bio's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Artificial Intelligence
- Drug Development
- Medical Devices
- Clinical Data
- Life Sciences
- Translational Science
---
