# MenatQA — 90 fictional Azerbaijani adaptations

Fictional local adaptations in English, not yet translated into Azerbaijani. Personal names use Azerbaijani forms. Descriptive clubs, organizations, offices, roles and biographies are fictional and are not verified real entities or factual histories of real Azerbaijanis.
All source numeric strings, dates, time_scope values, meta.type values, meta.ID values, context paragraph counts and paragraph order are preserved. Counterfactual conditions remain in the question; they are not imposed on or rewritten into the factual context.
Only entity references, culturally specific institutional wording and article agreement required by those substitutions change. Complete original records, original positions and replacement mappings are retained in the audit.
The 90 samples are a draft for human validation. Original gold answers are localized but are not independently certified. Some source passages are truncated, reverse sentence fragments, have missing names, or do not establish a queried month precisely; those defects are not silently repaired.
The scope selection contains 8 extract, 8 narrow, 7 granularity and 7 expand samples. Repeated question/context/answer combinations were avoided within each selected dataset. Related records across datasets are intentionally retained for comparison and are not independent train/test splits.
English spelling and token spacing from the source generally remain. Currency and competition names may be localized where needed; monetary and other numeric amounts remain unchanged.
A source answer with trailing whitespace is retained with that whitespace after its entity is replaced. Unanswerable labels remain exactly unanswerable.

## Counts

| Dataset | Answerable | Unanswerable | Total |
|---|---:|---:|---:|
| counterfactual | 23 | 7 | 30 |
| order | 23 | 7 | 30 |
| scope | 23 | 7 | 30 |

## Scope categories

| Category | Count |
|---|---:|
| extract | 8 |
| narrow | 8 |
| granularity | 7 |
| expand | 7 |

## Counterfactual — 30 samples

### 01. az_menatqa_counterfactual_001

Source record: **7** (1-based). Original meta.ID: `338`. Category: `counterfactual`.

**Question:** Who was the head of Caspian Mathematical Society from 1972 to 1973, if Kamil Şükürov was the head of Caspian Mathematical Society from Mar 1971?

**Answer:** "Kamil Şükürov"

**Context (original paragraph order):**

Paragraph 1: 1971–1974 : Kamil Şükürov ( vice : Əhməd Məcidov , Lətif Vəliyev )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the head of International Mathematical Union from 1972 to 1973, if K . S . Chandrasekharan was the head of International Mathematical Union from Mar 1971?",
  "answer": "K . S . Chandrasekharan",
  "context": [
    "1971–1974 : K . S . Chandrasekharan ( vice : Abraham Adrian Albert , Lev Pontryagin )"
  ],
  "meta": {
    "time_scope": [
      "1971",
      "1974"
    ],
    "annotated_para": "1971–1974 : K . S . Chandrasekharan ( vice : Abraham Adrian Albert , Lev Pontryagin )",
    "type": "counterfactual",
    "ID": 338
  }
}
```

| Original | Localized |
|---|---|
| International Mathematical Union | Caspian Mathematical Society |
| K . S . Chandrasekharan | Kamil Şükürov |
| Abraham Adrian Albert | Əhməd Məcidov |
| Lev Pontryagin | Lətif Vəliyev |

</details>

### 02. az_menatqa_counterfactual_002

Source record: **44** (1-based). Original meta.ID: `977`. Category: `counterfactual`.

**Question:** Who was the chair of Regional Relations and Information Office from 2016 to 2019, if Cəlal Məmmədov resigned as the chair of Regional Relations and Information Office in 2020?

**Answer:** "Cəlal Məmmədov"

**Context (original paragraph order):**

Paragraph 1: The current director of RRIO is Məhərrəm Kazımov Former Directors of the agency include : - Oqtay Həsənov - Pərviz Rəsulov,Cəlal Məmmədov 2014-2018,Cavid Nəcəfov - Kamran Həmidov - İlqar Səlimov - Fəxri Quliyev

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the chair of Office for Foreign Relations and Information from 2016 to 2019, if Jiří Šašek resigned as the chair of Office for Foreign Relations and Information in 2020?",
  "answer": "Jiří Šašek",
  "context": [
    "The current director of USZI is Marek Šimandl Former Directors of the agency include : - Oldřich Černý - Petr Zeman,Jiří Šašek 2014-2018,Jiří Lang - Karel Randák - Ivo Schwarz - František Bublan"
  ],
  "meta": {
    "time_scope": [
      "Jul 2014",
      "Sep 2018"
    ],
    "annotated_para": "- Jiří Šašek 2014-2018",
    "type": "counterfactual",
    "ID": 977
  }
}
```

| Original | Localized |
|---|---|
| Office for Foreign Relations and Information | Regional Relations and Information Office |
| Jiří Šašek | Cəlal Məmmədov |
| USZI | RRIO |
| Marek Šimandl | Məhərrəm Kazımov |
| Oldřich Černý | Oqtay Həsənov |
| Petr Zeman | Pərviz Rəsulov |
| Jiří Lang | Cavid Nəcəfov |
| Karel Randák | Kamran Həmidov |
| Ivo Schwarz | İlqar Səlimov |
| František Bublan | Fəxri Quliyev |

</details>

### 03. az_menatqa_counterfactual_003

Source record: **29** (1-based). Original meta.ID: `938`. Category: `counterfactual`.

**Question:** What position did Mahir Vəliyev take from 2000 to 2002, if Mahir Vəliyev stepped down as the Director of Education in 2003?

**Answer:** "Director of Education"

**Context (original paragraph order):**

Paragraph 1: He was Civic Unity Partys candidate for Head of the National Council in the 2011 election .of Education in the Northern District Executive Council between 1999 and 2002 . 

Paragraph 2: child . He was re-elected to the Regional Assembly in 2001 , 2005 and 2010 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What position did Martin McGuinness take from 2000 to 2002, if Martin McGuinness stepped down as the Minister of Education in 2003?",
  "answer": "Minister of Education",
  "context": [
    "He was Sinn Féins candidate for President of Ireland in the 2011 election .of Education in the Northern Ireland Executive between 1999 and 2002 . ",
    "child . He was re-elected to the Westminster Parliament in 2001 , 2005 and 2010 ."
  ],
  "meta": {
    "time_scope": [
      "Nov 1999",
      "May 2001"
    ],
    "annotated_para": "and was the MP for Mid Ulster from 1997 until his resignation in 2013 . Like all Sinn Féin MPs , McGuinness abstained from participation in the Westminster Parliament . Following the St Andrews Agreement and the Assembly election in 2007 , he became deputy First Minister of Northern Ireland on 8 May 2007 , with the Democratic Unionist Party ( DUP ) leader Ian Paisley becoming First Minister . On 5 June 2008 , he was re-appointed as deputy First Minister to serve alongside Peter Robinson , who succeeded Paisley as First Minister . McGuinness previously served as Minister of Education in the Northern Ireland Executive between 1999 and 2002 . He was Sinn Féins candidate for President of Ireland in the 2011 election .",
    "type": "counterfactual",
    "ID": 938
  }
}
```

| Original | Localized |
|---|---|
| Martin McGuinness | Mahir Vəliyev |
| Minister of | Director of |
| Sinn Féin | Civic Unity Party |
| President of Ireland | Head of the National Council |
| Northern Ireland Executive | Northern District Executive Council |
| Westminster Parliament | Regional Assembly |
| Mid Ulster | Guba District |
| McGuinness | Vəliyev |
| St Andrews Agreement | Shaki Agreement |
| First Minister | Executive Chair |
| Northern Ireland | Northern District |
| Democratic Unionist Party | Regional Unity Party |
| DUP | RUP |
| Ian Paisley | İlham Məcidov |
| Peter Robinson | Pərviz Hacıyev |
| Paisley | Məcidov |

</details>

### 04. az_menatqa_counterfactual_004

Source record: **84** (1-based). Original meta.ID: `873`. Category: `counterfactual`.

**Question:** Where was Ənvər Səfərov educated from 1938 to 1941, if Ənvər Səfərov graduated from Shaki Medical Institute in 1942?

**Answer:** "Shaki Medical Institute"

**Context (original paragraph order):**

Paragraph 1: at Shaki in 1936 . In his fourth year of study Səfərov had decided to either pursue a higher degree in organic chemistry or study medicine . Receiving a scholarship to attend Ganja Medical College in Ganja , he chose the latter .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Where was Edwin G. Krebs educated from 1938 to 1941, if Edwin G. Krebs graduated from University of Illinois at Urbana-Champaign in 1942?",
  "answer": "University of Illinois at Urbana-Champaign",
  "context": [
    "at Urbana-Champaign in 1936 . In his fourth year of study Krebs had decided to either pursue a higher degree in organic chemistry or study medicine . Receiving a scholarship to attend Washington University School of Medicine in St . Louis , he chose the latter ."
  ],
  "meta": {
    "time_scope": [
      "1936",
      "1940"
    ],
    "annotated_para": "Krebs was born in Lansing , Iowa , the third child of William Carl Krebs , a Presbyterian minister and Louise Helen ( Stegeman ) Krebs . The family moved frequently due to the nature of his fathers work , though they settled in Greenville , Illinois when Krebs was six and remained there until his fathers unexpected death in 1933 . Louise Krebs decided to move her family to Urbana , Illinois , where Krebss elder brothers were attending the University of Illinois at Urbana-Champaign . Krebs attended Urbana High School , and enrolled at the University of Illinois at Urbana-Champaign in 1936 . In his fourth year of study Krebs had decided to either pursue a higher degree in organic chemistry or study medicine . Receiving a scholarship to attend Washington University School of Medicine in St . Louis , he chose the latter .",
    "type": "counterfactual",
    "ID": 873
  }
}
```

| Original | Localized |
|---|---|
| Edwin G. Krebs | Ənvər Səfərov |
| University of Illinois at Urbana-Champaign | Shaki Medical Institute |
| Urbana-Champaign | Shaki |
| Krebs | Səfərov |
| Washington University School of Medicine | Ganja Medical College |
| St . Louis | Ganja |
| Lansing , Iowa | Goychay , Shirvan |
| William Carl Krebs | Vəli Səfərov |
| a Presbyterian minister | a schoolteacher |
| Louise Helen ( Stegeman ) Krebs | Lalə Səfərova |
| Greenville , Illinois | Shaki , Azerbaijan |
| Louise Krebs | Lalə Səfərova |
| Urbana , Illinois | Shaki , Azerbaijan |
| Urbana High School | Shaki Central School |

</details>

### 05. az_menatqa_counterfactual_005

Source record: **72** (1-based). Original meta.ID: `888`. Category: `counterfactual`.

**Question:** Rəna Nəsirova took which position from 2005 to 2008, if Rəna Nəsirova resigned as the Regional Assembly Member in 2009?

**Answer:** "Regional Assembly Member"

**Context (original paragraph order):**

Paragraph 1: She was formerly Member of Parliament ( MP ) for Shaki and Gakh from 1995 to 1997 then for Shaki 1997 to 2001 .She served as the Regional Assembly Member ( MSP ) for Shaki from 1999 to 2011 , and then for Southern Shaki and Gakh from 2011 to 2021 . 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Roseanna Cunningham took which position from 2005 to 2008, if Roseanna Cunningham resigned as the Member of the Scottish Parliament in 2009?",
  "answer": "Member of the Scottish Parliament",
  "context": [
    "She was formerly Member of Parliament ( MP ) for Perth and Kinross from 1995 to 1997 then for Perth 1997 to 2001 .She served as the Member of the Scottish Parliament ( MSP ) for Perth from 1999 to 2011 , and then for Perthshire South and Kinross-shire from 2011 to 2021 . "
  ],
  "meta": {
    "time_scope": [
      "May 2003",
      "Apr 2007"
    ],
    "annotated_para": "She served as the Member of the Scottish Parliament ( MSP ) for Perth from 1999 to 2011 , and then for Perthshire South and Kinross-shire from 2011 to 2021 . She was formerly Member of Parliament ( MP ) for Perth and Kinross from 1995 to 1997 then for Perth 1997 to 2001 .",
    "type": "counterfactual",
    "ID": 888
  }
}
```

| Original | Localized |
|---|---|
| Roseanna Cunningham | Rəna Nəsirova |
| Member of the Scottish Parliament | Regional Assembly Member |
| Perth and Kinross | Shaki and Gakh |
| Perth | Shaki |
| Perthshire South and Kinross-shire | Southern Shaki and Gakh |

</details>

### 06. az_menatqa_counterfactual_006

Source record: **184** (1-based). Original meta.ID: `690`. Category: `counterfactual`.

**Question:** Who owned The Flute Player from 1876 to 1890, if  The Flute Player belonged to Zaur Məcidov from 1875?

**Answer:** "Zaur Məcidov"

**Context (original paragraph order):**

Paragraph 1: It was included in a large exhibition of Vaqif İsmayılovs work in 1884 , a year after his premature death .Between 1873 and 1893 , the painting was owned by Vaqif İsmayılovs friend , composer and baritone Zaur Məcidov .  The painting was acquired by Qasımov Art Gallery in 1872 and again in 1893 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who owned The Fifer from 1876 to 1890, if  The Fifer belonged to Jean-Baptiste Faure from 1875?",
  "answer": "Jean-Baptiste Faure",
  "context": [
    "It was included in a large exhibition of Manets work in 1884 , a year after his premature death .Between 1873 and 1893 , the painting was owned by Manets friend , composer and baritone Jean-Baptiste Faure .  The painting was acquired by Durand-Ruell in 1872 and again in 1893 ."
  ],
  "meta": {
    "time_scope": [
      "1873",
      "1893"
    ],
    "annotated_para": "The painting was acquired by Durand-Ruell in 1872 and again in 1893 . Between 1873 and 1893 , the painting was owned by Manets friend , composer and baritone Jean-Baptiste Faure . It was included in a large exhibition of Manets work in 1884 , a year after his premature death .",
    "type": "counterfactual",
    "ID": 690
  }
}
```

| Original | Localized |
|---|---|
| The Fifer | The Flute Player |
| Jean-Baptiste Faure | Zaur Məcidov |
| Manet | Vaqif İsmayılov |
| Durand-Ruell | Qasımov Art Gallery |

</details>

### 07. az_menatqa_counterfactual_007

Source record: **200** (1-based). Original meta.ID: `569`. Category: `counterfactual`.

**Question:** What was the occupation of Tofiq Həsənli from 1967 to 1969, if Tofiq Həsənli served as the National Council aide from 1966?

**Answer:** "National Council aide"

**Context (original paragraph order):**

Paragraph 1: From 1969 to 1970 he served as a National Council aide during the Presidency of Rəhim Kazımov .He was one of the founders of the Regional Policy Society , a public policy organization aligned with the Civic Reform Party . He served as a volunteer with the Regional Volunteer Service in Shirvan from 1966-1967 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the occupation of Tom Petri from 1967 to 1969, if Tom Petri served as the White House aide from 1966?",
  "answer": "White House aide",
  "context": [
    "From 1969 to 1970 he served as a White House aide during the Presidency of Richard Nixon .He was one of the founders of the Ripon Society , a public policy organization aligned with the Republican Party . He served as a volunteer with the Peace Corps in Somalia from 1966-1967 "
  ],
  "meta": {
    "time_scope": [
      "1969",
      "1970"
    ],
    "annotated_para": "He served as a volunteer with the Peace Corps in Somalia from 1966-1967 . From 1969 to 1970 he served as a White House aide during the Presidency of Richard Nixon .",
    "type": "counterfactual",
    "ID": 569
  }
}
```

| Original | Localized |
|---|---|
| Tom Petri | Tofiq Həsənli |
| White House aide | National Council aide |
| Richard Nixon | Rəhim Kazımov |
| Ripon Society | Regional Policy Society |
| Republican Party | Civic Reform Party |
| Peace Corps | Regional Volunteer Service |
| Somalia | Shirvan |

</details>

### 08. az_menatqa_counterfactual_008

Source record: **153** (1-based). Original meta.ID: `568`. Category: `counterfactual`.

**Question:** What was Tofiq Həsənli's occupation from 1966 to 1968, if Tofiq Həsənli resigned from volunteer with the Regional Volunteer Service in 1969?

**Answer:** "volunteer with the Regional Volunteer Service"

**Context (original paragraph order):**

Paragraph 1: From 1969 to 1970 he served as a National Council aide during the Presidency of Rəhim Kazımov . He was one of the founders of the Regional Policy Society , a public policy organization aligned with the Civic Reform Party . He served as a volunteer with the Regional Volunteer Service in Shirvan from 1966-1967 . 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was Tom Petri's occupation from 1966 to 1968, if Tom Petri resigned from volunteer with the Peace Corps in 1969?",
  "answer": "volunteer with the Peace Corps",
  "context": [
    "From 1969 to 1970 he served as a White House aide during the Presidency of Richard Nixon . He was one of the founders of the Ripon Society , a public policy organization aligned with the Republican Party . He served as a volunteer with the Peace Corps in Somalia from 1966-1967 . "
  ],
  "meta": {
    "time_scope": [
      "1966",
      "1967"
    ],
    "annotated_para": "He served as a volunteer with the Peace Corps in Somalia from 1966-1967 . From 1969 to 1970 he served as a White House aide during the Presidency of Richard Nixon .",
    "type": "counterfactual",
    "ID": 568
  }
}
```

| Original | Localized |
|---|---|
| Tom Petri | Tofiq Həsənli |
| Peace Corps | Regional Volunteer Service |
| White House aide | National Council aide |
| Richard Nixon | Rəhim Kazımov |
| Ripon Society | Regional Policy Society |
| Republican Party | Civic Reform Party |
| Somalia | Shirvan |

</details>

### 09. az_menatqa_counterfactual_009

Source record: **154** (1-based). Original meta.ID: `163`. Category: `counterfactual`.

**Question:** Who was Sənan Rəsulov's spouse from 2003 to 2008, if Leyla Hacıyeva and Sənan Rəsulov divorced in 2010?

**Answer:** "Leyla Hacıyeva"

**Context (original paragraph order):**

Paragraph 1: Kamil Nəsirov ( born 1975 ) together with Vəfa Nəsirova and the youngest child Mahir . From 2003 until his death he was married to Leyla Hacıyeva . Rəsulov had five children ; Yeganə ( 1962–1992 ) and Səbinə Rəsulov ( born 1964 ) together with Aynur Məcidova , Lalə Rəsulov together with Elnarə Səfərova 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was Sven Wollter's spouse from 2003 to 2008, if Lisa Wede and Sven Wollter divorced in 2010?",
  "answer": "Lisa Wede",
  "context": [
    "Karl Seldahl ( born 1975 ) together with Viveka Seldahl and the youngest child Magnus . From 2003 until his death he was married to Lisa Wede . Wollter had five children ; Ylva ( 1962–1992 ) and Stina Wollter ( born 1964 ) together with Annie Jenhoff , Lina Wollter together with Evabritt Strandberg "
  ],
  "meta": {
    "time_scope": [
      "2003",
      "2004"
    ],
    "annotated_para": "Wollter had five children ; Ylva ( 1962–1992 ) and Stina Wollter ( born 1964 ) together with Annie Jenhoff , Lina Wollter together with Evabritt Strandberg , Karl Seldahl ( born 1975 ) together with Viveka Seldahl and the youngest child Magnus . From 2003 until his death he was married to Lisa Wede .",
    "type": "counterfactual",
    "ID": 163
  }
}
```

| Original | Localized |
|---|---|
| Sven Wollter | Sənan Rəsulov |
| Lisa Wede | Leyla Hacıyeva |
| Karl Seldahl | Kamil Nəsirov |
| Viveka Seldahl | Vəfa Nəsirova |
| Magnus | Mahir |
| Wollter | Rəsulov |
| Ylva | Yeganə |
| Stina | Səbinə |
| Annie Jenhoff | Aynur Məcidova |
| Lina | Lalə |
| Evabritt Strandberg | Elnarə Səfərova |

</details>

### 10. az_menatqa_counterfactual_010

Source record: **193** (1-based). Original meta.ID: `269`. Category: `counterfactual`.

**Question:** Which title was conferred to İradə Quliyeva in 1975, if Woman Grandmaster was conferred to İradə Quliyeva in 1974?

**Answer:** "Woman Grandmaster"

**Context (original paragraph order):**

Paragraph 1: In chess , she has been a World Championship Candidate in 1984 and gained the title Woman Grandmaster . In contract bridge she has won five world championship events , four women and two mixed , including play on two world-champion regional womens teams .İradə Quliyeva ( born June 8 , 1954 ) is an Azerbaijani chess and bridge player . 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which title was conferred to Irina Levitina in 1975, if Woman Grandmaster was conferred to Irina Levitina in 1974?",
  "answer": "Woman Grandmaster",
  "context": [
    "In chess , she has been a World Championship Candidate in 1984 and gained the title Woman Grandmaster . In contract bridge she has won five world championship events , four women and two mixed , including play on two world-champion USA women teams .Irina Solomonovna Levitina ( born June 8 , 1954 ) is a Russian-American chess and bridge player . "
  ],
  "meta": {
    "time_scope": [
      "1976",
      "1976"
    ],
    "annotated_para": "Irina Solomonovna Levitina ( born June 8 , 1954 ) is a Russian-American chess and bridge player . In chess , she has been a World Championship Candidate in 1984 and gained the title Woman Grandmaster . In contract bridge she has won five world championship events , four women and two mixed , including play on two world-champion USA women teams .",
    "type": "counterfactual",
    "ID": 269
  }
}
```

| Original | Localized |
|---|---|
| Irina Levitina | İradə Quliyeva |
| USA women teams | regional womens teams |
| Irina Solomonovna Levitina | İradə Quliyeva |
| Russian-American | Azerbaijani |

</details>

### 11. az_menatqa_counterfactual_011

Source record: **147** (1-based). Original meta.ID: `483`. Category: `counterfactual`.

**Question:** Mahir Rəhimov took which position from 2009 to 2011, if Mahir Rəhimov elected to president of the Caspian Football Association in 2008?

**Answer:** "president of the Caspian Football Association"

**Context (original paragraph order):**

Paragraph 1:  He is an Azerbaijani from Shamakhi , Shirvan . Rəhimov was elected president of the Caspian Football Association in 2003 and re-elected for another term in 2010 . On 22 March 2012 , he replaced Rəşid Məmmədov on the Regional Football Executive Committee . On 16 April 2014 , Rəhimov was elected to replace Cəfər Rəsulov as president of the Regional Football Confederation in 2015 . Involvement with Regional Football Scandal .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Marco Polo Del Nero took which position from 2009 to 2011, if Marco Polo Del Nero elected to president of the Federação Paulista de Futebol in 2008?",
  "answer": "president of the Federação Paulista de Futebol",
  "context": [
    " He is a Brazilian of Italian origins from Montazzoli , Abruzzo . Del Nero was elected president of the Federação Paulista de Futebol in 2003 and re-elected for another term in 2010 . On 22 March 2012 , he replaced Ricardo Teixeira on the FIFA Executive Committee . On 16 April 2014 , Del Nero was elected to replace José Maria Marin as president of the Brazilian Football Confederation in 2015 . Involvement with FIFA Scandal ."
  ],
  "meta": {
    "time_scope": [
      "2007",
      "2012"
    ],
    "annotated_para": "Del Nero was elected president of the Federação Paulista de Futebol in 2003 and re-elected for another term in 2010 . On 22 March 2012 , he replaced Ricardo Teixeira on the FIFA Executive Committee .",
    "type": "counterfactual",
    "ID": 483
  }
}
```

| Original | Localized |
|---|---|
| Marco Polo Del Nero | Mahir Rəhimov |
| Federação Paulista de Futebol | Caspian Football Association |
| Brazilian of Italian origins from Montazzoli , Abruzzo | Azerbaijani from Shamakhi , Shirvan |
| Del Nero | Rəhimov |
| Ricardo Teixeira | Rəşid Məmmədov |
| FIFA Executive Committee | Regional Football Executive Committee |
| José Maria Marin | Cəfər Rəsulov |
| Brazilian Football Confederation | Regional Football Confederation |
| FIFA Scandal | Regional Football Scandal |

</details>

### 12. az_menatqa_counterfactual_012

Source record: **30** (1-based). Original meta.ID: `102`. Category: `counterfactual`.

**Question:** Who was Pərviz Səlimov's spouse from 1970 to 1984, if Gülnar Rzayeva and Pərviz Səlimov got married in 1969?

**Answer:** "Gülnar Rzayeva"

**Context (original paragraph order):**

Paragraph 1: Səlimov was then married to actress Təranə Əsədova from 1985 to 1998 . He and his third wife , cellist Aygün Rəsulova , primarily reside in Ganja . They often appear as soloists together .Səlimov was married to Gülnar Rzayeva in 1968 . The couple had two daughters together , opera singer Ayan Səlimov and blues/folk musician Nigar Səlimov . They frequently appeared together in concert until their divorce in 1985 . 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was Pinchas Zukerman's spouse from 1970 to 1984, if Eugenia Rich and Pinchas Zukerman got married in 1969?",
  "answer": "Eugenia Rich",
  "context": [
    "Zukerman was then married to actress Tuesday Weld from 1985 to 1998 . He and his third wife , cellist Amanda Forsyth , primarily reside in New York City . They often appear as soloists together .Zukerman was married to Eugenia Rich in 1968 . The couple had two daughters together , opera singer Arianna Zukerman and blues/folk musician Natalia Zukerman . They frequently appeared together in concert until their divorce in 1985 . "
  ],
  "meta": {
    "time_scope": [
      "1968",
      "1985"
    ],
    "annotated_para": "Zukerman was married to Eugenia Rich in 1968 . The couple had two daughters together , opera singer Arianna Zukerman and blues/folk musician Natalia Zukerman . They frequently appeared together in concert until their divorce in 1985 . Zukerman was then married to actress Tuesday Weld from 1985 to 1998 . He and his third wife , cellist Amanda Forsyth , primarily reside in New York City . They often appear as soloists together .",
    "type": "counterfactual",
    "ID": 102
  }
}
```

| Original | Localized |
|---|---|
| Pinchas Zukerman | Pərviz Səlimov |
| Eugenia Rich | Gülnar Rzayeva |
| Zukerman | Səlimov |
| Tuesday Weld | Təranə Əsədova |
| Amanda Forsyth | Aygün Rəsulova |
| New York City | Ganja |
| Arianna | Ayan |
| Natalia | Nigar |

</details>

### 13. az_menatqa_counterfactual_013

Source record: **66** (1-based). Original meta.ID: `897`. Category: `counterfactual`.

**Question:** Where was Musa Rzayev educated from 1965 to 1972, if Musa Rzayev graduated from Ganja Pedagogical Institute from 1973?

**Answer:** "Ganja Pedagogical Institute"

