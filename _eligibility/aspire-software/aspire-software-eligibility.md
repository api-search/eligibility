---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering for an account or using the Service on behalf of an entity, organization, or company (“Corporate Entity”), you agree to the Agreement on behalf of that Corporate Entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitors barred
    text: Aspire’s direct competitors (or third-party agents acting on behalf of such direct competitors) are prohibited from accessing the Service.
  - summary: Sensitive regulated data
    text: (n) import or transfer to Aspire or the Protected Technology any data that is sensitive financial information (including credit card numbers), health information, medical information
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
name: Aspire (Powered by MindCloud)
provenance_date: '2026-11-09'
provider_name: Aspire (Powered by MindCloud)
provider_slug: aspire-software
slug: aspire-software-eligibility
source_date: '2026-11-09'
source_filename: aspire-software-eligibility.yml
source_heading: Eligibility
source_page: https://www.youraspire.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aspire (Powered by MindCloud)\naid: aspire-software\nurl: https://www.youraspire.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering for an account or using the Service on behalf of an entity, organization, or company\n    (“Corporate Entity”), you agree to the Agreement on behalf of that Corporate Entity\nrestricted_uses:\n- summary: Competitors barred\n  text: Aspire’s direct competitors (or third-party agents acting on behalf of such direct competitors) are prohibited\n\
  \    from accessing the Service.\n- summary: Sensitive regulated data\n  text: (n) import or transfer to Aspire or the Protected Technology any data that is sensitive financial information\n    (including credit card numbers), health information, medical information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aspire-software/eligibility/aspire-software-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Aspire (Powered by MindCloud)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Field Service Management
- Software
- Automation
- Landscaping
---
