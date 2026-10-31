# TimeQA — fictional Azerbaijani adaptation

**Draft for your validation. English text; Azerbaijani translation has not been performed.**

All localized people, organizations, roles, biographies, teams, and events are fictional. Azerbaijani personal names and geographic settings are used for localization. Coincidental matches with real people or organizations do not assert facts about them.

30 easy + 30 hard = 60 records. Original temporal expressions, numbers, dates, question types and answer counts are preserved.

## Category counts

| Question type | Easy | Hard |
|---|---:|---:|
| after_implicit | 0 | 2 |
| before_implicit | 0 | 3 |
| between_explicit | 28 | 0 |
| between_implicit | 0 | 12 |
| in_explicit | 2 | 4 |
| in_implicit | 0 | 9 |
| **Total** | **30** | **30** |

## Review notes

- Names, locations and institutions were allowed to change by the user after the initial no-edit selection phase.
- Source-answer pairs with clear missing evidence or contradictions were excluded during selection; this is a human-review draft, not a claim of independently proven gold labels.
- The single selected unanswerable record remains unanswerable; its context contains no joining event for the queried year.
- Before/after questions retain the source benchmark convention and may need wording review during Azerbaijani translation.
- Some contexts occur in both easy and hard, as in the supplied files. These subsets are not independent train/test splits.
- International sports competitions are localized as fictional national or Caspian competitions to avoid assigning real-world international tournament results to Azerbaijan. Technical vocabulary is retained.
- A generic retrospective fictional setting is used. These texts are not historical accounts of Azerbaijan or its real institutions.

## Easy — 30 samples

### Easy 01 — az_timeqa_easy_001

Source: `timeqa_easy_timebench.json`, record **116** (1-based). Type: `between_explicit`.

**Adapted question:** Spring Morning (painting) was owned by whom from 1918 to 1920?

**Adapted answer:** ["Rəşad Məmmədov and Co"]

**Adapted context:**

The painting was first exhibited in the second Impressionism exhibition of 1876 , and is now exhibited at the Baku Fine Arts Museum . - April 14 , 1876 , Səlim Qasımov and sale , , Baku , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Baku , lot 48 , to ( d . 1923 ) , Baku - 1918 , sold by to Rəşad Məmmədov and Co. , Baku and Ganja - 1920 , sold by Məmmədov to Fərid Həsənov ( b . 1861 - d . 1947 ) , Ganja - 1921 , sold by Həsənov to Quliyev Brothers Gallery , Shaki ; 1937 , shipped from Quliyev Gallery , Shaki to Quliyev Gallery , Ganja - March 8 , 1956 , sold by Quliyev Gallery to the BFAM for 45,000 rubles

<details><summary>Original record and replacements</summary>

```json
{
  "question": "La Japonaise (painting) was owned by whom from 1918 to 1920?",
  "context": "The painting was first exhibited in the second Impressionism exhibition of 1876 , and is now exhibited at the Museum of Fine Arts , Boston . - April 14 , 1876 , Monet and sale , , Paris , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Paris , lot 48 , to ( d . 1923 ) , Paris - 1918 , sold by to Paul Rosenberg and Co. , Paris and New York - 1920 , sold by Rosenberg to Philip Lehman ( b . 1861 - d . 1947 ) , New York - 1921 , sold by Lehman to Duveen Brothers , Inc. , London ; 1937 , shipped from Duveen , London to Duveen , New York - March 8 , 1956 , sold by Duveen to the MFA for $45,000",
  "answer": [
    "Paul Rosenberg and Co"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/La_Japonaise_(painting)#P127#0"
}
```

| Original | Replacement |
|---|---|
| La Japonaise (painting) | Spring Morning (painting) |
| Museum of Fine Arts , Boston | Baku Fine Arts Museum |
| Monet | Səlim Qasımov |
| Paris | Baku |
| Paul Rosenberg and Co | Rəşad Məmmədov and Co |
| New York | Ganja |
| Rosenberg | Məmmədov |
| Philip Lehman | Fərid Həsənov |
| Lehman | Həsənov |
| Duveen Brothers , Inc. | Quliyev Brothers Gallery |
| London | Shaki |
| Duveen | Quliyev Gallery |
| MFA | BFAM |
| for $45,000 | for 45,000 rubles |

</details>

### Easy 02 — az_timeqa_easy_002

Source: `timeqa_easy_timebench.json`, record **288** (1-based). Type: `between_explicit`.

**Adapted question:** Who owned Spring Morning (painting) from 1920 to 1921?

**Adapted answer:** ["Fərid Həsənov"]

**Adapted context:**

The painting was first exhibited in the second Impressionism exhibition of 1876 , and is now exhibited at the Baku Fine Arts Museum . - April 14 , 1876 , Səlim Qasımov and sale , , Baku , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Baku , lot 48 , to ( d . 1923 ) , Baku - 1918 , sold by to Rəşad Məmmədov and Co. , Baku and Ganja - 1920 , sold by Məmmədov to Fərid Həsənov ( b . 1861 - d . 1947 ) , Ganja - 1921 , sold by Həsənov to Quliyev Brothers Gallery , Shaki ; 1937 , shipped from Quliyev Gallery , Shaki to Quliyev Gallery , Ganja - March 8 , 1956 , sold by Quliyev Gallery to the BFAM for 45,000 rubles

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who owned La Japonaise (painting) from 1920 to 1921?",
  "context": "The painting was first exhibited in the second Impressionism exhibition of 1876 , and is now exhibited at the Museum of Fine Arts , Boston . - April 14 , 1876 , Monet and sale , , Paris , lot 37 - April 19 , 1877 , anonymous ( L. ) sale , , Paris , lot 48 , to ( d . 1923 ) , Paris - 1918 , sold by to Paul Rosenberg and Co. , Paris and New York - 1920 , sold by Rosenberg to Philip Lehman ( b . 1861 - d . 1947 ) , New York - 1921 , sold by Lehman to Duveen Brothers , Inc. , London ; 1937 , shipped from Duveen , London to Duveen , New York - March 8 , 1956 , sold by Duveen to the MFA for $45,000",
  "answer": [
    "Philip Lehman"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/La_Japonaise_(painting)#P127#1"
}
```

| Original | Replacement |
|---|---|
| La Japonaise (painting) | Spring Morning (painting) |
| Museum of Fine Arts , Boston | Baku Fine Arts Museum |
| Monet | Səlim Qasımov |
| Paris | Baku |
| Paul Rosenberg and Co | Rəşad Məmmədov and Co |
| New York | Ganja |
| Rosenberg | Məmmədov |
| Philip Lehman | Fərid Həsənov |
| Lehman | Həsənov |
| Duveen Brothers , Inc. | Quliyev Brothers Gallery |
| London | Shaki |
| Duveen | Quliyev Gallery |
| MFA | BFAM |
| for $45,000 | for 45,000 rubles |

</details>

### Easy 03 — az_timeqa_easy_003

Source: `timeqa_easy_timebench.json`, record **92** (1-based). Type: `between_explicit`.

**Adapted question:** Which employer did Rauf Əhmədov work for from 2004 to 2006?

**Adapted answer:** ["Baku Dawn"]

**Adapted context:**

Rauf Əhmədov ( ; born 16 April 1970 ) is an Azerbaijani football manager and a former player who played as a midfielder . He is the manager of Northern Regional League side Baku Stars . He most notably spent three and a half years with Baku Dawn in Azerbaijan , winning seven major trophies , which included two consecutive National Premier League titles . After starting as a manager with his main team Shamakhi Youth , Əhmədov moved in 2004 to Baku Dawn , spending two seasons with its junior side . In 2006 , Əhmədov signed for Shaki Hope , helping the club promote to the second level in his first season , followed by immediate relegation back . In 2008–09 , again as champion , he again led the side to division two .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which employer did Rui Vitória work for from 2004 to 2006?",
  "context": "Rui Carlos Pinho da Vitória ( ; born 16 April 1970 ) is a Portuguese football manager and a former player who played as a midfielder . He is the manager of Russian Premier League side Spartak Moscow . He most notably spent three and a half years with Benfica in Portugal , winning seven major trophies , which included two consecutive Primeira Liga titles . After starting as a manager with his main team Vilafranquense , Vitória moved in 2004 to Benfica , spending two seasons with its junior side . In 2006 , Vitória signed for Fátima , helping the club promote to the second level in his first season , followed by immediate relegation back . In 2008–09 , again as champion , he again led the side to division two .",
  "answer": [
    "Benfica"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Rui_Vitória#P108#1"
}
```

| Original | Replacement |
|---|---|
| Rui Vitória | Rauf Əhmədov |
| Rui Carlos Pinho da Vitória | Rauf Əhmədov |
| Portuguese | Azerbaijani |
| Russian Premier League | Northern Regional League |
| Spartak Moscow | Baku Stars |
| Benfica | Baku Dawn |
| Portugal | Azerbaijan |
| Primeira Liga | National Premier League |
| Vilafranquense | Shamakhi Youth |
| Vitória | Əhmədov |
| Fátima | Shaki Hope |

</details>

### Easy 04 — az_timeqa_easy_004

Source: `timeqa_easy_timebench.json`, record **171** (1-based). Type: `between_explicit`.

**Adapted question:** Who was the head of Youth Union from 1961 to 1963?

**Adapted answer:** ["İlqar Nəsirov"]

**Adapted context:**

