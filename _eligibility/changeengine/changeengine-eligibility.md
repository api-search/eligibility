---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Business Partner” means a legal entity that requires use of a Cloud Service in connection with Customer’s and its Affiliates’ internal business operations.
    type: business
  - text: If you are a United States federal government agency, use of the Services is subject to this amendment.
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No penetration testing without approval
    text: Customer will not conduct or authorize penetration tests of the Cloud Service without advance approval from ChangeEngine.
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
name: ChangeEngine
provenance_date: '2026-11-09'
provider_name: ChangeEngine
provider_slug: changeengine
slug: changeengine-eligibility
source_date: '2026-11-09'
source_filename: changeengine-eligibility.yml
source_heading: Eligibility
source_page: https://www.changeengine.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChangeEngine\naid: changeengine\nurl: https://www.changeengine.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Business Partner” means a legal entity that requires use of a Cloud Service in connection with Customer’s\n    and its Affiliates’ internal business operations.\n- type: government\n  text: If you are a United States federal government agency, use of the Services is subject to this amendment.\nrestricted_uses:\n- summary: No penetration testing without approval\n  text: Customer will not conduct or authorize\
  \ penetration tests of the Cloud Service without advance approval from\n    ChangeEngine.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/changeengine/eligibility/changeengine-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ChangeEngine's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Human Resources
- Internal Communications
- Employee Engagement
- People Operations
- Employee Experience
- Artificial Intelligence
---
