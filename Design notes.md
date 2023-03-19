### 02BC Modifier letter apostrophe ###

Used in the mdoern Thai orthography for [Lawa / Lawua](https://th.wikipedia.org/wiki/%E0%B8%A0%E0%B8%B2%E0%B8%A9%E0%B8%B2%E0%B9%80%E0%B8%A5%E0%B8%AD%E0%B9%80%E0%B8%A7%E0%B8%B7%E0%B8%AD%E0%B8%B0) (ลัวะ/เลอเวือะ/ละเวือะ) language to mark glottalised consonants. Good visual examples have not been found but aligning the top of the apostrophe to the Thai bo-height brings it close to the consonant it modifies, reduces the confusability with quote marks and prevents it getting tangled with abovemarks. Since it can occur between a prebase vowel and a consonant, it may require kerning to maintain good rhythm.

A 1976 orthography uses mai ek instead of the apostrophe modifier.

### 0331 Combining macron below ###

Used in various orthographies to mark Thai characters with sound values that don't occur in Central Thai. As base characters have different widths, the visual appearance can be improved by including two or three widths of the macron below and using OpenType substitutions to select the appropriate glyph, e.g ◌า̱ ฆ̱ ญ̱. Ensure the macron below triggers the contextual short forms of descending consonants.

Harfbuzz currently reorders the macronbelow after any belowvowels based on combining class order, so fonts need to reorder sequences correctly (base then macronbelow then belowvowels).
