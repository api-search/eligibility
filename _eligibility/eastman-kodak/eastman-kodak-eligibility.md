---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Information about Services may differ by region; Kodak does not warrant that a user in one region may obtain Services available in another region.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Customer Portal limited to business customers
    text: The portal ("Customer Portal") and B2B store ("Shop & Orders") are intended solely for the use of Kodak's business customers
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: have completed the Customer Portal registration and have been approved by Kodak to place orders via the Customer Portal
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Eastman Kodak
provenance_date: '2026-11-09'
provider_name: Eastman Kodak
provider_slug: eastman-kodak
slug: eastman-kodak-eligibility
source_date: '2026-11-09'
source_filename: eastman-kodak-eligibility.yml
source_heading: Eligibility
source_page: https://www.kodak.com/en/company/page/site-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eastman Kodak\naid: eastman-kodak\nurl: https://www.kodak.com/en/company/page/site-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Information about Services may differ by region; Kodak does not warrant that a user in one region may obtain\n    Services available in another region.\nentity_types: []\nrestricted_uses:\n- summary: Customer Portal limited to business customers\n  text: The portal (\"Customer Portal\") and B2B store (\"Shop & Orders\") are intended solely for the use of Kodak's\n    business customers\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: have completed the Customer Portal registration and have been approved by Kodak to place orders via the\n    Customer Portal\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eastman-kodak/eligibility/eastman-kodak-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Eastman Kodak's own page on 2026-11-09.
synthetic: false
tags:
- Printing
- Imaging
- Packaging
- Manufacturing
- Print Workflow
- Photography
- Advanced Materials
---
