---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In order to use the Service, you need to (1) be 18 or older, or be 13 or older and have your parent or guardian’s consent to the terms
    type: individual
  - text: If you are using the Services on behalf of an entity, you are agreeing to these Terms for that entity and are representing to us that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: be 18 or older, or be 13 or older and have your parent or guardian’s consent to the terms
    value: '13'
  restricted_uses:
  - summary: No commercial solicitation
    text: That no commercial solicitation or advertising will be allowed.
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
name: Napatech
provenance_date: '2026-11-10'
provider_name: Napatech
provider_slug: napatech
slug: napatech-eligibility
source_date: '2026-11-10'
source_filename: napatech-eligibility.yml
source_heading: Eligibility
source_page: https://forum.napatech.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Napatech\naid: napatech\nurl: https://forum.napatech.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In order to use the Service, you need to (1) be 18 or older, or be 13 or older and have your parent or guardian’s\n    consent to the terms\n- type: business\n  text: If you are using the Services on behalf of an entity, you are agreeing to these Terms for that entity and\n    are representing to us that you have the authority to bind that entity to these Terms\nrestricted_uses:\n- summary: No commercial solicitation\n\
  \  text: That no commercial solicitation or advertising will be allowed.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: be 18 or older, or be 13 or older and have your parent or guardian’s consent to the terms\n"
source_yaml_url: https://artifacts.apis.io/napatech/eligibility/napatech-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Napatech's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Infra Devtools
- Networking
- SmartNIC
- FPGA
- Network Monitoring
- Cybersecurity
- Packet Capture
- Hardware SDK
---
