---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may only use the Service in jurisdictions authorized by us. You represent and warrant that (a) you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: THE SERVICE IS NOT AVAILABLE TO INDIVIDUALS UNDER THE AGE OF 16.
    type: individual
  - text: If you are using the Service, opening an account or accepting these Terms on behalf of a legal entity
    type: business
  minimum_age:
    text: THE SERVICE IS NOT AVAILABLE TO INDIVIDUALS UNDER THE AGE OF 16.
    value: '16'
  restricted_uses:
  - summary: Sexually explicit content
    text: content containing explicit nudity, pornography, or sexually explicit material
  - summary: Violent or graphic content
    text: graphic content depicting acts of cruelty, violence, assault, or harm towards humans or animals
  - summary: Illegal goods or activities
    text: content promoting or facilitating the sale or distribution of illegal or prohibited goods or services, including drugs, weapons, or similar items
  - summary: Generative AI output restrictions
    text: Upload, generate, or distribute content that promotes violence or incites hatred against individuals or groups
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
name: Loomly
provenance_date: '2026-11-09'
provider_name: Loomly
provider_slug: loomly
slug: loomly-eligibility
source_date: '2026-11-09'
source_filename: loomly-eligibility.yml
source_heading: Eligibility
source_page: https://www.loomly.com/terms/en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Loomly\naid: loomly\nurl: https://www.loomly.com/terms/en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may only use the Service in jurisdictions authorized by us. You represent and warrant that (a) you are\n    not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: THE SERVICE IS NOT AVAILABLE TO INDIVIDUALS UNDER THE AGE OF 16.\n- type: business\n  text: If you are using the Service, opening an account or accepting these Terms on behalf of a legal entity\nrestricted_uses:\n- summary: Sexually explicit\
  \ content\n  text: content containing explicit nudity, pornography, or sexually explicit material\n- summary: Violent or graphic content\n  text: graphic content depicting acts of cruelty, violence, assault, or harm towards humans or animals\n- summary: Illegal goods or activities\n  text: content promoting or facilitating the sale or distribution of illegal or prohibited goods or services, including\n    drugs, weapons, or similar items\n- summary: Generative AI output restrictions\n  text: Upload, generate, or distribute content that promotes violence or incites hatred against individuals or\n    groups\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: THE SERVICE IS NOT AVAILABLE TO INDIVIDUALS UNDER THE AGE OF 16.\n"
source_yaml_url: https://artifacts.apis.io/loomly/eligibility/loomly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 8 quoted statements, read from Loomly's own page on 2026-11-09.
synthetic: false
tags:
- Social Media
- Content Calendar
- Scheduling
- Approval Workflows
- Analytics
- Brand Management
- Publishing
- Community Management
- Marketing
- Social Media Management
---
