---
api_specs:
- filename: seven-io-events-api-openapi.yml
  format: yaml
  label: seven.io Events API
  slug: seven-io-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-events-api-openapi.yml
- filename: seven-io-journal-api-openapi.yml
  format: yaml
  label: seven.io Journal API
  slug: seven-io-journal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-journal-api-openapi.yml
- filename: seven-io-lookup-api-openapi.yml
  format: yaml
  label: seven.io Lookup API
  slug: seven-io-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-lookup-api-openapi.yml
- filename: seven-io-messages-api-openapi.yml
  format: yaml
  label: seven.io Messages API
  slug: seven-io-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-messages-api-openapi.yml
- filename: seven-io-numbers-api-openapi.yml
  format: yaml
  label: seven.io Numbers API
  slug: seven-io-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-numbers-api-openapi.yml
- filename: seven-io-rcs-api-openapi.yml
  format: yaml
  label: seven.io Rcs API
  slug: seven-io-rcs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-rcs-api-openapi.yml
- filename: seven-io-revoke-api-openapi.yml
  format: yaml
  label: seven.io Revoke API
  slug: seven-io-revoke-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-revoke-api-openapi.yml
- filename: seven-io-seven-io-api-api-openapi.yml
  format: yaml
  label: seven.io Seven.io API
  slug: seven-io-seven-io-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-seven-io-api-api-openapi.yml
- filename: seven-io-token-api-openapi.yml
  format: yaml
  label: seven.io Token API
  slug: seven-io-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-token-api-openapi.yml
- filename: seven-io-voice-api-openapi.yml
  format: yaml
  label: seven.io Voice API
  slug: seven-io-voice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-voice-api-openapi.yml
- filename: seven-io-waba-api-openapi.yml
  format: yaml
  label: seven.io Waba API
  slug: seven-io-waba-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seven-io/openapi/seven-io-waba-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The services offered by seven.io are aimed exclusively at traders.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited message content
    text: 'The transfer of messages with the following content or messages referring to such content is prohibited: SMS containing illegal, punishable, harassing, defamatory, discriminatory, threatening, vulgar, obscene, pester (§238 StGB), unauthorized or otherwise punishable content'
  - summary: Value-added numbers
    text: It is forbidden to use value-added numbers both in messages and as the sender.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: seven.io reserves the right to request proofs from the customer about the correctness of his information, for example a commercial register exract or a business registration. seven.io is not obliged to accept an application for conclusion of a contract, in particular if the applicant provides false information or if there is a reasonable suspicion that the customer intends to misuse the services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: seven.io
provenance_date: '2026-11-10'
provider_name: seven.io
provider_slug: seven-io
slug: seven-io-eligibility
source_date: '2026-11-10'
source_filename: seven-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.seven.io/en/company/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: seven.io\naid: seven-io\nurl: https://www.seven.io/en/company/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The services offered by seven.io are aimed exclusively at traders.\nrestricted_uses:\n- summary: Prohibited message content\n  text: 'The transfer of messages with the following content or messages referring to such content is prohibited:\n    SMS containing illegal, punishable, harassing, defamatory, discriminatory, threatening, vulgar, obscene, pester\n    (§238 StGB), unauthorized or otherwise punishable content'\n\
  - summary: Value-added numbers\n  text: It is forbidden to use value-added numbers both in messages and as the sender.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: seven.io reserves the right to request proofs from the customer about the correctness of his information,\n    for example a commercial register exract or a business registration. seven.io is not obliged to accept an application\n    for conclusion of a contract, in particular if the applicant provides false information or if there is a reasonable\n    suspicion that the customer intends to misuse the services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/seven-io/eligibility/seven-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from seven.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SMS
- Voice
- Messaging
- CPaaS
- Germany
---
