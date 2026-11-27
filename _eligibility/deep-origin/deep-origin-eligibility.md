---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users in U.S.-embargoed countries or on the U.S. Treasury Department's Specially Designated Nationals list cannot create Accounts or engage in Services.
  minimum_age:
    text: 'Users acknowledge being at least 18 years old. Users cannot use Services if they: (a) are under 18 or lack capacity to form contracts'
    value: '18'
  restricted_uses:
  - summary: Prohibited activities
    text: Produce any content that can harm people, including biological weapons or any documentation about them
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Deep Origin may verify identity information "to help the government verify your identity, fight identity theft, and combat the funding of terrorism and other money laundering activities."
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Deep Origin
provenance_date: '2026-11-09'
provider_name: Deep Origin
provider_slug: deep-origin
slug: deep-origin-eligibility
source_date: '2026-11-09'
source_filename: deep-origin-eligibility.yml
source_heading: Eligibility
source_page: https://www.deeporigin.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deep Origin\naid: deep-origin\nurl: https://www.deeporigin.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users in U.S.-embargoed countries or on the U.S. Treasury Department's Specially Designated Nationals list\n    cannot create Accounts or engage in Services.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited activities\n  text: Produce any content that can harm people, including biological weapons or any documentation about them\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Deep Origin may verify identity information \"to help\
  \ the government verify your identity, fight identity\n    theft, and combat the funding of terrorism and other money laundering activities.\"\nminimum_age:\n  value: '18'\n  text: 'Users acknowledge being at least 18 years old. Users cannot use Services if they: (a) are under 18 or lack\n    capacity to form contracts'\n"
source_yaml_url: https://artifacts.apis.io/deep-origin/eligibility/deep-origin-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Deep Origin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Drug Discovery
- Platform
- Biotechnology
---
