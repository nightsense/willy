## vim

- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-dark.vim> `c1c3e6c`

```
3,10d | 4d | 5d | 36d | 42,49d |
4s#.*/#execute "silent !/bin/sh $HOME/.nightshell/# |
4s/\.sh// |
%s/base16-default-dark/willy/ |

%s/181818/291b14/ |
%s/282828/302018/ |
%s/383838/523a29/ |
%s/585858/705441/ |
%s/b8b8b8/997959/ |
%s/d8d8d8/bfa580/ |
%s/e8e8e8/e8d0ae/ |
%s/f8f8f8/fff2e0/ |

%s/ab4642/d46a73/ |
%s/dc9656/d47b6a/ |
%s/f7ca88/d4ab59/ |
%s/a1b56c/85ab72/ |
%s/86c1b9/72ab98/ |
%s/7cafc2/80a5bf/ |
%s/ba8baf/978fbf/ |
%s/a16946/bf8fb7/ |

%s/Character",    s:gui08, "", s:cterm08/Character",    s:gui0A, "", s:cterm0A/ |
%s/ColorColumn",   "", s:gui01, "", s:cterm01/ColorColumn",   "", s:gui02, "", s:cterm02/ |
%s/Cursor",        s:gui00, s:gui05, s:cterm00, s:cterm05/Cursor",        s:gui01, s:gui0A, s:cterm01, s:cterm0A/ |
%s/CursorLine",    "", s:gui01, "", s:cterm01/CursorLine",    "", s:gui02, "", s:cterm02/ |
%s/CursorLineNr",  s:gui04, s:gui01, s:cterm04, s:cterm01/CursorLineNr",  s:gui04, s:gui01, s:cterm04, s:cterm01/ |
%s/Identifier",   s:gui08, "", s:cterm08, "", "none/Identifier",   s:gui0A, "", s:cterm0A, "", "bold/ |
%s/LineNr",        s:gui03, s:gui01, s:cterm03, s:cterm01/LineNr",        s:gui04, s:gui00, s:cterm04, s:cterm00/ |
%s/Normal",        s:gui05, s:gui00, s:cterm05, s:cterm00/Normal",        s:gui05, s:gui01, s:cterm05, s:cterm01/ |
%s/Search",        s:gui03, s:gui0A, s:cterm03, s:cterm0A/Search",        s:gui00, s:gui05, s:cterm00, s:cterm05/ |
%s/statusline",    s:gui04, s:gui02, s:cterm04, s:cterm02/statusline",    s:gui05, s:gui02, s:cterm05, s:cterm02/ |
%s/StatusLineNC",  s:gui03, s:gui01, s:cterm03, s:cterm01/StatusLineNC",  s:gui04, s:gui00, s:cterm04, s:cterm00/ |
%s/Visual",        "", s:gui02, "", s:cterm02/Visual",        s:gui06, s:gui03, s:cterm06, s:cterm03/ |
%s/VisualNOS",     s:gui08, "", s:cterm08, "", ""/VisualNOS",     "", s:gui02, "", s:cterm02, "none"/ |
%s/WildMenu",      s:gui08, s:gui0A, s:cterm08, ""/WildMenu",      s:gui00, s:gui0A, s:cterm00, s:cterm0A/ |

%s/Comment",      s:gui03, "", s:cterm03, ""/Comment",      s:gui04, "", s:cterm04, ""/ |
%s/Folded",        s:gui03, s:gui01, s:cterm03, s:cterm01/Folded",        s:gui03, s:gui01, s:cterm03, s:cterm01/ |
%s/MatchParen",    "", s:gui03, "", s:cterm03,  ""/MatchParen",    "", s:gui03, "", s:cterm03,  ""/ |
%s/SpecialKey",    s:gui03, "", s:cterm03, ""/SpecialKey",    s:gui03, "", s:cterm03, ""/ |
%s/NonText",       s:gui03, "", s:cterm03, ""/NonText",       s:gui03, "", s:cterm03, ""/ |
%s/SignColumn",    s:gui03, s:gui01, s:cterm03, s:cterm01/SignColumn",    s:gui03, s:gui01, s:cterm03, s:cterm01/ |
%s/TabLine",       s:gui03, s:gui01, s:cterm03, s:cterm01/TabLine",       s:gui03, s:gui01, s:cterm03, s:cterm01/ |
%s/TabLineFill",   s:gui03, s:gui01, s:cterm03, s:cterm01/TabLineFill",   s:gui03, s:gui01, s:cterm03, s:cterm01/ |
%s/DiffChange",   s:gui03, s:gui01,  s:cterm03, s:cterm01/DiffChange",   s:gui03, s:gui01,  s:cterm03, s:cterm01/ |
%s/gitcommitComment",        s:gui03, "", s:cterm03, ""/gitcommitComment",        s:gui03, "", s:cterm03, ""/ |
%s/gitcommitUntracked",      s:gui03, "", s:cterm03, ""/gitcommitUntracked",      s:gui03, "", s:cterm03, ""/ |
%s/gitcommitDiscarded",      s:gui03, "", s:cterm03, ""/gitcommitDiscarded",      s:gui03, "", s:cterm03, ""/ |
%s/gitcommitSelected",       s:gui03, "", s:cterm03, ""/gitcommitSelected",       s:gui03, "", s:cterm03, ""/ |

%s/ErrorMsg",      s:gui08, s:gui00, s:cterm08, s:cterm00/ErrorMsg",      s:gui08, s:gui01, s:cterm08, s:cterm01/ |
%s/Conceal",       s:gui0D, s:gui00, s:cterm0D, s:cterm00/Conceal",       s:gui0D, s:gui01, s:cterm0D, s:cterm01/ |
%s/DiffAdded",    s:gui0B, s:gui00,  s:cterm0B, s:cterm00/DiffAdded",    s:gui0B, s:gui01,  s:cterm0B, s:cterm01/ |
%s/DiffFile",     s:gui08, s:gui00,  s:cterm08, s:cterm00/DiffFile",     s:gui08, s:gui01,  s:cterm08, s:cterm01/ |
%s/DiffNewFile",  s:gui0B, s:gui00,  s:cterm0B, s:cterm00/DiffNewFile",  s:gui0B, s:gui01,  s:cterm0B, s:cterm01/ |
%s/DiffLine",     s:gui0D, s:gui00,  s:cterm0D, s:cterm00/DiffLine",     s:gui0D, s:gui01,  s:cterm0D, s:cterm01/ |
%s/DiffRemoved",  s:gui08, s:gui00,  s:cterm08, s:cterm00/DiffRemoved",  s:gui08, s:gui01,  s:cterm08, s:cterm01/ |
%s/markdownError",             s:gui05, s:gui00, s:cterm05, s:cterm00/markdownError",             s:gui05, s:gui01, s:cterm05, s:cterm01/ |
%s/SpellBad",     "", s:gui00, "", s:cterm00/SpellBad",     "", s:gui01, "", s:cterm01/ |
%s/SpellLocal",   "", s:gui00, "", s:cterm00/SpellLocal",   "", s:gui01, "", s:cterm01/ |
%s/SpellCap",     "", s:gui00, "", s:cterm00/SpellCap",     "", s:gui01, "", s:cterm01/ |
%s/SpellRare",    "", s:gui00, "", s:cterm00/SpellRare",    "", s:gui01, "", s:cterm01/ |

normal =gg
```

## nightshell

- <https://raw.githubusercontent.com/chriskempson/base16-shell/master/scripts/base16-default-dark.sh> `376294b`

```
2,4d |

%s#18/18/18#29/1b/14# |
%s#28/28/28#30/20/18# |
%s#38/38/38#52/3a/29# |
%s#58/58/58#70/54/41# |
%s#b8/b8/b8#99/79/59# |
%s#d8/d8/d8#bf/a5/80# |
%s#e8/e8/e8#e8/d0/ae# |
%s#f8/f8/f8#ff/f2/e0# |
%s#ab/46/42#d4/6a/73# |
%s#dc/96/56#d4/7b/6a# |
%s#f7/ca/88#d4/ab/59# |
%s#a1/b5/6c#85/ab/72# |
%s#86/c1/b9#72/ab/98# |
%s#7c/af/c2#80/a5/bf# |
%s#ba/8b/af#97/8f/bf# |
%s#a1/69/46#bf/8f/b7# |

%s/181818/291b14/ge |
%s/383838/523a29/g |
%s/d8d8d8/bfa580/g |
%s/f8f8f8/fff2e0/ge |

call append(123,["",
"echo -ne '\\e]12;#d4ab59\\a'"])
```
