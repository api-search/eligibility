---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are in Australia, nothing in these terms excludes, restricts or modifies any guarantee, right or remedy you have under the Australian Consumer Law that cannot be excluded.
  entity_types:
  - text: You need to be 18 or over and running a legitimate business to use Modern.
    type: business
  minimum_age:
    text: You need to be 18 or over and running a legitimate business to use Modern.
    value: '18'
  restricted_uses:
  - summary: Spam, illegal, impersonation
    text: Do not use it to send spam, to break the law, to impersonate someone, or to do anything you would not be comfortable explaining to a customer.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Give us accurate information when you sign up and keep it up to date.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Modern
provenance_date: '2026-11-09'
provider_name: Modern
provider_slug: getmodern-ai
slug: getmodern-ai-eligibility
source_date: '2026-11-09'
source_filename: getmodern-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.getmodern.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Modern\naid: getmodern-ai\nurl: https://www.getmodern.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are in Australia, nothing in these terms excludes, restricts or modifies any guarantee, right or\n    remedy you have under the Australian Consumer Law that cannot be excluded.\nentity_types:\n- type: business\n  text: You need to be 18 or over and running a legitimate business to use Modern.\nrestricted_uses:\n- summary: Spam, illegal, impersonation\n  text: Do not use it to send spam, to break the law, to impersonate someone, or to do anything you would not be\n\
  \    comfortable explaining to a customer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Give us accurate information when you sign up and keep it up to date.\nminimum_age:\n  value: '18'\n  text: You need to be 18 or over and running a legitimate business to use Modern.\n"
source_yaml_url: https://artifacts.apis.io/getmodern-ai/eligibility/getmodern-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Modern's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Finance
- Automation
- Accounts Receivable
---
