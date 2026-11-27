---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo
  minimum_age:
    text: The App is not directed towards anyone under the age of 18 and you should not use it if you are under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Hazardous and safety-critical use
    text: you shall not use the App in, or in association with, the design, construction, maintenance or operation of any hazardous environments or systems, including any power generation systems; safety-critical applications, or military or aerospace applications, weapons systems or environments
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the App, you must already be authorized to access Nextworld SaaS offerings (“Account”) by a Nextworld customer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Nextworld
provenance_date: '2026-11-10'
provider_name: Nextworld
provider_slug: nextworld
slug: nextworld-eligibility
source_date: '2026-11-10'
source_filename: nextworld-eligibility.yml
source_heading: Eligibility
source_page: https://www.nextw.com/utility/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nextworld\naid: nextworld\nurl: https://www.nextw.com/utility/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo\nentity_types: []\nrestricted_uses:\n- summary: Hazardous and safety-critical use\n  text: you shall not use the App in, or in association with, the design, construction, maintenance or operation\n    of any hazardous environments or systems, including any power generation systems; safety-critical applications,\n    or military or aerospace applications, weapons systems or environments\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the App, you must already be authorized to access Nextworld SaaS offerings (“Account”) by a Nextworld\n    customer.\nminimum_age:\n  value: '18'\n  text: The App is not directed towards anyone under the age of 18 and you should not use it if you are under the\n    age of 18.\n"
source_yaml_url: https://artifacts.apis.io/nextworld/eligibility/nextworld-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Nextworld's own page on 2026-11-10.
synthetic: false
tags:
- Company
- ERP
- No-Code
- Enterprise Application Platform
- Workflow Automation
- Artificial Intelligence
- MCP
- Integration
- Manufacturing
- Distribution
---
