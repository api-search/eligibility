---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer shall not access or use the Services in embargoed jurisdictions
  entity_types:
  - text: If you access or use the Services on behalf of a company or other legal entity, you represent that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive data without approval
    text: use the Services to process highly sensitive data, including sensitive personal information, protected health information, biometric information, precise geolocation data, government identification numbers, financial account information, credentials, or similarly sensitive categories of data, without Fulcrum’s prior written approval
  - summary: No surveillance or biometric identification
    text: use the Services to develop, deploy, or support surveillance, biometric identification, biometric verification, or profiling systems unless expressly permitted in the Agreement or otherwise approved by Fulcrum in writing
  - summary: No automated eligibility decisions without human review
    text: use the Services to make automated employment, credit, housing, insurance, healthcare, financial, or other eligibility decisions without any human review required by applicable law or otherwise appropriate for the context
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
name: Fulcrum
provenance_date: '2026-11-10'
provider_name: Fulcrum
provider_slug: withfulcrum-com
slug: withfulcrum-com-eligibility
source_date: '2026-11-10'
source_filename: withfulcrum-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.withfulcrum.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fulcrum\naid: withfulcrum-com\nurl: https://www.withfulcrum.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer shall not access or use the Services in embargoed jurisdictions\nentity_types:\n- type: business\n  text: If you access or use the Services on behalf of a company or other legal entity, you represent that you have\n    authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: No sensitive data without approval\n  text: use the Services to process highly sensitive data, including sensitive personal information, protected health\n\
  \    information, biometric information, precise geolocation data, government identification numbers, financial account\n    information, credentials, or similarly sensitive categories of data, without Fulcrum’s prior written approval\n- summary: No surveillance or biometric identification\n  text: use the Services to develop, deploy, or support surveillance, biometric identification, biometric verification,\n    or profiling systems unless expressly permitted in the Agreement or otherwise approved by Fulcrum in writing\n- summary: No automated eligibility decisions without human review\n  text: use the Services to make automated employment, credit, housing, insurance, healthcare, financial, or other\n    eligibility decisions without any human review required by applicable law or otherwise appropriate for the context\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/withfulcrum-com/eligibility/withfulcrum-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Fulcrum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Integration
- Platform
---
