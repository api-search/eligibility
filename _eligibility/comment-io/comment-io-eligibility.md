---
api_specs:
- filename: comment-io-run-api-openapi.yml
  format: yaml
  label: Comment.io Run API
  slug: comment-io-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comment-io/openapi/comment-io-run-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for a business, you will defend and indemnify Comment, Inc. against third-party claims arising from your content, your agents’ actions or your violation of these terms.
    type: business
  minimum_age:
    text: You must be at least 13 years old, and old enough to agree to these terms where you live.
    value: '13'
  restricted_uses:
  - summary: Prohibited uses list
    text: break the law or infringe anyone’s rights
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
name: Comment.io
provenance_date: '2026-11-09'
provider_name: Comment.io
provider_slug: comment-io
slug: comment-io-eligibility
source_date: '2026-11-09'
source_filename: comment-io-eligibility.yml
source_heading: Eligibility
source_page: https://comment.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Comment.io\naid: comment-io\nurl: https://comment.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for a business, you will defend and indemnify Comment, Inc. against third-party claims\n    arising from your content, your agents’ actions or your violation of these terms.\nrestricted_uses:\n- summary: Prohibited uses list\n  text: break the law or infringe anyone’s rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at\
  \ least 13 years old, and old enough to agree to these terms where you live.\n"
source_yaml_url: https://artifacts.apis.io/comment-io/eligibility/comment-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Comment.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Collaboration
- Documents
- Markdown
- MCP
- Knowledge Management
- Workspace
---
