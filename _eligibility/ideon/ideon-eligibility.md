---
api_specs:
- filename: ideon-ideon-api-api-openapi.yml
  format: yaml
  label: Ideon Ideon API
  slug: ideon-ideon-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ideon/openapi/ideon-ideon-api-api-openapi.yml
- filename: ideon-networks-api-openapi.yml
  format: yaml
  label: Ideon Networks API
  slug: ideon-networks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ideon/openapi/ideon-networks-api-openapi.yml
- filename: ideon-providers-api-openapi.yml
  format: yaml
  label: Ideon Providers API
  slug: ideon-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ideon/openapi/ideon-providers-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Not for diagnostic or treatment use
    text: The medical information on this site is provided as an information resource only, and is not to be used or relied on for any diagnostic or treatment purposes.
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
name: Ideon
provenance_date: '2026-11-09'
provider_name: Ideon
provider_slug: ideon
slug: ideon-eligibility
source_date: '2026-11-09'
source_filename: ideon-eligibility.yml
source_heading: Eligibility
source_page: https://ideonapi.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ideon\naid: ideon\nurl: https://ideonapi.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: These Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Not for diagnostic or treatment use\n  text: The medical information\
  \ on this site is provided as an information resource only, and is not to be used\n    or relied on for any diagnostic or treatment purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/ideon/eligibility/ideon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ideon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Benefits
- Data
- Health Tech
---
