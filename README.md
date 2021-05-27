<meta name="robots" content="noindex">

# tfra.dynamic_embedding.TimestampRestrictPolicy

<!-- Insert buttons and diff -->

<table class="tfo-notebook-buttons tfo-api" align="left">

<td>
  <a target="_blank" href="https://github.com/tensorflow/recommenders-addons/tree/Lifann/add-api-docs/tensorflow_recommenders_addons/dynamic_embedding/python/ops/restrict_policies.py#L114-L230">
    <img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />
    View source on GitHub
  </a>
</td>
<br/>
<br/>
<br/>
<br/>
</table>



## Class `TimestampRestrictPolicy`

A derived policy to eliminate features in variable follow the

Inherits From: [`RestrictPolicy`](../../tfra/dynamic_embedding/RestrictPolicy.md)

<!-- Placeholder for "Used in" -->
`oldest-out-first` rule.

<h2 id="__init__"><code>__init__</code></h2>

<a target="_blank" href="https://github.com/tensorflow/recommenders-addons/tree/Lifann/add-api-docs/tensorflow_recommenders_addons/dynamic_embedding/python/ops/restrict_policies.py#L120-L153">View source</a>

``` python
__init__(var)
```

A timestamp status sparse variable is created. The timestamp status
has same key_dtype as the target variable and value_dtype in int32,
which indicates the timestamp value. The timestamp means a digital
record of time. The later the time, the larger the timestamp.

#### Args:
