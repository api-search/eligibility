---
api_specs:
- filename: whoapi-domain-intelligence-api-openapi.yml
  format: yaml
  label: WhoAPI Domain Intelligence API
  slug: whoapi-domain-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoapi/openapi/whoapi-domain-intelligence-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Site if ... (iii) use of the Site or Services is prohibited by law in the country where you are located.
  entity_types:
  - text: You may not use the Site if (i) you are not at least 18 years old, or (ii) you lack legal capacity to enter into legally binding contracts
    type: individual
  minimum_age:
    text: You may not use the Site if (i) you are not at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Prohibited content and activities
    text: 'You may not use the Site or any Services provided through or in connection therewith to: (a) defame, abuse, harass, threaten or otherwise violate the legal rights'
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
name: WhoAPI
provenance_date: '2026-11-10'
provider_name: WhoAPI
provider_slug: whoapi
slug: whoapi-eligibility
source_date: '2026-11-10'
source_filename: whoapi-eligibility.yml
source_heading: Eligibility
source_page: https://whoapi.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WhoAPI\naid: whoapi\nurl: https://whoapi.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Site if ... (iii) use of the Site or Services is prohibited by law in the country where\n    you are located.\nentity_types:\n- type: individual\n  text: You may not use the Site if (i) you are not at least 18 years old, or (ii) you lack legal capacity to enter\n    into legally binding contracts\nrestricted_uses:\n- summary: Prohibited content and activities\n  text: 'You may not use the Site or any Services provided through or in connection therewith to:\
  \ (a) defame, abuse,\n    harass, threaten or otherwise violate the legal rights'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not use the Site if (i) you are not at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/whoapi/eligibility/whoapi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from WhoAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Domains
- WHOIS
- Domain Availability
- SSL
- Email Verification
- Blacklist
- Cybersecurity
- Domain Intelligence
- Screenshots
- Reputation
---