**Context (original paragraph order):**

Paragraph 1: After graduating from high school , Rzayev enlisted in the Caspian Coastal Air Service , and served in the Caspian Sea on the destroyer Caspian Training Ship . After being honorably discharged , he spent two years working as a laborer in a cement plant . While in college he earned his tuition working as a toll collector on the Ganja Regional Highway . He graduated from the Ganja Pedagogical Institute with a B.A . in 1968 and an M.A . in 1970 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Where was Maurice Hinchey educated from 1965 to 1972, if Maurice Hinchey graduated from New Paltz from 1973?",
  "answer": "New Paltz",
  "context": [
    "After graduating from high school , Hinchey enlisted in the U.S . Navy , and served in the Pacific on the destroyer USS Marshall . After being honorably discharged , he spent two years working as a laborer in a cement plant . While in college he earned his tuition working as a toll collector on the New York State Thruway . He graduated from the State University of New York at New Paltz with a B.A . in 1968 and an M.A . in 1970 ."
  ],
  "meta": {
    "time_scope": [
      "1956",
      "1970"
    ],
    "annotated_para": "After graduating from high school , Hinchey enlisted in the U.S . Navy , and served in the Pacific on the destroyer USS Marshall . After being honorably discharged , he spent two years working as a laborer in a cement plant . While in college he earned his tuition working as a toll collector on the New York State Thruway . He graduated from the State University of New York at New Paltz with a B.A . in 1968 and an M.A . in 1970 .",
    "type": "counterfactual",
    "ID": 897
  }
}
```

| Original | Localized |
|---|---|
| Maurice Hinchey | Musa Rzayev |
| New Paltz | Ganja Pedagogical Institute |
| Hinchey | Rzayev |
| U.S . Navy | Caspian Coastal Air Service |
| the Pacific | the Caspian Sea |
| USS Marshall | Caspian Training Ship |
| New York State Thruway | Ganja Regional Highway |
| State University of New York at New Paltz | Ganja Pedagogical Institute |

</details>

### 14. az_menatqa_counterfactual_014

Source record: **86** (1-based). Original meta.ID: `694`. Category: `counterfactual`.

**Question:** Akif Rəsulov went to which school from 1964 to 1966, if Akif Rəsulov joined in Shaki Psychology Institute from 1963?

**Answer:** "Shaki Psychology Institute"

**Context (original paragraph order):**

Paragraph 1: He went on leave to become a Sumgait City Council member in 1992 . He remained on leave for several years until retiring in 1998 .In 1969 , Rəsulov moved to Sumgait and became a professor of community psychology at Sumgait Social Sciences College .Rəsulov was born and raised in Nizami District , Ganja . His family is Azerbaijani . He graduated with a B.A . from Goychay Humanities College and earned a Ph.D . from Shaki Psychology Institute . 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Alan Lowenthal went to which school from 1964 to 1966, if Alan Lowenthal joined in Ohio State University from 1963?",
  "answer": "Ohio State University",
  "context": [
    "He went on leave to become a Long Beach City Councilman in 1992 . He remained on leave for several years until retiring in 1998 .In 1969 , Lowenthal moved to Long Beach and became a professor of community psychology at California State University , Long Beach .Lowenthal was born and raised in Queens , New York City . His family is Jewish . He graduated with a B.A . from Hobart College and earned a Ph.D . from Ohio State University . "
  ],
  "meta": {
    "time_scope": [
      "1962",
      "1967"
    ],
    "annotated_para": "Lowenthal was born and raised in Queens , New York City . His family is Jewish . He graduated with a B.A . from Hobart College and earned a Ph.D . from Ohio State University . In 1969 , Lowenthal moved to Long Beach and became a professor of community psychology at California State University , Long Beach . He went on leave to become a Long Beach City Councilman in 1992 . He remained on leave for several years until retiring in 1998 .",
    "type": "counterfactual",
    "ID": 694
  }
}
```

| Original | Localized |
|---|---|
| Alan Lowenthal | Akif Rəsulov |
| Ohio State University | Shaki Psychology Institute |
| Long Beach City Councilman | Sumgait City Council member |
| Lowenthal | Rəsulov |
| Long Beach | Sumgait |
| California State University , Long Beach | Sumgait Social Sciences College |
| Queens , New York City | Nizami District , Ganja |
| Jewish | Azerbaijani |
| Hobart College | Goychay Humanities College |

</details>

### 15. az_menatqa_counterfactual_015

Source record: **32** (1-based). Original meta.ID: `551`. Category: `counterfactual`.

**Question:** Which school did Adil Nəsirov go to from 1902 to 1905, if Adil Nəsirov joined in Shamakhi Higher Studies Institute from 1901

**Answer:** "Shamakhi Higher Studies Institute"

**Context (original paragraph order):**

Paragraph 1:  He graduated from Baku Legal Education Institute in 1912 , and returned to Shirvan . There he was admitted to the bar the same year and commenced practice in Shamakhi , Azerbaijan .He attended Shamakhi Higher Studies Institute ( SHSI ) from 1903 to 1906 , and Ganja Technical College ( GTC ) from 1909 to 1910 . Nəsirov was born in Goychay , Shirvan , Azerbaijan to Əli Nəsirov ( 1864–1959 ) and Elmira Quliyeva ( 1864–1947 ) . He was the eldest of 6 siblings .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which school did Arthur Vivian Watkins go to from 1902 to 1905, if Arthur Vivian Watkins joined in Brigham Young University from 1901",
  "answer": "Brigham Young University",
  "context": [
    " He graduated from Columbia University Law School in 1912 , and returned to Utah . There he was admitted to the bar the same year and commenced practice in Vernal , Utah .He attended Brigham Young University ( BYU ) from 1903 to 1906 , and New York University ( NYU ) from 1909 to 1910 . Watkins was born in Midway , Wasatch County , Utah to Arthur Watkins ( 1864–1959 ) and Emily Adelia Gerber ( 1864–1947 ) . He was the eldest of 6 siblings ."
  ],
  "meta": {
    "time_scope": [
      "1903",
      "1906"
    ],
    "annotated_para": "Watkins was born in Midway , Wasatch County , Utah to Arthur Watkins ( 1864–1959 ) and Emily Adelia Gerber ( 1864–1947 ) . He was the eldest of 6 siblings . He attended Brigham Young University ( BYU ) from 1903 to 1906 , and New York University ( NYU ) from 1909 to 1910 . He graduated from Columbia University Law School in 1912 , and returned to Utah . There he was admitted to the bar the same year and commenced practice in Vernal , Utah .",
    "type": "counterfactual",
    "ID": 551
  }
}
```

| Original | Localized |
|---|---|
| Arthur Vivian Watkins | Adil Nəsirov |
| Brigham Young University | Shamakhi Higher Studies Institute |
| Columbia University Law School | Baku Legal Education Institute |
| Utah | Shirvan |
| Vernal , Utah | Shamakhi , Azerbaijan |
| BYU | SHSI |
| New York University | Ganja Technical College |
| NYU | GTC |
| Watkins | Nəsirov |
| Midway , Wasatch County , Utah | Goychay , Shirvan , Azerbaijan |
| Arthur Watkins | Əli Nəsirov |
| Emily Adelia Gerber | Elmira Quliyeva |

</details>

### 16. az_menatqa_counterfactual_016

Source record: **27** (1-based). Original meta.ID: `237`. Category: `counterfactual`.

**Question:** What operated Caspian (locomotive) from 1921 to 1923, if Shaki Valley Railway operated Caspian (locomotive) from 1920?

**Answer:** "Shaki Valley Railway"

**Context (original paragraph order):**

Paragraph 1: Shaki Valley Railway , which it did from 1900 until 1924 , when it was scrapped .

Paragraph 2: Caspian was withdrawn in 1923 and scrapped at Ganja Railway Workshop in 1924 , having never carried its RRS number .The Shaki Valley Railway was taken over by the Regional Railway Service ( RRS ) in 1923 and the locomotive was allocated the number 1198 . In 1904 , the locomotive was fitted with a conventional chimney , and at some point was fitted with a steel cab back .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What operated Rheidol (locomotive) from 1921 to 1923, if Vale of Rheidol Railway operated Rheidol (locomotive) from 1920?",
  "answer": "Vale of Rheidol Railway",
  "context": [
    "Vale of Rheidol Railway , which it did from 1900 until 1924 , when it was scrapped .",
    "Rheidol was withdrawn in 1923 and scrapped at Swindon Works in 1924 , having never carried its GWR number .The Vale of Rheidol Railway was taken over by the Great Western Railway ( GWR ) in 1923 and the locomotive was allocated the number 1198 . In 1904 , the locomotive was fitted with a conventional chimney , and at some point was fitted with a steel cab back ."
  ],
  "meta": {
    "time_scope": [
      "1922",
      "1924"
    ],
    "annotated_para": "Rheidol , formerly named Treze de Maio and Talybont , was a steam locomotive built by W.G . Bagnall in Staffordshire , England , in 1896 . Originally built to a gauge of , it was ordered to work at a Brazilian sugar plantation , however the order was cancelled before it was exported . The locomotive was then regauged and renamed to work on the -gauge Plynlimon and Hafan Tramway , in Wales , where the locomotive worked from August 1897 until 1899 . It was then regauged and renamed a second time , to work on the -gauge Vale of Rheidol Railway , which it did from 1900 until 1924 , when it was scrapped .",
    "type": "counterfactual",
    "ID": 237
  }
}
```

| Original | Localized |
|---|---|
| Rheidol (locomotive) | Caspian (locomotive) |
| Vale of Rheidol Railway | Shaki Valley Railway |
| Rheidol | Caspian |
| Swindon Works | Ganja Railway Workshop |
| GWR | RRS |
| Great Western Railway | Regional Railway Service |
| Treze de Maio | Shirvan |
| Talybont | Goychay |
| W.G . Bagnall | Quliyev Engineering |
| Staffordshire , England | Shirvan , Azerbaijan |
| Brazilian sugar plantation | regional sugar plantation |
| Plynlimon and Hafan Tramway | Goychay Tramway |
| Wales | Shaki District |

</details>

### 17. az_menatqa_counterfactual_017

Source record: **71** (1-based). Original meta.ID: `785`. Category: `counterfactual`.

**Question:** Which position did Rəşid Qasımov hold from 1926 to 1927, if Rəşid Qasımov became member of the Guba Education Board from 1925?

**Answer:** "member of the Guba Education Board"

**Context (original paragraph order):**

Paragraph 1:  He was a candidate for Head of the Northern District in the 1938 election .He was a member of the Northern Regional Council from 1931 to 1934 .  He was city attorney of Guba from 1928 to 1938 . He was a member of the Guba Education Board from 1924 to 1932 .He was in private practice of law in Guba , Northern District from 1920 to 1956 . He was county attorney of Gusar District from 1918 to 1920 .same year . He was in private practice of law in Gusar from 1915 to 1920 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which position did Ross Rizley hold from 1926 to 1927, if Ross Rizley became member of the Guymon Board of Education from 1925?",
  "answer": "member of the Guymon Board of Education",
  "context": [
    " He was a candidate for Governor of Oklahoma in the 1938 election .He was a member of the Oklahoma Senate from 1931 to 1934 .  He was city attorney of Guymon from 1928 to 1938 . He was a member of the Guymon Board of Education from 1924 to 1932 .He was in private practice of law in Guymon , Oklahoma from 1920 to 1956 . He was county attorney of Beaver County from 1918 to 1920 .same year . He was in private practice of law in Beaver from 1915 to 1920 ."
  ],
  "meta": {
    "time_scope": [
      "1924",
      "1928"
    ],
    "annotated_para": "Born on a farm near the town of Beaver in Beaver County of the Oklahoma Territory , the son of Anabella Narcissus ( McCown ) and Robert Martin Rizley , Rizley attended the public schools and taught in the rural schools of Beaver County in 1909 and 1910 . He served as a deputy register of deeds in Beaver County in 1911 and 1912 . He received a Bachelor of Laws from the Kansas City School of Law ( now the University of Missouri–Kansas City School of Law ) in 1915 and was admitted to the bar in Oklahoma the same year . He was in private practice of law in Beaver from 1915 to 1920 . He was county attorney of Beaver County from 1918 to 1920 . He was in private practice of law in Guymon , Oklahoma from 1920 to 1956 . He was a member of the Guymon Board of Education from 1924 to 1932 . He was city attorney of Guymon from 1928 to 1938 . He was a member of the Oklahoma Senate from 1931 to 1934 . He was a candidate for Governor of Oklahoma in the 1938 election . He was a United States Representative from Oklahoma from 1941 to 1949 . He was solicitor for the United States Post Office Department ( now the United States Postal Service ) in 1953 . He was an Assistant United States Secretary of Agriculture from 1953 to 1954 . He was Chairman of the Civil Aeronautics Board from 1955 to 1956 .",
    "type": "counterfactual",
    "ID": 785
  }
}
```

| Original | Localized |
|---|---|
| Ross Rizley | Rəşid Qasımov |
| Guymon Board of Education | Guba Education Board |
| Governor of Oklahoma | Head of the Northern District |
| Oklahoma Senate | Northern Regional Council |
| Guymon | Guba |
| Guymon , Oklahoma | Guba , Northern District |
| Beaver County | Gusar District |
| Beaver | Gusar |
| Oklahoma Territory | Northern District |
| Anabella Narcissus ( McCown ) | Aynur Məcidova |
| Robert Martin Rizley | Rafiq Qasımov |
| Rizley | Qasımov |
| Kansas City School of Law | Ganja Law College |
| University of Missouri–Kansas City School of Law | Ganja Legal Studies University |
| Oklahoma | Northern District |
| United States | Azerbaijan |

</details>

### 18. az_menatqa_counterfactual_018

Source record: **198** (1-based). Original meta.ID: `168`. Category: `counterfactual`.

**Question:** Who directed or managed Caspian Policy Planning Centre from 1977 to 1983, if Bəxtiyar Rzayev directed  Caspian Policy Planning Centre from 1976?

**Answer:** "Bəxtiyar Rzayev"

**Context (original paragraph order):**

Paragraph 1: Rafiq İbrahimov ( 2010-2013 ) - Sərxan Əsədov ( 2013-2019 ) - Əliyar Əhmədov ( 2019- )İlham Nəcəfov ( 1999-2002 ) - Namiq Səlimov ( 2005-2010 ) - Lalə Vəliyeva ( 2010 ) Fərid Rəhmanov ( 1993-1995 ) - Hafiz Cabbarov ( 1995-1999 , 2002-2004 ) Ceyhun Qasımov ( 1984-1989 ) - Eldar Quliyev ( 1989-1993 )  Akif İsmayılov ( 1974-1978 ) - Bəxtiyar Rzayev ( 1979-1984 ) The CPPC has a history of renowned directors , either academics or career diplomats .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who directed or managed Policy Planning Staff (France) from 1977 to 1983, if Jean-Louis Gergorin directed  Policy Planning Staff (France) from 1976?",
  "answer": "Jean-Louis Gergorin",
  "context": [
    "Joseph Maïla ( 2010-2013 ) - Justin Vaïsse ( 2013-2019 ) - Manuel Lafont Rapnouil ( 2019- )Michel Foucher ( 1999-2002 ) - Pierre Lévy ( 2005-2010 ) - Marie Mendras ( 2010 ) Bruno Racine ( 1993-1995 ) - Gilles Andréani ( 1995-1999 , 2002-2004 ) Philippe Coste ( 1984-1989 ) - Jean-Marie Guéhenno ( 1989-1993 )  Thierry de Montbrial ( 1974-1978 ) - Jean-Louis Gergorin ( 1979-1984 ) The CAPS has a history of renowned directors , either academics or career diplomats ."
  ],
  "meta": {
    "time_scope": [
      "1979",
      "1984"
    ],
    "annotated_para": "- Jean-Louis Gergorin ( 1979-1984 )",
    "type": "counterfactual",
    "ID": 168
  }
}
```

| Original | Localized |
|---|---|
| Policy Planning Staff (France) | Caspian Policy Planning Centre |
| Jean-Louis Gergorin | Bəxtiyar Rzayev |
| Joseph Maïla | Rafiq İbrahimov |
| Justin Vaïsse | Sərxan Əsədov |
| Manuel Lafont Rapnouil | Əliyar Əhmədov |
| Michel Foucher | İlham Nəcəfov |
| Pierre Lévy | Namiq Səlimov |
| Marie Mendras | Lalə Vəliyeva |
| Bruno Racine | Fərid Rəhmanov |
| Gilles Andréani | Hafiz Cabbarov |
| Philippe Coste | Ceyhun Qasımov |
| Jean-Marie Guéhenno | Eldar Quliyev |
| Thierry de Montbrial | Akif İsmayılov |
| CAPS | CPPC |

</details>

### 19. az_menatqa_counterfactual_019

Source record: **11** (1-based). Original meta.ID: `320`. Category: `counterfactual`.

**Question:** Who was the head of Youth Union from 1971 to 1972, if Cavid Əliyev elected to the head of Youth Union in 1970?

**Answer:** "Cavid Əliyev"

**Context (original paragraph order):**

Paragraph 1: Sənan Nəcəfov ( 2014–2018 ) - Rəşad Qədirov ( since 2018 ) Aysel Rəhmanova ( 1998–2002 ) - Anar Vəliyev ( 2002–2014 )Elnur Əsədov ( 1989–1994 ) - Murad Kərimov ( 1994–1998 ) Cavid Əliyev ( 1969–1973 ) - Ramil Məlikov ( 1973–1983 ) - Orxan Cəfərov ( 1983–1989 )  İlqar Nəsirov ( 1961–1963 ) - Natiq Orucov ( 1963–1969 ) Elman Cabbarov ( 1950–1955 ) - Fikrət Əkbərov ( 1955–1961 )Adil Səfərov ( 1947–1948 ) - Vüqar Rzayev ( 1948–1949 ) - Səbuhi İbrahimov ( 1949–1950 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the head of Young Union from 1971 to 1972, if Jürgen Echternach elected to the head of Young Union in 1970?",
  "answer": "Jürgen Echternach",
  "context": [
    "aul Ziemiak ( 2014–2018 ) - Tilman Kuban ( since 2018 ) Hildegard Müller ( 1998–2002 ) - Philipp Mißfelder ( 2002–2014 )Hermann Gröhe ( 1989–1994 ) - Klaus Escher ( 1994–1998 ) Jürgen Echternach ( 1969–1973 ) - Matthias Wissmann ( 1973–1983 ) - Christoph Böhr ( 1983–1989 )  Bert Even ( 1961–1963 ) - Egon Klepsch ( 1963–1969 ) Ernst Majonica ( 1950–1955 ) - Gerhard Stoltenberg ( 1955–1961 )Bruno Six ( 1947–1948 ) - Alfred Sagner ( 1948–1949 ) - Josef Dufhues ( 1949–1950 )"
  ],
  "meta": {
    "time_scope": [
      "1969",
      "1973"
    ],
    "annotated_para": "- Jürgen Echternach ( 1969–1973 )",
    "type": "counterfactual",
    "ID": 320
  }
}
```

| Original | Localized |
|---|---|
| Young Union | Youth Union |
| Jürgen Echternach | Cavid Əliyev |
| aul Ziemiak | Sənan Nəcəfov |
| Tilman Kuban | Rəşad Qədirov |
| Hildegard Müller | Aysel Rəhmanova |
| Philipp Mißfelder | Anar Vəliyev |
| Hermann Gröhe | Elnur Əsədov |
| Klaus Escher | Murad Kərimov |
| Matthias Wissmann | Ramil Məlikov |
| Christoph Böhr | Orxan Cəfərov |
| Bert Even | İlqar Nəsirov |
| Egon Klepsch | Natiq Orucov |
| Ernst Majonica | Elman Cabbarov |
| Gerhard Stoltenberg | Fikrət Əkbərov |
| Bruno Six | Adil Səfərov |
| Alfred Sagner | Vüqar Rzayev |
| Josef Dufhues | Səbuhi İbrahimov |

</details>

### 20. az_menatqa_counterfactual_020

Source record: **19** (1-based). Original meta.ID: `518`. Category: `counterfactual`.

**Question:** Which employer did Mikayıl Rəhimov work for from 1956 to 1975, if Mikayıl Rəhimov employed by the Ganja Historical Studies Institute in 1955?

**Answer:** "Ganja Historical Studies Institute"

**Context (original paragraph order):**

Paragraph 1: On his return to Azerbaijan , be began his long association with the Ganja Historical Studies Institute ( 1954–76 ) .Meals : Its Place in Ancient Rituals . A Caspian Research Fellowship in 1949 supported him at the Shamakhi Classical Studies College , where he hiked the Shirvan Highlands with his new wife and gained an intimate knowledge of inscriptions . After a brief stint at the Goychay Historical Studies College , he accepted an Araz Research Fellowship at the Shaki Social Anthropology Institute . 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which employer did Michael H. Jameson work for from 1956 to 1975, if Michael H. Jameson employed by the University of Pennsylvania in 1955?",
  "answer": "University of Pennsylvania",
  "context": [
    "On his return to the United States , be began his long association with the University of Pennsylvania ( 1954–76 ) .Meals : Its Place in Greek Sacrifice . A Fulbright Fellowship in 1949 supported him at the American School of Classical Studies at Athens , where he hiked the Peloponnesos with his new wife and gained an intimate knowledge of inscriptions . After a brief stint at the University of Minnesota , he accepted a Ford Fellowship at the Institute for Social Anthropology at Oxford University . "
  ],
  "meta": {
    "time_scope": [
      "1954",
      "1976"
    ],
    "annotated_para": "His father , Raymond D . Jameson , professor of Western literature at the University of Peking , and mother , Rose Perel Jameson , were visiting London at the time of his birth . He spent his childhood in Beijing and with his mother in London , received his A.B . in Greek at the University of Chicago in 1942 , aged seventeen , served in the U.S . Navy as a Japanese translator , 1943–46 , then married Virginia Broyles . He received his Ph.D . at Chicago in 1949 , with a dissertation on The Offering at Meals : Its Place in Greek Sacrifice . A Fulbright Fellowship in 1949 supported him at the American School of Classical Studies at Athens , where he hiked the Peloponnesos with his new wife and gained an intimate knowledge of inscriptions . After a brief stint at the University of Minnesota , he accepted a Ford Fellowship at the Institute for Social Anthropology at Oxford University . On his return to the United States , be began his long association with the University of Pennsylvania ( 1954–76 ) .",
    "type": "counterfactual",
    "ID": 518
  }
}
```

| Original | Localized |
|---|---|
| Michael H. Jameson | Mikayıl Rəhimov |
| University of Pennsylvania | Ganja Historical Studies Institute |
| United States | Azerbaijan |
| Greek Sacrifice | Ancient Rituals |
| Fulbright Fellowship | Caspian Research Fellowship |
| American School of Classical Studies at Athens | Shamakhi Classical Studies College |
| Peloponnesos | Shirvan Highlands |
| University of Minnesota | Goychay Historical Studies College |
| Ford Fellowship | Araz Research Fellowship |
| Institute for Social Anthropology at Oxford University | Shaki Social Anthropology Institute |
| Raymond D . Jameson | Rəhim Rəhimov |
| University of Peking | Shamakhi Humanities Institute |
| Rose Perel Jameson | Roza Rəhimova |
| London | Shaki |
| Beijing | Shamakhi |
| University of Chicago | Shaki Research University |
| U.S . Navy as a Japanese translator | Caspian Coastal Air Service as a Russian translator |
| Virginia Broyles | Vəfa Məcidova |
| Chicago | Shaki |

</details>

### 21. az_menatqa_counterfactual_021

Source record: **83** (1-based). Original meta.ID: `687`. Category: `counterfactual`.

**Question:** Which team did Yusif Həsənli play for from 2006 to 2008, if Yusif Həsənli no longer renewed his contract with Lankaran football club in 2010?

**Answer:** "Lankaran football club"

**Context (original paragraph order):**

Paragraph 1:  At age of 21 ( Regional Premier League 2007-08 ) , Yusif became the youngest player to captain Lankaran football club . Shaki football academy training stint .Yusif is well known for his close control of the ball and good range of passing . He made his first appearance during the 2006/07 season , scoring two league goals and one goal in Regional Cup group match against Goychay youth club . Yusif Həsənli is a footballer who plays for Lankaran football club - his home state and the team he started his career with . 

Paragraph 2:  - Regional Athlete Profile 2006

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did Joseph Kalang Tie play for from 2006 to 2008, if Joseph Kalang Tie no longer renewed his contract with Sarawak in 2010?",
  "answer": "Sarawak",
  "context": [
    " At age of 21 ( Malaysia Super League 2007-08 ) , Joseph became the youngest player to captain Sarawak . Hartlepool United training stint .Joseph is well known for his close control of the ball and good range of passing . He made his first appearance during the 2006/07 season , scoring two league goals and one goal in Malaysia Cup group match against PDRM . Joseph Kalang Tie is a footballer who plays for Sarawak FA - his home state and the team he started his career with . ",
    " - Profil Atlet SUKMA XI Kedah 2006"
  ],
  "meta": {
    "time_scope": [
      "2006",
      "2007"
    ],
    "annotated_para": "Sarawak .",
    "type": "counterfactual",
    "ID": 687
  }
}
```

| Original | Localized |
|---|---|
| Joseph Kalang Tie | Yusif Həsənli |
| Sarawak | Lankaran football club |
| Malaysia Super League | Regional Premier League |
| Joseph | Yusif |
| Hartlepool United | Shaki football academy |
| Malaysia Cup | Regional Cup |
| PDRM | Goychay youth club |
| Sarawak FA | Lankaran football club |
| Profil Atlet SUKMA XI Kedah | Regional Athlete Profile |

</details>

### 22. az_menatqa_counterfactual_022

Source record: **36** (1-based). Original meta.ID: `294`. Category: `counterfactual`.

**Question:** Which employer did Rəşid Əfəndiyev work for from 1998 to 2000, if Rəşid Əfəndiyev joined in Caspian Advanced Studies Institute from 1997?

**Answer:** "Caspian Advanced Studies Institute "

**Context (original paragraph order):**

Paragraph 1: He was then Professor at the Caspian Advanced Studies Institute ( 1996–2001 ) , before moving to Ganja Legal Studies Institute , where he is the Senior Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice . He became a faculty instructor in the Ganja Legal Studies Institute,Əfəndiyev was then Professor at the Ganja Social Sciences Institute ( 1990–95 ) , and also director of its Center for International and Public Law . Əfəndiyevs first academic appointments were at Shamakhi Law College ( 1985–89 ) and Baku Legal Studies College ( 1984–89 ) 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which employer did Philip Alston work for from 1998 to 2000, if Philip Alston joined in European University Institute from 1997?",
  "answer": "European University Institute ",
  "context": [
    "He was then Professor at the European University Institute ( 1996–2001 ) , before moving to New York University School of Law , where he is the John Norton Pomeroy Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice . He became a faculty instructor in the NYU Law,Alston was then Professor at the Australian National University ( 1990–95 ) , and also director of its Center for International and Public Law . Alstons first academic appointments were at Tufts University ( 1985–89 ) and Harvard Law School ( 1984–89 ) "
  ],
  "meta": {
    "time_scope": [
      "1996",
      "2001"
    ],
    "annotated_para": "Alstons first academic appointments were at Tufts University ( 1985–89 ) and Harvard Law School ( 1984–89 ) . Alston was then Professor at the Australian National University ( 1990–95 ) , and also director of its Center for International and Public Law . He was then Professor at the European University Institute ( 1996–2001 ) , before moving to New York University School of Law , where he is the John Norton Pomeroy Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice . He became a faculty instructor in the NYU Law Institute for Executive Education , which was launched in 2015 .",
    "type": "counterfactual",
    "ID": 294
  }
}
```

