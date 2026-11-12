---
api_specs:
- filename: collabpls-com-agent-api-openapi.yml
  format: yaml
  label: CollabPls Agent API
  slug: collabpls-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/collabpls-com/openapi/collabpls-com-agent-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use CollabPls , you must be at least 18 years of age, possess a verified X account (blue checkmark), and agree to these Terms.
    type: individual
  minimum_age:
    text: To use CollabPls , you must be at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Safe-for-work content only
    text: CollabPls is a safe-for-work networking platform. The website does not contain nudity or explicit content, and users must not upload or display any such material on the platform.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: Users who complete this process receive an Identity Verified badge, but completion is not mandatory.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CollabPls
provenance_date: '2026-11-09'
provider_name: CollabPls
provider_slug: collabpls-com
slug: collabpls-com-eligibility
source_date: '2026-11-09'
source_filename: collabpls-com-eligibility.yml
source_heading: Eligibility
source_page: https://collabpls.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CollabPls\naid: collabpls-com\nurl: https://collabpls.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use CollabPls , you must be at least 18 years of age, possess a verified X account (blue checkmark),\n    and agree to these Terms.\nrestricted_uses:\n- summary: Safe-for-work content only\n  text: CollabPls is a safe-for-work networking platform. The website does not contain nudity or explicit content,\n    and users must not upload or display any such material on the platform.\nverification:\n  kyc: false\n  kyb: null\n\
  \  approval_required: null\n  text: Users who complete this process receive an Identity Verified badge, but completion is not mandatory.\nminimum_age:\n  value: '18'\n  text: To use CollabPls , you must be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/collabpls-com/eligibility/collabpls-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from CollabPls's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Creator Economy
- Marketplace
- Collaboration
- Scheduling
- Social Networking
- MCP
- Agents
---
