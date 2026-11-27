---
api_specs:
- filename: sonde-health-authentication-api-openapi.yml
  format: yaml
  label: Sonde Health Authentication API
  slug: sonde-health-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonde-health/openapi/sonde-health-authentication-api-openapi.yml
- filename: sonde-health-platform-api-openapi.yml
  format: yaml
  label: Sonde Health Platform API
  slug: sonde-health-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sonde-health/openapi/sonde-health-platform-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The page names no countries served. It says you represent that you are not located in a country subject to a U.S. Government embargo, and it names the United States and India only in the liability section.
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Not a substitute for medical advice
    text: THE MATERIALS SHOULD NOT BE USED DURING A MEDICAL EMERGENCY OR FOR THE DIAGNOSIS OR TREATMENT OF ANY MEDICAL CONDITION.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'By agreeing to these Terms, you represent and warrant to us that: (a) you are at least 18 years old; (b) you have not previously been suspended or removed from the Service'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sonde Health
provenance_date: '2026-11-10'
provider_name: Sonde Health
provider_slug: sonde-health
slug: sonde-health-eligibility
source_date: '2026-11-10'
source_filename: sonde-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.sondehealth.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sonde Health\naid: sonde-health\nurl: https://www.sondehealth.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The page names no countries served. It says you represent that you are not located in a country subject\n    to a U.S. Government embargo, and it names the United States and India only in the liability section.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: Not a substitute for medical advice\n  text: THE MATERIALS SHOULD NOT BE USED DURING A MEDICAL EMERGENCY OR FOR THE\
  \ DIAGNOSIS OR TREATMENT OF ANY MEDICAL\n    CONDITION.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'By agreeing to these Terms, you represent and warrant to us that: (a) you are at least 18 years old; (b)\n    you have not previously been suspended or removed from the Service'\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/sonde-health/eligibility/sonde-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Sonde Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Vocal Biomarkers
- Voice
- Audio
- Machine Learning
- Artificial Intelligence
- Mental Health
- Respiratory
- Remote Patient Monitoring
- Wellness
- HIPAA
---