The Azerbaijani Youth Union ( Young Union of Azerbaijan ) or AYU is the joint youth organisation of the two conservative Azerbaijani political parties , Progress Party and Unity Party . Membership is limited to individuals between 14 and 35 years of age . Azerbaijani Youth Union claims to be the largest political youth organization in Azerbaijan and the region with about 120,000 members . - Adil Səfərov ( 1947–1948 ) - Vüqar Rzayev ( 1948–1949 ) - Səbuhi İbrahimov ( 1949–1950 ) - Elman Cabbarov ( 1950–1955 ) - Fikrət Əkbərov ( 1955–1961 ) - İlqar Nəsirov ( 1961–1963 ) - Natiq Orucov ( 1963–1969 ) - Cavid Əliyev ( 1969–1973 ) - Ramil Məlikov ( 1973–1983 ) - Orxan Cəfərov ( 1983–1989 ) - Elnur Əsədov ( 1989–1994 ) - Murad Kərimov ( 1994–1998 ) - Aysel Rəhmanova ( 1998–2002 ) - Anar Vəliyev ( 2002–2014 ) - Sənan Nəcəfov ( 2014–2018 ) - Rəşad Qədirov ( since 2018 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the head of Young Union from 1961 to 1963?",
  "context": "The Junge Union Deutschlands ( Young Union of Germany ) or JU is the joint youth organisation of the two conservative German political parties , CDU and CSU . Membership is limited to individuals between 14 and 35 years of age . Junge Union claims to be the largest political youth organization in Germany and Europe with about 120,000 members . - Bruno Six ( 1947–1948 ) - Alfred Sagner ( 1948–1949 ) - Josef Dufhues ( 1949–1950 ) - Ernst Majonica ( 1950–1955 ) - Gerhard Stoltenberg ( 1955–1961 ) - Bert Even ( 1961–1963 ) - Egon Klepsch ( 1963–1969 ) - Jürgen Echternach ( 1969–1973 ) - Matthias Wissmann ( 1973–1983 ) - Christoph Böhr ( 1983–1989 ) - Hermann Gröhe ( 1989–1994 ) - Klaus Escher ( 1994–1998 ) - Hildegard Müller ( 1998–2002 ) - Philipp Mißfelder ( 2002–2014 ) - Paul Ziemiak ( 2014–2018 ) - Tilman Kuban ( since 2018 )",
  "answer": [
    "Bert Even"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Young_Union#P488#0"
}
```

| Original | Replacement |
|---|---|
| Young Union | Youth Union |
| Junge Union Deutschlands ( Young Union of Germany ) | Azerbaijani Youth Union ( Young Union of Azerbaijan ) |
| JU | AYU |
| German political parties | Azerbaijani political parties |
| CDU | Progress Party |
| CSU | Unity Party |
| Junge Union | Azerbaijani Youth Union |
| Germany and Europe | Azerbaijan and the region |
| Bruno Six | Adil Səfərov |
| Alfred Sagner | Vüqar Rzayev |
| Josef Dufhues | Səbuhi İbrahimov |
| Ernst Majonica | Elman Cabbarov |
| Gerhard Stoltenberg | Fikrət Əkbərov |
| Bert Even | İlqar Nəsirov |
| Egon Klepsch | Natiq Orucov |
| Jürgen Echternach | Cavid Əliyev |
| Matthias Wissmann | Ramil Məlikov |
| Christoph Böhr | Orxan Cəfərov |
| Hermann Gröhe | Elnur Əsədov |
| Klaus Escher | Murad Kərimov |
| Hildegard Müller | Aysel Rəhmanova |
| Philipp Mißfelder | Anar Vəliyev |
| Paul Ziemiak | Sənan Nəcəfov |
| Tilman Kuban | Rəşad Qədirov |

</details>

### Easy 05 — az_timeqa_easy_005

Source: `timeqa_easy_timebench.json`, record **251** (1-based). Type: `between_explicit`.

**Adapted question:** Who was the chair of Caspian Scientific Society from 1949 to 1951?

**Adapted answer:** ["Səlim Həmidov"]

**Adapted context:**

The Caspian Scientific Society ( or CSS ) is the national academy of Azerbaijan . It is headquartered in the city of Baku and was founded on May 3 , 1916 . Source : Caspian Scientific Society - 1916-1926 Ənvər Səlimov - 1926-1929 Əli Hacıyev - 1929-1931 Yusif Kazımov - 1931-1933 Musa Rəsulov - 1933-1935 Nəriman İsaqov - 1935-1937 Səlim Həmidov - 1937-1939 Tofiq Rəhimov - 1939-1941 Fərhad Məhərrəmov - 1941-1943 Nəriman İsaqov - 1943-1945 Kamran Şahbazov - 1945-1947 Zakir Əfəndiyev - 1947-1949 Nəriman İsaqov - 1949-1951 Səlim Həmidov - 1951-1965 Nəriman İsaqov - 1965–1967 Faiq Əlizadə - 1967–1981 Bəhram Xəlilov - 1981–1991 Aydın Mustafayev - 1991–1993 Rövşən Yusifov - 1993–2007 Samir Abbasov - 2007-2016 Vaqif Qurbanov - 2016– İntiqam Qənbərov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the chair of Brazilian Academy of Sciences from 1949 to 1951?",
  "context": "The Brazilian Academy of Sciences ( or ABC ) is the national academy of Brazil . It is headquartered in the city of Rio de Janeiro and was founded on May 3 , 1916 . Source : Brazilian Academy of Sciences - 1916-1926 Henrique Charles Morize - 1926-1929 Juliano Moreira - 1929-1931 Miguel Osório de Almeida - 1931-1933 Eusébio Paulo de Oliveira - 1933-1935 Arthur Alexandre Moses - 1935-1937 Álvaro Alberto da Mota e Silva - 1937-1939 Adalberto Menezes de Oliveira - 1939-1941 Inácio Manuel Azevedo do Amaral - 1941-1943 Arthur Alexandre Moses - 1943-1945 Cândido Firmino de Melo Leitão - 1945-1947 Mario Paulo de Brito - 1947-1949 Arthur Alexandre Moses - 1949-1951 Álvaro Alberto da Mota e Silva - 1951-1965 Arthur Alexandre Moses - 1965–1967 Carlos Chagas Filho - 1967–1981 Aristides Pacheco Leão - 1981–1991 Maurício Peixoto - 1991–1993 Oscar Sala - 1993–2007 Eduardo Krieger - 2007-2016 Jacob Palis Jr . - 2016– Luiz Davidovich",
  "answer": [
    "Álvaro Alberto da Mota e Silva"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Brazilian_Academy_of_Sciences#P488#1"
}
```

| Original | Replacement |
|---|---|
| Brazilian Academy of Sciences | Caspian Scientific Society |
| ABC | CSS |
| Brazil | Azerbaijan |
| Rio de Janeiro | Baku |
| Henrique Charles Morize | Ənvər Səlimov |
| Juliano Moreira | Əli Hacıyev |
| Miguel Osório de Almeida | Yusif Kazımov |
| Eusébio Paulo de Oliveira | Musa Rəsulov |
| Arthur Alexandre Moses | Nəriman İsaqov |
| Álvaro Alberto da Mota e Silva | Səlim Həmidov |
| Adalberto Menezes de Oliveira | Tofiq Rəhimov |
| Inácio Manuel Azevedo do Amaral | Fərhad Məhərrəmov |
| Cândido Firmino de Melo Leitão | Kamran Şahbazov |
| Mario Paulo de Brito | Zakir Əfəndiyev |
| Carlos Chagas Filho | Faiq Əlizadə |
| Aristides Pacheco Leão | Bəhram Xəlilov |
| Maurício Peixoto | Aydın Mustafayev |
| Oscar Sala | Rövşən Yusifov |
| Eduardo Krieger | Samir Abbasov |
| Jacob Palis Jr . | Vaqif Qurbanov |
| Luiz Davidovich | İntiqam Qənbərov |

</details>

### Easy 06 — az_timeqa_easy_006

Source: `timeqa_easy_timebench.json`, record **350** (1-based). Type: `between_explicit`.

**Adapted question:** Who was the head of Caspian Scientific Society from 1993 to 2007?

**Adapted answer:** ["Samir Abbasov"]

**Adapted context:**

The Caspian Scientific Society ( or CSS ) is the national academy of Azerbaijan . It is headquartered in the city of Baku and was founded on May 3 , 1916 . Source : Caspian Scientific Society - 1916-1926 Ənvər Səlimov - 1926-1929 Əli Hacıyev - 1929-1931 Yusif Kazımov - 1931-1933 Musa Rəsulov - 1933-1935 Nəriman İsaqov - 1935-1937 Səlim Həmidov - 1937-1939 Tofiq Rəhimov - 1939-1941 Fərhad Məhərrəmov - 1941-1943 Nəriman İsaqov - 1943-1945 Kamran Şahbazov - 1945-1947 Zakir Əfəndiyev - 1947-1949 Nəriman İsaqov - 1949-1951 Səlim Həmidov - 1951-1965 Nəriman İsaqov - 1965–1967 Faiq Əlizadə - 1967–1981 Bəhram Xəlilov - 1981–1991 Aydın Mustafayev - 1991–1993 Rövşən Yusifov - 1993–2007 Samir Abbasov - 2007-2016 Vaqif Qurbanov - 2016– İntiqam Qənbərov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the head of Brazilian Academy of Sciences from 1993 to 2007?",
  "context": "The Brazilian Academy of Sciences ( or ABC ) is the national academy of Brazil . It is headquartered in the city of Rio de Janeiro and was founded on May 3 , 1916 . Source : Brazilian Academy of Sciences - 1916-1926 Henrique Charles Morize - 1926-1929 Juliano Moreira - 1929-1931 Miguel Osório de Almeida - 1931-1933 Eusébio Paulo de Oliveira - 1933-1935 Arthur Alexandre Moses - 1935-1937 Álvaro Alberto da Mota e Silva - 1937-1939 Adalberto Menezes de Oliveira - 1939-1941 Inácio Manuel Azevedo do Amaral - 1941-1943 Arthur Alexandre Moses - 1943-1945 Cândido Firmino de Melo Leitão - 1945-1947 Mario Paulo de Brito - 1947-1949 Arthur Alexandre Moses - 1949-1951 Álvaro Alberto da Mota e Silva - 1951-1965 Arthur Alexandre Moses - 1965–1967 Carlos Chagas Filho - 1967–1981 Aristides Pacheco Leão - 1981–1991 Maurício Peixoto - 1991–1993 Oscar Sala - 1993–2007 Eduardo Krieger - 2007-2016 Jacob Palis Jr . - 2016– Luiz Davidovich",
  "answer": [
    "Eduardo Krieger"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Brazilian_Academy_of_Sciences#P488#7"
}
```

| Original | Replacement |
|---|---|
| Brazilian Academy of Sciences | Caspian Scientific Society |
| ABC | CSS |
| Brazil | Azerbaijan |
| Rio de Janeiro | Baku |
| Henrique Charles Morize | Ənvər Səlimov |
| Juliano Moreira | Əli Hacıyev |
| Miguel Osório de Almeida | Yusif Kazımov |
| Eusébio Paulo de Oliveira | Musa Rəsulov |
| Arthur Alexandre Moses | Nəriman İsaqov |
| Álvaro Alberto da Mota e Silva | Səlim Həmidov |
| Adalberto Menezes de Oliveira | Tofiq Rəhimov |
| Inácio Manuel Azevedo do Amaral | Fərhad Məhərrəmov |
| Cândido Firmino de Melo Leitão | Kamran Şahbazov |
| Mario Paulo de Brito | Zakir Əfəndiyev |
| Carlos Chagas Filho | Faiq Əlizadə |
| Aristides Pacheco Leão | Bəhram Xəlilov |
| Maurício Peixoto | Aydın Mustafayev |
| Oscar Sala | Rövşən Yusifov |
| Eduardo Krieger | Samir Abbasov |
| Jacob Palis Jr . | Vaqif Qurbanov |
| Luiz Davidovich | İntiqam Qənbərov |

</details>

### Easy 07 — az_timeqa_easy_007

Source: `timeqa_easy_timebench.json`, record **368** (1-based). Type: `between_explicit`.

**Adapted question:** Who was the head of Caspian Scientific Society from 1965 to 1967?

**Adapted answer:** ["Faiq Əlizadə"]

**Adapted context:**

The Caspian Scientific Society ( or CSS ) is the national academy of Azerbaijan . It is headquartered in the city of Baku and was founded on May 3 , 1916 . Source : Caspian Scientific Society - 1916-1926 Ənvər Səlimov - 1926-1929 Əli Hacıyev - 1929-1931 Yusif Kazımov - 1931-1933 Musa Rəsulov - 1933-1935 Nəriman İsaqov - 1935-1937 Səlim Həmidov - 1937-1939 Tofiq Rəhimov - 1939-1941 Fərhad Məhərrəmov - 1941-1943 Nəriman İsaqov - 1943-1945 Kamran Şahbazov - 1945-1947 Zakir Əfəndiyev - 1947-1949 Nəriman İsaqov - 1949-1951 Səlim Həmidov - 1951-1965 Nəriman İsaqov - 1965–1967 Faiq Əlizadə - 1967–1981 Bəhram Xəlilov - 1981–1991 Aydın Mustafayev - 1991–1993 Rövşən Yusifov - 1993–2007 Samir Abbasov - 2007-2016 Vaqif Qurbanov - 2016– İntiqam Qənbərov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the head of Brazilian Academy of Sciences from 1965 to 1967?",
  "context": "The Brazilian Academy of Sciences ( or ABC ) is the national academy of Brazil . It is headquartered in the city of Rio de Janeiro and was founded on May 3 , 1916 . Source : Brazilian Academy of Sciences - 1916-1926 Henrique Charles Morize - 1926-1929 Juliano Moreira - 1929-1931 Miguel Osório de Almeida - 1931-1933 Eusébio Paulo de Oliveira - 1933-1935 Arthur Alexandre Moses - 1935-1937 Álvaro Alberto da Mota e Silva - 1937-1939 Adalberto Menezes de Oliveira - 1939-1941 Inácio Manuel Azevedo do Amaral - 1941-1943 Arthur Alexandre Moses - 1943-1945 Cândido Firmino de Melo Leitão - 1945-1947 Mario Paulo de Brito - 1947-1949 Arthur Alexandre Moses - 1949-1951 Álvaro Alberto da Mota e Silva - 1951-1965 Arthur Alexandre Moses - 1965–1967 Carlos Chagas Filho - 1967–1981 Aristides Pacheco Leão - 1981–1991 Maurício Peixoto - 1991–1993 Oscar Sala - 1993–2007 Eduardo Krieger - 2007-2016 Jacob Palis Jr . - 2016– Luiz Davidovich",
  "answer": [
    "Carlos Chagas Filho"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Brazilian_Academy_of_Sciences#P488#3"
}
```

| Original | Replacement |
|---|---|
| Brazilian Academy of Sciences | Caspian Scientific Society |
| ABC | CSS |
| Brazil | Azerbaijan |
| Rio de Janeiro | Baku |
| Henrique Charles Morize | Ənvər Səlimov |
| Juliano Moreira | Əli Hacıyev |
| Miguel Osório de Almeida | Yusif Kazımov |
| Eusébio Paulo de Oliveira | Musa Rəsulov |
| Arthur Alexandre Moses | Nəriman İsaqov |
| Álvaro Alberto da Mota e Silva | Səlim Həmidov |
| Adalberto Menezes de Oliveira | Tofiq Rəhimov |
| Inácio Manuel Azevedo do Amaral | Fərhad Məhərrəmov |
| Cândido Firmino de Melo Leitão | Kamran Şahbazov |
| Mario Paulo de Brito | Zakir Əfəndiyev |
| Carlos Chagas Filho | Faiq Əlizadə |
| Aristides Pacheco Leão | Bəhram Xəlilov |
| Maurício Peixoto | Aydın Mustafayev |
| Oscar Sala | Rövşən Yusifov |
| Eduardo Krieger | Samir Abbasov |
| Jacob Palis Jr . | Vaqif Qurbanov |
| Luiz Davidovich | İntiqam Qənbərov |

</details>

### Easy 08 — az_timeqa_easy_008

Source: `timeqa_easy_timebench.json`, record **398** (1-based). Type: `between_explicit`.

**Adapted question:** Who was the chair of Caspian Scientific Society from 1991 to 1993?

**Adapted answer:** ["Rövşən Yusifov"]

**Adapted context:**

The Caspian Scientific Society ( or CSS ) is the national academy of Azerbaijan . It is headquartered in the city of Baku and was founded on May 3 , 1916 . Source : Caspian Scientific Society - 1916-1926 Ənvər Səlimov - 1926-1929 Əli Hacıyev - 1929-1931 Yusif Kazımov - 1931-1933 Musa Rəsulov - 1933-1935 Nəriman İsaqov - 1935-1937 Səlim Həmidov - 1937-1939 Tofiq Rəhimov - 1939-1941 Fərhad Məhərrəmov - 1941-1943 Nəriman İsaqov - 1943-1945 Kamran Şahbazov - 1945-1947 Zakir Əfəndiyev - 1947-1949 Nəriman İsaqov - 1949-1951 Səlim Həmidov - 1951-1965 Nəriman İsaqov - 1965–1967 Faiq Əlizadə - 1967–1981 Bəhram Xəlilov - 1981–1991 Aydın Mustafayev - 1991–1993 Rövşən Yusifov - 1993–2007 Samir Abbasov - 2007-2016 Vaqif Qurbanov - 2016– İntiqam Qənbərov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the chair of Brazilian Academy of Sciences from 1991 to 1993?",
  "context": "The Brazilian Academy of Sciences ( or ABC ) is the national academy of Brazil . It is headquartered in the city of Rio de Janeiro and was founded on May 3 , 1916 . Source : Brazilian Academy of Sciences - 1916-1926 Henrique Charles Morize - 1926-1929 Juliano Moreira - 1929-1931 Miguel Osório de Almeida - 1931-1933 Eusébio Paulo de Oliveira - 1933-1935 Arthur Alexandre Moses - 1935-1937 Álvaro Alberto da Mota e Silva - 1937-1939 Adalberto Menezes de Oliveira - 1939-1941 Inácio Manuel Azevedo do Amaral - 1941-1943 Arthur Alexandre Moses - 1943-1945 Cândido Firmino de Melo Leitão - 1945-1947 Mario Paulo de Brito - 1947-1949 Arthur Alexandre Moses - 1949-1951 Álvaro Alberto da Mota e Silva - 1951-1965 Arthur Alexandre Moses - 1965–1967 Carlos Chagas Filho - 1967–1981 Aristides Pacheco Leão - 1981–1991 Maurício Peixoto - 1991–1993 Oscar Sala - 1993–2007 Eduardo Krieger - 2007-2016 Jacob Palis Jr . - 2016– Luiz Davidovich",
  "answer": [
    "Oscar Sala"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Brazilian_Academy_of_Sciences#P488#6"
}
```

| Original | Replacement |
|---|---|
| Brazilian Academy of Sciences | Caspian Scientific Society |
| ABC | CSS |
| Brazil | Azerbaijan |
| Rio de Janeiro | Baku |
| Henrique Charles Morize | Ənvər Səlimov |
| Juliano Moreira | Əli Hacıyev |
| Miguel Osório de Almeida | Yusif Kazımov |
| Eusébio Paulo de Oliveira | Musa Rəsulov |
| Arthur Alexandre Moses | Nəriman İsaqov |
| Álvaro Alberto da Mota e Silva | Səlim Həmidov |
| Adalberto Menezes de Oliveira | Tofiq Rəhimov |
| Inácio Manuel Azevedo do Amaral | Fərhad Məhərrəmov |
| Cândido Firmino de Melo Leitão | Kamran Şahbazov |
| Mario Paulo de Brito | Zakir Əfəndiyev |
| Carlos Chagas Filho | Faiq Əlizadə |
| Aristides Pacheco Leão | Bəhram Xəlilov |
| Maurício Peixoto | Aydın Mustafayev |
| Oscar Sala | Rövşən Yusifov |
| Eduardo Krieger | Samir Abbasov |
| Jacob Palis Jr . | Vaqif Qurbanov |
| Luiz Davidovich | İntiqam Qənbərov |

</details>

### Easy 09 — az_timeqa_easy_009

Source: `timeqa_easy_timebench.json`, record **486** (1-based). Type: `between_explicit`.

**Adapted question:** Who was the head of Caspian Scientific Society from 1981 to 1991?

**Adapted answer:** ["Aydın Mustafayev"]

**Adapted context:**

The Caspian Scientific Society ( or CSS ) is the national academy of Azerbaijan . It is headquartered in the city of Baku and was founded on May 3 , 1916 . Source : Caspian Scientific Society - 1916-1926 Ənvər Səlimov - 1926-1929 Əli Hacıyev - 1929-1931 Yusif Kazımov - 1931-1933 Musa Rəsulov - 1933-1935 Nəriman İsaqov - 1935-1937 Səlim Həmidov - 1937-1939 Tofiq Rəhimov - 1939-1941 Fərhad Məhərrəmov - 1941-1943 Nəriman İsaqov - 1943-1945 Kamran Şahbazov - 1945-1947 Zakir Əfəndiyev - 1947-1949 Nəriman İsaqov - 1949-1951 Səlim Həmidov - 1951-1965 Nəriman İsaqov - 1965–1967 Faiq Əlizadə - 1967–1981 Bəhram Xəlilov - 1981–1991 Aydın Mustafayev - 1991–1993 Rövşən Yusifov - 1993–2007 Samir Abbasov - 2007-2016 Vaqif Qurbanov - 2016– İntiqam Qənbərov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the head of Brazilian Academy of Sciences from 1981 to 1991?",
  "context": "The Brazilian Academy of Sciences ( or ABC ) is the national academy of Brazil . It is headquartered in the city of Rio de Janeiro and was founded on May 3 , 1916 . Source : Brazilian Academy of Sciences - 1916-1926 Henrique Charles Morize - 1926-1929 Juliano Moreira - 1929-1931 Miguel Osório de Almeida - 1931-1933 Eusébio Paulo de Oliveira - 1933-1935 Arthur Alexandre Moses - 1935-1937 Álvaro Alberto da Mota e Silva - 1937-1939 Adalberto Menezes de Oliveira - 1939-1941 Inácio Manuel Azevedo do Amaral - 1941-1943 Arthur Alexandre Moses - 1943-1945 Cândido Firmino de Melo Leitão - 1945-1947 Mario Paulo de Brito - 1947-1949 Arthur Alexandre Moses - 1949-1951 Álvaro Alberto da Mota e Silva - 1951-1965 Arthur Alexandre Moses - 1965–1967 Carlos Chagas Filho - 1967–1981 Aristides Pacheco Leão - 1981–1991 Maurício Peixoto - 1991–1993 Oscar Sala - 1993–2007 Eduardo Krieger - 2007-2016 Jacob Palis Jr . - 2016– Luiz Davidovich",
  "answer": [
    "Maurício Peixoto"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Brazilian_Academy_of_Sciences#P488#5"
}
```

| Original | Replacement |
|---|---|
| Brazilian Academy of Sciences | Caspian Scientific Society |
| ABC | CSS |
| Brazil | Azerbaijan |
| Rio de Janeiro | Baku |
| Henrique Charles Morize | Ənvər Səlimov |
| Juliano Moreira | Əli Hacıyev |
| Miguel Osório de Almeida | Yusif Kazımov |
| Eusébio Paulo de Oliveira | Musa Rəsulov |
| Arthur Alexandre Moses | Nəriman İsaqov |
| Álvaro Alberto da Mota e Silva | Səlim Həmidov |
| Adalberto Menezes de Oliveira | Tofiq Rəhimov |
| Inácio Manuel Azevedo do Amaral | Fərhad Məhərrəmov |
| Cândido Firmino de Melo Leitão | Kamran Şahbazov |
| Mario Paulo de Brito | Zakir Əfəndiyev |
| Carlos Chagas Filho | Faiq Əlizadə |
| Aristides Pacheco Leão | Bəhram Xəlilov |
| Maurício Peixoto | Aydın Mustafayev |
| Oscar Sala | Rövşən Yusifov |
| Eduardo Krieger | Samir Abbasov |
| Jacob Palis Jr . | Vaqif Qurbanov |
| Luiz Davidovich | İntiqam Qənbərov |

</details>

### Easy 10 — az_timeqa_easy_010

Source: `timeqa_easy_timebench.json`, record **61** (1-based). Type: `between_explicit`.

**Adapted question:** Who commanded First Aviation Group from 1973 to 1977?

**Adapted answer:** ["Kənan Səfərov"]

**Adapted context:**

First Aviation Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Caspian Regional Air Service . The First Aviation Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Regional Defence Service and therefore nicknamed Komandirin dayağı ( Commanders support ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bəşir Ağayev - 1942-07-01 – 1952-03-31 : Cəmil Həsənli - 1952-04-01 – 1964-03-31 : Elşad Qasımov - 1964-04-01 – 1966-09-30 : Fərman Quliyev - 1966-10-01 – 1973-03-31 : İmran Məmmədli - 1973-04-04 – 1977-06-30 : Kənan Səfərov - 1977-07-01 – 1980-09-30 : Ramin Rzayev - 1980-10-01 – 1983-09-30 : Tahir Cabbarov - 1983-10-01 – 1990-09-30 : Vidadi Nəsirov - 1990-10-01 – 1994-10-01 : Zaur Əkbərov - 1994-10-01 – 1995-06-30 : Ədalət Orucov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who commanded First Air Group from 1973 to 1977?",
  "context": "First Air Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Swedish Air Force . The First Air Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Swedish Armed Forces and therefore nicknamed ÖB:s klubba ( Supreme Commanders club ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bengt Nordenskiöld - 1942-07-01 – 1952-03-31 : Paulus af Uhr - 1952-04-01 – 1964-03-31 : Björn Bjuggren - 1964-04-01 – 1966-09-30 : Stig Norén - 1966-10-01 – 1973-03-31 : Gösta Odqvist - 1973-04-04 – 1977-06-30 : Bengt Rosenius - 1977-07-01 – 1980-09-30 : Sven-Olof Olson - 1980-10-01 – 1983-09-30 : Erik Nygren - 1983-10-01 – 1990-09-30 : Bertil Nordström - 1990-10-01 – 1994-10-01 : Bert Stenfeldt - 1994-10-01 – 1995-06-30 : Christer Salsing",
  "answer": [
    "Bengt Rosenius"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/First_Air_Group#P4791#5"
}
```

| Original | Replacement |
|---|---|
| First Air Group | First Aviation Group |
| Swedish Air Force | Caspian Regional Air Service |
| Swedish Armed Forces | Regional Defence Service |
| ÖB:s klubba | Komandirin dayağı |
| Supreme Commanders club | Commanders support |
| Bengt Nordenskiöld | Bəşir Ağayev |
| Paulus af Uhr | Cəmil Həsənli |
| Björn Bjuggren | Elşad Qasımov |
| Stig Norén | Fərman Quliyev |
| Gösta Odqvist | İmran Məmmədli |
| Bengt Rosenius | Kənan Səfərov |
| Sven-Olof Olson | Ramin Rzayev |
| Erik Nygren | Tahir Cabbarov |
| Bertil Nordström | Vidadi Nəsirov |
| Bert Stenfeldt | Zaur Əkbərov |
| Christer Salsing | Ədalət Orucov |

</details>

### Easy 11 — az_timeqa_easy_011

Source: `timeqa_easy_timebench.json`, record **105** (1-based). Type: `between_explicit`.

**Adapted question:** Who was the commander of First Aviation Group from 1952 to 1964?

**Adapted answer:** ["Elşad Qasımov"]

**Adapted context:**

First Aviation Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Caspian Regional Air Service . The First Aviation Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Regional Defence Service and therefore nicknamed Komandirin dayağı ( Commanders support ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bəşir Ağayev - 1942-07-01 – 1952-03-31 : Cəmil Həsənli - 1952-04-01 – 1964-03-31 : Elşad Qasımov - 1964-04-01 – 1966-09-30 : Fərman Quliyev - 1966-10-01 – 1973-03-31 : İmran Məmmədli - 1973-04-04 – 1977-06-30 : Kənan Səfərov - 1977-07-01 – 1980-09-30 : Ramin Rzayev - 1980-10-01 – 1983-09-30 : Tahir Cabbarov - 1983-10-01 – 1990-09-30 : Vidadi Nəsirov - 1990-10-01 – 1994-10-01 : Zaur Əkbərov - 1994-10-01 – 1995-06-30 : Ədalət Orucov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the commander of First Air Group from 1952 to 1964?",
  "context": "First Air Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Swedish Air Force . The First Air Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Swedish Armed Forces and therefore nicknamed ÖB:s klubba ( Supreme Commanders club ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bengt Nordenskiöld - 1942-07-01 – 1952-03-31 : Paulus af Uhr - 1952-04-01 – 1964-03-31 : Björn Bjuggren - 1964-04-01 – 1966-09-30 : Stig Norén - 1966-10-01 – 1973-03-31 : Gösta Odqvist - 1973-04-04 – 1977-06-30 : Bengt Rosenius - 1977-07-01 – 1980-09-30 : Sven-Olof Olson - 1980-10-01 – 1983-09-30 : Erik Nygren - 1983-10-01 – 1990-09-30 : Bertil Nordström - 1990-10-01 – 1994-10-01 : Bert Stenfeldt - 1994-10-01 – 1995-06-30 : Christer Salsing",
  "answer": [
    "Björn Bjuggren"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/First_Air_Group#P4791#2"
}
```

| Original | Replacement |
|---|---|
| First Air Group | First Aviation Group |
| Swedish Air Force | Caspian Regional Air Service |
| Swedish Armed Forces | Regional Defence Service |
| ÖB:s klubba | Komandirin dayağı |
| Supreme Commanders club | Commanders support |
| Bengt Nordenskiöld | Bəşir Ağayev |
| Paulus af Uhr | Cəmil Həsənli |
| Björn Bjuggren | Elşad Qasımov |
| Stig Norén | Fərman Quliyev |
| Gösta Odqvist | İmran Məmmədli |
| Bengt Rosenius | Kənan Səfərov |
| Sven-Olof Olson | Ramin Rzayev |
| Erik Nygren | Tahir Cabbarov |
| Bertil Nordström | Vidadi Nəsirov |
| Bert Stenfeldt | Zaur Əkbərov |
| Christer Salsing | Ədalət Orucov |

</details>

### Easy 12 — az_timeqa_easy_012

Source: `timeqa_easy_timebench.json`, record **308** (1-based). Type: `between_explicit`.

**Adapted question:** Who was the commander of First Aviation Group from 1964 to 1966?

**Adapted answer:** ["Fərman Quliyev"]

**Adapted context:**

First Aviation Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Caspian Regional Air Service . The First Aviation Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Regional Defence Service and therefore nicknamed Komandirin dayağı ( Commanders support ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bəşir Ağayev - 1942-07-01 – 1952-03-31 : Cəmil Həsənli - 1952-04-01 – 1964-03-31 : Elşad Qasımov - 1964-04-01 – 1966-09-30 : Fərman Quliyev - 1966-10-01 – 1973-03-31 : İmran Məmmədli - 1973-04-04 – 1977-06-30 : Kənan Səfərov - 1977-07-01 – 1980-09-30 : Ramin Rzayev - 1980-10-01 – 1983-09-30 : Tahir Cabbarov - 1983-10-01 – 1990-09-30 : Vidadi Nəsirov - 1990-10-01 – 1994-10-01 : Zaur Əkbərov - 1994-10-01 – 1995-06-30 : Ədalət Orucov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the commander of First Air Group from 1964 to 1966?",
  "context": "First Air Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Swedish Air Force . The First Air Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Swedish Armed Forces and therefore nicknamed ÖB:s klubba ( Supreme Commanders club ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bengt Nordenskiöld - 1942-07-01 – 1952-03-31 : Paulus af Uhr - 1952-04-01 – 1964-03-31 : Björn Bjuggren - 1964-04-01 – 1966-09-30 : Stig Norén - 1966-10-01 – 1973-03-31 : Gösta Odqvist - 1973-04-04 – 1977-06-30 : Bengt Rosenius - 1977-07-01 – 1980-09-30 : Sven-Olof Olson - 1980-10-01 – 1983-09-30 : Erik Nygren - 1983-10-01 – 1990-09-30 : Bertil Nordström - 1990-10-01 – 1994-10-01 : Bert Stenfeldt - 1994-10-01 – 1995-06-30 : Christer Salsing",
  "answer": [
    "Stig Norén"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/First_Air_Group#P4791#3"
}
```

| Original | Replacement |
|---|---|
| First Air Group | First Aviation Group |
| Swedish Air Force | Caspian Regional Air Service |
| Swedish Armed Forces | Regional Defence Service |
| ÖB:s klubba | Komandirin dayağı |
| Supreme Commanders club | Commanders support |
| Bengt Nordenskiöld | Bəşir Ağayev |
| Paulus af Uhr | Cəmil Həsənli |
| Björn Bjuggren | Elşad Qasımov |
| Stig Norén | Fərman Quliyev |
| Gösta Odqvist | İmran Məmmədli |
| Bengt Rosenius | Kənan Səfərov |
| Sven-Olof Olson | Ramin Rzayev |
| Erik Nygren | Tahir Cabbarov |
| Bertil Nordström | Vidadi Nəsirov |
| Bert Stenfeldt | Zaur Əkbərov |
| Christer Salsing | Ədalət Orucov |

</details>

### Easy 13 — az_timeqa_easy_013

Source: `timeqa_easy_timebench.json`, record **46** (1-based). Type: `between_explicit`.

**Adapted question:** Who was the director or manager of Caspian Policy Planning Centre from 1999 to 2002?

**Adapted answer:** ["İlham Nəcəfov"]

**Adapted context:**

The Caspian Policy Planning Centre ( Caspian Policy Planning Centre , or CPPC , formerly known as Regional Analysis and Planning Centre ( or Centre for Analysis and Planning ) , and then as Foresight Department ( or Directorate for Foresight ) is a think tank within the Regional External Relations Department , tasked with making strategic recommendations to the External Relations Director and ensuring a regional presence in national and international debates and institutions . It is the local counterpart to the Regional Councils Policy Planning Office It is currently headed by diplomat Əliyar Əhmədov , who was appointed by External Relations Director Şahin Həsənov in July 2019 . The CPPC has a history of renowned directors , either academics or career diplomats . - Akif İsmayılov ( 1974-1978 ) - Bəxtiyar Rzayev ( 1979-1984 ) - Ceyhun Qasımov ( 1984-1989 ) - Eldar Quliyev ( 1989-1993 ) - Fərid Rəhmanov ( 1993-1995 ) - Hafiz Cabbarov ( 1995-1999 , 2002-2004 ) - İlham Nəcəfov ( 1999-2002 ) - Namiq Səlimov ( 2005-2010 ) - Lalə Vəliyeva ( 2010 ) - Rafiq İbrahimov ( 2010-2013 ) - Sərxan Əsədov ( 2013-2019 ) - Əliyar Əhmədov ( 2019- )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the director or manager of Policy Planning Staff (France) from 1999 to 2002?",
  "context": "The Centre for Analysis , Planning and Strategy ( Centre d’analyse , de prévision et de stratégie , or CAPS , formerly known as Centre danalyse et de prévision ( or Centre for Analysis and Planning ) , and then as Direction de la prospective ( or Directorate for Foresight ) is a think tank within the French Ministry of Foreign Affairs , tasked with making strategic recommendations to the Foreign Minister and ensuring a French presence in European and international debates and institutions . It is the French counterpart to the US State Department’s Policy Planning Staff It is currently headed by diplomat Manuel Lafont Rapnouil , who was appointed by Foreign Minister Jean-Yves Le Drian in July 2019 . The CAPS has a history of renowned directors , either academics or career diplomats . - Thierry de Montbrial ( 1974-1978 ) - Jean-Louis Gergorin ( 1979-1984 ) - Philippe Coste ( 1984-1989 ) - Jean-Marie Guéhenno ( 1989-1993 ) - Bruno Racine ( 1993-1995 ) - Gilles Andréani ( 1995-1999 , 2002-2004 ) - Michel Foucher ( 1999-2002 ) - Pierre Lévy ( 2005-2010 ) - Marie Mendras ( 2010 ) - Joseph Maïla ( 2010-2013 ) - Justin Vaïsse ( 2013-2019 ) - Manuel Lafont Rapnouil ( 2019- )",
  "answer": [
    "Michel Foucher"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Policy_Planning_Staff_(France)#P1037#6"
}
```

| Original | Replacement |
|---|---|
| Policy Planning Staff (France) | Caspian Policy Planning Centre |
| Centre for Analysis , Planning and Strategy | Caspian Policy Planning Centre |
| Centre d’analyse , de prévision et de stratégie | Caspian Policy Planning Centre |
| CAPS | CPPC |
| Centre danalyse et de prévision | Regional Analysis and Planning Centre |
| Direction de la prospective | Foresight Department |
| French Ministry of Foreign Affairs | Regional External Relations Department |
| Foreign Minister | External Relations Director |
| French presence in European and international debates and institutions | regional presence in national and international debates and institutions |
| French counterpart | local counterpart |
| US State Department’s Policy Planning Staff | Regional Councils Policy Planning Office |
| Manuel Lafont Rapnouil | Əliyar Əhmədov |
| Jean-Yves Le Drian | Şahin Həsənov |
| Thierry de Montbrial | Akif İsmayılov |
| Jean-Louis Gergorin | Bəxtiyar Rzayev |
| Philippe Coste | Ceyhun Qasımov |
| Jean-Marie Guéhenno | Eldar Quliyev |
| Bruno Racine | Fərid Rəhmanov |
| Gilles Andréani | Hafiz Cabbarov |
| Michel Foucher | İlham Nəcəfov |
| Pierre Lévy | Namiq Səlimov |
| Marie Mendras | Lalə Vəliyeva |
| Joseph Maïla | Rafiq İbrahimov |
| Justin Vaïsse | Sərxan Əsədov |

</details>

### Easy 14 — az_timeqa_easy_014

Source: `timeqa_easy_timebench.json`, record **151** (1-based). Type: `between_explicit`.

**Adapted question:** Who was the director or manager of Caspian Policy Planning Centre from 1979 to 1984?

**Adapted answer:** ["Bəxtiyar Rzayev"]

**Adapted context:**

The Caspian Policy Planning Centre ( Caspian Policy Planning Centre , or CPPC , formerly known as Regional Analysis and Planning Centre ( or Centre for Analysis and Planning ) , and then as Foresight Department ( or Directorate for Foresight ) is a think tank within the Regional External Relations Department , tasked with making strategic recommendations to the External Relations Director and ensuring a regional presence in national and international debates and institutions . It is the local counterpart to the Regional Councils Policy Planning Office It is currently headed by diplomat Əliyar Əhmədov , who was appointed by External Relations Director Şahin Həsənov in July 2019 . The CPPC has a history of renowned directors , either academics or career diplomats . - Akif İsmayılov ( 1974-1978 ) - Bəxtiyar Rzayev ( 1979-1984 ) - Ceyhun Qasımov ( 1984-1989 ) - Eldar Quliyev ( 1989-1993 ) - Fərid Rəhmanov ( 1993-1995 ) - Hafiz Cabbarov ( 1995-1999 , 2002-2004 ) - İlham Nəcəfov ( 1999-2002 ) - Namiq Səlimov ( 2005-2010 ) - Lalə Vəliyeva ( 2010 ) - Rafiq İbrahimov ( 2010-2013 ) - Sərxan Əsədov ( 2013-2019 ) - Əliyar Əhmədov ( 2019- )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the director or manager of Policy Planning Staff (France) from 1979 to 1984?",
  "context": "The Centre for Analysis , Planning and Strategy ( Centre d’analyse , de prévision et de stratégie , or CAPS , formerly known as Centre danalyse et de prévision ( or Centre for Analysis and Planning ) , and then as Direction de la prospective ( or Directorate for Foresight ) is a think tank within the French Ministry of Foreign Affairs , tasked with making strategic recommendations to the Foreign Minister and ensuring a French presence in European and international debates and institutions . It is the French counterpart to the US State Department’s Policy Planning Staff It is currently headed by diplomat Manuel Lafont Rapnouil , who was appointed by Foreign Minister Jean-Yves Le Drian in July 2019 . The CAPS has a history of renowned directors , either academics or career diplomats . - Thierry de Montbrial ( 1974-1978 ) - Jean-Louis Gergorin ( 1979-1984 ) - Philippe Coste ( 1984-1989 ) - Jean-Marie Guéhenno ( 1989-1993 ) - Bruno Racine ( 1993-1995 ) - Gilles Andréani ( 1995-1999 , 2002-2004 ) - Michel Foucher ( 1999-2002 ) - Pierre Lévy ( 2005-2010 ) - Marie Mendras ( 2010 ) - Joseph Maïla ( 2010-2013 ) - Justin Vaïsse ( 2013-2019 ) - Manuel Lafont Rapnouil ( 2019- )",
  "answer": [
    "Jean-Louis Gergorin"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Policy_Planning_Staff_(France)#P1037#1"
}
```

| Original | Replacement |
|---|---|
| Policy Planning Staff (France) | Caspian Policy Planning Centre |
| Centre for Analysis , Planning and Strategy | Caspian Policy Planning Centre |
| Centre d’analyse , de prévision et de stratégie | Caspian Policy Planning Centre |
| CAPS | CPPC |
| Centre danalyse et de prévision | Regional Analysis and Planning Centre |
| Direction de la prospective | Foresight Department |
| French Ministry of Foreign Affairs | Regional External Relations Department |
| Foreign Minister | External Relations Director |
| French presence in European and international debates and institutions | regional presence in national and international debates and institutions |
| French counterpart | local counterpart |
| US State Department’s Policy Planning Staff | Regional Councils Policy Planning Office |
| Manuel Lafont Rapnouil | Əliyar Əhmədov |
| Jean-Yves Le Drian | Şahin Həsənov |
| Thierry de Montbrial | Akif İsmayılov |
| Jean-Louis Gergorin | Bəxtiyar Rzayev |
| Philippe Coste | Ceyhun Qasımov |
| Jean-Marie Guéhenno | Eldar Quliyev |
| Bruno Racine | Fərid Rəhmanov |
| Gilles Andréani | Hafiz Cabbarov |
| Michel Foucher | İlham Nəcəfov |
| Pierre Lévy | Namiq Səlimov |
| Marie Mendras | Lalə Vəliyeva |
| Joseph Maïla | Rafiq İbrahimov |
| Justin Vaïsse | Sərxan Əsədov |

</details>

### Easy 15 — az_timeqa_easy_015

Source: `timeqa_easy_timebench.json`, record **295** (1-based). Type: `between_explicit`.

**Adapted question:** Caspian Policy Planning Centre was managed or directed by whom from 1984 to 1989?

**Adapted answer:** ["Ceyhun Qasımov"]

**Adapted context:**

The Caspian Policy Planning Centre ( Caspian Policy Planning Centre , or CPPC , formerly known as Regional Analysis and Planning Centre ( or Centre for Analysis and Planning ) , and then as Foresight Department ( or Directorate for Foresight ) is a think tank within the Regional External Relations Department , tasked with making strategic recommendations to the External Relations Director and ensuring a regional presence in national and international debates and institutions . It is the local counterpart to the Regional Councils Policy Planning Office It is currently headed by diplomat Əliyar Əhmədov , who was appointed by External Relations Director Şahin Həsənov in July 2019 . The CPPC has a history of renowned directors , either academics or career diplomats . - Akif İsmayılov ( 1974-1978 ) - Bəxtiyar Rzayev ( 1979-1984 ) - Ceyhun Qasımov ( 1984-1989 ) - Eldar Quliyev ( 1989-1993 ) - Fərid Rəhmanov ( 1993-1995 ) - Hafiz Cabbarov ( 1995-1999 , 2002-2004 ) - İlham Nəcəfov ( 1999-2002 ) - Namiq Səlimov ( 2005-2010 ) - Lalə Vəliyeva ( 2010 ) - Rafiq İbrahimov ( 2010-2013 ) - Sərxan Əsədov ( 2013-2019 ) - Əliyar Əhmədov ( 2019- )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Policy Planning Staff (France) was managed or directed by whom from 1984 to 1989?",
  "context": "The Centre for Analysis , Planning and Strategy ( Centre d’analyse , de prévision et de stratégie , or CAPS , formerly known as Centre danalyse et de prévision ( or Centre for Analysis and Planning ) , and then as Direction de la prospective ( or Directorate for Foresight ) is a think tank within the French Ministry of Foreign Affairs , tasked with making strategic recommendations to the Foreign Minister and ensuring a French presence in European and international debates and institutions . It is the French counterpart to the US State Department’s Policy Planning Staff It is currently headed by diplomat Manuel Lafont Rapnouil , who was appointed by Foreign Minister Jean-Yves Le Drian in July 2019 . The CAPS has a history of renowned directors , either academics or career diplomats . - Thierry de Montbrial ( 1974-1978 ) - Jean-Louis Gergorin ( 1979-1984 ) - Philippe Coste ( 1984-1989 ) - Jean-Marie Guéhenno ( 1989-1993 ) - Bruno Racine ( 1993-1995 ) - Gilles Andréani ( 1995-1999 , 2002-2004 ) - Michel Foucher ( 1999-2002 ) - Pierre Lévy ( 2005-2010 ) - Marie Mendras ( 2010 ) - Joseph Maïla ( 2010-2013 ) - Justin Vaïsse ( 2013-2019 ) - Manuel Lafont Rapnouil ( 2019- )",
  "answer": [
    "Philippe Coste"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Policy_Planning_Staff_(France)#P1037#2"
}
```

| Original | Replacement |
|---|---|
| Policy Planning Staff (France) | Caspian Policy Planning Centre |
| Centre for Analysis , Planning and Strategy | Caspian Policy Planning Centre |
| Centre d’analyse , de prévision et de stratégie | Caspian Policy Planning Centre |
| CAPS | CPPC |
| Centre danalyse et de prévision | Regional Analysis and Planning Centre |
| Direction de la prospective | Foresight Department |
| French Ministry of Foreign Affairs | Regional External Relations Department |
| Foreign Minister | External Relations Director |
| French presence in European and international debates and institutions | regional presence in national and international debates and institutions |
| French counterpart | local counterpart |
| US State Department’s Policy Planning Staff | Regional Councils Policy Planning Office |
| Manuel Lafont Rapnouil | Əliyar Əhmədov |
| Jean-Yves Le Drian | Şahin Həsənov |
| Thierry de Montbrial | Akif İsmayılov |
| Jean-Louis Gergorin | Bəxtiyar Rzayev |
| Philippe Coste | Ceyhun Qasımov |
| Jean-Marie Guéhenno | Eldar Quliyev |
| Bruno Racine | Fərid Rəhmanov |
| Gilles Andréani | Hafiz Cabbarov |
| Michel Foucher | İlham Nəcəfov |
| Pierre Lévy | Namiq Səlimov |
| Marie Mendras | Lalə Vəliyeva |
| Joseph Maïla | Rafiq İbrahimov |
| Justin Vaïsse | Sərxan Əsədov |

</details>

### Easy 16 — az_timeqa_easy_016

Source: `timeqa_easy_timebench.json`, record **383** (1-based). Type: `between_explicit`.

**Adapted question:** Caspian Policy Planning Centre was managed or directed by whom from 1989 to 1993?

**Adapted answer:** ["Eldar Quliyev"]

**Adapted context:**

The Caspian Policy Planning Centre ( Caspian Policy Planning Centre , or CPPC , formerly known as Regional Analysis and Planning Centre ( or Centre for Analysis and Planning ) , and then as Foresight Department ( or Directorate for Foresight ) is a think tank within the Regional External Relations Department , tasked with making strategic recommendations to the External Relations Director and ensuring a regional presence in national and international debates and institutions . It is the local counterpart to the Regional Councils Policy Planning Office It is currently headed by diplomat Əliyar Əhmədov , who was appointed by External Relations Director Şahin Həsənov in July 2019 . The CPPC has a history of renowned directors , either academics or career diplomats . - Akif İsmayılov ( 1974-1978 ) - Bəxtiyar Rzayev ( 1979-1984 ) - Ceyhun Qasımov ( 1984-1989 ) - Eldar Quliyev ( 1989-1993 ) - Fərid Rəhmanov ( 1993-1995 ) - Hafiz Cabbarov ( 1995-1999 , 2002-2004 ) - İlham Nəcəfov ( 1999-2002 ) - Namiq Səlimov ( 2005-2010 ) - Lalə Vəliyeva ( 2010 ) - Rafiq İbrahimov ( 2010-2013 ) - Sərxan Əsədov ( 2013-2019 ) - Əliyar Əhmədov ( 2019- )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Policy Planning Staff (France) was managed or directed by whom from 1989 to 1993?",
  "context": "The Centre for Analysis , Planning and Strategy ( Centre d’analyse , de prévision et de stratégie , or CAPS , formerly known as Centre danalyse et de prévision ( or Centre for Analysis and Planning ) , and then as Direction de la prospective ( or Directorate for Foresight ) is a think tank within the French Ministry of Foreign Affairs , tasked with making strategic recommendations to the Foreign Minister and ensuring a French presence in European and international debates and institutions . It is the French counterpart to the US State Department’s Policy Planning Staff It is currently headed by diplomat Manuel Lafont Rapnouil , who was appointed by Foreign Minister Jean-Yves Le Drian in July 2019 . The CAPS has a history of renowned directors , either academics or career diplomats . - Thierry de Montbrial ( 1974-1978 ) - Jean-Louis Gergorin ( 1979-1984 ) - Philippe Coste ( 1984-1989 ) - Jean-Marie Guéhenno ( 1989-1993 ) - Bruno Racine ( 1993-1995 ) - Gilles Andréani ( 1995-1999 , 2002-2004 ) - Michel Foucher ( 1999-2002 ) - Pierre Lévy ( 2005-2010 ) - Marie Mendras ( 2010 ) - Joseph Maïla ( 2010-2013 ) - Justin Vaïsse ( 2013-2019 ) - Manuel Lafont Rapnouil ( 2019- )",
  "answer": [
    "Jean-Marie Guéhenno"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Policy_Planning_Staff_(France)#P1037#3"
}
```

| Original | Replacement |
|---|---|
| Policy Planning Staff (France) | Caspian Policy Planning Centre |
| Centre for Analysis , Planning and Strategy | Caspian Policy Planning Centre |
| Centre d’analyse , de prévision et de stratégie | Caspian Policy Planning Centre |
| CAPS | CPPC |
| Centre danalyse et de prévision | Regional Analysis and Planning Centre |
| Direction de la prospective | Foresight Department |
| French Ministry of Foreign Affairs | Regional External Relations Department |
| Foreign Minister | External Relations Director |
| French presence in European and international debates and institutions | regional presence in national and international debates and institutions |
| French counterpart | local counterpart |
| US State Department’s Policy Planning Staff | Regional Councils Policy Planning Office |
| Manuel Lafont Rapnouil | Əliyar Əhmədov |
| Jean-Yves Le Drian | Şahin Həsənov |
| Thierry de Montbrial | Akif İsmayılov |
| Jean-Louis Gergorin | Bəxtiyar Rzayev |
| Philippe Coste | Ceyhun Qasımov |
| Jean-Marie Guéhenno | Eldar Quliyev |
| Bruno Racine | Fərid Rəhmanov |
| Gilles Andréani | Hafiz Cabbarov |
| Michel Foucher | İlham Nəcəfov |
| Pierre Lévy | Namiq Səlimov |
| Marie Mendras | Lalə Vəliyeva |
| Joseph Maïla | Rafiq İbrahimov |
| Justin Vaïsse | Sərxan Əsədov |

</details>

### Easy 17 — az_timeqa_easy_017

Source: `timeqa_easy_timebench.json`, record **228** (1-based). Type: `between_explicit`.

**Adapted question:** What position did Ənvər Məlikov take from 1955 to 1957?

**Adapted answer:** ["district head"]

**Adapted context:**

Ənvər Məlikov ( January 1 , 1884 – May 30 , 1970 ) was an Azerbaijani politician of the Civic Development Party who served as both district head of and National Council member from the Northern District . Beginning in 1923 , Məlikov served in the Northern District Council for four terms . He was deputy district head from 1931 to 1933 . He represented Northern District for three terms in the National Council from 1937 until 1955 , during which time from 1937 to 1940 he was an intraparty critic of the Renewal Programme policies of Council Chair Əli Rəhimov . Məlikov served as the 26th and 34th district head of Northern District from January 10 , 1933 until January 1 , 1937 and from January 12 , 1955 until January 8 , 1957 . He opposed Rəhimovs Renewal Programme policies .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What position did Edwin C. Johnson take from 1955 to 1957?",
  "context": "Edwin Carl Johnson ( January 1 , 1884 – May 30 , 1970 ) was an American politician of the Democratic Party who served as both governor of and U.S . senator from the state of Colorado . Beginning in 1923 , Johnson served in the Colorado House of Representatives for four terms . He was lieutenant governor from 1931 to 1933 . He represented Colorado for three terms in the United States Senate from 1937 until 1955 , during which time from 1937 to 1940 he was an intraparty critic of the New Deal policies of U.S . President Franklin D . Roosevelt . Johnson served as the 26th and 34th governor of Colorado from January 10 , 1933 until January 1 , 1937 and from January 12 , 1955 until January 8 , 1957 . He opposed FDR’s New Deal policies .",
  "answer": [
    "governor"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Edwin_C._Johnson#P39#2"
}
```

| Original | Replacement |
|---|---|
| Edwin C. Johnson | Ənvər Məlikov |
| Edwin Carl Johnson | Ənvər Məlikov |
| American politician | Azerbaijani politician |
| Democratic Party | Civic Development Party |
| governor | district head |
| U.S . senator | National Council member |
| state of Colorado | Northern District |
| Johnson | Məlikov |
| Colorado House of Representatives | Northern District Council |
| lieutenant governor | deputy district head |
| Colorado | Northern District |
| United States Senate | National Council |
| New Deal | Renewal Programme |
| U.S . President Franklin D . Roosevelt | Council Chair Əli Rəhimov |
| FDR’s | Rəhimovs |

</details>

### Easy 18 — az_timeqa_easy_018

Source: `timeqa_easy_timebench.json`, record **300** (1-based). Type: `between_explicit`.

**Adapted question:** What position did Ənvər Məlikov take from 1931 to 1933?

**Adapted answer:** ["deputy district head"]

**Adapted context:**

Ənvər Məlikov ( January 1 , 1884 – May 30 , 1970 ) was an Azerbaijani politician of the Civic Development Party who served as both district head of and National Council member from the Northern District . Beginning in 1923 , Məlikov served in the Northern District Council for four terms . He was deputy district head from 1931 to 1933 . He represented Northern District for three terms in the National Council from 1937 until 1955 , during which time from 1937 to 1940 he was an intraparty critic of the Renewal Programme policies of Council Chair Əli Rəhimov . Məlikov served as the 26th and 34th district head of Northern District from January 10 , 1933 until January 1 , 1937 and from January 12 , 1955 until January 8 , 1957 . He opposed Rəhimovs Renewal Programme policies .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What position did Edwin C. Johnson take from 1931 to 1933?",
  "context": "Edwin Carl Johnson ( January 1 , 1884 – May 30 , 1970 ) was an American politician of the Democratic Party who served as both governor of and U.S . senator from the state of Colorado . Beginning in 1923 , Johnson served in the Colorado House of Representatives for four terms . He was lieutenant governor from 1931 to 1933 . He represented Colorado for three terms in the United States Senate from 1937 until 1955 , during which time from 1937 to 1940 he was an intraparty critic of the New Deal policies of U.S . President Franklin D . Roosevelt . Johnson served as the 26th and 34th governor of Colorado from January 10 , 1933 until January 1 , 1937 and from January 12 , 1955 until January 8 , 1957 . He opposed FDR’s New Deal policies .",
  "answer": [
    "lieutenant governor"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Edwin_C._Johnson#P39#0"
}
```

| Original | Replacement |
|---|---|
| Edwin C. Johnson | Ənvər Məlikov |
| Edwin Carl Johnson | Ənvər Məlikov |
| American politician | Azerbaijani politician |
| Democratic Party | Civic Development Party |
| governor | district head |
| U.S . senator | National Council member |
| state of Colorado | Northern District |
| Johnson | Məlikov |
| Colorado House of Representatives | Northern District Council |
| lieutenant governor | deputy district head |
| Colorado | Northern District |
| United States Senate | National Council |
| New Deal | Renewal Programme |
| U.S . President Franklin D . Roosevelt | Council Chair Əli Rəhimov |
| FDR’s | Rəhimovs |

</details>

### Easy 19 — az_timeqa_easy_019

Source: `timeqa_easy_timebench.json`, record **20** (1-based). Type: `between_explicit`.

**Adapted question:** Cəlal Hacıyev was an employee for whom from 1909 to 1925?

**Adapted answer:** ["Shamakhi Scientific Institute"]

**Adapted context:**

Cəlal Hacıyev ( 2 February 1881 – 22 March 1953 ) was an Azerbaijani physicist . He is best known for his works on the theory of relativity and seismology . Hacıyev studied Mathematics and Astronomy at the Baku Mathematical Institute in 1899 , and attended lectures by Bəşir Kazımov . In this time of study , he had a friendship with his colleagues Emin Rəsulov , Həsən Səfərov and Mikayıl Qasımov . In 1900 he went to the Ganja Scientific College and achieved his Doctorate in 1902 under Nüsrət Rzayev . Afterwards , he went to the Shaki Institute of Applied Sciences , where he habilitated under Süleyman Kərimov . In 1904 he became Lecturer for Astronomy and Mathematics there , and in 1907 Associate Professor In 1908 he became Associate Professor in Baku , and in 1909 at the Shamakhi Scientific Institute . From 1925 ( until becoming Emeritus in 1947 ) he again was in Shaki as the successor of Vəli Həmidov on the chair of applied mathematics . One of his students was Yalçın Quliyev .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Gustav Herglotz was an employee for whom from 1909 to 1925?",
  "context": "Gustav Herglotz ( 2 February 1881 – 22 March 1953 ) was a German Bohemian physicist . He is best known for his works on the theory of relativity and seismology . Herglotz studied Mathematics and Astronomy at the University of Vienna in 1899 , and attended lectures by Ludwig Boltzmann . In this time of study , he had a friendship with his colleagues Paul Ehrenfest , Hans Hahn and Heinrich Tietze . In 1900 he went to the LMU Munich and achieved his Doctorate in 1902 under Hugo von Seeliger . Afterwards , he went to the University of Göttingen , where he habilitated under Felix Klein . In 1904 he became Privatdozent for Astronomy and Mathematics there , and in 1907 Professor extraordinarius In 1908 he became Professor extraordinarius in Vienna , and in 1909 at the University of Leipzig . From 1925 ( until becoming Emeritus in 1947 ) he again was in Göttingen as the successor of Carl Runge on the chair of applied mathematics . One of his students was Emil Artin .",
  "answer": [
    "University of Leipzig"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Gustav_Herglotz#P108#2"
}
```

| Original | Replacement |
|---|---|
| Gustav Herglotz | Cəlal Hacıyev |
| German Bohemian | Azerbaijani |
| Herglotz | Hacıyev |
| University of Vienna | Baku Mathematical Institute |
| Ludwig Boltzmann | Bəşir Kazımov |
| Paul Ehrenfest | Emin Rəsulov |
| Hans Hahn | Həsən Səfərov |
| Heinrich Tietze | Mikayıl Qasımov |
| LMU Munich | Ganja Scientific College |
| Hugo von Seeliger | Nüsrət Rzayev |
| University of Göttingen | Shaki Institute of Applied Sciences |
| Felix Klein | Süleyman Kərimov |
| Privatdozent | Lecturer |
| Professor extraordinarius | Associate Professor |
| Vienna | Baku |
| University of Leipzig | Shamakhi Scientific Institute |
| Göttingen | Shaki |
| Carl Runge | Vəli Həmidov |
| Emil Artin | Yalçın Quliyev |

</details>

### Easy 20 — az_timeqa_easy_020

Source: `timeqa_easy_timebench.json`, record **253** (1-based). Type: `between_explicit`.

**Adapted question:** What was the name of the employer Fərid Şahbazov work for from 1993 to 1997?

**Adapted answer:** ["Baku Computing Institute"]

**Adapted context:**

Fərid Şahbazov ( born 10 January 1964 ) is an Azerbaijani scientist , composer and director of the Caspian Music Technology Research Lab . Before joining Caspian Music Technologies he led Khazar Computing Laboratory in Baku . He is one of the pioneers of computer music closely linked to artificial intelligence , especially in the field of machine improvisation and style modelling . He has been elected Caspian Association for Artificial Intelligence Fellow in 2014 . In 1993 , he was appointed Assistant Professor ( locally , Assistant Professor ) , at Baku Computing Institute until 1997 in Computer Science , Research and Teaching . In 1997 , Şahbazov moved to Khazar Computing Laboratory ( Computer Science Laboratory ) Baku . He started a research activity on music and artificial intelligence . His team has authored and pioneered many technologies ( about 35 patents ) about electronic music distribution , audio feature extraction and music interaction . He was appointed director of Khazar Computing Laboratories in 2014 . The KCL ( the branch of Khazar Computing Laboratory Ganja ) is dedicated to basic research in computer science ; it was created by Cavid Kazımov and Fuad Rəsulov in 1996 . Since 2017 , he is director of Caspian Music Technology Research Lab in Baku , where he develops tools for assisting music creation .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the name of the employer François Pachet work for from 1993 to 1997?",
  "context": "François Pachet ( born 10 January 1964 ) is a French scientist , composer and director of the Spotify Creator Technology Research Lab . Before joining Spotify he led Sony Computer Science Laboratory in Paris . He is one of the pioneers of computer music closely linked to artificial intelligence , especially in the field of machine improvisation and style modelling . He has been elected ECCAI Fellow in 2014 . In 1993 , he was appointed Assistant Professor ( in French , Maitre de conférences ) , at Pierre and Marie Curie University until 1997 in Computer Science , Research and Teaching . In 1997 , Pachet moved to Sony-CSL ( Computer Science Laboratory ) Paris . He started a research activity on music and artificial intelligence . His team has authored and pioneered many technologies ( about 35 patents ) about electronic music distribution , audio feature extraction and music interaction . He was appointed director of Sony Computer Science Laboratories in 2014 . The CSL ( the branch of Sony-CSL Tokyo ) is dedicated to basic research in computer science ; it was created by Luc Steels and Mario Tokoro in 1996 . Since 2017 , he is director of Spotifys Creator Research Technology Lab in Paris , where he develops tools for assisting music creation .",
  "answer": [
    "Pierre and Marie Curie University"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/François_Pachet#P108#0"
}
```

| Original | Replacement |
|---|---|
| François Pachet | Fərid Şahbazov |
| French scientist | Azerbaijani scientist |
| Spotify Creator Technology Research Lab | Caspian Music Technology Research Lab |
| Spotify | Caspian Music Technologies |
| Sony Computer Science Laboratory | Khazar Computing Laboratory |
| Paris | Baku |
| ECCAI | Caspian Association for Artificial Intelligence |
| in French , Maitre de conférences | locally , Assistant Professor |
| Pierre and Marie Curie University | Baku Computing Institute |
| Pachet | Şahbazov |
| Sony-CSL | Khazar Computing Laboratory |
| Sony Computer Science Laboratories | Khazar Computing Laboratories |
| CSL | KCL |
| Sony-CSL Tokyo | Khazar Computing Laboratory Ganja |
| Luc Steels | Cavid Kazımov |
| Mario Tokoro | Fuad Rəsulov |
| Spotifys Creator Research Technology Lab | Caspian Music Technology Research Lab |

</details>

### Easy 21 — az_timeqa_easy_021

Source: `timeqa_easy_timebench.json`, record **234** (1-based). Type: `between_explicit`.

**Adapted question:** What was the name of the employer Səlim İbrahimov work for from 1968 to 1996?

**Adapted answer:** ["Shamakhi Astronomy Institute"]

**Adapted context:**

Səlim İbrahimov ( 4 February 1947 – 16 November 2019 ) was an Azerbaijani astronomer who worked primarily in solar physics . He held the posts of Chief Astronomer of the Regional Observatory , the Senior Professor of Astronomy at the Shamakhi Astronomy Institute , and honorary professorships at both the Baku Institute of Physical Sciences and the Ganja Astronomy College . The Shamakhi Astronomy Institute employed him as an astronomy research assistant in 1968–70 and lecturer from 1970 , while he was still studying for his PhD . In 1978 he was promoted to senior lecturer , and then reader in 1980 . He received a research fellowship from the Ulduz Research Foundation in 1983–1984 . He was then promoted to chair of astrophysics from 1984 and became the Senior Professor of Astronomy in 1996 . Beginning in 1986 , he was head of Shamakhi Institutes astronomy & astrophysics research group İbrahimov received additional appointments as honorary professor at the Baku Institute of Physical Sciences from 1996 , and the Ganja Astronomy College from 1998 . He taught astronomy at all university levels , from first year undergraduate to postgraduate courses .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the name of the employer John Campbell Brown work for from 1968 to 1996?",
  "context": "John Campbell Brown ( 4 February 1947 – 16 November 2019 ) was a Scottish astronomer who worked primarily in solar physics . He held the posts of Astronomer Royal for Scotland , the Regius Professor of Astronomy at the University of Glasgow , and honorary professorships at both the University of Edinburgh and the University of Aberdeen . The University of Glasgow employed him as an astronomy research assistant in 1968–70 and lecturer from 1970 , while he was still studying for his PhD . In 1978 he was promoted to senior lecturer , and then reader in 1980 . He received a research fellowship from the Nuffield Foundation in 1983–1984 . He was then promoted to chair of astrophysics from 1984 and became the Regius Professor of Astronomy in 1996 . Beginning in 1986 , he was head of Glasgows astronomy & astrophysics research group Brown received additional appointments as honorary professor at the University of Edinburgh from 1996 , and the University of Aberdeen from 1998 . He taught astronomy at all university levels , from first year undergraduate to postgraduate courses .",
  "answer": [
    "University of Glasgow"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/John_Campbell_Brown#P108#0"
}
```

| Original | Replacement |
|---|---|
| John Campbell Brown | Səlim İbrahimov |
| Scottish astronomer | Azerbaijani astronomer |
| Astronomer Royal for Scotland | Chief Astronomer of the Regional Observatory |
| Regius Professor | Senior Professor |
| University of Glasgow | Shamakhi Astronomy Institute |
| University of Edinburgh | Baku Institute of Physical Sciences |
| University of Aberdeen | Ganja Astronomy College |
| Nuffield Foundation | Ulduz Research Foundation |
| Glasgows | Shamakhi Institutes |
| Brown | İbrahimov |

</details>

### Easy 22 — az_timeqa_easy_022

Source: `timeqa_easy_timebench.json`, record **356** (1-based). Type: `between_explicit`.

**Adapted question:** What was the name of the employer Cəlal Hacıyev work for from 1925 to 1946?

**Adapted answer:** ["Shaki Institute of Applied Sciences"]

**Adapted context:**

Cəlal Hacıyev ( 2 February 1881 – 22 March 1953 ) was an Azerbaijani physicist . He is best known for his works on the theory of relativity and seismology . Hacıyev studied Mathematics and Astronomy at the Baku Mathematical Institute in 1899 , and attended lectures by Bəşir Kazımov . In this time of study , he had a friendship with his colleagues Emin Rəsulov , Həsən Səfərov and Mikayıl Qasımov . In 1900 he went to the Ganja Scientific College and achieved his Doctorate in 1902 under Nüsrət Rzayev . Afterwards , he went to the Shaki Institute of Applied Sciences , where he habilitated under Süleyman Kərimov . In 1904 he became Lecturer for Astronomy and Mathematics there , and in 1907 Associate Professor In 1908 he became Associate Professor in Baku , and in 1909 at the Shamakhi Scientific Institute . From 1925 ( until becoming Emeritus in 1947 ) he again was in Shaki as the successor of Vəli Həmidov on the chair of applied mathematics . One of his students was Yalçın Quliyev .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the name of the employer Gustav Herglotz work for from 1925 to 1946?",
  "context": "Gustav Herglotz ( 2 February 1881 – 22 March 1953 ) was a German Bohemian physicist . He is best known for his works on the theory of relativity and seismology . Herglotz studied Mathematics and Astronomy at the University of Vienna in 1899 , and attended lectures by Ludwig Boltzmann . In this time of study , he had a friendship with his colleagues Paul Ehrenfest , Hans Hahn and Heinrich Tietze . In 1900 he went to the LMU Munich and achieved his Doctorate in 1902 under Hugo von Seeliger . Afterwards , he went to the University of Göttingen , where he habilitated under Felix Klein . In 1904 he became Privatdozent for Astronomy and Mathematics there , and in 1907 Professor extraordinarius In 1908 he became Professor extraordinarius in Vienna , and in 1909 at the University of Leipzig . From 1925 ( until becoming Emeritus in 1947 ) he again was in Göttingen as the successor of Carl Runge on the chair of applied mathematics . One of his students was Emil Artin .",
  "answer": [
    "University of Göttingen"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Gustav_Herglotz#P108#3"
}
```

| Original | Replacement |
|---|---|
| Gustav Herglotz | Cəlal Hacıyev |
| German Bohemian | Azerbaijani |
| Herglotz | Hacıyev |
| University of Vienna | Baku Mathematical Institute |
| Ludwig Boltzmann | Bəşir Kazımov |
| Paul Ehrenfest | Emin Rəsulov |
| Hans Hahn | Həsən Səfərov |
| Heinrich Tietze | Mikayıl Qasımov |
| LMU Munich | Ganja Scientific College |
| Hugo von Seeliger | Nüsrət Rzayev |
| University of Göttingen | Shaki Institute of Applied Sciences |
| Felix Klein | Süleyman Kərimov |
| Privatdozent | Lecturer |
| Professor extraordinarius | Associate Professor |
| Vienna | Baku |
| University of Leipzig | Shamakhi Scientific Institute |
| Göttingen | Shaki |
| Carl Runge | Vəli Həmidov |
| Emil Artin | Yalçın Quliyev |

</details>

### Easy 23 — az_timeqa_easy_023

Source: `timeqa_easy_timebench.json`, record **483** (1-based). Type: `between_explicit`.

**Adapted question:** What was the name of the employer Rəşid Əfəndiyev work for from 1984 to 1985?

**Adapted answer:** ["Baku Legal Studies College"]

**Adapted context:**

Rəşid Əfəndiyev is an Azerbaijani international law scholar and human rights practitioner . He is Senior Professor of Law at Ganja Legal Studies Institute , and co-Chair of the law schools Center for Human Rights and Global Justice . In human rights law , Əfəndiyev has held a range of senior regional council appointments for over two decades , including Regional Council Special Rapporteur on extrajudicial , summary or arbitrary executions , a position he held from August 2004 to July 2010 In 2014 he was appointed to an unpaid role as Regional Council Special Rapporteur on extreme poverty and human rights . Əfəndiyevs first academic appointments were at Shamakhi Law College ( 1985–89 ) and Baku Legal Studies College ( 1984–89 ) . Əfəndiyev was then Professor at the Ganja Social Sciences Institute ( 1990–95 ) , and also director of its Center for International and Public Law . He was then Professor at the Caspian Advanced Studies Institute ( 1996–2001 ) , before moving to Ganja Legal Studies Institute , where he is the Senior Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice He became a faculty instructor in the Ganja Institute of Professional Legal Education , which was launched in 2015 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the name of the employer Philip Alston work for from 1984 to 1985?",
  "context": "Philip G . Alston is an Australian international law scholar and human rights practitioner . He is John Norton Pomeroy Professor of Law at New York University School of Law , and co-Chair of the law schools Center for Human Rights and Global Justice . In human rights law , Alston has held a range of senior UN appointments for over two decades , including United Nations Special Rapporteur on extrajudicial , summary or arbitrary executions , a position he held from August 2004 to July 2010 In 2014 he was appointed to an unpaid role as UN Special Rapporteur on extreme poverty and human rights . Alstons first academic appointments were at Tufts University ( 1985–89 ) and Harvard Law School ( 1984–89 ) . Alston was then Professor at the Australian National University ( 1990–95 ) , and also director of its Center for International and Public Law . He was then Professor at the European University Institute ( 1996–2001 ) , before moving to New York University School of Law , where he is the John Norton Pomeroy Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice He became a faculty instructor in the NYU Law Institute for Executive Education , which was launched in 2015 .",
  "answer": [
    "Harvard Law School"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Philip_Alston#P108#0"
}
```

| Original | Replacement |
|---|---|
| Philip Alston | Rəşid Əfəndiyev |
| Philip G . Alston | Rəşid Əfəndiyev |
| Australian international law scholar | Azerbaijani international law scholar |
| John Norton Pomeroy Professor | Senior Professor |
| New York University School of Law | Ganja Legal Studies Institute |
| Alston | Əfəndiyev |
| senior UN appointments | senior regional council appointments |
| United Nations Special Rapporteur | Regional Council Special Rapporteur |
| UN Special Rapporteur | Regional Council Special Rapporteur |
| Tufts University | Shamakhi Law College |
| Harvard Law School | Baku Legal Studies College |
| Australian National University | Ganja Social Sciences Institute |
| European University Institute | Caspian Advanced Studies Institute |
| NYU Law Institute for Executive Education | Ganja Institute of Professional Legal Education |

</details>

### Easy 24 — az_timeqa_easy_024

Source: `timeqa_easy_timebench.json`, record **129** (1-based). Type: `in_explicit`.

**Adapted question:** Cavid Həsənli became a member of what organization or association in 1964?

**Adapted answer:** ["Səhər Sədaları"]

**Adapted context:**

Cahangir Həsənov ( born 22 March 1946 ) , better known as his stage name Cavid Həsənli , is an Azerbaijani musician , songwriter and record producer . He is best known as lead guitarist of the 1960s Azerbaijani rock band the Səhər Sədaları who with fellow member Rauf Nəcəfov formed the 1970s and 1980s songwriting and record production duo Həsənli & Nəcəfov . Həsənlis family migrated to Baku from Shaki in 1963 , and settled in Baku . Həsənli , who had been a guitarist with the Shaki-based band the Ulduzlar , came to fame in 1964–65 as the lead guitarist of the Səhər Sədaları . In the same year he met rhythm guitarist Rauf Nəcəfov at the Baku newcomers hostel . In 2007 , Caspian Musician magazine selected this meeting as the most significant event in Azerbaijani pop and rock music history .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Harry Vanda became a member of what organization or association in 1964?",
  "context": "Johannes Hendrikus Jacob van den Berg ( born 22 March 1946 ) , better known as his stage name Harry Vanda , is a Dutch Australian musician , songwriter and record producer . He is best known as lead guitarist of the 1960s Australian rock band the Easybeats who with fellow member George Young formed the 1970s and 1980s songwriting and record production duo Vanda & Young . Vandas family migrated to Australia from the Netherlands in 1963 , and settled in Sydney . Vanda , who had been a guitarist with the Hague-based band the Starfighters , came to fame in 1964–65 as the lead guitarist of the Easybeats . In the same year he met rhythm guitarist George Young at the Villawood migrant hostel . In 2007 , Australian Musician magazine selected this meeting as the most significant event in Australian pop and rock music history .",
  "answer": [
    "Easybeats"
  ],
  "question_type": "in_explicit",
  "idx": "/wiki/Harry_Vanda#P463#0"
}
```

| Original | Replacement |
|---|---|
| Harry Vanda | Cavid Həsənli |
| Johannes Hendrikus Jacob van den Berg | Cahangir Həsənov |
| Dutch Australian | Azerbaijani |
| Australian rock band | Azerbaijani rock band |
| Easybeats | Səhər Sədaları |
| George Young | Rauf Nəcəfov |
| Vanda & Young | Həsənli & Nəcəfov |
| Vanda | Həsənli |
| Australia from the Netherlands | Baku from Shaki |
| Sydney | Baku |
| Hague-based | Shaki-based |
| Starfighters | Ulduzlar |
| Villawood migrant hostel | Baku newcomers hostel |
| Australian Musician | Caspian Musician |
| Australian pop and rock music | Azerbaijani pop and rock music |

</details>

### Easy 25 — az_timeqa_easy_025

Source: `timeqa_easy_timebench.json`, record **307** (1-based). Type: `in_explicit`.

**Adapted question:** Which award did Mənsur Kazımov receive in 1871?

**Adapted answer:** ["Cultural Heritage Medal"]

**Adapted context:**

Dr . Mənsur Kazımov ( 26 June 1836 – 1 March 1903 ) was an Azerbaijani historian and museum director . In March 1871 , the Regional Cultural Council honoured him with the Cultural Heritage Medal . In 1875 , the Senate of the Shaki Historical Studies College promoted him as Doctor Honoris causa in Literature . In 1882 , he was appointed as a member of the Caspian Society of Arts and Sciences . On 31 August 1898 , he was decorated with the Order of Service to Culture . He was a member of several national and international societies As one of the leading specialists in hieratic of his time , a portrait bust of Mənsur Kazımov was included in the funerary monument for Həmid Qasımov in the garden of the Historical Museum in Baku .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which award did Willem Pleyte receive in 1871?",
  "context": "Dr . Willem Pleyte ( 26 June 1836 – 1 March 1903 ) was a Dutch Egyptologist and museum director . In March 1871 , the Italian government honoured him with the Order of the Crown of Italy . In 1875 , the Senate of the Leyden University promoted him as Doctor Honoris causa in Literature . In 1882 , he was appointed as a member of the Royal Netherlands Academy of Arts and Sciences . On 31 August 1898 , he was decorated with the Knight of the Order of the Netherlands Lion . He was a member of several national and international societies As one of the leading specialists in hieratic of his time , a portrait bust of Willem Pleyte was included in the funerary monument for Auguste Mariette in the garden of the Egyptian Museum in Cairo .",
  "answer": [
    "Order of the Crown of Italy"
  ],
  "question_type": "in_explicit",
  "idx": "/wiki/Willem_Pleyte#P166#2"
}
```

| Original | Replacement |
|---|---|
| Willem Pleyte | Mənsur Kazımov |
| Dutch Egyptologist | Azerbaijani historian |
| Italian government | Regional Cultural Council |
| Order of the Crown of Italy | Cultural Heritage Medal |
| Leyden University | Shaki Historical Studies College |
| Royal Netherlands Academy of Arts and Sciences | Caspian Society of Arts and Sciences |
| Knight of the Order of the Netherlands Lion | Order of Service to Culture |
| Auguste Mariette | Həmid Qasımov |
| Egyptian Museum in Cairo | Historical Museum in Baku |

</details>

### Easy 26 — az_timeqa_easy_026

Source: `timeqa_easy_timebench.json`, record **29** (1-based). Type: `between_explicit`.

**Adapted question:** Nigar Səlimova went to which school from 1891 to 1894?

**Adapted answer:** ["Caspian Teacher Training College"]

**Adapted context:**

Nigar Səlimova ( 1872–1917 ) was an educator in Azerbaijan , responsible for the founding of schools , becoming the first Principal of Shamakhi Womens College , Shamakhi , Azerbaijan and then Principal of Caspian Womens College , Shaki , Azerbaijan from 1913 until her death in 1917 . She was born on 4 September 1872 in Sabunchu , Baku , the eldest sister of Cavid Səlimov , who became vice-principal of the Ganja Higher Education Institute . Her father , Səlim Səlimov , was an Azerbaijani merchant , and her mother was , Zəhra Səlimova , née Quliyeva . She was educated at Shamakhi Girls School and attended Caspian Teacher Training College , Baku from 1891 until 1894 , where she obtained a first class degree studying Azerbaijani and Russian . From 1895 to 1896 , she studied Oriental languages at Shaki Language College , Shaki She reputedly had a working knowledge of 14 languages . She then spent a time also teaching at Ganja Girls School .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Agnes de Selincourt went to which school from 1891 to 1894?",
  "context": "Agnes de Selincourt ( 1872–1917 ) was a Christian missionary in India , responsible for the founding of missions , becoming the first Principal of Lady Muir Memorial College , Allahabad , India and then Principal of Westfield College , London , UK from 1913 until her death in 1917 . She was born on 4 September 1872 in Streatham , London , the eldest sister of Ernest de Sélincourt , who became vice-principal of the University of Birmingham . Her father , Charles Alexandre De Sélincourt , was a merchant of French origin , and her mother was , Theodora Bruce , née Bendall . She was educated at Notting Hill High School and attended Girton College , Cambridge from 1891 until 1894 , where she obtained a first class degree studying French and German . From 1895 to 1896 , she studied Oriental languages at Somerville College , Oxford She reputedly had a working knowledge of 14 languages . She then spent a time also teaching at Sheffield High School .",
  "answer": [
    "Girton College"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Agnes_de_Selincourt#P69#1"
}
```

| Original | Replacement |
|---|---|
| Agnes de Selincourt | Nigar Səlimova |
| Christian missionary in India | educator in Azerbaijan |
| responsible for the founding of missions | responsible for the founding of schools |
| Lady Muir Memorial College , Allahabad , India | Shamakhi Womens College , Shamakhi , Azerbaijan |
| Westfield College , London , UK | Caspian Womens College , Shaki , Azerbaijan |
| Streatham , London | Sabunchu , Baku |
| Ernest de Sélincourt | Cavid Səlimov |
| University of Birmingham | Ganja Higher Education Institute |
| Charles Alexandre De Sélincourt | Səlim Səlimov |
| merchant of French origin | Azerbaijani merchant |
| Theodora Bruce , née Bendall | Zəhra Səlimova , née Quliyeva |
| Notting Hill High School | Shamakhi Girls School |
| Girton College , Cambridge | Caspian Teacher Training College , Baku |
| French and German | Azerbaijani and Russian |
| Somerville College , Oxford | Shaki Language College , Shaki |
| Sheffield High School | Ganja Girls School |
| Girton College | Caspian Teacher Training College |

</details>

### Easy 27 — az_timeqa_easy_027

Source: `timeqa_easy_timebench.json`, record **39** (1-based). Type: `between_explicit`.

**Adapted question:** Which team did Murad Hacıyev play for from 1996 to 1998?

**Adapted answer:** ["Ganja Dawn"]

**Adapted context:**

Murad Hacıyev ( ; born 9 October 1975 ) is an Azerbaijani retired footballer who played as a centre forward . He captained the Azerbaijan national team to the Round of 16 at the 2006 National Football Cup which remains their best ever performance to date . His four goals in the Caspian Champions League are the most scored by any Azerbaijani player . In 1995 , Hacıyev moved to Ganja to play with Ganja Dawn ( now Ganja Unity ) . He spent three-and-a-half seasons with the club , helping it to win three doubles in Azerbaijan between 1996 and 1998 . He was also part of the Ganja Dawn team that reached the third round of the Caspian Cup in 1997 and went on to make his Caspian Champions League group stage debut with the club a year later . He won the Best Footballer Award in the Regional League in his time at Ganja .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did Mark Viduka play for from 1996 to 1998?",
  "context": "Mark Antony Viduka ( ; born 9 October 1975 ) is an Australian retired footballer who played as a centre forward . He captained the Australia national team to the Round of 16 at the 2006 FIFA World Cup which remains their best ever performance to date . His four goals in the UEFA Champions League are the most scored by any Australian player . In 1995 , Viduka moved to Croatia to play with Croatia Zagreb ( now Dinamo Zagreb ) . He spent three-and-a-half seasons with the club , helping it to win three doubles in Croatia between 1996 and 1998 . He was also part of the Croatia Zagreb team that reached the third round of the UEFA Cup in 1997 and went on to make his UEFA Champions League group stage debut with the club a year later . He won the Best Foreigner Footballer Award in the Croatian League in his time at Zagreb .",
  "answer": [
    "Croatia Zagreb"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Mark_Viduka#P54#2"
}
```

| Original | Replacement |
|---|---|
| Mark Viduka | Murad Hacıyev |
| Mark Antony Viduka | Murad Hacıyev |
| Australian retired footballer | Azerbaijani retired footballer |
| Australia national team | Azerbaijan national team |
| FIFA World Cup | National Football Cup |
| UEFA Champions League | Caspian Champions League |
| Australian player | Azerbaijani player |
| Viduka | Hacıyev |
| moved to Croatia | moved to Ganja |
| Croatia Zagreb | Ganja Dawn |
| Dinamo Zagreb | Ganja Unity |
| Croatia | Azerbaijan |
| UEFA Cup | Caspian Cup |
| Best Foreigner Footballer Award | Best Footballer Award |
| Croatian League | Regional League |
| Zagreb | Ganja |

</details>

### Easy 28 — az_timeqa_easy_028

Source: `timeqa_easy_timebench.json`, record **324** (1-based). Type: `between_explicit`.

**Adapted question:** Dəniz Rəhimov played for which team from 1997 to 1999?

**Adapted answer:** ["Lankaran Stars"]

**Adapted context:**

Dəniz Rəhimov ( born 15 May 1975 ) is a retired Azerbaijani professional footballer who is currently the manager of the Azerbaijan national football team , Azerbaijan U-23 , and Azerbaijan U-20 . Rəhimov played as a central defender for National Premier League club Baku Horizon and National Football League side , Lankaran Stars . He also captained Shamakhi Unity in the Azerbaijan Football Championship . In August 1997 , Rəhimov signed for Lankaran Stars in only their second season in the National Football League . Rəhimov scored a goal in their 4–1 win over eventual season championship winners Ganja South at Lankaran City Stadium on 7 December 1997 . Lankaran Stars finished 8th on the table at the end of the season . Rəhimov was awarded the prestigious Lankaran Stars Most Glorious Player award . The following season proved to be more successful for Lankaran Stars finishing 3rd after losing the preliminary final to Baku Unity at Baku on 23 May 1999 . Rəhimov was awarded again the prestigious Lankaran Stars Most Glorious Player award this time jointly with Sərxan Hacıyev .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Danny Hay played for which team from 1997 to 1999?",
  "context": "Daniel John Danny Hay ( born 15 May 1975 ) is a retired New Zealand professional footballer who is currently the manager of the New Zealand national football team , New Zealand U-23 , and New Zealand U-20 . Hay played as a central defender for English Premier League club Leeds United and National Soccer League side , Perth Glory . He also captained Waitakere United in the New Zealand Football Championship . In August 1997 , Hay signed for Perth Glory in only their second season in the Australian National Soccer League . Hay scored a goal in their 4–1 win over eventual season championship winners South Melbourne at Perth Oval on 7 December 1997 . Perth Glory finished 8th on the table at the end of the season . Hay was awarded the prestigious Perth Glory Most Glorious Player award . The following season proved to be more successful for Perth Glory finishing 3rd after losing the preliminary final to Sydney United at Sydney on 23 May 1999 . Hay was awarded again the prestigious Perth Glory Most Glorious Player award this time jointly with Scott Miller .",
  "answer": [
    "Perth Glory"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Danny_Hay#P54#1"
}
```

| Original | Replacement |
|---|---|
| Danny Hay | Dəniz Rəhimov |
| Daniel John Danny Hay | Dəniz Rəhimov |
| New Zealand professional footballer | Azerbaijani professional footballer |
| New Zealand | Azerbaijan |
| Hay | Rəhimov |
| English Premier League | National Premier League |
| Leeds United | Baku Horizon |
| National Soccer League | National Football League |
| Perth Glory | Lankaran Stars |
| Waitakere United | Shamakhi Unity |
| Australian National Soccer League | National Football League |
| South Melbourne | Ganja South |
| Perth Oval | Lankaran City Stadium |
| Sydney United | Baku Unity |
| Sydney | Baku |
| Scott Miller | Sərxan Hacıyev |

</details>

### Easy 29 — az_timeqa_easy_029

Source: `timeqa_easy_timebench.json`, record **109** (1-based). Type: `between_explicit`.

**Adapted question:** Which team did the player Pərviz İsaqov belong to from 2009 to 2012?

**Adapted answer:** ["Ganja Horizon"]

**Adapted context:**

Pərviz İsaqov ( ; born 8 November 1983 ) is an Azerbaijani professional footballer who plays as a striker for Gabala Horizon . Born in Baku , İsaqov began his career at Baku Stars , making his professional debut in 2002 . Over the next three years , he spent time away on loan at Shaki North , Goychay Stars and Shamakhi Unity before joining Ganja South in 2006 . After a season with them , he moved to top local side Sumgait Stars . There he spent three seasons and had his greatest spell of success , winning the Northern Regional League , the Regional Super Cup , the Caspian League Cup and the Caspian Super Cup In 2009 , he joined local side Ganja Horizon . After two-and-a-half seasons , he moved to National Premier League side Baku South in January 2012 , and then to Shaki Dawn six months later . He is nicknamed The Rock , Qaya ( The Rock ) or Böyük Pərviz ( Parviz the Great ) , the latter popularized by his former Sumgait Stars teammate Asif Qurbanov . He is a powerful player who holds the ball up well . - Caspian Cup Top Scorer : 2007–08

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did the player Pavel Pogrebnyak belong to from 2009 to 2012?",
  "context": "Pavel Viktorovich Pogrebnyak ( ; born 8 November 1983 ) is a Russian professional footballer who plays as a striker for FC Ural Yekaterinburg . Born in Moscow , Pogrebnyak began his career at Spartak Moscow , making his professional debut in 2002 . Over the next three years , he spent time away on loan at Baltika Kaliningrad , Khimki and Shinnik Yaroslavl before joining Tom Tomsk in 2006 . After a season with them , he moved to top Russian side Zenit St . Petersburg . There he spent three seasons and had his greatest spell of success , winning the Russian Premier League , the Russian Super Cup , the UEFA Europa League and the UEFA Super Cup In 2009 , he joined German side VfB Stuttgart . After two-and-a-half seasons , he moved to English Premier League side Fulham in January 2012 , and then to Reading six months later . He is nicknamed The Pog , Pogreb ( The Cellar ) or Velikiy Po ( Po the Great ) , the latter popularized by his former Zenit teammate Andrei Arshavin . He is a powerful player who holds the ball up well . - UEFA Cup Top Scorer : 2007–08",
  "answer": [
    "VfB Stuttgart"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Pavel_Pogrebnyak#P54#2"
}
```

| Original | Replacement |
|---|---|
| Pavel Pogrebnyak | Pərviz İsaqov |
| Pavel Viktorovich Pogrebnyak | Pərviz İsaqov |
| Russian professional footballer | Azerbaijani professional footballer |
| FC Ural Yekaterinburg | Gabala Horizon |
| Moscow | Baku |
| Pogrebnyak | İsaqov |
| Spartak Moscow | Baku Stars |
| Baltika Kaliningrad | Shaki North |
| Khimki | Goychay Stars |
| Shinnik Yaroslavl | Shamakhi Unity |
| Tom Tomsk | Ganja South |
| Russian side | local side |
| Zenit St . Petersburg | Sumgait Stars |
| Russian Premier League | Northern Regional League |
| Russian Super Cup | Regional Super Cup |
| UEFA Europa League | Caspian League Cup |
| UEFA Super Cup | Caspian Super Cup |
| German side | local side |
| VfB Stuttgart | Ganja Horizon |
| English Premier League | National Premier League |
| Fulham | Baku South |
| Reading | Shaki Dawn |
| The Pog | The Rock |
| Pogreb ( The Cellar ) | Qaya ( The Rock ) |
| Velikiy Po ( Po the Great ) | Böyük Pərviz ( Parviz the Great ) |
| Zenit teammate | Sumgait Stars teammate |
| Andrei Arshavin | Asif Qurbanov |
| UEFA Cup | Caspian Cup |

</details>

### Easy 30 — az_timeqa_easy_030

Source: `timeqa_easy_timebench.json`, record **202** (1-based). Type: `between_explicit`.

**Adapted question:** Lalə Həmidova took which position from Dec 2007 to Oct 2014?

**Adapted answer:** ["Director of Social Affairs and Public Health ( December 2007 – October 2014 )"]

**Adapted context:**

Lalə Həmidova ( born 2 October 1958 in Shamakhi ) is an Azerbaijani public administrator from the Social Development Association . She was the Deputy Executive Chair – Director of Social Affairs and Public Health in the Regional Executive Council , i.e. , the Həsənov Administration , which took office on 6 December 2011 . First elected to the Regional Assembly in 1988 , she has held several administrative posts without any interruption since 1992 : - Director of Social Integration , Public Health and Environment ( 1992–1993 ) - Executive Chair and Director of the Civil Service , Childs healthcare and Promotion of Health in the Central District ( 1993–1995 ) - Executive Chair and Director of Education , Media , Youth , Childs healthcare and Promotion of Health in the Central District ( 1995–1999 ) - Deputy Executive Chair and Director of Labour ( 1999–2003 ) - Deputy Executive Chair and Director of Labour and Transport ( 2003 ) - Deputy Executive Chair and Director of Justice ( July 2003 – December 2007 ) - Director of Social Affairs and Public Health ( December 2007 – October 2014 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Laurette Onkelinx took which position from Dec 2007 to Oct 2014?",
  "context": "Laurette A . J . Onkelinx ( born 2 October 1958 in Ougrée ) is a Belgian politician from the Francophone Socialist Party . She was the Deputy Prime Minister – Minister of Social Affairs and Public Health in the Belgian federal government , i.e. , the Di Rupo Government , which took office on 6 December 2011 . First elected to the Belgian House of Representatives in 1988 , she has held several ministerial posts without any interruption since 1992 : - Minister of Social Integration , Public Health and Environment ( 1992–1993 ) - Minister-President and Minister of the Civil Service , Childs healthcare and Promotion of Health in the French Community ( 1993–1995 ) - Minister-President and Minister of Education , Media , Youth , Childs healthcare and Promotion of Health in the French Community ( 1995–1999 ) - Deputy Prime Minister and Minister of Labour ( 1999–2003 ) - Deputy Prime Minister and Minister of Labour and Transport ( 2003 ) - Deputy Prime Minister and Minister of Justice ( July 2003 – December 2007 ) - Minister of Social Affairs and Public Health ( December 2007 – October 2014 )",
  "answer": [
    "Minister of Social Affairs and Public Health ( December 2007 – October 2014 )"
  ],
  "question_type": "between_explicit",
  "idx": "/wiki/Laurette_Onkelinx#P39#2"
}
```

| Original | Replacement |
|---|---|
| Laurette Onkelinx | Lalə Həmidova |
| Laurette A . J . Onkelinx | Lalə Həmidova |
| Ougrée | Shamakhi |
| Belgian politician | Azerbaijani public administrator |
| Francophone Socialist Party | Social Development Association |
| Deputy Prime Minister | Deputy Executive Chair |
| Minister of | Director of |
| Belgian federal government | Regional Executive Council |
| Di Rupo Government | Həsənov Administration |
| Belgian House of Representatives | Regional Assembly |
| ministerial posts | administrative posts |
| Minister-President | Executive Chair |
| French Community | Central District |

</details>


## Hard — 30 samples

### Hard 01 — az_timeqa_hard_001

Source: `timeqa_hard_timebench.json`, record **24** (1-based). Type: `in_explicit`.

**Adapted question:** What organization did Cavid Həsənli join in 1964?

**Adapted answer:** ["Səhər Sədaları"]

**Adapted context:**

Cahangir Həsənov ( born 22 March 1946 ) , better known as his stage name Cavid Həsənli , is an Azerbaijani musician , songwriter and record producer . He is best known as lead guitarist of the 1960s Azerbaijani rock band the Səhər Sədaları who with fellow member Rauf Nəcəfov formed the 1970s and 1980s songwriting and record production duo Həsənli & Nəcəfov . Həsənlis family migrated to Baku from Shaki in 1963 , and settled in Baku . Həsənli , who had been a guitarist with the Shaki-based band the Ulduzlar , came to fame in 1964–65 as the lead guitarist of the Səhər Sədaları . In the same year he met rhythm guitarist Rauf Nəcəfov at the Baku newcomers hostel . In 2007 , Caspian Musician magazine selected this meeting as the most significant event in Azerbaijani pop and rock music history .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What organization did Harry Vanda join in 1964?",
  "context": "Johannes Hendrikus Jacob van den Berg ( born 22 March 1946 ) , better known as his stage name Harry Vanda , is a Dutch Australian musician , songwriter and record producer . He is best known as lead guitarist of the 1960s Australian rock band the Easybeats who with fellow member George Young formed the 1970s and 1980s songwriting and record production duo Vanda & Young . Vandas family migrated to Australia from the Netherlands in 1963 , and settled in Sydney . Vanda , who had been a guitarist with the Hague-based band the Starfighters , came to fame in 1964–65 as the lead guitarist of the Easybeats . In the same year he met rhythm guitarist George Young at the Villawood migrant hostel . In 2007 , Australian Musician magazine selected this meeting as the most significant event in Australian pop and rock music history .",
  "answer": [
    "Easybeats"
  ],
  "question_type": "in_explicit",
  "idx": "/wiki/Harry_Vanda#P463#0"
}
```

| Original | Replacement |
|---|---|
| Harry Vanda | Cavid Həsənli |
| Johannes Hendrikus Jacob van den Berg | Cahangir Həsənov |
| Dutch Australian | Azerbaijani |
| Australian rock band | Azerbaijani rock band |
| Easybeats | Səhər Sədaları |
| George Young | Rauf Nəcəfov |
| Vanda & Young | Həsənli & Nəcəfov |
| Vanda | Həsənli |
| Australia from the Netherlands | Baku from Shaki |
| Sydney | Baku |
| Hague-based | Shaki-based |
| Starfighters | Ulduzlar |
| Villawood migrant hostel | Baku newcomers hostel |
| Australian Musician | Caspian Musician |
| Australian pop and rock music | Azerbaijani pop and rock music |

</details>

### Hard 02 — az_timeqa_hard_002

Source: `timeqa_hard_timebench.json`, record **28** (1-based). Type: `between_implicit`.

**Adapted question:** Who was the chair of Youth Union between Sep 1996 and Jul 1997?

**Adapted answer:** ["Murad Kərimov"]

**Adapted context:**

The Azerbaijani Youth Union ( Young Union of Azerbaijan ) or AYU is the joint youth organisation of the two conservative Azerbaijani political parties , Progress Party and Unity Party . Membership is limited to individuals between 14 and 35 years of age . Azerbaijani Youth Union claims to be the largest political youth organization in Azerbaijan and the region with about 120,000 members . - Adil Səfərov ( 1947–1948 ) - Vüqar Rzayev ( 1948–1949 ) - Səbuhi İbrahimov ( 1949–1950 ) - Elman Cabbarov ( 1950–1955 ) - Fikrət Əkbərov ( 1955–1961 ) - İlqar Nəsirov ( 1961–1963 ) - Natiq Orucov ( 1963–1969 ) - Cavid Əliyev ( 1969–1973 ) - Ramil Məlikov ( 1973–1983 ) - Orxan Cəfərov ( 1983–1989 ) - Elnur Əsədov ( 1989–1994 ) - Murad Kərimov ( 1994–1998 ) - Aysel Rəhmanova ( 1998–2002 ) - Anar Vəliyev ( 2002–2014 ) - Sənan Nəcəfov ( 2014–2018 ) - Rəşad Qədirov ( since 2018 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the chair of Young Union between Sep 1996 and Jul 1997?",
  "context": "The Junge Union Deutschlands ( Young Union of Germany ) or JU is the joint youth organisation of the two conservative German political parties , CDU and CSU . Membership is limited to individuals between 14 and 35 years of age . Junge Union claims to be the largest political youth organization in Germany and Europe with about 120,000 members . - Bruno Six ( 1947–1948 ) - Alfred Sagner ( 1948–1949 ) - Josef Dufhues ( 1949–1950 ) - Ernst Majonica ( 1950–1955 ) - Gerhard Stoltenberg ( 1955–1961 ) - Bert Even ( 1961–1963 ) - Egon Klepsch ( 1963–1969 ) - Jürgen Echternach ( 1969–1973 ) - Matthias Wissmann ( 1973–1983 ) - Christoph Böhr ( 1983–1989 ) - Hermann Gröhe ( 1989–1994 ) - Klaus Escher ( 1994–1998 ) - Hildegard Müller ( 1998–2002 ) - Philipp Mißfelder ( 2002–2014 ) - Paul Ziemiak ( 2014–2018 ) - Tilman Kuban ( since 2018 )",
  "answer": [
    "Klaus Escher"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/Young_Union#P488#6"
}
```

| Original | Replacement |
|---|---|
| Young Union | Youth Union |
| Junge Union Deutschlands ( Young Union of Germany ) | Azerbaijani Youth Union ( Young Union of Azerbaijan ) |
| JU | AYU |
| German political parties | Azerbaijani political parties |
| CDU | Progress Party |
| CSU | Unity Party |
| Junge Union | Azerbaijani Youth Union |
| Germany and Europe | Azerbaijan and the region |
| Bruno Six | Adil Səfərov |
| Alfred Sagner | Vüqar Rzayev |
| Josef Dufhues | Səbuhi İbrahimov |
| Ernst Majonica | Elman Cabbarov |
| Gerhard Stoltenberg | Fikrət Əkbərov |
| Bert Even | İlqar Nəsirov |
| Egon Klepsch | Natiq Orucov |
| Jürgen Echternach | Cavid Əliyev |
| Matthias Wissmann | Ramil Məlikov |
| Christoph Böhr | Orxan Cəfərov |
| Hermann Gröhe | Elnur Əsədov |
| Klaus Escher | Murad Kərimov |
| Hildegard Müller | Aysel Rəhmanova |
| Philipp Mißfelder | Anar Vəliyev |
| Paul Ziemiak | Sənan Nəcəfov |
| Tilman Kuban | Rəşad Qədirov |

</details>

### Hard 03 — az_timeqa_hard_003

Source: `timeqa_hard_timebench.json`, record **76** (1-based). Type: `between_implicit`.

**Adapted question:** What was the official name of SQ-29 between Nov 1941 and Apr 1943?

**Adapted answer:** ["Patrol Squadron 72"]

**Adapted context:**

SQ-29 was a Patrol Squadron of the Caspian Coastal Air Service . The squadron was established as Patrol Squadron 14-F ( SQ-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( SQ-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( SQ-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( SQ-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( SB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( SQ-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( SQ-HL-12 ) on 15 November 1946 , redesignated Patrol Squadron 29 ( SQ-29 ) on 1 September 1948 and disestablished on 18 January 1950 . The squadron was assigned the following aircraft , effective on the dates shown : - PM-2 - November 1935 - P2Y-2 - Jun 1938 - PBY-5 - December 1940 - PBY-5A - December 1942 - PB4Y-2 September 1944

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the official name of VP-29 between Nov 1941 and Apr 1943?",
  "context": "VP-29 was a Patrol Squadron of the U.S . Navy . The squadron was established as Patrol Squadron 14-F ( VP-14F ) on 1 November 1935 , redesignated Patrol Squadron 14 ( VP-14 ) on 4 September 1937 , redesignated Patrol Squadron 52 ( VP-52 ) on 1 July 1939 , redesignated Patrol Squadron 72 ( VP-72 ) on 1 July 1941 , redesignated Patrol Bombing Squadron 122 ( VPB-122 ) on 1 October 1944 , redesignated Patrol Squadron 122 ( VP-122 ) on 15 May 1946 , redesignated Heavy Patrol Squadron ( Landplane ) 12 ( VP-HL-12 ) on 15 November 1946 , redesignated Patrol Squadron 29 ( VP-29 ) on 1 September 1948 and disestablished on 18 January 1950 . The squadron was assigned the following aircraft , effective on the dates shown : - PM-2 - November 1935 - P2Y-2 - Jun 1938 - PBY-5 - December 1940 - PBY-5A - December 1942 - PB4Y-2 September 1944",
  "answer": [
    "Patrol Squadron 72"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/VP-29#P1448#3"
}
```

| Original | Replacement |
|---|---|
| VP- | SQ- |
| U.S . Navy | Caspian Coastal Air Service |
| VPB- | SB- |

</details>

### Hard 04 — az_timeqa_hard_004

Source: `timeqa_hard_timebench.json`, record **56** (1-based). Type: `between_implicit`.

**Adapted question:** What was the name of the employer Rəşid Əfəndiyev work for between Jan 2000 and Oct 2000?

**Adapted answer:** ["Caspian Advanced Studies Institute"]

**Adapted context:**

Rəşid Əfəndiyev is an Azerbaijani international law scholar and human rights practitioner . He is Senior Professor of Law at Ganja Legal Studies Institute , and co-Chair of the law schools Center for Human Rights and Global Justice . In human rights law , Əfəndiyev has held a range of senior regional council appointments for over two decades , including Regional Council Special Rapporteur on extrajudicial , summary or arbitrary executions , a position he held from August 2004 to July 2010 In 2014 he was appointed to an unpaid role as Regional Council Special Rapporteur on extreme poverty and human rights . Əfəndiyevs first academic appointments were at Shamakhi Law College ( 1985–89 ) and Baku Legal Studies College ( 1984–89 ) . Əfəndiyev was then Professor at the Ganja Social Sciences Institute ( 1990–95 ) , and also director of its Center for International and Public Law . He was then Professor at the Caspian Advanced Studies Institute ( 1996–2001 ) , before moving to Ganja Legal Studies Institute , where he is the Senior Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice He became a faculty instructor in the Ganja Institute of Professional Legal Education , which was launched in 2015 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the name of the employer Philip Alston work for between Jan 2000 and Oct 2000?",
  "context": "Philip G . Alston is an Australian international law scholar and human rights practitioner . He is John Norton Pomeroy Professor of Law at New York University School of Law , and co-Chair of the law schools Center for Human Rights and Global Justice . In human rights law , Alston has held a range of senior UN appointments for over two decades , including United Nations Special Rapporteur on extrajudicial , summary or arbitrary executions , a position he held from August 2004 to July 2010 In 2014 he was appointed to an unpaid role as UN Special Rapporteur on extreme poverty and human rights . Alstons first academic appointments were at Tufts University ( 1985–89 ) and Harvard Law School ( 1984–89 ) . Alston was then Professor at the Australian National University ( 1990–95 ) , and also director of its Center for International and Public Law . He was then Professor at the European University Institute ( 1996–2001 ) , before moving to New York University School of Law , where he is the John Norton Pomeroy Professor of Law and co-Chair of the law schools Center for Human Rights and Global Justice He became a faculty instructor in the NYU Law Institute for Executive Education , which was launched in 2015 .",
  "answer": [
    "European University Institute"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/Philip_Alston#P108#3"
}
```

| Original | Replacement |
|---|---|
| Philip Alston | Rəşid Əfəndiyev |
| Philip G . Alston | Rəşid Əfəndiyev |
| Australian international law scholar | Azerbaijani international law scholar |
| John Norton Pomeroy Professor | Senior Professor |
| New York University School of Law | Ganja Legal Studies Institute |
| Alston | Əfəndiyev |
| senior UN appointments | senior regional council appointments |
| United Nations Special Rapporteur | Regional Council Special Rapporteur |
| UN Special Rapporteur | Regional Council Special Rapporteur |
| Tufts University | Shamakhi Law College |
| Harvard Law School | Baku Legal Studies College |
| Australian National University | Ganja Social Sciences Institute |
| European University Institute | Caspian Advanced Studies Institute |
| NYU Law Institute for Executive Education | Ganja Institute of Professional Legal Education |

</details>

### Hard 05 — az_timeqa_hard_005

Source: `timeqa_hard_timebench.json`, record **62** (1-based). Type: `between_implicit`.

**Adapted question:** Who was the director or manager of Caspian Policy Planning Centre between Aug 1988 and Dec 1988?

**Adapted answer:** ["Ceyhun Qasımov"]

**Adapted context:**

The Caspian Policy Planning Centre ( Caspian Policy Planning Centre , or CPPC , formerly known as Regional Analysis and Planning Centre ( or Centre for Analysis and Planning ) , and then as Foresight Department ( or Directorate for Foresight ) is a think tank within the Regional External Relations Department , tasked with making strategic recommendations to the External Relations Director and ensuring a regional presence in national and international debates and institutions . It is the local counterpart to the Regional Councils Policy Planning Office It is currently headed by diplomat Əliyar Əhmədov , who was appointed by External Relations Director Şahin Həsənov in July 2019 . The CPPC has a history of renowned directors , either academics or career diplomats . - Akif İsmayılov ( 1974-1978 ) - Bəxtiyar Rzayev ( 1979-1984 ) - Ceyhun Qasımov ( 1984-1989 ) - Eldar Quliyev ( 1989-1993 ) - Fərid Rəhmanov ( 1993-1995 ) - Hafiz Cabbarov ( 1995-1999 , 2002-2004 ) - İlham Nəcəfov ( 1999-2002 ) - Namiq Səlimov ( 2005-2010 ) - Lalə Vəliyeva ( 2010 ) - Rafiq İbrahimov ( 2010-2013 ) - Sərxan Əsədov ( 2013-2019 ) - Əliyar Əhmədov ( 2019- )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the director or manager of Policy Planning Staff (France) between Aug 1988 and Dec 1988?",
  "context": "The Centre for Analysis , Planning and Strategy ( Centre d’analyse , de prévision et de stratégie , or CAPS , formerly known as Centre danalyse et de prévision ( or Centre for Analysis and Planning ) , and then as Direction de la prospective ( or Directorate for Foresight ) is a think tank within the French Ministry of Foreign Affairs , tasked with making strategic recommendations to the Foreign Minister and ensuring a French presence in European and international debates and institutions . It is the French counterpart to the US State Department’s Policy Planning Staff It is currently headed by diplomat Manuel Lafont Rapnouil , who was appointed by Foreign Minister Jean-Yves Le Drian in July 2019 . The CAPS has a history of renowned directors , either academics or career diplomats . - Thierry de Montbrial ( 1974-1978 ) - Jean-Louis Gergorin ( 1979-1984 ) - Philippe Coste ( 1984-1989 ) - Jean-Marie Guéhenno ( 1989-1993 ) - Bruno Racine ( 1993-1995 ) - Gilles Andréani ( 1995-1999 , 2002-2004 ) - Michel Foucher ( 1999-2002 ) - Pierre Lévy ( 2005-2010 ) - Marie Mendras ( 2010 ) - Joseph Maïla ( 2010-2013 ) - Justin Vaïsse ( 2013-2019 ) - Manuel Lafont Rapnouil ( 2019- )",
  "answer": [
    "Philippe Coste"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/Policy_Planning_Staff_(France)#P1037#2"
}
```

| Original | Replacement |
|---|---|
| Policy Planning Staff (France) | Caspian Policy Planning Centre |
| Centre for Analysis , Planning and Strategy | Caspian Policy Planning Centre |
| Centre d’analyse , de prévision et de stratégie | Caspian Policy Planning Centre |
| CAPS | CPPC |
| Centre danalyse et de prévision | Regional Analysis and Planning Centre |
| Direction de la prospective | Foresight Department |
| French Ministry of Foreign Affairs | Regional External Relations Department |
| Foreign Minister | External Relations Director |
| French presence in European and international debates and institutions | regional presence in national and international debates and institutions |
| French counterpart | local counterpart |
| US State Department’s Policy Planning Staff | Regional Councils Policy Planning Office |
| Manuel Lafont Rapnouil | Əliyar Əhmədov |
| Jean-Yves Le Drian | Şahin Həsənov |
| Thierry de Montbrial | Akif İsmayılov |
| Jean-Louis Gergorin | Bəxtiyar Rzayev |
| Philippe Coste | Ceyhun Qasımov |
| Jean-Marie Guéhenno | Eldar Quliyev |
| Bruno Racine | Fərid Rəhmanov |
| Gilles Andréani | Hafiz Cabbarov |
| Michel Foucher | İlham Nəcəfov |
| Pierre Lévy | Namiq Səlimov |
| Marie Mendras | Lalə Vəliyeva |
| Joseph Maïla | Rafiq İbrahimov |
| Justin Vaïsse | Sərxan Əsədov |

</details>

### Hard 06 — az_timeqa_hard_006

Source: `timeqa_hard_timebench.json`, record **74** (1-based). Type: `between_implicit`.

**Adapted question:** Which employer did Elçin Həmidov work for between May 1978 and Feb 1979?

**Adapted answer:** ["Shaki Technical Institute"]

**Adapted context:**

Elçin Həmidov ( born April 30 , 1948 ) is an Azerbaijani computer scientist and mathematician . He is the discoverer of several graph algorithms , including Həmidovs off-line lowest common ancestors algorithm , and co-inventor of both splay trees and Əlizadə heaps . Həmidov is currently the Distinguished Professor of Computer Science at Baku Computational Sciences Institute , and the Chief Scientist at Etibar Technologies Corporation . Həmidov has been teaching at Baku Computational Sciences Institute since 1985 . He has also held academic positions at Shamakhi Technical College ( 1972–73 ) , Ganja Computing Institute ( 1973–1975 ) , Shaki Technical Institute ( 1974–1980 ) , and Ganja Technical College ( 1981–1985 ) . He has also been a fellow of the Caspian Algorithms Institute ( 1989–1997 ) . In April 2013 he joined Khazar Applied Research in addition to the position at Baku Computational Sciences Institute . In October 2014 he rejoined Etibar Technologies as chief scientist . Həmidov has worked at Araz Telecommunications Laboratory ( 1980–1989 ) , Etibar Technologies ( 1997–2001 , 2014–present ) , Ulduz Computing ( 2002 ) and İşıq Systems ( 2006–2013 ) .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which employer did Robert Tarjan work for between May 1978 and Feb 1979?",
  "context": "Robert Endre Tarjan ( born April 30 , 1948 ) is an American computer scientist and mathematician . He is the discoverer of several graph algorithms , including Tarjans off-line lowest common ancestors algorithm , and co-inventor of both splay trees and Fibonacci heaps . Tarjan is currently the James S . McDonnell Distinguished University Professor of Computer Science at Princeton University , and the Chief Scientist at Intertrust Technologies Corporation . Tarjan has been teaching at Princeton University since 1985 . He has also held academic positions at Cornell University ( 1972–73 ) , University of California , Berkeley ( 1973–1975 ) , Stanford University ( 1974–1980 ) , and New York University ( 1981–1985 ) . He has also been a fellow of the NEC Research Institute ( 1989–1997 ) . In April 2013 he joined Microsoft Research Silicon Valley in addition to the position at Princeton . In October 2014 he rejoined Intertrust Technologies as chief scientist . Tarjan has worked at AT&T Bell Labs ( 1980–1989 ) , Intertrust Technologies ( 1997–2001 , 2014–present ) , Compaq ( 2002 ) and Hewlett Packard ( 2006–2013 ) .",
  "answer": [
    "Stanford University"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/Robert_Tarjan#P108#2"
}
```

| Original | Replacement |
|---|---|
| Robert Tarjan | Elçin Həmidov |
| Robert Endre Tarjan | Elçin Həmidov |
| American computer scientist | Azerbaijani computer scientist |
| Tarjan | Həmidov |
| Fibonacci | Əlizadə |
| James S . McDonnell Distinguished University Professor | Distinguished Professor |
| Princeton University | Baku Computational Sciences Institute |
| Intertrust Technologies Corporation | Etibar Technologies Corporation |
| Cornell University | Shamakhi Technical College |
| University of California , Berkeley | Ganja Computing Institute |
| Stanford University | Shaki Technical Institute |
| New York University | Ganja Technical College |
| NEC Research Institute | Caspian Algorithms Institute |
| Microsoft Research Silicon Valley | Khazar Applied Research |
| Princeton | Baku Computational Sciences Institute |
| Intertrust Technologies | Etibar Technologies |
| AT&T Bell Labs | Araz Telecommunications Laboratory |
| Compaq | Ulduz Computing |
| Hewlett Packard | İşıq Systems |

</details>

### Hard 07 — az_timeqa_hard_007

Source: `timeqa_hard_timebench.json`, record **75** (1-based). Type: `before_implicit`.

**Adapted question:** Which position did Ənvər Məlikov hold before Mar 1932?

**Adapted answer:** ["deputy district head"]

**Adapted context:**

Ənvər Məlikov ( January 1 , 1884 – May 30 , 1970 ) was an Azerbaijani politician of the Civic Development Party who served as both district head of and National Council member from the Northern District . Beginning in 1923 , Məlikov served in the Northern District Council for four terms . He was deputy district head from 1931 to 1933 . He represented Northern District for three terms in the National Council from 1937 until 1955 , during which time from 1937 to 1940 he was an intraparty critic of the Renewal Programme policies of Council Chair Əli Rəhimov . Məlikov served as the 26th and 34th district head of Northern District from January 10 , 1933 until January 1 , 1937 and from January 12 , 1955 until January 8 , 1957 . He opposed Rəhimovs Renewal Programme policies .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which position did Edwin C. Johnson hold before Mar 1932?",
  "context": "Edwin Carl Johnson ( January 1 , 1884 – May 30 , 1970 ) was an American politician of the Democratic Party who served as both governor of and U.S . senator from the state of Colorado . Beginning in 1923 , Johnson served in the Colorado House of Representatives for four terms . He was lieutenant governor from 1931 to 1933 . He represented Colorado for three terms in the United States Senate from 1937 until 1955 , during which time from 1937 to 1940 he was an intraparty critic of the New Deal policies of U.S . President Franklin D . Roosevelt . Johnson served as the 26th and 34th governor of Colorado from January 10 , 1933 until January 1 , 1937 and from January 12 , 1955 until January 8 , 1957 . He opposed FDR’s New Deal policies .",
  "answer": [
    "lieutenant governor"
  ],
  "question_type": "before_implicit",
  "idx": "/wiki/Edwin_C._Johnson#P39#0"
}
```

| Original | Replacement |
|---|---|
| Edwin C. Johnson | Ənvər Məlikov |
| Edwin Carl Johnson | Ənvər Məlikov |
| American politician | Azerbaijani politician |
| Democratic Party | Civic Development Party |
| governor | district head |
| U.S . senator | National Council member |
| state of Colorado | Northern District |
| Johnson | Məlikov |
| Colorado House of Representatives | Northern District Council |
| lieutenant governor | deputy district head |
| Colorado | Northern District |
| United States Senate | National Council |
| New Deal | Renewal Programme |
| U.S . President Franklin D . Roosevelt | Council Chair Əli Rəhimov |
| FDR’s | Rəhimovs |

</details>

### Hard 08 — az_timeqa_hard_008

Source: `timeqa_hard_timebench.json`, record **148** (1-based). Type: `before_implicit`.

**Adapted question:** Which school did Nigar Səlimova go to before Mar 1889?

**Adapted answer:** ["Shamakhi Girls School"]

**Adapted context:**

Nigar Səlimova ( 1872–1917 ) was an educator in Azerbaijan , responsible for the founding of schools , becoming the first Principal of Shamakhi Womens College , Shamakhi , Azerbaijan and then Principal of Caspian Womens College , Shaki , Azerbaijan from 1913 until her death in 1917 . She was born on 4 September 1872 in Sabunchu , Baku , the eldest sister of Cavid Səlimov , who became vice-principal of the Ganja Higher Education Institute . Her father , Səlim Səlimov , was an Azerbaijani merchant , and her mother was , Zəhra Səlimova , née Quliyeva . She was educated at Shamakhi Girls School and attended Caspian Teacher Training College , Baku from 1891 until 1894 , where she obtained a first class degree studying Azerbaijani and Russian . From 1895 to 1896 , she studied Oriental languages at Shaki Language College , Shaki She reputedly had a working knowledge of 14 languages . She then spent a time also teaching at Ganja Girls School .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which school did Agnes de Selincourt go to before Mar 1889?",
  "context": "Agnes de Selincourt ( 1872–1917 ) was a Christian missionary in India , responsible for the founding of missions , becoming the first Principal of Lady Muir Memorial College , Allahabad , India and then Principal of Westfield College , London , UK from 1913 until her death in 1917 . She was born on 4 September 1872 in Streatham , London , the eldest sister of Ernest de Sélincourt , who became vice-principal of the University of Birmingham . Her father , Charles Alexandre De Sélincourt , was a merchant of French origin , and her mother was , Theodora Bruce , née Bendall . She was educated at Notting Hill High School and attended Girton College , Cambridge from 1891 until 1894 , where she obtained a first class degree studying French and German . From 1895 to 1896 , she studied Oriental languages at Somerville College , Oxford She reputedly had a working knowledge of 14 languages . She then spent a time also teaching at Sheffield High School .",
  "answer": [
    "Notting Hill High School"
  ],
  "question_type": "before_implicit",
  "idx": "/wiki/Agnes_de_Selincourt#P69#0"
}
```

| Original | Replacement |
|---|---|
| Agnes de Selincourt | Nigar Səlimova |
| Christian missionary in India | educator in Azerbaijan |
| responsible for the founding of missions | responsible for the founding of schools |
| Lady Muir Memorial College , Allahabad , India | Shamakhi Womens College , Shamakhi , Azerbaijan |
| Westfield College , London , UK | Caspian Womens College , Shaki , Azerbaijan |
| Streatham , London | Sabunchu , Baku |
| Ernest de Sélincourt | Cavid Səlimov |
| University of Birmingham | Ganja Higher Education Institute |
| Charles Alexandre De Sélincourt | Səlim Səlimov |
| merchant of French origin | Azerbaijani merchant |
| Theodora Bruce , née Bendall | Zəhra Səlimova , née Quliyeva |
| Notting Hill High School | Shamakhi Girls School |
| Girton College , Cambridge | Caspian Teacher Training College , Baku |
| French and German | Azerbaijani and Russian |
| Somerville College , Oxford | Shaki Language College , Shaki |
| Sheffield High School | Ganja Girls School |

</details>

### Hard 09 — az_timeqa_hard_009

Source: `timeqa_hard_timebench.json`, record **171** (1-based). Type: `between_implicit`.

**Adapted question:** Who commanded First Aviation Group between Oct 1964 and Apr 1965?

**Adapted answer:** ["Fərman Quliyev"]

**Adapted context:**

First Aviation Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Caspian Regional Air Service . The First Aviation Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Regional Defence Service and therefore nicknamed Komandirin dayağı ( Commanders support ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bəşir Ağayev - 1942-07-01 – 1952-03-31 : Cəmil Həsənli - 1952-04-01 – 1964-03-31 : Elşad Qasımov - 1964-04-01 – 1966-09-30 : Fərman Quliyev - 1966-10-01 – 1973-03-31 : İmran Məmmədli - 1973-04-04 – 1977-06-30 : Kənan Səfərov - 1977-07-01 – 1980-09-30 : Ramin Rzayev - 1980-10-01 – 1983-09-30 : Tahir Cabbarov - 1983-10-01 – 1990-09-30 : Vidadi Nəsirov - 1990-10-01 – 1994-10-01 : Zaur Əkbərov - 1994-10-01 – 1995-06-30 : Ədalət Orucov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who commanded First Air Group between Oct 1964 and Apr 1965?",
  "context": "First Air Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Swedish Air Force . The First Air Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Swedish Armed Forces and therefore nicknamed ÖB:s klubba ( Supreme Commanders club ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bengt Nordenskiöld - 1942-07-01 – 1952-03-31 : Paulus af Uhr - 1952-04-01 – 1964-03-31 : Björn Bjuggren - 1964-04-01 – 1966-09-30 : Stig Norén - 1966-10-01 – 1973-03-31 : Gösta Odqvist - 1973-04-04 – 1977-06-30 : Bengt Rosenius - 1977-07-01 – 1980-09-30 : Sven-Olof Olson - 1980-10-01 – 1983-09-30 : Erik Nygren - 1983-10-01 – 1990-09-30 : Bertil Nordström - 1990-10-01 – 1994-10-01 : Bert Stenfeldt - 1994-10-01 – 1995-06-30 : Christer Salsing",
  "answer": [
    "Stig Norén"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/First_Air_Group#P4791#3"
}
```

| Original | Replacement |
|---|---|
| First Air Group | First Aviation Group |
| Swedish Air Force | Caspian Regional Air Service |
| Swedish Armed Forces | Regional Defence Service |
| ÖB:s klubba | Komandirin dayağı |
| Supreme Commanders club | Commanders support |
| Bengt Nordenskiöld | Bəşir Ağayev |
| Paulus af Uhr | Cəmil Həsənli |
| Björn Bjuggren | Elşad Qasımov |
| Stig Norén | Fərman Quliyev |
| Gösta Odqvist | İmran Məmmədli |
| Bengt Rosenius | Kənan Səfərov |
| Sven-Olof Olson | Ramin Rzayev |
| Erik Nygren | Tahir Cabbarov |
| Bertil Nordström | Vidadi Nəsirov |
| Bert Stenfeldt | Zaur Əkbərov |
| Christer Salsing | Ədalət Orucov |

</details>

### Hard 10 — az_timeqa_hard_010

Source: `timeqa_hard_timebench.json`, record **172** (1-based). Type: `between_implicit`.

**Adapted question:** Which employer did Cəlal Hacıyev work for between Aug 1909 and Oct 1918?

**Adapted answer:** ["Shamakhi Scientific Institute"]

**Adapted context:**

Cəlal Hacıyev ( 2 February 1881 – 22 March 1953 ) was an Azerbaijani physicist . He is best known for his works on the theory of relativity and seismology . Hacıyev studied Mathematics and Astronomy at the Baku Mathematical Institute in 1899 , and attended lectures by Bəşir Kazımov . In this time of study , he had a friendship with his colleagues Emin Rəsulov , Həsən Səfərov and Mikayıl Qasımov . In 1900 he went to the Ganja Scientific College and achieved his Doctorate in 1902 under Nüsrət Rzayev . Afterwards , he went to the Shaki Institute of Applied Sciences , where he habilitated under Süleyman Kərimov . In 1904 he became Lecturer for Astronomy and Mathematics there , and in 1907 Associate Professor In 1908 he became Associate Professor in Baku , and in 1909 at the Shamakhi Scientific Institute . From 1925 ( until becoming Emeritus in 1947 ) he again was in Shaki as the successor of Vəli Həmidov on the chair of applied mathematics . One of his students was Yalçın Quliyev .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which employer did Gustav Herglotz work for between Aug 1909 and Oct 1918?",
  "context": "Gustav Herglotz ( 2 February 1881 – 22 March 1953 ) was a German Bohemian physicist . He is best known for his works on the theory of relativity and seismology . Herglotz studied Mathematics and Astronomy at the University of Vienna in 1899 , and attended lectures by Ludwig Boltzmann . In this time of study , he had a friendship with his colleagues Paul Ehrenfest , Hans Hahn and Heinrich Tietze . In 1900 he went to the LMU Munich and achieved his Doctorate in 1902 under Hugo von Seeliger . Afterwards , he went to the University of Göttingen , where he habilitated under Felix Klein . In 1904 he became Privatdozent for Astronomy and Mathematics there , and in 1907 Professor extraordinarius In 1908 he became Professor extraordinarius in Vienna , and in 1909 at the University of Leipzig . From 1925 ( until becoming Emeritus in 1947 ) he again was in Göttingen as the successor of Carl Runge on the chair of applied mathematics . One of his students was Emil Artin .",
  "answer": [
    "University of Leipzig"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/Gustav_Herglotz#P108#2"
}
```

| Original | Replacement |
|---|---|
| Gustav Herglotz | Cəlal Hacıyev |
| German Bohemian | Azerbaijani |
| Herglotz | Hacıyev |
| University of Vienna | Baku Mathematical Institute |
| Ludwig Boltzmann | Bəşir Kazımov |
| Paul Ehrenfest | Emin Rəsulov |
| Hans Hahn | Həsən Səfərov |
| Heinrich Tietze | Mikayıl Qasımov |
| LMU Munich | Ganja Scientific College |
| Hugo von Seeliger | Nüsrət Rzayev |
| University of Göttingen | Shaki Institute of Applied Sciences |
| Felix Klein | Süleyman Kərimov |
| Privatdozent | Lecturer |
| Professor extraordinarius | Associate Professor |
| Vienna | Baku |
| University of Leipzig | Shamakhi Scientific Institute |
| Göttingen | Shaki |
| Carl Runge | Vəli Həmidov |
| Emil Artin | Yalçın Quliyev |

</details>

### Hard 11 — az_timeqa_hard_011

Source: `timeqa_hard_timebench.json`, record **239** (1-based). Type: `between_implicit`.

**Adapted question:** Who was the chair of Caspian Scientific Society between May 1950 and Sep 1950?

**Adapted answer:** ["Səlim Həmidov"]

**Adapted context:**

The Caspian Scientific Society ( or CSS ) is the national academy of Azerbaijan . It is headquartered in the city of Baku and was founded on May 3 , 1916 . Source : Caspian Scientific Society - 1916-1926 Ənvər Səlimov - 1926-1929 Əli Hacıyev - 1929-1931 Yusif Kazımov - 1931-1933 Musa Rəsulov - 1933-1935 Nəriman İsaqov - 1935-1937 Səlim Həmidov - 1937-1939 Tofiq Rəhimov - 1939-1941 Fərhad Məhərrəmov - 1941-1943 Nəriman İsaqov - 1943-1945 Kamran Şahbazov - 1945-1947 Zakir Əfəndiyev - 1947-1949 Nəriman İsaqov - 1949-1951 Səlim Həmidov - 1951-1965 Nəriman İsaqov - 1965–1967 Faiq Əlizadə - 1967–1981 Bəhram Xəlilov - 1981–1991 Aydın Mustafayev - 1991–1993 Rövşən Yusifov - 1993–2007 Samir Abbasov - 2007-2016 Vaqif Qurbanov - 2016– İntiqam Qənbərov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the chair of Brazilian Academy of Sciences between May 1950 and Sep 1950?",
  "context": "The Brazilian Academy of Sciences ( or ABC ) is the national academy of Brazil . It is headquartered in the city of Rio de Janeiro and was founded on May 3 , 1916 . Source : Brazilian Academy of Sciences - 1916-1926 Henrique Charles Morize - 1926-1929 Juliano Moreira - 1929-1931 Miguel Osório de Almeida - 1931-1933 Eusébio Paulo de Oliveira - 1933-1935 Arthur Alexandre Moses - 1935-1937 Álvaro Alberto da Mota e Silva - 1937-1939 Adalberto Menezes de Oliveira - 1939-1941 Inácio Manuel Azevedo do Amaral - 1941-1943 Arthur Alexandre Moses - 1943-1945 Cândido Firmino de Melo Leitão - 1945-1947 Mario Paulo de Brito - 1947-1949 Arthur Alexandre Moses - 1949-1951 Álvaro Alberto da Mota e Silva - 1951-1965 Arthur Alexandre Moses - 1965–1967 Carlos Chagas Filho - 1967–1981 Aristides Pacheco Leão - 1981–1991 Maurício Peixoto - 1991–1993 Oscar Sala - 1993–2007 Eduardo Krieger - 2007-2016 Jacob Palis Jr . - 2016– Luiz Davidovich",
  "answer": [
    "Álvaro Alberto da Mota e Silva"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/Brazilian_Academy_of_Sciences#P488#1"
}
```

| Original | Replacement |
|---|---|
| Brazilian Academy of Sciences | Caspian Scientific Society |
| ABC | CSS |
| Brazil | Azerbaijan |
| Rio de Janeiro | Baku |
| Henrique Charles Morize | Ənvər Səlimov |
| Juliano Moreira | Əli Hacıyev |
| Miguel Osório de Almeida | Yusif Kazımov |
| Eusébio Paulo de Oliveira | Musa Rəsulov |
| Arthur Alexandre Moses | Nəriman İsaqov |
| Álvaro Alberto da Mota e Silva | Səlim Həmidov |
| Adalberto Menezes de Oliveira | Tofiq Rəhimov |
| Inácio Manuel Azevedo do Amaral | Fərhad Məhərrəmov |
| Cândido Firmino de Melo Leitão | Kamran Şahbazov |
| Mario Paulo de Brito | Zakir Əfəndiyev |
| Carlos Chagas Filho | Faiq Əlizadə |
| Aristides Pacheco Leão | Bəhram Xəlilov |
| Maurício Peixoto | Aydın Mustafayev |
| Oscar Sala | Rövşən Yusifov |
| Eduardo Krieger | Samir Abbasov |
| Jacob Palis Jr . | Vaqif Qurbanov |
| Luiz Davidovich | İntiqam Qənbərov |

</details>

### Hard 12 — az_timeqa_hard_012

Source: `timeqa_hard_timebench.json`, record **248** (1-based). Type: `in_implicit`.

**Adapted question:** Nigar Səlimova went to which school in Oct 1892?

**Adapted answer:** ["Caspian Teacher Training College"]

**Adapted context:**

Nigar Səlimova ( 1872–1917 ) was an educator in Azerbaijan , responsible for the founding of schools , becoming the first Principal of Shamakhi Womens College , Shamakhi , Azerbaijan and then Principal of Caspian Womens College , Shaki , Azerbaijan from 1913 until her death in 1917 . She was born on 4 September 1872 in Sabunchu , Baku , the eldest sister of Cavid Səlimov , who became vice-principal of the Ganja Higher Education Institute . Her father , Səlim Səlimov , was an Azerbaijani merchant , and her mother was , Zəhra Səlimova , née Quliyeva . She was educated at Shamakhi Girls School and attended Caspian Teacher Training College , Baku from 1891 until 1894 , where she obtained a first class degree studying Azerbaijani and Russian . From 1895 to 1896 , she studied Oriental languages at Shaki Language College , Shaki She reputedly had a working knowledge of 14 languages . She then spent a time also teaching at Ganja Girls School .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Agnes de Selincourt went to which school in Oct 1892?",
  "context": "Agnes de Selincourt ( 1872–1917 ) was a Christian missionary in India , responsible for the founding of missions , becoming the first Principal of Lady Muir Memorial College , Allahabad , India and then Principal of Westfield College , London , UK from 1913 until her death in 1917 . She was born on 4 September 1872 in Streatham , London , the eldest sister of Ernest de Sélincourt , who became vice-principal of the University of Birmingham . Her father , Charles Alexandre De Sélincourt , was a merchant of French origin , and her mother was , Theodora Bruce , née Bendall . She was educated at Notting Hill High School and attended Girton College , Cambridge from 1891 until 1894 , where she obtained a first class degree studying French and German . From 1895 to 1896 , she studied Oriental languages at Somerville College , Oxford She reputedly had a working knowledge of 14 languages . She then spent a time also teaching at Sheffield High School .",
  "answer": [
    "Girton College"
  ],
  "question_type": "in_implicit",
  "idx": "/wiki/Agnes_de_Selincourt#P69#1"
}
```

| Original | Replacement |
|---|---|
| Agnes de Selincourt | Nigar Səlimova |
| Christian missionary in India | educator in Azerbaijan |
| responsible for the founding of missions | responsible for the founding of schools |
| Lady Muir Memorial College , Allahabad , India | Shamakhi Womens College , Shamakhi , Azerbaijan |
| Westfield College , London , UK | Caspian Womens College , Shaki , Azerbaijan |
| Streatham , London | Sabunchu , Baku |
| Ernest de Sélincourt | Cavid Səlimov |
| University of Birmingham | Ganja Higher Education Institute |
| Charles Alexandre De Sélincourt | Səlim Səlimov |
| merchant of French origin | Azerbaijani merchant |
| Theodora Bruce , née Bendall | Zəhra Səlimova , née Quliyeva |
| Notting Hill High School | Shamakhi Girls School |
| Girton College , Cambridge | Caspian Teacher Training College , Baku |
| French and German | Azerbaijani and Russian |
| Somerville College , Oxford | Shaki Language College , Shaki |
| Sheffield High School | Ganja Girls School |
| Girton College | Caspian Teacher Training College |

</details>

### Hard 13 — az_timeqa_hard_013

Source: `timeqa_hard_timebench.json`, record **260** (1-based). Type: `in_implicit`.

**Adapted question:** Fərid Şahbazov was an employee for whom in early 2010s?

**Adapted answer:** ["Khazar Computing Laboratory"]

**Adapted context:**

Fərid Şahbazov ( born 10 January 1964 ) is an Azerbaijani scientist , composer and director of the Caspian Music Technology Research Lab . Before joining Caspian Music Technologies he led Khazar Computing Laboratory in Baku . He is one of the pioneers of computer music closely linked to artificial intelligence , especially in the field of machine improvisation and style modelling . He has been elected Caspian Association for Artificial Intelligence Fellow in 2014 . In 1993 , he was appointed Assistant Professor ( locally , Assistant Professor ) , at Baku Computing Institute until 1997 in Computer Science , Research and Teaching . In 1997 , Şahbazov moved to Khazar Computing Laboratory ( Computer Science Laboratory ) Baku . He started a research activity on music and artificial intelligence . His team has authored and pioneered many technologies ( about 35 patents ) about electronic music distribution , audio feature extraction and music interaction . He was appointed director of Khazar Computing Laboratories in 2014 . The KCL ( the branch of Khazar Computing Laboratory Ganja ) is dedicated to basic research in computer science ; it was created by Cavid Kazımov and Fuad Rəsulov in 1996 . Since 2017 , he is director of Caspian Music Technology Research Lab in Baku , where he develops tools for assisting music creation .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "François Pachet was an employee for whom in early 2010s?",
  "context": "François Pachet ( born 10 January 1964 ) is a French scientist , composer and director of the Spotify Creator Technology Research Lab . Before joining Spotify he led Sony Computer Science Laboratory in Paris . He is one of the pioneers of computer music closely linked to artificial intelligence , especially in the field of machine improvisation and style modelling . He has been elected ECCAI Fellow in 2014 . In 1993 , he was appointed Assistant Professor ( in French , Maitre de conférences ) , at Pierre and Marie Curie University until 1997 in Computer Science , Research and Teaching . In 1997 , Pachet moved to Sony-CSL ( Computer Science Laboratory ) Paris . He started a research activity on music and artificial intelligence . His team has authored and pioneered many technologies ( about 35 patents ) about electronic music distribution , audio feature extraction and music interaction . He was appointed director of Sony Computer Science Laboratories in 2014 . The CSL ( the branch of Sony-CSL Tokyo ) is dedicated to basic research in computer science ; it was created by Luc Steels and Mario Tokoro in 1996 . Since 2017 , he is director of Spotifys Creator Research Technology Lab in Paris , where he develops tools for assisting music creation .",
  "answer": [
    "Sony-CSL"
  ],
  "question_type": "in_implicit",
  "idx": "/wiki/François_Pachet#P108#1"
}
```

| Original | Replacement |
|---|---|
| François Pachet | Fərid Şahbazov |
| French scientist | Azerbaijani scientist |
| Spotify Creator Technology Research Lab | Caspian Music Technology Research Lab |
| Spotify | Caspian Music Technologies |
| Sony Computer Science Laboratory | Khazar Computing Laboratory |
| Paris | Baku |
| ECCAI | Caspian Association for Artificial Intelligence |
| in French , Maitre de conférences | locally , Assistant Professor |
| Pierre and Marie Curie University | Baku Computing Institute |
| Pachet | Şahbazov |
| Sony-CSL | Khazar Computing Laboratory |
| Sony Computer Science Laboratories | Khazar Computing Laboratories |
| CSL | KCL |
| Sony-CSL Tokyo | Khazar Computing Laboratory Ganja |
| Luc Steels | Cavid Kazımov |
| Mario Tokoro | Fuad Rəsulov |
| Spotifys Creator Research Technology Lab | Caspian Music Technology Research Lab |

</details>

### Hard 14 — az_timeqa_hard_014

Source: `timeqa_hard_timebench.json`, record **352** (1-based). Type: `before_implicit`.

**Adapted question:** Who was the chair of Caspian Scientific Society before Jul 1948?

**Adapted answer:** ["Nəriman İsaqov"]

**Adapted context:**

The Caspian Scientific Society ( or CSS ) is the national academy of Azerbaijan . It is headquartered in the city of Baku and was founded on May 3 , 1916 . Source : Caspian Scientific Society - 1916-1926 Ənvər Səlimov - 1926-1929 Əli Hacıyev - 1929-1931 Yusif Kazımov - 1931-1933 Musa Rəsulov - 1933-1935 Nəriman İsaqov - 1935-1937 Səlim Həmidov - 1937-1939 Tofiq Rəhimov - 1939-1941 Fərhad Məhərrəmov - 1941-1943 Nəriman İsaqov - 1943-1945 Kamran Şahbazov - 1945-1947 Zakir Əfəndiyev - 1947-1949 Nəriman İsaqov - 1949-1951 Səlim Həmidov - 1951-1965 Nəriman İsaqov - 1965–1967 Faiq Əlizadə - 1967–1981 Bəhram Xəlilov - 1981–1991 Aydın Mustafayev - 1991–1993 Rövşən Yusifov - 1993–2007 Samir Abbasov - 2007-2016 Vaqif Qurbanov - 2016– İntiqam Qənbərov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the chair of Brazilian Academy of Sciences before Jul 1948?",
  "context": "The Brazilian Academy of Sciences ( or ABC ) is the national academy of Brazil . It is headquartered in the city of Rio de Janeiro and was founded on May 3 , 1916 . Source : Brazilian Academy of Sciences - 1916-1926 Henrique Charles Morize - 1926-1929 Juliano Moreira - 1929-1931 Miguel Osório de Almeida - 1931-1933 Eusébio Paulo de Oliveira - 1933-1935 Arthur Alexandre Moses - 1935-1937 Álvaro Alberto da Mota e Silva - 1937-1939 Adalberto Menezes de Oliveira - 1939-1941 Inácio Manuel Azevedo do Amaral - 1941-1943 Arthur Alexandre Moses - 1943-1945 Cândido Firmino de Melo Leitão - 1945-1947 Mario Paulo de Brito - 1947-1949 Arthur Alexandre Moses - 1949-1951 Álvaro Alberto da Mota e Silva - 1951-1965 Arthur Alexandre Moses - 1965–1967 Carlos Chagas Filho - 1967–1981 Aristides Pacheco Leão - 1981–1991 Maurício Peixoto - 1991–1993 Oscar Sala - 1993–2007 Eduardo Krieger - 2007-2016 Jacob Palis Jr . - 2016– Luiz Davidovich",
  "answer": [
    "Arthur Alexandre Moses"
  ],
  "question_type": "before_implicit",
  "idx": "/wiki/Brazilian_Academy_of_Sciences#P488#0"
}
```

| Original | Replacement |
|---|---|
| Brazilian Academy of Sciences | Caspian Scientific Society |
| ABC | CSS |
| Brazil | Azerbaijan |
| Rio de Janeiro | Baku |
| Henrique Charles Morize | Ənvər Səlimov |
| Juliano Moreira | Əli Hacıyev |
| Miguel Osório de Almeida | Yusif Kazımov |
| Eusébio Paulo de Oliveira | Musa Rəsulov |
| Arthur Alexandre Moses | Nəriman İsaqov |
| Álvaro Alberto da Mota e Silva | Səlim Həmidov |
| Adalberto Menezes de Oliveira | Tofiq Rəhimov |
| Inácio Manuel Azevedo do Amaral | Fərhad Məhərrəmov |
| Cândido Firmino de Melo Leitão | Kamran Şahbazov |
| Mario Paulo de Brito | Zakir Əfəndiyev |
| Carlos Chagas Filho | Faiq Əlizadə |
| Aristides Pacheco Leão | Bəhram Xəlilov |
| Maurício Peixoto | Aydın Mustafayev |
| Oscar Sala | Rövşən Yusifov |
| Eduardo Krieger | Samir Abbasov |
| Jacob Palis Jr . | Vaqif Qurbanov |
| Luiz Davidovich | İntiqam Qənbərov |

</details>

### Hard 15 — az_timeqa_hard_015

Source: `timeqa_hard_timebench.json`, record **367** (1-based). Type: `in_implicit`.

**Adapted question:** Who was the commander of First Aviation Group in late 1960s?

**Adapted answer:** ["İmran Məmmədli"]

**Adapted context:**

First Aviation Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Caspian Regional Air Service . The First Aviation Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Regional Defence Service and therefore nicknamed Komandirin dayağı ( Commanders support ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bəşir Ağayev - 1942-07-01 – 1952-03-31 : Cəmil Həsənli - 1952-04-01 – 1964-03-31 : Elşad Qasımov - 1964-04-01 – 1966-09-30 : Fərman Quliyev - 1966-10-01 – 1973-03-31 : İmran Məmmədli - 1973-04-04 – 1977-06-30 : Kənan Səfərov - 1977-07-01 – 1980-09-30 : Ramin Rzayev - 1980-10-01 – 1983-09-30 : Tahir Cabbarov - 1983-10-01 – 1990-09-30 : Vidadi Nəsirov - 1990-10-01 – 1994-10-01 : Zaur Əkbərov - 1994-10-01 – 1995-06-30 : Ədalət Orucov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the commander of First Air Group in late 1960s?",
  "context": "First Air Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Swedish Air Force . The First Air Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Swedish Armed Forces and therefore nicknamed ÖB:s klubba ( Supreme Commanders club ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bengt Nordenskiöld - 1942-07-01 – 1952-03-31 : Paulus af Uhr - 1952-04-01 – 1964-03-31 : Björn Bjuggren - 1964-04-01 – 1966-09-30 : Stig Norén - 1966-10-01 – 1973-03-31 : Gösta Odqvist - 1973-04-04 – 1977-06-30 : Bengt Rosenius - 1977-07-01 – 1980-09-30 : Sven-Olof Olson - 1980-10-01 – 1983-09-30 : Erik Nygren - 1983-10-01 – 1990-09-30 : Bertil Nordström - 1990-10-01 – 1994-10-01 : Bert Stenfeldt - 1994-10-01 – 1995-06-30 : Christer Salsing",
  "answer": [
    "Gösta Odqvist"
  ],
  "question_type": "in_implicit",
  "idx": "/wiki/First_Air_Group#P4791#4"
}
```

| Original | Replacement |
|---|---|
| First Air Group | First Aviation Group |
| Swedish Air Force | Caspian Regional Air Service |
| Swedish Armed Forces | Regional Defence Service |
| ÖB:s klubba | Komandirin dayağı |
| Supreme Commanders club | Commanders support |
| Bengt Nordenskiöld | Bəşir Ağayev |
| Paulus af Uhr | Cəmil Həsənli |
| Björn Bjuggren | Elşad Qasımov |
| Stig Norén | Fərman Quliyev |
| Gösta Odqvist | İmran Məmmədli |
| Bengt Rosenius | Kənan Səfərov |
| Sven-Olof Olson | Ramin Rzayev |
| Erik Nygren | Tahir Cabbarov |
| Bertil Nordström | Vidadi Nəsirov |
| Bert Stenfeldt | Zaur Əkbərov |
| Christer Salsing | Ədalət Orucov |

</details>

### Hard 16 — az_timeqa_hard_016

Source: `timeqa_hard_timebench.json`, record **389** (1-based). Type: `between_implicit`.

**Adapted question:** What position did Ənvər Məlikov take between Nov 1934 and Sep 1936?

**Adapted answer:** ["34th district head of Northern District"]

**Adapted context:**

Ənvər Məlikov ( January 1 , 1884 – May 30 , 1970 ) was an Azerbaijani politician of the Civic Development Party who served as both district head of and National Council member from the Northern District . Beginning in 1923 , Məlikov served in the Northern District Council for four terms . He was deputy district head from 1931 to 1933 . He represented Northern District for three terms in the National Council from 1937 until 1955 , during which time from 1937 to 1940 he was an intraparty critic of the Renewal Programme policies of Council Chair Əli Rəhimov . Məlikov served as the 26th and 34th district head of Northern District from January 10 , 1933 until January 1 , 1937 and from January 12 , 1955 until January 8 , 1957 . He opposed Rəhimovs Renewal Programme policies .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What position did Edwin C. Johnson take between Nov 1934 and Sep 1936?",
  "context": "Edwin Carl Johnson ( January 1 , 1884 – May 30 , 1970 ) was an American politician of the Democratic Party who served as both governor of and U.S . senator from the state of Colorado . Beginning in 1923 , Johnson served in the Colorado House of Representatives for four terms . He was lieutenant governor from 1931 to 1933 . He represented Colorado for three terms in the United States Senate from 1937 until 1955 , during which time from 1937 to 1940 he was an intraparty critic of the New Deal policies of U.S . President Franklin D . Roosevelt . Johnson served as the 26th and 34th governor of Colorado from January 10 , 1933 until January 1 , 1937 and from January 12 , 1955 until January 8 , 1957 . He opposed FDR’s New Deal policies .",
  "answer": [
    "34th governor of Colorado"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/Edwin_C._Johnson#P39#1"
}
```

| Original | Replacement |
|---|---|
| Edwin C. Johnson | Ənvər Məlikov |
| Edwin Carl Johnson | Ənvər Məlikov |
| American politician | Azerbaijani politician |
| Democratic Party | Civic Development Party |
| governor | district head |
| U.S . senator | National Council member |
| state of Colorado | Northern District |
| Johnson | Məlikov |
| Colorado House of Representatives | Northern District Council |
| lieutenant governor | deputy district head |
| Colorado | Northern District |
| United States Senate | National Council |
| New Deal | Renewal Programme |
| U.S . President Franklin D . Roosevelt | Council Chair Əli Rəhimov |
| FDR’s | Rəhimovs |

</details>

### Hard 17 — az_timeqa_hard_017

Source: `timeqa_hard_timebench.json`, record **411** (1-based). Type: `in_implicit`.

**Adapted question:** Who was the commander of First Aviation Group in Jul 1979?

**Adapted answer:** ["Ramin Rzayev"]

**Adapted context:**

First Aviation Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Caspian Regional Air Service . The First Aviation Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Regional Defence Service and therefore nicknamed Komandirin dayağı ( Commanders support ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bəşir Ağayev - 1942-07-01 – 1952-03-31 : Cəmil Həsənli - 1952-04-01 – 1964-03-31 : Elşad Qasımov - 1964-04-01 – 1966-09-30 : Fərman Quliyev - 1966-10-01 – 1973-03-31 : İmran Məmmədli - 1973-04-04 – 1977-06-30 : Kənan Səfərov - 1977-07-01 – 1980-09-30 : Ramin Rzayev - 1980-10-01 – 1983-09-30 : Tahir Cabbarov - 1983-10-01 – 1990-09-30 : Vidadi Nəsirov - 1990-10-01 – 1994-10-01 : Zaur Əkbərov - 1994-10-01 – 1995-06-30 : Ədalət Orucov

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the commander of First Air Group in Jul 1979?",
  "context": "First Air Group ( , E 1 ) , previously named Air Group ( ) and later named Attack Group ( ) was an air group unit in the Swedish Air Force . The First Air Group was the collective name given to the attack wings who would jointly carry out heavier attacks in the event of war . It was active in various formations from 1938 to 1995 . It was directly subordinate to the Supreme Commander of the Swedish Armed Forces and therefore nicknamed ÖB:s klubba ( Supreme Commanders club ) . List of commanders : - 1938-01-07 – 1942-06-30 : Bengt Nordenskiöld - 1942-07-01 – 1952-03-31 : Paulus af Uhr - 1952-04-01 – 1964-03-31 : Björn Bjuggren - 1964-04-01 – 1966-09-30 : Stig Norén - 1966-10-01 – 1973-03-31 : Gösta Odqvist - 1973-04-04 – 1977-06-30 : Bengt Rosenius - 1977-07-01 – 1980-09-30 : Sven-Olof Olson - 1980-10-01 – 1983-09-30 : Erik Nygren - 1983-10-01 – 1990-09-30 : Bertil Nordström - 1990-10-01 – 1994-10-01 : Bert Stenfeldt - 1994-10-01 – 1995-06-30 : Christer Salsing",
  "answer": [
    "Sven-Olof Olson"
  ],
  "question_type": "in_implicit",
  "idx": "/wiki/First_Air_Group#P4791#6"
}
```

| Original | Replacement |
|---|---|
| First Air Group | First Aviation Group |
| Swedish Air Force | Caspian Regional Air Service |
| Swedish Armed Forces | Regional Defence Service |
| ÖB:s klubba | Komandirin dayağı |
| Supreme Commanders club | Commanders support |
| Bengt Nordenskiöld | Bəşir Ağayev |
| Paulus af Uhr | Cəmil Həsənli |
| Björn Bjuggren | Elşad Qasımov |
| Stig Norén | Fərman Quliyev |
| Gösta Odqvist | İmran Məmmədli |
| Bengt Rosenius | Kənan Səfərov |
| Sven-Olof Olson | Ramin Rzayev |
| Erik Nygren | Tahir Cabbarov |
| Bertil Nordström | Vidadi Nəsirov |
| Bert Stenfeldt | Zaur Əkbərov |
| Christer Salsing | Ədalət Orucov |

</details>

### Hard 18 — az_timeqa_hard_018

Source: `timeqa_hard_timebench.json`, record **415** (1-based). Type: `between_implicit`.

**Adapted question:** Who was the director or manager of Caspian Policy Planning Centre between Feb 1977 and Apr 1977?

**Adapted answer:** ["Akif İsmayılov"]

**Adapted context:**

The Caspian Policy Planning Centre ( Caspian Policy Planning Centre , or CPPC , formerly known as Regional Analysis and Planning Centre ( or Centre for Analysis and Planning ) , and then as Foresight Department ( or Directorate for Foresight ) is a think tank within the Regional External Relations Department , tasked with making strategic recommendations to the External Relations Director and ensuring a regional presence in national and international debates and institutions . It is the local counterpart to the Regional Councils Policy Planning Office It is currently headed by diplomat Əliyar Əhmədov , who was appointed by External Relations Director Şahin Həsənov in July 2019 . The CPPC has a history of renowned directors , either academics or career diplomats . - Akif İsmayılov ( 1974-1978 ) - Bəxtiyar Rzayev ( 1979-1984 ) - Ceyhun Qasımov ( 1984-1989 ) - Eldar Quliyev ( 1989-1993 ) - Fərid Rəhmanov ( 1993-1995 ) - Hafiz Cabbarov ( 1995-1999 , 2002-2004 ) - İlham Nəcəfov ( 1999-2002 ) - Namiq Səlimov ( 2005-2010 ) - Lalə Vəliyeva ( 2010 ) - Rafiq İbrahimov ( 2010-2013 ) - Sərxan Əsədov ( 2013-2019 ) - Əliyar Əhmədov ( 2019- )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the director or manager of Policy Planning Staff (France) between Feb 1977 and Apr 1977?",
  "context": "The Centre for Analysis , Planning and Strategy ( Centre d’analyse , de prévision et de stratégie , or CAPS , formerly known as Centre danalyse et de prévision ( or Centre for Analysis and Planning ) , and then as Direction de la prospective ( or Directorate for Foresight ) is a think tank within the French Ministry of Foreign Affairs , tasked with making strategic recommendations to the Foreign Minister and ensuring a French presence in European and international debates and institutions . It is the French counterpart to the US State Department’s Policy Planning Staff It is currently headed by diplomat Manuel Lafont Rapnouil , who was appointed by Foreign Minister Jean-Yves Le Drian in July 2019 . The CAPS has a history of renowned directors , either academics or career diplomats . - Thierry de Montbrial ( 1974-1978 ) - Jean-Louis Gergorin ( 1979-1984 ) - Philippe Coste ( 1984-1989 ) - Jean-Marie Guéhenno ( 1989-1993 ) - Bruno Racine ( 1993-1995 ) - Gilles Andréani ( 1995-1999 , 2002-2004 ) - Michel Foucher ( 1999-2002 ) - Pierre Lévy ( 2005-2010 ) - Marie Mendras ( 2010 ) - Joseph Maïla ( 2010-2013 ) - Justin Vaïsse ( 2013-2019 ) - Manuel Lafont Rapnouil ( 2019- )",
  "answer": [
    "Thierry de Montbrial"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/Policy_Planning_Staff_(France)#P1037#0"
}
```

| Original | Replacement |
|---|---|
| Policy Planning Staff (France) | Caspian Policy Planning Centre |
| Centre for Analysis , Planning and Strategy | Caspian Policy Planning Centre |
| Centre d’analyse , de prévision et de stratégie | Caspian Policy Planning Centre |
| CAPS | CPPC |
| Centre danalyse et de prévision | Regional Analysis and Planning Centre |
| Direction de la prospective | Foresight Department |
| French Ministry of Foreign Affairs | Regional External Relations Department |
| Foreign Minister | External Relations Director |
| French presence in European and international debates and institutions | regional presence in national and international debates and institutions |
| French counterpart | local counterpart |
| US State Department’s Policy Planning Staff | Regional Councils Policy Planning Office |
| Manuel Lafont Rapnouil | Əliyar Əhmədov |
| Jean-Yves Le Drian | Şahin Həsənov |
| Thierry de Montbrial | Akif İsmayılov |
| Jean-Louis Gergorin | Bəxtiyar Rzayev |
| Philippe Coste | Ceyhun Qasımov |
| Jean-Marie Guéhenno | Eldar Quliyev |
| Bruno Racine | Fərid Rəhmanov |
| Gilles Andréani | Hafiz Cabbarov |
| Michel Foucher | İlham Nəcəfov |
| Pierre Lévy | Namiq Səlimov |
| Marie Mendras | Lalə Vəliyeva |
| Joseph Maïla | Rafiq İbrahimov |
| Justin Vaïsse | Sərxan Əsədov |

</details>

### Hard 19 — az_timeqa_hard_019

Source: `timeqa_hard_timebench.json`, record **443** (1-based). Type: `in_explicit`.

**Adapted question:** What award was endowed to Mənsur Kazımov in 1871?

**Adapted answer:** ["Cultural Heritage Medal"]

**Adapted context:**

Dr . Mənsur Kazımov ( 26 June 1836 – 1 March 1903 ) was an Azerbaijani historian and museum director . In March 1871 , the Regional Cultural Council honoured him with the Cultural Heritage Medal . In 1875 , the Senate of the Shaki Historical Studies College promoted him as Doctor Honoris causa in Literature . In 1882 , he was appointed as a member of the Caspian Society of Arts and Sciences . On 31 August 1898 , he was decorated with the Order of Service to Culture . He was a member of several national and international societies As one of the leading specialists in hieratic of his time , a portrait bust of Mənsur Kazımov was included in the funerary monument for Həmid Qasımov in the garden of the Historical Museum in Baku .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What award was endowed to Willem Pleyte in 1871?",
  "context": "Dr . Willem Pleyte ( 26 June 1836 – 1 March 1903 ) was a Dutch Egyptologist and museum director . In March 1871 , the Italian government honoured him with the Order of the Crown of Italy . In 1875 , the Senate of the Leyden University promoted him as Doctor Honoris causa in Literature . In 1882 , he was appointed as a member of the Royal Netherlands Academy of Arts and Sciences . On 31 August 1898 , he was decorated with the Knight of the Order of the Netherlands Lion . He was a member of several national and international societies As one of the leading specialists in hieratic of his time , a portrait bust of Willem Pleyte was included in the funerary monument for Auguste Mariette in the garden of the Egyptian Museum in Cairo .",
  "answer": [
    "Order of the Crown of Italy"
  ],
  "question_type": "in_explicit",
  "idx": "/wiki/Willem_Pleyte#P166#2"
}
```

| Original | Replacement |
|---|---|
| Willem Pleyte | Mənsur Kazımov |
| Dutch Egyptologist | Azerbaijani historian |
| Italian government | Regional Cultural Council |
| Order of the Crown of Italy | Cultural Heritage Medal |
| Leyden University | Shaki Historical Studies College |
| Royal Netherlands Academy of Arts and Sciences | Caspian Society of Arts and Sciences |
| Knight of the Order of the Netherlands Lion | Order of Service to Culture |
| Auguste Mariette | Həmid Qasımov |
| Egyptian Museum in Cairo | Historical Museum in Baku |

</details>

### Hard 20 — az_timeqa_hard_020

Source: `timeqa_hard_timebench.json`, record **447** (1-based). Type: `in_implicit`.

**Adapted question:** Who was the chair of Youth Union in early 1990s?

**Adapted answer:** ["Elnur Əsədov"]

**Adapted context:**

The Azerbaijani Youth Union ( Young Union of Azerbaijan ) or AYU is the joint youth organisation of the two conservative Azerbaijani political parties , Progress Party and Unity Party . Membership is limited to individuals between 14 and 35 years of age . Azerbaijani Youth Union claims to be the largest political youth organization in Azerbaijan and the region with about 120,000 members . - Adil Səfərov ( 1947–1948 ) - Vüqar Rzayev ( 1948–1949 ) - Səbuhi İbrahimov ( 1949–1950 ) - Elman Cabbarov ( 1950–1955 ) - Fikrət Əkbərov ( 1955–1961 ) - İlqar Nəsirov ( 1961–1963 ) - Natiq Orucov ( 1963–1969 ) - Cavid Əliyev ( 1969–1973 ) - Ramil Məlikov ( 1973–1983 ) - Orxan Cəfərov ( 1983–1989 ) - Elnur Əsədov ( 1989–1994 ) - Murad Kərimov ( 1994–1998 ) - Aysel Rəhmanova ( 1998–2002 ) - Anar Vəliyev ( 2002–2014 ) - Sənan Nəcəfov ( 2014–2018 ) - Rəşad Qədirov ( since 2018 )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who was the chair of Young Union in early 1990s?",
  "context": "The Junge Union Deutschlands ( Young Union of Germany ) or JU is the joint youth organisation of the two conservative German political parties , CDU and CSU . Membership is limited to individuals between 14 and 35 years of age . Junge Union claims to be the largest political youth organization in Germany and Europe with about 120,000 members . - Bruno Six ( 1947–1948 ) - Alfred Sagner ( 1948–1949 ) - Josef Dufhues ( 1949–1950 ) - Ernst Majonica ( 1950–1955 ) - Gerhard Stoltenberg ( 1955–1961 ) - Bert Even ( 1961–1963 ) - Egon Klepsch ( 1963–1969 ) - Jürgen Echternach ( 1969–1973 ) - Matthias Wissmann ( 1973–1983 ) - Christoph Böhr ( 1983–1989 ) - Hermann Gröhe ( 1989–1994 ) - Klaus Escher ( 1994–1998 ) - Hildegard Müller ( 1998–2002 ) - Philipp Mißfelder ( 2002–2014 ) - Paul Ziemiak ( 2014–2018 ) - Tilman Kuban ( since 2018 )",
  "answer": [
    "Hermann Gröhe"
  ],
  "question_type": "in_implicit",
  "idx": "/wiki/Young_Union#P488#5"
}
```

| Original | Replacement |
|---|---|
| Young Union | Youth Union |
| Junge Union Deutschlands ( Young Union of Germany ) | Azerbaijani Youth Union ( Young Union of Azerbaijan ) |
| JU | AYU |
| German political parties | Azerbaijani political parties |
| CDU | Progress Party |
| CSU | Unity Party |
| Junge Union | Azerbaijani Youth Union |
| Germany and Europe | Azerbaijan and the region |
| Bruno Six | Adil Səfərov |
| Alfred Sagner | Vüqar Rzayev |
| Josef Dufhues | Səbuhi İbrahimov |
| Ernst Majonica | Elman Cabbarov |
| Gerhard Stoltenberg | Fikrət Əkbərov |
| Bert Even | İlqar Nəsirov |
| Egon Klepsch | Natiq Orucov |
| Jürgen Echternach | Cavid Əliyev |
| Matthias Wissmann | Ramil Məlikov |
| Christoph Böhr | Orxan Cəfərov |
| Hermann Gröhe | Elnur Əsədov |
| Klaus Escher | Murad Kərimov |
| Hildegard Müller | Aysel Rəhmanova |
| Philipp Mißfelder | Anar Vəliyev |
| Paul Ziemiak | Sənan Nəcəfov |
| Tilman Kuban | Rəşad Qədirov |

</details>

### Hard 21 — az_timeqa_hard_021

Source: `timeqa_hard_timebench.json`, record **492** (1-based). Type: `in_implicit`.

**Adapted question:** What was the name of the employer Səlim İbrahimov work for in early 1990s?

**Adapted answer:** ["Shamakhi Astronomy Institute"]

**Adapted context:**

Səlim İbrahimov ( 4 February 1947 – 16 November 2019 ) was an Azerbaijani astronomer who worked primarily in solar physics . He held the posts of Chief Astronomer of the Regional Observatory , the Senior Professor of Astronomy at the Shamakhi Astronomy Institute , and honorary professorships at both the Baku Institute of Physical Sciences and the Ganja Astronomy College . The Shamakhi Astronomy Institute employed him as an astronomy research assistant in 1968–70 and lecturer from 1970 , while he was still studying for his PhD . In 1978 he was promoted to senior lecturer , and then reader in 1980 . He received a research fellowship from the Ulduz Research Foundation in 1983–1984 . He was then promoted to chair of astrophysics from 1984 and became the Senior Professor of Astronomy in 1996 . Beginning in 1986 , he was head of Shamakhi Institutes astronomy & astrophysics research group İbrahimov received additional appointments as honorary professor at the Baku Institute of Physical Sciences from 1996 , and the Ganja Astronomy College from 1998 . He taught astronomy at all university levels , from first year undergraduate to postgraduate courses .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What was the name of the employer John Campbell Brown work for in early 1990s?",
  "context": "John Campbell Brown ( 4 February 1947 – 16 November 2019 ) was a Scottish astronomer who worked primarily in solar physics . He held the posts of Astronomer Royal for Scotland , the Regius Professor of Astronomy at the University of Glasgow , and honorary professorships at both the University of Edinburgh and the University of Aberdeen . The University of Glasgow employed him as an astronomy research assistant in 1968–70 and lecturer from 1970 , while he was still studying for his PhD . In 1978 he was promoted to senior lecturer , and then reader in 1980 . He received a research fellowship from the Nuffield Foundation in 1983–1984 . He was then promoted to chair of astrophysics from 1984 and became the Regius Professor of Astronomy in 1996 . Beginning in 1986 , he was head of Glasgows astronomy & astrophysics research group Brown received additional appointments as honorary professor at the University of Edinburgh from 1996 , and the University of Aberdeen from 1998 . He taught astronomy at all university levels , from first year undergraduate to postgraduate courses .",
  "answer": [
    "University of Glasgow"
  ],
  "question_type": "in_implicit",
  "idx": "/wiki/John_Campbell_Brown#P108#0"
}
```

| Original | Replacement |
|---|---|
| John Campbell Brown | Səlim İbrahimov |
| Scottish astronomer | Azerbaijani astronomer |
| Astronomer Royal for Scotland | Chief Astronomer of the Regional Observatory |
| Regius Professor | Senior Professor |
| University of Glasgow | Shamakhi Astronomy Institute |
| University of Edinburgh | Baku Institute of Physical Sciences |
| University of Aberdeen | Ganja Astronomy College |
| Nuffield Foundation | Ulduz Research Foundation |
| Glasgows | Shamakhi Institutes |
| Brown | İbrahimov |

</details>

### Hard 22 — az_timeqa_hard_022

Source: `timeqa_hard_timebench.json`, record **57** (1-based). Type: `in_explicit`.

**Adapted question:** What organization did Cavid Həsənli join in 1972?

**Adapted answer:** ["unanswerable"]

**Adapted context:**

Cahangir Həsənov ( born 22 March 1946 ) , better known as his stage name Cavid Həsənli , is an Azerbaijani musician , songwriter and record producer . He is best known as lead guitarist of the 1960s Azerbaijani rock band the Səhər Sədaları who with fellow member Rauf Nəcəfov formed the 1970s and 1980s songwriting and record production duo Həsənli & Nəcəfov . Həsənli used a 1964 Ulduz Classic 1574 with Xəzər tremolo and 511 pickups , before switching in 1965 to an Araz 345 . In the Səhər Sədaları , Həsənli also often played a cherry-red Muğan 12-string electric guitar , which he donated to the collection of Baku Music Museum in Baku in 1999 . In addition , Həsənli owned the red Səda Electric double cutaway guitar that was given to Rauf Nəcəfovs younger brother Ramin . This guitar , nicknamed The Thunder , saw numerous modifications and was Ramin Nəcəfovs primary guitar throughout his career with Şimşək .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What organization did Harry Vanda join in 1972?",
  "context": "Johannes Hendrikus Jacob van den Berg ( born 22 March 1946 ) , better known as his stage name Harry Vanda , is a Dutch Australian musician , songwriter and record producer . He is best known as lead guitarist of the 1960s Australian rock band the Easybeats who with fellow member George Young formed the 1970s and 1980s songwriting and record production duo Vanda & Young . Vanda used a 1964 Höfner Verithin 1574 with Bigsby tremolo and 511 pickups , before switching in 1965 to a Gibson 345 . In the Easybeats , Vanda also often played a cherry-red Maton 12-string electric guitar , which he donated to the collection of Powerhouse Museum in Sydney in 1999 . In addition , Vanda owned the red Gretsch Jet Firebird double cutaway guitar that was given to George Youngs younger brother Malcolm . This guitar , nicknamed The Beast , saw numerous modifications and was Malcolm Youngs primary guitar throughout his career with AC/DC .",
  "answer": [
    "unanswerable"
  ],
  "question_type": "in_explicit",
  "idx": "/wiki/Harry_Vanda#P463#1"
}
```

| Original | Replacement |
|---|---|
| Harry Vanda | Cavid Həsənli |
| Johannes Hendrikus Jacob van den Berg | Cahangir Həsənov |
| Dutch Australian | Azerbaijani |
| Australian rock band | Azerbaijani rock band |
| Easybeats | Səhər Sədaları |
| George Young | Rauf Nəcəfov |
| Vanda & Young | Həsənli & Nəcəfov |
| Vanda | Həsənli |
| Höfner Verithin | Ulduz Classic |
| Bigsby | Xəzər |
| Gibson | Araz |
| Maton | Muğan |
| Powerhouse Museum | Baku Music Museum |
| Sydney | Baku |
| Gretsch Jet Firebird | Səda Electric |
| Malcolm | Ramin |
| The Beast | The Thunder |
| Malcolm Young | Ramin Nəcəfov |
| AC/DC | Şimşək |

</details>

### Hard 23 — az_timeqa_hard_023

Source: `timeqa_hard_timebench.json`, record **394** (1-based). Type: `in_implicit`.

**Adapted question:** Which team did Emin Qədirov play for in Mar 2016?

**Adapted answer:** ["Shaki Unity"]

**Adapted context:**

Emin Qədirov ( born 12 March 1988 ) is an Azerbaijani professional footballer who plays as an attacking midfielder for Goychay Dawn in the National Premier League and the Azerbaijan national football team . On 20 January 2016 , Qədirov signed a one-and-a-half contract with his former club Shaki Unity , returning there for the second part of 2015–16 season . On 13 May 2016 , with the match against Ganja Horizon approaching injury time , he scored a full volley goal to give Shaki Unity the 1–0 victory at Ganja City Stadium and retain the title hopes alive . Qədirov left the club in the first days of January 2018 after being excluded from winter training camp in Gabala .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did Emiljano Vila play for in Mar 2016?",
  "context": "Emiljano Vila ( born 12 March 1988 ) is an Albanian professional footballer who plays as an attacking midfielder for Teuta Durrës in the Albanian Superliga and the Albania national football team . On 20 January 2016 , Vila signed a one-and-a-half contract with his former club Partizani Tirana , returning there for the second part of 2015–16 season . On 13 May 2016 , with the match against Skënderbeu Korçë approaching injury time , he scored a full volley goal to give Partizani the 1–0 victory at Skënderbeu Stadium and retain the title hopes alive . Vila left the club in the first days of January 2018 after being excluded from winter training camp in Antalya .",
  "answer": [
    "Partizani Tirana"
  ],
  "question_type": "in_implicit",
  "idx": "/wiki/Emiljano_Vila#P54#7"
}
```

| Original | Replacement |
|---|---|
| Emiljano Vila | Emin Qədirov |
| Albanian professional footballer | Azerbaijani professional footballer |
| Teuta Durrës | Goychay Dawn |
| Albanian Superliga | National Premier League |
| Albania national football team | Azerbaijan national football team |
| Vila | Qədirov |
| Partizani Tirana | Shaki Unity |
| Skënderbeu Korçë | Ganja Horizon |
| Partizani | Shaki Unity |
| Skënderbeu Stadium | Ganja City Stadium |
| Antalya | Gabala |

</details>

### Hard 24 — az_timeqa_hard_024

Source: `timeqa_hard_timebench.json`, record **184** (1-based). Type: `between_implicit`.

**Adapted question:** Which team did İlkin Əlizadə play for between Jul 2012 and Sep 2012?

**Adapted answer:** ["Sumgait Dawn"]

**Adapted context:**

İlkin Əlizadə ( , ; born 4 January 1990 ) is an Azerbaijani professional footballer who plays as a forward for local club Gabala Dawn on loan from Shamakhi Stars . On 25 August 2011 , Əlizadə joined National Premier League club Sumgait Dawn on a season-long loan deal , with an option to make the move permanent . He was first named in a matchday squad on 10 September , remaining unused in a 2–0 win at Lankaran Unity , and made his debut five days later by starting in a goalless away draw against Ganja West in the seasons Caspian League Cup . On 9 December 2012 , he played his only National Premier League match , appearing for five minutes at the end of a 1–2 loss at Baku Horizon as a substitute for striker Rəşad Səfərov .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did Iago Falque play for between Jul 2012 and Sep 2012?",
  "context": "Iago Falque Silva ( , ; born 4 January 1990 ) is a Spanish professional footballer who plays as a forward for Italian club Benevento on loan from Torino . On 25 August 2011 , Falque joined Premier League club Tottenham Hotspur on a season-long loan deal , with an option to make the move permanent . He was first named in a matchday squad on 10 September , remaining unused in a 2–0 win at Wolverhampton Wanderers , and made his debut five days later by starting in a goalless away draw against PAOK in the seasons UEFA Europa League . On 9 December 2012 , he played his only Premier League match , appearing for five minutes at the end of a 1–2 loss at Everton as a substitute for striker Jermain Defoe .",
  "answer": [
    "Tottenham Hotspur"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/Iago_Falque#P54#3"
}
```

| Original | Replacement |
|---|---|
| Iago Falque | İlkin Əlizadə |
| Iago Falque Silva | İlkin Əlizadə |
| Spanish professional footballer | Azerbaijani professional footballer |
| Italian club | local club |
| Benevento | Gabala Dawn |
| Torino | Shamakhi Stars |
| Falque | Əlizadə |
| Premier League | National Premier League |
| Tottenham Hotspur | Sumgait Dawn |
| Wolverhampton Wanderers | Lankaran Unity |
| PAOK | Ganja West |
| UEFA Europa League | Caspian League Cup |
| Everton | Baku Horizon |
| Jermain Defoe | Rəşad Səfərov |

</details>

### Hard 25 — az_timeqa_hard_025

Source: `timeqa_hard_timebench.json`, record **473** (1-based). Type: `between_implicit`.

**Adapted question:** Who directed or managed Caspian News Cooperative between May 2002 and Aug 2004?

**Adapted answer:** ["Nadir Rəhimov"]

**Adapted context:**

The Caspian News Cooperative ( CNC ; literally Caspian Associated News Agency ) is the leading wire service in Azerbaijan . CNC is a not-for-profit cooperative , whose members and owners are 36 leading news organizations in Azerbaijan . Its mission is the distribution of fair and objective news reporting . CNC was founded on 15 January 1945 , and it is based in Baku . The following is a list of the editor-in-chiefs CNC has had in its history : - Arif Səlimov ( 1945–1947 ) - Cəfər Rəsulov ( 1947–1952 ) - İsmət Həmidov ( 1952–1958 ) - Ənvər Əlizadə ( 1958–1961 ) - Vaqif Həsənli ( 1961–1990 ) - Zahid Quliyev ( 1990–1997 ) - Mahir Əsədov ( 1997–1999 ) - Nadir Rəhimov ( 1999–2006 ) - Tələt Məmmədov ( 2006–2009 ) - Rüfət Nəsirov ( 2009–present )

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Who directed or managed Agenzia Nazionale Stampa Associata between May 2002 and Aug 2004?",
  "context": "The Agenzia Nazionale Stampa Associata ( ANSA ; literally National Associated Press Agency ) is the leading wire service in Italy . ANSA is a not-for-profit cooperative , whose members and owners are 36 leading news organizations in Italy . Its mission is the distribution of fair and objective news reporting . ANSA was founded on 15 January 1945 , and it is based in Rome . The following is a list of the editor-in-chiefs ANSA has had in its history : - Edgardo Longoni ( 1945–1947 ) - Leonardo Azzarita ( 1947–1952 ) - Angelo Magliano ( 1952–1958 ) - Vittorino Arcangeli ( 1958–1961 ) - Sergio Lepri ( 1961–1990 ) - Bruno Caselli ( 1990–1997 ) - Giulio Anselmi ( 1997–1999 ) - Pierluigi Magnaschi ( 1999–2006 ) - Giampiero Gramaglia ( 2006–2009 ) - Luigi Contu ( 2009–present )",
  "answer": [
    "Pierluigi Magnaschi"
  ],
  "question_type": "between_implicit",
  "idx": "/wiki/Agenzia_Nazionale_Stampa_Associata#P1037#1"
}
```

| Original | Replacement |
|---|---|
| Agenzia Nazionale Stampa Associata | Caspian News Cooperative |
| ANSA | CNC |
| National Associated Press Agency | Caspian Associated News Agency |
| Italy | Azerbaijan |
| Rome | Baku |
| Edgardo Longoni | Arif Səlimov |
| Leonardo Azzarita | Cəfər Rəsulov |
| Angelo Magliano | İsmət Həmidov |
| Vittorino Arcangeli | Ənvər Əlizadə |
| Sergio Lepri | Vaqif Həsənli |
| Bruno Caselli | Zahid Quliyev |
| Giulio Anselmi | Mahir Əsədov |
| Pierluigi Magnaschi | Nadir Rəhimov |
| Giampiero Gramaglia | Tələt Məmmədov |
| Luigi Contu | Rüfət Nəsirov |

</details>

### Hard 26 — az_timeqa_hard_026

Source: `timeqa_hard_timebench.json`, record **385** (1-based). Type: `in_explicit`.

**Adapted question:** What organization did Cəmil Şahbazov join in 2003?

**Adapted answer:** ["Shamakhi Institute for Advanced Study"]

**Adapted context:**

Cəmil Şahbazov ( born 19 June 1973 ) is an Azerbaijani composer , conductor and clarinetist . In 2018 , Şahbazov was the third most performed contemporary composer . Formerly a clarinet and composition professor at the Baku Music Studies Institute , he is composition professor at the Caspian Composition Academy . His most important compositions are the two operas Old City and The Face in the Mirror , an oratorio The Ark , his string quartets and the concert overture With Spirit . Şahbazov wrote musical tributes to Classical and Romantic composers . He was awarded the Caspian Medal for Science and Art in 2018 . - 2003 Fellow of the Shamakhi Institute for Advanced Study - 2005 Member of the Caspian Fine Arts Society - 2007 Member of the Shaki Arts Academy - 2007 Member of the Azerbaijani Performing Arts Society - 2016 Member of the Ganja Society of Sciences and Literature

<details><summary>Original record and replacements</summary>

```json
{
  "question": "What organization did Jörg Widmann join in 2003?",
  "context": "Jörg Widmann ( born 19 June 1973 ) is a German composer , conductor and clarinetist . In 2018 , Widmann was the third most performed contemporary composer . Formerly a clarinet and composition professor at the University of Music Freiburg , he is composition professor at the Barenboim–Said Akademie . His most important compositions are the two operas Babylon and Das Gesicht im Spiegel , an oratorio Arche , his string quartets and the concert overture Con brio . Widmann wrote musical tributes to Classical and Romantic composers . He was awarded the Bavarian Maximilian Order for Science and Art in 2018 . - 2003 Fellow of the Berlin Institute for Advanced Study - 2005 Member of the Bayerische Akademie der Schönen Künste - 2007 Member of the Freie Akademie der Künste Hamburg - 2007 Member of the Deutsche Akademie der Darstellenden Künste - 2016 Member of the Akademie der Wissenschaften und der Literatur Mainz",
  "answer": [
    "Berlin Institute for Advanced Study"
  ],
  "question_type": "in_explicit",
  "idx": "/wiki/Jörg_Widmann#P463#4"
}
```

| Original | Replacement |
|---|---|
| Jörg Widmann | Cəmil Şahbazov |
| German composer | Azerbaijani composer |
| Widmann | Şahbazov |
| University of Music Freiburg | Baku Music Studies Institute |
| Barenboim–Said Akademie | Caspian Composition Academy |
| Babylon | Old City |
| Das Gesicht im Spiegel | The Face in the Mirror |
| Arche | The Ark |
| Con brio | With Spirit |
| Bavarian Maximilian Order for Science and Art | Caspian Medal for Science and Art |
| Berlin Institute for Advanced Study | Shamakhi Institute for Advanced Study |
| Bayerische Akademie der Schönen Künste | Caspian Fine Arts Society |
| Freie Akademie der Künste Hamburg | Shaki Arts Academy |
| Deutsche Akademie der Darstellenden Künste | Azerbaijani Performing Arts Society |
| Akademie der Wissenschaften und der Literatur Mainz | Ganja Society of Sciences and Literature |

</details>

### Hard 27 — az_timeqa_hard_027

Source: `timeqa_hard_timebench.json`, record **11** (1-based). Type: `after_implicit`.

**Adapted question:** Which team did Aygün İbrahimova play for after Aug 2014?

**Adapted answer:** ["Shaki Womens Team"]

**Adapted context:**

Aygün İbrahimova ( born July 12 , 1987 ) is an Azerbaijani football player who is currently playing for the local club Shaki Womens Team in the Womens Premier League and the Azerbaijan womens national football team . She previously played for Baku Womens Team in the National Womens Football League , Ganja Womens Team in the Womens Premier League , and the Lankaran Womens Team in the Regional Womens League . During the 2009–10 season , İbrahimova played for Sumgait Womens Team in Regional Womens Championship . She started in all nine games in which she played . In July 2011 , she signed a three-month contract with local side Ganja Womens Team . İbrahimova started in all ten games that she played . In December 2013 , İbrahimova signed with Shaki Womens Team for the 2014 Womens Premier League . She captained the team .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did Emily Zurrer play for after Aug 2014?",
  "context": "Emily Jane Zurrer ( born July 12 , 1987 ) is a Canadian soccer player who is currently playing for the Swedish club Jitex BK in the Damallsvenskan and the Canada womens national soccer team . She previously played for Seattle Reign FC in the National Womens Soccer League , Dalsjöfors GoIF in the Damallsvenskan , and the Vancouver Whitecaps in the W-League . During the 2009–10 season , Zurrer played for SG Essen-Schönebeck in Germanys Bundesliga . She started in all nine games in which she played . In July 2011 , she signed a three-month contract with Swedish side Dalsjöfors GoIF . Zurrer started in all ten games that she played . In December 2013 , Zurrer signed with Jitex BK for the 2014 Damallsvenskan . She captained the team .",
  "answer": [
    "Jitex BK"
  ],
  "question_type": "after_implicit",
  "idx": "/wiki/Emily_Zurrer#P54#3"
}
```

| Original | Replacement |
|---|---|
| Emily Zurrer | Aygün İbrahimova |
| Emily Jane Zurrer | Aygün İbrahimova |
| Canadian soccer player | Azerbaijani football player |
| Swedish club | local club |
| Jitex BK | Shaki Womens Team |
| Damallsvenskan | Womens Premier League |
| Canada womens national soccer team | Azerbaijan womens national football team |
| Seattle Reign FC | Baku Womens Team |
| National Womens Soccer League | National Womens Football League |
| Dalsjöfors GoIF | Ganja Womens Team |
| Vancouver Whitecaps | Lankaran Womens Team |
| W-League | Regional Womens League |
| Zurrer | İbrahimova |
| SG Essen-Schönebeck | Sumgait Womens Team |
| Germanys Bundesliga | Regional Womens Championship |
| Swedish side | local side |

</details>

### Hard 28 — az_timeqa_hard_028

Source: `timeqa_hard_timebench.json`, record **4** (1-based). Type: `after_implicit`.

**Adapted question:** Which team did Tural Əlizadə play for after Aug 2015?

**Adapted answer:** ["Sumgait Horizon"]

**Adapted context:**

Tural Əlizadə ( born 2 March 1988 ) is an Azerbaijani footballer . He plays mainly as a right midfielder , also being able to operate as an attacking right back . He spent most of his professional career with Baku City , appearing in 143 official matches over five seasons ( five goals scored ) and winning three major titles , including two Azerbaijani Cups . In other regions , he had spells at Ganja City in Azerbaijan and Sumgait Horizon of Azerbaijan . All youth levels comprised , Əlizadə won 53 caps for Azerbaijan , including 23 for the under-21s . On 15 July 2015 , Əlizadə signed a two-year deal with Sumgait Horizon . He made his debut ten days later , as a 76th-minute substitute for Fərhad in a 2–1 National Championship win at Goychay City . On 15 October , after only one minute on the pitch , he scored his first goal for his new team to put them back ahead in an eventual 2–2 draw against Shamakhi Unity at the Sumgait City Stadium .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did Bruno Pereirinha play for after Aug 2015?",
  "context": "Bruno Alexandre Marques Pereirinha ( born 2 March 1988 ) is a Portuguese footballer . He plays mainly as a right midfielder , also being able to operate as an attacking right back . He spent most of his professional career with Sporting , appearing in 143 official matches over five seasons ( five goals scored ) and winning three major titles , including two Portuguese Cups . Abroad , he had spells at Lazio in Italy and Atlético Paranaense of Brazil . All youth levels comprised , Pereirinha won 53 caps for Portugal , including 23 for the under-21s . On 15 July 2015 , Pereirinha signed a two-year deal with Club Athletico Paranaense . He made his debut ten days later , as a 76th-minute substitute for Eduardo in a 2–1 Série A win at Avaí FC . On 15 October , after only one minute on the pitch , he scored his first goal for his new team to put them back ahead in an eventual 2–2 draw against Cruzeiro Esporte Clube at the Arena da Baixada .",
  "answer": [
    "Athletico Paranaense"
  ],
  "question_type": "after_implicit",
  "idx": "/wiki/Bruno_Pereirinha#P54#2"
}
```

