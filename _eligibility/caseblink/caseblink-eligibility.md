---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use in violation of law or export law
    text: otherwise use the Company Service in violation of applicable law (including any export law)
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
name: CaseBlink
provenance_date: '2026-11-09'
provider_name: CaseBlink
provider_slug: caseblink
slug: caseblink-eligibility
source_date: '2026-11-09'
source_filename: caseblink-eligibility.yml
source_heading: Eligibility
source_page: https://www.caseblink.com/service-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CaseBlink\naid: caseblink\nurl: https://www.caseblink.com/service-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT\nrestricted_uses:\n- summary: Use in violation of law or export law\n  text: otherwise use the Company Service in violation of applicable law (including any export law)\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/caseblink/eligibility/caseblink-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CaseBlink's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Immigration
- Legal Tech
- Automation
---
