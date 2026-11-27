---
api_specs:
- filename: clear-verification-sessions-api-openapi.yml
  format: yaml
  label: CLEAR Verification Sessions API
  slug: clear-verification-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clear/openapi/clear-verification-sessions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all Services are available in all jurisdictions.
  entity_types:
  - text: You may enroll either via the Sites, in person at a CLEAR enrollment location, or by enrolling to use the Services through one of our partners.
    type: individual
  - text: If you are employed by an organization through which we offer a corporate rate plan, you may be able to receive a discounted rate for paid Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Fraud or unlawful use
    text: if we suspect you are using a Service fraudulently, in a malicious or unlawful manner, or in any manner not permitted by these Terms
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: To use some of our Services, you may be required to perform additional verification, or provide additional information or data
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CLEAR
provenance_date: '2026-11-09'
provider_name: CLEAR
provider_slug: clear
slug: clear-eligibility
source_date: '2026-11-09'
source_filename: clear-eligibility.yml
source_heading: Eligibility
source_page: https://www.clearme.com/member-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CLEAR\naid: clear\nurl: https://www.clearme.com/member-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not all Services are available in all jurisdictions.\nentity_types:\n- type: individual\n  text: You may enroll either via the Sites, in person at a CLEAR enrollment location, or by enrolling to use the\n    Services through one of our partners.\n- type: business\n  text: If you are employed by an organization through which we offer a corporate rate plan, you may be able to\n    receive a discounted rate for paid Services\nrestricted_uses:\n- summary: Fraud or unlawful use\n\
  \  text: if we suspect you are using a Service fraudulently, in a malicious or unlawful manner, or in any manner\n    not permitted by these Terms\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: To use some of our Services, you may be required to perform additional verification, or provide additional\n    information or data\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clear/eligibility/clear-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from CLEAR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Identity
- Identity Verification
- Authentication
- KYC
- Biometrics
- OAuth
- OpenID Connect
- Healthcare
- Financial Services
---
