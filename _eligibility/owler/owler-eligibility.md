---
api_specs:
- filename: owler-company-premium-api-api-openapi.yml
  format: yaml
  label: Owler Company Premium API
  slug: owler-company-premium-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/owler/openapi/owler-company-premium-api-api-openapi.yml
- filename: owler-competitor-premium-api-api-openapi.yml
  format: yaml
  label: Owler Competitor Premium API
  slug: owler-competitor-premium-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/owler/openapi/owler-competitor-premium-api-api-openapi.yml
- filename: owler-feed-api-api-openapi.yml
  format: yaml
  label: Owler Feed API
  slug: owler-feed-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/owler/openapi/owler-feed-api-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Site for use only by persons located in the United States.
  minimum_age:
    text: By using the Site, you represent that you are over the age of 13.
    value: '13'
  restricted_uses:
  - summary: Spam and deceptive addressing
    text: You may not use the Site for the purpose of gathering information for or transmitting unsolicited commercial phone calls
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
name: Owler
provenance_date: '2026-11-10'
provider_name: Owler
provider_slug: owler
slug: owler-eligibility
source_date: '2026-11-10'
source_filename: owler-eligibility.yml
source_heading: Eligibility
source_page: https://corp.owler.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Owler\naid: owler\nurl: https://corp.owler.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Site for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Spam and deceptive addressing\n  text: You may not use the Site for the purpose of gathering information for or transmitting unsolicited commercial\n    phone calls\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: By using the Site, you represent that you are over the age of\
  \ 13.\n"
source_yaml_url: https://artifacts.apis.io/owler/eligibility/owler-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Owler's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Company Intelligence
- Sales Intelligence
- Competitive Intelligence
- Business Data
- Data Licensing
- News Monitoring
- Market Research
- Firmographics
- Company Search
- Funding Data
---
