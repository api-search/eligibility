---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for use in the United States. We do not guarantee that use of the Site will be available or permitted in any location other than the United States.
  minimum_age:
    text: The Site is not directed at children under the age of eighteen (18) years old. If you are under eighteen (18) years old, you must immediately stop using the Site.
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: You will not use the Site for unlawful purposes.
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
name: Allonnia
provenance_date: '2026-11-09'
provider_name: Allonnia
provider_slug: allonnia
slug: allonnia-eligibility
source_date: '2026-11-09'
source_filename: allonnia-eligibility.yml
source_heading: Eligibility
source_page: https://allonnia.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Allonnia\naid: allonnia\nurl: https://allonnia.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for use in the United States. We do not guarantee that use of the Site will be available\n    or permitted in any location other than the United States.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful purposes\n  text: You will not use the Site for unlawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is not directed at children under\
  \ the age of eighteen (18) years old. If you are under eighteen\n    (18) years old, you must immediately stop using the Site.\n"
source_yaml_url: https://artifacts.apis.io/allonnia/eligibility/allonnia-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Allonnia's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Materials
- Sustainability
- Artificial Intelligence
- Mining
---
