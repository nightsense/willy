## vim

- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-light.vim> `c1c3e6c`
- <https://github.com/chriskempson/base16-vim/blob/master/colors/base16-default-dark.vim> `c1c3e6c`

```
3,10d | 4d | 5d | 36d | 42,49d |
4s#.*/#execute "silent !/bin/sh $HOME/.nightshell/# |
4s/\.sh// |
%s/base16-default/willy/ |

%s/181818/291b14/ |
%s/282828/302018/ |
%s/383838/523a29/ |
%s/585858/705441/ |
%s/b8b8b8/997959/ |
%s/d8d8d8/bfa580/ |
%s/e8e8e8/e8d0ae/ |
%s/f8f8f8/fff2e0/ |

%s/ab4642/d45963/ |
%s/dc9656/d46d59/ |
%s/f7ca88/bf953f/ |
%s/a1b56c/63944a/ |
%s/86c1b9/56947f/ |
%s/7cafc2/6097bf/ |
%s/ba8baf/7c72ab/ |
%s/a16946/ab80a4/ |

%s/Character",    s:gui08, "", s:cterm08/Character",    s:gui0A, "", s:cterm0A/ |
%s/Cursor",        s:gui00, s:gui05, s:cterm00, s:cterm05/Cursor",        s:gui00, s:gui0A, s:cterm00, s:cterm0A/ |
%s/Identifier",   s:gui08, "", s:cterm08, "", "none/Identifier",   s:gui0A, "", s:cterm0A, "", "bold/ |
%s/LineNr",        s:gui03, s:gui01, s:cterm03/LineNr",        s:gui04, s:gui01, s:cterm04/ |
%s/Search",        s:gui03, s:gui0A, s:cterm03, s:cterm0A/Search",        s:gui00, s:gui04, s:cterm00, s:cterm04/ |
%s/statusline",    s:gui04, s:gui02, s:cterm04, s:cterm02/statusline",    s:gui00, s:gui0A, s:cterm00, s:cterm0A/ |
%s/StatusLineNC",  s:gui03, s:gui01, s:cterm03, s:cterm01/StatusLineNC",  s:gui05, s:gui01, s:cterm05, s:cterm01/ |
%s/Visual",        "", s:gui02, "", s:cterm02/Visual",        s:gui06, s:gui02, s:cterm06, s:cterm02/ |
%s/VisualNOS",     s:gui08, "", s:cterm08, "", ""/VisualNOS",     "", s:gui01, "", s:cterm01, "none"/ |
%s/WildMenu",      s:gui08, s:gui0A, s:cterm08, ""/WildMenu",      s:gui00, s:gui0A, s:cterm00, s:cterm0A/ |

normal =gg
```

## nightshell

- <https://raw.githubusercontent.com/chriskempson/base16-shell/master/scripts/base16-default-light.sh> `376294b`
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
%s#ab/46/42#d4/59/63# |
%s#dc/96/56#d4/6d/59# |
%s#f7/ca/88#bf/95/3f# |
%s#a1/b5/6c#63/94/4a# |
%s#86/c1/b9#56/94/7f# |
%s#7c/af/c2#60/97/bf# |
%s#ba/8b/af#7c/72/ab# |
%s#a1/69/46#ab/80/a4# |

%s/181818/291b14/ge |
%s/383838/523a29/g |
%s/d8d8d8/bfa580/g |
%s/f8f8f8/fff2e0/ge |

call append(123,["",
"echo -ne '\\e]12;#bf953f\\a'"])
```
