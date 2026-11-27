---
api_specs:
- filename: snap-conversion-api-openapi.yml
  format: yaml
  label: Snap Conversion API
  slug: snap-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap/openapi/snap-conversion-api-openapi.yml
- filename: snap-events-api-openapi.yml
  format: yaml
  label: Snap Events API
  slug: snap-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap/openapi/snap-events-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These Terms apply if you live in the United States or if your principal place of business is in the United States.
  entity_types:
  - text: If you are using the Services on behalf of a business or some other entity, you represent that you are authorized to bind that business or entity to these Terms
    type: business
  - text: If you are using the Services on behalf of an entity of the U.S. Government, you agree to the Amendment to Snap Inc. Terms of Service for U.S. Government Users
    type: government
  minimum_age:
    text: Our Services are not directed to children under the age of 13 or those below the applicable minimum age
    value: '13'
  restricted_uses:
  - summary: Restricted persons
    text: you are not a person who is barred from using the Services under the laws of the United States or any other applicable jurisdiction
  - summary: Convicted sex offenders
    text: you are not a convicted sex offender
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require you to verify your age before you are allowed to use our Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Snap
provenance_date: '2026-11-10'
provider_name: Snap
provider_slug: snap
slug: snap-eligibility
source_date: '2026-11-10'
source_filename: snap-eligibility.yml
source_heading: Eligibility
source_page: https://www.snap.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Snap\naid: snap\nurl: https://www.snap.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These Terms apply if you live in the United States or if your principal place of business is in the United\n    States.\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a business or some other entity, you represent that you are authorized\n    to bind that business or entity to these Terms\n- type: government\n  text: If you are using the Services on behalf of an entity of the U.S. Government, you agree to the Amendment\n  \
  \  to Snap Inc. Terms of Service for U.S. Government Users\nrestricted_uses:\n- summary: Restricted persons\n  text: you are not a person who is barred from using the Services under the laws of the United States or any other\n    applicable jurisdiction\n- summary: Convicted sex offenders\n  text: you are not a convicted sex offender\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require you to verify your age before you are allowed to use our Services.\nminimum_age:\n  value: '13'\n  text: Our Services are not directed to children under the age of 13 or those below the applicable minimum age\n"
source_yaml_url: https://artifacts.apis.io/snap/eligibility/snap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Snap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- Marketing
- Social Media
- Augmented Reality
- Camera
- Authentication
- Identity
- Conversion
- Attribution
- SDK
---
