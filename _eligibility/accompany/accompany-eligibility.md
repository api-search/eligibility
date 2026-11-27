---
api_specs:
- filename: accompany-openapi-generated.yml
  format: yaml
  label: Accompany API
  slug: accompany-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/accompany/openapi/_ae-authored/accompany-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: the Service is not available to children (persons under the age of 18) or others who are not capable of entering into binding contracts.
    value: '18'
  restricted_uses:
  - summary: Competitors excluded
    text: are not a competitor of Accompany and are not using the Services for reasons that are in competition with Accompany
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: ACCOMPANY DOES NOT HAVE ANY OBLIGATION TO VERIFY THE IDENTITY OF THE PERSONS SUBSCRIBING TO ITS SERVICES
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Accompany
provenance_date: '2026-11-09'
provider_name: Accompany
provider_slug: accompany
slug: accompany-eligibility
source_date: '2026-11-09'
source_filename: accompany-eligibility.yml
source_heading: Eligibility
source_page: https://www.accompany.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accompany\naid: accompany\nurl: https://www.accompany.com/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity\nrestricted_uses:\n- summary: Competitors excluded\n  text: are not a competitor of Accompany and are not using the Services for reasons that are in competition with\n    Accompany\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: ACCOMPANY\
  \ DOES NOT HAVE ANY OBLIGATION TO VERIFY THE IDENTITY OF THE PERSONS SUBSCRIBING TO ITS SERVICES\nminimum_age:\n  value: '18'\n  text: the Service is not available to children (persons under the age of 18) or others who are not capable of\n    entering into binding contracts.\n"
source_yaml_url: https://artifacts.apis.io/accompany/eligibility/accompany-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Accompany's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Relationship Intelligence
- Sales Intelligence
- Acquired
- Defunct
---
