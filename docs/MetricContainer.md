# Class: MetricContainer
_A container of metrics for a trained classifier._





URI: [https://w3id.org/neat_schema/:MetricContainer](https://w3id.org/neat_schema/:MetricContainer)



<!-- no inheritance hierarchy -->



## Slots

| Name | Range | Cardinality | Description  | Info |
| ---  | --- | --- | --- | --- |
| [metrics](metrics.md) | [Metric](Metric.md) | 0..* | None  | . |


## Usages


| used by | used in | type | used |
| ---  | --- | --- | --- |
| [TFKerasParams](TFKerasParams.md) | [metrics_config](metrics_config.md) | range | MetricContainer |



## Identifier and Mapping Information









## LinkML Specification

<!-- TODO: investigate https://stackoverflow.com/questions/37606292/how-to-create-tabbed-code-blocks-in-mkdocs-or-sphinx -->

### Direct

<details>
```yaml
name: MetricContainer
description: A container of metrics for a trained classifier.
from_schema: https://w3id.org/neat_schema
attributes:
  metrics:
    name: metrics
    from_schema: https://w3id.org/neat_schema
    multivalued: true
    range: Metric
    inlined: true
    inlined_as_list: true

```
</details>

### Induced

<details>
```yaml
name: MetricContainer
description: A container of metrics for a trained classifier.
from_schema: https://w3id.org/neat_schema
attributes:
  metrics:
    name: metrics
    from_schema: https://w3id.org/neat_schema
    multivalued: true
    alias: metrics
    owner: MetricContainer
    range: Metric
    inlined: true
    inlined_as_list: true

```
</details>