---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These Plume Terms apply to Customers and Users located in the U.S., not including U.S. territories.
  entity_types:
  - text: If you are the Customer and a natural person, then you also are a User.
    type: individual
  - text: IF YOU ARE ACCEPTING THESE PLUME TERMS ON BEHALF OF A LEGAL ENTITY, YOU REPRESENT TO PLUME THAT YOU HAVE THE AUTHORITY TO BIND THAT ENTITY TO THESE PLUME TERMS.
    type: business
  minimum_age:
    text: The Plume Services are not targeted for use by children. Customer is responsible for obtaining verifiable consent from the parent or legal guardian of any User who is under the age of majority.
    value: not stated
  restricted_uses:
  - summary: No life, safety or critical use
    text: YOU AGREE THAT YOU WILL NOT RELY ON THE PLUME SERVICES FOR ANY LIFE, SAFETY OR CRITICAL PURPOSES.
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
name: Plume
provenance_date: '2026-11-10'
provider_name: Plume
provider_slug: plume
slug: plume-eligibility
source_date: '2026-11-10'
source_filename: plume-eligibility.yml
source_heading: Eligibility
source_page: https://www.plume.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plume\naid: plume\nurl: https://www.plume.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These Plume Terms apply to Customers and Users located in the U.S., not including U.S. territories.\nentity_types:\n- type: individual\n  text: If you are the Customer and a natural person, then you also are a User.\n- type: business\n  text: IF YOU ARE ACCEPTING THESE PLUME TERMS ON BEHALF OF A LEGAL ENTITY, YOU REPRESENT TO PLUME THAT YOU HAVE\n    THE AUTHORITY TO BIND THAT ENTITY TO THESE PLUME TERMS.\nrestricted_uses:\n- summary: No life, safety or critical\
  \ use\n  text: YOU AGREE THAT YOU WILL NOT RELY ON THE PLUME SERVICES FOR ANY LIFE, SAFETY OR CRITICAL PURPOSES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: not stated\n  text: The Plume Services are not targeted for use by children. Customer is responsible for obtaining verifiable\n    consent from the parent or legal guardian of any User who is under the age of majority.\n"
source_yaml_url: https://artifacts.apis.io/plume/eligibility/plume-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Plume's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Wi-Fi
- ISP
- Smart Home
- Network Intelligence
- Cybersecurity
- Software-as-a-Service
- OpenSync
- CPE
- Connectivity
---
