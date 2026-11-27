---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to access Vivoo Services and create a Vivoo user account.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to access Vivoo Services and create a Vivoo user account.
    value: '18'
  restricted_uses:
  - summary: Not for diagnosis or medical use
    text: This product is not intended for use in diagnosing diseases or other conditions; determining or monitoring the state of health; or curing, mitigating, treating, or preventing any diseases.
  - summary: Pregnant and nursing women
    text: PREGNANT WOMEN AND NURSING WOMEN SHOULD NOT TAKE INTO ACCOUNT THE ADVICE GIVEN AT VIVOO.
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
name: Vivoo
provenance_date: '2026-11-10'
provider_name: Vivoo
provider_slug: vivoo
slug: vivoo-eligibility
source_date: '2026-11-10'
source_filename: vivoo-eligibility.yml
source_heading: Eligibility
source_page: https://www.vivoo.io/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vivoo\naid: vivoo\nurl: https://www.vivoo.io/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to access Vivoo Services and create a Vivoo user account.\nrestricted_uses:\n- summary: Not for diagnosis or medical use\n  text: This product is not intended for use in diagnosing diseases or other conditions; determining or monitoring\n    the state of health; or curing, mitigating, treating, or preventing any diseases.\n- summary: Pregnant and nursing women\n  text: PREGNANT WOMEN\
  \ AND NURSING WOMEN SHOULD NOT TAKE INTO ACCOUNT THE ADVICE GIVEN AT VIVOO.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to access Vivoo Services and create a Vivoo user account.\n"
source_yaml_url: https://artifacts.apis.io/vivoo/eligibility/vivoo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vivoo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Wellness
- Consumer Health
- Nutrition
- Diagnostics
- E-Commerce
- Agentic Commerce
- MCP
---
