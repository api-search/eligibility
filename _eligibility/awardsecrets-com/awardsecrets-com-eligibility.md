---
api_specs:
- filename: awardsecrets-com-api-php-api-openapi.yml
  format: yaml
  label: AwardSecrets Api.php API
  slug: awardsecrets-com-api-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awardsecrets-com/openapi/awardsecrets-com-api-php-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the API or otherwise use the Service in connection with a business, you agree to indemnify and hold harmless MetroSpaces LLC
    type: business
  minimum_age:
    text: You must be at least 18, or the age of majority where you live, to hold an account.
    value: '18'
  restricted_uses:
  - summary: No violating airline terms or law
    text: Use the Service to violate any law, or any airline's or loyalty programme's terms
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
name: AwardSecrets
provenance_date: '2026-11-09'
provider_name: AwardSecrets
provider_slug: awardsecrets-com
slug: awardsecrets-com-eligibility
source_date: '2026-11-09'
source_filename: awardsecrets-com-eligibility.yml
source_heading: Eligibility
source_page: https://awardsecrets.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AwardSecrets\naid: awardsecrets-com\nurl: https://awardsecrets.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the API or otherwise use the Service in connection with a business, you agree to indemnify and\n    hold harmless MetroSpaces LLC\nrestricted_uses:\n- summary: No violating airline terms or law\n  text: Use the Service to violate any law, or any airline's or loyalty programme's terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You\
  \ must be at least 18, or the age of majority where you live, to hold an account.\n"
source_yaml_url: https://artifacts.apis.io/awardsecrets-com/eligibility/awardsecrets-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AwardSecrets's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Awards
- Flights
- Points
- Company
---
