---
api_specs:
- filename: western-digital-authentication-api-openapi.yml
  format: yaml
  label: western-digital Authentication API
  slug: western-digital-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-digital/openapi/western-digital-authentication-api-openapi.yml
- filename: western-digital-configuration-api-openapi.yml
  format: yaml
  label: western-digital Configuration API
  slug: western-digital-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-digital/openapi/western-digital-configuration-api-openapi.yml
- filename: western-digital-device-api-openapi.yml
  format: yaml
  label: western-digital Device API
  slug: western-digital-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-digital/openapi/western-digital-device-api-openapi.yml
- filename: western-digital-files-api-openapi.yml
  format: yaml
  label: western-digital Files API
  slug: western-digital-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-digital/openapi/western-digital-files-api-openapi.yml
- filename: western-digital-search-api-openapi.yml
  format: yaml
  label: western-digital Search API
  slug: western-digital-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-digital/openapi/western-digital-search-api-openapi.yml
- filename: western-digital-sharing-api-openapi.yml
  format: yaml
  label: western-digital Sharing API
  slug: western-digital-sharing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-digital/openapi/western-digital-sharing-api-openapi.yml
- filename: western-digital-user-api-openapi.yml
  format: yaml
  label: western-digital User API
  slug: western-digital-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/western-digital/openapi/western-digital-user-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and operated by us from our offices within the United States. We make no representation that the Services are appropriate or available for Use in other locations, and access to them from territories where their contents are illegal is prohibited.
  entity_types:
  - text: you represent and warrant that you are at least the age of majority in your jurisdiction
    type: individual
  minimum_age:
    text: you represent and warrant that you are at least the age of majority in your jurisdiction
    value: age of majority
  restricted_uses:
  - summary: Military end use and certain weapons or nuclear activities
    text: nor be Used for nuclear activities, chemical biological weapons, or missile projects, unless specifically authorized by the United States government
  - summary: Sanctioned countries and parties
    text: you are not listed as a sanctioned party on the list of specially designated nationals and blocked persons maintained by OFAC
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
name: Western Digital
provenance_date: '2026-11-10'
provider_name: Western Digital
provider_slug: western-digital
slug: western-digital-eligibility
source_date: '2026-11-10'
source_filename: western-digital-eligibility.yml
source_heading: Eligibility
source_page: https://www.westerndigital.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Western Digital\naid: western-digital\nurl: https://www.westerndigital.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and operated by us from our offices within the United States. We make no representation\n    that the Services are appropriate or available for Use in other locations, and access to them from territories\n    where their contents are illegal is prohibited.\nentity_types:\n- type: individual\n  text: you represent and warrant that you are at least the age of majority in your jurisdiction\nrestricted_uses:\n\
  - summary: Military end use and certain weapons or nuclear activities\n  text: nor be Used for nuclear activities, chemical biological weapons, or missile projects, unless specifically\n    authorized by the United States government\n- summary: Sanctioned countries and parties\n  text: you are not listed as a sanctioned party on the list of specially designated nationals and blocked persons\n    maintained by OFAC\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent and warrant that you are at least the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/western-digital/eligibility/western-digital-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Western Digital's own page on 2026-11-10.
synthetic: false
tags:
- Fortune 500
---
