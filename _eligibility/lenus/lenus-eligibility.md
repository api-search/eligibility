---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - DK
    - SE
    - 'NO'
    - FI
    - GB
    - NL
    - DE
    - ES
    - US
    - CA
    text: 'Unless otherwise expressly agreed in writing by Lenus, operate a legally registered business entity in one of the following jurisdictions: Denmark, Sweden, Norway, Finland, United Kingdom, Netherlands, Germany, Spain, United States, or Canada.'
  entity_types:
  - text: Only use the Services for the purposes of carrying on a business activity and not for any personal, household or family purpose.
    type: business
  - text: Be the older of (i) 18 years old, or (ii) the age of majority in the jurisdiction where you reside.
    type: individual
  minimum_age:
    text: Be the older of (i) 18 years old, or (ii) the age of majority in the jurisdiction where you reside.
    value: '18'
  restricted_uses:
  - summary: No unlicensed medical/nutrition practice
    text: YOU SHALL NOT ENGAGE IN ANY ACTIVITIES THAT MAY CONSTITUTE THE PRACTICE OF MEDICINE, HEALTHCARE, NUTRITION OR DIETETICS IN ANY JURISDICTIONS WHERE YOU ARE NOT LICENSED TO DO SO
  - summary: No clients under 18
    text: Not to market, direct, or provide your services to Clients under the age of 18 or the age of majority in the Client’s jurisdiction
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
name: Lenus eHealth
provenance_date: '2026-11-09'
provider_name: Lenus eHealth
provider_slug: lenus
slug: lenus-eligibility
source_date: '2026-11-09'
source_filename: lenus-eligibility.yml
source_heading: Eligibility
source_page: https://www.lenusehealth.com/legal/lenus-terms-of-service-for-coaching-partners
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lenus eHealth\naid: lenus\nurl: https://www.lenusehealth.com/legal/lenus-terms-of-service-for-coaching-partners\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - DK\n  - SE\n  - 'NO'\n  - FI\n  - GB\n  - NL\n  - DE\n  - ES\n  - US\n  - CA\n  excluded: []\n  text: 'Unless otherwise expressly agreed in writing by Lenus, operate a legally registered business entity in\n    one of the following jurisdictions: Denmark, Sweden, Norway, Finland, United Kingdom, Netherlands, Germany,\n    Spain, United States, or Canada.'\nentity_types:\n- type: business\n  text: Only use the Services for the purposes of carrying\
  \ on a business activity and not for any personal, household\n    or family purpose.\n- type: individual\n  text: Be the older of (i) 18 years old, or (ii) the age of majority in the jurisdiction where you reside.\nrestricted_uses:\n- summary: No unlicensed medical/nutrition practice\n  text: YOU SHALL NOT ENGAGE IN ANY ACTIVITIES THAT MAY CONSTITUTE THE PRACTICE OF MEDICINE, HEALTHCARE, NUTRITION\n    OR DIETETICS IN ANY JURISDICTIONS WHERE YOU ARE NOT LICENSED TO DO SO\n- summary: No clients under 18\n  text: Not to market, direct, or provide your services to Clients under the age of 18 or the age of majority in\n    the Client’s jurisdiction\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be the older of (i) 18 years old, or (ii) the age of majority in the jurisdiction where you reside.\n"
source_yaml_url: https://artifacts.apis.io/lenus/eligibility/lenus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Lenus eHealth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fitness Tech
- Health
- Health Coaching
- Digital Health
- Wellness
- Fitness
- Coaching Platform
- Software-as-a-Service
- Denmark
---
