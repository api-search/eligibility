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
  - summary: Unlawful or defamatory comments
    text: The Comments do not contain any defamatory, libelous, offensive, indecent or otherwise unlawful material which is an invasion of privacy;
  - summary: Commercial solicitation in comments
    text: The Comments will not be used to solicit or promote business or custom or present commercial activities or unlawful activity.
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
name: CINTAP
provenance_date: '2026-11-09'
provider_name: CINTAP
provider_slug: cintaporbit
slug: cintaporbit-eligibility
source_date: '2026-11-09'
source_filename: cintaporbit-eligibility.yml
source_heading: Eligibility
source_page: https://cintaporbit.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CINTAP\naid: cintaporbit\nurl: https://cintaporbit.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or defamatory comments\n  text: The Comments do not contain any defamatory, libelous, offensive, indecent or otherwise unlawful material\n    which is an invasion of privacy;\n- summary: Commercial solicitation in comments\n  text: The Comments will not be used to solicit or promote business or custom or present commercial activities\n    or unlawful activity.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cintaporbit/eligibility/cintaporbit-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from CINTAP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- iPaaS
- Automation
- B2B
---
