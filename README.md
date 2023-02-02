# license
Licensing Policy

# MITライセンスとは？
MITライセンスは2個の条件だけからなるオープンソースライセンスです．
```
Copyright (c) [作成年] [著作権者名]
以下の条件を満たす限り、自由な複製・配布・修正を無制限に許可する。
・上記の著作権表示と本許諾書を、ソフトウェアの複製または重要な部分に記載する
・本ソフトウェアは無保証である。自己責任で使用する。
```
```
Copyright (c) [year] [fullname]
This software is released under the MIT License.
http://opensource.org/licenses/mit-license.php
```

# MITライセンスを適用したい自作ソフトウェアに、他のMIT/BSDライセンスなソフトウェアを同梱する場合

もとのライセンス条項にしたがって(つまり、ヘッダーの著作権表記とライセンス文書を残して)ライブラリにできます。慣習として、AUTHORS.txtというテキストファイルを用意して、そこに追加OSSの著作権者名を記載していきます。
```
#!/usr/bin/env python
# -*- coding: utf-8 -*-
# Copyright (c) 2023, Hiroyuki Okada
# This software is released under the MIT License.
# http://opensource.org/licenses/mit-license.php
#
#
```
```
"""
 * jQuery JavaScript Library v1.4.2
 * http://jquery.com/
 *
 * Copyright 2010, John Resig
 * Dual licensed under the MIT or GPL Version 2 licenses.
 * http://jquery.org/license
 *
 * Includes Sizzle.js
 * http://sizzlejs.com/
 * Copyright 2010, The Dojo Foundation
 * Released under the MIT, BSD, and GPL Licenses.
 *
 * Date: Sat Feb 13 22:33:48 2010 -0500
"""
```
