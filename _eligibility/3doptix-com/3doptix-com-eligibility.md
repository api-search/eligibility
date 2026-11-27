---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: an individual ordering Services
    type: individual
  - text: an organization ordering Services to be used by one or more of your personnel
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No regulated data
    text: 'You agree that the Content will not include: any information, or documents or technical data that are U.S. Government Classified, Controlled Unclassified Information, ITAR or EAR controlled'
  - summary: No protected health information
    text: any data that is “protected health information, including any medical, demographic, visual or descriptive information that can be used to identify a particular patient/individual”
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must provide us with a current, valid accepted method of payment
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 3DOptix
provenance_date: '2026-11-09'
provider_name: 3DOptix
provider_slug: 3doptix-com
slug: 3doptix-com-eligibility
source_date: '2026-11-09'
source_filename: 3doptix-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.3doptix.com/term-conditions-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 3DOptix\naid: 3doptix-com\nurl: https://www.3doptix.com/term-conditions-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo, or that has been designated\n    by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: an individual ordering Services\n- type: business\n  text: an organization ordering Services to be used by one or more of your personnel\nrestricted_uses:\n- summary: No regulated data\n  text: 'You agree that the Content will not include: any\
  \ information, or documents or technical data that are U.S.\n    Government Classified, Controlled Unclassified Information, ITAR or EAR controlled'\n- summary: No protected health information\n  text: any data that is “protected health information, including any medical, demographic, visual or descriptive\n    information that can be used to identify a particular patient/individual”\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must provide us with a current, valid accepted method of payment\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/3doptix-com/eligibility/3doptix-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from 3DOptix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- OpticalDesign
- Simulation
- Cloud Software
- Engineering
---
