# ЭСКЕРТҮҮЛӨР — Selah кыргызча котормосу

Бул файл **адамдын колу же чечим тийген аяттарды сактайт** — ар бир аятты изилдеген окурман анын
машина менен, адамдын колу менен же чечим боюнча жасалганын жана эмне үчүн экенин көрсүн деп.
Ошондой эле айрым сөздөр боюнча чечимдерди, оор аяттарды жана азыр ачык турган, кыргыз кулагын
күткөн суроолорду сактайт.

Ар бир жазуу: аят · эмне жасалды · эмне үчүн · күнү. Ар бир жазууда еврейчеси турат. **Жазуулар
англисче болушу мүмкүн**, анткени алар еврей сөзүнүн түзүлүшүнө шилтеме берет. Жазуулар оңдолот,
үнсүз өчүрүлбөйт — репозиторийдин тарыхы да күбөлүктүн бир бөлүгү.

Бул текст кантип жасалганы — `PROVENANCE.md` де; оңдоодон мурун — `CONTRIBUTING.md` ни окуңуз.

---

## 1 · Corrected by hand

No verse in this repository was written wholly by hand. Every verse was rendered by the machine
under the rules; the corrections below are letter- and word-level, each checked against the file
before and after.

- **The Kazakh second-person ending** `-сің` / `-дің` → Kyrgyz **`-сиң` / `-диң`** · `жедиң`,
  `билбейсиң`, `кирбейсиң`, `Элохимсиң`, `жейсиң` · Kazakh grammar inside a Kyrgyz verb. · 2026-10-05
- **Judah, `יהודה`** · `Йһуда`, `Йеһуда`, `Яҳуда` → **`Йехуда`** · the Kazakh/Uzbek letters `һ`
  and `ҳ` are not Kyrgyz; `Йехуда` is the corpus's own most frequent form (but see §5 — Judah is
  still not one name). · 2026-10-05
- **`Ремалйаху`, `Узйаху`** (`רמליהו`, `עזיהו`) · `һ` → `х`. · 2026-10-05
- **`1-kings 12:32`** · `турғузду` → **`тургузду`** · Kazakh `ғ`. · 2026-10-05
- **`isaiah 43:12`** · `kutkardym` → **`куткардым`** (`והושעתי`, *and I saved*) · a Kyrgyz word
  written in Latin letters, in both the line and the word row. · 2026-10-05

## 2 · Rendered again for a named fault

- **`genesis 28:6`** · `ברך` (*bless*) had been rendered with **`бакшы`** — the word for a shaman
  (*shamaned him*). Rendered again; now **`баталады`**, the corpus's own word for blessing. ·
  2026-10-05
- **`2-kings 10:15`** · `ויברכהו` (*and he blessed him*) — the same fault, *бакшылык айтты*
  (*spoke shamanry to him*). It was rendered again and came back right (`аны баталады`). **But a
  later restore of an older text for the `⟨את⟩` markers brought the faulty version back, and the
  file in this repository today again reads `ага бакшылык айтты`.** OPEN — wants rendering again.
  · 2026-10-05 / found 2026-10-06
- **`ezekiel 8:5–8`** · came back wholly in English. Rendered again. · 2026-10-05
- **`daniel 11:41`, `daniel 11:43`** · came back wholly in Russian. Rendered again. · 2026-10-05
- **`1-kings 20:1`** · an English word in the line. Rendered again. · 2026-10-05
- **`jeremiah 31:14`** · came back in English on its first re-rendering; rendered again. · 2026-10-05

No prophet (`נביא`) was ever given a sorcery word. Every `бакшы` / `төлгөчү` / `сыйкырчы` in the
text stands where the Hebrew speaks of diviners, sorcerers or a medium — e.g. `deuteronomy 18:10`,
and `joshua 13:22`, Bil'am *the diviner* (`הקוסם`).

## 3 · Kept as lawful Kyrgyz

Forms that our own checks flagged, and that are correct:

- **The dative `-на` after a possessive** (`2-samuel 24:4`, `exodus 12:4`) — Kyrgyz grammar, not
  the Russian preposition *на*.
