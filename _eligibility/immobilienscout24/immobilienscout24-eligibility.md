---
api_specs:
- filename: immobilienscout24-openapi-generated.yml
  format: yaml
  label: ImmobilienScout24 API
  slug: immobilienscout24-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immobilienscout24/openapi/_ae-authored/immobilienscout24-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any natural person or legal entity using the ImmoScout24 API
    type: individual
  - text: any natural person or legal entity using the ImmoScout24 API
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Content restrictions on hosting data
    text: The ImmoScout24 Data and/or retrieved parts thereof must not be placed on websites with contents glorifying violence, political, pornographic or immoral contents
  - summary: No unsolicited messages to users
    text: The Licensee must not use the information it obtains on ImmoScout24 users, in particular personal data such as address and e-mail address, to send unsolicited messages to such users
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: ImmoScout24 shall be free to decide whether or not it will accept the offer and may decline at any time a registration without the obligation to provide reasons.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ImmobilienScout24
provenance_date: '2026-11-09'
provider_name: ImmobilienScout24
provider_slug: immobilienscout24
slug: immobilienscout24-eligibility
source_date: '2026-11-09'
source_filename: immobilienscout24-eligibility.yml
source_heading: Eligibility
source_page: https://api.immobilienscout24.de/terms-of-use/en/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ImmobilienScout24\naid: immobilienscout24\nurl: https://api.immobilienscout24.de/terms-of-use/en/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: any natural person or legal entity using the ImmoScout24 API\n- type: business\n  text: any natural person or legal entity using the ImmoScout24 API\nrestricted_uses:\n- summary: Content restrictions on hosting data\n  text: The ImmoScout24 Data and/or retrieved parts thereof must not be placed on websites with contents glorifying\n    violence, political, pornographic or immoral contents\n\
  - summary: No unsolicited messages to users\n  text: The Licensee must not use the information it obtains on ImmoScout24 users, in particular personal data such\n    as address and e-mail address, to send unsolicited messages to such users\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: ImmoScout24 shall be free to decide whether or not it will accept the offer and may decline at any time\n    a registration without the obligation to provide reasons.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/immobilienscout24/eligibility/immobilienscout24-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from ImmobilienScout24's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Marketplace
- Germany
- Property Listings
- OAuth
- Search
- Construction Financing
---
