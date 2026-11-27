---
api_specs:
- filename: ninetyio-issues-api-openapi.yml
  format: yaml
  label: Ninety.io Issues API
  slug: ninetyio-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ninetyio/openapi/ninetyio-issues-api-openapi.yml
- filename: ninetyio-milestones-api-openapi.yml
  format: yaml
  label: Ninety.io Milestones API
  slug: ninetyio-milestones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ninetyio/openapi/ninetyio-milestones-api-openapi.yml
- filename: ninetyio-rocks-api-openapi.yml
  format: yaml
  label: Ninety.io Rocks API
  slug: ninetyio-rocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ninetyio/openapi/ninetyio-rocks-api-openapi.yml
- filename: ninetyio-scorecard-api-openapi.yml
  format: yaml
  label: Ninety.io Scorecard API
  slug: ninetyio-scorecard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ninetyio/openapi/ninetyio-scorecard-api-openapi.yml
- filename: ninetyio-teams-api-openapi.yml
  format: yaml
  label: Ninety.io Teams API
  slug: ninetyio-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ninetyio/openapi/ninetyio-teams-api-openapi.yml
- filename: ninetyio-to-dos-api-openapi.yml
  format: yaml
  label: Ninety.io To-Dos API
  slug: ninetyio-to-dos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ninetyio/openapi/ninetyio-to-dos-api-openapi.yml
- filename: ninetyio-users-api-openapi.yml
  format: yaml
  label: Ninety.io Users API
  slug: ninetyio-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ninetyio/openapi/ninetyio-users-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: You will not permit any User to access or use any part of the Services in a U.S.-embargoed country or region (currently the Crimea, Luhansk or Donetsk regions, Cuba, Iran, North Korea, or Syria)
  entity_types:
  - text: the individual or company registering for or using the Services
    type: individual
  - text: If you are accepting this agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful, infringing or privacy-violating material
    text: (c) use the Services to store or transmit infringing, libelous, or otherwise unlawful or tortious material, or to store or transmit material in violation of third-party privacy rights
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: if we are unable to verify or authenticate any information you provide to us, should we elect to engage in such verification
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ninety.io
provenance_date: '2026-11-10'
provider_name: Ninety.io
provider_slug: ninetyio
slug: ninetyio-eligibility
source_date: '2026-11-10'
source_filename: ninetyio-eligibility.yml
source_heading: Eligibility
source_page: https://www.ninety.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ninety.io\naid: ninetyio\nurl: https://www.ninety.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You will not permit any User to access or use any part of the Services in a U.S.-embargoed country or region\n    (currently the Crimea, Luhansk or Donetsk regions, Cuba, Iran, North Korea, or Syria)\nentity_types:\n- type: individual\n  text: the individual or company registering for or using the Services\n- type: business\n  text: If you are accepting this agreement on behalf of a company or other legal entity, you represent that you\n    have\
  \ the authority to bind such entity\nrestricted_uses:\n- summary: No unlawful, infringing or privacy-violating material\n  text: (c) use the Services to store or transmit infringing, libelous, or otherwise unlawful or tortious material,\n    or to store or transmit material in violation of third-party privacy rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: if we are unable to verify or authenticate any information you provide to us, should we elect to engage\n    in such verification\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ninetyio/eligibility/ninetyio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Ninety.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EOS
- Entrepreneurial Operating System
- Business Management
- Meetings
- Productivity
- Scorecards
- Team Management
- Goal Tracking
---
