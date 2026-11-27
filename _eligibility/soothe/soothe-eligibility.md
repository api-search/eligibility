---
api_specs:
- filename: soothe-health-api-openapi.yml
  format: yaml
  label: Soothe Health API
  slug: soothe-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soothe/openapi/soothe-health-api-openapi.yml
- filename: soothe-manifest-json-api-openapi.yml
  format: yaml
  label: Soothe Manifest.json API
  slug: soothe-manifest-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soothe/openapi/soothe-manifest-json-api-openapi.yml
- filename: soothe-soothe-help-center-mirror-api-openapi.yml
  format: yaml
  label: Soothe Soothe Help Center Mirror API
  slug: soothe-soothe-help-center-mirror-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soothe/openapi/soothe-soothe-help-center-mirror-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: IF YOU ARE A UNITED STATES RESIDENT, YOU MAY SUBSCRIBE TO SoothePass ON A MONTHLY BASIS.
  entity_types:
  - text: You confirm and warrant to us that you meet the eligibility requirements set out in Section 4.3 and have the right, authority, and capacity to enter into this Agreement
    type: individual
  minimum_age:
    text: Persons under 13 are prohibited from providing personal information on our Websites or via our Apps. If you are under the age of majority in your jurisdiction of residence, you may use the Services only with the consent and involvement of your parent or legal guardian.
    value: '13'
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
name: Soothe
provenance_date: '2026-11-10'
provider_name: Soothe
provider_slug: soothe
slug: soothe-eligibility
source_date: '2026-11-10'
source_filename: soothe-eligibility.yml
source_heading: Eligibility
source_page: https://www.soothe.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Soothe\naid: soothe\nurl: https://www.soothe.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: IF YOU ARE A UNITED STATES RESIDENT, YOU MAY SUBSCRIBE TO SoothePass ON A MONTHLY BASIS.\nentity_types:\n- type: individual\n  text: You confirm and warrant to us that you meet the eligibility requirements set out in Section 4.3 and have\n    the right, authority, and capacity to enter into this Agreement\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text:\
  \ Persons under 13 are prohibited from providing personal information on our Websites or via our Apps. If\n    you are under the age of majority in your jurisdiction of residence, you may use the Services only with the\n    consent and involvement of your parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/soothe/eligibility/soothe-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Soothe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wellness
- Health and Wellness
- Massage
- Marketplace
- On-Demand Services
- Beauty
- Corporate Wellness
- Hospitality
- Consumer Services
- Local Services
- Booking
---
