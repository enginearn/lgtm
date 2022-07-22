# lgtm

## Python実践入門のChapter_13の内容

~~Pillowでモジュールエラー出たら`pip`で入れ直す~~

~~`ModuleNotFoundError: No module named 'PIL'`~~

### 動作環境

- Windows 10
- Python 3.10.5
- Click 8.1.3
- Pillow 9.2.0
- requests 2.28.1

### USAGE

ローカル環境では以下。

``` PowerShell
git clone
cd lgtm
python main.py book
または
pip install -e .
lgtm book
```

GitHub repositoryから`pip install`は以下。

`pip install git+https://github.com/enginearn/lgtm#egg=lgtm`

---

Circle CIはよくわからないので、改めていろいろ調べる

そもそもディレクトリ構成を間違えていた...

`main.py`が`lgtm`フォルダにあったのでうまくいかない。(それはそう...)