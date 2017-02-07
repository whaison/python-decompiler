Pythonデコンパイラ
=================

このプロジェクトは、CPythonバイトコード用の包括的な逆コンパイラを作成することを目的としています
（おそらく、PyPyとPythonの他のPython実装でも動作します
CPythonのバイトコード）。 現時点では、それは比較的不完全であり、多くの
サポートされていないもの（ただしこれに限定されない）：

 * Unpacking
 * try/except/finally
 * else clauses on try/for loops
 * any sort of arithmatic
 * あらゆる種類の arithmatic
 * keyword argument and *args, **kwargs to functions
 * キーワード引数と* args、**関数へのkwargs

私はパッチを取っていますが、少なくともそれらのいくつかは必要と思われます
リファクタリングと私はあまりにも自分自身を行うために退屈なおかげで成長しました。









------------------------------------------------------------------------------------------


Python Decompiler
=================

This project aims to create a comprehensive decompiler for CPython bytecode
(likely works with PyPy as well, and any other Python implementation that uses
CPython's bytecode). At the moment it is relatively incomplete, with many
things not supported, including, but certainly not limited to:

 * Unpacking
 * try/except/finally
 * else clauses on try/for loops
 * any sort of arithmatic
 * keyword argument and *args, **kwargs to functions

I'm taking patches, but I suspect at least some of those will require
refactorings and I've grown a tad too bored to do it myself.
