---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: THE SITE AND ITS INFORMATION IS INTENDED PRIMARILY FOR FRENCH USERS
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Linking to the Site
    text: The insertion of hypertext links pointing to all or part of the Site is prohibited without prior written consent from the Site Publisher.
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
name: SBS
provenance_date: '2026-11-10'
provider_name: SBS
provider_slug: soprabanking
slug: soprabanking-eligibility
source_date: '2026-11-10'
source_filename: soprabanking-eligibility.yml
source_heading: Eligibility
source_page: https://sbs-software.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SBS\naid: soprabanking\nurl: https://sbs-software.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: THE SITE AND ITS INFORMATION IS INTENDED PRIMARILY FOR FRENCH USERS\nentity_types: []\nrestricted_uses:\n- summary: Linking to the Site\n  text: The insertion of hypertext links pointing to all or part of the Site is prohibited without prior written\n    consent from the Site Publisher.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/soprabanking/eligibility/soprabanking-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from SBS's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Banking
- Software
- Fintech
---
