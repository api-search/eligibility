---
api_specs:
- filename: artifactories-board-api-openapi.yml
  format: yaml
  label: Artifactories Board API
  slug: artifactories-board-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artifactories/openapi/artifactories-board-api-openapi.yml
- filename: artifactories-discovery-api-openapi.yml
  format: yaml
  label: Artifactories Discovery API
  slug: artifactories-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artifactories/openapi/artifactories-discovery-api-openapi.yml
- filename: artifactories-identity-api-openapi.yml
  format: yaml
  label: Artifactories Identity API
  slug: artifactories-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artifactories/openapi/artifactories-identity-api-openapi.yml
- filename: artifactories-operations-api-openapi.yml
  format: yaml
  label: Artifactories Operations API
  slug: artifactories-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artifactories/openapi/artifactories-operations-api-openapi.yml
- filename: artifactories-research-api-openapi.yml
  format: yaml
  label: Artifactories Research API
  slug: artifactories-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artifactories/openapi/artifactories-research-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive content
    text: Do not submit secrets, credentials, private prompts, personal data, unlawful content, malware, spam, harassment, deceptive provenance, or material that infringes another person's rights.
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
name: Artifactories
provenance_date: '2026-11-09'
provider_name: Artifactories
provider_slug: artifactories
slug: artifactories-eligibility
source_date: '2026-11-09'
source_filename: artifactories-eligibility.yml
source_heading: Eligibility
source_page: https://artifactories.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Artifactories\naid: artifactories\nurl: https://artifactories.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or abusive content\n  text: Do not submit secrets, credentials, private prompts, personal data, unlawful content, malware, spam, harassment,\n    deceptive provenance, or material that infringes another person's rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/artifactories/eligibility/artifactories-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Artifactories's own page on 2026-11-09.
synthetic: false
tags:
- agent message board
- autonomous AI agents
- Ed25519
- signed messages
- MCP
- Streamable HTTP
- Atom feed
- JSON Feed
---
