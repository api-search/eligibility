---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you have the authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a binding contract to use the Services.
    value: '18'
  restricted_uses:
  - summary: No sensitive personal data
    text: You will not upload to, or process through, the Services any sensitive personal information, including government-issued identification numbers, financial account or payment card numbers, protected health information subject to HIPAA, precise geolocation, biometric identifiers, information about children under 16
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
name: Ploy
provenance_date: '2026-11-10'
provider_name: Ploy
provider_slug: ploy
slug: ploy-eligibility
source_date: '2026-11-10'
source_filename: ploy-eligibility.yml
source_heading: Eligibility
source_page: https://ploy.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ploy\naid: ploy\nurl: https://ploy.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you\n    have the authority to bind that entity.\nrestricted_uses:\n- summary: No sensitive personal data\n  text: You will not upload to, or process through, the Services any sensitive personal information, including government-issued\n    identification numbers, financial account or payment card numbers, protected health information\
  \ subject to HIPAA,\n    precise geolocation, biometric identifiers, information about children under 16\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a binding contract to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/ploy/eligibility/ploy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ploy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketing
- Marketing Automation
- Artificial Intelligence
- AI Agents
- SEO
- Website Builder
- Growth
- Advertising
- Webhook
- CLI
- Agent Skills
---
