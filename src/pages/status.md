---
title: Status
---

# Status

OpenTelemetry is made up of [several components](https://opentelemetry.io/docs/concepts/components/), some language-specific and others language-agnostic. When looking for a [status](https://opentelemetry.io/docs/specs/otel/versioning-and-stability/), make sure to look for the status from the right component page. For example, the status of a signal in the specification may not be the same as the signal status in a particular language SDK.


## Language APIs & SDKs

For the development status, or maturity level, of a [language API or SDK](https://opentelemetry.io/docs/languages/), see the following table:


| Language                                                                 | Traces     | Metrics     | Logs         |
|--------------------------------------------------------------------------|------------|-------------|--------------|
| [C++](https://opentelemetry.io/docs/languages/cpp/)                      | Stable     | Stable      | Stable       |
| [C#/.NET](https://opentelemetry.io/docs/languages/dotnet/)              | Stable     | Stable      | Stable       |
| [Erlang/Elixir](https://opentelemetry.io/docs/languages/erlang/)        | Stable     | Development | Development  |
| [Go](https://opentelemetry.io/docs/languages/go/)                        | Stable     | Stable      | Beta         |
| [Java](https://opentelemetry.io/docs/languages/java/)                    | Stable     | Stable      | Stable       |
| [JavaScript](https://opentelemetry.io/docs/languages/js/)                | Stable     | Stable      | Development  |
| [PHP](https://opentelemetry.io/docs/languages/php/)                      | Stable     | Stable      | Stable       |
| [Python](https://opentelemetry.io/docs/languages/python/)                | Stable     | Stable      | Development  |
| [Ruby](https://opentelemetry.io/docs/languages/ruby/)                    | Stable     | Development | Development  |
| [Rust](https://opentelemetry.io/docs/languages/rust/)                    | Beta       | Beta        | Beta         |
| [Swift](https://opentelemetry.io/docs/languages/swift/)                  | Stable     | Development | Development  |



For more details on the specification compliance per implementation, see the [Spec Compliance Matrix](https://github.com/open-telemetry/opentelemetry-specification/blob/main/spec-compliance-matrix.md).


## Collector

The collector status is: [mixed](https://opentelemetry.io/docs/specs/otel/document-status/#mixed), since core collector components currently have mixed [stability levels](https://github.com/open-telemetry/opentelemetry-collector#stability-levels).

**Collector components** differ in their maturity levels. Each component has its stability documented in its `README.md`. You can find a list of all available collector components in the [registry](https://opentelemetry.io/ecosystem/registry/?language=collector).


## Kubernetes Operator

The OpenTelemetry Operator status is [mixed](https://opentelemetry.io/docs/specs/otel/document-status/#mixed), since it deploys components of differing statuses.

The Operator itself is in a [mixed](https://opentelemetry.io/docs/specs/otel/document-status/#mixed) state with components in `v1alpha1` and `v1beta1` states.


## Specifications

For the development status, or maturity level, of the [specification](https://opentelemetry.io/docs/specs/otel/), see the following: [Specification Status Summary](https://opentelemetry.io/docs/specs/status/).