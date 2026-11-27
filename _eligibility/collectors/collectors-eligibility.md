---
api_specs:
- filename: collectors-psa-public-api-methods-api-openapi.yml
  format: yaml
  label: Collectors PSA Public API Methods API
  slug: collectors-psa-public-api-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collectors/openapi/collectors-psa-public-api-methods-api-openapi.yml
claim_count: 8
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - SY
    served:
    - US
    - CA
    text: WE DO NOT REPRESENT OR WARRANT THAT THE SERVICES OR ANY PART THEREOF ARE APPROPRIATE OR AVAILABLE FOR USE IN ANY PARTICULAR JURISDICTION OTHER THAN THE UNITED STATES OR CANADA. Software may not be downloaded or exported into Cuba, Iran, Syria, or any other country to which the United States has embargoed goods.
  entity_types:
  - text: The Services are available to people who have reached the age of legal majority and can form legally binding agreements under applicable law
    type: individual
  - text: If you create or use an Account on behalf of a business entity, you represent that you are authorized to act on behalf of such business and bind the business to this User Agreement.
    type: business
  minimum_age:
    text: The Services are available to people who have reached the age of legal majority
    value: age of legal majority
  restricted_uses:
  - summary: Unlawful, fraudulent or malicious use
    text: use the Services or Content for any unlawful, fraudulent, or malicious purposes
  - summary: Price manipulation
    text: manipulate the price of any item or interfere with any other user's listings
  - summary: Circumventing security
    text: circumvent or attempt to circumvent any security or authentication measures implemented by us or on our behalf
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We reserve the right to limit or modify account registration at any time and to accept or refuse registration at our discretion.
excluded_countries:
- CU
- IR
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Collectors
provenance_date: '2026-11-09'
provider_name: Collectors
provider_slug: collectors
slug: collectors-eligibility
source_date: '2026-11-09'
source_filename: collectors-eligibility.yml
source_heading: Eligibility
source_page: https://app.collectors.com/collectorsuseragreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Collectors\naid: collectors\nurl: https://app.collectors.com/collectorsuseragreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded:\n  - CU\n  - IR\n  - SY\n  text: WE DO NOT REPRESENT OR WARRANT THAT THE SERVICES OR ANY PART THEREOF ARE APPROPRIATE OR AVAILABLE FOR USE\n    IN ANY PARTICULAR JURISDICTION OTHER THAN THE UNITED STATES OR CANADA. Software may not be downloaded or exported\n    into Cuba, Iran, Syria, or any other country to which the United States has embargoed goods.\nentity_types:\n- type: individual\n  text: The Services are available to people who have reached\
  \ the age of legal majority and can form legally binding\n    agreements under applicable law\n- type: business\n  text: If you create or use an Account on behalf of a business entity, you represent that you are authorized to\n    act on behalf of such business and bind the business to this User Agreement.\nrestricted_uses:\n- summary: Unlawful, fraudulent or malicious use\n  text: use the Services or Content for any unlawful, fraudulent, or malicious purposes\n- summary: Price manipulation\n  text: manipulate the price of any item or interfere with any other user's listings\n- summary: Circumventing security\n  text: circumvent or attempt to circumvent any security or authentication measures implemented by us or on our\n    behalf\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We reserve the right to limit or modify account registration at any time and to accept or refuse registration\n    at our discretion.\nminimum_age:\n  value: age of legal majority\n\
  \  text: The Services are available to people who have reached the age of legal majority\n"
source_yaml_url: https://artifacts.apis.io/collectors/eligibility/collectors-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Collectors's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Collectibles
- Authentication
- Grading
- Trading Cards
- Verification
---
