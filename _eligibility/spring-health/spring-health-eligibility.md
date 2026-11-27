---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled, hosted and operated from the United States. The Services may not be appropriate or available for use in some non-U.S. jurisdictions.
  minimum_age:
    text: BY USING THE SERVICES, YOU AFFIRM THAT YOU ARE OF LEGAL AGE TO ENTER INTO THIS AGREEMENT.
    value: legal age
  restricted_uses:
  - summary: Not medical advice
    text: The Services, including, without limitation, the Questionnaires and the results of the Questionnaires, are provided by Spring Health and its licensors for informational purposes only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to register to use all or part of the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Spring Health
provenance_date: '2026-11-10'
provider_name: Spring Health
provider_slug: spring-health
slug: spring-health-eligibility
source_date: '2026-11-10'
source_filename: spring-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.springhealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spring Health\naid: spring-health\nurl: https://www.springhealth.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled, hosted and operated from the United States. The Services may not be appropriate\n    or available for use in some non-U.S. jurisdictions.\nentity_types: []\nrestricted_uses:\n- summary: Not medical advice\n  text: The Services, including, without limitation, the Questionnaires and the results of the Questionnaires, are\n    provided by Spring Health and its licensors for informational purposes only.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: You may need to register to use all or part of the Services.\nminimum_age:\n  value: legal age\n  text: BY USING THE SERVICES, YOU AFFIRM THAT YOU ARE OF LEGAL AGE TO ENTER INTO THIS AGREEMENT.\n"
source_yaml_url: https://artifacts.apis.io/spring-health/eligibility/spring-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Spring Health's own page on 2026-11-10.
synthetic: false
tags:
- Mental Health
- Behavioral Health
- Employee Benefits
- Employee Assistance Program
- EAP
- Health Plans
- Healthcare
- Therapy
- Medication Management
- Coaching
- Care Navigation
- Digital Health
- Wellbeing
- Workforce Health
- Generative AI
---
