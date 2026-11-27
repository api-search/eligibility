---
api_specs:
- filename: bereach-ai-openapi-generated.yml
  format: yaml
  label: BeReach API
  slug: bereach-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bereach-ai/openapi/_ae-authored/bereach-ai-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Client", "you": the individual or entity that creates an account and uses the Service.'
    type: individual
  - text: if you act for an entity, authorised to bind it.
    type: business
  minimum_age:
    text: You must be legally capable of entering into these Terms
    value: null
  restricted_uses:
  - summary: Unlawful, deceptive, harassing or unsolicited content
    text: You will not use the Service to send unlawful, deceptive, harassing or unsolicited content in breach of applicable law (including anti-spam and data-protection law), nor to infringe anyone's rights.
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
name: BeReach
provenance_date: '2026-11-09'
provider_name: BeReach
provider_slug: bereach-ai
slug: bereach-ai-eligibility
source_date: '2026-11-09'
source_filename: bereach-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bereach.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BeReach\naid: bereach-ai\nurl: https://bereach.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"Client\", \"you\": the individual or entity that creates an account and uses the Service.'\n- type: business\n  text: if you act for an entity, authorised to bind it.\nrestricted_uses:\n- summary: Unlawful, deceptive, harassing or unsolicited content\n  text: You will not use the Service to send unlawful, deceptive, harassing or unsolicited content in breach of\n    applicable law (including anti-spam and data-protection\
  \ law), nor to infringe anyone's rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be legally capable of entering into these Terms\n"
source_yaml_url: https://artifacts.apis.io/bereach-ai/eligibility/bereach-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BeReach's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Sales
- LinkedIn
- Outreach
- Automation
---
