---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Pandora GraphQL API
  slug: pandora-graphql-api
  spec_type: OpenAPI
  url: https://developer.pandora.com/docs/reference/graphql/
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Territory means the United States of America.
  entity_types:
  - text: This Agreement is between you, either as an individual or as part of an entity or organization
    type: individual
  - text: If you are an entity, the person who signs this Agreement on your behalf has full power and authority to enter into and bind such entity to the terms of this Agreement
    type: business
  minimum_age:
    text: If you have actual knowledge that an end user is under the age of 13, you must prevent such end users from using the Pandora Service on your Developer Application.
    value: '13'
  restricted_uses:
  - summary: Children under 13
    text: If your Developer Application is targeted to children under the age of 13, you may not use the Pandora Software.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: In order to access the Additional Materials, you must submit an application to be approved by Pandora in its sole discretion
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pandora
provenance_date: '2026-11-10'
provider_name: Pandora
provider_slug: pandora
slug: pandora-eligibility
source_date: '2026-11-10'
source_filename: pandora-eligibility.yml
source_heading: Eligibility
source_page: https://developer.pandora.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pandora\naid: pandora\nurl: https://developer.pandora.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Territory means the United States of America.\nentity_types:\n- type: individual\n  text: This Agreement is between you, either as an individual or as part of an entity or organization\n- type: business\n  text: If you are an entity, the person who signs this Agreement on your behalf has full power and authority to\n    enter into and bind such entity to the terms of this Agreement\nrestricted_uses:\n- summary: Children under 13\n  text: If your Developer\
  \ Application is targeted to children under the age of 13, you may not use the Pandora Software.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: In order to access the Additional Materials, you must submit an application to be approved by Pandora in\n    its sole discretion\nminimum_age:\n  value: '13'\n  text: If you have actual knowledge that an end user is under the age of 13, you must prevent such end users from\n    using the Pandora Service on your Developer Application.\n"
source_yaml_url: https://artifacts.apis.io/pandora/eligibility/pandora-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Pandora's own page on 2026-11-10.
synthetic: false
tags:
- Music
- Streaming
- Radio
- Podcasts
- Music Genome Project
- Personalization
- Audio
---