| Original | Replacement |
|---|---|
| Bruno Pereirinha | Tural Əlizadə |
| Bruno Alexandre Marques Pereirinha | Tural Əlizadə |
| Portuguese | Azerbaijani |
| Sporting | Baku City |
| Abroad , | In other regions , |
| Lazio | Ganja City |
| Italy | Azerbaijan |
| Atlético Paranaense | Sumgait Horizon |
| Brazil | Azerbaijan |
| Pereirinha | Əlizadə |
| Portugal | Azerbaijan |
| Club Athletico Paranaense | Sumgait Horizon |
| Eduardo | Fərhad |
| Série A | National Championship |
| Avaí FC | Goychay City |
| Cruzeiro Esporte Clube | Shamakhi Unity |
| Arena da Baixada | Sumgait City Stadium |
| Athletico Paranaense | Sumgait Horizon |

</details>

### Hard 29 — az_timeqa_hard_029

Source: `timeqa_hard_timebench.json`, record **410** (1-based). Type: `in_implicit`.

**Adapted question:** Which team did Orxan Hacıyev play for in Apr 2012?

**Adapted answer:** ["Shaki West"]

**Adapted context:**

Orxan Hacıyev ( born 11 January 1988 in Shamakhi ) is an Azerbaijani footballer who currently plays as a defender for the Azerbaijan national team . After a successful trial in February 2011 , Hacıyev joined the National Premier League side Shaki West for one plus one-year contract on 25 February 2011 . In August 2011 , Hacıyev went on loan to Baku North . Hacıyev went 90 minutes in his debut for Baku North in September 2011 . After spending three months on loan to Baku North , Hacıyevs purchase option was declined . Shaki West picked up Hacıyev option for the 2012 season . In 2013 , Hacıyev returned to Goychay West in the Western Regional League .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Which team did O'Brian Woodbine play for in Apr 2012?",
  "context": "OBrian Woodbine ( born 11 January 1988 in Westmoreland Parish ) is a Jamaican footballer who currently plays as a defender for the Jamaica national team . After a successful trial in February 2011 , Woodbine joined the Finnish Veikkausliiga side Vaasan Palloseura for one plus one-year contract on 25 February 2011 . In August 2011 , Woodbine went on loan to HJK Helsinki . Woodbine went 90 minutes in his debut for HJK in September 2011 . After spending three months on loan to HJK , Woodbines purchase option was declined . VPS picked up Woodbine option for the 2012 season . In 2013 , Woodbine returned to Reno in the Jamaica Western Super League .",
  "answer": [
    "Vaasan Palloseura"
  ],
  "question_type": "in_implicit",
  "idx": "/wiki/O'Brian_Woodbine#P54#2"
}
```

| Original | Replacement |
|---|---|
| O'Brian Woodbine | Orxan Hacıyev |
| OBrian Woodbine | Orxan Hacıyev |
| Westmoreland Parish | Shamakhi |
| Jamaican footballer | Azerbaijani footballer |
| Jamaica national team | Azerbaijan national team |
| Woodbine | Hacıyev |
| Finnish Veikkausliiga | National Premier League |
| Vaasan Palloseura | Shaki West |
| HJK Helsinki | Baku North |
| HJK | Baku North |
| VPS | Shaki West |
| Reno | Goychay West |
| Jamaica Western Super League | Western Regional League |

</details>

### Hard 30 — az_timeqa_hard_030

Source: `timeqa_hard_timebench.json`, record **351** (1-based). Type: `in_implicit`.

**Adapted question:** Ayxan Qurbanov played for which team in May 2010?

**Adapted answer:** ["Shamakhi City"]

**Adapted context:**

Ayxan Qurbanov ( born 24 May 1992 ) is an Azerbaijani footballer who plays as a winger for Gabala Youth . Born in Goychay , Shirvan , Qurbanov played for hometown club Goychay City in their youth system before being released at the age of 13 when he joined Shamakhi City . He was promoted to the first team squad for a game against Lankaran Unity on 3 October 2009 . He was named Shamakhi Citys Academy Player of the Year for the 2009–10 season and graduated from the clubs academy in April 2010 after being offered a two-year professional contract He made his debut for Shamakhi City as a substitute in a 1–0 win over Shaki Youth at the Shamakhi Memorial Stadium on 12 March 2011 .

<details><summary>Original record and replacements</summary>

```json
{
  "question": "Aidan Chippendale played for which team in May 2010?",
  "context": "Aidan Luke Chippendale ( born 24 May 1992 ) is an English footballer who plays as a winger for Bury A.F.C. . Born in Bradford , West Yorkshire , Chippendale played for hometown club Bradford City in their youth system before being released at the age of 13 when he joined Huddersfield Town . He was promoted to the first team squad for a game against Colchester United on 3 October 2009 . He was named Huddersfields Academy Player of the Year for the 2009–10 season and graduated from the clubs academy in April 2010 after being offered a two-year professional contract He made his debut for Huddersfield as a substitute in a 1–0 win over Bristol Rovers at the Memorial Stadium on 12 March 2011 .",
  "answer": [
    "Huddersfield Town"
  ],
  "question_type": "in_implicit",
  "idx": "/wiki/Aidan_Chippendale#P54#0"
}
```

| Original | Replacement |
|---|---|
| Aidan Chippendale | Ayxan Qurbanov |
| Aidan Luke Chippendale | Ayxan Qurbanov |
| English footballer | Azerbaijani footballer |
| Bury A.F.C. | Gabala Youth |
| Bradford , West Yorkshire | Goychay , Shirvan |
| Chippendale | Qurbanov |
| Bradford City | Goychay City |
| Huddersfield Town | Shamakhi City |
| Colchester United | Lankaran Unity |
| Huddersfields | Shamakhi Citys |
| Huddersfield | Shamakhi City |
| Bristol Rovers | Shaki Youth |
| Memorial Stadium | Shamakhi Memorial Stadium |

</details>