| Original | Localized |
|---|---|
| Philip Alston | Rəşid Əfəndiyev |
| European University Institute | Caspian Advanced Studies Institute |
| New York University School of Law | Ganja Legal Studies Institute |
| John Norton Pomeroy Professor | Senior Professor |
| NYU Law | Ganja Legal Studies Institute |
| Alston | Əfəndiyev |
| Australian National University | Ganja Social Sciences Institute |
| Tufts University | Shamakhi Law College |
| Harvard Law School | Baku Legal Studies College |
| NYU Law Institute for Executive Education | Ganja Institute of Professional Legal Education |

</details>

### 23. az_menatqa_counterfactual_023

Source record: **195** (1-based). Original meta.ID: `580`. Category: `counterfactual`.

**Question:** Which team did Səbuhi Vəliyev play for from 2013 to 2016, if Səbuhi Vəliyev terminated contract with Gabala football club in 2017?

**Answer:** "Gabala football club"

**Context (original paragraph order):**

Paragraph 1: He was named captain of his new club on 10 July 2013 , and scored a penalty on his competitive debut on 3 August 2013 in a Regional Challenge Cup match against Guba football club .On 22 May 2013 , Vəliyev signed for Gabala football club on a two-year contract . 

Paragraph 2:  On 27 January 2015 , Coach Qabil Hacıyev bolstered the Sumgait backline with the signings of Vəliyev and fellow Azerbaijani player Pərviz Həmidov . However he left the club in January 2016 due to the side folding after failing to find local ownership . Returning to Shirvan , Vəliyev trained with Regional First Division side Gusar football club with a view to signing for the Gusar team who were suffering an injury crisis , with four defenders out through injury .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did Simon Mensing play for from 2013 to 2016, if Simon Mensing terminated contract with Livingston in 2017?",
  "answer": "Livingston",
  "context": [
    "He was named captain of his new club on 10 July 2013 , and scored a penalty on his competitive debut on 3 August 2013 in a Scottish Challenge Cup match against Berwick Rangers .On 22 May 2013 , Mensing signed for Livingston on a two-year contract . ",
    " On 27 January 2015 , Coach Gary Smith bolstered the Atlanta backline with the signings of Mensing and fellow Englishman Paul Black . However he left the club in January 2016 due to the side folding after failing to find local ownership . Returning to Scotland , Mensing trained with Scottish League One side Dunfermline Athletic with a view to signing for the Pars who were suffering an injury crisis , with four defenders out through injury ."
  ],
  "meta": {
    "time_scope": [
      "2013",
      "2015"
    ],
    "annotated_para": "Livingston .",
    "type": "counterfactual",
    "ID": 580
  }
}
```

| Original | Localized |
|---|---|
| Simon Mensing | Səbuhi Vəliyev |
| Livingston | Gabala football club |
| Scottish Challenge Cup | Regional Challenge Cup |
| Berwick Rangers | Guba football club |
| Mensing | Vəliyev |
| Gary Smith | Qabil Hacıyev |
| Atlanta | Sumgait |
| Englishman | Azerbaijani player |
| Paul Black | Pərviz Həmidov |
| Scotland | Shirvan |
| Scottish League One | Regional First Division |
| Dunfermline Athletic | Gusar football club |
| Pars | Gusar team |

</details>

### 24. az_menatqa_counterfactual_024

Source record: **6** (1-based). Original meta.ID: `611`. Category: `counterfactual`.

**Question:** Pərviz Qurbanov played for which team from 2011 to 2014, if Pərviz Qurbanov played for Guba football club from 2015?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1:  - National Football League ( 1 ) : 2012 - National Football Cup ( 1 ) : 2013

Paragraph 2: After impressing with a goal in his second pre-season game , Guba football club signed him to a contract for the 2012 season .Qurbanov joined Guba football club on trial in early February 2012 .

Paragraph 3:  Qurbanov was unable to play with Guba in the early part of the season due to issues with a work permit , but he made his debut on 20 April , coming on as a second-half substitute in a league match against Gusar football club . Qurbanov helped Guba club win the league title , appearing 17 times and netting 2 goals . In December 2012 , Qurbanov agreed a new contract with the club extending his stay for another season .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Pascal Millien played for which team from 2011 to 2014, if Pascal Millien played for Sligo Rovers from 2015?",
  "answer": "unanswerable",
  "context": [
    " - League of Ireland ( 1 ) : 2012 - FAI Cup ( 1 ) : 2013",
    "After impressing with a goal in his second pre-season game , Sligo Rovers signed him to a contract for the 2012 season .Millien joined Sligo Rovers on trial in early February 2012 .",
    " Millien was unable to play with Sligo in the early part of the season due to issues with a work permit , but he made his debut on 20 April , coming on as a second-half substitute in a league match against Cork City . Millien helped Rovers win the league title , appearing 17 times and netting 2 goals . In December 2012 , Millien agreed a new contract with the club extending his stay for another season ."
  ],
  "meta": {
    "time_scope": [
      "2012",
      "2013"
    ],
    "annotated_para": "Millien joined Sligo Rovers on trial in early February 2012 . After impressing with a goal in his second pre-season game , Sligo Rovers signed him to a contract for the 2012 season .",
    "type": "counterfactual",
    "ID": 611
  }
}
```

| Original | Localized |
|---|---|
| Pascal Millien | Pərviz Qurbanov |
| Sligo Rovers | Guba football club |
| League of Ireland | National Football League |
| FAI Cup | National Football Cup |
| Millien | Qurbanov |
| Sligo | Guba |
| Cork City | Gusar football club |
| Rovers | Guba club |

</details>

### 25. az_menatqa_counterfactual_025

Source record: **140** (1-based). Original meta.ID: `875`. Category: `counterfactual`.

**Question:** Which team did the player Mahir Məcidov belong to from 2008 to 2010, if the player Mahir Məcidov employed by the Sumgait football club from 2011?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: He received a call-up twice in 2006 for the national squad . Then he was a late replacement for injured Rəşad Vəliyev for the 2007 Caspian Regional Cup finals but did not play in the competition . He signed with Sumgait football club after a successful trial and he took a leave of absence from the university with which he is still enrolled as of April 2008 . Manager Ələsgər Rzayev immediately established him as a starting member in his midfield .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did the player Masahiko Inoha belong to from 2008 to 2010, if the player Masahiko Inoha employed by the F.C . Tokyo from 2011?",
  "answer": "unanswerable",
  "context": [
    "He received a call-up twice in 2006 for the national squad . Then he was a late replacement for injured Ryuji Bando for the 2007 AFC Asian Cup finals but did not play in the competition . He signed with F.C . Tokyo after a successful trial and he took a leave of absence from the university with which he is still enrolled as of April 2008 . Manager Alexandre Gallo immediately established him as a starting member in his midfield ."
  ],
  "meta": {
    "time_scope": [
      "2006",
      "2007"
    ],
    "annotated_para": "He signed with F.C . Tokyo after a successful trial and he took a leave of absence from the university with which he is still enrolled as of April 2008 . Manager Alexandre Gallo immediately established him as a starting member in his midfield .",
    "type": "counterfactual",
    "ID": 875
  }
}
```

| Original | Localized |
|---|---|
| Masahiko Inoha | Mahir Məcidov |
| F.C . Tokyo | Sumgait football club |
| Ryuji Bando | Rəşad Vəliyev |
| AFC Asian Cup | Caspian Regional Cup |
| Alexandre Gallo | Ələsgər Rzayev |

</details>

### 26. az_menatqa_counterfactual_026

Source record: **197** (1-based). Original meta.ID: `725`. Category: `counterfactual`.

**Question:** Which team did Anar İbrahimov play for from 2010 to 2012, if Anar İbrahimov played for Goychay rugby club from 2011?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: İbrahimov came to wider attention in 2011 with the Goychay rugby club . As an attacking threat he underlined his credentials during the regions Regional Rugby Cup campaign - scoring a brace as they secured a quarter-final berth with victory over Ganja rugby club .

Paragraph 2:  Although born and raised in Absheron , İbrahimov qualifies for Shaki District as his mother was born in Shaki . He was noticed by Shaki District rugby sevens team coach Pərviz Quliyev . As a result , İbrahimov played for them in the 2009-2010 and the 2010-2011 Regional Rugby Sevens Series , and in the 2010 Regional Games .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did Alex Cuthbert play for from 2010 to 2012, if Alex Cuthbert played for Cardiff Blues from 2011?",
  "answer": "unanswerable",
  "context": [
    "Cuthbert came to wider attention in 2011 with the Cardiff Blues . As an attacking threat he underlined his credentials during the regions Heineken Cup campaign - scoring a brace as they secured a quarter-final berth with victory over Racing Metro .",
    " Although born and raised in England , Cuthbert qualifies for Wales as his mother was born in Wrexham . He was noticed by Wales rugby sevens team coach Paul John . As a result , Cuthbert played for them in the 2009-2010 and the 2010-2011 IRB Sevens World Series , and in the 2010 Commonwealth Games ."
  ],
  "meta": {
    "time_scope": [
      "2011",
      "Dec 2011"
    ],
    "annotated_para": "Cuthbert came to wider attention in 2011 with the Cardiff Blues . As an attacking threat he underlined his credentials during the regions Heineken Cup campaign - scoring a brace as they secured a quarter-final berth with victory over Racing Metro .",
    "type": "counterfactual",
    "ID": 725
  }
}
```

| Original | Localized |
|---|---|
| Alex Cuthbert | Anar İbrahimov |
| Cardiff Blues | Goychay rugby club |
| Cuthbert | İbrahimov |
| Heineken Cup | Regional Rugby Cup |
| Racing Metro | Ganja rugby club |
| England | Absheron |
| Wales | Shaki District |
| Wrexham | Shaki |
| Paul John | Pərviz Quliyev |
| IRB Sevens World Series | Regional Rugby Sevens Series |
| Commonwealth Games | Regional Games |

</details>

### 27. az_menatqa_counterfactual_027

Source record: **190** (1-based). Original meta.ID: `932`. Category: `counterfactual`.

**Question:** Which team did Davud Əliyev play for from 2011 to 2016, if Davud Əliyev left the Shamakhi youth club in 2012?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1:  On 21 January 2014 , Əliyev signed for fellow Regional Premier League club Shamakhi youth club , citing that he needed more time on the pitch to continue develop as a player . Shaki youth club acknowledged that a buy-back agreement existed in the transfer and that they would follow Əliyevs development in Shamakhi youth club .

Paragraph 2: His final international was a September 2014 friendly against Goychay district .He made his senior debut for Shirvan district in a May 2014 friendly match against Absheron district and earned a total of 3 caps , scoring no goals .  Əliyev made his debut for Shirvan U21 on 24 March 2011 in a training match against Absheron U21 . 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did Dardan Rexhepi play for from 2011 to 2016, if Dardan Rexhepi left the IF Brommapojkarna in 2012?",
  "answer": "unanswerable",
  "context": [
    " On 21 January 2014 , Rexhepi signed for fellow Allsvenskan club IF Brommapojkarna , citing that he needed more time on the pitch to continue develop as a player . Malmö FF acknowledged that a buy-back agreement existed in the transfer and that they would follow Rexhepis development in Brommapojkarna .",
    "His final international was a September 2014 friendly against Oman .He made his senior debut for Kosovo in a May 2014 friendly match against Turkey and earned a total of 3 caps , scoring no goals .  Rexhepi made his debut for Sweden U21 on 24 March 2011 in a training match against Italy U21 . "
  ],
  "meta": {
    "time_scope": [
      "2014",
      "2015"
    ],
    "annotated_para": "IF Brommapojkarna .",
    "type": "counterfactual",
    "ID": 932
  }
}
```

| Original | Localized |
|---|---|
| Dardan Rexhepi | Davud Əliyev |
| IF Brommapojkarna | Shamakhi youth club |
| Rexhepi | Əliyev |
| Allsvenskan | Regional Premier League |
| Malmö FF | Shaki youth club |
| Brommapojkarna | Shamakhi youth club |
| Oman | Goychay district |
| Kosovo | Shirvan district |
| Turkey | Absheron district |
| Sweden U21 | Shirvan U21 |
| Italy U21 | Absheron U21 |

</details>

### 28. az_menatqa_counterfactual_028

Source record: **40** (1-based). Original meta.ID: `161`. Category: `counterfactual`.

**Question:** Which team did Mahir Qədirov play for from 2005 to 2010, if Mahir Qədirov played for Sabirabad football club from 2007?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1:  Mahir Qədirov ( born June 6 , 1984 in Goychay , Azerbaijan ) is an Azerbaijani footballer who last played for Guba football club . He has previously played in Shirvan for Gusar football club and Shamakhi football club , in Azerbaijan for Sabirabad football club ( twice ) and in Azerbaijan for July 14 football club , Salyan football club and Masalli football club from Southern District , and Jalilabad football club from Lankaran District .

Paragraph 2:  In 2012 , he helped Salyan football club win promotion from the second level of the Southern District league to the top level .Qədirovs early career was spent in Shirvan , before joining Sabirabad football club , who at the time played in the National Premier League ,After the club suffered relegation , he moved to Azerbaijan , signing first for July 14 football club in 2009 and then Salyan football club in 2011 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did Mario Larramendi play for from 2005 to 2010, if Mario Larramendi played for Cerrito from 2007?",
  "answer": "unanswerable",
  "context": [
    " Mario Larramendi ( born June 6 , 1984 in Montevideo , Uruguay ) is a Uruguayan footballer who last played for Treze . He has previously played in Chilé for Deportivo Arauco and Provincial Osorno , in Uruguay for Cerrito ( twice ) and in Brazil for 14 de Julho , Passo Fundo and Novo Hamburgo from Rio Grande do Sul state , and Botafogo-PB from Paraíba state .",
    " In 2012 , he helped Passo Fundo win promotion from the second level of the Rio Grande do Sul state league to the top level .Larremendis early career was spent in Chilé , before joining Cerrito , who at the time played in the Uruguayan Primera División ,After the club suffered relegation , he moved to Brazil , signing first for 14 de Julho in 2009 and then Passo Fundo in 2011 ."
  ],
  "meta": {
    "time_scope": [
      "2006",
      "2009"
    ],
    "annotated_para": "Mario Larramendi ( born June 6 , 1984 in Montevideo , Uruguay ) is a Uruguayan footballer who last played for Treze . He has previously played in Chilé for Deportivo Arauco and Provincial Osorno , in Uruguay for Cerrito ( twice ) and in Brazil for 14 de Julho , Passo Fundo and Novo Hamburgo from Rio Grande do Sul state , and Botafogo-PB from Paraíba state .",
    "type": "counterfactual",
    "ID": 161
  }
}
```

| Original | Localized |
|---|---|
| Mario Larramendi | Mahir Qədirov |
| Cerrito | Sabirabad football club |
| Montevideo , Uruguay | Goychay , Azerbaijan |
| Uruguayan footballer | Azerbaijani footballer |
| Treze | Guba football club |
| Chilé | Shirvan |
| Deportivo Arauco | Gusar football club |
| Provincial Osorno | Shamakhi football club |
| Uruguay | Azerbaijan |
| Brazil | Azerbaijan |
| 14 de Julho | July 14 football club |
| Passo Fundo | Salyan football club |
| Novo Hamburgo | Masalli football club |
| Rio Grande do Sul state | Southern District |
| Botafogo-PB | Jalilabad football club |
| Paraíba state | Lankaran District |
| Larremendi | Qədirov |
| Uruguayan Primera División | National Premier League |

</details>

### 29. az_menatqa_counterfactual_029

Source record: **50** (1-based). Original meta.ID: `946`. Category: `counterfactual`.

**Question:** Which team did the player Davud Həmidov belong to from 2001 to 2004, if the player Davud Həmidov erminated contract with Ganja football club in 2003?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1:  Həmidov represented the Absheron under-20 team at the 2003 National Youth Championship , and was capped 11 times in all at that level . In one match he was sent off for a foul on Shirvans Cavid Rəsulov .

Paragraph 2:  In March 2004 he was scheduled to go out on loan to Shirvan football club before injuries and suspensions at Ganja persuaded manager Səlim Nəsirov to put an end to the deal .His first team opportunities were even more restricted in the 2003–04 campaign , as he featured in just five National Premier League matches . Despite this , he signed a three-and-a-half-year contract in January 2004 after 20 months of negotiations .Həmidov played only 12 National Premier League matches in the 2002–03 season , with half of these appearances coming before mid-October . 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did the player Darren Carter belong to from 2001 to 2004, if the player Darren Carter erminated contract with Birmingham City in 2003?",
  "answer": "unanswerable",
  "context": [
    " Carter represented the England under-20 team at the 2003 FIFA World Youth Championship , and was capped 11 times in all at that level . In one match he was sent off for a foul on Portugals Cristiano Ronaldo .",
    " In March 2004 he was scheduled to go out on loan to Rotherham United before injuries and suspensions at Birmingham persuaded manager Steve Bruce to put an end to the deal .His first team opportunities were even more restricted in the 2003–04 campaign , as he featured in just five Premier League matches . Despite this , he signed a three-and-a-half-year contract in January 2004 after 20 months of negotiations .Carter played only 12 Premier League matches in the 2002–03 season , with half of these appearances coming before mid-October . "
  ],
  "meta": {
    "time_scope": [
      "2001",
      "2003"
    ],
    "annotated_para": "Birmingham City .",
    "type": "counterfactual",
    "ID": 946
  }
}
```

| Original | Localized |
|---|---|
| Darren Carter | Davud Həmidov |
| Birmingham City | Ganja football club |
| Carter | Həmidov |
| England under-20 team | Absheron under-20 team |
| FIFA World Youth Championship | National Youth Championship |
| Portugals Cristiano Ronaldo | Shirvans Cavid Rəsulov |
| Rotherham United | Shirvan football club |
| Birmingham | Ganja |
| Steve Bruce | Səlim Nəsirov |
| Premier League | National Premier League |

</details>

### 30. az_menatqa_counterfactual_030

Source record: **74** (1-based). Original meta.ID: `418`. Category: `counterfactual`.

**Question:** Which position did Həsən Rəhimov hold from 1840 to 1842, if Həsən Rəhimov held Regional Council delegate from 1843?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1:  In between his two terms as district head , Rəhimov was elected as a non-voting Regional Council delegate to the Twenty-seventh and Twenty-eighth Regional Assemblies ( March 4 , 1841 – March 3 , 1845 ) representing Northern Districts at-large congressional district . Rəhimov was the first Head of the Northern District from 1836 to 1841 and again from 1845 to 1848 , an area which encompassed ( before July 4 , 1838 , when Central District became a territory ) what became the states of Northern District , Central District and Southern District 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which position did Henry Dodge hold from 1840 to 1842, if Henry Dodge held Democratic delegate from 1843?",
  "answer": "unanswerable",
  "context": [
    " In between his two terms as governor , Dodge was elected as a non-voting Democratic delegate to the Twenty-seventh and Twenty-eighth Congresses ( March 4 , 1841 – March 3 , 1845 ) representing Wisconsin Territorys at-large congressional district . Dodge was the first Territorial governor of Wisconsin Territory from 1836 to 1841 and again from 1845 to 1848 , an area which encompassed ( before July 4 , 1838 , when Iowa became a territory ) what became the states of Wisconsin , Iowa and Minnesota "
  ],
  "meta": {
    "time_scope": [
      "Mar 1841",
      "Sep 1841"
    ],
    "annotated_para": "Dodge was the first Territorial governor of Wisconsin Territory from 1836 to 1841 and again from 1845 to 1848 , an area which encompassed ( before July 4 , 1838 , when Iowa became a territory ) what became the states of Wisconsin , Iowa and Minnesota . In between his two terms as governor , Dodge was elected as a non-voting Democratic delegate to the Twenty-seventh and Twenty-eighth Congresses ( March 4 , 1841 – March 3 , 1845 ) representing Wisconsin Territorys at-large congressional district .",
    "type": "counterfactual",
    "ID": 418
  }
}
```

| Original | Localized |
|---|---|
| Henry Dodge | Həsən Rəhimov |
| Democratic delegate | Regional Council delegate |
| governor | district head |
| Dodge | Rəhimov |
| Twenty-seventh and Twenty-eighth Congresses | Twenty-seventh and Twenty-eighth Regional Assemblies |
| Wisconsin Territorys | Northern Districts |
| Territorial governor of Wisconsin Territory | Head of the Northern District |
| Iowa | Central District |
| Wisconsin | Northern District |
| Minnesota | Southern District |

</details>


## Order — 30 samples

### 01. az_menatqa_order_001

Source record: **13** (1-based). Original meta.ID: `731`. Category: `order`.

**Question:** What was the official name of SQ-29 from Sep 1948 to 1950?

**Answer:** "Patrol Squadron 29"

**Context (original paragraph order):**

Paragraph 1: - 2 June 1948 : SQ-HL-12 deployed to Guba Air Station , Northern District . Navigation training , winter patrols from Guba to Khachmaz , and collection of data on mountain snowfield topography comprised the majority of squadron duties .

Paragraph 2: 15 November 1946 , redesignated Patrol Squadron 29 ( SQ-29 ) on 1 September 1948 and disestablished on 18 January 1950 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the official name of VP-29 from Sep 1948 to 1950?",
  "answer": "Patrol Squadron 29",
  "context": [
    "- 2 June 1948 : VP-HL-12 deployed to NAS Kodiak , Alaska . Navigation training , ice patrols from Kodiak to Point Barrow , and collection of data on Arctic ice cap topography comprised the majority of squadron duties .",
    "15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 ."
  ],
  "meta": {
    "time_scope": [
      "Sep 1948",
      "Jan 1950"
    ],
    "annotated_para": "VP-29 was a Patrol Squadron of the U.S . Navy . The squadron was established as Patrol Squadron 14-F ( VP-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( VP-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( VP-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( VP-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( VPB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( VP-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( VP-HL-12 ) on 15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 .",
    "type": "order",
    "ID": 731
  }
}
```

| Original | Localized |
|---|---|
| VP- | SQ- |
| VP-HL- | SQ-HL- |
| NAS Kodiak | Guba Air Station |
| Alaska | Northern District |
| ice patrols | winter patrols |
| Kodiak | Guba |
| Point Barrow | Khachmaz |
| Arctic ice cap | mountain snowfield |
| U.S . Navy | Caspian Coastal Air Service |
| VPB- | SB- |

</details>

### 02. az_menatqa_order_002

Source record: **28** (1-based). Original meta.ID: `169`. Category: `order`.

**Question:** Who directed or managed Caspian Policy Planning Centre from 1983 to 1990?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: Rafiq İbrahimov ( 2010-2013 ) - Sərxan Əsədov ( 2013-2019 ) - Əliyar Əhmədov ( 2019- )İlham Nəcəfov ( 1999-2002 ) - Namiq Səlimov ( 2005-2010 ) - Lalə Vəliyeva ( 2010 ) Fərid Rəhmanov ( 1993-1995 ) - Hafiz Cabbarov ( 1995-1999 , 2002-2004 ) Ceyhun Qasımov ( 1984-1989 ) - Eldar Quliyev ( 1989-1993 )  Akif İsmayılov ( 1974-1978 ) - Bəxtiyar Rzayev ( 1979-1984 ) The CPPC has a history of renowned directors , either academics or career diplomats .

Paragraph 2: Its YLP program ( Young Leaders Programme – an invitation program for young foreign leaders ) , established in 1989 , which hosts about 75 young leaders ( under 45 ) a year , seeks to present the select few who are chosen with an unvarnished image of contemporary Azerbaijan and establish friendly ties with them . Since its creation , the program has hosted over 2,000 personalities from over 150 countries .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who directed or managed Policy Planning Staff (France) from 1983 to 1990?",
  "answer": "unanswerable",
  "context": [
    "Joseph Maïla ( 2010-2013 ) - Justin Vaïsse ( 2013-2019 ) - Manuel Lafont Rapnouil ( 2019- )Michel Foucher ( 1999-2002 ) - Pierre Lévy ( 2005-2010 ) - Marie Mendras ( 2010 ) Bruno Racine ( 1993-1995 ) - Gilles Andréani ( 1995-1999 , 2002-2004 ) Philippe Coste ( 1984-1989 ) - Jean-Marie Guéhenno ( 1989-1993 )  Thierry de Montbrial ( 1974-1978 ) - Jean-Louis Gergorin ( 1979-1984 ) The CAPS has a history of renowned directors , either academics or career diplomats .",
    "Its PIPA program ( Programme d’invitation des personnalités d’avenir – an invitation program for young foreign leaders ) , established in 1989 , which hosts about 75 young leaders ( under 45 ) a year , seeks to present the select few who are chosen with an unvarnished image of contemporary France and establish friendly ties with them . Since its creation , the program has hosted over 2,000 personalities from over 150 countries ."
  ],
  "meta": {
    "time_scope": [
      "1984",
      "1989"
    ],
    "annotated_para": "- Philippe Coste ( 1984-1989 )",
    "type": "order",
    "ID": 169
  }
}
```

| Original | Localized |
|---|---|
| Policy Planning Staff (France) | Caspian Policy Planning Centre |
| Joseph Maïla | Rafiq İbrahimov |
| Justin Vaïsse | Sərxan Əsədov |
| Manuel Lafont Rapnouil | Əliyar Əhmədov |
| Michel Foucher | İlham Nəcəfov |
| Pierre Lévy | Namiq Səlimov |
| Marie Mendras | Lalə Vəliyeva |
| Bruno Racine | Fərid Rəhmanov |
| Gilles Andréani | Hafiz Cabbarov |
| Philippe Coste | Ceyhun Qasımov |
| Jean-Marie Guéhenno | Eldar Quliyev |
| Thierry de Montbrial | Akif İsmayılov |
| Jean-Louis Gergorin | Bəxtiyar Rzayev |
| CAPS | CPPC |
| PIPA | YLP |
| Programme d’invitation des personnalités d’avenir | Young Leaders Programme |
| France | Azerbaijan |

