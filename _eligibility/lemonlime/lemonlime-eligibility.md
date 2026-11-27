---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Services are available only to business entities organized or operating in the United States or Canada
  entity_types:
  - text: The Services are provided exclusively on a business-to-business basis.
    type: business
  - text: If Customer is a U.S. government entity or contractor, the Services are
    type: government
  minimum_age:
    text: only to individuals who are at least eighteen (18) years of age and have the legal authority to bind such an entity
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: use the Services in connection with any high-risk activity where failure or inaccuracy of the Services could lead to death, personal injury, or severe physical, environmental, or property damage
  - summary: Sanctioned destinations
    text: Customer will not export, re-export, or transfer the Services or any Output to any prohibited destination, end user, or end use
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: LemonLime may, in its discretion, verify the identity of Customer or any Authorized User
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LemonLime
provenance_date: '2026-11-09'
provider_name: LemonLime
provider_slug: lemonlime
slug: lemonlime-eligibility
source_date: '2026-11-09'
source_filename: lemonlime-eligibility.yml
source_heading: Eligibility
source_page: https://lemonlime.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LemonLime\naid: lemonlime\nurl: https://lemonlime.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Services are available only to business entities organized or operating in the United States or Canada\nentity_types:\n- type: business\n  text: The Services are provided exclusively on a business-to-business basis.\n- type: government\n  text: If Customer is a U.S. government entity or contractor, the Services are\nrestricted_uses:\n- summary: High-risk activities\n  text: use the Services in connection with any high-risk activity where failure or inaccuracy\
  \ of the Services could\n    lead to death, personal injury, or severe physical, environmental, or property damage\n- summary: Sanctioned destinations\n  text: Customer will not export, re-export, or transfer the Services or any Output to any prohibited destination,\n    end user, or end use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: LemonLime may, in its discretion, verify the identity of Customer or any Authorized User\nminimum_age:\n  value: '18'\n  text: only to individuals who are at least eighteen (18) years of age and have the legal authority to bind such\n    an entity\n"
source_yaml_url: https://artifacts.apis.io/lemonlime/eligibility/lemonlime-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from LemonLime's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Knowledge Management
- AI Agents
- Workflow Automation
- MCP
- Enterprise Software
- Software-as-a-Service
- Y Combinator
---
