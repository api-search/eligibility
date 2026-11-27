---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Website is intended for a global audience
  entity_types:
  - text: 'Certain sections of this Website may be intended exclusively for: Healthcare professionals (HCPs)'
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No offer or solicitation where restricted
    text: Nothing on this Website should be interpreted as an offer or solicitation of products or services in any jurisdiction where such activity is restricted or prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to HCP-only information may be subject to confirmation of professional status, gating requirements and local regulatory requirements.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pharming Group
provenance_date: '2026-11-10'
provider_name: Pharming Group
provider_slug: pharming-group
slug: pharming-group-eligibility
source_date: '2026-11-10'
source_filename: pharming-group-eligibility.yml
source_heading: Eligibility
source_page: https://www.pharming.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pharming Group\naid: pharming-group\nurl: https://www.pharming.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Website is intended for a global audience\nentity_types:\n- type: other\n  text: 'Certain sections of this Website may be intended exclusively for: Healthcare professionals (HCPs)'\nrestricted_uses:\n- summary: No offer or solicitation where restricted\n  text: Nothing on this Website should be interpreted as an offer or solicitation of products or services in any\n    jurisdiction where such activity is restricted or prohibited.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: Access to HCP-only information may be subject to confirmation of professional status, gating requirements\n    and local regulatory requirements.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pharming-group/eligibility/pharming-group-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Pharming Group's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- RNA Therapeutics
- Pharma
- Innovation
---
