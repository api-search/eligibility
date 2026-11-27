---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Company provides this Platform for use only by persons located in the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use
    text: Your right to access and use the Platform shall be limited to non-commercial purposes unless you are otherwise expressly authorized by the Company
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
name: HubSync
provenance_date: '2026-11-09'
provider_name: HubSync
provider_slug: hubsync
slug: hubsync-eligibility
source_date: '2026-11-09'
source_filename: hubsync-eligibility.yml
source_heading: Eligibility
source_page: https://hubsync.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HubSync\naid: hubsync\nurl: https://hubsync.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Company provides this Platform for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use\n  text: Your right to access and use the Platform shall be limited to non-commercial purposes unless you are otherwise\n    expressly authorized by the Company\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hubsync/eligibility/hubsync-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from HubSync's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tax
- Accounting
- Workflow Automation
- Document Management
- E-Signature
- Professional Services
- Artificial Intelligence
- MCP
- Software-as-a-Service
---
