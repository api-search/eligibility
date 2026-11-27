---
api_specs:
- filename: bounti-llms-full-txt-api-openapi.yml
  format: yaml
  label: Bounti Llms Full.txt API
  slug: bounti-llms-full-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bounti/openapi/bounti-llms-full-txt-api-openapi.yml
- filename: bounti-llms-txt-api-openapi.yml
  format: yaml
  label: Bounti Llms.txt API
  slug: bounti-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bounti/openapi/bounti-llms-txt-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Serves licensed real estate professionals across the United States.
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Bounti Platform, or any direct product thereof in violation of any restrictions, laws or regulations
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
name: Bounti
provenance_date: '2026-11-09'
provider_name: Bounti
provider_slug: bounti
slug: bounti-eligibility
source_date: '2026-11-09'
source_filename: bounti-eligibility.yml
source_heading: Eligibility
source_page: https://bounti.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bounti\naid: bounti\nurl: https://bounti.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Serves licensed real estate professionals across the United States.\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Bounti\n    Platform, or any direct\
  \ product thereof in violation of any restrictions, laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bounti/eligibility/bounti-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Bounti's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Artificial Intelligence
- Marketing
- Sales Enablement
- Virtual Staging
- Content Generation
- AI Agents
---
