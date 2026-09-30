# Shared Schemas for decentralised.art API Specification

Common reusable components for decentralised.art API contracts.

The `shared/` directory contains **canonical schema definitions** for
decentralised.art. These definitions keep API contracts
consistent in their data structures, error formats, metadata, and primitive types.

These files are imported via `$ref` from endpoint group OpenAPI contracts.

Endpoint groups under `apis/` may reference these files.
