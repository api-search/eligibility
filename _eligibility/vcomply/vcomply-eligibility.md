---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Customer is entering into this Agreement on behalf of a company or other legal entity, Customer represents that it has the authority to bind such entity to these terms.
    type: business
  - text: If Customer is a U.S. federal government end user, the Services and related Documentation are “commercial computer software”
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and embargo restrictions
    text: Customer shall not permit any third party to access or use the Services in violation of any U.S. or international embargo, export law, or regulation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If Customer is approved for Free Trial Services, Customer may use the Services free of charge
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: VComply
provenance_date: '2026-11-10'
provider_name: VComply
provider_slug: vcomply
slug: vcomply-eligibility
source_date: '2026-11-10'
source_filename: vcomply-eligibility.yml
source_heading: Eligibility
source_page: https://www.v-comply.com/termsofservice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VComply\naid: vcomply\nurl: https://www.v-comply.com/termsofservice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If Customer is entering into this Agreement on behalf of a company or other legal entity, Customer represents\n    that it has the authority to bind such entity to these terms.\n- type: government\n  text: If Customer is a U.S. federal government end user, the Services and related Documentation are “commercial\n    computer software”\nrestricted_uses:\n- summary: Export and embargo restrictions\n  text: Customer shall\
  \ not permit any third party to access or use the Services in violation of any U.S. or international\n    embargo, export law, or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If Customer is approved for Free Trial Services, Customer may use the Services free of charge\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vcomply/eligibility/vcomply-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from VComply's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- GRC
- Compliance
- Risk Management
- Policy Management
- Audit
- Incident Management
- Software-as-a-Service
---
