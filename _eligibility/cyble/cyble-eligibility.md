---
api_specs:
- filename: cyble-domain-api-openapi.yml
  format: yaml
  label: Cyble Domain API
  slug: cyble-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cyble/openapi/cyble-domain-api-openapi.yml
- filename: cyble-exposedbuckets-api-openapi.yml
  format: yaml
  label: Cyble Exposed Buckets API
  slug: cyble-exposedbuckets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cyble/openapi/cyble-exposedbuckets-api-openapi.yml
- filename: cyble-exposedfiles-api-openapi.yml
  format: yaml
  label: Cyble Exposed Files API
  slug: cyble-exposedfiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cyble/openapi/cyble-exposedfiles-api-openapi.yml
- filename: cyble-fields-api-openapi.yml
  format: yaml
  label: Cyble Fields API
  slug: cyble-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cyble/openapi/cyble-fields-api-openapi.yml
- filename: cyble-health-api-openapi.yml
  format: yaml
  label: Cyble Health API
  slug: cyble-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cyble/openapi/cyble-health-api-openapi.yml
- filename: cyble-hosts-api-openapi.yml
  format: yaml
  label: Cyble Hosts API
  slug: cyble-hosts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cyble/openapi/cyble-hosts-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: To have all the rights allowing access to the Service from the place of connection;
  entity_types:
  - text: IF YOU ARE USING THIS SERVICE ON BEHALF OF A COMPANY OR OTHER ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO DO SO.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful purposes only
    text: To be authorized and empowered by law to use the Service for lawful purposes;
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
name: Cyble
provenance_date: '2026-11-09'
provider_name: Cyble
provider_slug: cyble
slug: cyble-eligibility
source_date: '2026-11-09'
source_filename: cyble-eligibility.yml
source_heading: Eligibility
source_page: https://search.odin.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cyble\naid: cyble\nurl: https://search.odin.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: To have all the rights allowing access to the Service from the place of connection;\nentity_types:\n- type: business\n  text: IF YOU ARE USING THIS SERVICE ON BEHALF OF A COMPANY OR OTHER ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY\n    TO DO SO.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: To be authorized and empowered by law to use the Service for lawful purposes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cyble/eligibility/cyble-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Cyble's own page on 2026-11-09.
synthetic: false
tags:
- Threat Intelligence
- Cybersecurity
- Attack Surface Management
- Internet Scanning
- Dark Web Monitoring
- Vulnerability Management
- CVE
- ExposedBuckets
- Domain Intelligence
- WHOIS
- OSINT
- Security
- A2A
---
