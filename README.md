# Plover Dictionaries

[Plover](http://stenoknight.com/wiki/FAQ#What_is_Plover.3F) steno dictionaries in JSON format.

## Punctuation Dictionary

Copy the [`punctuation.json`](https://github.com/dimonster/plover-dictionaries/raw/master/punctuation.json) file into your dictionary folder and add it to your Plover config to use the following briefs:

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





## Australian English Dictionary

This is an Australian English companion dictionary intended to be used in combination with the default Plover dictionary. It overrides default briefs with Australian variations, and also includes Australian prefixes, suffixes, alternative spellings, and vocabulary.

To use this dictionary, copy the [`dict_en_AU.json`](https://github.com/dimonster/plover-dictionaries/raw/master/dict_en_AU.json) file into your dictionary folder and add it to your Plover config after the default Plover dictionary so that it overrides default Plover briefs.



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





## Git Dictionary

Copy the [`git.json`](https://github.com/dimonster/plover-dictionaries/raw/master/git.json) file into your dictionary folder and add it to your Plover config to use the following briefs:

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

Copy the [`ruby.json`](https://github.com/dimonster/plover-dictionaries/raw/master/ruby.json) file into your dictionary folder and add it to your Plover config to use the following briefs:

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

This dictionary consists of common words already available in the default Plover dictionary. If you need only the common words for some reason, copy the [`common-words.json`](https://github.com/dimonster/plover-dictionaries/raw/master/common-words.json) file into your dictionary folder and add it to your Plover config to use the briefs for a thousand or so common English words.
