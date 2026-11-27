---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk environments
    text: or use the Services in any high-risk environment where failure could lead to death, personal injury, or severe physical or environmental damage
  - summary: Protected health information
    text: The Services are not designed to receive or process protected health information ("PHI") under the Health Insurance Portability and Accountability Act ("HIPAA")
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
name: TablesReady
provenance_date: '2026-11-10'
provider_name: TablesReady
provider_slug: tablesready
slug: tablesready-eligibility
source_date: '2026-11-10'
source_filename: tablesready-eligibility.yml
source_heading: Eligibility
source_page: https://www.tablesready.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TablesReady\naid: tablesready\nurl: https://www.tablesready.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk environments\n  text: or use the Services in any high-risk environment where failure could lead to death, personal injury, or\n    severe physical or environmental damage\n- summary: Protected health information\n  text: The Services are not designed to receive or process protected health information (\"PHI\") under the Health\n    Insurance Portability and Accountability Act (\"HIPAA\")\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tablesready/eligibility/tablesready-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from TablesReady's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Waitlist
- Scheduling
- Restaurant
- Software-as-a-Service
---
