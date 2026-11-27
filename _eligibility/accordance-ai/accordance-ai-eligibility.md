---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer will not access or use the Services if Customer or any Authorized Users are located in any jurisdiction in which the provision of the Services ... is prohibited under U.S. or other applicable laws
  entity_types:
  - text: the customer (i) set forth on the Order Form or (ii) who registers for the Services on a trial basis
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited jurisdictions and sanctioned parties
    text: Customer represents and warrants that (a) it is not named on any U.S. government list of persons or entities prohibited from receiving U.S. exports
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
name: Accordance Ai
provenance_date: '2026-11-09'
provider_name: Accordance Ai
provider_slug: accordance-ai
slug: accordance-ai-eligibility
source_date: '2026-11-09'
source_filename: accordance-ai-eligibility.yml
source_heading: Eligibility
source_page: https://accordance.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accordance Ai\naid: accordance-ai\nurl: https://accordance.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer will not access or use the Services if Customer or any Authorized Users are located in any jurisdiction\n    in which the provision of the Services ... is prohibited under U.S. or other applicable laws\nentity_types:\n- type: business\n  text: the customer (i) set forth on the Order Form or (ii) who registers for the Services on a trial basis\nrestricted_uses:\n- summary: Prohibited jurisdictions and sanctioned parties\n  text: Customer represents and\
  \ warrants that (a) it is not named on any U.S. government list of persons or entities\n    prohibited from receiving U.S. exports\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/accordance-ai/eligibility/accordance-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Accordance Ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Tax
- Accounting
- Audit
- Agents
- Compliance
- Professional Services
---
