---
api_specs:
- filename: hooklayer-dev-openapi-generated.yml
  format: yaml
  label: hooklayer-dev API
  slug: hooklayer-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hooklayer-dev/openapi/_ae-authored/hooklayer-dev-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you sign up on behalf of a company, you confirm you have the authority to bind that company to these terms.
    type: business
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: Illegal or infringing content
    text: Generate content that is illegal, defamatory, harassing, hateful, sexually explicit involving minors, or that infringes intellectual-property rights.
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
name: hooklayer-dev
provenance_date: '2026-11-09'
provider_name: hooklayer-dev
provider_slug: hooklayer-dev
slug: hooklayer-dev-eligibility
source_date: '2026-11-09'
source_filename: hooklayer-dev-eligibility.yml
source_heading: Eligibility
source_page: https://hooklayer.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: hooklayer-dev\naid: hooklayer-dev\nurl: https://hooklayer.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you sign up on behalf of a company, you confirm you have the authority to bind that company to these\n    terms.\nrestricted_uses:\n- summary: Illegal or infringing content\n  text: Generate content that is illegal, defamatory, harassing, hateful, sexually explicit involving minors, or\n    that infringes intellectual-property rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '16'\n  text: You must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/hooklayer-dev/eligibility/hooklayer-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from hooklayer-dev's own page on 2026-11-09.
synthetic: false
tags:
- MCP
- Artificial Intelligence
- Video
- Marketing
- Analytics
- Content
---
