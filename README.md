<meta name="robots" content="noindex">

# tfra.dynamic_embedding.Variable

<!-- Insert buttons and diff -->

<table class="tfo-notebook-buttons tfo-api" align="left">

<td>
  <a target="_blank" href="https://github.com/tensorflow/recommenders-addons/tree/Lifann/add-api-docs/tensorflow_recommenders_addons/dynamic_embedding/python/ops/dynamic_embedding_variable.py#L130-L487">
    <img src="https://www.tensorflow.org/images/GitHub-Mark-32px.png" />
    View source on GitHub
  </a>
</td></table>
<br/>
<br/>



## Class `Variable`

A Distributed version of HashTable(reference from lookup_ops.MutableHashTable)



<!-- Placeholder for "Used in" -->
It is designed to dynamically store the Sparse Weights(Parameters) of DLRMs.

<h2 id="__init__"><code>__init__</code></h2>

<a target="_blank" href="https://github.com/tensorflow/recommenders-addons/tree/Lifann/add-api-docs/tensorflow_recommenders_addons/dynamic_embedding/python/ops/dynamic_embedding_variable.py#L136-L274">View source</a>

``` python
__init__(
    key_dtype=dtypes.int64,
    value_dtype=dtypes.float32,
    dim=1,
    devices=None,
    partitioner=default_partition_fn,
    shared_name=None,
    name='DynamicEmbedding_Variable',
    initializer=None,
    trainable=True,
    checkpoint=True,
    init_size=0,
    restrict_policy=None
)
