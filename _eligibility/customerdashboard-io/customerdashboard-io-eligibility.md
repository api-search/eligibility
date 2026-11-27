---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is offered only to businesses and persons acting for business purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data not supported
    text: The Service is not designed or certified for payment-card data, protected health information, government identification numbers, biometric or genetic data, children’s data, or other information subject to heightened legal or industry requirements.
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
name: CustomerDashboard
provenance_date: '2026-11-09'
provider_name: CustomerDashboard
provider_slug: customerdashboard-io
slug: customerdashboard-io-eligibility
source_date: '2026-11-09'
source_filename: customerdashboard-io-eligibility.yml
source_heading: Eligibility
source_page: https://app.customerdashboard.io/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CustomerDashboard\naid: customerdashboard-io\nurl: https://app.customerdashboard.io/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is offered only to businesses and persons acting for business purposes.\nrestricted_uses:\n- summary: Sensitive data not supported\n  text: The Service is not designed or certified for payment-card data, protected health information, government\n    identification numbers, biometric or genetic data, children’s data, or other information subject to heightened\n    legal or industry\
  \ requirements.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/customerdashboard-io/eligibility/customerdashboard-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CustomerDashboard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Dashboards
- Customer-Facing Analytics
- Embedded Analytics
- Client Reporting
- White Label
- Multi-Tenant
- MCP
- Software-as-a-Service
---
