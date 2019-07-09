page_type: reference
<style>{% include "site-assets/css/style.css" %}</style>

<!-- DO NOT EDIT! Automatically generated file. -->

# Module: tf.contrib.linalg



Defined in [`tensorflow/contrib/linalg/__init__.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.11/tensorflow/contrib/linalg/__init__.py).

Linear algebra libraries.

See the[Contrib Linalg](https://tensorflow.org/api_guides/python/contrib.linalg)
guide.


## Classes

[`class LinearOperator`](../../tf/linalg/LinearOperator): Base class defining a [batch of] linear operator[s].

[`class LinearOperatorBlockDiag`](../../tf/linalg/LinearOperatorBlockDiag): Combines one or more `LinearOperators` in to a Block Diagonal matrix.

[`class LinearOperatorCirculant`](../../tf/linalg/LinearOperatorCirculant): `LinearOperator` acting like a circulant matrix.

[`class LinearOperatorCirculant2D`](../../tf/linalg/LinearOperatorCirculant2D): `LinearOperator` acting like a block circulant matrix.

[`class LinearOperatorCirculant3D`](../../tf/linalg/LinearOperatorCirculant3D): `LinearOperator` acting like a nested block circulant matrix.

[`class LinearOperatorComposition`](../../tf/linalg/LinearOperatorComposition): Composes one or more `LinearOperators`.

[`class LinearOperatorDiag`](../../tf/linalg/LinearOperatorDiag): `LinearOperator` acting like a [batch] square diagonal matrix.

[`class LinearOperatorFullMatrix`](../../tf/linalg/LinearOperatorFullMatrix): `LinearOperator` that wraps a [batch] matrix.

[`class LinearOperatorIdentity`](../../tf/linalg/LinearOperatorIdentity): `LinearOperator` acting like a [batch] square identity matrix.

[`class LinearOperatorKronecker`](../../tf/linalg/LinearOperatorKronecker): Kronecker product between two `LinearOperators`.

[`class LinearOperatorLowRankUpdate`](../../tf/linalg/LinearOperatorLowRankUpdate): Perturb a `LinearOperator` with a rank `K` update.

[`class LinearOperatorLowerTriangular`](../../tf/linalg/LinearOperatorLowerTriangular): `LinearOperator` acting like a [batch] square lower triangular matrix.

[`class LinearOperatorScaledIdentity`](../../tf/linalg/LinearOperatorScaledIdentity): `LinearOperator` acting like a scaled [batch] identity matrix `A = c I`.
