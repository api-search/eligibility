---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Health data (PHI/HIPAA)
    text: Protected health information (PHI) or any data subject to the Health Insurance Portability and Accountability Act (HIPAA) or equivalent health data regulations in any jurisdiction;
  - summary: Children's data under COPPA
    text: Personal data of children under 13 years of age that is subject to the Children's Online Privacy Protection Act (COPPA) or equivalent regulations;
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
name: Chrysai
provenance_date: '2026-11-09'
provider_name: Chrysai
provider_slug: chrysai-com
slug: chrysai-com-eligibility
source_date: '2026-11-09'
source_filename: chrysai-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.chrysai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chrysai\naid: chrysai-com\nurl: https://www.chrysai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Health data (PHI/HIPAA)\n  text: Protected health information (PHI) or any data subject to the Health Insurance Portability and Accountability\n    Act (HIPAA) or equivalent health data regulations in any jurisdiction;\n- summary: Children's data under COPPA\n  text: Personal data of children under 13 years of age that is subject to the Children's Online Privacy Protection\n    Act (COPPA) or equivalent regulations;\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/chrysai-com/eligibility/chrysai-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Chrysai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Database
- MCP
- Low-Code
- Data
---
