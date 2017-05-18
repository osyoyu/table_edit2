table_edit2
===========

[taruのメモ帳ページ](http://taru.s223.xrea.com/index.php?PukiWiki%2Fmake%2Ftable_edit2.inc.php)で公開されている table_edit2 のフォークです。

インストール (PukiWiki 1.5.1)
-----------------------------
1. table_edit2.inc.php を /plugin にコピー
2. plus を /image にコピー
3. pukiwiki.ini.php 内の `define('PKWKEXP_DISABLE_MULTILINE_PLUGIN_HACK', 1)` を `0` に変更する

使い方
------
[オリジナルのページ](http://taru.s223.xrea.com/index.php?PukiWiki%2Fmake%2Ftable_edit2.inc.php)をご覧ください。

変更点
------
PHP 4.x 時代の syntax が数行残っていたものをエラーが出ないよう修正しただけです。

- PHP 5.4.0 で削除された call-time pass-by-reference の除去
- `$foo =& new Foo()` http://php.net/manual/pl/oop4.newref.php の除去

ライセンスについて
------------------
オリジナルではライセンスが "GPL" とのみ記述されていましたので、指定がないときは任意のバージョンを選択できるとする条項に基づき GPLv3 を選択しました。

    table_edit2
    Copyright (C) 2006 taru
    Copyright (C) 2017 osyoyu
    
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
