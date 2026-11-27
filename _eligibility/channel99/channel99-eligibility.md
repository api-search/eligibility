---
api_specs:
- filename: channel99-ad-accounts-api-openapi.yml
  format: yaml
  label: Channel99 Ad Accounts API
  slug: channel99-ad-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-ad-accounts-api-openapi.yml
- filename: channel99-ad-campaign-groups-api-openapi.yml
  format: yaml
  label: Channel99 Ad Campaign Groups API
  slug: channel99-ad-campaign-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-ad-campaign-groups-api-openapi.yml
- filename: channel99-ad-campaigns-api-openapi.yml
  format: yaml
  label: Channel99 Ad Campaigns API
  slug: channel99-ad-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-ad-campaigns-api-openapi.yml
- filename: channel99-ad-groups-api-openapi.yml
  format: yaml
  label: Channel99 Ad Groups API
  slug: channel99-ad-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-ad-groups-api-openapi.yml
- filename: channel99-ad-units-api-openapi.yml
  format: yaml
  label: Channel99 Ad Units API
  slug: channel99-ad-units-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-ad-units-api-openapi.yml
- filename: channel99-ads-api-openapi.yml
  format: yaml
  label: Channel99 Ads API
  slug: channel99-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-ads-api-openapi.yml
- filename: channel99-audiences-api-openapi.yml
  format: yaml
  label: Channel99 Audiences API
  slug: channel99-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-audiences-api-openapi.yml
- filename: channel99-auth-api-openapi.yml
  format: yaml
  label: Channel99 Auth API
  slug: channel99-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-auth-api-openapi.yml
- filename: channel99-channels-api-openapi.yml
  format: yaml
  label: Channel99 Channels API
  slug: channel99-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-channels-api-openapi.yml
- filename: channel99-companies-api-openapi.yml
  format: yaml
  label: Channel99 Companies API
  slug: channel99-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-companies-api-openapi.yml
- filename: channel99-health-api-openapi.yml
  format: yaml
  label: Channel99 Health API
  slug: channel99-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-health-api-openapi.yml
- filename: channel99-impressions-api-openapi.yml
  format: yaml
  label: Channel99 Impressions API
  slug: channel99-impressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-impressions-api-openapi.yml
- filename: channel99-intents-api-openapi.yml
  format: yaml
  label: Channel99 Intents API
  slug: channel99-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-intents-api-openapi.yml
- filename: channel99-ip-lookup-api-openapi.yml
  format: yaml
  label: Channel99 IP Lookup API
  slug: channel99-ip-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-ip-lookup-api-openapi.yml
- filename: channel99-pageviews-api-openapi.yml
  format: yaml
  label: Channel99 Pageviews API
  slug: channel99-pageviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-pageviews-api-openapi.yml
- filename: channel99-vendors-api-openapi.yml
  format: yaml
  label: Channel99 Vendors API
  slug: channel99-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-vendors-api-openapi.yml
- filename: channel99-visits-api-openapi.yml
  format: yaml
  label: Channel99 Visits API
  slug: channel99-visits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channel99/openapi/channel99-visits-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If your use of the Service is on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind such legal entity to these Terms of Use
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Harvesting contact data
    text: (e) harvest or collect email addresses or other contact and personal information of users
  - summary: Unsolicited communications
    text: (f) send any unsolicited or unauthorized advertisements, spam, chain letters, or other communications to other users
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
name: Channel99
provenance_date: '2026-11-09'
provider_name: Channel99
provider_slug: channel99
slug: channel99-eligibility
source_date: '2026-11-09'
source_filename: channel99-eligibility.yml
source_heading: Eligibility
source_page: https://www.channel99.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Channel99\naid: channel99\nurl: https://www.channel99.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If your use of the Service is on behalf of a company or other legal entity, you represent and warrant that\n    you have the authority to bind such legal entity to these Terms of Use\nrestricted_uses:\n- summary: Harvesting contact data\n  text: (e) harvest or collect email addresses or other contact and personal information of users\n- summary: Unsolicited communications\n  text: (f) send any unsolicited or unauthorized\
  \ advertisements, spam, chain letters, or other communications to\n    other users\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/channel99/eligibility/channel99-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Channel99's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Analytics
- Attribution
- B2B
- Advertising
- Marketing Technology
- Artificial Intelligence
- Account Based Marketing
- Reporting
- MCP
- Intent Data
- Account Identification
- Data Export
---
