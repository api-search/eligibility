---
api_specs:
- filename: google-classroom-courses-api-openapi.yml
  format: yaml
  label: Google Classroom Courses API
  slug: google-classroom-courses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-classroom/openapi/google-classroom-courses-api-openapi.yml
- filename: google-classroom-invitations-api-openapi.yml
  format: yaml
  label: Google Classroom Invitations API
  slug: google-classroom-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-classroom/openapi/google-classroom-invitations-api-openapi.yml
- filename: google-classroom-registrations-api-openapi.yml
  format: yaml
  label: Google Classroom Registrations API
  slug: google-classroom-registrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-classroom/openapi/google-classroom-registrations-api-openapi.yml
- filename: google-classroom-user-profiles-api-openapi.yml
  format: yaml
  label: Google Classroom User Profiles API
  slug: google-classroom-user-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-classroom/openapi/google-classroom-user-profiles-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind that entity to the Terms
    type: business
  minimum_age:
    text: you are not of legal age to form a binding contract with Google
    value: legal age to form a binding contract
  restricted_uses:
  - summary: Life-critical or safety uses
    text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury, or environmental damage
  - summary: ITAR-controlled data
    text: Use the APIs to process or store any data that is subject to the International Traffic in Arms Regulations maintained by the U.S. Department of State.
  - summary: HIPAA protected health information
    text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information to Google unless you have received prior written consent to such use from Google.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may be required to provide certain information (such as identification or contact details) as part of the registration process for the APIs
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Classroom
provenance_date: '2026-11-09'
provider_name: Google Classroom
provider_slug: google-classroom
slug: google-classroom-eligibility
source_date: '2026-11-09'
source_filename: google-classroom-eligibility.yml
source_heading: Eligibility
source_page: https://developers.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Classroom\naid: google-classroom\nurl: https://developers.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the APIs on behalf of an entity, you represent and warrant that you have authority to bind\n    that entity to the Terms\nrestricted_uses:\n- summary: Life-critical or safety uses\n  text: Use the APIs for any activities where the use or failure of the APIs could lead to death, personal injury,\n    or environmental damage\n- summary: ITAR-controlled data\n  text: Use the APIs to process or\
  \ store any data that is subject to the International Traffic in Arms Regulations\n    maintained by the U.S. Department of State.\n- summary: HIPAA protected health information\n  text: you will not use the APIs for any purpose or in any manner involving transmitting protected health information\n    to Google unless you have received prior written consent to such use from Google.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you may be required to provide certain information (such as identification or contact details) as part of\n    the registration process for the APIs\nminimum_age:\n  value: legal age to form a binding contract\n  text: you are not of legal age to form a binding contract with Google\n"
source_yaml_url: https://artifacts.apis.io/google-classroom/eligibility/google-classroom-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Google Classroom's own page on 2026-11-09.
synthetic: false
tags:
- Assignments
- Classroom
- Courses
- Education
- Google
- Google Workspace
- Students
---