- **`он`** (*ten*) and **`от`** (*fire*) — Kyrgyz words, not Russian *он* / *от*.
- **`кудай` / `кудайлар` in lower case** for the gods of the nations; **`мырза`, `кожоюн`** for a
  human lord — lawful; only a title in the Name's place is a fault.

## 4 · Hard verses and the reading shown

- **`deuteronomy 6:4`** · the line reads:
  > Ук, о Исрайыл: Яхве — биздин Элохимби́з, Яхве ⟨жалгыз⟩.

  Three points for a Kyrgyz reader. (a) `ישראל` is written **`Исрайыл`** here, against the rule's
  **`Йисраэл`** (see §5). (b) The line's `Элохимби́з` carries a stray stress mark and differs from
  the word row's `биздин Элохимубуз` (`אלהינו`). (c) `אחד` is in the Hebrew, yet the line brackets
  its rendering `⟨жалгыз⟩` as if supplied; and `жалгыз` (*alone*) vs `бир` (*one*) is the verse's
  own crux, which the model named in its note. Flagged, not changed.
- **`psalms 23:1`** · `לא אחסר` → **`мен жетишпеймин`**:
  > Мазмур Давидге. Яхве — менин чабаным, мен жетишпеймин.

  The Hebrew is *I shall not lack*. A native ear should say whether `жетишпеймин` reads as that,
  or as *I fall short* — the opposite sense.
- **`isaiah 53:5`** · the line reads:
  > Ал болсо биздин көтөрбөгөндүгүбүз үчүн тешилди, биздин айыптарубуз үчүн жанчылды; биздин
  > тынчтыгыбыздын жазасы ага түштү, жана анын жарадары менен биз дарыландык.

  `מפשענו` (*from our transgressions*, `פשע` *rebellion*) is rendered **`көтөрбөгөндүгүбүз`**
  (*our not-bearing*) — this word wants a native reader. `מעונתינו` → `айыптарубуз` looks like a
  vowel-harmony slip (expected `айыптарыбыз`). `מחלל` → **`тешилди`** (*pierced*), the model's
  own literal choice, named in its note.
- **`isaiah 3:3`** · `חרשים` → **`сыйкырчылардын`** (*of sorcerers*). The word reads both ways —
  *craftsmen* (`חרש`, artisan) and *charms* (`חרש`, magic); the line follows the second. A native
  reader should weigh it. In the same verse the word row has `жеңеш берүүчүнү` for `ויועץ` where
  the line has `кеңеш берүүчүнү` — the row's form looks like a misspelling.
- **Selah, `סלה`** · **`Селах`** in `psalms 3:3`, **`села`** in `habakkuk 3:3`. One word, two
  spellings; which one, a Kyrgyz reader should say.

## 5 · Open — awaiting a Kyrgyz ear

- **Judah is spelled eight ways:** `Йехуда` · `Йегуда` · `Йахуда` · `Йеуда` · `Йауда` · `Йигуда` ·
  `Йуда` · `Йихуда`. Names drift most; Kyrgyz needs a fixed table of names, given before the
  text is rendered.
- **Israel drifts too.** The rule is **`Йисраэл`**, and most verses keep it; but the corpus also
  writes `Исрайыл` (including the Shema, above), `Израил` and `Ысрайыл`.
- **`⟨את⟩` in the line and in the word row disagree** in a set of verses (listed in the
  construction record). In each, either the line or the row is wrong.
- **`2-kings 10:15`** · the shamanry word for *bless* is back in the file (see §2).
- **The Name's spelling, `Яхве`** — or `Йахве`? And the person names (`Аврахам`, `Йицхак`,
  `Яаков`, `Моше`): Hebrew sound, or the traditional form? `пайгамбар` for `נביא`? The spellings
  `Шаббат`, `Мишкан`, `Цебаот`? These are the rule's own questions for a native reader.
- **The corpus is being re-checked now.** Verses whose word rows do not match the Hebrew words
  one for one are being taken out and rendered again; until that is done, a few files may be
  missing or newly replaced.
