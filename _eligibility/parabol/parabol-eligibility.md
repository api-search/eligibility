---
api_specs:
- filename: parabol-graphql-subscriptions-asyncapi.yml
  format: yaml
  label: Parabol GraphQL API
  slug: parabol-graphql-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/parabol/asyncapi/parabol-graphql-subscriptions-asyncapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “You” refers to any individual who creates an account on the Service
    type: individual
  - text: if the Service is being used on behalf of an entity by an individual authorized to agree to such terms on behalf of such entity, then “You” refers to such entity.
    type: business
  - text: If you are a government user or otherwise accessing or using any Parabol service in a government capacity, this Amendment to Parabol Terms of Service applies to you.
    type: government
  minimum_age:
    text: You represent and warrant that You are at least 13 years of age, and no one under the age of 13 may use the Service
    value: '13'
  restricted_uses:
  - summary: Hazardous environments
    text: the Service is not designed or licensed for use in hazardous environments requiring fail-safe controls, including without limitation operation of nuclear facilities, aircraft navigation/communication systems, air traffic control, and life support or weapons systems.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Parabol assumes no duty to verify such information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Parabol
provenance_date: '2026-11-10'
provider_name: Parabol
provider_slug: parabol
slug: parabol-eligibility
source_date: '2026-11-10'
source_filename: parabol-eligibility.yml
source_heading: Eligibility
source_page: https://www.parabol.co/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Parabol\naid: parabol\nurl: https://www.parabol.co/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “You” refers to any individual who creates an account on the Service\n- type: business\n  text: if the Service is being used on behalf of an entity by an individual authorized to agree to such terms on\n    behalf of such entity, then “You” refers to such entity.\n- type: government\n  text: If you are a government user or otherwise accessing or using any Parabol service in a government capacity,\n    this Amendment\
  \ to Parabol Terms of Service applies to you.\nrestricted_uses:\n- summary: Hazardous environments\n  text: the Service is not designed or licensed for use in hazardous environments requiring fail-safe controls,\n    including without limitation operation of nuclear facilities, aircraft navigation/communication systems, air\n    traffic control, and life support or weapons systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Parabol assumes no duty to verify such information\nminimum_age:\n  value: '13'\n  text: You represent and warrant that You are at least 13 years of age, and no one under the age of 13 may use\n    the Service\n"
source_yaml_url: https://artifacts.apis.io/parabol/eligibility/parabol-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Parabol's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Agile
- Retrospectives
- Meetings
- Collaboration
- GraphQL
- Team Productivity
- Open Source
- Real-Time
---
