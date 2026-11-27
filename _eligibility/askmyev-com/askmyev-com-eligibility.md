---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: AskMyEV is run from the United States. If you use it from another country, you are responsible for following your local laws
  entity_types:
  - text: You must be at least 18 and able to form a binding contract, and you may only connect vehicles you own or are legally authorized to manage
    type: individual
  - text: The affiliate is the human owner, who must be 18 or older and is responsible for the agent.
    type: other
  minimum_age:
    text: You must be at least 18 and able to form a binding contract
    value: '18'
  restricted_uses:
  - summary: No use while driving
    text: use the Service, or read or speak to an AI about it, in a way that distracts you while driving or operating a vehicle
  - summary: No reliance for safety-critical decisions
    text: Never rely on the Service for any decision where a mistake could cause injury, death, or damage to property
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Payouts are made only after the owner verifies their email and AskMyEV approves the account, and may require tax forms.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AskMyEV
provenance_date: '2026-11-09'
provider_name: AskMyEV
provider_slug: askmyev-com
slug: askmyev-com-eligibility
source_date: '2026-11-09'
source_filename: askmyev-com-eligibility.yml
source_heading: Eligibility
source_page: https://askmyev.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AskMyEV\naid: askmyev-com\nurl: https://askmyev.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: AskMyEV is run from the United States. If you use it from another country, you are responsible for following\n    your local laws\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to form a binding contract, and you may only connect vehicles you own or\n    are legally authorized to manage\n- type: other\n  text: The affiliate is the human owner, who must be 18 or older and is responsible for the agent.\nrestricted_uses:\n- summary: No use while driving\n\
  \  text: use the Service, or read or speak to an AI about it, in a way that distracts you while driving or operating\n    a vehicle\n- summary: No reliance for safety-critical decisions\n  text: Never rely on the Service for any decision where a mistake could cause injury, death, or damage to property\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Payouts are made only after the owner verifies their email and AskMyEV approves the account, and may require\n    tax forms.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/askmyev-com/eligibility/askmyev-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from AskMyEV's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Tesla
- Automotive
- Assistant
---
