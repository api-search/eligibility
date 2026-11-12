---
api_specs:
- filename: codequiry-com-auth-api-openapi.yml
  format: yaml
  label: Codequiry Auth API
  slug: codequiry-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-auth-api-openapi.yml
- filename: codequiry-com-checks-api-openapi.yml
  format: yaml
  label: Codequiry Checks API
  slug: codequiry-com-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-checks-api-openapi.yml
- filename: codequiry-com-reference-api-openapi.yml
  format: yaml
  label: Codequiry Reference API
  slug: codequiry-com-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-reference-api-openapi.yml
- filename: codequiry-com-results-api-openapi.yml
  format: yaml
  label: Codequiry Results API
  slug: codequiry-com-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-results-api-openapi.yml
- filename: codequiry-com-run-api-openapi.yml
  format: yaml
  label: Codequiry Run API
  slug: codequiry-com-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-run-api-openapi.yml
- filename: codequiry-com-submissions-api-openapi.yml
  format: yaml
  label: Codequiry Submissions API
  slug: codequiry-com-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codequiry-com/openapi/codequiry-com-submissions-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - AT
    - BE
    - BG
    - HR
    - CY
    - CZ
    - DK
    - EE
    - FI
    - FR
    - DE
    - GR
    - HU
    - IE
    - IT
    - LV
    - LT
    - LU
    - MT
    - NL
    - PL
    - PT
    - RO
    - SK
    - SI
    - ES
    - SE
    - IS
    - LI
    - 'NO'
    - GB
    served: []
    text: Not offered in the EU, EEA or UK. We offer the Service only outside the member states of the European Union, the other countries of the European Economic Area (Iceland, Liechtenstein and Norway) and the United Kingdom
  entity_types:
  - text: You must be at least 18, or the age of majority where you live if that is higher, to create an account or accept these Terms.
    type: individual
  minimum_age:
    text: You must be at least 18, or the age of majority where you live if that is higher, to create an account or accept these Terms.
    value: '18'
  restricted_uses:
  - summary: Regulated data not accepted
    text: The Service is not designed for regulated data. We are not a business associate under HIPAA or a service provider under PCI DSS
  - summary: No use for adverse action based solely on AI detection
    text: You must not use AI detection output, or any result, as the sole or main basis for a penalty, grade, disciplinary step, hiring decision or other adverse action against any person.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Students who submit work through an instructor's or institution's account do so under that account holder's authority
excluded_countries:
- AT
- BE
- BG
- HR
- CY
- CZ
- DK
- EE
- FI
- FR
- DE
- GR
- HU
- IE
- IT
- LV
- LT
- LU
- MT
- NL
- PL
- PT
- RO
- SK
- SI
- ES
- SE
- IS
- LI
- 'NO'
- GB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Codequiry
provenance_date: '2026-11-09'
provider_name: Codequiry
provider_slug: codequiry-com
slug: codequiry-com-eligibility
source_date: '2026-11-09'
source_filename: codequiry-com-eligibility.yml
source_heading: Eligibility
source_page: https://codequiry.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Codequiry\naid: codequiry-com\nurl: https://codequiry.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - AT\n  - BE\n  - BG\n  - HR\n  - CY\n  - CZ\n  - DK\n  - EE\n  - FI\n  - FR\n  - DE\n  - GR\n  - HU\n  - IE\n  - IT\n  - LV\n  - LT\n  - LU\n  - MT\n  - NL\n  - PL\n  - PT\n  - RO\n  - SK\n  - SI\n  - ES\n  - SE\n  - IS\n  - LI\n  - 'NO'\n  - GB\n  text: Not offered in the EU, EEA or UK. We offer the Service only outside the member states of the European Union,\n    the other countries of the European Economic Area (Iceland, Liechtenstein and Norway)\
  \ and the United Kingdom\nentity_types:\n- type: individual\n  text: You must be at least 18, or the age of majority where you live if that is higher, to create an account or\n    accept these Terms.\nrestricted_uses:\n- summary: Regulated data not accepted\n  text: The Service is not designed for regulated data. We are not a business associate under HIPAA or a service\n    provider under PCI DSS\n- summary: No use for adverse action based solely on AI detection\n  text: You must not use AI detection output, or any result, as the sole or main basis for a penalty, grade, disciplinary\n    step, hiring decision or other adverse action against any person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Students who submit work through an instructor's or institution's account do so under that account holder's\n    authority\nminimum_age:\n  value: '18'\n  text: You must be at least 18, or the age of majority where you live if that is higher, to create an account\
  \ or\n    accept these Terms.\n"
source_yaml_url: https://artifacts.apis.io/codequiry-com/eligibility/codequiry-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Codequiry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Code Plagiarism
- AI Code Detection
- Education
- Source Code Analysis
- Academic Integrity
- MCP
---