</details>

### 03. az_menatqa_order_003

Source record: **37** (1-based). Original meta.ID: `293`. Category: `order`.

**Question:** Who did Rəşid Əfəndiyev work for from Mar 1991 to Dec 1994?

**Answer:** "Ganja Social Sciences Institute"

**Context (original paragraph order):**

Paragraph 1: He was then Professor at the Caspian Advanced Studies Institute ( 1996–2001 ) , before moving to Ganja Legal Studies Institute , where he is the Senior Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice . He became a faculty instructor in the Ganja Legal Studies Institute,Əfəndiyev was then Professor at the Ganja Social Sciences Institute ( 1990–95 ) , and also director of its Center for International and Public Law . Əfəndiyevs first academic appointments were at Shamakhi Law College ( 1985–89 ) and Baku Legal Studies College ( 1984–89 ) .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who did Philip Alston work for from Mar 1991 to Dec 1994?",
  "answer": "Australian National University",
  "context": [
    "He was then Professor at the European University Institute ( 1996–2001 ) , before moving to New York University School of Law , where he is the John Norton Pomeroy Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice . He became a faculty instructor in the NYU Law,Alston was then Professor at the Australian National University ( 1990–95 ) , and also director of its Center for International and Public Law . Alstons first academic appointments were at Tufts University ( 1985–89 ) and Harvard Law School ( 1984–89 ) ."
  ],
  "meta": {
    "time_scope": [
      "1990",
      "1995"
    ],
    "annotated_para": "Alstons first academic appointments were at Tufts University ( 1985–89 ) and Harvard Law School ( 1984–89 ) . Alston was then Professor at the Australian National University ( 1990–95 ) , and also director of its Center for International and Public Law . He was then Professor at the European University Institute ( 1996–2001 ) , before moving to New York University School of Law , where he is the John Norton Pomeroy Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice . He became a faculty instructor in the NYU Law Institute for Executive Education , which was launched in 2015 .",
    "type": "order",
    "ID": 293
  }
}
```

| Original | Localized |
|---|---|
| Philip Alston | Rəşid Əfəndiyev |
| Australian National University | Ganja Social Sciences Institute |
| European University Institute | Caspian Advanced Studies Institute |
| New York University School of Law | Ganja Legal Studies Institute |
| John Norton Pomeroy Professor | Senior Professor |
| NYU Law | Ganja Legal Studies Institute |
| Alston | Əfəndiyev |
| Tufts University | Shamakhi Law College |
| Harvard Law School | Baku Legal Studies College |
| NYU Law Institute for Executive Education | Ganja Institute of Professional Legal Education |

</details>

### 04. az_menatqa_order_004

Source record: **57** (1-based). Original meta.ID: `729`. Category: `order`.

**Question:** What was the official name of SQ-29 from May 1946 to Nov 1946?

**Answer:** "Patrol Squadron 122"

**Context (original paragraph order):**

Paragraph 1: 15 November 1946 , redesignated Patrol Squadron 29 ( SQ-29 ) on 1 September 1948 and disestablished on 18 January 1950 .

Paragraph 2: SQ-29 was a Patrol Squadron of the Caspian Coastal Air Service . The squadron was established as Patrol Squadron 14-F ( SQ-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( SQ-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( SQ-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( SQ-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( SB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( SQ-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( SQ-HL-12 ) on

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the official name of VP-29 from May 1946 to Nov 1946?",
  "answer": "Patrol Squadron 122",
  "context": [
    "15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 .",
    "VP-29 was a Patrol Squadron of the U.S . Navy . The squadron was established as Patrol Squadron 14-F ( VP-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( VP-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( VP-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( VP-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( VPB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( VP-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( VP-HL-12 ) on"
  ],
  "meta": {
    "time_scope": [
      "May 1946",
      "Nov 1946"
    ],
    "annotated_para": "VP-29 was a Patrol Squadron of the U.S . Navy . The squadron was established as Patrol Squadron 14-F ( VP-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( VP-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( VP-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( VP-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( VPB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( VP-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( VP-HL-12 ) on 15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 .",
    "type": "order",
    "ID": 729
  }
}
```

| Original | Localized |
|---|---|
| VP- | SQ- |
| U.S . Navy | Caspian Coastal Air Service |
| VPB- | SB- |
| VP-HL- | SQ-HL- |

</details>

### 05. az_menatqa_order_005

Source record: **73** (1-based). Original meta.ID: `279`. Category: `order`.

**Question:** What was the name of the employer Rauf Əhmədov work for from 2004 to 2006?

**Answer:** "Baku football club"

**Context (original paragraph order):**

Paragraph 1:  Early years and Shaki football club . After starting as a manager with his main team Shamakhi football club , Əhmədov moved in 2004 to Baku football club , spending two seasons with its junior side . In 2006 , Əhmədov signed for Shaki football club , helping the club promote to the second level in his first season , followed by immediate relegation back . In 2008–09 , again as champion , he again led the side to division two .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the name of the employer Rui Vitória work for from 2004 to 2006?",
  "answer": "Benfica",
  "context": [
    " Early years and Fátima . After starting as a manager with his main team Vilafranquense , Vitória moved in 2004 to Benfica , spending two seasons with its junior side . In 2006 , Vitória signed for Fátima , helping the club promote to the second level in his first season , followed by immediate relegation back . In 2008–09 , again as champion , he again led the side to division two ."
  ],
  "meta": {
    "time_scope": [
      "2004",
      "2006"
    ],
    "annotated_para": "After starting as a manager with his main team Vilafranquense , Vitória moved in 2004 to Benfica , spending two seasons with its junior side .",
    "type": "order",
    "ID": 279
  }
}
```

| Original | Localized |
|---|---|
| Rui Vitória | Rauf Əhmədov |
| Benfica | Baku football club |
| Fátima | Shaki football club |
| Vilafranquense | Shamakhi football club |
| Vitória | Əhmədov |

</details>

### 06. az_menatqa_order_006

Source record: **89** (1-based). Original meta.ID: `280`. Category: `order`.

**Question:** Who did Rauf Əhmədov work for from 2005 to 2011?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: In 2008–09 , again as champion , he again led the side to division two .In 2006 , Əhmədov signed for Shaki football club , helping the club promote to the second level in his first season , followed by immediate relegation back .Early years and Shaki football club . After starting as a manager with his main team Shamakhi football club , Əhmədov moved in 2004 to Baku football club , spending two seasons with its junior side . 

Paragraph 2:  On 2 June 2010 , Əhmədov replaced Tural İsmayılov at the helm of Goychay football club . In his first season in the top division , he guided the team to the seventh position in the league , also achieving runner-up honours in the domestic League Cup , which was won by Baku football club ( 2–1 ) .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who did Rui Vitória work for from 2005 to 2011?",
  "answer": "unanswerable",
  "context": [
    "In 2008–09 , again as champion , he again led the side to division two .In 2006 , Vitória signed for Fátima , helping the club promote to the second level in his first season , followed by immediate relegation back .Early years and Fátima . After starting as a manager with his main team Vilafranquense , Vitória moved in 2004 to Benfica , spending two seasons with its junior side . ",
    " On 2 June 2010 , Vitória replaced Ulisses Morais at the helm of Paços de Ferreira . In his first season in the top division , he guided the team to the seventh position in the league , also achieving runner-up honours in the domestic League Cup , which was won by Benfica ( 2–1 ) ."
  ],
  "meta": {
    "time_scope": [
      "2006",
      "2010"
    ],
    "annotated_para": "In 2006 , Vitória signed for Fátima , helping the club promote to the second level in his first season , followed by immediate relegation back . In 2008–09 , again as champion , he again led the side to division two .",
    "type": "order",
    "ID": 280
  }
}
```

| Original | Localized |
|---|---|
| Rui Vitória | Rauf Əhmədov |
| Vitória | Əhmədov |
| Fátima | Shaki football club |
| Vilafranquense | Shamakhi football club |
| Benfica | Baku football club |
| Ulisses Morais | Tural İsmayılov |
| Paços de Ferreira | Goychay football club |

</details>

### 07. az_menatqa_order_007

Source record: **98** (1-based). Original meta.ID: `619`. Category: `order`.

**Question:** Who owned Spring Morning (painting) from April 1920 to March 1921?

**Answer:** "Fərid Həsənov"

**Context (original paragraph order):**

Paragraph 1: - 1921 , sold by Həsənov to Quliyev Brothers Gallery , Shaki ; 1937 , shipped from Quliyev Gallery , Shaki to Quliyev Gallery , Ganja

Paragraph 2: lot 48 , to ( d . 1923 ) , Baku - 1918 , sold by to Rəşad Məmmədov and Co. , Baku and Ganja - 1920 , sold by Məmmədov to Fərid Həsənov ( b . 1861 - d . 1947 ) , Ganja.April 14 , 1876 , Səlim Qasımov and sale , , Baku , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Baku 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who owned La Japonaise (painting) from April 1920 to March 1921?",
  "answer": "Philip Lehman",
  "context": [
    "- 1921 , sold by Lehman to Duveen Brothers , Inc. , London ; 1937 , shipped from Duveen , London to Duveen , New York",
    "lot 48 , to ( d . 1923 ) , Paris - 1918 , sold by to Paul Rosenberg and Co. , Paris and New York - 1920 , sold by Rosenberg to Philip Lehman ( b . 1861 - d . 1947 ) , New York.April 14 , 1876 , Monet and sale , , Paris , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Paris "
  ],
  "meta": {
    "time_scope": [
      "1920",
      "1921"
    ],
    "annotated_para": "- 1920 , sold by Rosenberg to Philip Lehman ( b . 1861 - d . 1947 ) , New York",
    "type": "order",
    "ID": 619
  }
}
```

| Original | Localized |
|---|---|
| La Japonaise (painting) | Spring Morning (painting) |
| Philip Lehman | Fərid Həsənov |
| Lehman | Həsənov |
| Duveen Brothers , Inc. | Quliyev Brothers Gallery |
| London | Shaki |
| Duveen | Quliyev Gallery |
| New York | Ganja |
| Paris | Baku |
| Paul Rosenberg and Co | Rəşad Məmmədov and Co |
| Rosenberg | Məmmədov |
| Monet | Səlim Qasımov |

</details>

### 08. az_menatqa_order_008

Source record: **99** (1-based). Original meta.ID: `618`. Category: `order`.

**Question:** Spring Morning (painting) was owned by whom from 1919 to 1921?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1:  lot 48 , to ( d . 1923 ) , Baku - 1918 , sold by to Rəşad Məmmədov and Co. , Baku and Ganja - 1920 , sold by Məmmədov to Fərid Həsənov ( b . 1861 - d . 1947 ) , Ganja.April 14 , 1876 , Səlim Qasımov and sale , , Baku , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Baku ,

Paragraph 2:  It is possible that Səlim Qasımov had informed of his trick , and that he had warned him not to tell anyone else , or that Səlim Qasımov wanted to hide from the public the painting Aysel had modeled for , given the criticism of the paintings sexually suggestive nature , though no one mentioned Aysels name in connection with the work until Səlim Qasımov revealed her role to and in 1918 , the blond wig having disguised her identity until this point .

Paragraph 3: Forty years later , in 1918 , when the art dealers and visited Səlim Qasımov and informed him that had sold for a very decent price , Səlim Qasımov was said to stated that he was ashamed by the fact of having painted the work simply to please the market , calling it a piece of filth . Some scholars believe that he may have been more committed to this subject than these comments would suggest ; when the work was in progress , Səlim Qasımov wrote to Pərviz Əfəndiyev , a famous art critic and collector of regional artworks , commenting that

<details><summary>Original record and replacements</summary>

```json
{
  "question": "La Japonaise (painting) was owned by whom from 1919 to 1921?",
  "answer": "unanswerable",
  "context": [
    " lot 48 , to ( d . 1923 ) , Paris - 1918 , sold by to Paul Rosenberg and Co. , Paris and New York - 1920 , sold by Rosenberg to Philip Lehman ( b . 1861 - d . 1947 ) , New York.April 14 , 1876 , Monet and sale , , Paris , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Paris ,",
    " It is possible that Monet had informed of his trick , and that he had warned him not to tell anyone else , or that Monet wanted to hide from the public the painting Camille had modeled for , given the criticism of the paintings sexually suggestive nature , though no one mentioned Camilles name in connection with the work until Monet revealed her role to and in 1918 , the blond wig having disguised her identity until this point .",
    "Forty years later , in 1918 , when the art dealers and visited Monet and informed him that had sold for a very decent price , Monet was said to stated that he was ashamed by the fact of having painted the work simply to please the market , calling it a piece of filth . Some scholars believe that he may have been more committed to this subject than these comments would suggest ; when the work was in progress , Monet wrote to Philippe Burty , a famous art critic and collector of Japanese artworks , commenting that"
  ],
  "meta": {
    "time_scope": [
      "1918",
      "1920"
    ],
    "annotated_para": "- 1918 , sold by to Paul Rosenberg and Co. , Paris and New York",
    "type": "order",
    "ID": 618
  }
}
```

| Original | Localized |
|---|---|
| La Japonaise (painting) | Spring Morning (painting) |
| Paris | Baku |
| Paul Rosenberg and Co | Rəşad Məmmədov and Co |
| New York | Ganja |
| Rosenberg | Məmmədov |
| Philip Lehman | Fərid Həsənov |
| Monet | Səlim Qasımov |
| Camille | Aysel |
| Philippe Burty | Pərviz Əfəndiyev |
| Japanese artworks | regional artworks |

</details>

### 09. az_menatqa_order_009

Source record: **128** (1-based). Original meta.ID: `181`. Category: `order`.

**Question:** Which position did Lalə Həmidova hold from January 2008 to September 2014?

**Answer:** "Director of Social Affairs and Public Health ( December 2007 – October 2014 )"

**Context (original paragraph order):**

Paragraph 1:  In 2009 , she criticized community leader Bəhram Hacıyev over his comments that condoms distribution without prior education only worsen the AIDS crisis . In 2014 , it was revealed that her Ministry hired the firm of her own husband , , as a legal consultant , for a cost of 245,000 manat . On 13 September 2017 Həmidova announces not be a candidate for the 2019 elections .

Paragraph 2: Director of Social Affairs and Public Health ( December 2007 – October 2014 )Deputy Executive Chair and Director of Justice ( July 2003 – December 2007 ) 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which position did Laurette Onkelinx hold from January 2008 to September 2014?",
  "answer": "Minister of Social Affairs and Public Health ( December 2007 – October 2014 )",
  "context": [
    " In 2009 , she criticized Pope Benedict XVI over his comments that condoms distribution without prior education only worsen the AIDS crisis . In 2014 , it was revealed that her Ministry hired the firm of her own husband , , as a legal consultant , for a cost of 245,000 euros . On 13 September 2017 Onkelincx announces not be a candidate for the 2019 elections .",
    "Minister of Social Affairs and Public Health ( December 2007 – October 2014 )Deputy Prime Minister and Minister of Justice ( July 2003 – December 2007 ) "
  ],
  "meta": {
    "time_scope": [
      "Dec 2007",
      "Oct 2014"
    ],
    "annotated_para": "- Minister of Social Affairs and Public Health ( December 2007 – October 2014 )",
    "type": "order",
    "ID": 181
  }
}
```

| Original | Localized |
|---|---|
| Laurette Onkelinx | Lalə Həmidova |
| Minister of | Director of |
| Pope Benedict XVI | community leader Bəhram Hacıyev |
| 245,000 euros | 245,000 manat |
| Onkelincx | Həmidova |
| Deputy Prime Minister | Deputy Executive Chair |

</details>

### 10. az_menatqa_order_010

Source record: **161** (1-based). Original meta.ID: `321`. Category: `order`.

**Question:** Who was the chair of Youth Union from 1975 to 1981?

**Answer:** "Ramil Məlikov"

**Context (original paragraph order):**

Paragraph 1: Sənan Nəcəfov ( 2014–2018 ) - Rəşad Qədirov ( since 2018 ) Aysel Rəhmanova ( 1998–2002 ) - Anar Vəliyev ( 2002–2014 )Elnur Əsədov ( 1989–1994 ) - Murad Kərimov ( 1994–1998 ) Cavid Əliyev ( 1969–1973 ) - Ramil Məlikov ( 1973–1983 ) - Orxan Cəfərov ( 1983–1989 )  İlqar Nəsirov ( 1961–1963 ) - Natiq Orucov ( 1963–1969 ) Elman Cabbarov ( 1950–1955 ) - Fikrət Əkbərov ( 1955–1961 )Adil Səfərov ( 1947–1948 ) - Vüqar Rzayev ( 1948–1949 ) - Səbuhi İbrahimov ( 1949–1950 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the chair of Young Union from 1975 to 1981?",
  "answer": "Matthias Wissmann",
  "context": [
    "aul Ziemiak ( 2014–2018 ) - Tilman Kuban ( since 2018 ) Hildegard Müller ( 1998–2002 ) - Philipp Mißfelder ( 2002–2014 )Hermann Gröhe ( 1989–1994 ) - Klaus Escher ( 1994–1998 ) Jürgen Echternach ( 1969–1973 ) - Matthias Wissmann ( 1973–1983 ) - Christoph Böhr ( 1983–1989 )  Bert Even ( 1961–1963 ) - Egon Klepsch ( 1963–1969 ) Ernst Majonica ( 1950–1955 ) - Gerhard Stoltenberg ( 1955–1961 )Bruno Six ( 1947–1948 ) - Alfred Sagner ( 1948–1949 ) - Josef Dufhues ( 1949–1950 )"
  ],
  "meta": {
    "time_scope": [
      "1973",
      "1983"
    ],
    "annotated_para": "- Matthias Wissmann ( 1973–1983 )",
    "type": "order",
    "ID": 321
  }
}
```

| Original | Localized |
|---|---|
| Young Union | Youth Union |
| Matthias Wissmann | Ramil Məlikov |
| aul Ziemiak | Sənan Nəcəfov |
| Tilman Kuban | Rəşad Qədirov |
| Hildegard Müller | Aysel Rəhmanova |
| Philipp Mißfelder | Anar Vəliyev |
| Hermann Gröhe | Elnur Əsədov |
| Klaus Escher | Murad Kərimov |
| Jürgen Echternach | Cavid Əliyev |
| Christoph Böhr | Orxan Cəfərov |
| Bert Even | İlqar Nəsirov |
| Egon Klepsch | Natiq Orucov |
| Ernst Majonica | Elman Cabbarov |
| Gerhard Stoltenberg | Fikrət Əkbərov |
| Bruno Six | Adil Səfərov |
| Alfred Sagner | Vüqar Rzayev |
| Josef Dufhues | Səbuhi İbrahimov |

</details>

### 11. az_menatqa_order_011

Source record: **67** (1-based). Original meta.ID: `116`. Category: `order`.

**Question:** 194th Fighter Squadron was officially named what from  1951 to June 1956?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: 31 October 1950 - 144th Fighter-Interceptor Wing , 1 October 1952 - 144th Fighter-Bomber Wing ,  372d Fighter ( Later Fighter-Bomber , Fighter ) Group , 15 October 1943 – 7 November 1945 - 144th Fighter Group , 25 June 1948 - 144th Fighter Wing ,1 December 1952 - 144th Fighter-Interceptor Wing , 7 July 1955 - 144th Operations Group , 16 March 1992 – Present.

Paragraph 2:  

<details><summary>Original record and replacements</summary>

```json
{
  "question": "194th Fighter Squadron was officially named what from  1951 to June 1956?",
  "answer": "unanswerable",
  "context": [
    "31 October 1950 - 144th Fighter-Interceptor Wing , 1 October 1952 - 144th Fighter-Bomber Wing ,  372d Fighter ( Later Fighter-Bomber , Fighter ) Group , 15 October 1943 – 7 November 1945 - 144th Fighter Group , 25 June 1948 - 144th Fighter Wing ,1 December 1952 - 144th Fighter-Interceptor Wing , 7 July 1955 - 144th Operations Group , 16 March 1992 – Present.",
    " "
  ],
  "meta": {
    "time_scope": [
      "Dec 1952",
      "Jul 1955"
    ],
    "annotated_para": "The wartime 409th Fighter Squadron was re-activated and re-designated as the 194th Fighter Squadron , and was allotted to the California Air National Guard , on 24 May 1946 . It was organized at Naval Air Station Alameda , California , and was extended federal recognition on 25 June 1948 by the National Guard Bureau . The 194th Fighter Squadron was bestowed to the history , honors , and colors of the 409th Fighter Squadron . The squadron was equipped with F-51D Mustangs and was assigned to the CA ANG 144th Fighter Group . During its early years with the F-51D , the unit earned prominence as one of the Air Forces most respected aerial gunnery competitors .",
    "type": "order",
    "ID": 116
  }
}
```

| Original | Localized |
|---|---|
| California Air National Guard | Regional Air Service |
| Naval Air Station Alameda , California | Sumgait Air Station |
| National Guard Bureau | Regional Defence Office |
| F-51D Mustangs | F-51D aircraft |
| CA ANG | RAS |

</details>

### 12. az_menatqa_order_012

Source record: **134** (1-based). Original meta.ID: `597`. Category: `order`.

**Question:** Caspian Research Library was managed or directed by whom from 2015 to 2016?

**Answer:** "Lətif İsmayılov"

**Context (original paragraph order):**

Paragraph 1:  - Musa Məmmədov - 1983—1988 - Mətin Hacıyev - 1988—2001 - Sadiq Quliyev - 2001—2012 - Davud Rəhmanov - 2012—2013 - Səbinə Rzayeva - 2013—2015 - Lətif İsmayılov 2015—incumbent

<details><summary>Original record and replacements</summary>

```json
{
  "question": "National Library of Serbia was managed or directed by whom from 2015 to 2016?",
  "answer": "Laslo Blašković",
  "context": [
    " - Milan Milutinović - 1983—1988 - Milomir Petrović - 1988—2001 - Sreten Ugričić - 2001—2012 - Dejan Ristić - 2012—2013 - Svetlana Jančić - 2013—2015 - Laslo Blašković 2015—incumbent"
  ],
  "meta": {
    "time_scope": [
      "2015",
      "2016"
    ],
    "annotated_para": "- Laslo Blašković 2015—incumbent",
    "type": "order",
    "ID": 597
  }
}
```

| Original | Localized |
|---|---|
| National Library of Serbia | Caspian Research Library |
| Laslo Blašković | Lətif İsmayılov |
| Milan Milutinović | Musa Məmmədov |
| Milomir Petrović | Mətin Hacıyev |
| Sreten Ugričić | Sadiq Quliyev |
| Dejan Ristić | Davud Rəhmanov |
| Svetlana Jančić | Səbinə Rzayeva |

</details>

### 13. az_menatqa_order_013

Source record: **5** (1-based). Original meta.ID: `841`. Category: `order`.

**Question:** Which position did Cəlil Həsənov hold in June 2002?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: He moved to the Regional Interior Department in 1999 , and joined the Cabinet as Director without Portfolio and Party Chair after the 2001 general election .Elected to the Regional Assembly in the Civic Unity victory of 1997 , Həsənov served just over a year on the back benches , before joining the government as a deputy education director in July 1998 . 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which position did Charles Clarke hold in June 2002?",
  "answer": "unanswerable",
  "context": [
    "He moved to the Home Office in 1999 , and joined the Cabinet as Minister without Portfolio and Party Chair after the 2001 general election .Elected to the British House of Commons in the Labour landslide of 1997 , Clarke served just over a year on the back benches , before joining the government as a junior education minister in July 1998 . "
  ],
  "meta": {
    "time_scope": [
      "Jun 2001",
      "Jun 2001"
    ],
    "annotated_para": "Elected to the British House of Commons in the Labour landslide of 1997 , Clarke served just over a year on the back benches , before joining the government as a junior education minister in July 1998 . He moved to the Home Office in 1999 , and joined the Cabinet as Minister without Portfolio and Party Chair after the 2001 general election .",
    "type": "order",
    "ID": 841
  }
}
```

| Original | Localized |
|---|---|
| Charles Clarke | Cəlil Həsənov |
| Home Office | Regional Interior Department |
| Minister without Portfolio | Director without Portfolio |
| British House of Commons | Regional Assembly |
| Labour landslide | Civic Unity victory |
| Clarke | Həsənov |
| junior education minister | deputy education director |

</details>

### 14. az_menatqa_order_014

Source record: **88** (1-based). Original meta.ID: `224`. Category: `order`.

**Question:** Who directed or managed Historical Pottery Catalogue from 2001 to 2004?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1:  Every participating country is completely responsible for its own scope , while the Caspian Academic Union in Baku has the patronage traditionally led by an Azerbaijani scientist . Currently in charge is Jalə Həmidova .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who directed or managed Corpus vasorum antiquorum from 2001 to 2004?",
  "answer": "unanswerable",
  "context": [
    " Every participating country is completely responsible for its own scope , while the Union Académique Internationale in Brussels has the patronage traditionally led by a French scientist . Currently in charge is Juliette de La Genière ."
  ],
  "meta": {
    "time_scope": [
      "2002",
      "2003"
    ],
    "annotated_para": "Every participating country is completely responsible for its own scope , while the Union Académique Internationale in Brussels has the patronage traditionally led by a French scientist . Currently in charge is Juliette de La Genière .",
    "type": "order",
    "ID": 224
  }
}
```

| Original | Localized |
|---|---|
| Corpus vasorum antiquorum | Historical Pottery Catalogue |
| Union Académique Internationale | Caspian Academic Union |
| Brussels | Baku |
| French scientist | Azerbaijani scientist |
| Juliette de La Genière | Jalə Həmidova |

</details>

### 15. az_menatqa_order_015

Source record: **117** (1-based). Original meta.ID: `276`. Category: `order`.

**Question:** Nərmin Əliyeva became a member of what organization or association in June 2012?

**Answer:** "Səda48"

**Context (original paragraph order):**

Paragraph 1:  - Səda Musiqi Şousu ! ( 2012– ) - ( 2012-2016 ) - ( 2013– ) - ( 2014 )

Paragraph 2:  2012 . Əliyeva joined Səda48 as part of the 14th generation trainees , after failing to pass the 13th generation audition the previous year . 2013 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Nana Okada became a member of what organization or association in June 2012?",
  "answer": "AKB48",
  "context": [
    " - AKBingo ! ( 2012– ) - ( 2012-2016 ) - ( 2013– ) - ( 2014 )",
    " 2012 . Okada joined AKB48 as part of the 14th generation trainees , after failing to pass the 13th generation audition the previous year . 2013 ."
  ],
  "meta": {
    "time_scope": [
      "2012",
      "2012"
    ],
    "annotated_para": "Okada joined AKB48 as part of the 14th generation trainees , after failing to pass the 13th generation audition the previous year .",
    "type": "order",
    "ID": 276
  }
}
```

