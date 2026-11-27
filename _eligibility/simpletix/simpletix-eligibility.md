---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 13 years of age. If you are under the age of 18, you represent that you have the consent of a parent or legal guardian to use the Service.
    type: individual
  minimum_age:
    text: You are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: High-risk environments
    text: The Service is not designed for use in high-risk environments where failure could lead to significant harm, injury, or death, such as in nuclear facilities, aircraft navigation systems, medical devices, or weapons systems.
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
name: SimpleTix
provenance_date: '2026-11-10'
provider_name: SimpleTix
provider_slug: simpletix
slug: simpletix-eligibility
source_date: '2026-11-10'
source_filename: simpletix-eligibility.yml
source_heading: Eligibility
source_page: https://www.simpletix.com/terms.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SimpleTix\naid: simpletix\nurl: https://www.simpletix.com/terms.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 13 years of age. If you are under the age of 18, you represent that you have the consent\n    of a parent or legal guardian to use the Service.\nrestricted_uses:\n- summary: High-risk environments\n  text: The Service is not designed for use in high-risk environments where failure could lead to significant harm,\n    injury, or death, such as in nuclear facilities, aircraft navigation systems, medical\
  \ devices, or weapons systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/simpletix/eligibility/simpletix-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SimpleTix's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ticketing
- Event
- Software-as-a-Service
- Online Payments
---
