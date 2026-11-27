---
api_specs:
- filename: helika-events-api-openapi.yml
  format: yaml
  label: Helika Events API
  slug: helika-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helika/openapi/helika-events-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our services to any person, geographic region or jurisdiction.
  minimum_age:
    text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Prohibited uses list
    text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose; (b) to solicit others to perform or participate in any unlawful acts'
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
name: Helika
provenance_date: '2026-11-09'
provider_name: Helika
provider_slug: helika
slug: helika-eligibility
source_date: '2026-11-09'
source_filename: helika-eligibility.yml
source_heading: Eligibility
source_page: https://www.helika.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Helika\naid: helika\nurl: https://www.helika.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our services to any person, geographic\n    region or jurisdiction.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses list\n  text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose; (b) to solicit others\n    to perform or participate in any unlawful acts'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: age of majority\n  text: By agreeing to these Terms of Service, you represent that you are at least the age of majority in your state\n    or province of residence\n"
source_yaml_url: https://artifacts.apis.io/helika/eligibility/helika-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Helika's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Gaming
- Analytics
- Game Analytics
- Web3
- Event
- Artificial Intelligence
- SDK
- Player Data
---
