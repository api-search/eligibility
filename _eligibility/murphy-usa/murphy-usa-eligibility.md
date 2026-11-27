---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We control and operate the Services from our headquarters in the United States and the entirety of the Services may not be appropriate or available for use in other locations.
  entity_types:
  - text: We invite you to use the Services for individual and informational purposes.
    type: individual
  - text: if you are a government entity, the Commercial Computer Software and Commercial Computer Software Documentation are being licensed to U.S. Government end-users
    type: government
  minimum_age:
    text: By using the Services, you promise that you are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Commercial use
    text: For any commercial purpose or through a networked computer environment;
  - summary: Sanctioned jurisdictions
    text: you are not located in a country that is subject to a U.S. Government embargo
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Once you submit the required registration information, we alone will determine whether to approve your proposed account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Murphy USA
provenance_date: '2026-11-10'
provider_name: Murphy USA
provider_slug: murphy-usa
slug: murphy-usa-eligibility
source_date: '2026-11-10'
source_filename: murphy-usa-eligibility.yml
source_heading: Eligibility
source_page: https://www.murphyusa.com/murphyusa/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Murphy USA\naid: murphy-usa\nurl: https://www.murphyusa.com/murphyusa/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: We control and operate the Services from our headquarters in the United States and the entirety of the Services\n    may not be appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: We invite you to use the Services for individual and informational purposes.\n- type: government\n  text: if you are a government entity, the Commercial Computer Software and Commercial Computer Software Documentation\n\
  \    are being licensed to U.S. Government end-users\nrestricted_uses:\n- summary: Commercial use\n  text: For any commercial purpose or through a networked computer environment;\n- summary: Sanctioned jurisdictions\n  text: you are not located in a country that is subject to a U.S. Government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Once you submit the required registration information, we alone will determine whether to approve your proposed\n    account.\nminimum_age:\n  value: '13'\n  text: By using the Services, you promise that you are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/murphy-usa/eligibility/murphy-usa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Murphy USA's own page on 2026-11-10.
synthetic: false
tags:
- Fortune 500
- Fuel Retail
- Convenience Stores
- Gas Stations
- Retail
- Loyalty Programs
- Energy
---
