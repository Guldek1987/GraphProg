# pyKT model implementations

`akt.py` and `ukt.py` are unmodified copies from [pykt-team/pykt-toolkit](https://github.com/pykt-team/pykt-toolkit/tree/77c3e90fdb807542194b989656ccac10e5d92e12), revision `77c3e90fdb807542194b989656ccac10e5d92e12`, distributed under the accompanying MIT license.

Notebooks 04 and 06 load these pinned files. The UKT adapter omits the unused relative import `from .utils import transformer_FFN, ut_mask, pos_encode, get_clones` when constructing the module. No other model-source transformation is applied. Device selection and dataset adapters are visible in the notebooks.
