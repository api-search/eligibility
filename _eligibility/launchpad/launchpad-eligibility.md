---
claim_count: 1
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
  - summary: No resale or exploitation of the service
    text: You may not sell, resell, or exploit any portion of the Launchpad service, use of the Launchpad service, or access to the Launchpad service.
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
name: Launchpad
provenance_date: '2026-11-09'
provider_name: Launchpad
provider_slug: launchpad
slug: launchpad-eligibility
source_date: '2026-11-09'
source_filename: launchpad-eligibility.yml
source_heading: Eligibility
source_page: https://canonical.com/legal/launchpad-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Launchpad\naid: launchpad\nurl: https://canonical.com/legal/launchpad-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No resale or exploitation of the service\n  text: You may not sell, resell, or exploit any portion of the Launchpad service, use of the Launchpad service,\n    or access to the Launchpad service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/launchpad/eligibility/launchpad-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Launchpad's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Collaboration
- Open Source
- Bug Tracking
- Code Hosting
---
