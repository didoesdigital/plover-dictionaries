# Plover Dictionaries

[Plover](http://stenoknight.com/wiki/FAQ#What_is_Plover.3F) steno dictionaries in JSON format.



## Main Dictionary

Based on [Plover's default `main.json` dictionary](https://github.com/openstenoproject/plover/blob/master/plover/assets/main.json), the main [`dict.json`](https://github.com/dimonster/plover-dictionaries/raw/master/dictionaries/dict.json) file in this repo contains many English words using briefs and phonetic strokes, but contains fewer misstrokes.



## Navigation Dictionary

This dictionary lets you navigate and edit text efficiently on a Mac. You can move the cursor by letter, word, or line, select while doing so, and also backspace or forward delete by character, word, or line. You can also switch tabs, windows, and apps.

To use the following briefs, copy the [`navigation.json`](https://github.com/dimonster/plover-dictionaries/raw/master/dictionaries/navigation.json) file into your dictionary folder and add it to your Plover config:

As per Plover's default, you use `-R`, `-P`, `-B`, and `-G` for left, up, down, and right.

Use `STPH-` to move by character, `STPH-RB` to jump a word left, and `STPH-BG` to jump a word right.

Use `KPH-` to use Command ⌘, jumping to line beginning and ending, file top and bottom.

Use `STP-` (**s**hi**f**t) to select characters with movement keys. Again, `-RB` and `-BG` work by word.

Use `SHR-` (**s**e**l**ect) to select words with the movement keys. (This and the strokes described above actually add redundant strokes for selecting whole words to the left and right.)

Use `PW*` and `-F`, `-FP`, or `-FPL` for backspacing a character, a word, or a line.

Use `PW*` and `-R`, `-RB`, or `-RBG` for forward deleting a character, a word, or a line.

Use `KPHR-` for Command + Option (⌘⌥) movements (usually for navigating tabs and file trees).

Use `SP-B` to space up/forward and `SP-P` to space down/backward. That is, in the browser use the former stroke to page up and the latter to page down (this is using ⇧Space).

Use `THRAB` for ⌥ ⇓ and `THRAP` for ⌥ ⇑.

Use `TW-` and a direction for tabbing. Adding `-F`/`-L` gives you ⌘⇧[/⌘⇧] to switch tabs forward and backward. Adding `-B`/`-G` gives you ⌘\`/⌘⇧\` to switch windows forward and backward. Adding `-G`/`-R` gives you ⌘Tab/⌘⇧Tab to switch applications forward and backward. Adding a star to `TW*G` gives you ⌘Tab Tab to switch 2 applications.



## Punctuation Dictionary

Copy the [`punctuation.json`](https://github.com/dimonster/plover-dictionaries/raw/master/dictionaries/punctuation.json) file into your dictionary folder and add it to your Plover config to use the following briefs:

* . `TP-PL` =&gt; `F-PL` (<strong>f</strong>u<strong>ll</strong> sto<strong>p</strong>, spaced)
* . `P-P` (decimal <strong>p</strong>oint, unspaced)
* ... `SKWR-RBGS` =&gt; `SY-SHUN` (<strong>su</strong>spen<strong>sion</strong> point, then capital)
* ... `HR-PS` =&gt; `L-PS` (e<strong>ll</strong>i<strong>ps</strong>is, then lowercase)
* ? `H-F` (question mark, spaced)
* ! `SKHRAPL` =&gt; `SKLAM` (e<strong>xclam</strong>ation mark, spaced)
* ' `A*E` (opening single quote/<strong>a</strong>postroph<strong>e</strong>, no space)
* ' `AE` (closing single quote/<strong>a</strong>postroph<strong>e</strong>, space)
* " `KW-GS` =&gt; `Q-SHUN` (opening <strong>q</strong>uota<strong>tion</strong> mark, no space)
* " `KR-GS` =&gt; `C-SHUN` (<strong>c</strong>losing quota<strong>tion</strong> mark, space)
* , `KW-BG` (comma, spaced)
* ; `SKWR*RBGS` or `STPH*FPLT` (semi-colon, spaced)
* : `STPH-FPLT` (colon, spaced)
* : `KHR-PB` =&gt; `KL-N` (<strong>c</strong>o<strong>l</strong>o<strong>n</strong>, unspaced)
* - `H-PB` =&gt; `H-PB` (<strong>h</strong>yphe<strong>n</strong>), unspaced
* -- `TK-RB` =&gt; `D-SH` (<strong>d</strong>a<strong>sh</strong>)
* - `PH*PBS` =&gt; `M-NS` (<strong>m</strong>i<strong>n</strong>u<strong>s</strong>, spaced)
* + `PHR*US` => `PL*US` (<strong>plus</strong>)
* = `KWA*LS` =&gt; `QA*LS` (unspaced e<strong>q</strong>u<strong>als</strong>)
* = `KW-L` =&gt; `Q-L` (spaced e<strong>q</strong>ua<strong>l</strong>s)
* * `STA*R` (<strong>star</strong>)
* &lt; `AEPBGT` or `AEPBG` =&gt; `ANGT` (opening <strong>ang</strong>le bracke<strong>t</strong>)
* &gt; `A*EPBGT` or `A*EPBG` =&gt; `A*NGT` (closing <strong>ang</strong>le bracke<strong>t</strong>)
* &lt; `HR*PB` =&gt; `L*N` (<strong>l</strong>ess tha<strong>n</strong>)
* &gt; `TKPWR*PB` =&gt; `GR*N` (<strong>gr</strong>eater tha<strong>n</strong>)
* &lt; `PWRABG` =&gt; `BRAK` (opening angle <strong>bra</strong>c<strong>k</strong>et)
* &gt; `PWRA*BG` =&gt; `BRA*K` (closing angle <strong>bra</strong>c<strong>k</strong>et)
* ( `PREPB` =&gt; `PREN` (opening <strong>p</strong>a<strong>ren</strong>thesis)
* ) `PR*EPB` =&gt; `PR*EN` (closing <strong>p</strong>a<strong>ren</strong>thesis)
* [ `PWR-BGT` =&gt; `BR-KT` (opening <strong>br</strong>ac<strong>k</strong>e<strong>t</strong>)
* ] `PWR*BGT` =&gt; `BR*KT` (closing <strong>br</strong>ac<strong>k</strong>e<strong>t</strong>)
* { `TPR-BGT` =&gt; `FR-KT` (opening <strong>Fr</strong>ench brac<strong>k</strong>e<strong>t</strong>)
* } `TPR*BGT` =&gt; `FR*KT` (closing <strong>Fr</strong>ench brac<strong>k</strong>e<strong>t</strong>)
* / `OEU` (forward slash, unspaced)
* \ `SPWHRAERB` =&gt; `SBLAESH` (<strong>b</strong>ack<strong>slash</strong>)
* ~ `T*LD` (<strong>t</strong>i<strong>ld</strong>e, spaced)
* ~ `T*EULD` (<strong>t</strong>i<strong>ld</strong>e, unspaced)
* @ `KWRAT` =&gt; `YAT` (<strong>at</strong>-sign
* # `HAERB` =&gt; `HAESH` (<strong>hash</strong>)
* $ `TK-PL` =&gt; `D-M` (<strong>d</strong>ollar <strong>m</strong>ark)
* % `PERS` (<strong>perce</strong>nt)
* ^ `KR-RT` =&gt; `C-RT` (<strong>c</strong>a<strong>r</strong>e<strong>t</strong>)
* &amp; `SP-PBD` =&gt; `SP-ND` (am<strong>p</strong>er<strong>sand</strong>)
* _ `R*UPBD` or `RUPBD` =&gt; `RUND` (<strong>und</strong>e<strong>r</strong>score)
* | `PAO*EUP` (<strong>pipe</strong>)
* \` `KH-FG` =&gt; `CH-VG` (<strong>g</strong>ra<strong>v</strong>e <strong>ch</strong>aracter, backwards)
* \` `TR-RL` =&gt; `CH-VG` (opening backquote, grave brief inverted)
* \` `TR*RL` =&gt; `CH-VG` (closing backquote, grave brief inverted)
* <strong>R</strong>eturn key `R-R`
* New paragraph `SKWRAURBGS`
* Undo stroke `*`
* <strong>B</strong>ack<strong>sp</strong>ace `PW-FP` =&gt; `B-SP`
* <strong>D</strong>e<strong>l</strong>ete <strong>s</strong>pace `TK-LS` =&gt; `D-LS`
* Insert <strong>sp</strong>ace `S-P`
* <strong>Cap</strong>ital with a space `KPA`
* <strong>Cap</strong>ital without a space `KPA*`



## Unspaced Punctuation Dictionary

This dictionary uses common briefs for punctuation, but with translations that suppress surrounding spaces (before and after the punctuation) for more precise input. This might be handy for programming, for example.

To use the following briefs, copy the [`unspaced_punctuation.json`](https://github.com/dimonster/plover-dictionaries/raw/master/dictionaries/unspaced_punctuation.json) file into your dictionary folder and add it to your Plover config:

* `EPB/TKA*RB`: –
* `EPL/TKA*RB`: —
* `KH-FG`: \`
* `KR-RT`: ^
* `KA*RT`: ^
* `T*LD`: ~
* `T*EULD`: ~
* `AEPBGT`: <
* `AEPBG`: <
* `A*EPBGT`: >
* `A*EPBG`: >
* `HR*PB`: <
* `TKPWR*PB`: >
* `PWRABG`: <
* `PWRA*BG`: >
* `KWA*LS`: =
* `KW-L`: =
* `KW-LS`: ==
* `KW*LS`: ===
* `PAO*EUP`: \|
* `R*UPB`: _
* `R*UPBD`: _
* `RUPBD`: _
* `H-PB`: -
* `PH*PBS`: -
* `TK-RB`: --
* `OEU`: /
* `SPWHRAERB`: \
* `P-P`: .
* `HR-PS`: ...
* `A*E`: '
* `AE`: '
* `KW-GS`: "
* `KR-GS`: "
* `PREPB`: (
* `PR*EPB`: )
* `PWR*BGT`: ]
* `PWR-BGT`: [
* `TPR-BGT`: {
* `TPR*BGT`: }
* `TK-PL`: $
* `STA*R`: *
* `SP-PBD`: &
* `HAERB`: #
* `PERS`: %
* `PHR*US`: +

There is an additional stroke for an unspaced double quotation mark combining the opening and closing double quotation mark briefs:

* `KWR-GS`: "

You might then remove the usual strokes for opening and closing double quotation marks from your dictionary so you can still use these marks with spacing on demand. You might also replace these entries with smart or curly double quotation marks, for example:

```
"KW-GS": "{“^}",
"KR-GS": "{^”}",
```

You could then write `Test “test” test.` using `KPA* TEFT KW-GS TEFT KR-GS TEFT TP-PL`.

Similarly with single quotation marks (not included in this dictionary):

```
"TP-P": "{‘^}",
"TP-L": "{^’}",
```



## Australian English Dictionary

This is an Australian English companion dictionary intended to be used in combination with the default Plover dictionary. It overrides default briefs with Australian variations, and also includes Australian prefixes, suffixes, alternative spellings, and vocabulary.

To use this dictionary, copy the [`dict_en_AU.json`](https://github.com/dimonster/plover-dictionaries/raw/master/dictionaries/dict_en_AU.json) file into your dictionary folder and add it to your Plover config after the default Plover dictionary so that it overrides default Plover briefs.



### Notes on Design of and Changes in the Australian English Dictionary

- Briefs primarily form the Australian spelling, while longer phonetic strokes may form the US spelling on demand.
- `A*ER`strokes the "aero" prefix for the Australian spelling of aeroplane
- `*EG` strokes the "eing" suffix for words such as "ageing"
- `*LG` strokes the "ling" suffix for words such as "labelling"
- `*LD` strokes the "led" suffix for words such as "labelled"
- `*EPLT` strokes the "ement" suffix for words such as "judgement", "acknowledgement", "lodgement" and "abridgement"
- `O*UR` strokes the "our" suffix for words such as "humour"
- `KWRO*R` strokes the "iour" suffix for words such as "behaviour"
- Add "U" to `O*R` or `TPHOR` strokes for "nour" endings in words such as "honour"
- Add "U" to `O*R` or `TKOR` strokes for "dour" endings in words such as "candour"
- Add "U" to `O*R` or `KHROR` strokes for "our" endings in words such as "colour"
- For words such as "practice" and "practise", the basic rule is that the noun form uses the "c" spelling while the verb uses the "s" spelling. Therefore, translations have been included for producing both.
  - For example, Australian briefs for "defense" with an "s" will use `S` in the brief itself, while Australian briefs for "defence" with a "c" will drop the `S`, eg, `"TKEFS": "defense"`, `"TKE/TPEPB": "defence"`.
  - As another example, drop the `S` or use `KRE` to spell licence with a "c", eg: `"HR-PB": "licence"`, `"HR-PBS": "license",`
- Use "AE" in strokes for Australian "ae" spellings such as "encyclopaedia":
  - The Australian spelling is used in words stroked with `AE` where it would normally use the long "e" sound stroke `AOE`
  - Briefs form the Australian spelling, eg, "KAOEUPL/RA": "chimaera",
  - Words starting with "ae" can be stroked with the prefix `A` such as `"A/AOE/O*PB": "aeon",`
  - The Australian spelling of "gynaecological" uses briefs and phonetic strokes beginning with `TKPWAOEUPB` => "gyne", while the US spelling uses strokes beginning with `SKWREUPB` => "jyn"



### Australian vocabulary

New briefs have been added for Australian [diminuitives](https://en.wikipedia.org/wiki/Diminutives_in_Australian_English), flora, fauna, [slang and more](https://en.wikipedia.org/wiki/Australian_English_vocabulary). For example:

* `"STRA*EU": "Australia",`
* `"STRA*EU/KWRA": "straya",`
* `"PWOE/TKPWAPB": "bogan",`
* `"RE/PHOFL/EUFT": "removalist",`
* `"STRAO*UT": "strewth",`
* `"HROL/HREU": "lolly",`
* `"TKPWAE/TKAEU": "g'day",`
* `"RAO": "roo",`
* `"PHABG/KAS": "Maccas",`



### Changed Briefs

The brief for "programme" is overriden by "pram", requiring a new brief for "program":

    +"PRAPL": "pram",
    +"PRO/TKPWRAPL": "program",

The `*EG` brief for "e.g." is overriden by the "eing" suffix for the Australian spelling of "ageing", requiring a new brief for "e.g.":

    +"AOE/SKWRAO*E": "e.g.",





## Vim Dictionary

Copy the [`vim.json`](https://github.com/dimonster/plover-dictionaries/raw/master/dictionaries/vim.json) file into your dictionary folder and add it to your Plover config to use the following briefs. Note, most strokes use `STPR` to indicate vim (`SR` => `V`):

* `"SREUPL"`: Phonetic brief for "vim".
* `"SR*EUPL"`: Restore brief for "victim" using additional star.
* Punctuation with suppressed spaces to run vim commands (see also: unspaced punctuation dictionary):
    - `"P-P"`: Unspaced period for vim's "last edit" command.
    - `"T*EULD"`: Unspaced tilde for capitalisation. That is, `~`. This brief follows format for tilde `TEULD` with additional star.
    - `"TPHRORB"` => `FLOSH`: Unspaced dollar sign for end of line command.
    - `HR*PB`: Unspaced `<` for left indent.
    - `TKPWR*PB`: Unspaced `>` for right indent.
    - `KW-L`: Unspaced `=`.
    - `OEU`: Unspaced `/` for searching.
* `STPR` and `*`, `-B`, `-G`, `-R` for vim style navigation keys `hjkl`:
    - `"STPR*"`: `h`
    - `"STPR-B"`: `k`
    - `"STPR-G"`: `l`
    - `"STPR-R"`: `j`
    - `"STPR*B"`: `⌃f` to page forward
    - `"STPR*P"`: `⌃b` to page backward
* Move lines up and down in any mode:
    - `.vimrc` mappings are:

            " Move lines up/down using alt j/k when iTerm is set to:
            " Left option (⌥) key acts as Normal
            " In mapping, press opt/alt+j/k to type these characters
            nnoremap ∆ :m .+1<CR>
            nnoremap ˚ :m .-2<CR>

            inoremap ∆ <Esc>:m .+1<CR>gi
            inoremap ˚ <Esc>:m .-2<CR>gi

            vnoremap ∆ :m '>+1<CR>gv=gv
            vnoremap ˚ :m '<-2<CR>gv=gv

    - Briefs are:
        - `"PHR-B"` => `MLB`: Move line up using vim style navigation `k`.
        - `"PHR-R"` => `MLR`: Move line down using vim style navigation `j`.
* `"SPWAO*UT"`: Exit insert mode and start substitution. That is, Escape and `:%s/`.
* `"SR*F"`: Exit insert mode and run command to write buffer (i.e. save the file). That is, Escape, `:w`, and Return. Brief format follows brief for Save command `"S*F"`.
* `"STPR*F"`: Exit insert mode and run command to write buffer (i.e. save the file). That is, Escape, `:w`, and Return. This alternative brief format follows brief for Save command `"S*F"` combined with brief format for most of these vim strokes using `STPR`.
* `"STPROEUFRL"`: Steno lookup shortcut that exits insert mode, yanks inside word to system clipboard (this might be Neovim only) using `"yiw` and runs my shortcut for steno lookup tool `⌃⌘⌥⇧s`. Brief format combines vim brief and regular steno lookup brief `STOEUFRL`. To use your own shortcut, replace this part of the translation `{#Control_L(Alt_L(Shift_L(Super_L(s))))}` with your shortcut command.
* `"STPREFBG"`: Exit insert mode and prepare command to write buffer (i.e. save the file) and quit. That is, Escape and `:x`. Brief format follows vim brief format `STPR` and brief for Escape `TPEFBK`.
* `"STPR-FPLT"`: Exit insert mode and write unspaced colon to enter command mode. That is, Escape and `:`.
* `"STPR-L"`: Runs `gt` to go to next tab. Follows brief format of tabs from tab navigation dictionary.
* `"STPR-F"`: Runs `gT` to go to previous tab. Follows brief format of tabs from tab navigation dictionary.

* Single-stroke Control key (`⌃`) fingerspelling modifier collection:
    - `"A*RBL": "{#Control_L(a)}",`
    - `"PW*RBL": "{#Control_L(b)}",`
    - `"KR*RBL": "{#Control_L(c)}",`
    - `"TK*RBL": "{#Control_L(d)}",`
    - `"*ERBL": "{#Control_L(e)}",`
    - `"TP*RBL": "{#Control_L(f)}",`
    - `"TKPW*RBL": "{#Control_L(g)}",`
    - `"H*RBL": "{#Control_L(h)}",`
    - `"*EURBL": "{#Control_L(i)}",`
    - `"SKWR*RBL": "{#Control_L(j)}",`
    - `"K*RBL": "{#Control_L(k)}",`
    - `"HR*RBL": "{#Control_L(l)}",`
    - `"PH*RBL": "{#Control_L(m)}",`
    - `"TPH*RBL": "{#Control_L(n)}",`
    - `"O*RBL": "{#Control_L(o)}",`
    - `"P*RBL": "{#Control_L(p)}",`
    - `"KW*RBL": "{#Control_L(q)}",`
    - `"R*RBL": "{#Control_L(r)}",`
    - `"S*RBL": "{#Control_L(s)}",`
    - `"T*RBL": "{#Control_L(t)}",`
    - `"*URBL": "{#Control_L(u)}",`
    - `"SR*RBL": "{#Control_L(v)}",`
    - `"W*RBL": "{#Control_L(w)}",`
    - `"KP*RBL": "{#Control_L(x)}",`
    - `"KWR*RBL": "{#Control_L(y)}",`
    - `"STKPW*RBL": "{#Control_L(z)}",`





## Git Dictionary

Copy the [`git.json`](https://github.com/dimonster/plover-dictionaries/raw/master/dictionaries/git.json) file into your dictionary folder and add it to your Plover config to use the following briefs:

* "git" `TKPWEUT`
* "add" `AD`
* " " `S-P`
* "dict" `TKEUBGT`
* " ." `P-P`
* "JSON" `SKWRO*FPB`
* "status" `ST*TS`
* "diff" `TKEUF`
* " --" `TK*RB`
* "cached" `KAERBD`
* "commit" `KPHEUT`
* " -" `H*PB`
* "v" `SR*`
* "log" `HROG`
* "p" `P*`
* "push" `PURB`
* "origin" `O*RPBLG`
* "master" `PHAFRT`
* "pull" `PUL`
* "{re^}" `RE`
* "base" `PWAEUS`
* "check" `KHEBG`
* "-out" `O*UT`
* "hot" `HOT`
* delete space `TK-LS`
* "fix `TPEUBGS`
* "reset" `RE/SET`
* "HEAD" `KPA*E/HED`
* "^" `KR-RT`
* "/" `OEU`





## Ruby Dictionary

Copy the [`ruby.json`](https://github.com/dimonster/plover-dictionaries/raw/master/dictionaries/ruby.json) file into your dictionary folder and add it to your Plover config to use the following briefs:

* "%>" `*ERB/KHRO*EZ` (<strong>ERB close</strong>ing tag)
* "<%=" `*ERB/KPEBG` (<strong>ERB</strong> e<strong>xec</strong>ute tag)
* "<%" `*ERB/O*EP` (<strong>ERB open</strong>ing tag)
* "utf-" `*UFT`
* "utf-8" `*UFT/#L`
* "UTF-" `*UFT/*UFT`
* "ARGV" `A*RG/SR*`
* "ARGF" `A*RG/TP*`
* "attr_accessor" `A*RT/KPES` (<strong>attr</strong> _ ac<strong>cess</strong>or)
* "attr_reader" `A*RT/RAERD` (<strong>attr</strong> _ <strong>reader</strong>)
* "attr_writer" `A*RT/WREUR` (<strong>attr</strong> _ <strong>writer</strong>)
* "after_filter" `AF/TP*EURLT` (<strong>af</strong>ter <strong>filter</strong>)
* "before_filter" `PW-FR/TP*EURLT` (<strong>befor</strong>e <strong>filter</strong>)
* "ERB" `ERB`
* "=>" `HARB/RO*BGT` (<strong>hash rocket</strong>)
* "https://rubygems.org" `HAOEPTS/RO*EUB/SKWREPLS`
* "<<-" `HAOER/TKO*BG` (<strong>heredoc</strong>)
* "<<-ERROR" `HAOER/TKO*BG/ROEUR` (<strong>heredoc</strong> e<strong>rror</strong>)
* "::" `KHR-PBS`  (<strong>c</strong>o<strong>lons</strong>)
* ".html.erb" `P-P/HAOEPLT/ERB`
* "params[:" `PRA*PLS/PWR-BGT`
* "rspec" `R*/SP*EBG`
* "rspec-rerun:spec" `R*/SP*EBG/RE/RUPB/SP*EBG`
* "rspec-rerun/tasks" `R*/SP*EBG/RE/RUPB/TAFBGS`
* "regex" `REG/EBG`
* "regexp" `REG/EBGS`
* "rubygems" `RO*EUB/SKWREPLS`
* "def" `TK-F`
* "nokogiri" `TPHO/KO/TKPWEU/REU`
* "flash[:" `TPHRARB/PWR-BGT`
* "flash[:error]" `TPHRARB/PWR-BGT/ROEUR`
* "flash[:success]" `TPHRARB/PWR-BGT/SKES`
* "flash[:notice]" `TPHRARB/PWR-BGT/TPH-TS`





## Common Words Dictionary

This dictionary consists of common words already available in the default Plover dictionary. If you need only the common words for some reason, copy the [`common-words.json`](https://github.com/dimonster/plover-dictionaries/raw/master/dictionaries/common-words.json) file into your dictionary folder and add it to your Plover config to use the briefs for a thousand or so common English words.
