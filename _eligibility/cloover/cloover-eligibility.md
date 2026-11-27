---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - GB
    - US
    served: []
    text: access to the Website does not constitute an invitation or advice in the United Kingdom or the United States, and none of the services offered on the Website are intended for persons residing in those states.
  entity_types:
  - text: natural persons who are at least 18 years old and fully legally competent
    type: individual
  - text: duly established legal entities (represented by a natural person who creates the account and confirms that he/she has the necessary authority to do so)
    type: business
  minimum_age:
    text: natural persons who are at least 18 years old and fully legally competent
    value: '18'
  restricted_uses:
  - summary: Country or individual access restrictions
    text: Access to the Website may be restricted for certain individuals or countries, either through general prohibitions or through specific marketing rules set at Cloover’s discretion.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: After creating the member account, the User must complete the accreditation procedure in accordance with the requirements of CLOOVER and its partners in order to access the services offered on the Website.
excluded_countries:
- GB
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cloover
provenance_date: '2026-11-09'
provider_name: Cloover
provider_slug: cloover
slug: cloover-eligibility
source_date: '2026-11-09'
source_filename: cloover-eligibility.yml
source_heading: Eligibility
source_page: https://www.cloover.com/en/nutzungsbedingungen
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cloover\naid: cloover\nurl: https://www.cloover.com/en/nutzungsbedingungen\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - GB\n  - US\n  text: access to the Website does not constitute an invitation or advice in the United Kingdom or the United States,\n    and none of the services offered on the Website are intended for persons residing in those states.\nentity_types:\n- type: individual\n  text: natural persons who are at least 18 years old and fully legally competent\n- type: business\n  text: duly established legal entities (represented by a natural person who creates the account and\
  \ confirms that\n    he/she has the necessary authority to do so)\nrestricted_uses:\n- summary: Country or individual access restrictions\n  text: Access to the Website may be restricted for certain individuals or countries, either through general prohibitions\n    or through specific marketing rules set at Cloover’s discretion.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: After creating the member account, the User must complete the accreditation procedure in accordance with\n    the requirements of CLOOVER and its partners in order to access the services offered on the Website.\nminimum_age:\n  value: '18'\n  text: natural persons who are at least 18 years old and fully legally competent\n"
source_yaml_url: https://artifacts.apis.io/cloover/eligibility/cloover-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cloover's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Climate
- Renewable Energy
- Solar
- Energy
- Embedded Finance
- Installers
---
