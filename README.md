# Alation (alation)
Alation is a data intelligence platform that helps organizations harness the power of their data by providing a centralized platform for data cataloging, governance, and collaboration. By enabling users to easily search, understand, and trust their data, Alation empowers organizations to make data-driven decisions with confidence. Through advanced analytics and AI capabilities, Alation helps organizations uncover insights, improve data quality, and drive innovation.

**URL:** [https://developer.alation.com](https://developer.alation.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Data Catalog, Data Governance, Data Intelligence, Data Lineage, Data Quality, Business Glossary, Metadata Management, AI

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## APIs

### Alation Data Catalog API
REST API for managing data sources, schemas, tables, columns, and custom field values in the Alation data catalog. Supports metadata retrieval and batch updates for catalog objects.

**Human URL:** [https://developer.alation.com](https://developer.alation.com)

#### Tags:

 - Data Catalog, Metadata, Data Sources, Schemas, Tables, Columns

#### Properties

- [Documentation](https://developer.alation.com)
- [OpenAPI](openapi/alation-data-catalog-openapi.yaml)
- [JSONSchema](json-schema/alation-alation-data-catalog-data-source-schema.json)
- [JSONSchema](json-schema/alation-alation-data-catalog-schema-schema.json)
- [JSONSchema](json-schema/alation-alation-data-catalog-table-schema.json)
- [JSONSchema](json-schema/alation-alation-data-catalog-column-schema.json)
- [JSONSchema](json-schema/alation-alation-data-catalog-custom-field-value-schema.json)

### Alation Lineage API
REST API for managing data lineage and dataflow objects in Alation. Supports creating, retrieving, updating, and deleting lineage paths between catalog objects.

**Human URL:** [https://developer.alation.com/dev/reference/lineage-overview](https://developer.alation.com/dev/reference/lineage-overview)

#### Tags:

 - Data Lineage, Dataflow, Metadata

#### Properties

- [Documentation](https://developer.alation.com)
- [OpenAPI](openapi/alation-lineage-openapi.yaml)
- [JSONSchema](json-schema/alation-alation-lineage-dataflow-schema.json)
- [JSONSchema](json-schema/alation-alation-lineage-lineage-graph-schema.json)

### Alation Governance API
REST API for data governance workflows in Alation, including business glossary management, governance policy enforcement, and data quality rules and scoring.

**Human URL:** [https://developer.alation.com](https://developer.alation.com)

#### Tags:

 - Data Governance, Business Glossary, Data Quality, Policies

#### Properties

- [Documentation](https://developer.alation.com)
- [OpenAPI](openapi/alation-governance-openapi.yaml)
- [JSONSchema](json-schema/alation-alation-governance-glossary-term-schema.json)
- [JSONSchema](json-schema/alation-alation-governance-policy-schema.json)
- [JSONSchema](json-schema/alation-alation-governance-data-quality-rule-schema.json)
- [JSONSchema](json-schema/alation-alation-governance-data-quality-score-schema.json)

### Alation Search API
REST API for searching and discovering catalog assets in Alation. Supports full-text search, AI-powered aggregated context retrieval, and article browsing.

**Human URL:** [https://developer.alation.com](https://developer.alation.com)

#### Tags:

 - Search, Data Discovery, AI, Catalog

#### Properties

- [Documentation](https://developer.alation.com)
- [OpenAPI](openapi/alation-search-openapi.yaml)
- [JSONSchema](json-schema/alation-alation-search-search-result-schema.json)
- [JSONSchema](json-schema/alation-alation-search-search-results-schema.json)
- [JSONSchema](json-schema/alation-alation-search-context-request-schema.json)
- [JSONSchema](json-schema/alation-alation-search-article-schema.json)

## Common Properties

- [Website](https://alation.com)
- [Documentation](https://developer.alation.com)
- [GettingStarted](https://developer.alation.com/dev/docs/about-the-alation-apis)
- [GitHubOrganization](https://github.com/Alation)

## Features

| Name | Description |
|------|-------------|
| Data Catalog | Centralized catalog for data sources, schemas, tables, and columns with rich metadata, descriptions, and custom fields for discoverability. |
| Data Lineage | End-to-end data lineage tracking via dataflow objects showing how data moves between sources, transformations, and targets. |
| Business Glossary | Collaborative business glossary for defining standardized terms, abbreviations, and synonyms with stewardship assignments. |
| Data Quality | Comprehensive data quality rules covering accuracy, completeness, consistency, timeliness, uniqueness, validity, and custom dimensions. |
| Governance Policies | Governance policy management for data protection, retention, access control, and quality enforcement across the enterprise. |
| AI-Powered Search | Full-text and semantic search powered by AI for discovering trusted data assets, with aggregated context for LLM consumption. |
| Aggregated Context API | Specialized API for AI applications to retrieve structured catalog context for natural language queries, enabling RAG and AI agent workflows. |
| Custom Fields | Extensible metadata framework with custom fields for any catalog object type, supporting batch updates via the REST API. |

## Use Cases

| Name | Description |
|------|-------------|
| Enterprise Data Discovery | Enable data teams to search and find trusted data assets across all data sources using metadata-enriched catalog browsing and search. |
| Data Governance Compliance | Enforce data governance policies, maintain business glossaries, and track stewardship for regulatory compliance and data accountability. |
| AI Data Context | Power AI applications with structured catalog context from the aggregated context API, enabling accurate data-aware LLM responses. |
| Data Lineage Auditing | Track data flows between systems for compliance auditing, impact analysis, and root cause investigation of data quality issues. |
| Data Quality Management | Define and score data quality rules across catalog objects for continuous quality monitoring and improvement workflows. |

## Integrations

| Name | Description |
|------|-------------|
| Snowflake | Native Snowflake integration for automatic metadata harvesting and query log analysis to build comprehensive data lineage. |
| dbt | dbt integration for capturing transformation lineage and linking dbt models to physical tables in the Alation catalog. |
| Tableau | BI metadata integration for cataloging Tableau reports and dashboards with lineage to underlying data sources. |
| Python SDK | Official Python SDK and AI Agent SDK for programmatic access to Alation catalog APIs and AI agent development. |
| Apache Atlas | Integration with Apache Atlas for federated metadata management across heterogeneous data platforms. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Alation Data Catalog API](openapi/alation-data-catalog-openapi.yaml)
- [Alation Lineage API](openapi/alation-lineage-openapi.yaml)
- [Alation Governance API](openapi/alation-governance-openapi.yaml)
- [Alation Search API](openapi/alation-search-openapi.yaml)

### JSON Schema

- [alation-alation-data-catalog-data-source-schema.json](json-schema/alation-alation-data-catalog-data-source-schema.json)
- [alation-alation-data-catalog-schema-schema.json](json-schema/alation-alation-data-catalog-schema-schema.json)
- [alation-alation-data-catalog-table-schema.json](json-schema/alation-alation-data-catalog-table-schema.json)
- [alation-alation-data-catalog-column-schema.json](json-schema/alation-alation-data-catalog-column-schema.json)
- [alation-alation-data-catalog-custom-field-value-schema.json](json-schema/alation-alation-data-catalog-custom-field-value-schema.json)
- [alation-alation-lineage-dataflow-schema.json](json-schema/alation-alation-lineage-dataflow-schema.json)
- [alation-alation-lineage-lineage-graph-schema.json](json-schema/alation-alation-lineage-lineage-graph-schema.json)
- [alation-alation-governance-glossary-term-schema.json](json-schema/alation-alation-governance-glossary-term-schema.json)
- [alation-alation-governance-policy-schema.json](json-schema/alation-alation-governance-policy-schema.json)
- [alation-alation-governance-data-quality-rule-schema.json](json-schema/alation-alation-governance-data-quality-rule-schema.json)
- [alation-alation-governance-data-quality-score-schema.json](json-schema/alation-alation-governance-data-quality-score-schema.json)
- [alation-alation-search-search-result-schema.json](json-schema/alation-alation-search-search-result-schema.json)
- [alation-alation-search-search-results-schema.json](json-schema/alation-alation-search-search-results-schema.json)
- [alation-alation-search-context-request-schema.json](json-schema/alation-alation-search-context-request-schema.json)
- [alation-alation-search-article-schema.json](json-schema/alation-alation-search-article-schema.json)

### JSON Structure

- [alation-alation-data-catalog-data-source-structure.json](json-structure/alation-alation-data-catalog-data-source-structure.json)
- [alation-alation-data-catalog-schema-structure.json](json-structure/alation-alation-data-catalog-schema-structure.json)
- [alation-alation-data-catalog-table-structure.json](json-structure/alation-alation-data-catalog-table-structure.json)
- [alation-alation-data-catalog-column-structure.json](json-structure/alation-alation-data-catalog-column-structure.json)
- [alation-alation-data-catalog-custom-field-value-structure.json](json-structure/alation-alation-data-catalog-custom-field-value-structure.json)
- [alation-alation-lineage-dataflow-structure.json](json-structure/alation-alation-lineage-dataflow-structure.json)
- [alation-alation-lineage-lineage-graph-structure.json](json-structure/alation-alation-lineage-lineage-graph-structure.json)
- [alation-alation-governance-glossary-term-structure.json](json-structure/alation-alation-governance-glossary-term-structure.json)
- [alation-alation-governance-policy-structure.json](json-structure/alation-alation-governance-policy-structure.json)
- [alation-alation-governance-data-quality-rule-structure.json](json-structure/alation-alation-governance-data-quality-rule-structure.json)
- [alation-alation-governance-data-quality-score-structure.json](json-structure/alation-alation-governance-data-quality-score-structure.json)
- [alation-alation-search-search-result-structure.json](json-structure/alation-alation-search-search-result-structure.json)
- [alation-alation-search-search-results-structure.json](json-structure/alation-alation-search-search-results-structure.json)
- [alation-alation-search-context-request-structure.json](json-structure/alation-alation-search-context-request-structure.json)
- [alation-alation-search-article-structure.json](json-structure/alation-alation-search-article-structure.json)

### JSON-LD

- [alation-alation-context.jsonld](json-ld/alation-alation-context.jsonld)

### Examples

- [alation-alation-data-catalog-data-source-example.json](examples/alation-alation-data-catalog-data-source-example.json)
- [alation-alation-data-catalog-schema-example.json](examples/alation-alation-data-catalog-schema-example.json)
- [alation-alation-data-catalog-table-example.json](examples/alation-alation-data-catalog-table-example.json)
- [alation-alation-data-catalog-column-example.json](examples/alation-alation-data-catalog-column-example.json)
- [alation-alation-data-catalog-custom-field-value-example.json](examples/alation-alation-data-catalog-custom-field-value-example.json)
- [alation-alation-lineage-dataflow-example.json](examples/alation-alation-lineage-dataflow-example.json)
- [alation-alation-lineage-lineage-graph-example.json](examples/alation-alation-lineage-lineage-graph-example.json)
- [alation-alation-governance-glossary-term-example.json](examples/alation-alation-governance-glossary-term-example.json)
- [alation-alation-governance-policy-example.json](examples/alation-alation-governance-policy-example.json)
- [alation-alation-governance-data-quality-rule-example.json](examples/alation-alation-governance-data-quality-rule-example.json)
- [alation-alation-governance-data-quality-score-example.json](examples/alation-alation-governance-data-quality-score-example.json)
- [alation-alation-search-search-result-example.json](examples/alation-alation-search-search-result-example.json)
- [alation-alation-search-search-results-example.json](examples/alation-alation-search-search-results-example.json)
- [alation-alation-search-context-request-example.json](examples/alation-alation-search-context-request-example.json)
- [alation-alation-search-article-example.json](examples/alation-alation-search-article-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Alation Data Catalog API](capabilities/shared/data-catalog-api.yaml) — 7 operations for catalog metadata access
- [Alation Lineage API](capabilities/shared/lineage-api.yaml) — 4 operations for lineage management
- [Alation Governance API](capabilities/shared/governance-api.yaml) — 4 operations for governance workflows
- [Alation Search API](capabilities/shared/search-api.yaml) — 3 operations for catalog discovery

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Data Intelligence](capabilities/data-intelligence.yaml) | alation-data-catalog, alation-lineage, alation-governance, alation-search | 9 | Data Steward, Data Analyst, AI Agent Developer |

## Vocabulary

- [Alation Vocabulary](vocabulary/alation-vocabulary.yaml) — Unified taxonomy mapping 12 resources, 5 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Alation Spectral Rules](rules/alation-spectral-rules.yml) — 26 rules across 8 categories enforcing Alation API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
