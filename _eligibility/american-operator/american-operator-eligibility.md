---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 years old.
    type: individual
  - text: You have the right, authority, and capacity to agree to these Terms on your own behalf and on behalf of any entity for whom you are acting
    type: business
  minimum_age:
    text: You are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No unauthorized commercial use
    text: You will not use the Platform for any commercial matter not otherwise authorized by American Operator.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Unless otherwise required by law, American Operator retains sole discretion to reject or accept any Visitor to participate on the Platform, for any reason or no reason at all.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: American Operator
provenance_date: '2026-11-09'
provider_name: American Operator
provider_slug: american-operator
slug: american-operator-eligibility
source_date: '2026-11-09'
source_filename: american-operator-eligibility.yml
source_heading: Eligibility
source_page: https://www.americanoperator.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: American Operator\naid: american-operator\nurl: https://www.americanoperator.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 years old.\n- type: business\n  text: You have the right, authority, and capacity to agree to these Terms on your own behalf and on behalf of\n    any entity for whom you are acting\nrestricted_uses:\n- summary: No unauthorized commercial use\n  text: You will not use the Platform for any commercial matter not otherwise authorized by American Operator.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: true\n  text: Unless otherwise required by law, American Operator retains sole discretion to reject or accept any Visitor\n    to participate on the Platform, for any reason or no reason at all.\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/american-operator/eligibility/american-operator-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from American Operator's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Small Business
- Business Acquisition
- Ownership Transition
- Operate to Own
- Private Equity
- 8vc
---
