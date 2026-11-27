---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You may use the Services only if you can form a binding contract with Pacaso and are not a person barred from accessing the Services under the laws of the United States or other applicable jurisdiction.
  entity_types:
  - text: If you are under 18 years of age you may not access or use the Services for any reason.
    type: individual
  minimum_age:
    text: If you are under 18 years of age you may not access or use the Services for any reason.
    value: '18'
  restricted_uses:
  - summary: Fractional ownership solicitation limits
    text: None of the material or opportunities presented by, or available through, Pacaso, are intended to be offerings of, or solicitations of purchasers for, any fractional ownership interest in any jurisdiction where such an offering or solicitation would be prohibited or would require registration and/or regulatory approval.
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
name: Pacaso
provenance_date: '2026-11-10'
provider_name: Pacaso
provider_slug: pacaso
slug: pacaso-eligibility
source_date: '2026-11-10'
source_filename: pacaso-eligibility.yml
source_heading: Eligibility
source_page: https://www.pacaso.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pacaso\naid: pacaso\nurl: https://www.pacaso.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You may use the Services only if you can form a binding contract with Pacaso and are not a person barred\n    from accessing the Services under the laws of the United States or other applicable jurisdiction.\nentity_types:\n- type: individual\n  text: If you are under 18 years of age you may not access or use the Services for any reason.\nrestricted_uses:\n- summary: Fractional ownership solicitation limits\n  text: None of the material or opportunities presented\
  \ by, or available through, Pacaso, are intended to be offerings\n    of, or solicitations of purchasers for, any fractional ownership interest in any jurisdiction where such an\n    offering or solicitation would be prohibited or would require registration and/or regulatory approval.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age you may not access or use the Services for any reason.\n"
source_yaml_url: https://artifacts.apis.io/pacaso/eligibility/pacaso-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pacaso's own page on 2026-11-10.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Co-Ownership
- Fractional Ownership
- Vacation Homes
- Second Homes
---
