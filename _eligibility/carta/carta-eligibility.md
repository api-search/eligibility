---
api_specs:
- filename: carta-openapi-generated.yml
  format: yaml
  label: Carta API
  slug: carta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carta/openapi/_ae-authored/carta-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You represent and warrant that You are not: (a) located in a country that is subject to a U.S. government embargo'
  entity_types:
  - text: Each registration is for a single natural person user only, unless otherwise expressly agreed by Carta.
    type: individual
  - text: If You access the Content on behalf of any organization, Your organization will be bound to these Terms and be liable for any breach by You
    type: business
  minimum_age:
    text: The Content is not intended for use or access by any individual under the age of thirteen (13) years
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: use or access the Content for any unlawful, fraudulent, deceptive, tortious, malicious, or otherwise harmful or injurious purpose
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Carta uses Entrust for identity checks in connection with its regulatory and compliance requirements
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Carta
provenance_date: '2026-11-09'
provider_name: Carta
provider_slug: carta
slug: carta-eligibility
source_date: '2026-11-09'
source_filename: carta-eligibility.yml
source_heading: Eligibility
source_page: https://carta.com/legal/terms-agreements/terms-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carta\naid: carta\nurl: https://carta.com/legal/terms-agreements/terms-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'You represent and warrant that You are not: (a) located in a country that is subject to a U.S. government\n    embargo'\nentity_types:\n- type: individual\n  text: Each registration is for a single natural person user only, unless otherwise expressly agreed by Carta.\n- type: business\n  text: If You access the Content on behalf of any organization, Your organization will be bound to these Terms\n    and be liable for any breach by You\nrestricted_uses:\n\
  - summary: Unlawful or harmful use\n  text: use or access the Content for any unlawful, fraudulent, deceptive, tortious, malicious, or otherwise harmful\n    or injurious purpose\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Carta uses Entrust for identity checks in connection with its regulatory and compliance requirements\nminimum_age:\n  value: '13'\n  text: The Content is not intended for use or access by any individual under the age of thirteen (13) years\n"
source_yaml_url: https://artifacts.apis.io/carta/eligibility/carta-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Carta's own page on 2026-11-09.
synthetic: false
tags:
- Equity Management
- Cap Table
- 409A Valuations
- Fund Administration
- Employee Equity
- Investor Portfolio
- Private Markets
- Fintech
- Startups
---