| Original | Localized |
|---|---|
| Nana Okada | Nərmin Əliyeva |
| AKB48 | Səda48 |
| AKBingo | Səda Musiqi Şousu |
| Okada | Əliyeva |

</details>

### 16. az_menatqa_order_016

Source record: **94** (1-based). Original meta.ID: `568`. Category: `order`.

**Question:** What was Tofiq Həsənli 's occupation from 1966 to 1967?

**Answer:** "volunteer with the Regional Volunteer Service"

**Context (original paragraph order):**

Paragraph 1:  He was one of the founders of the Regional Policy Society , a public policy organization aligned with the Civic Reform Party . He served as a volunteer with the Regional Volunteer Service in Shirvan from 1966-1967 . From 1969 to 1970 he served as a National Council aide during the Presidency of Rəhim Kazımov .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was Tom Petri 's occupation from 1966 to 1967?",
  "answer": "volunteer with the Peace Corps",
  "context": [
    " He was one of the founders of the Ripon Society , a public policy organization aligned with the Republican Party . He served as a volunteer with the Peace Corps in Somalia from 1966-1967 . From 1969 to 1970 he served as a White House aide during the Presidency of Richard Nixon ."
  ],
  "meta": {
    "time_scope": [
      "1966",
      "1967"
    ],
    "annotated_para": "He served as a volunteer with the Peace Corps in Somalia from 1966-1967 . From 1969 to 1970 he served as a White House aide during the Presidency of Richard Nixon .",
    "type": "order",
    "ID": 568
  }
}
```

| Original | Localized |
|---|---|
| Tom Petri | Tofiq Həsənli |
| Peace Corps | Regional Volunteer Service |
| Ripon Society | Regional Policy Society |
| Republican Party | Civic Reform Party |
| Somalia | Shirvan |
| White House aide | National Council aide |
| Richard Nixon | Rəhim Kazımov |

</details>

### 17. az_menatqa_order_017

Source record: **10** (1-based). Original meta.ID: `6`. Category: `order`.

**Question:** Which school did Çiçək Həsənova go to from 1985 to 1987?

**Answer:** "Shaki Humanities Institute"

**Context (original paragraph order):**

Paragraph 1:  Çiçək Həsənova was born on 22 July 1965 in Shaki . She attended Shaki Girls School , graduating in 1984 , and then Shaki Humanities Institute where she received her bachelors degree in International Relations in 1988 . She later went to Baku Legal Education Institute where she received her Master of Laws degree in 2001 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which school did Cho Yoon-sun go to from 1985 to 1987?",
  "answer": "Seoul National University",
  "context": [
    " Cho Yoon-sun was born on 22 July 1965 in Seoul . She attended Sehwa Girls High School , graduating in 1984 , and then Seoul National University where she received her bachelors degree in International Relations in 1988 . She later went to Columbia Law School where she received her Master of Laws degree in 2001 ."
  ],
  "meta": {
    "time_scope": [
      "1984",
      "1988"
    ],
    "annotated_para": "Cho Yoon-sun was born on 22 July 1965 in Seoul . She attended Sehwa Girls High School , graduating in 1984 , and then Seoul National University where she received her bachelors degree in International Relations in 1988 . She later went to Columbia Law School where she received her Master of Laws degree in 2001 .",
    "type": "order",
    "ID": 6
  }
}
```

| Original | Localized |
|---|---|
| Cho Yoon-sun | Çiçək Həsənova |
| Seoul National University | Shaki Humanities Institute |
| Seoul | Shaki |
| Sehwa Girls High School | Shaki Girls School |
| Columbia Law School | Baku Legal Education Institute |

</details>

### 18. az_menatqa_order_018

Source record: **49** (1-based). Original meta.ID: `691`. Category: `order`.

**Question:** Who was the owner of The Flute Player from January 1893 to December 1893?

**Answer:** "Qasımov Art Gallery"

**Context (original paragraph order):**

Paragraph 1: It was included in a large exhibition of Vaqif İsmayılovs work in 1884 , a year after his premature death .Between 1873 and 1893 , the painting was owned by Vaqif İsmayılovs friend , composer and baritone Zaur Məcidov .  The painting was acquired by Qasımov Art Gallery in 1872 and again in 1893 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the owner of The Fifer from January 1893 to December 1893?",
  "answer": "Durand-Ruell",
  "context": [
    "It was included in a large exhibition of Manets work in 1884 , a year after his premature death .Between 1873 and 1893 , the painting was owned by Manets friend , composer and baritone Jean-Baptiste Faure .  The painting was acquired by Durand-Ruell in 1872 and again in 1893 ."
  ],
  "meta": {
    "time_scope": [
      "1893",
      "1894"
    ],
    "annotated_para": "The painting was acquired by Durand-Ruell in 1872 and again in 1893 . Between 1873 and 1893 , the painting was owned by Manets friend , composer and baritone Jean-Baptiste Faure . It was included in a large exhibition of Manets work in 1884 , a year after his premature death .",
    "type": "order",
    "ID": 691
  }
}
```

| Original | Localized |
|---|---|
| The Fifer | The Flute Player |
| Durand-Ruell | Qasımov Art Gallery |
| Manet | Vaqif İsmayılov |
| Jean-Baptiste Faure | Zaur Məcidov |

</details>

### 19. az_menatqa_order_019

Source record: **69** (1-based). Original meta.ID: `689`. Category: `order`.

**Question:** Who was the owner of The Flute Player from 1871 to 1874?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: It was included in a large exhibition of Vaqif İsmayılovs work in 1884 , a year after his premature death .Between 1873 and 1893 , the painting was owned by Vaqif İsmayılovs friend , composer and baritone Zaur Məcidov .  The painting was acquired by Qasımov Art Gallery in 1872 and again in 1893 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the owner of The Fifer from 1871 to 1874?",
  "answer": "unanswerable",
  "context": [
    "It was included in a large exhibition of Manets work in 1884 , a year after his premature death .Between 1873 and 1893 , the painting was owned by Manets friend , composer and baritone Jean-Baptiste Faure .  The painting was acquired by Durand-Ruell in 1872 and again in 1893 ."
  ],
  "meta": {
    "time_scope": [
      "1872",
      "1873"
    ],
    "annotated_para": "The painting was acquired by Durand-Ruell in 1872 and again in 1893 . Between 1873 and 1893 , the painting was owned by Manets friend , composer and baritone Jean-Baptiste Faure . It was included in a large exhibition of Manets work in 1884 , a year after his premature death .",
    "type": "order",
    "ID": 689
  }
}
```

| Original | Localized |
|---|---|
| The Fifer | The Flute Player |
| Manet | Vaqif İsmayılov |
| Jean-Baptiste Faure | Zaur Məcidov |
| Durand-Ruell | Qasımov Art Gallery |

</details>

### 20. az_menatqa_order_020

Source record: **104** (1-based). Original meta.ID: `693`. Category: `order`.

**Question:** Who owned The Flute Player from April 1911 to March 1912?

**Answer:** "the Regional Cultural Council"

**Context (original paragraph order):**

Paragraph 1:  It was included in the sweeping Vaqif İsmayılov retrospective held at the Baku Exhibition Hall in 1983 , the 100th anniversary of the artists death .It was displayed at the Baku Art Museum from 1914 until 1947 , when it was relocated to the Shaki Art Museum .The Flute Player was accepted by the Regional Cultural Council in lieu of taxes on the estate of its last private owner , the İsmayıl Cəfərov , and entered the national collections in 1911 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who owned The Fifer from April 1911 to March 1912?",
  "answer": "the French government",
  "context": [
    " It was included in the sweeping Manet retrospective held at the Grand Palais in 1983 , the 100th anniversary of the artists death .It was displayed at the Louvre from 1914 until 1947 , when it was relocated to the Musée du Jeu de Paume .Le fifre was accepted by the French government in lieu of taxes on the estate of its last private owner , the Count Isaac de Camondo , and entered the national collections in 1911 ."
  ],
  "meta": {
    "time_scope": [
      "1911",
      "1912"
    ],
    "annotated_para": "Le fifre was accepted by the French government in lieu of taxes on the estate of its last private owner , the Count Isaac de Camondo , and entered the national collections in 1911 . It was displayed at the Louvre from 1914 until 1947 , when it was relocated to the Musée du Jeu de Paume . It was included in the sweeping Manet retrospective held at the Grand Palais in 1983 , the 100th anniversary of the artists death .",
    "type": "order",
    "ID": 693
  }
}
```

| Original | Localized |
|---|---|
| The Fifer | The Flute Player |
| the French government | the Regional Cultural Council |
| Manet | Vaqif İsmayılov |
| Grand Palais | Baku Exhibition Hall |
| Louvre | Baku Art Museum |
| Musée du Jeu de Paume | Shaki Art Museum |
| Le fifre | The Flute Player |
| Count Isaac de Camondo | İsmayıl Cəfərov |

</details>

### 21. az_menatqa_order_021

Source record: **152** (1-based). Original meta.ID: `39`. Category: `order`.

**Question:** Orxan Rzayev played for which team from March 2012 to June 2012?

**Answer:** "Guba football club"

**Context (original paragraph order):**

Paragraph 1: Rzayev started a trial with regional club Guba football club in February 2012 , and after impressing signed for the club on a six-month loan . His time in Northern District was hampered by poor form and injuries , and he returned to Shirvan after playing just three Regional Premier League matches .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Oumar Niasse played for which team from March 2012 to June 2012?",
  "answer": "Brann",
  "context": [
    "Niasse started a trial with Norwegian club Brann in February 2012 , and after impressing signed for the club on a six-month loan . His time in Norway was hampered by poor form and injuries , and he returned to Senegal after playing just three Tippeligaen matches ."
  ],
  "meta": {
    "time_scope": [
      "Feb 2012",
      "Jul 2012"
    ],
    "annotated_para": "Niasse started a trial with Norwegian club Brann in February 2012 , and after impressing signed for the club on a six-month loan . His time in Norway was hampered by poor form and injuries , and he returned to Senegal after playing just three Tippeligaen matches .",
    "type": "order",
    "ID": 39
  }
}
```

| Original | Localized |
|---|---|
| Oumar Niasse | Orxan Rzayev |
| Brann | Guba football club |
| Niasse | Rzayev |
| Norwegian club | regional club |
| Norway | Northern District |
| Senegal | Shirvan |
| Tippeligaen | Regional Premier League |

</details>

### 22. az_menatqa_order_022

Source record: **22** (1-based). Original meta.ID: `556`. Category: `order`.

**Question:** Səlim Kazımov became a member of what organization or association in June 1995?

**Answer:** "Caspian Research Society"

**Context (original paragraph order):**

Paragraph 1: 1994 : Elected as a member of the Caspian Molecular Biology Society,1995 : Elected as a Fellow of the Caspian Research Society ,2000 : Elected as a Fellow of the Regional Academy of Medical Sciences,2001 : Caspian Cancer Research Prize,2002 : Hacıyev Lecture Award of the Caspian Research Society ,2007 : Rzayev Prize for Medicine ( 2007 ),2008 : Araz Medical Prize and Medal of the Caspian Research Society 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Stephen C. West became a member of what organization or association in June 1995?",
  "answer": "Royal Society",
  "context": [
    "1994 : Elected as a member of the European Molecular Biology Organization,1995 : Elected as a Fellow of the Royal Society ,2000 : Elected as a Fellow of the Academy of Medical Sciences,2001 : Swiss Bridge Prize for Cancer Research,2002 : Leeuwenhoek Lecture award of the Royal Society ,2007 : Louis-Jeantet Prize for Medicine ( 2007 ),2008 : Novartis Prize and Medal of the Royal Society "
  ],
  "meta": {
    "time_scope": [
      "1995",
      "1995"
    ],
    "annotated_para": "- 1995 : Elected as a Fellow of the Royal Society",
    "type": "order",
    "ID": 556
  }
}
```

| Original | Localized |
|---|---|
| Stephen C. West | Səlim Kazımov |
| Royal Society | Caspian Research Society |
| European Molecular Biology Organization | Caspian Molecular Biology Society |
| Academy of Medical Sciences | Regional Academy of Medical Sciences |
| Swiss Bridge Prize for Cancer Research | Caspian Cancer Research Prize |
| Leeuwenhoek Lecture award | Hacıyev Lecture Award |
| Louis-Jeantet Prize for Medicine | Rzayev Prize for Medicine |
| Novartis Prize | Araz Medical Prize |

</details>

### 23. az_menatqa_order_023

Source record: **1** (1-based). Original meta.ID: `557`. Category: `order`.

**Question:** Səlim Kazımov became a member of what organization or association in May 2016?

**Answer:** "Regional Academy of Sciences"

**Context (original paragraph order):**

Paragraph 1:  2010 : Khazar Medical Prize and Medal of the Caspian Research Society,2011 : Elected as a Fellow of the Caspian Academy of Cancer Sciences,2012 : The Regional Genetics Society Medal,2016 : Elected as an International Member of the Regional Academy of Sciences2018 : Lifetime Achievement in Cancer Research Prize awarded by Caspian Cancer Research Foundation,Kazımov has been recognised on a number of occasions for his research : - 2021 : Elected as International Honorary Member of the Caspian Academy of Arts and Sciences . 

Paragraph 2: Regional Cancer Research Funds laboratories in Guba in the Northern District , which subsequently became known as Caspian Cancer Research Foundation . His colleagues at Araz Research Centre laboratory included the Caspian Science Prize winners Tofiq Hacıyev and Tahir Quliyev . In 2016 , his laboratory moved to the new Caspian Molecular Research Institute in Shaki .

Paragraph 3:  Kazımov is on the editorial boards of a number of journals including Bio-Life ( 2014-2016 ) , Caspian Biology Journal ( 1996-2020 ) and Caspian Biology Reports .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Stephen C. West became a member of what organization or association in May 2016?",
  "answer": "National Academy of Sciences",
  "context": [
    " 2010 : GlaxoSmithKline Prize and Medal of the Royal Society,2011 : Elected as a Fellow of the European Academy of Cancer Sciences,2012 : The Genetics Society Medal,2016 : Elected as an International Member of the National Academy of Sciences ( USA )2018 : Lifetime Achievement in Cancer Research Prize awarded by Cancer Research UK,West has been recognised on a number of occasions for his research : - 2021 : Elected as International Honorary Member of the American Academy of Arts and Sciences . ",
    "Imperial Cancer Research Funds laboratories in South Mimms in Hertfordshire , which subsequently became known as Cancer Research UK . His colleagues at Clare Hall laboratory included the Nobel Prize winners Tim Hunt and Tomas Lindahl . In 2016 , his laboratory moved to the new Francis Crick Institute in London .",
    " West is on the editorial boards of a number of journals including e-Life ( 2014-2016 ) , EMBO Journal ( 1996-2020 ) and EMBO Reports ."
  ],
  "meta": {
    "time_scope": [
      "2016",
      "2016"
    ],
    "annotated_para": "- 2016 : Elected as an International Member of the National Academy of Sciences ( USA )",
    "type": "order",
    "ID": 557
  }
}
```

| Original | Localized |
|---|---|
| Stephen C. West | Səlim Kazımov |
| National Academy of Sciences | Regional Academy of Sciences |
| GlaxoSmithKline Prize | Khazar Medical Prize |
| Royal Society | Caspian Research Society |
| European Academy of Cancer Sciences | Caspian Academy of Cancer Sciences |
| The Genetics Society Medal | The Regional Genetics Society Medal |
| National Academy of Sciences ( USA ) | Regional Academy of Sciences |
| Cancer Research UK | Caspian Cancer Research Foundation |
| West | Kazımov |
| American Academy of Arts and Sciences | Caspian Academy of Arts and Sciences |
| Imperial Cancer Research Funds | Regional Cancer Research Funds |
| South Mimms in Hertfordshire | Guba in the Northern District |
| Clare Hall | Araz Research Centre |
| Nobel Prize | Caspian Science Prize |
| Tim Hunt | Tofiq Hacıyev |
| Tomas Lindahl | Tahir Quliyev |
| Francis Crick Institute | Caspian Molecular Research Institute |
| London | Shaki |
| e-Life | Bio-Life |
| EMBO Journal | Caspian Biology Journal |
| EMBO Reports | Caspian Biology Reports |

</details>

### 24. az_menatqa_order_024

Source record: **196** (1-based). Original meta.ID: `450`. Category: `order`.

**Question:** Elşən Rəsulov became a member of what organization or association in June 2009?

**Answer:** "Caspian Society of Sciences and Arts"

**Context (original paragraph order):**

Paragraph 1: a Member of the Caspian Academic Society ( 2020 ) , and a Fellow of the Caspian Research Society ( 2021 ) . He was invited speaker at the Caspian Congress of Mathematicians in Baku in 2006 and was Chair of the Caspian Computational Mathematics Society,Rəsulov is a Regional Member of the Caspian Society of Sciences and Arts ( 2009 ) , Fellow of the Regional Academy of Sciences ( 2010 ) , Fellow of the Caspian Applied Mathematics Society ( 2016 ) 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Endre Süli became a member of what organization or association in June 2009?",
  "answer": "Serbian Academy of Sciences and Arts",
  "context": [
    "a Member of the Academia Europaea ( 2020 ) , and a Fellow of the Royal Society ( 2021 ) . He was invited speaker at the International Congress of Mathematicians in Madrid in 2006 and was Chair of the Society for the Foundations of Computational Mathematics,Süli is a Foreign Member of the Serbian Academy of Sciences and Arts ( 2009 ) , Fellow of the European Academy of Sciences ( 2010 ) , Fellow of the Society for Industrial and Applied Mathematics ( 2016 ) "
  ],
  "meta": {
    "time_scope": [
      "2009",
      "2009"
    ],
    "annotated_para": "Süli is a Foreign Member of the Serbian Academy of Sciences and Arts ( 2009 ) , Fellow of the European Academy of Sciences ( 2010 ) , Fellow of the Society for Industrial and Applied Mathematics ( 2016 ) , a Member of the Academia Europaea ( 2020 ) , and a Fellow of the Royal Society ( 2021 ) . He was invited speaker at the International Congress of Mathematicians in Madrid in 2006 and was Chair of the Society for the Foundations of Computational Mathematics",
    "type": "order",
    "ID": 450
  }
}
```

| Original | Localized |
|---|---|
| Endre Süli | Elşən Rəsulov |
| Serbian Academy of Sciences and Arts | Caspian Society of Sciences and Arts |
| Academia Europaea | Caspian Academic Society |
| Royal Society | Caspian Research Society |
| International Congress of Mathematicians in Madrid | Caspian Congress of Mathematicians in Baku |
| Society for the Foundations of Computational Mathematics | Caspian Computational Mathematics Society |
| Süli | Rəsulov |
| Foreign Member | Regional Member |
| European Academy of Sciences | Regional Academy of Sciences |
| Society for Industrial and Applied Mathematics | Caspian Applied Mathematics Society |

</details>

### 25. az_menatqa_order_025

Source record: **15** (1-based). Original meta.ID: `201`. Category: `order`.

**Question:** Where was Rövşən Hacıyev educated from 1959 to 1963?

**Answer:** "Baku Business College"

**Context (original paragraph order):**

Paragraph 1: Hacıyev was born on May 16 , 1937 , in Goychay , Shirvan . He graduated from Goychay Central School in Goychay , Shirvan and earned a full scholarship to Baku Higher Studies Institute . He received his A.B . from Baku Humanities College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . in 1963 from the Baku Business College . He worked at the Ganja Economics Institute for a very brief time and then joined the faculty at Shaki Technical Institute . He has been on the faculty of the Shaki Business College since

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Where was Robert B. Wilson educated from 1959 to 1963?",
  "answer": "Harvard Business School",
  "context": [
    "Wilson was born on May 16 , 1937 , in Geneva , Nebraska . He graduated from Lincoln High School in Lincoln , Nebraska and earned a full scholarship to Harvard University . He received his A.B . from Harvard College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . in 1963 from the Harvard Business School . He worked at the University of California , Los Angeles for a very brief time and then joined the faculty at Stanford University . He has been on the faculty of the Stanford Business School since"
  ],
  "meta": {
    "time_scope": [
      "1959",
      "1963"
    ],
    "annotated_para": "Wilson was born on May 16 , 1937 , in Geneva , Nebraska . He graduated from Lincoln High School in Lincoln , Nebraska and earned a full scholarship to Harvard University . He received his A.B . from Harvard College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . in 1963 from the Harvard Business School . He worked at the University of California , Los Angeles for a very brief time and then joined the faculty at Stanford University . He has been on the faculty of the Stanford Business School since 1964 . He was also an affiliated faculty member of Harvard Law School from 1993 to 2001 .",
    "type": "order",
    "ID": 201
  }
}
```

| Original | Localized |
|---|---|
| Robert B. Wilson | Rövşən Hacıyev |
| Harvard Business School | Baku Business College |
| Wilson | Hacıyev |
| Geneva , Nebraska | Goychay , Shirvan |
| Lincoln High School in Lincoln , Nebraska | Goychay Central School in Goychay , Shirvan |
| Harvard University | Baku Higher Studies Institute |
| Harvard College | Baku Humanities College |
| University of California , Los Angeles | Ganja Economics Institute |
| Stanford University | Shaki Technical Institute |
| Stanford Business School | Shaki Business College |
| Harvard Law School | Baku Legal Studies College |

</details>

### 26. az_menatqa_order_026

Source record: **199** (1-based). Original meta.ID: `200`. Category: `order`.

**Question:** Rövşən Hacıyev went to which school from September 1958 to June 1959?

**Answer:** "Baku Humanities College"

**Context (original paragraph order):**

Paragraph 1:  in 1963 from the Baku Business College . He worked at the Ganja Economics Institute for a very brief time and then joined the faculty at Shaki Technical Institute . He has been on the faculty of the Shaki Business College since,He received his A.B . from Baku Humanities College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . Hacıyev was born on May 16 , 1937 , in Goychay , Shirvan . He graduated from Goychay Central School in Goychay , Shirvan and earned a full scholarship to Baku Higher Studies Institute .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Robert B. Wilson went to which school from September 1958 to June 1959?",
  "answer": "Harvard College",
  "context": [
    " in 1963 from the Harvard Business School . He worked at the University of California , Los Angeles for a very brief time and then joined the faculty at Stanford University . He has been on the faculty of the Stanford Business School since,He received his A.B . from Harvard College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . Wilson was born on May 16 , 1937 , in Geneva , Nebraska . He graduated from Lincoln High School in Lincoln , Nebraska and earned a full scholarship to Harvard University ."
  ],
  "meta": {
    "time_scope": [
      "1958",
      "1959"
    ],
    "annotated_para": "Wilson was born on May 16 , 1937 , in Geneva , Nebraska . He graduated from Lincoln High School in Lincoln , Nebraska and earned a full scholarship to Harvard University . He received his A.B . from Harvard College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . in 1963 from the Harvard Business School . He worked at the University of California , Los Angeles for a very brief time and then joined the faculty at Stanford University . He has been on the faculty of the Stanford Business School since 1964 . He was also an affiliated faculty member of Harvard Law School from 1993 to 2001 .",
    "type": "order",
    "ID": 200
  }
}
```

| Original | Localized |
|---|---|
| Robert B. Wilson | Rövşən Hacıyev |
| Harvard College | Baku Humanities College |
| Harvard Business School | Baku Business College |
| University of California , Los Angeles | Ganja Economics Institute |
| Stanford University | Shaki Technical Institute |
| Stanford Business School | Shaki Business College |
| Wilson | Hacıyev |
| Geneva , Nebraska | Goychay , Shirvan |
| Lincoln High School in Lincoln , Nebraska | Goychay Central School in Goychay , Shirvan |
| Harvard University | Baku Higher Studies Institute |
| Harvard Law School | Baku Legal Studies College |

</details>

### 27. az_menatqa_order_027

Source record: **96** (1-based). Original meta.ID: `594`. Category: `order`.

**Question:** Where was Vaqif Rəsulov educated from September 1930 to June 1931?

**Answer:** "Goychay Geography Institute"

**Context (original paragraph order):**

Paragraph 1:  Rəsulov joined the Regional Assembly Library in 1946 and became chief of its map department in 1967 . Rəsulov graduated with a degree in geography from the Goychay Geography Institute in 1931 . He went on to earn a masters degree in geography from Shaki Geography College and a doctorate from Ganja Geography Institute .Vaqif Rəsulov ( April 20 , 1908 in Goychay , Shirvan – April 3 , 2006 in Shaki , Azerbaijan ) was the head librarian of the map library at the Ganja Public Library and later the Regional Assembly Library .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Where was Walter Ristow educated from September 1930 to June 1931?",
  "answer": "University of Wisconsin",
  "context": [
    " Ristow joined the Library of Congress in 1946 and became chief of its map department in 1967 . Ristow graduated with a degree in geography from the University of Wisconsin in 1931 . He went on to earn a masters degree in geography from Oberlin College and a doctorate from Clark University .Walter William Ristow ( April 20 , 1908 in La Crosse , Wisconsin – April 3 , 2006 in Mitchellville , Maryland ) was the head librarian of the map library at the New York Public Library and later the Library of Congress ."
  ],
  "meta": {
    "time_scope": [
      "1930",
      "1931"
    ],
    "annotated_para": "Walter William Ristow ( April 20 , 1908 in La Crosse , Wisconsin – April 3 , 2006 in Mitchellville , Maryland ) was the head librarian of the map library at the New York Public Library and later the Library of Congress . Ristow graduated with a degree in geography from the University of Wisconsin in 1931 . He went on to earn a masters degree in geography from Oberlin College and a doctorate from Clark University . Ristow joined the Library of Congress in 1946 and became chief of its map department in 1967 . He retired in 1978 .",
    "type": "order",
    "ID": 594
  }
}
```

| Original | Localized |
|---|---|
| Walter Ristow | Vaqif Rəsulov |
| University of Wisconsin | Goychay Geography Institute |
| Ristow | Rəsulov |
| Library of Congress | Regional Assembly Library |
| Oberlin College | Shaki Geography College |
| Clark University | Ganja Geography Institute |
| Walter William Ristow | Vaqif Rəsulov |
| La Crosse , Wisconsin | Goychay , Shirvan |
| Mitchellville , Maryland | Shaki , Azerbaijan |
| New York Public Library | Ganja Public Library |

