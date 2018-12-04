# [Chainer](https://docs.chainer.org/en/latest/) on [Google Colaboratory](https://colab.research.google.com/)

Use the following snippet to install Chainer & CuPy (with cuDNN) on Google Colaboratory.
Make sure to enable GPU (`Runtime` > `Change runtime type` > `Hardware accelerator` > `GPU`) on your notebook **before** running the snippet!

```
!curl https://colab.chainer.org/install | sh -
```

To install Chainer with ChainerX support (experimental), use the following snippet.

```
!curl https://colab.chainer.org/install-chainerx | sh -
```

## Examples

* [MNIST Example](https://drive.google.com/file/d/1SsxHvQdSz23kaVov8yKizVD3_2tkXdZM/view) (by @mitmul)
    * Click `Open with Colaboratory` button to open the notebook.

* [chainer-colab-notebook](https://github.com/chainer-community/chainer-colab-notebook) (by Chainer Community)
