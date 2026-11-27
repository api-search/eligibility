---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to our Services is administered in the United States and is intended for users in the US.
  entity_types:
  - text: You are not eligible to use our Services (including obtaining a Credential or entering into a User Agreement) unless you are at least 18 years old
    type: individual
  - source: https://www.practicefusion.com/pds-api/termsofservice/
    text: THIS IS A LEGALLY BINDING AGREEMENT between Practice Fusion, Inc., a Delaware corporation ("Practice Fusion"), and you ("Developer/API User").
    type: developer
  minimum_age:
    text: You are not eligible to use our Services (including obtaining a Credential or entering into a User Agreement) unless you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Children under 13
    text: Under no circumstances may our Services be used by a child under 13 years old.
  - summary: Illegal jurisdictions
    text: You may not use our Services in any jurisdiction where offering, accessing or using our Services would be illegal or unlawful.
  - source: https://www.practicefusion.com/pds-api/termsofservice/
    summary: Use only with registered users
    text: Developer/API User shall only make instances of the Developer Application that have an Integration to the Practice Fusion Solution available to those Practitioners and patients of such Practitioners that are registered users of both the Practice Fusion Solution and the Developer Application
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to obtain Credentials, you must provide certain information about yourself.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Practice Fusion
provenance_date: '2026-11-10'
provider_name: Practice Fusion
provider_slug: practice-fusion
slug: practice-fusion-eligibility
source_date: '2026-11-10'
source_filename: practice-fusion-eligibility.yml
source_heading: Eligibility
source_page: https://www.practicefusion.com/pages/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Practice Fusion\naid: practice-fusion\nurl: https://www.practicefusion.com/pages/terms-of-use.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.practicefusion.com/pages/terms-of-use.html\n  - https://www.practicefusion.com/pds-api/termsofservice/\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to our Services is administered in the United States and is intended for users in the US.\nentity_types:\n- type: individual\n  text: You are not eligible to use our Services (including obtaining a Credential or entering into a User Agreement)\n    unless you are at least 18 years old\n- type:\
  \ developer\n  text: THIS IS A LEGALLY BINDING AGREEMENT between Practice Fusion, Inc., a Delaware corporation (\"Practice Fusion\"),\n    and you (\"Developer/API User\").\n  source: https://www.practicefusion.com/pds-api/termsofservice/\nrestricted_uses:\n- summary: Children under 13\n  text: Under no circumstances may our Services be used by a child under 13 years old.\n- summary: Illegal jurisdictions\n  text: You may not use our Services in any jurisdiction where offering, accessing or using our Services would be\n    illegal or unlawful.\n- summary: Use only with registered users\n  text: Developer/API User shall only make instances of the Developer Application that have an Integration to the\n    Practice Fusion Solution available to those Practitioners and patients of such Practitioners that are registered\n    users of both the Practice Fusion Solution and the Developer Application\n  source: https://www.practicefusion.com/pds-api/termsofservice/\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: In order to obtain Credentials, you must provide certain information about yourself.\nminimum_age:\n  value: '18'\n  text: You are not eligible to use our Services (including obtaining a Credential or entering into a User Agreement)\n    unless you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/practice-fusion/eligibility/practice-fusion-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Practice Fusion's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Electronic Health Records
- FHIR
- Interoperability
- Medical
- Health IT
- SMART on FHIR
- Clinical Data
---
