---
api_specs:
- filename: hatch-contacts-api-openapi.yml
  format: yaml
  label: Hatch Contacts API
  slug: hatch-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hatch/openapi/hatch-contacts-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By accepting this Agreement on behalf of Customer, you represent that you have authority to bind Customer and its affiliates.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sensitive data uploads prohibited
    text: it will not upload sensitive or special categories of information as defined in Data Protection Laws
  - summary: Children under thirteen
    text: it will not knowingly collect or use personally identifiable information from children under thirteen when using the Service
  - summary: Communications only with consent
    text: send Communications only to individuals from whom Customer has obtained all necessary and legally required consent
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
name: Hatch
provenance_date: '2026-11-09'
provider_name: Hatch
provider_slug: hatch
slug: hatch-eligibility
source_date: '2026-11-09'
source_filename: hatch-eligibility.yml
source_heading: Eligibility
source_page: https://www.usehatchapp.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hatch\naid: hatch\nurl: https://www.usehatchapp.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: By accepting this Agreement on behalf of Customer, you represent that you have authority to bind Customer\n    and its affiliates.\nrestricted_uses:\n- summary: Sensitive data uploads prohibited\n  text: it will not upload sensitive or special categories of information as defined in Data Protection Laws\n- summary: Children under thirteen\n  text: it will not knowingly collect or use personally identifiable information from\
  \ children under thirteen when\n    using the Service\n- summary: Communications only with consent\n  text: send Communications only to individuals from whom Customer has obtained all necessary and legally required\n    consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hatch/eligibility/hatch-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Hatch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Vertical Software
- Customer Communication
- Conversational AI
- SMS
- Voice
- Email
- Marketing
- Home Services
- Contact Center
---
