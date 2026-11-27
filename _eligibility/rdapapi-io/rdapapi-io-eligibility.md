---
api_specs:
- filename: rdapapi-io-asn-api-openapi.yml
  format: yaml
  label: rdapapi-io ASN API
  slug: rdapapi-io-asn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-asn-api-openapi.yml
- filename: rdapapi-io-domain-api-openapi.yml
  format: yaml
  label: rdapapi-io Domain API
  slug: rdapapi-io-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-domain-api-openapi.yml
- filename: rdapapi-io-entity-api-openapi.yml
  format: yaml
  label: rdapapi-io Entity API
  slug: rdapapi-io-entity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-entity-api-openapi.yml
- filename: rdapapi-io-health-api-openapi.yml
  format: yaml
  label: rdapapi-io Health API
  slug: rdapapi-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-health-api-openapi.yml
- filename: rdapapi-io-ip-api-openapi.yml
  format: yaml
  label: rdapapi-io IP API
  slug: rdapapi-io-ip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-ip-api-openapi.yml
- filename: rdapapi-io-nameserver-api-openapi.yml
  format: yaml
  label: rdapapi-io Nameserver API
  slug: rdapapi-io-nameserver-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-nameserver-api-openapi.yml
- filename: rdapapi-io-tlds-api-openapi.yml
  format: yaml
  label: rdapapi-io TLDs API
  slug: rdapapi-io-tlds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rdapapi-io/openapi/rdapapi-io-tlds-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: For business customers, any dispute falls under the exclusive jurisdiction of the competent courts of Créteil, France.
    type: business
  - text: For consumers resident in the European Union, jurisdiction is determined by Regulation (EU) No 1215/2012 (Brussels I recast).
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harvesting personal data
    text: Use the Service to harvest personal data in violation of applicable privacy laws.
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
name: rdapapi-io
provenance_date: '2026-11-10'
provider_name: rdapapi-io
provider_slug: rdapapi-io
slug: rdapapi-io-eligibility
source_date: '2026-11-10'
source_filename: rdapapi-io-eligibility.yml
source_heading: Eligibility
source_page: https://rdapapi.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rdapapi-io\naid: rdapapi-io\nurl: https://rdapapi.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: For business customers, any dispute falls under the exclusive jurisdiction of the competent courts of Créteil,\n    France.\n- type: individual\n  text: For consumers resident in the European Union, jurisdiction is determined by Regulation (EU) No 1215/2012\n    (Brussels I recast).\nrestricted_uses:\n- summary: Harvesting personal data\n  text: Use the Service to harvest personal data in violation of applicable privacy laws.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rdapapi-io/eligibility/rdapapi-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from rdapapi-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- RDAP
- Domain
- WHOIS
---
