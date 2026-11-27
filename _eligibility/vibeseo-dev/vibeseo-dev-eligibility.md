---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into these Terms.
    type: individual
  - text: If you use the Service on behalf of a company or other organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into these Terms.
    value: '18'
  restricted_uses:
  - summary: Illegal or minor-harming content
    text: You may not use the Service to generate or publish content for illegal products or services, content that exploits or harms minors
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
name: vibeseo-dev
provenance_date: '2026-11-10'
provider_name: vibeseo-dev
provider_slug: vibeseo-dev
slug: vibeseo-dev-eligibility
source_date: '2026-11-10'
source_filename: vibeseo-dev-eligibility.yml
source_heading: Eligibility
source_page: https://vibeseo.dev/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: vibeseo-dev\naid: vibeseo-dev\nurl: https://vibeseo.dev/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into these Terms.\n- type: business\n  text: If you use the Service on behalf of a company or other organization, you represent that you have authority\n    to bind that organization.\nrestricted_uses:\n- summary: Illegal or minor-harming content\n  text: You may not use the Service to generate or publish content for illegal products or services, content\
  \ that\n    exploits or harms minors\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into these Terms.\n"
source_yaml_url: https://artifacts.apis.io/vibeseo-dev/eligibility/vibeseo-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from vibeseo-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- SEO
- Marketing
- Automation
---
