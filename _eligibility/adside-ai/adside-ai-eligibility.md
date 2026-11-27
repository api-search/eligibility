---
api_specs:
- filename: adside-ai-openapi.yaml
  format: yaml
  label: Multi-Source Ads API
  slug: multi-source-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adside-ai/openapi/adside-ai-openapi.yaml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for business use by individuals who are at least 18 years of age.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: The Service is intended for business use by individuals who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Fraudulent or deceptive advertising
    text: Create, distribute, or promote fraudulent, deceptive, or misleading advertisements;
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
name: Adside
provenance_date: '2026-11-09'
provider_name: Adside
provider_slug: adside-ai
slug: adside-ai-eligibility
source_date: '2026-11-09'
source_filename: adside-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.adside.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adside\naid: adside-ai\nurl: https://www.adside.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is intended for business use by individuals who are at least 18 years of age.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to these Terms.\nrestricted_uses:\n- summary: Fraudulent or deceptive advertising\n  text: Create, distribute, or promote fraudulent, deceptive, or misleading advertisements;\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended for business use by individuals who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/adside-ai/eligibility/adside-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Adside's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- Artificial Intelligence
- Marketing
- Software-as-a-Service
- Automation
---
