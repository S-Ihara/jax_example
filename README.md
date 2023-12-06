# jax_examples

jaxとflaxをベースに使った実装例やなんやかんやを書いていく

## 環境構築
jaxはお手元のcudaやcudnnのバージョンなどに適宜合わせてください。
```bash
pip install --upgrade "jax[cuda11_cudnn82]==0.4.7" -f https://storage.googleapis.com
/jax-releases/jax_cuda_releases.html # jaxのインストール

pip install --upgrade "jaxlib[cuda11_cudnn82]==0.4.7" -f https://storage.googleapis.com
/jax-releases/jax_cuda_releases.html
```
