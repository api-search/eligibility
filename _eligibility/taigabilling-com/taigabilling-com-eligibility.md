---
api_specs:
- filename: taigabilling-com-openapi-generated.yml
  format: yaml
  label: Taiga API
  slug: taigabilling-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taigabilling-com/openapi/_ae-authored/taigabilling-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a practice, organization, or other entity, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Submitting false or unlawful claims
    text: (a) use the services to submit claims or information you know or should know to be false, fraudulent, or otherwise in violation of law
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
name: Taiga
provenance_date: '2026-11-10'
provider_name: Taiga
provider_slug: taigabilling-com
slug: taigabilling-com-eligibility
source_date: '2026-11-10'
source_filename: taigabilling-com-eligibility.yml
source_heading: Eligibility
source_page: https://taigabilling.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Taiga\naid: taigabilling-com\nurl: https://taigabilling.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a practice, organization, or other entity, you represent\n    that you have authority to bind that entity.\nrestricted_uses:\n- summary: Submitting false or unlawful claims\n  text: (a) use the services to submit claims or information you know or should know to be false, fraudulent, or\n    otherwise in violation of law\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/taigabilling-com/eligibility/taigabilling-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Taiga's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Medical Billing
- Healthcare
- Software-as-a-Service
- Automation
---
