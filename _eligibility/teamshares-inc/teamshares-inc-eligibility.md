---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States.
  entity_types:
  - text: If you are an entity, organization, or company, the individual accessing or using this Site on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Access where illegal
    text: Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.
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
name: Teamshares
provenance_date: '2026-11-10'
provider_name: Teamshares
provider_slug: teamshares-inc
slug: teamshares-inc-eligibility
source_date: '2026-11-10'
source_filename: teamshares-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.teamshares.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Teamshares\naid: teamshares-inc\nurl: https://www.teamshares.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States.\nentity_types:\n- type: business\n  text: If you are an entity, organization, or company, the individual accessing or using this Site on your behalf\n    represents and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Access where\
  \ illegal\n  text: Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/teamshares-inc/eligibility/teamshares-inc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Teamshares's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Employee Ownership
- Small Business
- Acquisition
- Financial Services
---
