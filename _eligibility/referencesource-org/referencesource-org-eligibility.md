---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Misuse of connector
    text: Do not use the connector to try to reach anything other than this site's own published records. The tools cannot do it, and attempting to make them is misuse.
  verification:
    approval_required: false
    kyb: false
    kyc: false
    text: no accounts, no payments and nothing to sign up for.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: referencesource-org
provenance_date: '2026-11-10'
provider_name: referencesource-org
provider_slug: referencesource-org
slug: referencesource-org-eligibility
source_date: '2026-11-10'
source_filename: referencesource-org-eligibility.yml
source_heading: Eligibility
source_page: https://referencesource.org/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: referencesource-org\naid: referencesource-org\nurl: https://referencesource.org/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Misuse of connector\n  text: Do not use the connector to try to reach anything other than this site's own published records. The tools\n    cannot do it, and attempting to make them is misuse.\nverification:\n  kyc: false\n  kyb: false\n  approval_required: false\n  text: no accounts, no payments and nothing to sign up for.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/referencesource-org/eligibility/referencesource-org-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from referencesource-org's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Catalog
- Reference
- Open Data
---
