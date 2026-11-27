---
api_specs:
- filename: brainbox3ae3-io-api-openapi.yml
  format: yaml
  label: Brainbox3ae3 Io API
  slug: brainbox3ae3-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainbox3ae3/openapi/brainbox3ae3-io-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Military, aerospace, medical or life-support use
    text: customers must request and obtain formal written consent (such as a Letter of Authorisation) by contacting the Brainboxes Sales or Support team before integrating them into any military, aerospace, medical, or life-support equipment
  - summary: Weapons of mass destruction and conventional weapons
    text: Customers shall not use, export, re-export, or resell Brainboxes products, through any channels, for use in the design, development, production, utilization, maintenance, or operation of Weapons of Mass Destruction
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
name: Brainbox3ae3
provenance_date: '2026-11-09'
provider_name: Brainbox3ae3
provider_slug: brainbox3ae3
slug: brainbox3ae3-eligibility
source_date: '2026-11-09'
source_filename: brainbox3ae3-eligibility.yml
source_heading: Eligibility
source_page: https://www.brainboxes.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brainbox3ae3\naid: brainbox3ae3\nurl: https://www.brainboxes.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Military, aerospace, medical or life-support use\n  text: customers must request and obtain formal written consent (such as a Letter of Authorisation) by contacting\n    the Brainboxes Sales or Support team before integrating them into any military, aerospace, medical, or life-support\n    equipment\n- summary: Weapons of mass destruction and conventional weapons\n  text: Customers shall not use,\
  \ export, re-export, or resell Brainboxes products, through any channels, for use\n    in the design, development, production, utilization, maintenance, or operation of Weapons of Mass Destruction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/brainbox3ae3/eligibility/brainbox3ae3-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Brainbox3ae3's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Industrial
- Connectivity
- IoT
- Automation
---
