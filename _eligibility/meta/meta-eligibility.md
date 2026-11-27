---
api_specs:
- filename: meta-custom-audiences-api-openapi.yml
  format: yaml
  label: Meta Custom Audiences API
  slug: meta-custom-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meta/openapi/meta-custom-audiences-api-openapi.yml
- filename: meta-pages-api-openapi.yml
  format: yaml
  label: Meta Pages API
  slug: meta-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meta/openapi/meta-pages-api-openapi.yml
- filename: meta-users-api-openapi.yml
  format: yaml
  label: Meta Users API
  slug: meta-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meta/openapi/meta-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms or accessing or using Platform on behalf of an entity, you represent and warrant that you have the authority to bind such entity to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No eligibility determinations
    text: Processing Platform Data to make eligibility determinations about people, including for housing, employment, insurance, education opportunities, credit, government benefits, or immigration status.
  - summary: No surveillance
    text: Processing Platform Data to perform, facilitate, or provide tools for surveillance.
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
name: Meta
provenance_date: '2026-11-10'
provider_name: Meta
provider_slug: meta
slug: meta-eligibility
source_date: '2026-11-10'
source_filename: meta-eligibility.yml
source_heading: Eligibility
source_page: https://developers.facebook.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Meta\naid: meta\nurl: https://developers.facebook.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms or accessing or using Platform on behalf of an entity, you represent and\n    warrant that you have the authority to bind such entity to these Terms\nrestricted_uses:\n- summary: No eligibility determinations\n  text: Processing Platform Data to make eligibility determinations about people, including for housing, employment,\n    insurance, education opportunities, credit, government benefits,\
  \ or immigration status.\n- summary: No surveillance\n  text: Processing Platform Data to perform, facilitate, or provide tools for surveillance.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/meta/eligibility/meta-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Meta's own page on 2026-11-10.
synthetic: false
tags:
- Meta
- Advertising
- Analytics
- Artificial Intelligence
- Messaging
- Social
- Social Media
- Virtual Reality
---
