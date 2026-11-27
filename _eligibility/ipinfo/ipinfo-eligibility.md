---
api_specs:
- filename: ipinfo-abuse-api-openapi.yml
  format: yaml
  label: IPinfo Abuse API
  slug: ipinfo-abuse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-abuse-api-openapi.yml
- filename: ipinfo-asn-api-openapi.yml
  format: yaml
  label: IPinfo Asn API
  slug: ipinfo-asn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-asn-api-openapi.yml
- filename: ipinfo-carrier-api-openapi.yml
  format: yaml
  label: IPinfo Carrier API
  slug: ipinfo-carrier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-carrier-api-openapi.yml
- filename: ipinfo-company-api-openapi.yml
  format: yaml
  label: IPinfo Company API
  slug: ipinfo-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-company-api-openapi.yml
- filename: ipinfo-domains-api-openapi.yml
  format: yaml
  label: IPinfo Domains API
  slug: ipinfo-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-domains-api-openapi.yml
- filename: ipinfo-general-api-openapi.yml
  format: yaml
  label: IPinfo General API
  slug: ipinfo-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-general-api-openapi.yml
- filename: ipinfo-ipinfo-core-api-openapi.yml
  format: yaml
  label: IPinfo Core API
  slug: ipinfo-ipinfo-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-ipinfo-core-api-openapi.yml
- filename: ipinfo-ipinfo-lite-api-openapi.yml
  format: yaml
  label: IPinfo Lite API
  slug: ipinfo-ipinfo-lite-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-ipinfo-lite-api-openapi.yml
- filename: ipinfo-ipinfo-max-api-openapi.yml
  format: yaml
  label: IPinfo Max API
  slug: ipinfo-ipinfo-max-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-ipinfo-max-api-openapi.yml
- filename: ipinfo-ipinfo-plus-api-openapi.yml
  format: yaml
  label: IPinfo Plus API
  slug: ipinfo-ipinfo-plus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-ipinfo-plus-api-openapi.yml
- filename: ipinfo-places-api-openapi.yml
  format: yaml
  label: IPinfo Places API
  slug: ipinfo-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-places-api-openapi.yml
- filename: ipinfo-privacy-detection-api-openapi.yml
  format: yaml
  label: IPinfo privacy detection API
  slug: ipinfo-privacy-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-privacy-detection-api-openapi.yml
- filename: ipinfo-privacy-detection-extended-api-openapi.yml
  format: yaml
  label: IPinfo privacy detection extended API
  slug: ipinfo-privacy-detection-extended-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-privacy-detection-extended-api-openapi.yml
- filename: ipinfo-ranges-api-openapi.yml
  format: yaml
  label: IPinfo Ranges API
  slug: ipinfo-ranges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-ranges-api-openapi.yml
- filename: ipinfo-residential-proxy-detection-api-openapi.yml
  format: yaml
  label: IPinfo residential proxy detection API
  slug: ipinfo-residential-proxy-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-residential-proxy-detection-api-openapi.yml
- filename: ipinfo-single-api-openapi.yml
  format: yaml
  label: IPinfo Single API
  slug: ipinfo-single-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-single-api-openapi.yml
- filename: ipinfo-whois-api-openapi.yml
  format: yaml
  label: IPinfo Whois API
  slug: ipinfo-whois-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-whois-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are registering for or using the Site on behalf of an organization, you are agreeing to these Terms for that organization
    type: business
  minimum_age:
    text: You must be 18 years of age or older to use the Site.
    value: '18'
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
name: IPinfo
provenance_date: '2026-11-09'
provider_name: IPinfo
provider_slug: ipinfo
slug: ipinfo-eligibility
source_date: '2026-11-09'
source_filename: ipinfo-eligibility.yml
source_heading: Eligibility
source_page: https://ipinfo.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IPinfo\naid: ipinfo\nurl: https://ipinfo.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are registering for or using the Site on behalf of an organization, you are agreeing to these Terms\n    for that organization\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/ipinfo/eligibility/ipinfo-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from IPinfo's own page on 2026-11-09.
synthetic: false
tags:
- IP Intelligence
- IP Geolocation
- ASN
- Privacy Detection
- VPN Detection
- Threat Intelligence
- Network Data
- Mobile Carrier
- WHOIS
- Public APIs
- Development
---
