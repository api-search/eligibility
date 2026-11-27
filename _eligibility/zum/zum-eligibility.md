---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: you are at least 18 years old or under the supervision of an adult
    type: individual
  minimum_age:
    text: you are at least 18 years old or under the supervision of an adult
    value: '18'
  restricted_uses:
  - summary: Minors without consent
    text: Use our Services if you are under eighteen (18) years old without your parent or legal guardian’s consent
  - summary: Unauthorized ride arrangements
    text: Arrange or attempt to arrange rides for any Passenger for whom you are not authorized to do so
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you are an “Authorized User” as identified and authenticated by (i) your Organization, in the case of Parents or Passengers
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zum
provenance_date: '2026-11-10'
provider_name: Zum
provider_slug: zum
slug: zum-eligibility
source_date: '2026-11-10'
source_filename: zum-eligibility.yml
source_heading: Eligibility
source_page: https://www.ridezum.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zum\naid: zum\nurl: https://www.ridezum.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo\nentity_types:\n- type: individual\n  text: you are at least 18 years old or under the supervision of an adult\nrestricted_uses:\n- summary: Minors without consent\n  text: Use our Services if you are under eighteen (18) years old without your parent or legal guardian’s consent\n- summary: Unauthorized ride arrangements\n  text: Arrange or attempt to arrange\
  \ rides for any Passenger for whom you are not authorized to do so\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you are an “Authorized User” as identified and authenticated by (i) your Organization, in the case of Parents\n    or Passengers\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old or under the supervision of an adult\n"
source_yaml_url: https://artifacts.apis.io/zum/eligibility/zum-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Zum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Transportation
- Student Transportation
- Mobility
- School Bus
- Fleet Management
- Electrification
- K-12 Education
---
