---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are currently offered for use only in the United States, and these Terms are written for United States residents.
  entity_types:
  - text: We invite You to use the Services for Your individual, consumer purposes ("Permitted Purposes")
    type: individual
  minimum_age:
    text: By using the Services, You agree, represent and promise that You are at least 22 years of age.
    value: '22'
  restricted_uses:
  - summary: Commercial or public purposes
    text: For any public or commercial purpose which includes use of the Services on another site or through a networked computer environment;
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
name: Happy Health
provenance_date: '2026-11-09'
provider_name: Happy Health
provider_slug: happy-health
slug: happy-health-eligibility
source_date: '2026-11-09'
source_filename: happy-health-eligibility.yml
source_heading: Eligibility
source_page: https://happysleep.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Happy Health\naid: happy-health\nurl: https://happysleep.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are currently offered for use only in the United States, and these Terms are written for United\n    States residents.\nentity_types:\n- type: individual\n  text: We invite You to use the Services for Your individual, consumer purposes (\"Permitted Purposes\")\nrestricted_uses:\n- summary: Commercial or public purposes\n  text: For any public or commercial purpose which includes use of the Services on another site or through\
  \ a networked\n    computer environment;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '22'\n  text: By using the Services, You agree, represent and promise that You are at least 22 years of age.\n"
source_yaml_url: https://artifacts.apis.io/happy-health/eligibility/happy-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Happy Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Wearables
- Remote Patient Monitoring
- Sleep
- Medical Devices
- Clinical Trials
- Consumer Health
---
