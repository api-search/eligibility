---
api_specs:
- filename: coderpad-account-api-openapi.yml
  format: yaml
  label: CoderPad Account API
  slug: coderpad-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-account-api-openapi.yml
- filename: coderpad-campaigns-api-openapi.yml
  format: yaml
  label: CoderPad Campaigns API
  slug: coderpad-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-campaigns-api-openapi.yml
- filename: coderpad-me-api-openapi.yml
  format: yaml
  label: CoderPad Me API
  slug: coderpad-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-me-api-openapi.yml
- filename: coderpad-organization-api-openapi.yml
  format: yaml
  label: CoderPad Organization API
  slug: coderpad-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-organization-api-openapi.yml
- filename: coderpad-pad-environments-api-openapi.yml
  format: yaml
  label: CoderPad Pad environments API
  slug: coderpad-pad-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-pad-environments-api-openapi.yml
- filename: coderpad-pads-api-openapi.yml
  format: yaml
  label: CoderPad Pads API
  slug: coderpad-pads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-pads-api-openapi.yml
- filename: coderpad-question-variants-api-openapi.yml
  format: yaml
  label: CoderPad Question variants API
  slug: coderpad-question-variants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-question-variants-api-openapi.yml
- filename: coderpad-questions-api-openapi.yml
  format: yaml
  label: CoderPad Questions API
  slug: coderpad-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-questions-api-openapi.yml
- filename: coderpad-temporaryfile-api-openapi.yml
  format: yaml
  label: CoderPad Temporary File API
  slug: coderpad-temporaryfile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-temporaryfile-api-openapi.yml
- filename: coderpad-tests-api-openapi.yml
  format: yaml
  label: CoderPad Tests API
  slug: coderpad-tests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-tests-api-openapi.yml
- filename: coderpad-webhook-api-openapi.yml
  format: yaml
  label: CoderPad Webhook API
  slug: coderpad-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderpad/openapi/coderpad-webhook-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export clause: you represent you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country; no countries are named.'
  entity_types:
  - text: This Website is only intended for individuals who are at least 16 years of age.
    type: individual
  - text: If you are entering into or accepting these Terms on behalf of a legal entity, you represent and warrant that you have the right, authority and capacity to bind such entity to these Terms
    type: business
  minimum_age:
    text: This Website is only intended for individuals who are at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: No discriminatory or unlawful hiring use
    text: not conduct interviews via the Service or otherwise use the Service in a manner that violates applicable laws, including laws that prohibit discrimination in hiring and employment
  - summary: No circumventing usage or capacity limits
    text: not permit direct or indirect access to or use the Service in a way that circumvents a usage or capacity limit of the Service;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: All paid plans require a valid credit card or advance arrangement of a custom billing plan unless otherwise agreed by CoderPad.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CoderPad
provenance_date: '2026-11-09'
provider_name: CoderPad
provider_slug: coderpad
slug: coderpad-eligibility
source_date: '2026-11-09'
source_filename: coderpad-eligibility.yml
source_heading: Eligibility
source_page: https://coderpad.io/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoderPad\naid: coderpad\nurl: https://coderpad.io/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'Export clause: you represent you are not located in a country that is subject to a U.S. Government embargo,\n    or that has been designated by the U.S. Government as a “terrorist supporting” country; no countries are named.'\nentity_types:\n- type: individual\n  text: This Website is only intended for individuals who are at least 16 years of age.\n- type: business\n  text: If you are entering into or accepting these Terms on behalf of a legal entity, you represent\
  \ and warrant\n    that you have the right, authority and capacity to bind such entity to these Terms\nrestricted_uses:\n- summary: No discriminatory or unlawful hiring use\n  text: not conduct interviews via the Service or otherwise use the Service in a manner that violates applicable\n    laws, including laws that prohibit discrimination in hiring and employment\n- summary: No circumventing usage or capacity limits\n  text: not permit direct or indirect access to or use the Service in a way that circumvents a usage or capacity\n    limit of the Service;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: All paid plans require a valid credit card or advance arrangement of a custom billing plan unless otherwise\n    agreed by CoderPad.\nminimum_age:\n  value: '16'\n  text: This Website is only intended for individuals who are at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/coderpad/eligibility/coderpad-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from CoderPad's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Hiring
- Technical Assessment
- InterviewPlatform
---
