---
api_specs:
- filename: cleverutils-com-openapi-generated.yml
  format: yaml
  label: CleverUtils API
  slug: cleverutils-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleverutils-com/openapi/_ae-authored/cleverutils-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) You are not located in a country that is subject to the United States government embargo, or that has been designated by the United States government as a "terrorist supporting" country
  entity_types:
  - text: '"You" means the individual accessing or using the Service'
    type: individual
  - text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service, as applicable.
    type: business
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
    value: '18'
  restricted_uses:
  - summary: Sanctioned countries or listed parties
    text: You are not listed on any United States government list of prohibited or restricted parties.
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
name: CleverUtils
provenance_date: '2026-11-09'
provider_name: CleverUtils
provider_slug: cleverutils-com
slug: cleverutils-com-eligibility
source_date: '2026-11-09'
source_filename: cleverutils-com-eligibility.yml
source_heading: Eligibility
source_page: https://cleverutils.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CleverUtils\naid: cleverutils-com\nurl: https://cleverutils.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) You are not located in a country that is subject to the United States\n    government embargo, or that has been designated by the United States government as a \"terrorist supporting\"\n    country\nentity_types:\n- type: individual\n  text: '\"You\" means the individual accessing or using the Service'\n- type: business\n  text: or the company, or other legal entity on behalf of which such individual is accessing or using the Service,\n\
  \    as applicable.\nrestricted_uses:\n- summary: Sanctioned countries or listed parties\n  text: You are not listed on any United States government list of prohibited or restricted parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cleverutils-com/eligibility/cleverutils-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from CleverUtils's own page on 2026-11-09.
synthetic: false
tags:
- File Conversion
- AI Features
- Multi-format
---
