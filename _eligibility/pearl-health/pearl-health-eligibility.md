---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Platform is limited exclusively to users located in states within the United States where the Platform is available. Services are not available to users located outside the United States.
  entity_types:
  - text: These Terms of Use permit you to use the Platform for your business purposes only
    type: business
  minimum_age:
    text: you represent and warrant that you are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Business purposes only
    text: These Terms of Use permit you to use the Platform for your business purposes only and not for any commercial-use outside the intended business purposes.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: You hereby authorize Pearl Health or their processing agent to make any inquiries we consider necessary to validate your identity or authenticate your identity and account Information or your company or employer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pearl Health
provenance_date: '2026-11-10'
provider_name: Pearl Health
provider_slug: pearl-health
slug: pearl-health-eligibility
source_date: '2026-11-10'
source_filename: pearl-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.pearlhealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pearl Health\naid: pearl-health\nurl: https://www.pearlhealth.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Platform is limited exclusively to users located in states within the United States\n    where the Platform is available. Services are not available to users located outside the United States.\nentity_types:\n- type: business\n  text: These Terms of Use permit you to use the Platform for your business purposes only\nrestricted_uses:\n- summary: Business purposes only\n  text: These Terms of Use permit you to use the Platform\
  \ for your business purposes only and not for any commercial-use\n    outside the intended business purposes.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: You hereby authorize Pearl Health or their processing agent to make any inquiries we consider necessary\n    to validate your identity or authenticate your identity and account Information or your company or employer.\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/pearl-health/eligibility/pearl-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Pearl Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Value-Based Care
- Medicare
- Health Systems
- Primary Care
- Population Health
- Health Analytics
---
