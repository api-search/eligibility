---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The license is granted to a single individual developer
    type: individual
  - text: The license covers an unlimited number of individual developers within the same legal entity or organization
    type: business
  minimum_age:
    text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction, to create an account and purchase a license.
    value: '18'
  restricted_uses:
  - summary: No competing products
    text: You may not use the Pro Package source code to create, contribute to, or distribute a product that is substantially similar to or directly competes with Aura UI.
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
name: Aura UI
provenance_date: '2026-11-09'
provider_name: Aura UI
provider_slug: aura-ui-com
slug: aura-ui-com-eligibility
source_date: '2026-11-09'
source_filename: aura-ui-com-eligibility.yml
source_heading: Eligibility
source_page: https://aura-ui.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aura UI\naid: aura-ui-com\nurl: https://aura-ui.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The license is granted to a single individual developer\n- type: business\n  text: The license covers an unlimited number of individual developers within the same legal entity or organization\nrestricted_uses:\n- summary: No competing products\n  text: You may not use the Pro Package source code to create, contribute to, or distribute a product that is substantially\n    similar to or directly competes with Aura UI.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age, or the age of legal majority in your jurisdiction, to create an account\n    and purchase a license.\n"
source_yaml_url: https://artifacts.apis.io/aura-ui-com/eligibility/aura-ui-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Aura UI's own page on 2026-11-09.
synthetic: false
tags:
- UI
- Laravel
- Blade
- Components
- Open Source
---
