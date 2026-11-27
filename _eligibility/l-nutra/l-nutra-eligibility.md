---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: L-Nutra may reject orders where the stated delivery address is outside the United States.
  minimum_age:
    source: https://l-nutrahealth.com/policies/terms-of-service
    text: L-Nutra does not knowingly collect, either online or offline, personal information from persons under the age of thirteen. If you are under 18, you may use L-NutraHealth.com only with permission of a parent or guardian.
    value: '13'
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
name: L-Nutra
provenance_date: '2026-11-09'
provider_name: L-Nutra
provider_slug: l-nutra
slug: l-nutra-eligibility
source_date: '2026-11-09'
source_filename: l-nutra-eligibility.yml
source_heading: Eligibility
source_page: https://prolonlife.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: L-Nutra\naid: l-nutra\nurl: https://prolonlife.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://l-nutrahealth.com/policies/terms-of-service\n  - https://prolonlife.com/policies/terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: L-Nutra may reject orders where the stated delivery address is outside the United States.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: L-Nutra does not knowingly collect, either online or offline, personal information from persons\
  \ under the\n    age of thirteen. If you are under 18, you may use L-NutraHealth.com only with permission of a parent or guardian.\n  source: https://l-nutrahealth.com/policies/terms-of-service\n"
source_yaml_url: https://artifacts.apis.io/l-nutra/eligibility/l-nutra-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from L-Nutra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Nutrition
- Health
- Longevity
- Consumer Products
- E-Commerce
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
---
