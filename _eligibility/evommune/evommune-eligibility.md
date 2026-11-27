---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is not directed at any person in any jurisdiction where (by reason of that person’s nationality, residence or otherwise) the publication or availability of the Site is prohibited.
  minimum_age:
    text: You must be at least 18 years old to use our Site.
    value: '18'
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
name: Evommune
provenance_date: '2026-11-09'
provider_name: Evommune
provider_slug: evommune
slug: evommune-eligibility
source_date: '2026-11-09'
source_filename: evommune-eligibility.yml
source_heading: Eligibility
source_page: https://www.evommune.com/wp-content/uploads/2023/12/Evommune_privacy-statement_for_website.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evommune\naid: evommune\nurl: https://www.evommune.com/wp-content/uploads/2023/12/Evommune_privacy-statement_for_website.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is not directed at any person in any jurisdiction where (by reason of that person’s nationality,\n    residence or otherwise) the publication or availability of the Site is prohibited.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/evommune/eligibility/evommune-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Evommune's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Life Sciences
- Immunology
- Drug Development
- Clinical Trials
- Healthcare
---
