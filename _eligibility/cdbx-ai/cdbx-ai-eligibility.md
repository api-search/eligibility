---
api_specs:
- filename: cdbx-ai-openapi-generated.yml
  format: yaml
  label: cdbx API
  slug: cdbx-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cdbx-ai/openapi/_ae-authored/cdbx-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accessing or using CDBX, you confirm that you are at least 16 years old, have the legal capacity to enter into a binding agreement, and agree to these Terms and our Privacy Policy.
    type: individual
  - text: If you are using CDBX on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: you confirm that you are at least 16 years old
    value: '16'
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
name: cdbx
provenance_date: '2026-11-09'
provider_name: cdbx
provider_slug: cdbx-ai
slug: cdbx-ai-eligibility
source_date: '2026-11-09'
source_filename: cdbx-ai-eligibility.yml
source_heading: Eligibility
source_page: https://cdbx.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: cdbx\naid: cdbx-ai\nurl: https://cdbx.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By accessing or using CDBX, you confirm that you are at least 16 years old, have the legal capacity to enter\n    into a binding agreement, and agree to these Terms and our Privacy Policy.\n- type: business\n  text: If you are using CDBX on behalf of an organization, you represent that you have authority to bind that organization\n    to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '16'\n  text: you confirm that you are at least 16 years old\n"
source_yaml_url: https://artifacts.apis.io/cdbx-ai/eligibility/cdbx-ai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from cdbx's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Platform
- Development
- Workspace
- Collaboration
- Company
---
