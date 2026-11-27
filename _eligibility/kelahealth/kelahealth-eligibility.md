---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled, operated and administered by KelaHealth from our offices within the USA.
  minimum_age:
    text: KelaHealth does not knowingly collect, either online or offline, personal information from persons under the age of thirteen. If you are under 18, you may use www.kelahealth.com only with permission of a parent or guardian.
    value: '13'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: you warrant to KelaHealth that you will not use the Site for any purpose that is unlawful or prohibited by these Terms.
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
name: kelaHealth
provenance_date: '2026-11-09'
provider_name: kelaHealth
provider_slug: kelahealth
slug: kelahealth-eligibility
source_date: '2026-11-09'
source_filename: kelahealth-eligibility.yml
source_heading: Eligibility
source_page: https://www.kelahealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: kelaHealth\naid: kelahealth\nurl: https://www.kelahealth.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled, operated and administered by KelaHealth from our offices within the USA.\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: you warrant to KelaHealth that you will not use the Site for any purpose that is unlawful or prohibited\n    by these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: KelaHealth does not knowingly collect,\
  \ either online or offline, personal information from persons under\n    the age of thirteen. If you are under 18, you may use www.kelahealth.com only with permission of a parent or\n    guardian.\n"
source_yaml_url: https://artifacts.apis.io/kelahealth/eligibility/kelahealth-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from kelaHealth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Surgery
- Artificial Intelligence
- Predictive Analytics
- Perioperative
- Machine Learning
- Medical Technology
- Patient Risk
- HIPAA
---
