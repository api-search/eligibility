---
api_specs:
- filename: asvaai-com-openapi-generated.yml
  format: yaml
  label: Asva AI API
  slug: asvaai-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asvaai-com/openapi/_ae-authored/asvaai-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen years of age and capable of forming a binding contract to use the Service.
    type: individual
  - text: If you are using the Service on behalf of a company or other legal entity, you represent that you have authority to bind that entity, and "you" refers to both you and the entity.
    type: business
  minimum_age:
    text: You must be at least eighteen years of age and capable of forming a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Stalking or harassment
    text: Use the Service for stalking, harassment, or activities that target an individual's private information.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must sign in with a work email address; personal email providers such as Gmail, Yahoo, and Hotmail are not accepted at signup.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Asva AI
provenance_date: '2026-11-09'
provider_name: Asva AI
provider_slug: asvaai-com
slug: asvaai-com-eligibility
source_date: '2026-11-09'
source_filename: asvaai-com-eligibility.yml
source_heading: Eligibility
source_page: https://asvaai.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asva AI\naid: asvaai-com\nurl: https://asvaai.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen years of age and capable of forming a binding contract to use the Service.\n- type: business\n  text: If you are using the Service on behalf of a company or other legal entity, you represent that you have authority\n    to bind that entity, and \"you\" refers to both you and the entity.\nrestricted_uses:\n- summary: Stalking or harassment\n  text: Use the Service for stalking, harassment, or activities\
  \ that target an individual's private information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must sign in with a work email address; personal email providers such as Gmail, Yahoo, and Hotmail are\n    not accepted at signup.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen years of age and capable of forming a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/asvaai-com/eligibility/asvaai-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Asva AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketing
- SEO
- Brand Monitoring
- Analytics
---