</details>

### 28. az_menatqa_order_028

Source record: **76** (1-based). Original meta.ID: `942`. Category: `order`.

**Question:** Davud Qasımov went to which school from September 1947 to June 1948?

**Answer:** "Goychay Engineering College"

**Context (original paragraph order):**

Paragraph 1: Midway through his undergraduate years at Goychay Engineering College , he served two years in the Caspian Coastal Air Service as a radio and radar technician in the Absheron Islands . It was there on a small island , in a tiny hut on stilts , he read Vahid Hacıyevs article As We May Think , which greatly inspired him . He returned to Goychay Engineering College and completed his bachelors degree in electrical engineering in 1948 . While at Goychay Engineering College , he was a member of Caspian Student Society social fraternity . He was hired by the National Advisory Committee for

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Douglas Engelbart went to which school from September 1947 to June 1948?",
  "answer": "Oregon State University",
  "context": [
    "Midway through his undergraduate years at Oregon State University , he served two years in the United States Navy as a radio and radar technician in the Philippines . It was there on a small island , in a tiny hut on stilts , he read Vannevar Bushs article As We May Think , which greatly inspired him . He returned to Oregon State and completed his bachelors degree in electrical engineering in 1948 . While at Oregon State , he was a member of Sigma Phi Epsilon social fraternity . He was hired by the National Advisory Committee for"
  ],
  "meta": {
    "time_scope": [
      "1947",
      "1948"
    ],
    "annotated_para": "Midway through his undergraduate years at Oregon State University , he served two years in the United States Navy as a radio and radar technician in the Philippines . It was there on a small island , in a tiny hut on stilts , he read Vannevar Bushs article As We May Think , which greatly inspired him . He returned to Oregon State and completed his bachelors degree in electrical engineering in 1948 . While at Oregon State , he was a member of Sigma Phi Epsilon social fraternity . He was hired by the National Advisory Committee for Aeronautics at the Ames Research Center , where he worked in wind tunnel maintenance . In his off hours he enjoyed hiking , camping , and folk dancing . It was there he met Ballard Fish ( August 18 , 1928 – June 18 , 1997 ) , who was just completing her training to become an occupational therapist . They were married in Portola State Park on May 5 , 1951 . Soon after , Engelbart left Ames to pursue graduate studies at the University of California , Berkeley . There , he received an M.S . in electrical engineering in 1953 and a Ph.D . in the discipline in 1955 .",
    "type": "order",
    "ID": 942
  }
}
```

| Original | Localized |
|---|---|
| Douglas Engelbart | Davud Qasımov |
| Oregon State University | Goychay Engineering College |
| United States Navy | Caspian Coastal Air Service |
| Philippines | Absheron Islands |
| Vannevar Bush | Vahid Hacıyev |
| Oregon State | Goychay Engineering College |
| Sigma Phi Epsilon | Caspian Student Society |
| National Advisory Committee for Aeronautics | Regional Aeronautics Advisory Committee |
| Ames Research Center | Caspian Engineering Research Centre |
| Ballard Fish | Bahar Quliyeva |
| Portola State Park | Shaki Regional Park |
| Engelbart | Qasımov |
| Ames | Caspian Research Centre |
| University of California , Berkeley | Ganja Computing Institute |

</details>

### 29. az_menatqa_order_029

Source record: **65** (1-based). Original meta.ID: `308`. Category: `order`.

**Question:** Who did Cavid Rəsulov work for from 1989 to 1990?

**Answer:** "Caspian Natural History Institute"

**Context (original paragraph order):**

Paragraph 1:  - Shaki Research University , Committee on Evolutionary Biology , PhD , 1994 . - Shamakhi Biology College , Department of Biology , B.A. , 1989 . - Ganja Science School , graduated 1984 .

Paragraph 2:  - Shaki Natural Sciences Institute , Future Fellow , 2010–present . - Marine Science Institute , Lankaran Marine Studies College , Assistant and later Associate Researcher , 2000–2010 . - Caspian Ecology Centre , Post-doctoral Fellow , 1998–2000 , and Center Associate , 2000–2010 . - Shamakhi Biology Institute , Research Training Group in the Analysis of Biodiversification , 1994–1996 . - Caspian Natural History Institute , Predoctoral internship , Department of Paleobiology and Evolution of Terrestrial Ecosystems consortium , 1989–1990 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who did John Alroy work for from 1989 to 1990?",
  "answer": "Smithsonian Institution",
  "context": [
    " - University of Chicago , Committee on Evolutionary Biology , PhD , 1994 . - Reed College , Department of Biology , B.A. , 1989 . - Hunter College High School , graduated 1984 .",
    " - Macquarie University , Future Fellow , 2010–present . - Marine Science Institute , University of California , Santa Barbara , Assistant and later Associate Researcher , 2000–2010 . - National Center for Ecological Analysis and Synthesis , Post-doctoral Fellow , 1998–2000 , and Center Associate , 2000–2010 . - University of Arizona , Research Training Group in the Analysis of Biodiversification , 1994–1996 . - Smithsonian Institution , Predoctoral internship , Department of Paleobiology and Evolution of Terrestrial Ecosystems consortium , 1989–1990 ."
  ],
  "meta": {
    "time_scope": [
      "1989",
      "1990"
    ],
    "annotated_para": "- Smithsonian Institution , Predoctoral internship , Department of Paleobiology and Evolution of Terrestrial Ecosystems consortium , 1989–1990 .",
    "type": "order",
    "ID": 308
  }
}
```

| Original | Localized |
|---|---|
| John Alroy | Cavid Rəsulov |
| Smithsonian Institution | Caspian Natural History Institute |
| University of Chicago | Shaki Research University |
| Reed College | Shamakhi Biology College |
| Hunter College High School | Ganja Science School |
| Macquarie University | Shaki Natural Sciences Institute |
| University of California , Santa Barbara | Lankaran Marine Studies College |
| National Center for Ecological Analysis and Synthesis | Caspian Ecology Centre |
| University of Arizona | Shamakhi Biology Institute |

</details>

### 30. az_menatqa_order_030

Source record: **110** (1-based). Original meta.ID: `552`. Category: `order`.

**Question:** Which school did Adil Nəsirov go to from 1909 to 1910?

**Answer:** "Ganja Technical College"

**Context (original paragraph order):**

Paragraph 1:  Nəsirov was born in Goychay , Shirvan , Azerbaijan to Əli Nəsirov ( 1864–1959 ) and Elmira Quliyeva ( 1864–1947 ) . He was the eldest of 6 siblings . He attended Shamakhi Higher Studies Institute ( SHSI ) from 1903 to 1906 , and Ganja Technical College ( GTC ) from 1909 to 1910 . He graduated from Baku Legal Education Institute in 1912 , and returned to Shirvan . There he was admitted to the bar the same year and commenced practice in Shamakhi , Azerbaijan .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which school did Arthur Vivian Watkins go to from 1909 to 1910?",
  "answer": "New York University",
  "context": [
    " Watkins was born in Midway , Wasatch County , Utah to Arthur Watkins ( 1864–1959 ) and Emily Adelia Gerber ( 1864–1947 ) . He was the eldest of 6 siblings . He attended Brigham Young University ( BYU ) from 1903 to 1906 , and New York University ( NYU ) from 1909 to 1910 . He graduated from Columbia University Law School in 1912 , and returned to Utah . There he was admitted to the bar the same year and commenced practice in Vernal , Utah ."
  ],
  "meta": {
    "time_scope": [
      "1909",
      "1910"
    ],
    "annotated_para": "Watkins was born in Midway , Wasatch County , Utah to Arthur Watkins ( 1864–1959 ) and Emily Adelia Gerber ( 1864–1947 ) . He was the eldest of 6 siblings . He attended Brigham Young University ( BYU ) from 1903 to 1906 , and New York University ( NYU ) from 1909 to 1910 . He graduated from Columbia University Law School in 1912 , and returned to Utah . There he was admitted to the bar the same year and commenced practice in Vernal , Utah .",
    "type": "order",
    "ID": 552
  }
}
```

| Original | Localized |
|---|---|
| Arthur Vivian Watkins | Adil Nəsirov |
| New York University | Ganja Technical College |
| Watkins | Nəsirov |
| Midway , Wasatch County , Utah | Goychay , Shirvan , Azerbaijan |
| Arthur Watkins | Əli Nəsirov |
| Emily Adelia Gerber | Elmira Quliyeva |
| Brigham Young University | Shamakhi Higher Studies Institute |
| BYU | SHSI |
| NYU | GTC |
| Columbia University Law School | Baku Legal Education Institute |
| Utah | Shirvan |
| Vernal , Utah | Shamakhi , Azerbaijan |

</details>


## Scope — 30 samples

### 01. az_menatqa_scope_001

Source record: **332** (1-based). Original meta.ID: `597`. Category: `extract`.

**Question:** Caspian Research Library was managed or directed by whom from 2015 to 2016?

**Answer:** "Lətif İsmayılov"

**Context (original paragraph order):**

Paragraph 1:  - Musa Məmmədov - 1983—1988 - Mətin Hacıyev - 1988—2001 - Sadiq Quliyev - 2001—2012 - Davud Rəhmanov - 2012—2013 - Səbinə Rzayeva - 2013—2015 - Lətif İsmayılov 2015—incumbent

<details><summary>Original record and replacements</summary>

```json
{
  "question": "National Library of Serbia was managed or directed by whom from 2015 to 2016?",
  "answer": "Laslo Blašković",
  "context": [
    " - Milan Milutinović - 1983—1988 - Milomir Petrović - 1988—2001 - Sreten Ugričić - 2001—2012 - Dejan Ristić - 2012—2013 - Svetlana Jančić - 2013—2015 - Laslo Blašković 2015—incumbent"
  ],
  "meta": {
    "time_scope": [
      "2015",
      "2016"
    ],
    "annotated_para": "- Laslo Blašković 2015—incumbent",
    "type": "extract",
    "ID": 597
  }
}
```

| Original | Localized |
|---|---|
| National Library of Serbia | Caspian Research Library |
| Laslo Blašković | Lətif İsmayılov |
| Milan Milutinović | Musa Məmmədov |
| Milomir Petrović | Mətin Hacıyev |
| Sreten Ugričić | Sadiq Quliyev |
| Dejan Ristić | Davud Rəhmanov |
| Svetlana Jančić | Səbinə Rzayeva |

</details>

### 02. az_menatqa_scope_002

Source record: **260** (1-based). Original meta.ID: `279`. Category: `extract`.

**Question:** What was the name of the employer Rauf Əhmədov work for from 2004 to 2006?

**Answer:** "Baku football club"

**Context (original paragraph order):**

Paragraph 1:  Early years and Shaki football club . After starting as a manager with his main team Shamakhi football club , Əhmədov moved in 2004 to Baku football club , spending two seasons with its junior side . In 2006 , Əhmədov signed for Shaki football club , helping the club promote to the second level in his first season , followed by immediate relegation back . In 2008–09 , again as champion , he again led the side to division two .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the name of the employer Rui Vitória work for from 2004 to 2006?",
  "answer": "Benfica",
  "context": [
    " Early years and Fátima . After starting as a manager with his main team Vilafranquense , Vitória moved in 2004 to Benfica , spending two seasons with its junior side . In 2006 , Vitória signed for Fátima , helping the club promote to the second level in his first season , followed by immediate relegation back . In 2008–09 , again as champion , he again led the side to division two ."
  ],
  "meta": {
    "time_scope": [
      "2004",
      "2006"
    ],
    "annotated_para": "After starting as a manager with his main team Vilafranquense , Vitória moved in 2004 to Benfica , spending two seasons with its junior side .",
    "type": "extract",
    "ID": 279
  }
}
```

| Original | Localized |
|---|---|
| Rui Vitória | Rauf Əhmədov |
| Benfica | Baku football club |
| Fátima | Shaki football club |
| Vilafranquense | Shamakhi football club |
| Vitória | Əhmədov |

</details>

### 03. az_menatqa_scope_003

Source record: **108** (1-based). Original meta.ID: `618`. Category: `extract`.

**Question:** Spring Morning (painting) was owned by whom from 1918 to 1920?

**Answer:** "Rəşad Məmmədov and Co"

**Context (original paragraph order):**

Paragraph 1:  - April 14 , 1876 , Səlim Qasımov and sale , , Baku , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Baku , lot 48 , to ( d . 1923 ) , Baku - 1918 , sold by to Rəşad Məmmədov and Co. , Baku and Ganja - 1920 , sold by Məmmədov to Fərid Həsənov ( b . 1861 - d . 1947 ) , Ganja

Paragraph 2: Forty years later , in 1918 , when the art dealers and visited Səlim Qasımov and informed him that had sold for a very decent price , Səlim Qasımov was said to stated that he was ashamed by the fact of having painted the work simply to please the market , calling it a piece of filth . Some scholars believe that he may have been more committed to this subject than these comments would suggest ; when the work was in progress , Səlim Qasımov wrote to Pərviz Əfəndiyev , a famous art critic and collector of regional artworks , commenting that

Paragraph 3:  It is possible that Səlim Qasımov had informed of his trick , and that he had warned him not to tell anyone else , or that Səlim Qasımov wanted to hide from the public the painting Aysel had modeled for , given the criticism of the paintings sexually suggestive nature , though no one mentioned Aysels name in connection with the work until Səlim Qasımov revealed her role to and in 1918 , the blond wig having disguised her identity until this point .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "La Japonaise (painting) was owned by whom from 1918 to 1920?",
  "answer": "Paul Rosenberg and Co",
  "context": [
    " - April 14 , 1876 , Monet and sale , , Paris , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Paris , lot 48 , to ( d . 1923 ) , Paris - 1918 , sold by to Paul Rosenberg and Co. , Paris and New York - 1920 , sold by Rosenberg to Philip Lehman ( b . 1861 - d . 1947 ) , New York",
    "Forty years later , in 1918 , when the art dealers and visited Monet and informed him that had sold for a very decent price , Monet was said to stated that he was ashamed by the fact of having painted the work simply to please the market , calling it a piece of filth . Some scholars believe that he may have been more committed to this subject than these comments would suggest ; when the work was in progress , Monet wrote to Philippe Burty , a famous art critic and collector of Japanese artworks , commenting that",
    " It is possible that Monet had informed of his trick , and that he had warned him not to tell anyone else , or that Monet wanted to hide from the public the painting Camille had modeled for , given the criticism of the paintings sexually suggestive nature , though no one mentioned Camilles name in connection with the work until Monet revealed her role to and in 1918 , the blond wig having disguised her identity until this point ."
  ],
  "meta": {
    "time_scope": [
      "1918",
      "1920"
    ],
    "annotated_para": "- 1918 , sold by to Paul Rosenberg and Co. , Paris and New York",
    "type": "extract",
    "ID": 618
  }
}
```

| Original | Localized |
|---|---|
| La Japonaise (painting) | Spring Morning (painting) |
| Paul Rosenberg and Co | Rəşad Məmmədov and Co |
| Monet | Səlim Qasımov |
| Paris | Baku |
| New York | Ganja |
| Rosenberg | Məmmədov |
| Philip Lehman | Fərid Həsənov |
| Philippe Burty | Pərviz Əfəndiyev |
| Japanese artworks | regional artworks |
| Camille | Aysel |

</details>

### 04. az_menatqa_scope_004

Source record: **442** (1-based). Original meta.ID: `729`. Category: `extract`.

**Question:** What was the official name of SQ-29 from May 1946 to Nov 1946?

**Answer:** "Patrol Squadron 122"

**Context (original paragraph order):**

Paragraph 1: SQ-29 was a Patrol Squadron of the Caspian Coastal Air Service . The squadron was established as Patrol Squadron 14-F ( SQ-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( SQ-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( SQ-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( SQ-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( SB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( SQ-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( SQ-HL-12 ) on

Paragraph 2: 15 November 1946 , redesignated Patrol Squadron 29 ( SQ-29 ) on 1 September 1948 and disestablished on 18 January 1950 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the official name of VP-29 from May 1946 to Nov 1946?",
  "answer": "Patrol Squadron 122",
  "context": [
    "VP-29 was a Patrol Squadron of the U.S . Navy . The squadron was established as Patrol Squadron 14-F ( VP-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( VP-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( VP-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( VP-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( VPB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( VP-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( VP-HL-12 ) on",
    "15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 ."
  ],
  "meta": {
    "time_scope": [
      "May 1946",
      "Nov 1946"
    ],
    "annotated_para": "VP-29 was a Patrol Squadron of the U.S . Navy . The squadron was established as Patrol Squadron 14-F ( VP-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( VP-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( VP-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( VP-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( VPB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( VP-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( VP-HL-12 ) on 15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 .",
    "type": "extract",
    "ID": 729
  }
}
```

| Original | Localized |
|---|---|
| VP- | SQ- |
| U.S . Navy | Caspian Coastal Air Service |
| VPB- | SB- |
| VP-HL- | SQ-HL- |

</details>

### 05. az_menatqa_scope_005

Source record: **458** (1-based). Original meta.ID: `731`. Category: `extract`.

**Question:** What was the official name of SQ-29 from Sep 1948 to 1950?

**Answer:** "Patrol Squadron 29"

**Context (original paragraph order):**

Paragraph 1: 15 November 1946 , redesignated Patrol Squadron 29 ( SQ-29 ) on 1 September 1948 and disestablished on 18 January 1950 .

Paragraph 2: - 2 June 1948 : SQ-HL-12 deployed to Guba Air Station , Northern District . Navigation training , winter patrols from Guba to Khachmaz , and collection of data on mountain snowfield topography comprised the majority of squadron duties .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the official name of VP-29 from Sep 1948 to 1950?",
  "answer": "Patrol Squadron 29",
  "context": [
    "15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 .",
    "- 2 June 1948 : VP-HL-12 deployed to NAS Kodiak , Alaska . Navigation training , ice patrols from Kodiak to Point Barrow , and collection of data on Arctic ice cap topography comprised the majority of squadron duties ."
  ],
  "meta": {
    "time_scope": [
      "Sep 1948",
      "Jan 1950"
    ],
    "annotated_para": "VP-29 was a Patrol Squadron of the U.S . Navy . The squadron was established as Patrol Squadron 14-F ( VP-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( VP-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( VP-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( VP-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( VPB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( VP-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( VP-HL-12 ) on 15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 .",
    "type": "extract",
    "ID": 731
  }
}
```

| Original | Localized |
|---|---|
| VP- | SQ- |
| VP-HL- | SQ-HL- |
| NAS Kodiak | Guba Air Station |
| Alaska | Northern District |
| ice patrols | winter patrols |
| Kodiak | Guba |
| Point Barrow | Khachmaz |
| Arctic ice cap | mountain snowfield |
| U.S . Navy | Caspian Coastal Air Service |
| VPB- | SB- |

</details>

### 06. az_menatqa_scope_006

Source record: **470** (1-based). Original meta.ID: `568`. Category: `extract`.

**Question:** What was Tofiq Həsənli 's occupation from 1966 to 1967?

**Answer:** "volunteer with the Regional Volunteer Service"

**Context (original paragraph order):**

Paragraph 1:  He was one of the founders of the Regional Policy Society , a public policy organization aligned with the Civic Reform Party . He served as a volunteer with the Regional Volunteer Service in Shirvan from 1966-1967 . From 1969 to 1970 he served as a National Council aide during the Presidency of Rəhim Kazımov .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was Tom Petri 's occupation from 1966 to 1967?",
  "answer": "volunteer with the Peace Corps",
  "context": [
    " He was one of the founders of the Ripon Society , a public policy organization aligned with the Republican Party . He served as a volunteer with the Peace Corps in Somalia from 1966-1967 . From 1969 to 1970 he served as a White House aide during the Presidency of Richard Nixon ."
  ],
  "meta": {
    "time_scope": [
      "1966",
      "1967"
    ],
    "annotated_para": "He served as a volunteer with the Peace Corps in Somalia from 1966-1967 . From 1969 to 1970 he served as a White House aide during the Presidency of Richard Nixon .",
    "type": "extract",
    "ID": 568
  }
}
```

| Original | Localized |
|---|---|
| Tom Petri | Tofiq Həsənli |
| Peace Corps | Regional Volunteer Service |
| Ripon Society | Regional Policy Society |
| Republican Party | Civic Reform Party |
| Somalia | Shirvan |
| White House aide | National Council aide |
| Richard Nixon | Rəhim Kazımov |

</details>

### 07. az_menatqa_scope_007

Source record: **19** (1-based). Original meta.ID: `552`. Category: `extract`.

**Question:** Which school did Adil Nəsirov go to from 1909 to 1910?

**Answer:** "Ganja Technical College"

**Context (original paragraph order):**

Paragraph 1:  Nəsirov was born in Goychay , Shirvan , Azerbaijan to Əli Nəsirov ( 1864–1959 ) and Elmira Quliyeva ( 1864–1947 ) . He was the eldest of 6 siblings . He attended Shamakhi Higher Studies Institute ( SHSI ) from 1903 to 1906 , and Ganja Technical College ( GTC ) from 1909 to 1910 . He graduated from Baku Legal Education Institute in 1912 , and returned to Shirvan . There he was admitted to the bar the same year and commenced practice in Shamakhi , Azerbaijan .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which school did Arthur Vivian Watkins go to from 1909 to 1910?",
  "answer": "New York University",
  "context": [
    " Watkins was born in Midway , Wasatch County , Utah to Arthur Watkins ( 1864–1959 ) and Emily Adelia Gerber ( 1864–1947 ) . He was the eldest of 6 siblings . He attended Brigham Young University ( BYU ) from 1903 to 1906 , and New York University ( NYU ) from 1909 to 1910 . He graduated from Columbia University Law School in 1912 , and returned to Utah . There he was admitted to the bar the same year and commenced practice in Vernal , Utah ."
  ],
  "meta": {
    "time_scope": [
      "1909",
      "1910"
    ],
    "annotated_para": "Watkins was born in Midway , Wasatch County , Utah to Arthur Watkins ( 1864–1959 ) and Emily Adelia Gerber ( 1864–1947 ) . He was the eldest of 6 siblings . He attended Brigham Young University ( BYU ) from 1903 to 1906 , and New York University ( NYU ) from 1909 to 1910 . He graduated from Columbia University Law School in 1912 , and returned to Utah . There he was admitted to the bar the same year and commenced practice in Vernal , Utah .",
    "type": "extract",
    "ID": 552
  }
}
```

| Original | Localized |
|---|---|
| Arthur Vivian Watkins | Adil Nəsirov |
| New York University | Ganja Technical College |
| Watkins | Nəsirov |
| Midway , Wasatch County , Utah | Goychay , Shirvan , Azerbaijan |
| Arthur Watkins | Əli Nəsirov |
| Emily Adelia Gerber | Elmira Quliyeva |
| Brigham Young University | Shamakhi Higher Studies Institute |
| BYU | SHSI |
| NYU | GTC |
| Columbia University Law School | Baku Legal Education Institute |
| Utah | Shirvan |
| Vernal , Utah | Shamakhi , Azerbaijan |

</details>

### 08. az_menatqa_scope_008

Source record: **342** (1-based). Original meta.ID: `201`. Category: `extract`.

**Question:** Where was Rövşən Hacıyev educated from 1959 to 1963?

**Answer:** "Baku Business College"

**Context (original paragraph order):**

Paragraph 1: Hacıyev was born on May 16 , 1937 , in Goychay , Shirvan . He graduated from Goychay Central School in Goychay , Shirvan and earned a full scholarship to Baku Higher Studies Institute . He received his A.B . from Baku Humanities College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . in 1963 from the Baku Business College . He worked at the Ganja Economics Institute for a very brief time and then joined the faculty at Shaki Technical Institute . He has been on the faculty of the Shaki Business College since

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Where was Robert B. Wilson educated from 1959 to 1963?",
  "answer": "Harvard Business School",
  "context": [
    "Wilson was born on May 16 , 1937 , in Geneva , Nebraska . He graduated from Lincoln High School in Lincoln , Nebraska and earned a full scholarship to Harvard University . He received his A.B . from Harvard College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . in 1963 from the Harvard Business School . He worked at the University of California , Los Angeles for a very brief time and then joined the faculty at Stanford University . He has been on the faculty of the Stanford Business School since"
  ],
  "meta": {
    "time_scope": [
      "1959",
      "1963"
    ],
    "annotated_para": "Wilson was born on May 16 , 1937 , in Geneva , Nebraska . He graduated from Lincoln High School in Lincoln , Nebraska and earned a full scholarship to Harvard University . He received his A.B . from Harvard College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . in 1963 from the Harvard Business School . He worked at the University of California , Los Angeles for a very brief time and then joined the faculty at Stanford University . He has been on the faculty of the Stanford Business School since 1964 . He was also an affiliated faculty member of Harvard Law School from 1993 to 2001 .",
    "type": "extract",
    "ID": 201
  }
}
```

| Original | Localized |
|---|---|
| Robert B. Wilson | Rövşən Hacıyev |
| Harvard Business School | Baku Business College |
| Wilson | Hacıyev |
| Geneva , Nebraska | Goychay , Shirvan |
| Lincoln High School in Lincoln , Nebraska | Goychay Central School in Goychay , Shirvan |
| Harvard University | Baku Higher Studies Institute |
| Harvard College | Baku Humanities College |
| University of California , Los Angeles | Ganja Economics Institute |
| Stanford University | Shaki Technical Institute |
| Stanford Business School | Shaki Business College |
| Harvard Law School | Baku Legal Studies College |

</details>

### 09. az_menatqa_scope_009

Source record: **302** (1-based). Original meta.ID: `181`. Category: `narrow`.

**Question:** Which position did Lalə Həmidova hold from January 2008 to September 2014?

**Answer:** "Director of Social Affairs and Public Health ( December 2007 – October 2014 )"

**Context (original paragraph order):**

Paragraph 1:  In 2009 , she criticized community leader Bəhram Hacıyev over his comments that condoms distribution without prior education only worsen the AIDS crisis . In 2014 , it was revealed that her Ministry hired the firm of her own husband , , as a legal consultant , for a cost of 245,000 manat . On 13 September 2017 Həmidova announces not be a candidate for the 2019 elections .

