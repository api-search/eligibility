---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Services are available only to eligible users in the United States who are 18 or older.
  entity_types:
  - text: The Services are available only to eligible users in the United States who are 18 or older. Minors under the age of 18 are not permitted to use or otherwise access the Services.
    type: individual
  minimum_age:
    text: The Services are available only to eligible users in the United States who are 18 or older.
    value: '18'
  restricted_uses:
  - summary: Not for commercial use
    text: The Services are not intended for commercial use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: access to the Services may be denied depending on eligibility, and other reasons at our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lark
provenance_date: '2026-11-09'
provider_name: Lark
provider_slug: lark-technologies
slug: lark-technologies-eligibility
source_date: '2026-11-09'
source_filename: lark-technologies-eligibility.yml
source_heading: Eligibility
source_page: https://www.lark.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lark\naid: lark-technologies\nurl: https://www.lark.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Services are available only to eligible users in the United States who are 18 or older.\nentity_types:\n- type: individual\n  text: The Services are available only to eligible users in the United States who are 18 or older. Minors under\n    the age of 18 are not permitted to use or otherwise access the Services.\nrestricted_uses:\n- summary: Not for commercial use\n  text: The Services are not intended for commercial use.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: access to the Services may be denied depending on eligibility, and other reasons at our discretion.\nminimum_age:\n  value: '18'\n  text: The Services are available only to eligible users in the United States who are 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/lark-technologies/eligibility/lark-technologies-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Lark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Chronic Disease Management
- Diabetes
- Hypertension
- Weight Management
- Artificial Intelligence
- Health Coaching
- Remote Patient Monitoring
- Telehealth
---
