---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that You are not located in a country that is subject to a U.S. or European Union government embargo
  minimum_age:
    text: The use of Imerso and its Products and Documentation is intended for users who are at least 18 years old and not regarded as minors.
    value: '18'
  restricted_uses:
  - summary: Export compliance
    text: Imerso Products, including technical data, may be subject to Norwegian export laws and its associated regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Creating a User Account, using any of Imerso Products, Imerso Processing Services, Imerso Generated Data, or Imerso Documentation can be made conditional on an active Engagement Contract.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Imerso
provenance_date: '2026-11-09'
provider_name: Imerso
provider_slug: imerso
slug: imerso-eligibility
source_date: '2026-11-09'
source_filename: imerso-eligibility.yml
source_heading: Eligibility
source_page: https://www.imerso.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Imerso\naid: imerso\nurl: https://www.imerso.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that You are not located in a country that is subject to a U.S. or European Union\n    government embargo\nentity_types: []\nrestricted_uses:\n- summary: Export compliance\n  text: Imerso Products, including technical data, may be subject to Norwegian export laws and its associated regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Creating a User Account, using any of Imerso Products, Imerso Processing Services,\
  \ Imerso Generated Data,\n    or Imerso Documentation can be made conditional on an active Engagement Contract.\nminimum_age:\n  value: '18'\n  text: The use of Imerso and its Products and Documentation is intended for users who are at least 18 years old\n    and not regarded as minors.\n"
source_yaml_url: https://artifacts.apis.io/imerso/eligibility/imerso-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Imerso's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- BIM
- Reality Capture
- 3D Scanning
- Digital Twin
- Quality Control
- Artificial Intelligence
---
