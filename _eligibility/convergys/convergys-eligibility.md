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
    value: age of majority
  restricted_uses:
  - summary: Unlawful or malicious purposes
    text: To engage in any illegal, unlawful or malicious purpose or activity
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
name: Convergys
provenance_date: '2026-11-09'
provider_name: Convergys
provider_slug: convergys
slug: convergys-eligibility
source_date: '2026-11-09'
source_filename: convergys-eligibility.yml
source_heading: Eligibility
source_page: https://www.concentrix.com/wp-content/uploads/2024/04/Concentrix-Website-Terms-of-Use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Convergys\naid: convergys\nurl: https://www.concentrix.com/wp-content/uploads/2024/04/Concentrix-Website-Terms-of-Use.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use our Services on behalf or for the benefit of an organization, \"you\" also includes that organization.\nrestricted_uses:\n- summary: Unlawful or malicious purposes\n  text: To engage in any illegal, unlawful or malicious purpose or activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n\
  \  text: Are of the age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/convergys/eligibility/convergys-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Convergys's own page on 2026-11-09.
synthetic: false
tags:
- Acquired
- Analytics
- Business Process Outsourcing
- Concentrix
- Contact Center
- Customer Experience
- Customer Management
- Workforce Management
---
