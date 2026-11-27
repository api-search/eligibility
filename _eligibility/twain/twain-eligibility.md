---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Services.
    type: individual
  - text: you have the legal authority to enter into these Terms on your own behalf or on behalf of your organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: No PHI or card data
    text: you may not include personal health information (PHI) or credit card data in your content submitted to Twain.
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
name: Twain
provenance_date: '2026-11-10'
provider_name: Twain
provider_slug: twain
slug: twain-eligibility
source_date: '2026-11-10'
source_filename: twain-eligibility.yml
source_heading: Eligibility
source_page: https://www.twain.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Twain\naid: twain\nurl: https://www.twain.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services.\n- type: business\n  text: you have the legal authority to enter into these Terms on your own behalf or on behalf of your organization.\nrestricted_uses:\n- summary: No PHI or card data\n  text: you may not include personal health information (PHI) or credit card data in your content submitted to Twain.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/twain/eligibility/twain-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Twain's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Outreach
- Sales
- Marketing
---
