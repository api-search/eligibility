---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: These Terms of Service apply only to individual consumer users.
    type: individual
  minimum_age:
    text: The Services are intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Competing or revenue-generating use
    text: Use the Services as part of any effort to compete with us or otherwise use the Services and/or the Content for any revenue-generating endeavor or commercial enterprise.
  - summary: Automated account creation
    text: creating user accounts by automated means or under false pretenses
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
name: Pensive
provenance_date: '2026-11-10'
provider_name: Pensive
provider_slug: pensive
slug: pensive-eligibility
source_date: '2026-11-10'
source_filename: pensive-eligibility.yml
source_heading: Eligibility
source_page: https://www.pensive.com/schools/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pensive\naid: pensive\nurl: https://www.pensive.com/schools/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: These Terms of Service apply only to individual consumer users.\nrestricted_uses:\n- summary: Competing or revenue-generating use\n  text: Use the Services as part of any effort to compete with\
  \ us or otherwise use the Services and/or the Content\n    for any revenue-generating endeavor or commercial enterprise.\n- summary: Automated account creation\n  text: creating user accounts by automated means or under false pretenses\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/pensive/eligibility/pensive-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Pensive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Artificial Intelligence
- Grading
- Assessment
- Teaching
---
