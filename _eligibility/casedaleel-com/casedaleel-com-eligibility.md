---
api_specs:
- filename: casedaleel-com-public-api-openapi.yml
  format: yaml
  label: CaseDaleel Public API
  slug: casedaleel-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/casedaleel-com/openapi/casedaleel-com-public-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    text: The platform is intended for matters connected to the United Arab Emirates. We make no claim that it is appropriate or lawful to use anywhere else
  entity_types:
  - text: You must be at least 18 and legally capable of entering a contract.
    type: individual
  - text: This section applies if you apply, through For lawyers , to receive introductions or to be listed.
    type: other
  minimum_age:
    text: You must be at least 18 and legally capable of entering a contract.
    value: '18'
  restricted_uses:
  - summary: No legal services to third parties
    text: You may not use the platform to provide legal services to third parties
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Before a professional can receive introductions or be listed, one of our administrators checks the licence number they gave by hand against the issuing authority's public register
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CaseDaleel
provenance_date: '2026-11-09'
provider_name: CaseDaleel
provider_slug: casedaleel-com
slug: casedaleel-com-eligibility
source_date: '2026-11-09'
source_filename: casedaleel-com-eligibility.yml
source_heading: Eligibility
source_page: https://casedaleel.com/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CaseDaleel\naid: casedaleel-com\nurl: https://casedaleel.com/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AE\n  excluded: []\n  text: The platform is intended for matters connected to the United Arab Emirates. We make no claim that it is\n    appropriate or lawful to use anywhere else\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally capable of entering a contract.\n- type: other\n  text: This section applies if you apply, through For lawyers , to receive introductions or to be listed.\nrestricted_uses:\n- summary: No legal services to third parties\n  text: You\
  \ may not use the platform to provide legal services to third parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Before a professional can receive introductions or be listed, one of our administrators checks the licence\n    number they gave by hand against the issuing authority's public register\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally capable of entering a contract.\n"
source_yaml_url: https://artifacts.apis.io/casedaleel-com/eligibility/casedaleel-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from CaseDaleel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- United Arab Emirates
- Lawyer Matching
- Artificial Intelligence
- Employment Law
- MCP
---
