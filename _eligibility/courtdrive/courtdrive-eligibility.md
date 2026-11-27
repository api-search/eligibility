---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: CourtDrive provides enterprise licenses to law firms based on the number of attorneys in your firm at the time of enrollment.
    type: business
  - text: are not under the age of 18
    type: individual
  minimum_age:
    text: are not under the age of 18
    value: '18'
  restricted_uses:
  - summary: Commercial purpose without authorization
    text: Use the Services for any commercial purpose other than as authorized by CourtDrive
  - summary: Unlawful goods or services
    text: Use the Services to sell any goods or services that are unlawful in the location at which the content is posted or received or the goods or services delivered
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: CourtDrive reserves the right in its sole discretion to refuse, prevent or restrict your access to Services at any time for any reason or for no reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CourtDrive
provenance_date: '2026-11-09'
provider_name: CourtDrive
provider_slug: courtdrive
slug: courtdrive-eligibility
source_date: '2026-11-09'
source_filename: courtdrive-eligibility.yml
source_heading: Eligibility
source_page: https://www.courtdrive.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CourtDrive\naid: courtdrive\nurl: https://www.courtdrive.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: CourtDrive provides enterprise licenses to law firms based on the number of attorneys in your firm at the\n    time of enrollment.\n- type: individual\n  text: are not under the age of 18\nrestricted_uses:\n- summary: Commercial purpose without authorization\n  text: Use the Services for any commercial purpose other than as authorized by CourtDrive\n- summary: Unlawful goods or services\n  text: Use the Services to\
  \ sell any goods or services that are unlawful in the location at which the content is\n    posted or received or the goods or services delivered\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: CourtDrive reserves the right in its sole discretion to refuse, prevent or restrict your access to Services\n    at any time for any reason or for no reason.\nminimum_age:\n  value: '18'\n  text: are not under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/courtdrive/eligibility/courtdrive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from CourtDrive's own page on 2026-11-09.
synthetic: false
tags:
- Legal Tech
- Artificial Intelligence
- Docketing
- Automation
- Document Management
- Company
---
