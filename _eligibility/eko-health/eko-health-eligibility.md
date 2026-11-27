---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: ARE AVAILABLE TO USERS IN THE UNITED STATES OF AMERICA (USA) AND CERTAIN OTHER COUNTRIES.
  entity_types:
  - text: You must be at least 13 years of age to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an entity, organization, or company, You represent and warrant that You have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 13 years of age to use the Service.
    value: '13'
  restricted_uses:
  - summary: Intended clinical use only
    text: THE APPLICATION IS INTENDED TO BE USED AS A PART OF A PHYSICAL ASSESSMENT OR MONITORING OF A PATIENT BY HEALTHCARE PROFESSIONALS FOR DIAGNOSTIC DECISION SUPPORT.
  - summary: Not for active or continuous monitoring
    text: It is NOT intended for use in connection with active patient monitoring to allow immediate clinical action or continuous monitoring by a health care provider or the patient.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must be a registered user with Eko in order to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Eko Health
provenance_date: '2026-11-09'
provider_name: Eko Health
provider_slug: eko-health
slug: eko-health-eligibility
source_date: '2026-11-09'
source_filename: eko-health-eligibility.yml
source_heading: Eligibility
source_page: https://support.ekohealth.com/hc/en-us/articles/13156765697563-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eko Health\naid: eko-health\nurl: https://support.ekohealth.com/hc/en-us/articles/13156765697563-Terms-of-Service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: ARE AVAILABLE TO USERS IN THE UNITED STATES OF AMERICA (USA) AND CERTAIN OTHER COUNTRIES.\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to use the Service.\n- type: business\n  text: If you are using the Service on behalf of an entity, organization, or company, You represent and warrant\n    that You have the authority to bind that organization to these Terms\nrestricted_uses:\n- summary:\
  \ Intended clinical use only\n  text: THE APPLICATION IS INTENDED TO BE USED AS A PART OF A PHYSICAL ASSESSMENT OR MONITORING OF A PATIENT BY\n    HEALTHCARE PROFESSIONALS FOR DIAGNOSTIC DECISION SUPPORT.\n- summary: Not for active or continuous monitoring\n  text: It is NOT intended for use in connection with active patient monitoring to allow immediate clinical action\n    or continuous monitoring by a health care provider or the patient.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must be a registered user with Eko in order to use the Services.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/eko-health/eligibility/eko-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Eko Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Medical Devices
- Digital Health
- Telehealth
- Artificial Intelligence
- Cardiology
- Remote Patient Monitoring
- Commerce
---
