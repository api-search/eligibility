---
api_specs:
- filename: jid-com-monitors-api-openapi.yml
  format: yaml
  label: jid-com Monitors API
  slug: jid-com-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-monitors-api-openapi.yml
- filename: jid-com-qualify-api-openapi.yml
  format: yaml
  label: jid-com Qualify API
  slug: jid-com-qualify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-qualify-api-openapi.yml
- filename: jid-com-screen-api-openapi.yml
  format: yaml
  label: jid-com Screen API
  slug: jid-com-screen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-screen-api-openapi.yml
- filename: jid-com-search-api-openapi.yml
  format: yaml
  label: jid-com Search API
  slug: jid-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-search-api-openapi.yml
- filename: jid-com-signal-api-openapi.yml
  format: yaml
  label: jid-com Signal API
  slug: jid-com-signal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-signal-api-openapi.yml
- filename: jid-com-verify-api-openapi.yml
  format: yaml
  label: jid-com Verify API
  slug: jid-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jid-com/openapi/jid-com-verify-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You confirm that you are not, and are not acting for, a person on a US sanctions list, and that you will not use the paid service from a country or region subject to comprehensive US sanctions.
  entity_types:
  - text: You must be at least 18 years old and legally able to enter a contract to use the paid service, claim a file or create an API key.
    type: individual
  - text: If you use the service for an organisation, you accept these Terms for that organisation and confirm that you are authorised to bind it.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter a contract to use the paid service
    value: '18'
  restricted_uses:
  - summary: No FCRA consumer decisions
    text: use any part of the service as a factor in determining any individual's eligibility for credit, insurance, employment, housing or any other purpose covered by the FCRA or a similar law
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
name: jid-com
provenance_date: '2026-11-09'
provider_name: jid-com
provider_slug: jid-com
slug: jid-com-eligibility
source_date: '2026-11-09'
source_filename: jid-com-eligibility.yml
source_heading: Eligibility
source_page: https://jid.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: jid-com\naid: jid-com\nurl: https://jid.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You confirm that you are not, and are not acting for, a person on a US sanctions list, and that you will\n    not use the paid service from a country or region subject to comprehensive US sanctions.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter a contract to use the paid service, claim a\n    file or create an API key.\n- type: business\n  text: If you use the service for an organisation, you accept these Terms for that organisation\
  \ and confirm that\n    you are authorised to bind it.\nrestricted_uses:\n- summary: No FCRA consumer decisions\n  text: use any part of the service as a factor in determining any individual's eligibility for credit, insurance,\n    employment, housing or any other purpose covered by the FCRA or a similar law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter a contract to use the paid service\n"
source_yaml_url: https://artifacts.apis.io/jid-com/eligibility/jid-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from jid-com's own page on 2026-11-09.
synthetic: false
tags:
- Trust
- Artificial Intelligence
- Compliance
- Data
- Verification
---
