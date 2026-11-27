---
api_specs:
- filename: volkswagen-catalog-api-openapi.yml
  format: yaml
  label: Volkswagen Catalog API
  slug: volkswagen-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volkswagen/openapi/volkswagen-catalog-api-openapi.yml
- filename: volkswagen-configuration-api-openapi.yml
  format: yaml
  label: Volkswagen Configuration API
  slug: volkswagen-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volkswagen/openapi/volkswagen-configuration-api-openapi.yml
- filename: volkswagen-information-api-openapi.yml
  format: yaml
  label: Volkswagen Information API
  slug: volkswagen-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/volkswagen/openapi/volkswagen-information-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms and Conditions of Use govern the contractual relationship between Volkswagen and the company, which uses OKAPI
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or offensive content
    text: The User is obliged to comply with all legal provisions and not to develop content that is unlawful or otherwise offensive.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The contractual relationship in connection with the use of OKAPI begins with approval of the User's access request by Volkswagen
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Volkswagen
provenance_date: '2026-11-10'
provider_name: Volkswagen
provider_slug: volkswagen
slug: volkswagen-eligibility
source_date: '2026-11-10'
source_filename: volkswagen-eligibility.yml
source_heading: Eligibility
source_page: https://productdata.volkswagenag.com/condition-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Volkswagen\naid: volkswagen\nurl: https://productdata.volkswagenag.com/condition-of-use.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Terms and Conditions of Use govern the contractual relationship between Volkswagen and the company,\n    which uses OKAPI\nrestricted_uses:\n- summary: No unlawful or offensive content\n  text: The User is obliged to comply with all legal provisions and not to develop content that is unlawful or otherwise\n    offensive.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n\
  \  text: The contractual relationship in connection with the use of OKAPI begins with approval of the User's access\n    request by Volkswagen\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/volkswagen/eligibility/volkswagen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Volkswagen's own page on 2026-11-10.
synthetic: false
tags:
- Automobiles
- Cars
- Vehicles
- Automotive
- Vehicle Configuration
---
