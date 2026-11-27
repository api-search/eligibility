---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Services are not available to Student Users located outside the United States.
  entity_types:
  - text: If you are a User, in order to access the Site and the Services, you represent and warrant that you are 18 years old or older or otherwise have adequate authority and capacity to consent to use the Site and the Services under applicable state laws, federal laws or the authorization of a parent or legal guardian
    type: individual
  minimum_age:
    text: you are 18 years old or older or otherwise have adequate authority and capacity to consent
    value: '18'
  restricted_uses:
  - summary: Hub Website access limited to enrolled students
    text: Access to and use of the Hub Website is limited exclusively to Student Users who are enrolled at the universities with which Mantra has contracted.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: If you do not provide this information in the manner requested within fourteen (14) days of the request, we reserve the right to suspend, discontinue, or deny your access to and use of the Site and the Services until you provide the information to us as requested.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mantra Health
provenance_date: '2026-11-10'
provider_name: Mantra Health
provider_slug: mantra-health
slug: mantra-health-eligibility
source_date: '2026-11-10'
source_filename: mantra-health-eligibility.yml
source_heading: Eligibility
source_page: https://mantrahealth.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mantra Health\naid: mantra-health\nurl: https://mantrahealth.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are not available to Student Users located outside the United States.\nentity_types:\n- type: individual\n  text: If you are a User, in order to access the Site and the Services, you represent and warrant that you are\n    18 years old or older or otherwise have adequate authority and capacity to consent to use the Site and the Services\n    under applicable state laws, federal laws or the authorization of a parent or legal guardian\n\
  restricted_uses:\n- summary: Hub Website access limited to enrolled students\n  text: Access to and use of the Hub Website is limited exclusively to Student Users who are enrolled at the universities\n    with which Mantra has contracted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: If you do not provide this information in the manner requested within fourteen (14) days of the request,\n    we reserve the right to suspend, discontinue, or deny your access to and use of the Site and the Services until\n    you provide the information to us as requested.\nminimum_age:\n  value: '18'\n  text: you are 18 years old or older or otherwise have adequate authority and capacity to consent\n"
source_yaml_url: https://artifacts.apis.io/mantra-health/eligibility/mantra-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Mantra Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Mental Health
- Telehealth
- Higher Education
- Digital Health
- Patient Engagement
- HIPAA
- GraphQL
---
