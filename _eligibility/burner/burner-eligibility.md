---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not (a) located in or a national or resident of any country that is subject to U.S. trade sanctions
  entity_types:
  - text: By using the Service, you affirm that you are at least 18 years of age (or have reached the age of majority if that is not 18 years of age where you live).
    type: individual
  minimum_age:
    text: By using the Service, you affirm that you are at least 18 years of age (or have reached the age of majority if that is not 18 years of age where you live).
    value: '18'
  restricted_uses:
  - summary: No 911/emergency calling
    text: THE SERVICE CANNOT BE USED FOR 911 OR EMERGENCY CALLING.
  - summary: Prohibited content and uses
    text: use the Service for call centers, conference calling, trunking (to a PBX or otherwise) or other high volume or multi-person calling purposes
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
name: Burner
provenance_date: '2026-11-09'
provider_name: Burner
provider_slug: burner
slug: burner-eligibility
source_date: '2026-11-09'
source_filename: burner-eligibility.yml
source_heading: Eligibility
source_page: https://www.adhoclabs.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Burner\naid: burner\nurl: https://www.adhoclabs.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not (a) located in or a national or resident of any country that\n    is subject to U.S. trade sanctions\nentity_types:\n- type: individual\n  text: By using the Service, you affirm that you are at least 18 years of age (or have reached the age of majority\n    if that is not 18 years of age where you live).\nrestricted_uses:\n- summary: No 911/emergency calling\n  text: THE SERVICE CANNOT BE USED FOR 911 OR\
  \ EMERGENCY CALLING.\n- summary: Prohibited content and uses\n  text: use the Service for call centers, conference calling, trunking (to a PBX or otherwise) or other high volume\n    or multi-person calling purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Service, you affirm that you are at least 18 years of age (or have reached the age of majority\n    if that is not 18 years of age where you live).\n"
source_yaml_url: https://artifacts.apis.io/burner/eligibility/burner-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Burner's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Phone Numbers
- SMS
- MMS
- Voice
- Messaging
- Telephony
- Privacy
- Communications
- Second Phone Number
- OAuth
- Webhook
- Authentication
---
