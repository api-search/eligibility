---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - IL
    text: The use of the Services is currently limited to Users located in the United States, Canada and in Israel.
  entity_types:
  - text: Organizations, companies, and/or businesses may not use the Services without express consent from Company.
    type: business
  minimum_age:
    text: Any use or access to the Services by anyone under the age of 18 or anyone who is not a resident of Israel, Canada or the United States is strictly prohibited
    value: '18'
  restricted_uses:
  - summary: Personal and medical use only
    text: All content shared within the Services are for personal or medical use only.
  - summary: No commercial solicitation
    text: Users with individual commercial interests may not solicit or overtly promote their products or services within the Service.
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
name: Leal Health (fka TrialJectory)
provenance_date: '2026-11-09'
provider_name: Leal Health (fka TrialJectory)
provider_slug: leal-health-fka-trialjectory
slug: leal-health-fka-trialjectory-eligibility
source_date: '2026-11-09'
source_filename: leal-health-fka-trialjectory-eligibility.yml
source_heading: Eligibility
source_page: https://www.leal.health/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Leal Health (fka TrialJectory)\naid: leal-health-fka-trialjectory\nurl: https://www.leal.health/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - IL\n  excluded: []\n  text: The use of the Services is currently limited to Users located in the United States, Canada and in Israel.\nentity_types:\n- type: business\n  text: Organizations, companies, and/or businesses may not use the Services without express consent from Company.\nrestricted_uses:\n- summary: Personal and medical use only\n  text: All content shared within the Services are for personal or medical use only.\n- summary: No\
  \ commercial solicitation\n  text: Users with individual commercial interests may not solicit or overtly promote their products or services\n    within the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access to the Services by anyone under the age of 18 or anyone who is not a resident of Israel,\n    Canada or the United States is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/leal-health-fka-trialjectory/eligibility/leal-health-fka-trialjectory-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Leal Health (fka TrialJectory)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Oncology
- Clinical Trials
- Patient Matching
- Artificial Intelligence
- Life Sciences
- Pharmaceuticals
- Decision Support
---
