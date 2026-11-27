---
api_specs:
- filename: pexels-collections-api-openapi.yml
  format: yaml
  label: Pexels Collections API
  slug: pexels-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexels/openapi/pexels-collections-api-openapi.yml
- filename: pexels-photos-api-openapi.yml
  format: yaml
  label: Pexels Photos API
  slug: pexels-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexels/openapi/pexels-photos-api-openapi.yml
- filename: pexels-videos-api-openapi.yml
  format: yaml
  label: Pexels Videos API
  slug: pexels-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pexels/openapi/pexels-videos-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Children may not access or use the Service. For the purposes of these Terms, a child is a person under the age of 13
    value: '13'
  restricted_uses:
  - summary: Political context
    text: in a political context (such as the promotion, advertisement or endorsement of any party, candidate, or elected official or in connection with any political party or viewpoint)
  - summary: Misleading or deceptive use
    text: You cannot use Content in a misleading or deceptive way.
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
name: Pexels
provenance_date: '2026-11-10'
provider_name: Pexels
provider_slug: pexels
slug: pexels-eligibility
source_date: '2026-11-10'
source_filename: pexels-eligibility.yml
source_heading: Eligibility
source_page: https://www.pexels.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pexels\naid: pexels\nurl: https://www.pexels.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Political context\n  text: in a political context (such as the promotion, advertisement or endorsement of any party, candidate, or\n    elected official or in connection with any political party or viewpoint)\n- summary: Misleading or deceptive use\n  text: You cannot use Content in a misleading or deceptive way.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '13'\n  text: Children may not access or use the Service. For the purposes of these Terms, a child is a person under the\n    age of 13\n"
source_yaml_url: https://artifacts.apis.io/pexels/eligibility/pexels-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pexels's own page on 2026-11-10.
synthetic: false
tags:
- Photos
- Stock Media
- Video
---
