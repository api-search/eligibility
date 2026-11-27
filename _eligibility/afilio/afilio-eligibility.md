---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - DE
    text: Die Dienste richten sich an Verbraucher; Gerichtsstand Berlin-Geschäftssitz für Kunden ohne Gerichtsstand in EU. Länderbeschränkung nicht ausdrücklich genannt außer Deutschland als Sitz.
  entity_types:
  - text: Afilio richtet sich ausschließlich an Verbraucher und Verbraucherinnen.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use
    text: Die Nutzung von Afilio zu gewerblichen oder sonstigen kommerziellen Zwecken ist ausdrücklich untersagt.
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
name: Afilio
provenance_date: '2026-11-09'
provider_name: Afilio
provider_slug: afilio
slug: afilio-eligibility
source_date: '2026-11-09'
source_filename: afilio-eligibility.yml
source_heading: Eligibility
source_page: https://www.afilio.de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Afilio\naid: afilio\nurl: https://www.afilio.de/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DE\n  excluded: []\n  text: Die Dienste richten sich an Verbraucher; Gerichtsstand Berlin-Geschäftssitz für Kunden ohne Gerichtsstand\n    in EU. Länderbeschränkung nicht ausdrücklich genannt außer Deutschland als Sitz.\nentity_types:\n- type: individual\n  text: Afilio richtet sich ausschließlich an Verbraucher und Verbraucherinnen.\nrestricted_uses:\n- summary: No commercial use\n  text: Die Nutzung von Afilio zu gewerblichen oder sonstigen kommerziellen Zwecken ist ausdrücklich untersagt.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/afilio/eligibility/afilio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Afilio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal Tech
- Estate Planning
- Digital Provision
- Healthcare
- Elder Care
- Consumer
- Germany
- GDPR
- Wills
---
