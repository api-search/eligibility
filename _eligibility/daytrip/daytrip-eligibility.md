---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Daytrip Global provides the Booking Services exclusively in and from the Czech Republic and not in or from any other jurisdiction.
  entity_types:
  - text: Except as described below, you must be at least 18 years of age, or the age of legal majority in your jurisdiction (if different than 18), to use the Booking Services.
    type: individual
  - text: If you are accepting these Terms on behalf of an entity, you represent and warrant that you have the authority to do so.
    type: business
  minimum_age:
    text: The Booking Services are not available for use by persons under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Unlawful or hazardous transport
    text: you may only access or use the Booking Services and Transport Services for lawful purposes (e.g., not request for the purpose or intent of transport of unlawful or hazardous materials)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In certain instances, you may be asked to provide proof of age, identity, or other method of identity verification to access or use the Transport Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Daytrip
provenance_date: '2026-11-09'
provider_name: Daytrip
provider_slug: daytrip
slug: daytrip-eligibility
source_date: '2026-11-09'
source_filename: daytrip-eligibility.yml
source_heading: Eligibility
source_page: https://daytrip.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Daytrip\naid: daytrip\nurl: https://daytrip.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Daytrip Global provides the Booking Services exclusively in and from the Czech Republic and not in or from\n    any other jurisdiction.\nentity_types:\n- type: individual\n  text: Except as described below, you must be at least 18 years of age, or the age of legal majority in your jurisdiction\n    (if different than 18), to use the Booking Services.\n- type: business\n  text: If you are accepting these Terms on behalf of an entity, you represent and warrant that you have the\
  \ authority\n    to do so.\nrestricted_uses:\n- summary: Unlawful or hazardous transport\n  text: you may only access or use the Booking Services and Transport Services for lawful purposes (e.g., not request\n    for the purpose or intent of transport of unlawful or hazardous materials)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In certain instances, you may be asked to provide proof of age, identity, or other method of identity verification\n    to access or use the Transport Services\nminimum_age:\n  value: '18'\n  text: The Booking Services are not available for use by persons under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/daytrip/eligibility/daytrip-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Daytrip's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Transportation
- Booking
- Platform
---
