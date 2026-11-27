---
api_specs:
- filename: altoira-handoffs-api-openapi.yml
  format: yaml
  label: AltoIRA Handoffs API
  slug: altoira-handoffs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/altoira/openapi/altoira-handoffs-api-openapi.yml
- filename: altoira-investment-api-openapi.yml
  format: yaml
  label: AltoIRA Investment API
  slug: altoira-investment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/altoira/openapi/altoira-investment-api-openapi.yml
- filename: altoira-offering-api-openapi.yml
  format: yaml
  label: AltoIRA Offering API
  slug: altoira-offering-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/altoira/openapi/altoira-offering-api-openapi.yml
- filename: altoira-user-api-openapi.yml
  format: yaml
  label: AltoIRA User API
  slug: altoira-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/altoira/openapi/altoira-user-api-openapi.yml
- filename: altoira-oauth-api-openapi.yml
  format: yaml
  label: AltoIRA OAUTH API
  slug: altoira-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/altoira/openapi/altoira-oauth-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: In the case of Investors, the Alto Platform is available only to United States residents.
  entity_types:
  - text: The Alto Platform is available only to persons who are at least eighteen (18) years old
    type: individual
  - text: and legal entities otherwise capable of forming legally binding contracts under applicable law.
    type: business
  minimum_age:
    text: at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Accredited investor offerings
    text: Certain of these investments may be offered by Issuers only to investors who are “accredited investors,” and you represent and warrant that any information submitted by you through the Alto Platform regarding your status as an accredited investor will be true and correct.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You agree to provide the personal information requested by Alto to comply with this program, including your name, address, date of birth, and tax identification number, and, upon request, to provide a readable copy of an unexpired, photo-bearing, government-issued identification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AltoIRA
provenance_date: '2026-11-09'
provider_name: AltoIRA
provider_slug: altoira
slug: altoira-eligibility
source_date: '2026-11-09'
source_filename: altoira-eligibility.yml
source_heading: Eligibility
source_page: https://www.altoira.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AltoIRA\naid: altoira\nurl: https://www.altoira.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: In the case of Investors, the Alto Platform is available only to United States residents.\nentity_types:\n- type: individual\n  text: The Alto Platform is available only to persons who are at least eighteen (18) years old\n- type: business\n  text: and legal entities otherwise capable of forming legally binding contracts under applicable law.\nrestricted_uses:\n- summary: Accredited investor offerings\n  text: Certain of these investments may be offered by Issuers\
  \ only to investors who are “accredited investors,”\n    and you represent and warrant that any information submitted by you through the Alto Platform regarding your\n    status as an accredited investor will be true and correct.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You agree to provide the personal information requested by Alto to comply with this program, including your\n    name, address, date of birth, and tax identification number, and, upon request, to provide a readable copy of\n    an unexpired, photo-bearing, government-issued identification\nminimum_age:\n  value: '18'\n  text: at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/altoira/eligibility/altoira-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from AltoIRA's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Retirement
- Self-Directed IRA
- Alternative Investments
- Private Markets
- Fintech
- Custody
- Cryptocurrency
- Wealth Management
- Investing
- Capital Raising
---