Paragraph 2: Director of Social Affairs and Public Health ( December 2007 – October 2014 )Deputy Executive Chair and Director of Justice ( July 2003 – December 2007 ) 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which position did Laurette Onkelinx hold from January 2008 to September 2014?",
  "answer": "Minister of Social Affairs and Public Health ( December 2007 – October 2014 )",
  "context": [
    " In 2009 , she criticized Pope Benedict XVI over his comments that condoms distribution without prior education only worsen the AIDS crisis . In 2014 , it was revealed that her Ministry hired the firm of her own husband , , as a legal consultant , for a cost of 245,000 euros . On 13 September 2017 Onkelincx announces not be a candidate for the 2019 elections .",
    "Minister of Social Affairs and Public Health ( December 2007 – October 2014 )Deputy Prime Minister and Minister of Justice ( July 2003 – December 2007 ) "
  ],
  "meta": {
    "time_scope": [
      "Dec 2007",
      "Oct 2014"
    ],
    "annotated_para": "- Minister of Social Affairs and Public Health ( December 2007 – October 2014 )",
    "type": "narrow",
    "ID": 181
  }
}
```

| Original | Localized |
|---|---|
| Laurette Onkelinx | Lalə Həmidova |
| Minister of | Director of |
| Pope Benedict XVI | community leader Bəhram Hacıyev |
| 245,000 euros | 245,000 manat |
| Onkelincx | Həmidova |
| Deputy Prime Minister | Deputy Executive Chair |

</details>

### 10. az_menatqa_scope_010

Source record: **372** (1-based). Original meta.ID: `167`. Category: `narrow`.

**Question:** Who was the director or manager of Caspian Policy Planning Centre from 1975 to 1977?

**Answer:** "Akif İsmayılov"

**Context (original paragraph order):**

Paragraph 1:  The Regional Analysis and Planning Centre , as it was first called , was set up on 18 May 1974 by then-External Relations Director Şakir Əhmədov , who wanted to implement some institutionalised out-of-the-box thought . The decree establishing its existence states its purpose as “contributing to the preparation of decisions in foreign affairs” by “analysing current situations” and “conducting attempts at foreseeing future evolutions” . Despite having changed names two times since then , it has remained a constant source of doctrine for ministers .

Paragraph 2: Rafiq İbrahimov ( 2010-2013 ) - Sərxan Əsədov ( 2013-2019 ) - Əliyar Əhmədov ( 2019- )İlham Nəcəfov ( 1999-2002 ) - Namiq Səlimov ( 2005-2010 ) - Lalə Vəliyeva ( 2010 ) Fərid Rəhmanov ( 1993-1995 ) - Hafiz Cabbarov ( 1995-1999 , 2002-2004 ) Ceyhun Qasımov ( 1984-1989 ) - Eldar Quliyev ( 1989-1993 )  Akif İsmayılov ( 1974-1978 ) - Bəxtiyar Rzayev ( 1979-1984 ) The CPPC has a history of renowned directors , either academics or career diplomats .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the director or manager of Policy Planning Staff (France) from 1975 to 1977?",
  "answer": "Thierry de Montbrial",
  "context": [
    " The Centre d’analyse et de prévision , as it was first called , was set up on 18 May 1974 by then-Foreign Minister Michel Jobert , who wanted to implement some institutionalised out-of-the-box thought . The decree establishing its existence states its purpose as “contributing to the preparation of decisions in foreign affairs” by “analysing current situations” and “conducting attempts at foreseeing future evolutions” . Despite having changed names two times since then , it has remained a constant source of doctrine for ministers .",
    "Joseph Maïla ( 2010-2013 ) - Justin Vaïsse ( 2013-2019 ) - Manuel Lafont Rapnouil ( 2019- )Michel Foucher ( 1999-2002 ) - Pierre Lévy ( 2005-2010 ) - Marie Mendras ( 2010 ) Bruno Racine ( 1993-1995 ) - Gilles Andréani ( 1995-1999 , 2002-2004 ) Philippe Coste ( 1984-1989 ) - Jean-Marie Guéhenno ( 1989-1993 )  Thierry de Montbrial ( 1974-1978 ) - Jean-Louis Gergorin ( 1979-1984 ) The CAPS has a history of renowned directors , either academics or career diplomats ."
  ],
  "meta": {
    "time_scope": [
      "1974",
      "1978"
    ],
    "annotated_para": "- Thierry de Montbrial ( 1974-1978 )",
    "type": "narrow",
    "ID": 167
  }
}
```

| Original | Localized |
|---|---|
| Policy Planning Staff (France) | Caspian Policy Planning Centre |
| Thierry de Montbrial | Akif İsmayılov |
| The Centre d’analyse et de prévision | The Regional Analysis and Planning Centre |
| Foreign Minister | External Relations Director |
| Michel Jobert | Şakir Əhmədov |
| Joseph Maïla | Rafiq İbrahimov |
| Justin Vaïsse | Sərxan Əsədov |
| Manuel Lafont Rapnouil | Əliyar Əhmədov |
| Michel Foucher | İlham Nəcəfov |
| Pierre Lévy | Namiq Səlimov |
| Marie Mendras | Lalə Vəliyeva |
| Bruno Racine | Fərid Rəhmanov |
| Gilles Andréani | Hafiz Cabbarov |
| Philippe Coste | Ceyhun Qasımov |
| Jean-Marie Guéhenno | Eldar Quliyev |
| Jean-Louis Gergorin | Bəxtiyar Rzayev |
| CAPS | CPPC |

</details>

### 11. az_menatqa_scope_011

Source record: **480** (1-based). Original meta.ID: `321`. Category: `narrow`.

**Question:** Who was the chair of Youth Union from 1975 to 1981?

**Answer:** "Ramil Məlikov"

**Context (original paragraph order):**

Paragraph 1: Sənan Nəcəfov ( 2014–2018 ) - Rəşad Qədirov ( since 2018 ) Aysel Rəhmanova ( 1998–2002 ) - Anar Vəliyev ( 2002–2014 )Elnur Əsədov ( 1989–1994 ) - Murad Kərimov ( 1994–1998 ) Cavid Əliyev ( 1969–1973 ) - Ramil Məlikov ( 1973–1983 ) - Orxan Cəfərov ( 1983–1989 )  İlqar Nəsirov ( 1961–1963 ) - Natiq Orucov ( 1963–1969 ) Elman Cabbarov ( 1950–1955 ) - Fikrət Əkbərov ( 1955–1961 )Adil Səfərov ( 1947–1948 ) - Vüqar Rzayev ( 1948–1949 ) - Səbuhi İbrahimov ( 1949–1950 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the chair of Young Union from 1975 to 1981?",
  "answer": "Matthias Wissmann",
  "context": [
    "aul Ziemiak ( 2014–2018 ) - Tilman Kuban ( since 2018 ) Hildegard Müller ( 1998–2002 ) - Philipp Mißfelder ( 2002–2014 )Hermann Gröhe ( 1989–1994 ) - Klaus Escher ( 1994–1998 ) Jürgen Echternach ( 1969–1973 ) - Matthias Wissmann ( 1973–1983 ) - Christoph Böhr ( 1983–1989 )  Bert Even ( 1961–1963 ) - Egon Klepsch ( 1963–1969 ) Ernst Majonica ( 1950–1955 ) - Gerhard Stoltenberg ( 1955–1961 )Bruno Six ( 1947–1948 ) - Alfred Sagner ( 1948–1949 ) - Josef Dufhues ( 1949–1950 )"
  ],
  "meta": {
    "time_scope": [
      "1973",
      "1983"
    ],
    "annotated_para": "- Matthias Wissmann ( 1973–1983 )",
    "type": "narrow",
    "ID": 321
  }
}
```

| Original | Localized |
|---|---|
| Young Union | Youth Union |
| Matthias Wissmann | Ramil Məlikov |
| aul Ziemiak | Sənan Nəcəfov |
| Tilman Kuban | Rəşad Qədirov |
| Hildegard Müller | Aysel Rəhmanova |
| Philipp Mißfelder | Anar Vəliyev |
| Hermann Gröhe | Elnur Əsədov |
| Klaus Escher | Murad Kərimov |
| Jürgen Echternach | Cavid Əliyev |
| Christoph Böhr | Orxan Cəfərov |
| Bert Even | İlqar Nəsirov |
| Egon Klepsch | Natiq Orucov |
| Ernst Majonica | Elman Cabbarov |
| Gerhard Stoltenberg | Fikrət Əkbərov |
| Bruno Six | Adil Səfərov |
| Alfred Sagner | Vüqar Rzayev |
| Josef Dufhues | Səbuhi İbrahimov |

</details>

### 12. az_menatqa_scope_012

Source record: **491** (1-based). Original meta.ID: `619`. Category: `narrow`.

**Question:** Who owned Spring Morning (painting) from April 1920 to March 1921?

**Answer:** "Fərid Həsənov"

**Context (original paragraph order):**

Paragraph 1: lot 48 , to ( d . 1923 ) , Baku - 1918 , sold by to Rəşad Məmmədov and Co. , Baku and Ganja - 1920 , sold by Məmmədov to Fərid Həsənov ( b . 1861 - d . 1947 ) , Ganja.April 14 , 1876 , Səlim Qasımov and sale , , Baku , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Baku 

Paragraph 2: - 1921 , sold by Həsənov to Quliyev Brothers Gallery , Shaki ; 1937 , shipped from Quliyev Gallery , Shaki to Quliyev Gallery , Ganja

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who owned La Japonaise (painting) from April 1920 to March 1921?",
  "answer": "Philip Lehman",
  "context": [
    "lot 48 , to ( d . 1923 ) , Paris - 1918 , sold by to Paul Rosenberg and Co. , Paris and New York - 1920 , sold by Rosenberg to Philip Lehman ( b . 1861 - d . 1947 ) , New York.April 14 , 1876 , Monet and sale , , Paris , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Paris ",
    "- 1921 , sold by Lehman to Duveen Brothers , Inc. , London ; 1937 , shipped from Duveen , London to Duveen , New York"
  ],
  "meta": {
    "time_scope": [
      "1920",
      "1921"
    ],
    "annotated_para": "- 1920 , sold by Rosenberg to Philip Lehman ( b . 1861 - d . 1947 ) , New York",
    "type": "narrow",
    "ID": 619
  }
}
```

| Original | Localized |
|---|---|
| La Japonaise (painting) | Spring Morning (painting) |
| Philip Lehman | Fərid Həsənov |
| Paris | Baku |
| Paul Rosenberg and Co | Rəşad Məmmədov and Co |
| New York | Ganja |
| Rosenberg | Məmmədov |
| Monet | Səlim Qasımov |
| Lehman | Həsənov |
| Duveen Brothers , Inc. | Quliyev Brothers Gallery |
| London | Shaki |
| Duveen | Quliyev Gallery |

</details>

### 13. az_menatqa_scope_013

Source record: **493** (1-based). Original meta.ID: `39`. Category: `narrow`.

**Question:** Orxan Rzayev played for which team from March 2012 to June 2012?

**Answer:** "Guba football club"

**Context (original paragraph order):**

Paragraph 1: Rzayev started a trial with regional club Guba football club in February 2012 , and after impressing signed for the club on a six-month loan . His time in Northern District was hampered by poor form and injuries , and he returned to Shirvan after playing just three Regional Premier League matches .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Oumar Niasse played for which team from March 2012 to June 2012?",
  "answer": "Brann",
  "context": [
    "Niasse started a trial with Norwegian club Brann in February 2012 , and after impressing signed for the club on a six-month loan . His time in Norway was hampered by poor form and injuries , and he returned to Senegal after playing just three Tippeligaen matches ."
  ],
  "meta": {
    "time_scope": [
      "Feb 2012",
      "Jul 2012"
    ],
    "annotated_para": "Niasse started a trial with Norwegian club Brann in February 2012 , and after impressing signed for the club on a six-month loan . His time in Norway was hampered by poor form and injuries , and he returned to Senegal after playing just three Tippeligaen matches .",
    "type": "narrow",
    "ID": 39
  }
}
```

| Original | Localized |
|---|---|
| Oumar Niasse | Orxan Rzayev |
| Brann | Guba football club |
| Niasse | Rzayev |
| Norwegian club | regional club |
| Norway | Northern District |
| Senegal | Shirvan |
| Tippeligaen | Regional Premier League |

</details>

### 14. az_menatqa_scope_014

Source record: **6** (1-based). Original meta.ID: `6`. Category: `narrow`.

**Question:** Which school did Çiçək Həsənova go to from 1985 to 1987?

**Answer:** "Shaki Humanities Institute"

**Context (original paragraph order):**

Paragraph 1:  Çiçək Həsənova was born on 22 July 1965 in Shaki . She attended Shaki Girls School , graduating in 1984 , and then Shaki Humanities Institute where she received her bachelors degree in International Relations in 1988 . She later went to Baku Legal Education Institute where she received her Master of Laws degree in 2001 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which school did Cho Yoon-sun go to from 1985 to 1987?",
  "answer": "Seoul National University",
  "context": [
    " Cho Yoon-sun was born on 22 July 1965 in Seoul . She attended Sehwa Girls High School , graduating in 1984 , and then Seoul National University where she received her bachelors degree in International Relations in 1988 . She later went to Columbia Law School where she received her Master of Laws degree in 2001 ."
  ],
  "meta": {
    "time_scope": [
      "1984",
      "1988"
    ],
    "annotated_para": "Cho Yoon-sun was born on 22 July 1965 in Seoul . She attended Sehwa Girls High School , graduating in 1984 , and then Seoul National University where she received her bachelors degree in International Relations in 1988 . She later went to Columbia Law School where she received her Master of Laws degree in 2001 .",
    "type": "narrow",
    "ID": 6
  }
}
```

| Original | Localized |
|---|---|
| Cho Yoon-sun | Çiçək Həsənova |
| Seoul National University | Shaki Humanities Institute |
| Seoul | Shaki |
| Sehwa Girls High School | Shaki Girls School |
| Columbia Law School | Baku Legal Education Institute |

</details>

### 15. az_menatqa_scope_015

Source record: **337** (1-based). Original meta.ID: `200`. Category: `narrow`.

**Question:** Rövşən Hacıyev went to which school from September 1958 to June 1959?

**Answer:** "Baku Humanities College"

**Context (original paragraph order):**

Paragraph 1:  in 1963 from the Baku Business College . He worked at the Ganja Economics Institute for a very brief time and then joined the faculty at Shaki Technical Institute . He has been on the faculty of the Shaki Business College since,He received his A.B . from Baku Humanities College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . Hacıyev was born on May 16 , 1937 , in Goychay , Shirvan . He graduated from Goychay Central School in Goychay , Shirvan and earned a full scholarship to Baku Higher Studies Institute .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Robert B. Wilson went to which school from September 1958 to June 1959?",
  "answer": "Harvard College",
  "context": [
    " in 1963 from the Harvard Business School . He worked at the University of California , Los Angeles for a very brief time and then joined the faculty at Stanford University . He has been on the faculty of the Stanford Business School since,He received his A.B . from Harvard College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . Wilson was born on May 16 , 1937 , in Geneva , Nebraska . He graduated from Lincoln High School in Lincoln , Nebraska and earned a full scholarship to Harvard University ."
  ],
  "meta": {
    "time_scope": [
      "1958",
      "1959"
    ],
    "annotated_para": "Wilson was born on May 16 , 1937 , in Geneva , Nebraska . He graduated from Lincoln High School in Lincoln , Nebraska and earned a full scholarship to Harvard University . He received his A.B . from Harvard College in 1959 . He then completed his M.B.A . in 1961 and his D.B.A . in 1963 from the Harvard Business School . He worked at the University of California , Los Angeles for a very brief time and then joined the faculty at Stanford University . He has been on the faculty of the Stanford Business School since 1964 . He was also an affiliated faculty member of Harvard Law School from 1993 to 2001 .",
    "type": "narrow",
    "ID": 200
  }
}
```

| Original | Localized |
|---|---|
| Robert B. Wilson | Rövşən Hacıyev |
| Harvard College | Baku Humanities College |
| Harvard Business School | Baku Business College |
| University of California , Los Angeles | Ganja Economics Institute |
| Stanford University | Shaki Technical Institute |
| Stanford Business School | Shaki Business College |
| Wilson | Hacıyev |
| Geneva , Nebraska | Goychay , Shirvan |
| Lincoln High School in Lincoln , Nebraska | Goychay Central School in Goychay , Shirvan |
| Harvard University | Baku Higher Studies Institute |
| Harvard Law School | Baku Legal Studies College |

</details>

### 16. az_menatqa_scope_016

Source record: **465** (1-based). Original meta.ID: `729`. Category: `narrow`.

**Question:** What was the official name of SQ-29 from June 1946 to October 1946?

**Answer:** "Patrol Squadron 122"

**Context (original paragraph order):**

Paragraph 1: on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( SQ-HL-12 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( SQ-122 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( SB-122 )on 1 July 1939 , redesignated Patrol Squadron 72 ( SQ-72 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( SQ-52 ) on 1 November 1935 , redesignated Patrol Squadron 14 ( SQ-14 ) SQ-29 was a Patrol Squadron of the Caspian Coastal Air Service . The squadron was established as Patrol Squadron 14-F ( SQ-14F ) 

Paragraph 2: 15 November 1946 , redesignated Patrol Squadron 29 ( SQ-29 ) on 1 September 1948 and disestablished on 18 January 1950 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the official name of VP-29 from June 1946 to October 1946?",
  "answer": "Patrol Squadron 122",
  "context": [
    "on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( VP-HL-12 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( VP-122 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( VPB-122 )on 1 July 1939 , redesignated Patrol Squadron 72 ( VP-72 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( VP-52 ) on 1 November 1935 , redesignated Patrol Squadron 14 ( VP-14 ) VP-29 was a Patrol Squadron of the U.S . Navy . The squadron was established as Patrol Squadron 14-F ( VP-14F ) ",
    "15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 ."
  ],
  "meta": {
    "time_scope": [
      "May 1946",
      "Nov 1946"
    ],
    "annotated_para": "VP-29 was a Patrol Squadron of the U.S . Navy . The squadron was established as Patrol Squadron 14-F ( VP-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( VP-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( VP-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( VP-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( VPB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( VP-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( VP-HL-12 ) on 15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 .",
    "type": "narrow",
    "ID": 729
  }
}
```

| Original | Localized |
|---|---|
| VP- | SQ- |
| VP-HL- | SQ-HL- |
| VPB- | SB- |
| U.S . Navy | Caspian Coastal Air Service |

</details>

### 17. az_menatqa_scope_017

Source record: **15** (1-based). Original meta.ID: `318`. Category: `granularity`.

**Question:** Who was the chair of Youth Union from Feb 1962 to May 1963?

**Answer:** "İlqar Nəsirov"

**Context (original paragraph order):**

Paragraph 1: Sənan Nəcəfov ( 2014–2018 ) - Rəşad Qədirov ( since 2018 ) Aysel Rəhmanova ( 1998–2002 ) - Anar Vəliyev ( 2002–2014 )Elnur Əsədov ( 1989–1994 ) - Murad Kərimov ( 1994–1998 ) Cavid Əliyev ( 1969–1973 ) - Ramil Məlikov ( 1973–1983 ) - Orxan Cəfərov ( 1983–1989 )  İlqar Nəsirov ( 1961–1963 ) - Natiq Orucov ( 1963–1969 ) Elman Cabbarov ( 1950–1955 ) - Fikrət Əkbərov ( 1955–1961 )Adil Səfərov ( 1947–1948 ) - Vüqar Rzayev ( 1948–1949 ) - Səbuhi İbrahimov ( 1949–1950 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the chair of Young Union from Feb 1962 to May 1963?",
  "answer": "Bert Even",
  "context": [
    "aul Ziemiak ( 2014–2018 ) - Tilman Kuban ( since 2018 ) Hildegard Müller ( 1998–2002 ) - Philipp Mißfelder ( 2002–2014 )Hermann Gröhe ( 1989–1994 ) - Klaus Escher ( 1994–1998 ) Jürgen Echternach ( 1969–1973 ) - Matthias Wissmann ( 1973–1983 ) - Christoph Böhr ( 1983–1989 )  Bert Even ( 1961–1963 ) - Egon Klepsch ( 1963–1969 ) Ernst Majonica ( 1950–1955 ) - Gerhard Stoltenberg ( 1955–1961 )Bruno Six ( 1947–1948 ) - Alfred Sagner ( 1948–1949 ) - Josef Dufhues ( 1949–1950 )"
  ],
  "meta": {
    "time_scope": [
      "1961",
      "1963"
    ],
    "annotated_para": "- Bert Even ( 1961–1963 )",
    "type": "granularity",
    "ID": 318
  }
}
```

| Original | Localized |
|---|---|
| Young Union | Youth Union |
| Bert Even | İlqar Nəsirov |
| aul Ziemiak | Sənan Nəcəfov |
| Tilman Kuban | Rəşad Qədirov |
| Hildegard Müller | Aysel Rəhmanova |
| Philipp Mißfelder | Anar Vəliyev |
| Hermann Gröhe | Elnur Əsədov |
| Klaus Escher | Murad Kərimov |
| Jürgen Echternach | Cavid Əliyev |
| Matthias Wissmann | Ramil Məlikov |
| Christoph Böhr | Orxan Cəfərov |
| Egon Klepsch | Natiq Orucov |
| Ernst Majonica | Elman Cabbarov |
| Gerhard Stoltenberg | Fikrət Əkbərov |
| Bruno Six | Adil Səfərov |
| Alfred Sagner | Vüqar Rzayev |
| Josef Dufhues | Səbuhi İbrahimov |

</details>

### 18. az_menatqa_scope_018

Source record: **355** (1-based). Original meta.ID: `293`. Category: `granularity`.

**Question:** Who did Rəşid Əfəndiyev work for from Mar 1991 to Dec 1994?

**Answer:** "Ganja Social Sciences Institute"

**Context (original paragraph order):**

Paragraph 1: He was then Professor at the Caspian Advanced Studies Institute ( 1996–2001 ) , before moving to Ganja Legal Studies Institute , where he is the Senior Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice . He became a faculty instructor in the Ganja Legal Studies Institute,Əfəndiyev was then Professor at the Ganja Social Sciences Institute ( 1990–95 ) , and also director of its Center for International and Public Law . Əfəndiyevs first academic appointments were at Shamakhi Law College ( 1985–89 ) and Baku Legal Studies College ( 1984–89 ) .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who did Philip Alston work for from Mar 1991 to Dec 1994?",
  "answer": "Australian National University",
  "context": [
    "He was then Professor at the European University Institute ( 1996–2001 ) , before moving to New York University School of Law , where he is the John Norton Pomeroy Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice . He became a faculty instructor in the NYU Law,Alston was then Professor at the Australian National University ( 1990–95 ) , and also director of its Center for International and Public Law . Alstons first academic appointments were at Tufts University ( 1985–89 ) and Harvard Law School ( 1984–89 ) ."
  ],
  "meta": {
    "time_scope": [
      "1990",
      "1995"
    ],
    "annotated_para": "Alstons first academic appointments were at Tufts University ( 1985–89 ) and Harvard Law School ( 1984–89 ) . Alston was then Professor at the Australian National University ( 1990–95 ) , and also director of its Center for International and Public Law . He was then Professor at the European University Institute ( 1996–2001 ) , before moving to New York University School of Law , where he is the John Norton Pomeroy Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice . He became a faculty instructor in the NYU Law Institute for Executive Education , which was launched in 2015 .",
    "type": "granularity",
    "ID": 293
  }
}
```

| Original | Localized |
|---|---|
| Philip Alston | Rəşid Əfəndiyev |
| Australian National University | Ganja Social Sciences Institute |
| European University Institute | Caspian Advanced Studies Institute |
| New York University School of Law | Ganja Legal Studies Institute |
| John Norton Pomeroy Professor | Senior Professor |
| NYU Law | Ganja Legal Studies Institute |
| Alston | Əfəndiyev |
| Tufts University | Shamakhi Law College |
| Harvard Law School | Baku Legal Studies College |
| NYU Law Institute for Executive Education | Ganja Institute of Professional Legal Education |

</details>

### 19. az_menatqa_scope_019

Source record: **359** (1-based). Original meta.ID: `324`. Category: `granularity`.

**Question:** Who was the head of Youth Union from Jun 1995 to Dec 1997?

**Answer:** "Murad Kərimov"

**Context (original paragraph order):**

Paragraph 1: Sənan Nəcəfov ( 2014–2018 ) - Rəşad Qədirov ( since 2018 ) Aysel Rəhmanova ( 1998–2002 ) - Anar Vəliyev ( 2002–2014 )Elnur Əsədov ( 1989–1994 ) - Murad Kərimov ( 1994–1998 ) Cavid Əliyev ( 1969–1973 ) - Ramil Məlikov ( 1973–1983 ) - Orxan Cəfərov ( 1983–1989 )  İlqar Nəsirov ( 1961–1963 ) - Natiq Orucov ( 1963–1969 ) Elman Cabbarov ( 1950–1955 ) - Fikrət Əkbərov ( 1955–1961 )Adil Səfərov ( 1947–1948 ) - Vüqar Rzayev ( 1948–1949 ) - Səbuhi İbrahimov ( 1949–1950 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the head of Young Union from Jun 1995 to Dec 1997?",
  "answer": "Klaus Escher",
  "context": [
    "aul Ziemiak ( 2014–2018 ) - Tilman Kuban ( since 2018 ) Hildegard Müller ( 1998–2002 ) - Philipp Mißfelder ( 2002–2014 )Hermann Gröhe ( 1989–1994 ) - Klaus Escher ( 1994–1998 ) Jürgen Echternach ( 1969–1973 ) - Matthias Wissmann ( 1973–1983 ) - Christoph Böhr ( 1983–1989 )  Bert Even ( 1961–1963 ) - Egon Klepsch ( 1963–1969 ) Ernst Majonica ( 1950–1955 ) - Gerhard Stoltenberg ( 1955–1961 )Bruno Six ( 1947–1948 ) - Alfred Sagner ( 1948–1949 ) - Josef Dufhues ( 1949–1950 )"
  ],
  "meta": {
    "time_scope": [
      "1994",
      "1998"
    ],
    "annotated_para": "- Klaus Escher ( 1994–1998 )",
    "type": "granularity",
    "ID": 324
  }
}
```

| Original | Localized |
|---|---|
| Young Union | Youth Union |
| Klaus Escher | Murad Kərimov |
| aul Ziemiak | Sənan Nəcəfov |
| Tilman Kuban | Rəşad Qədirov |
| Hildegard Müller | Aysel Rəhmanova |
| Philipp Mißfelder | Anar Vəliyev |
| Hermann Gröhe | Elnur Əsədov |
| Jürgen Echternach | Cavid Əliyev |
| Matthias Wissmann | Ramil Məlikov |
| Christoph Böhr | Orxan Cəfərov |
| Bert Even | İlqar Nəsirov |
| Egon Klepsch | Natiq Orucov |
| Ernst Majonica | Elman Cabbarov |
| Gerhard Stoltenberg | Fikrət Əkbərov |
| Bruno Six | Adil Səfərov |
| Alfred Sagner | Vüqar Rzayev |
| Josef Dufhues | Səbuhi İbrahimov |

</details>

### 20. az_menatqa_scope_020

Source record: **250** (1-based). Original meta.ID: `276`. Category: `granularity`.

**Question:** Nərmin Əliyeva became a member of what organization or association in June 2012?

**Answer:** "Səda48"

**Context (original paragraph order):**

Paragraph 1:  2012 . Əliyeva joined Səda48 as part of the 14th generation trainees , after failing to pass the 13th generation audition the previous year . 2013 .

Paragraph 2:  - Səda Musiqi Şousu ! ( 2012– ) - ( 2012-2016 ) - ( 2013– ) - ( 2014 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Nana Okada became a member of what organization or association in June 2012?",
  "answer": "AKB48",
  "context": [
    " 2012 . Okada joined AKB48 as part of the 14th generation trainees , after failing to pass the 13th generation audition the previous year . 2013 .",
    " - AKBingo ! ( 2012– ) - ( 2012-2016 ) - ( 2013– ) - ( 2014 )"
  ],
  "meta": {
    "time_scope": [
      "2012",
      "2012"
    ],
    "annotated_para": "Okada joined AKB48 as part of the 14th generation trainees , after failing to pass the 13th generation audition the previous year .",
    "type": "granularity",
    "ID": 276
  }
}
```

