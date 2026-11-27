---
api_specs:
- filename: zurelay-com-openapi-generated.yml
  format: yaml
  label: zurelay-com API
  slug: zurelay-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zurelay-com/openapi/_ae-authored/zurelay-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, organized in or ordinarily resident in a country or region subject to comprehensive United States sanctions
  entity_types:
  - text: The Services are offered only to businesses, developers and professionals acting for business purposes, and not to consumers.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Restricted Data
    text: 'you must not submit any of the following ( Restricted Data ): protected health information under HIPAA'
  - summary: Prohibited uses
    text: create malware or carry out unauthorized intrusion, credential theft, phishing, denial-of-service or other attacks on any system
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
name: zurelay-com
provenance_date: '2026-11-10'
provider_name: zurelay-com
provider_slug: zurelay-com
slug: zurelay-com-eligibility
source_date: '2026-11-10'
source_filename: zurelay-com-eligibility.yml
source_heading: Eligibility
source_page: https://zurelay.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: zurelay-com\naid: zurelay-com\nurl: https://zurelay.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, organized in or ordinarily resident in a country or\n    region subject to comprehensive United States sanctions\nentity_types:\n- type: business\n  text: The Services are offered only to businesses, developers and professionals acting for business purposes,\n    and not to consumers.\nrestricted_uses:\n- summary: Restricted Data\n  text: 'you must not submit any of the following ( Restricted Data ): protected health\
  \ information under HIPAA'\n- summary: Prohibited uses\n  text: create malware or carry out unauthorized intrusion, credential theft, phishing, denial-of-service or other\n    attacks on any system\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/zurelay-com/eligibility/zurelay-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from zurelay-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cloud
- Machine Learning
- Cost-Saving
---
