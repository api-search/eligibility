---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Customer agrees not to access or use the Services in a U.S.-embargoed country or region, nor to provide access to anyone on the U.S. Treasury Department’s list of Specially Designated Nationals.
  entity_types:
  - text: Our services are directed exclusively at Business to Business customers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No ePHI without BAA
    text: Customer shall not submit, and shall not permit any Permitted User to submit, ePHI to the Services unless and until a Business Associate Agreement between the parties is then in effect.
  - summary: Sandbox not for production data
    text: Customer shall not submit, process, or store production Customer Data in the Sandbox Workspace, including any ePHI.
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
name: MCP Manager
provenance_date: '2026-11-10'
provider_name: MCP Manager
provider_slug: mcp-manager
slug: mcp-manager-eligibility
source_date: '2026-11-10'
source_filename: mcp-manager-eligibility.yml
source_heading: Eligibility
source_page: https://mcpmanager.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MCP Manager\naid: mcp-manager\nurl: https://mcpmanager.ai/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Customer agrees not to access or use the Services in a U.S.-embargoed country or region, nor to provide\n    access to anyone on the U.S. Treasury Department’s list of Specially Designated Nationals.\nentity_types:\n- type: business\n  text: Our services are directed exclusively at Business to Business customers.\nrestricted_uses:\n- summary: No ePHI without BAA\n  text: Customer shall not submit, and shall not permit any Permitted User to submit, ePHI to the\
  \ Services unless\n    and until a Business Associate Agreement between the parties is then in effect.\n- summary: Sandbox not for production data\n  text: Customer shall not submit, process, or store production Customer Data in the Sandbox Workspace, including\n    any ePHI.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mcp-manager/eligibility/mcp-manager-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from MCP Manager's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- AI Governance
- API Gateway
- Security
- Observability
- DLP
- Identity
- RBAC
- Enterprise
---
