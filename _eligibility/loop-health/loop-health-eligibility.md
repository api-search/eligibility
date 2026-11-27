---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Sorry, currently we are only providing our services to companies with 100+ employees.
    type: business
  minimum_age:
    text: A registered user, being also a parent or legal guardian of a person ‘incompetent to contract’ such as minors or persons with unsound mind, would be permitted to access and use the Sites for the purposes of procuring the Services, on behalf of such persons.
    value: null
  restricted_uses:
  - summary: Emergency appointments
    text: The Services should not be used for emergency appointment purposes and if used, You agree to take full responsibility and liability for the consequences thereof.
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
name: Loop Health
provenance_date: '2026-11-09'
provider_name: Loop Health
provider_slug: loop-health
slug: loop-health-eligibility
source_date: '2026-11-09'
source_filename: loop-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.loophealth.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Loop Health\naid: loop-health\nurl: https://www.loophealth.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Sorry, currently we are only providing our services to companies with 100+ employees.\nrestricted_uses:\n- summary: Emergency appointments\n  text: The Services should not be used for emergency appointment purposes and if used, You agree to take full responsibility\n    and liability for the consequences thereof.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: A registered user, being also a parent or legal guardian of a person ‘incompetent to contract’ such as minors\n    or persons with unsound mind, would be permitted to access and use the Sites for the purposes of procuring the\n    Services, on behalf of such persons.\n"
source_yaml_url: https://artifacts.apis.io/loop-health/eligibility/loop-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Loop Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Insurance
- Insurance
- Healthcare
- Employee Benefits
- Health Assurance
- Telehealth
- Insurtech
- India
---
