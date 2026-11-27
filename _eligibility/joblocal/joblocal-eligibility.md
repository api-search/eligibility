---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Zugangsberechtigt sind Unternehmen aller Branchen.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content
    text: Ausdrücklich untersagt ist die Einstellung von rassistischen, pornographischen, menschenverachtenden, beleidigenden, zu Straftaten anleitenden und gegen die guten Sitten verstoßenden Inhalten.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Der Anbieter behält sich vor, die Registrierung einzelner Unternehmen ohne Angabe von Gründen abzulehnen.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Joblocal
provenance_date: '2026-11-09'
provider_name: Joblocal
provider_slug: joblocal
slug: joblocal-eligibility
source_date: '2026-11-09'
source_filename: joblocal-eligibility.yml
source_heading: Eligibility
source_page: https://www.joblocal.de/agb
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Joblocal\naid: joblocal\nurl: https://www.joblocal.de/agb\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Zugangsberechtigt sind Unternehmen aller Branchen.\nrestricted_uses:\n- summary: Prohibited content\n  text: Ausdrücklich untersagt ist die Einstellung von rassistischen, pornographischen, menschenverachtenden, beleidigenden,\n    zu Straftaten anleitenden und gegen die guten Sitten verstoßenden Inhalten.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Der Anbieter behält sich vor, die Registrierung einzelner\
  \ Unternehmen ohne Angabe von Gründen abzulehnen.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/joblocal/eligibility/joblocal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Joblocal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Recruiting
- Job
- HR Technology
- Job Portal
- Talent Acquisition
- Artificial Intelligence
- Labor Market
- Employment
- Germany
---
