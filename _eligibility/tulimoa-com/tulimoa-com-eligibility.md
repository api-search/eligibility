---
api_specs:
- filename: tulimoa-com-openapi-generated.yml
  format: yaml
  label: tulimoa-com API
  slug: tulimoa-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tulimoa-com/openapi/_ae-authored/tulimoa-com-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only one account per natural person is permitted.
    type: individual
  - text: For merchants, legal entities under public law and special public-law funds, the place of jurisdiction is Cuxhaven.
    type: business
  minimum_age:
    text: Users must be at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: Listing content restrictions
    text: 'Not a real SaaS product: e.g. affiliate sites, lead-generation landing pages, domain parking, MLM schemes, crypto pumps, gambling, adult content, consulting or agency offerings without an own software product.'
  - summary: Security and fraud risks
    text: 'Security and fraud risks: phishing, malware distribution, distribution of malicious software, identity theft, fraud or pyramid schemes.'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: A listing goes live for free once it is approved and the Tulimoa badge is embedded on the vendor's website
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tulimoa-com
provenance_date: '2026-11-10'
provider_name: tulimoa-com
provider_slug: tulimoa-com
slug: tulimoa-com-eligibility
source_date: '2026-11-10'
source_filename: tulimoa-com-eligibility.yml
source_heading: Eligibility
source_page: https://tulimoa.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tulimoa-com\naid: tulimoa-com\nurl: https://tulimoa.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only one account per natural person is permitted.\n- type: business\n  text: For merchants, legal entities under public law and special public-law funds, the place of jurisdiction is\n    Cuxhaven.\nrestricted_uses:\n- summary: Listing content restrictions\n  text: 'Not a real SaaS product: e.g. affiliate sites, lead-generation landing pages, domain parking, MLM schemes,\n    crypto pumps, gambling, adult content, consulting\
  \ or agency offerings without an own software product.'\n- summary: Security and fraud risks\n  text: 'Security and fraud risks: phishing, malware distribution, distribution of malicious software, identity\n    theft, fraud or pyramid schemes.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: A listing goes live for free once it is approved and the Tulimoa badge is embedded on the vendor's website\nminimum_age:\n  value: '16'\n  text: Users must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/tulimoa-com/eligibility/tulimoa-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from tulimoa-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Directory
- Artificial Intelligence
- MCP
- Reviews
---
