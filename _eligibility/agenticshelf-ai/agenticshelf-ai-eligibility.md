---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you’re accepting on behalf of a company, you confirm you have authority to bind that company.
    type: business
  minimum_age:
    text: You must be at least 18 and authorised to use your Shopify store on your organisation’s behalf.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent content
    text: Use the Service to generate content that is unlawful, fraudulent, defamatory, or infringing
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
name: agenticshelf-ai
provenance_date: '2026-11-09'
provider_name: agenticshelf-ai
provider_slug: agenticshelf-ai
slug: agenticshelf-ai-eligibility
source_date: '2026-11-09'
source_filename: agenticshelf-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.agenticshelf.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agenticshelf-ai\naid: agenticshelf-ai\nurl: https://www.agenticshelf.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you’re accepting on behalf of a company, you confirm you have authority to bind that company.\nrestricted_uses:\n- summary: Unlawful or fraudulent content\n  text: Use the Service to generate content that is unlawful, fraudulent, defamatory, or infringing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and authorised\
  \ to use your Shopify store on your organisation’s behalf.\n"
source_yaml_url: https://artifacts.apis.io/agenticshelf-ai/eligibility/agenticshelf-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from agenticshelf-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Commerce
- MCP
- Auditing
---
