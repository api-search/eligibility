---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo, or that has been designated by the United States government as a "terrorist supporting" country, and (ii) You are not listed on any United States government list of prohibited or restricted parties.
  entity_types:
  - text: You represent that you are over the age of 18.
    type: individual
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service, as applicable.
    type: business
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
    value: '18'
  restricted_uses:
  - summary: Unlawful or objectionable content
    text: You may not transmit any Content that is unlawful, offensive, upsetting, intended to disgust, threatening, libelous, defamatory, obscene or otherwise objectionable.
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
name: Freeform
provenance_date: '2026-11-09'
provider_name: Freeform
provider_slug: freeform
slug: freeform-eligibility
source_date: '2026-11-09'
source_filename: freeform-eligibility.yml
source_heading: Eligibility
source_page: https://freeform.co/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Freeform\naid: freeform\nurl: https://freeform.co/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo, or that has been designated by the United States government as a \"terrorist supporting\"\n    country, and (ii) You are not listed on any United States government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: You represent that you are over the age of 18.\n- type: business\n  text: You means the individual\
  \ accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service, as applicable.\nrestricted_uses:\n- summary: Unlawful or objectionable content\n  text: You may not transmit any Content that is unlawful, offensive, upsetting, intended to disgust, threatening,\n    libelous, defamatory, obscene or otherwise objectionable.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/freeform/eligibility/freeform-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Freeform's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advanced Manufacturing
- Metal 3D Printing
- 3D Printing
- Physical AI
- Autonomous Factories
- Aerospace
- Defense
---
