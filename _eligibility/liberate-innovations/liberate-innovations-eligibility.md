---
api_specs:
- filename: liberate-innovations-events-api-openapi.yml
  format: yaml
  label: Liberate Innovations Events API
  slug: liberate-innovations-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liberate-innovations/openapi/liberate-innovations-events-api-openapi.yml
- filename: liberate-innovations-workflows-api-openapi.yml
  format: yaml
  label: Liberate Innovations Workflows API
  slug: liberate-innovations-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/liberate-innovations/openapi/liberate-innovations-workflows-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which you reside
    type: individual
  - text: If you accept or agree to these Terms of Service on behalf of your employer or another legal entity, you represent and warrant that (i) you have full legal authority to bind your employer or such entity
    type: business
  minimum_age:
    text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which you reside
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: conducting any unlawful purposes or soliciting others to perform or participate in any unlawful acts
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
name: Liberate Innovations
provenance_date: '2026-11-09'
provider_name: Liberate Innovations
provider_slug: liberate-innovations
slug: liberate-innovations-eligibility
source_date: '2026-11-09'
source_filename: liberate-innovations-eligibility.yml
source_heading: Eligibility
source_page: https://www.liberate.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liberate Innovations\naid: liberate-innovations\nurl: https://www.liberate.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which\n    you reside\n- type: business\n  text: If you accept or agree to these Terms of Service on behalf of your employer or another legal entity, you\n    represent and warrant that (i) you have full legal authority to bind your employer or such entity\nrestricted_uses:\n- summary: Unlawful\
  \ purposes\n  text: conducting any unlawful purposes or soliciting others to perform or participate in any unlawful acts\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which\n    you reside\n"
source_yaml_url: https://artifacts.apis.io/liberate-innovations/eligibility/liberate-innovations-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Liberate Innovations's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Artificial Intelligence
- Voice AI
- Conversational AI
- Workflow Orchestration
- Claims Automation
- Integration
- Contact Center
---
