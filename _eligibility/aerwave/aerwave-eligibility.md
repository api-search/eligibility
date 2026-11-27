---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To be a Member Account holder you must either be: (i) 18 years or older, if an individual'
    type: individual
  - text: or (ii) be a corporation, partnership, or other legal entity duly formed (and incorporated if applicable) in good standing
    type: business
  - source: https://www.aerwave.com/acceptable-use-policy
    text: Aerwave Services are provided to you for your reasonable, personal, non-commercial use only
    type: individual
  - source: https://www.aerwave.com/acceptable-use-policy
    text: if you have a business account with Aerwave, you may use the Aerwave Services for your internal business operations
    type: business
  minimum_age:
    text: 18 years or older, if an individual
    value: '18'
  restricted_uses:
  - summary: Export restrictions on software
    text: None of the software or underlying information or technology may be downloaded or otherwise exported or re-exported (a) into (or to a national or resident of) any country to which the United States has embargoed goods
  - source: https://www.aerwave.com/acceptable-use-policy
    summary: No resale of Services
    text: Aerwave prohibits the resale of, or to permit or facilitate the use of, the Services, in whole or in part, directly or indirectly, by other persons or entities
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
name: Aerwave
provenance_date: '2026-11-09'
provider_name: Aerwave
provider_slug: aerwave
slug: aerwave-eligibility
source_date: '2026-11-09'
source_filename: aerwave-eligibility.yml
source_heading: Eligibility
source_page: https://www.aerwave.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aerwave\naid: aerwave\nurl: https://www.aerwave.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://www.aerwave.com/acceptable-use-policy\n  - https://www.aerwave.com/terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'To be a Member Account holder you must either be: (i) 18 years or older, if an individual'\n- type: business\n  text: or (ii) be a corporation, partnership, or other legal entity duly formed (and incorporated if applicable)\n    in good standing\n- type: individual\n  text: Aerwave Services\
  \ are provided to you for your reasonable, personal, non-commercial use only\n  source: https://www.aerwave.com/acceptable-use-policy\n- type: business\n  text: if you have a business account with Aerwave, you may use the Aerwave Services for your internal business\n    operations\n  source: https://www.aerwave.com/acceptable-use-policy\nrestricted_uses:\n- summary: Export restrictions on software\n  text: None of the software or underlying information or technology may be downloaded or otherwise exported or\n    re-exported (a) into (or to a national or resident of) any country to which the United States has embargoed\n    goods\n- summary: No resale of Services\n  text: Aerwave prohibits the resale of, or to permit or facilitate the use of, the Services, in whole or in part,\n    directly or indirectly, by other persons or entities\n  source: https://www.aerwave.com/acceptable-use-policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: 18 years or older, if an individual\n"
source_yaml_url: https://artifacts.apis.io/aerwave/eligibility/aerwave-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Aerwave's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Managed WiFi
- Multifamily
- Real Estate
- Telecommunications
- Internet Service Provider
- Connectivity
- Smart Buildings
- PropTech
---
