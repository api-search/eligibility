---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is a business tool and is not intended for personal, household, or consumer use.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: Spam and unsolicited messaging
    text: Send unlawful, unsolicited, or bulk messages (spam)
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
name: CommSync
provenance_date: '2026-11-09'
provider_name: CommSync
provider_slug: commsync-ai
slug: commsync-ai-eligibility
source_date: '2026-11-09'
source_filename: commsync-ai-eligibility.yml
source_heading: Eligibility
source_page: https://commsync.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CommSync\naid: commsync-ai\nurl: https://commsync.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is a business tool and is not intended for personal, household, or consumer use.\nrestricted_uses:\n- summary: Spam and unsolicited messaging\n  text: Send unlawful, unsolicited, or bulk messages (spam)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/commsync-ai/eligibility/commsync-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CommSync's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Unified Inbox
- SMS
- Email
- Messaging
- Artificial Intelligence
- AI Agents
- MCP
- Webhooks
- Communications
---
