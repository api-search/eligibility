---
claim_count: 1
description: ''
doc:
  countries:
    excluded:
    - UN non-member states
    - OFAC sanctioned countries
    served: []
    text: The Customer warrants it shall not import, distribute, deploy and use the Equipment in any non-member state of the United Nations or any country subject to any sanctions program of the Office of Foreign Assets Control (OFAC)
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- UN non-member states
- OFAC sanctioned countries
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LiquidStack
provenance_date: '2026-11-09'
provider_name: LiquidStack
provider_slug: liquidstack
slug: liquidstack-eligibility
source_date: '2026-11-09'
source_filename: liquidstack-eligibility.yml
source_heading: Eligibility
source_page: https://liquidstack.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LiquidStack\naid: liquidstack\nurl: https://liquidstack.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - UN non-member states\n  - OFAC sanctioned countries\n  text: The Customer warrants it shall not import, distribute, deploy and use the Equipment in any non-member state\n    of the United Nations or any country subject to any sanctions program of the Office of Foreign Assets Control\n    (OFAC)\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/liquidstack/eligibility/liquidstack-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from LiquidStack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Center
- Liquid Cooling
- Immersion Cooling
- Thermal Management
- Infrastructure
- Hardware
- High Performance Computing
- Artificial Intelligence
- Energy Efficiency
- Sustainability
- Edge Computing
---
