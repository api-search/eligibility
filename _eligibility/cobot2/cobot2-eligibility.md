---
api_specs:
- filename: cobot2-openapi.yml
  format: yaml
  label: Cobot API
  slug: cobot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cobot2/openapi/cobot2-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Any use of Cobot requires prior registration on the Website by creating an account (“Account”) and the acceptance of these Terms of Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cobot2
provenance_date: '2026-11-09'
provider_name: Cobot2
provider_slug: cobot2
slug: cobot2-eligibility
source_date: '2026-11-09'
source_filename: cobot2-eligibility.yml
source_heading: Eligibility
source_page: https://www.cobot.me/en/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cobot2\naid: cobot2\nurl: https://www.cobot.me/en/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Any use of Cobot requires prior registration on the Website by creating an account (“Account”) and the acceptance\n    of these Terms of Service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cobot2/eligibility/cobot2-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Cobot2's own page on 2026-11-09.
synthetic: false
tags:
- Co-Working
- Software-as-a-Service
- Management
- Software
- Collaboration
- Company
---
