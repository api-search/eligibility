---
api_specs:
- filename: calico-bgpconfiguration-api-openapi.yml
  format: yaml
  label: Calico BGPConfiguration API
  slug: calico-bgpconfiguration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-bgpconfiguration-api-openapi.yml
- filename: calico-bgppeer-api-openapi.yml
  format: yaml
  label: Calico BGPPeer API
  slug: calico-bgppeer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-bgppeer-api-openapi.yml
- filename: calico-globalnetworkpolicy-api-openapi.yml
  format: yaml
  label: Calico GlobalNetworkPolicy API
  slug: calico-globalnetworkpolicy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-globalnetworkpolicy-api-openapi.yml
- filename: calico-hostendpoint-api-openapi.yml
  format: yaml
  label: Calico HostEndpoint API
  slug: calico-hostendpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-hostendpoint-api-openapi.yml
- filename: calico-profile-api-openapi.yml
  format: yaml
  label: Calico Profile API
  slug: calico-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-profile-api-openapi.yml
- filename: calico-ip-pool-api-openapi.yml
  format: yaml
  label: Calico IP Pool API
  slug: calico-ip-pool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-ip-pool-api-openapi.yml
- filename: calico-network-policy-api-openapi.yml
  format: yaml
  label: Calico Network Policy API
  slug: calico-network-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-network-policy-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export law compliance
    text: You may not use this site or export information and materials in violation of any applicable laws or regulations including, without limitation, the United States export laws and regulations.
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
name: Calico
provenance_date: '2026-11-09'
provider_name: Calico
provider_slug: calico
slug: calico-eligibility
source_date: '2026-11-09'
source_filename: calico-eligibility.yml
source_heading: Eligibility
source_page: https://www.tigera.io/legal/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calico\naid: calico\nurl: https://www.tigera.io/legal/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export law compliance\n  text: You may not use this site or export information and materials in violation of any applicable laws or regulations\n    including, without limitation, the United States export laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/calico/eligibility/calico-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Calico's own page on 2026-11-09.
synthetic: false
tags:
- CNI
- Containers
- eBPF
- Kubernetes
- Network Policy
- Network Security
- Networking
- Open Source
- Service Mesh
---
