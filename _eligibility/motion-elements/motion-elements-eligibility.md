---
api_specs:
- filename: motion-elements-account-api-openapi.yml
  format: yaml
  label: Motion Elements Account API
  slug: motion-elements-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/motion-elements/openapi/motion-elements-account-api-openapi.yml
- filename: motion-elements-elements-api-openapi.yml
  format: yaml
  label: Motion Elements API
  slug: motion-elements-elements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/motion-elements/openapi/motion-elements-elements-api-openapi.yml
- filename: motion-elements-media-types-api-openapi.yml
  format: yaml
  label: Motion Elements Media types API
  slug: motion-elements-media-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/motion-elements/openapi/motion-elements-media-types-api-openapi.yml
- filename: motion-elements-search-api-openapi.yml
  format: yaml
  label: Motion Elements Search API
  slug: motion-elements-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/motion-elements/openapi/motion-elements-search-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are of sufficient legal age to use the Site and to create binding legal obligations
    type: individual
  - text: If you are agreeing to these terms on behalf of someone else (like your employer), you represent and warrant that you have full legal authority to bind that third party.
    type: business
  minimum_age:
    text: You need to be 18 years or over to sign-up as a member.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited conduct
    text: You agree that you will not use the Site for any purpose that is unlawful or not permitted by this Agreement
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: you need to (a) register as a Contributor (b) accept the terms in our Contributor Agreement and (c) upload your digital assets for the initial contributor approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Motion Elements
provenance_date: '2026-11-10'
provider_name: Motion Elements
provider_slug: motion-elements
slug: motion-elements-eligibility
source_date: '2026-11-10'
source_filename: motion-elements-eligibility.yml
source_heading: Eligibility
source_page: https://www.motionelements.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Motion Elements\naid: motion-elements\nurl: https://www.motionelements.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are of sufficient legal age to use the Site and to create binding legal\n    obligations\n- type: business\n  text: If you are agreeing to these terms on behalf of someone else (like your employer), you represent and warrant\n    that you have full legal authority to bind that third party.\nrestricted_uses:\n- summary: Unlawful or prohibited conduct\n  text: You agree\
  \ that you will not use the Site for any purpose that is unlawful or not permitted by this Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: you need to (a) register as a Contributor (b) accept the terms in our Contributor Agreement and (c) upload\n    your digital assets for the initial contributor approval.\nminimum_age:\n  value: '18'\n  text: You need to be 18 years or over to sign-up as a member.\n"
source_yaml_url: https://artifacts.apis.io/motion-elements/eligibility/motion-elements-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Motion Elements's own page on 2026-11-10.
synthetic: false
tags:
- Media
- Stock Media
- Video
- Music
- Sound Effects
- Templates
- Marketplace
- Creative Assets
- Generative AI
- Search
- Company
---