| Original | Localized |
|---|---|
| Nana Okada | Nərmin Əliyeva |
| AKB48 | Səda48 |
| Okada | Əliyeva |
| AKBingo | Səda Musiqi Şousu |

</details>

### 21. az_menatqa_scope_021

Source record: **297** (1-based). Original meta.ID: `556`. Category: `granularity`.

**Question:** Səlim Kazımov became a member of what organization or association in June 1995?

**Answer:** "Caspian Research Society"

**Context (original paragraph order):**

Paragraph 1: 1994 : Elected as a member of the Caspian Molecular Biology Society,1995 : Elected as a Fellow of the Caspian Research Society ,2000 : Elected as a Fellow of the Regional Academy of Medical Sciences,2001 : Caspian Cancer Research Prize,2002 : Hacıyev Lecture Award of the Caspian Research Society ,2007 : Rzayev Prize for Medicine ( 2007 ),2008 : Araz Medical Prize and Medal of the Caspian Research Society 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Stephen C. West became a member of what organization or association in June 1995?",
  "answer": "Royal Society",
  "context": [
    "1994 : Elected as a member of the European Molecular Biology Organization,1995 : Elected as a Fellow of the Royal Society ,2000 : Elected as a Fellow of the Academy of Medical Sciences,2001 : Swiss Bridge Prize for Cancer Research,2002 : Leeuwenhoek Lecture award of the Royal Society ,2007 : Louis-Jeantet Prize for Medicine ( 2007 ),2008 : Novartis Prize and Medal of the Royal Society "
  ],
  "meta": {
    "time_scope": [
      "1995",
      "1995"
    ],
    "annotated_para": "- 1995 : Elected as a Fellow of the Royal Society",
    "type": "granularity",
    "ID": 556
  }
}
```

| Original | Localized |
|---|---|
| Stephen C. West | Səlim Kazımov |
| Royal Society | Caspian Research Society |
| European Molecular Biology Organization | Caspian Molecular Biology Society |
| Academy of Medical Sciences | Regional Academy of Medical Sciences |
| Swiss Bridge Prize for Cancer Research | Caspian Cancer Research Prize |
| Leeuwenhoek Lecture award | Hacıyev Lecture Award |
| Louis-Jeantet Prize for Medicine | Rzayev Prize for Medicine |
| Novartis Prize | Araz Medical Prize |

</details>

### 22. az_menatqa_scope_022

Source record: **303** (1-based). Original meta.ID: `450`. Category: `granularity`.

**Question:** Elşən Rəsulov became a member of what organization or association in June 2009?

**Answer:** "Caspian Society of Sciences and Arts"

**Context (original paragraph order):**

Paragraph 1: a Member of the Caspian Academic Society ( 2020 ) , and a Fellow of the Caspian Research Society ( 2021 ) . He was invited speaker at the Caspian Congress of Mathematicians in Baku in 2006 and was Chair of the Caspian Computational Mathematics Society,Rəsulov is a Regional Member of the Caspian Society of Sciences and Arts ( 2009 ) , Fellow of the Regional Academy of Sciences ( 2010 ) , Fellow of the Caspian Applied Mathematics Society ( 2016 ) 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Endre Süli became a member of what organization or association in June 2009?",
  "answer": "Serbian Academy of Sciences and Arts",
  "context": [
    "a Member of the Academia Europaea ( 2020 ) , and a Fellow of the Royal Society ( 2021 ) . He was invited speaker at the International Congress of Mathematicians in Madrid in 2006 and was Chair of the Society for the Foundations of Computational Mathematics,Süli is a Foreign Member of the Serbian Academy of Sciences and Arts ( 2009 ) , Fellow of the European Academy of Sciences ( 2010 ) , Fellow of the Society for Industrial and Applied Mathematics ( 2016 ) "
  ],
  "meta": {
    "time_scope": [
      "2009",
      "2009"
    ],
    "annotated_para": "Süli is a Foreign Member of the Serbian Academy of Sciences and Arts ( 2009 ) , Fellow of the European Academy of Sciences ( 2010 ) , Fellow of the Society for Industrial and Applied Mathematics ( 2016 ) , a Member of the Academia Europaea ( 2020 ) , and a Fellow of the Royal Society ( 2021 ) . He was invited speaker at the International Congress of Mathematicians in Madrid in 2006 and was Chair of the Society for the Foundations of Computational Mathematics",
    "type": "granularity",
    "ID": 450
  }
}
```

| Original | Localized |
|---|---|
| Endre Süli | Elşən Rəsulov |
| Serbian Academy of Sciences and Arts | Caspian Society of Sciences and Arts |
| Academia Europaea | Caspian Academic Society |
| Royal Society | Caspian Research Society |
| International Congress of Mathematicians in Madrid | Caspian Congress of Mathematicians in Baku |
| Society for the Foundations of Computational Mathematics | Caspian Computational Mathematics Society |
| Süli | Rəsulov |
| Foreign Member | Regional Member |
| European Academy of Sciences | Regional Academy of Sciences |
| Society for Industrial and Applied Mathematics | Caspian Applied Mathematics Society |

</details>

### 23. az_menatqa_scope_023

Source record: **471** (1-based). Original meta.ID: `942`. Category: `granularity`.

**Question:** Davud Qasımov went to which school from September 1947 to June 1948?

**Answer:** "Goychay Engineering College"

**Context (original paragraph order):**

Paragraph 1: Midway through his undergraduate years at Goychay Engineering College , he served two years in the Caspian Coastal Air Service as a radio and radar technician in the Absheron Islands . It was there on a small island , in a tiny hut on stilts , he read Vahid Hacıyevs article As We May Think , which greatly inspired him . He returned to Goychay Engineering College and completed his bachelors degree in electrical engineering in 1948 . While at Goychay Engineering College , he was a member of Caspian Student Society social fraternity . He was hired by the National Advisory Committee for

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Douglas Engelbart went to which school from September 1947 to June 1948?",
  "answer": "Oregon State University",
  "context": [
    "Midway through his undergraduate years at Oregon State University , he served two years in the United States Navy as a radio and radar technician in the Philippines . It was there on a small island , in a tiny hut on stilts , he read Vannevar Bushs article As We May Think , which greatly inspired him . He returned to Oregon State and completed his bachelors degree in electrical engineering in 1948 . While at Oregon State , he was a member of Sigma Phi Epsilon social fraternity . He was hired by the National Advisory Committee for"
  ],
  "meta": {
    "time_scope": [
      "1947",
      "1948"
    ],
    "annotated_para": "Midway through his undergraduate years at Oregon State University , he served two years in the United States Navy as a radio and radar technician in the Philippines . It was there on a small island , in a tiny hut on stilts , he read Vannevar Bushs article As We May Think , which greatly inspired him . He returned to Oregon State and completed his bachelors degree in electrical engineering in 1948 . While at Oregon State , he was a member of Sigma Phi Epsilon social fraternity . He was hired by the National Advisory Committee for Aeronautics at the Ames Research Center , where he worked in wind tunnel maintenance . In his off hours he enjoyed hiking , camping , and folk dancing . It was there he met Ballard Fish ( August 18 , 1928 – June 18 , 1997 ) , who was just completing her training to become an occupational therapist . They were married in Portola State Park on May 5 , 1951 . Soon after , Engelbart left Ames to pursue graduate studies at the University of California , Berkeley . There , he received an M.S . in electrical engineering in 1953 and a Ph.D . in the discipline in 1955 .",
    "type": "granularity",
    "ID": 942
  }
}
```

| Original | Localized |
|---|---|
| Douglas Engelbart | Davud Qasımov |
| Oregon State University | Goychay Engineering College |
| United States Navy | Caspian Coastal Air Service |
| Philippines | Absheron Islands |
| Vannevar Bush | Vahid Hacıyev |
| Oregon State | Goychay Engineering College |
| Sigma Phi Epsilon | Caspian Student Society |
| National Advisory Committee for Aeronautics | Regional Aeronautics Advisory Committee |
| Ames Research Center | Caspian Engineering Research Centre |
| Ballard Fish | Bahar Quliyeva |
| Portola State Park | Shaki Regional Park |
| Engelbart | Qasımov |
| Ames | Caspian Research Centre |
| University of California , Berkeley | Ganja Computing Institute |

</details>

### 24. az_menatqa_scope_024

Source record: **54** (1-based). Original meta.ID: `179`. Category: `expand`.

**Question:** What position did Lalə Həmidova take in January and Oct 2003?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: this marriage were both their former husband and wife . In 2003 , Rəhmanov became an adviser to Həmidova cabinet , charged with the preparation of the election of the Regional Religious Affairs Council , and dealing with town management but , especially , with the communication between the cabinet and the Islamic associations .

Paragraph 2: Deputy Executive Chair and Director of Labour ( 1999–2003 ) Executive Chair and Director of Education , Media , Youth , Childs healthcare and Promotion of Health in the Central District ( 1995–1999 ) Executive Chair and Director of the Civil Service , Childs healthcare and Promotion of Health in the Central District ( 1993–1995 ) Director of Social Integration , Public Health and Environment ( 1992–1993 ) First elected to the Regional Assembly in 1988 , she has held several administrative posts without any interruption since 1992

Paragraph 3: - Deputy Executive Chair and Director of Labour and Transport ( 2003 )

Paragraph 4:  - Deputy Executive Chair and Director of Justice ( July 2003 – December 2007 ) - Director of Social Affairs and Public Health ( December 2007 – October 2014 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What position did Laurette Onkelinx take in January and Oct 2003?",
  "answer": "unanswerable",
  "context": [
    "this marriage were both their former husband and wife . In 2003 , Guenned became an adviser to Onkelinx cabinet , charged with the preparation of the election of the Belgian advisory Muslim council , and dealing with town management but , especially , with the communication between the cabinet and the Islamic associations .",
    "Deputy Prime Minister and Minister of Labour ( 1999–2003 ) Minister-President and Minister of Education , Media , Youth , Childs healthcare and Promotion of Health in the French Community ( 1995–1999 ) Minister-President and Minister of the Civil Service , Childs healthcare and Promotion of Health in the French Community ( 1993–1995 ) Minister of Social Integration , Public Health and Environment ( 1992–1993 ) First elected to the Belgian House of Representatives in 1988 , she has held several ministerial posts without any interruption since 1992",
    "- Deputy Prime Minister and Minister of Labour and Transport ( 2003 )",
    " - Deputy Prime Minister and Minister of Justice ( July 2003 – December 2007 ) - Minister of Social Affairs and Public Health ( December 2007 – October 2014 )"
  ],
  "meta": {
    "time_scope": [
      "May 2003",
      "Jul 2003"
    ],
    "annotated_para": "- Deputy Prime Minister and Minister of Labour and Transport ( 2003 )",
    "type": "expand",
    "ID": 179
  }
}
```

| Original | Localized |
|---|---|
| Laurette Onkelinx | Lalə Həmidova |
| Guenned | Rəhmanov |
| Onkelinx | Həmidova |
| Belgian advisory Muslim council | Regional Religious Affairs Council |
| Deputy Prime Minister | Deputy Executive Chair |
| Minister of | Director of |
| Minister-President | Executive Chair |
| French Community | Central District |
| Belgian House of Representatives | Regional Assembly |
| ministerial posts | administrative posts |

</details>

### 25. az_menatqa_scope_025

Source record: **117** (1-based). Original meta.ID: `618`. Category: `expand`.

**Question:** Spring Morning (painting) was owned by whom from 1919 to 1921?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1:  lot 48 , to ( d . 1923 ) , Baku - 1918 , sold by to Rəşad Məmmədov and Co. , Baku and Ganja - 1920 , sold by Məmmədov to Fərid Həsənov ( b . 1861 - d . 1947 ) , Ganja.April 14 , 1876 , Səlim Qasımov and sale , , Baku , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Baku ,

Paragraph 2: Forty years later , in 1918 , when the art dealers and visited Səlim Qasımov and informed him that had sold for a very decent price , Səlim Qasımov was said to stated that he was ashamed by the fact of having painted the work simply to please the market , calling it a piece of filth . Some scholars believe that he may have been more committed to this subject than these comments would suggest ; when the work was in progress , Səlim Qasımov wrote to Pərviz Əfəndiyev , a famous art critic and collector of regional artworks , commenting that

Paragraph 3:  It is possible that Səlim Qasımov had informed of his trick , and that he had warned him not to tell anyone else , or that Səlim Qasımov wanted to hide from the public the painting Aysel had modeled for , given the criticism of the paintings sexually suggestive nature , though no one mentioned Aysels name in connection with the work until Səlim Qasımov revealed her role to and in 1918 , the blond wig having disguised her identity until this point .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "La Japonaise (painting) was owned by whom from 1919 to 1921?",
  "answer": "unanswerable",
  "context": [
    " lot 48 , to ( d . 1923 ) , Paris - 1918 , sold by to Paul Rosenberg and Co. , Paris and New York - 1920 , sold by Rosenberg to Philip Lehman ( b . 1861 - d . 1947 ) , New York.April 14 , 1876 , Monet and sale , , Paris , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Paris ,",
    "Forty years later , in 1918 , when the art dealers and visited Monet and informed him that had sold for a very decent price , Monet was said to stated that he was ashamed by the fact of having painted the work simply to please the market , calling it a piece of filth . Some scholars believe that he may have been more committed to this subject than these comments would suggest ; when the work was in progress , Monet wrote to Philippe Burty , a famous art critic and collector of Japanese artworks , commenting that",
    " It is possible that Monet had informed of his trick , and that he had warned him not to tell anyone else , or that Monet wanted to hide from the public the painting Camille had modeled for , given the criticism of the paintings sexually suggestive nature , though no one mentioned Camilles name in connection with the work until Monet revealed her role to and in 1918 , the blond wig having disguised her identity until this point ."
  ],
  "meta": {
    "time_scope": [
      "1918",
      "1920"
    ],
    "annotated_para": "- 1918 , sold by to Paul Rosenberg and Co. , Paris and New York",
    "type": "expand",
    "ID": 618
  }
}
```

| Original | Localized |
|---|---|
| La Japonaise (painting) | Spring Morning (painting) |
| Paris | Baku |
| Paul Rosenberg and Co | Rəşad Məmmədov and Co |
| New York | Ganja |
| Rosenberg | Məmmədov |
| Philip Lehman | Fərid Həsənov |
| Monet | Səlim Qasımov |
| Philippe Burty | Pərviz Əfəndiyev |
| Japanese artworks | regional artworks |
| Camille | Aysel |

</details>

### 26. az_menatqa_scope_026

Source record: **127** (1-based). Original meta.ID: `280`. Category: `expand`.

**Question:** Who did Rauf Əhmədov work for from 2005 to 2011?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: In 2008–09 , again as champion , he again led the side to division two .In 2006 , Əhmədov signed for Shaki football club , helping the club promote to the second level in his first season , followed by immediate relegation back .Early years and Shaki football club . After starting as a manager with his main team Shamakhi football club , Əhmədov moved in 2004 to Baku football club , spending two seasons with its junior side . 

Paragraph 2:  On 2 June 2010 , Əhmədov replaced Tural İsmayılov at the helm of Goychay football club . In his first season in the top division , he guided the team to the seventh position in the league , also achieving runner-up honours in the domestic League Cup , which was won by Baku football club ( 2–1 ) .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who did Rui Vitória work for from 2005 to 2011?",
  "answer": "unanswerable",
  "context": [
    "In 2008–09 , again as champion , he again led the side to division two .In 2006 , Vitória signed for Fátima , helping the club promote to the second level in his first season , followed by immediate relegation back .Early years and Fátima . After starting as a manager with his main team Vilafranquense , Vitória moved in 2004 to Benfica , spending two seasons with its junior side . ",
    " On 2 June 2010 , Vitória replaced Ulisses Morais at the helm of Paços de Ferreira . In his first season in the top division , he guided the team to the seventh position in the league , also achieving runner-up honours in the domestic League Cup , which was won by Benfica ( 2–1 ) ."
  ],
  "meta": {
    "time_scope": [
      "2006",
      "2010"
    ],
    "annotated_para": "In 2006 , Vitória signed for Fátima , helping the club promote to the second level in his first season , followed by immediate relegation back . In 2008–09 , again as champion , he again led the side to division two .",
    "type": "expand",
    "ID": 280
  }
}
```

| Original | Localized |
|---|---|
| Rui Vitória | Rauf Əhmədov |
| Vitória | Əhmədov |
| Fátima | Shaki football club |
| Vilafranquense | Shamakhi football club |
| Benfica | Baku football club |
| Ulisses Morais | Tural İsmayılov |
| Paços de Ferreira | Goychay football club |

</details>

### 27. az_menatqa_scope_027

Source record: **144** (1-based). Original meta.ID: `169`. Category: `expand`.

**Question:** Who directed or managed Caspian Policy Planning Centre from 1983 to 1990?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: Rafiq İbrahimov ( 2010-2013 ) - Sərxan Əsədov ( 2013-2019 ) - Əliyar Əhmədov ( 2019- )İlham Nəcəfov ( 1999-2002 ) - Namiq Səlimov ( 2005-2010 ) - Lalə Vəliyeva ( 2010 ) Fərid Rəhmanov ( 1993-1995 ) - Hafiz Cabbarov ( 1995-1999 , 2002-2004 ) Ceyhun Qasımov ( 1984-1989 ) - Eldar Quliyev ( 1989-1993 )  Akif İsmayılov ( 1974-1978 ) - Bəxtiyar Rzayev ( 1979-1984 ) The CPPC has a history of renowned directors , either academics or career diplomats .

Paragraph 2: Its YLP program ( Young Leaders Programme – an invitation program for young foreign leaders ) , established in 1989 , which hosts about 75 young leaders ( under 45 ) a year , seeks to present the select few who are chosen with an unvarnished image of contemporary Azerbaijan and establish friendly ties with them . Since its creation , the program has hosted over 2,000 personalities from over 150 countries .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who directed or managed Policy Planning Staff (France) from 1983 to 1990?",
  "answer": "unanswerable",
  "context": [
    "Joseph Maïla ( 2010-2013 ) - Justin Vaïsse ( 2013-2019 ) - Manuel Lafont Rapnouil ( 2019- )Michel Foucher ( 1999-2002 ) - Pierre Lévy ( 2005-2010 ) - Marie Mendras ( 2010 ) Bruno Racine ( 1993-1995 ) - Gilles Andréani ( 1995-1999 , 2002-2004 ) Philippe Coste ( 1984-1989 ) - Jean-Marie Guéhenno ( 1989-1993 )  Thierry de Montbrial ( 1974-1978 ) - Jean-Louis Gergorin ( 1979-1984 ) The CAPS has a history of renowned directors , either academics or career diplomats .",
    "Its PIPA program ( Programme d’invitation des personnalités d’avenir – an invitation program for young foreign leaders ) , established in 1989 , which hosts about 75 young leaders ( under 45 ) a year , seeks to present the select few who are chosen with an unvarnished image of contemporary France and establish friendly ties with them . Since its creation , the program has hosted over 2,000 personalities from over 150 countries ."
  ],
  "meta": {
    "time_scope": [
      "1984",
      "1989"
    ],
    "annotated_para": "- Philippe Coste ( 1984-1989 )",
    "type": "expand",
    "ID": 169
  }
}
```

| Original | Localized |
|---|---|
| Policy Planning Staff (France) | Caspian Policy Planning Centre |
| Joseph Maïla | Rafiq İbrahimov |
| Justin Vaïsse | Sərxan Əsədov |
| Manuel Lafont Rapnouil | Əliyar Əhmədov |
| Michel Foucher | İlham Nəcəfov |
| Pierre Lévy | Namiq Səlimov |
| Marie Mendras | Lalə Vəliyeva |
| Bruno Racine | Fərid Rəhmanov |
| Gilles Andréani | Hafiz Cabbarov |
| Philippe Coste | Ceyhun Qasımov |
| Jean-Marie Guéhenno | Eldar Quliyev |
| Thierry de Montbrial | Akif İsmayılov |
| Jean-Louis Gergorin | Bəxtiyar Rzayev |
| CAPS | CPPC |
| PIPA | YLP |
| Programme d’invitation des personnalités d’avenir | Young Leaders Programme |
| France | Azerbaijan |

</details>

### 28. az_menatqa_scope_028

Source record: **292** (1-based). Original meta.ID: `597`. Category: `expand`.

**Question:** Caspian Research Library was managed or directed by whom from 2014 to 2017?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1:  Səbinə Rzayeva - 2013—2015 - Lətif İsmayılov 2015—incumbent,Musa Məmmədov - 1983—1988 - Mətin Hacıyev - 1988—2001 - Sadiq Quliyev - 2001—2012 - Davud Rəhmanov - 2012—2013 

<details><summary>Original record and replacements</summary>

```json
{
  "question": "National Library of Serbia was managed or directed by whom from 2014 to 2017?",
  "answer": "unanswerable",
  "context": [
    " Svetlana Jančić - 2013—2015 - Laslo Blašković 2015—incumbent,Milan Milutinović - 1983—1988 - Milomir Petrović - 1988—2001 - Sreten Ugričić - 2001—2012 - Dejan Ristić - 2012—2013 "
  ],
  "meta": {
    "time_scope": [
      "2015",
      "2016"
    ],
    "annotated_para": "- Laslo Blašković 2015—incumbent",
    "type": "expand",
    "ID": 597
  }
}
```

| Original | Localized |
|---|---|
| National Library of Serbia | Caspian Research Library |
| Svetlana Jančić | Səbinə Rzayeva |
| Laslo Blašković | Lətif İsmayılov |
| Milan Milutinović | Musa Məmmədov |
| Milomir Petrović | Mətin Hacıyev |
| Sreten Ugričić | Sadiq Quliyev |
| Dejan Ristić | Davud Rəhmanov |

</details>

### 29. az_menatqa_scope_029

Source record: **421** (1-based). Original meta.ID: `975`. Category: `expand`.

**Question:** Who was in charge of Regional Relations and Information Office from 2005 to 2008?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: The current director of RRIO is Məhərrəm Kazımov Former Directors of the agency include : - Oqtay Həsənov - Pərviz Rəsulov,Cəlal Məmmədov 2014-2018,Cavid Nəcəfov - Kamran Həmidov - İlqar Səlimov - Fəxri Quliyev

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was in charge of Office for Foreign Relations and Information from 2005 to 2008?",
  "answer": "unanswerable",
  "context": [
    "The current director of USZI is Marek Šimandl Former Directors of the agency include : - Oldřich Černý - Petr Zeman,Jiří Šašek 2014-2018,Jiří Lang - Karel Randák - Ivo Schwarz - František Bublan"
  ],
  "meta": {
    "time_scope": [
      "Sep 2006",
      "May 2007"
    ],
    "annotated_para": "- Jiří Lang",
    "type": "expand",
    "ID": 975
  }
}
```

| Original | Localized |
|---|---|
| Office for Foreign Relations and Information | Regional Relations and Information Office |
| USZI | RRIO |
| Marek Šimandl | Məhərrəm Kazımov |
| Oldřich Černý | Oqtay Həsənov |
| Petr Zeman | Pərviz Rəsulov |
| Jiří Šašek | Cəlal Məmmədov |
| Jiří Lang | Cavid Nəcəfov |
| Karel Randák | Kamran Həmidov |
| Ivo Schwarz | İlqar Səlimov |
| František Bublan | Fəxri Quliyev |

</details>

### 30. az_menatqa_scope_030

Source record: **424** (1-based). Original meta.ID: `260`. Category: `expand`.

**Question:** Which team did the player Kənan Məcidov belong to from 1987 to 1991?

**Answer:** "unanswerable"

**Context (original paragraph order):**

Paragraph 1: Məcidov was also one of the original participants of the National Basketball Three-Point Contest when it debuted in 1986 .and Goychay basketball club ( 1988–90 ) .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did the player Kyle Macy belong to from 1987 to 1991?",
  "answer": "unanswerable",
  "context": [
    "Macy was also one of the original participants of the NBA All-Star Three Point Contest when it debuted in 1986 .and Benetton Treviso ( 1988–90 ) ."
  ],
  "meta": {
    "time_scope": [
      "1988",
      "1990"
    ],
    "annotated_para": "Macy was selected with the 22nd pick of the 1979 NBA Draft by the Phoenix Suns , even though he had a year of college eligibility remaining . Macy played out his last year of college , and started playing for the Suns in 1980 . Macy spent five years with the Suns , averaging 10.6 points and 4.0 assists per game . Macy spent one year each with the Chicago Bulls ( 1985–86 ) and the Indiana Pacers ( 1986–87 ) before retiring from the NBA . Then he played professionally in Italy for Dietor Bologna ( 1987–88 ) and Benetton Treviso ( 1988–90 ) . Macy was also one of the original participants of the NBA All-Star Three Point Contest when it debuted in 1986 .",
    "type": "expand",
    "ID": 260
  }
}
```

| Original | Localized |
|---|---|
| Kyle Macy | Kənan Məcidov |
| Macy | Məcidov |
| NBA All-Star Three Point Contest | National Basketball Three-Point Contest |
| Benetton Treviso | Goychay basketball club |
| NBA Draft | National Basketball Draft |
| Phoenix Suns | Baku basketball club |
| Suns | Baku club |
| Chicago Bulls | Ganja basketball club |
| Indiana Pacers | Shaki basketball club |
| NBA | National Basketball League |
| Italy | Azerbaijan |
| Dietor Bologna | Sumgait basketball club |

</details>

