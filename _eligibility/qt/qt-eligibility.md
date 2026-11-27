---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Business Id (e.g. VAT or EIN number):'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: Customer acknowledges that the Services, or portions thereof, may be subject to export control restrictions under the applicable laws of respective countries.
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
name: Qt
provenance_date: '2026-11-10'
provider_name: Qt
provider_slug: qt
slug: qt-eligibility
source_date: '2026-11-10'
source_filename: qt-eligibility.yml
source_heading: Eligibility
source_page: https://www.qt.io/terms-conditions-2024-02
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qt\naid: qt\nurl: https://www.qt.io/terms-conditions-2024-02\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'Business Id (e.g. VAT or EIN number):'\nrestricted_uses:\n- summary: Export control restrictions\n  text: Customer acknowledges that the Services, or portions thereof, may be subject to export control restrictions\n    under the applicable laws of respective countries.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/qt/eligibility/qt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Qt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Developer Tools
- Cross-Platform
- Framework
- SDK
- IDE
- Quality Assurance
- UI Design
- Embedded
---
