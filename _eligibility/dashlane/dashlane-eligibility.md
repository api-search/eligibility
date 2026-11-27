---
api_specs:
- filename: dashlane-teams-api-openapi.yml
  format: yaml
  label: Dashlane Teams API
  slug: dashlane-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dashlane/openapi/dashlane-teams-api-openapi.yml
- filename: dashlane-time-api-openapi.yml
  format: yaml
  label: Dashlane Time API
  slug: dashlane-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dashlane/openapi/dashlane-time-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Services under an account provided by your employer or similar entity (a “ B2B Account ”), your use of the Services is governed by the agreement between Dashlane and your employer.
    type: business
  minimum_age:
    text: You must be old enough to agree to the Terms to use our Services.
    value: null
  restricted_uses:
  - summary: No use in embargoed countries or export violations
    text: You will not use the Services in a U.S.-embargoed country or in violation of any U.S. export law or regulation.
  - summary: No harmful content to minors or illegal use
    text: use the Services to store or distribute content that is harmful to minors
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
name: Dashlane
provenance_date: '2026-11-09'
provider_name: Dashlane
provider_slug: dashlane
slug: dashlane-eligibility
source_date: '2026-11-09'
source_filename: dashlane-eligibility.yml
source_heading: Eligibility
source_page: https://www.dashlane.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dashlane\naid: dashlane\nurl: https://www.dashlane.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Services under an account provided by your employer or similar entity (a “ B2B\n    Account ”), your use of the Services is governed by the agreement between Dashlane and your employer.\nrestricted_uses:\n- summary: No use in embargoed countries or export violations\n  text: You will not use the Services in a U.S.-embargoed country or in violation of any U.S. export law or regulation.\n- summary: No harmful\
  \ content to minors or illegal use\n  text: use the Services to store or distribute content that is harmful to minors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to agree to the Terms to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/dashlane/eligibility/dashlane-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dashlane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Password Management
- Identity
- Security
- Credential Monitoring
- Secrets Management
---
