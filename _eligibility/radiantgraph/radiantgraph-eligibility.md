---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: PleasebeadvisedtheServicesarehostedintheUnitedStates.
  entity_types:
  - text: whetherpersonallyor onbehalf of anentity("you")
    type: individual
  minimum_age:
    text: TheServicesareintendedfor userswhoareat least 18yearsold.
    value: '18'
  restricted_uses:
  - summary: Healthcare regulation
    text: However, useof thePlatformissubject toHIPAAandother state-specificlawsregulatingthehealthcareindustry.
  - summary: Sanctioned countries and parties
    text: youarenot locatedinacountrythat issubject totheUnitedStatesgovernment embargo
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Youmayberequiredtoregister tousetheServices.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RadiantGraph
provenance_date: '2026-11-10'
provider_name: RadiantGraph
provider_slug: radiantgraph
slug: radiantgraph-eligibility
source_date: '2026-11-10'
source_filename: radiantgraph-eligibility.yml
source_heading: Eligibility
source_page: https://44461861.fs1.hubspotusercontent-na1.net/hubfs/44461861/Terms%20Jan%202024.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RadiantGraph\naid: radiantgraph\nurl: https://44461861.fs1.hubspotusercontent-na1.net/hubfs/44461861/Terms%20Jan%202024.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: PleasebeadvisedtheServicesarehostedintheUnitedStates.\nentity_types:\n- type: individual\n  text: whetherpersonallyor onbehalf of anentity(\"you\")\nrestricted_uses:\n- summary: Healthcare regulation\n  text: However, useof thePlatformissubject toHIPAAandother state-specificlawsregulatingthehealthcareindustry.\n- summary: Sanctioned countries and parties\n  text: youarenot locatedinacountrythat issubject totheUnitedStatesgovernment\
  \ embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Youmayberequiredtoregister tousetheServices.\nminimum_age:\n  value: '18'\n  text: TheServicesareintendedfor userswhoareat least 18yearsold.\n"
source_yaml_url: https://artifacts.apis.io/radiantgraph/eligibility/radiantgraph-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from RadiantGraph's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Data
- Personalization
- Member Engagement
- Care Management
- Social Determinants of Health
---
