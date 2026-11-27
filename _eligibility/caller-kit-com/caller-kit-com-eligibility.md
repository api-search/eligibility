---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Services.
    type: individual
  - text: If you access or use the Services on behalf of an organization, business, application, or other entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: For unlawful, fraudulent, deceptive, abusive, or harmful activities.
  - summary: Decisions prohibited by law
    text: To make decisions or take actions that are prohibited by applicable law.
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
name: caller-kit-com
provenance_date: '2026-11-09'
provider_name: caller-kit-com
provider_slug: caller-kit-com
slug: caller-kit-com-eligibility
source_date: '2026-11-09'
source_filename: caller-kit-com-eligibility.yml
source_heading: Eligibility
source_page: https://caller-kit.com/page/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: caller-kit-com\naid: caller-kit-com\nurl: https://caller-kit.com/page/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Services.\n- type: business\n  text: If you access or use the Services on behalf of an organization, business, application, or other entity,\n    you represent and warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: For unlawful, fraudulent, deceptive, abusive, or harmful activities.\n\
  - summary: Decisions prohibited by law\n  text: To make decisions or take actions that are prohibited by applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/caller-kit-com/eligibility/caller-kit-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from caller-kit-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Phone Lookup
- Caller ID
- Data Enrichment
---
