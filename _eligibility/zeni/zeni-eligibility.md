---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: use of the Zeni Services is not authorized in any jurisdiction that does not give effect to all provisions of the Terms of Service.
  entity_types:
  - text: If you are accessing and using the Zeni Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these terms.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may refuse to offer the Zeni Services to any entity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zeni
provenance_date: '2026-11-10'
provider_name: Zeni
provider_slug: zeni
slug: zeni-eligibility
source_date: '2026-11-10'
source_filename: zeni-eligibility.yml
source_heading: Eligibility
source_page: https://www.zeni.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zeni\naid: zeni\nurl: https://www.zeni.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: use of the Zeni Services is not authorized in any jurisdiction that does not give effect to all provisions\n    of the Terms of Service.\nentity_types:\n- type: business\n  text: If you are accessing and using the Zeni Services on behalf of a company (such as your employer) or other\n    legal entity, you represent and warrant that you have the authority to bind that company or other legal entity\n    to these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: We may refuse to offer the Zeni Services to any entity\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zeni/eligibility/zeni-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Zeni's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Bookkeeping
- Accounting
- Financial Operations
- Startups
- MCP
- AI Agents
---
