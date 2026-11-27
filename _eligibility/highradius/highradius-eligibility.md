---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You agree that by using the Website, you are at least 18 years of age and you are legally able to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: Unsolicited marketing and unlawful material
    text: You agree not to (i) use the Website to process, store or transmit (x) infringing, libelous, or otherwise unlawful or tortious material, (y) any material in violation of third-party privacy rights, or (z) unsolicited marketing emails
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
name: HighRadius
provenance_date: '2026-11-09'
provider_name: HighRadius
provider_slug: highradius
slug: highradius-eligibility
source_date: '2026-11-09'
source_filename: highradius-eligibility.yml
source_heading: Eligibility
source_page: https://www.highradius.com/about/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HighRadius\naid: highradius\nurl: https://www.highradius.com/about/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unsolicited marketing and unlawful material\n  text: You agree not to (i) use the Website to process, store or transmit (x) infringing, libelous, or otherwise\n    unlawful or tortious material, (y) any material in violation of third-party privacy rights, or (z) unsolicited\n    marketing emails\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You agree that by using the Website, you are at least 18 years of age and you are legally able to enter\n    into a contract.\n"
source_yaml_url: https://artifacts.apis.io/highradius/eligibility/highradius-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from HighRadius's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Autonomous Finance
- Accounts Receivable
- Order-to-Cash
- Treasury
- Accounts Payable
- Financial Close
- ERP Integration
- CFO
---
