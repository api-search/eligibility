---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use our Services on behalf or for the benefit of an organization, "you" also includes that organization.
    type: business
  minimum_age:
    text: Are of the age of majority in your jurisdiction.
    value: null
  restricted_uses:
  - summary: Authorized purposes only
    text: solely to search for, identify and view information about our products and services for lawful and legitimate purposes and to initiate or maintain a relationship with us
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
name: Concentrix
provenance_date: '2026-11-09'
provider_name: Concentrix
provider_slug: concentrix
slug: concentrix-eligibility
source_date: '2026-11-09'
source_filename: concentrix-eligibility.yml
source_heading: Eligibility
source_page: https://www.concentrix.com/wp-content/uploads/2024/04/Concentrix-Website-Terms-of-Use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Concentrix\naid: concentrix\nurl: https://www.concentrix.com/wp-content/uploads/2024/04/Concentrix-Website-Terms-of-Use.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use our Services on behalf or for the benefit of an organization, \"you\" also includes that organization.\nrestricted_uses:\n- summary: Authorized purposes only\n  text: solely to search for, identify and view information about our products and services for lawful and legitimate\n    purposes and to initiate or maintain a relationship with us\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Are of the age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/concentrix/eligibility/concentrix-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Concentrix's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Business Process Outsourcing
- Consulting
- Conversational AI
- Customer Experience
- Digital Transformation
- Enterprise Services
- Contact Center
- Voice
- Webhook
- Fortune 500
---
