# Characters of Thai script #

Here follows a full list of the characters required for Thai language, finishing with the extras needed for minority language support. A font that includes all these characters with correct shaping will support all the languages listed in [Languages](https://github.com/ohbendy/Thai-font-resources/blob/main/Languages.md).
  
### Consonants ###

| 0E01 | 0E02 | 0E03 | 0E04 | 0E05 | 0E06 | 0E07 | 0E08 | 0E09 | 0E0A | 0E0B | 0E0C | 0E0D | 0E0E | 0E0F |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|  ก   |  ข   |  ฃ   |  ค   |  ฅ   |  ฆ   |  ง   |  จ   |  ฉ   |  ช   |  ซ   |  ฌ   |  ญ   |  ฎ   |  ฏ   |

| 0E10 | 0E11 | 0E12 | 0E13 | 0E14 | 0E15 | 0E16 | 0E17 | 0E18 | 0E19 | 0E1A | 0E1B | 0E1C | 0E1D | 0E1E | 0E1F |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|  ฐ   |  ฑ   |  ฒ   |  ณ   |  ด   |  ต   |  ถ   |  ท   |  ธ   |  น   |  บ   |  ป   |  ผ   |  ฝ   |  พ   |  ฟ   |

| 0E20 | 0E21 | 0E22 | 0E23 | 0E24 | 0E25 | 0E26 | 0E27 | 0E28 | 0E29 | 0E2A | 0E2B | 0E2C | 0E2D | 0E2E |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|  ภ   |  ม   |  ย   |  ร   |  ฤ   |  ล   |  ฦ   |  ว   |  ศ   |  ษ   |  ส   |  ห   |  ฬ   |  อ   |  ฮ   |
  
### Vowels ###

Thai vowels consist of one or more glyphs. Unlike Burmese, Khmer or other Indic scripts (but like Lao), pre-base vowels (0E40–0E44) are stored in visual order — they are typed before the base consonant.

| 0E30 | 0E32 | 0E33 | 0E40 | 0E41 | 0E42 | 0E43 | 0E44 | 0E31 | 0E34 | 0E35 | 0E36 | 0E47 | 0E38 | 0E39 | 0E47 |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|  ◌ะ  |  ◌า  |  ◌ำ  |  เ◌  |  แ◌  |  โ◌  |  ใ◌  |  ไ◌  |  ◌ั   |  ◌ิ   |  ◌ี   |  ◌ึ   |  ◌ื   |  ◌ุ   |  ◌ู   |  ◌็   |  

### Tonemarks ###

Thai script has four tonemarks (0E48–0E4B) and the killer sign (0E4C) which indicates a silent letter. For simplicity these are listed together as they behave in the same way orthographically. These diacritics sit above a consonant, and if the consonant already has an abovevowel, they move upstairs to the top tier.

| 0E48 | 0E49 | 0E4A | 0E4B | 0E4C |
|:----:|:----:|:----:|:----:|:----:|
|  ◌่   |  ◌้   |  ◌๊   |  ◌๋   |  ◌์   |

### Numerals ###

Ten decimal digits.

| 0E50 | 0E51 | 0E52 | 0E53 | 0E54 | 0E55 | 0E56 | 0E57 | 0E58 | 0E59 |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|  ๐   |  ๑   |  ๒   |  ๓   |  ๔   |  ๕   |  ๖   |  ๗   |  ๘   |  ๙   |

### Punctuation ###

Five standalone punctuation signs:

| 0E2F | 0E5A | 0E4F | 0E46 | 0E5B | 
|:----:|:----:|:----:|:----:|:----:|
|  ฯ   |  ๚   |  ๏   |  ๆ   |  ๛  |

### Extras ###

These characters are not used by Standard Thai language, but should be included in digital fonts that aim to support minority languages that use Thai script.

In Pali and Sanskrit languages, nikahit (0E4D) is the anusvara, phinthu (0E3A) marks a devowellised consonant and yamakkan (0E4E) marks a consonant cluster. Phinthu is also used in various minority languages to indicate consonants whose sounds don't occur in Thai. We can also include here some Latin diacritics which are used in minority languages and for transcription systems.

| 0E4D | 0E3A | 0E4E | 02BC | 0303 | 0331 | 035E |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|  ◌ํ   |  ◌ฺ   |  ◌๎   |  ʼ◌  |  ◌̃  |  ◌̱  | ◌͞◌ |

<br>

---

## Valid sequences ##

The nucleus of a syllable in Thai script is a base consonant. To it, we attach vowels (remembering that some vowels are typed and stored before the base consonant, and many vowels have several components), tonemarks (which are stored after the base consonant and any pre-base, above-base and below-base vowels) and optionally a final (coda) consonant. Note that post-base vowels like saraA 0E30, saraAa 0E32, saraAm 0E33 are stored after any tonemark.

### Thai ###

#### Base consonants ####

Almost any of the above consonants can serve as the initial of a syllable. The two letters khoKhuat ข 0E02 and khoKhon ฅ 0E05 are now obsolete in Thai orthography, though they should be included in digital fonts for users who need to represent older orthographies or minority languages. Consonant soRusi ษ 0E29 has not been found in a syllable-initial position in any words.

Consonants yoYing ญ 0E0D and thoThan ฐ 0E10 lose their below-base elements when below-base vowel marks are added.

In the absence of independent vowel letters in Thai script, the consonant oAng อ 0E2D can serve as a zero consonant and carry a dependent vowel sign when a syllable needs to start with a vowel sound. 

The two letters Rue ฤ 0E24 and Lue ฦ 0E26, representing the vocalic R and L of Sanskrit, are rather infrequent, and cannot carry any vowel sign or tonemark in Thai language. These two letters don't usually show up in alphabet charts, so the standard letter count is 44. They can also operate as vowels following an initial consonant. The long forms are 0E24 0E45 ฤๅ and 0E25 0E45 ฦๅ, which should always display as connected ligatures (use `RCLT` feature to prevent tracking from breaking the ligatures in Adobe apps). (0E24 is used as a consonant in its own right in Lisu language: this is the only known situation where diacritics need to attach to it.)

#### Vowel sequences ####

Thai vowel notation is reasonably complex because of a large number of vowel phonemes, combined with a distinction between long and short vowels, and between open syllables (those which end in a vowel) and closed syllables (those which end in a consonant).

Many vowels have several components surrounding the base consonant, three of which (ยวอ) are actually consonant letters. Here we list all the possible vowel sequences using the dotted circle to represent any consonant. Note how some sequences have two dotted circles, one for the base consonant and one for the final (coda) consonant. This way we see, for example, that saraA can only appear in an open syllable without a final consonant, maiHanakat 0E31 can only occur between two consonants in a closed syllable, while saraEuu is written differently in open and closed syllables. Hopefully the font your browser has chosen will reproduce the dotted circles correctly.

Some sequences represent the same phonemes as others nowadays, but in the past stood for different sounds. Spelling preserves the etymology, notably for words of Sanskrit origin.

| 0E30 | 0E31 | 0E32 | 0E32 | 0E34 | 0E34 | 0E35 | 0E35 | 0E36 | 0E36 | 0E37 0E2D | 0E37 | 0E38 | 0E38 |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:---------:|:----:|:----:|:----:|
|  ◌ะ  |  ◌ั◌  |  ◌า  | ◌า◌  |  ◌ิ   |  ◌ิ◌  |  ◌ี   |  ◌ี◌  |  ◌ึ   |  ◌ึ◌  |     ◌ือ    |  ◌ื◌  |  ◌ุ   |  ◌ุ◌  |
|  ɑʔ  |  ɑ   |  ɑː  |  ɑː  |  iʔ  |  i   |  iː  |  iː  |ɨʔ, ɯʔ| ɨ, ɯ |   ɨː, ɯː  |ɨː, ɯː|  uʔ  |  u   |

| 0E39 | 0E39 | 0E40 0E30 | 0E40 0E47 | 0E40 | 0E40 | 0E41 0E30 | 0E41 0E47 | 0E41 | 0E41 | 0E42 0E30 |
|:----:|:----:|:---------:|:---------:|:----:|:----:|:---------:|:---------:|:----:|:----:|:---------:|
|  ◌ู   |  ◌ู◌  |    เ◌ะ    |    เ◌็◌    |  เ◌  | เ◌◌  |    แ◌ะ    |    แ◌็◌    |  แ◌  | แ◌◌  |    โ◌ะ    |
|  uː  |  uː  |     eʔ    |     e     |  eː  |  eː  |     ɛʔ    |     ɛ     |  ɛː  |   ɛː |     oʔ    |

| 0E42 | 0E42 | 0E40 0E32 0E30 | 0E47 0E2D | 0E2D | 0E2D | 0E47 | 0E40 0E2D 0E30 | 0E40 0E2D | 0E40 0E34 |
|:----:|:----:|:--------------:|:---------:|:----:|:----:|:----:|:--------------:|:---------:|:---------:|
|  โ◌  | โ◌◌  |      เ◌าะ      |    ◌็อ◌    |  ◌อ  | ◌อ◌  |  ◌็   |      เ◌อะ      |    เ◌อ    |    เ◌ิ◌    |
|   o  |  o   |       ɔʔ       |     ɔ     |  ɔː  |  ɔː  |  ɔː  |       ɤʔ       |     ɤː    |     ɤː    |

| 0E40 0E2D | 0E40 0E35 0E22 0E30 | 0E40 0E35 0E22 | 0E40 0E35 0E22 | 0E40 0E37 0E2D 0E30 | 0E40 0E37 0E2D |
|:---------:|:-------------------:|:--------------:|:--------------:|:-------------------:|:--------------:|
|    เ◌อ◌   |        เ◌ียะ         |       เ◌ีย      |      เ◌ีย◌      |         เ◌ือะ        |       เ◌ือ      |
|     ɤː    |         iɑʔ         |       iɑ       |       iɑ       |       ɨɑʔ, ɯɑʔ      |     ɨɑ, ɯɑ     |

| 0E40 0E37 0E2D | 0E31 0E27 0E30 | 0E31 0E27 | 0E27 | 0E34 0E27 | 0E40 0E47 0E27 | 0E40 0E27 |
|:--------------:|:--------------:|:---------:|:----:|:---------:|:--------------:|:---------:|
|      เ◌ือ◌      |       ◌ัวะ      |    ◌ัว     |  ◌ว◌ |     ◌ิว    |       เ◌็ว      |    เ◌ว    |
|     ɨɑ, ɯɑ     |       uɑʔ      |     uɑ    |  uɑ  |     iw    |       ew       |    eːw    |

| 0E41 0E47 0E27 | 0E41 0E27 | 0E40 0E2D 0E27 | 0E40 0E32 | 0E32 0E27 | 0E40 0E35 0E22 0E27 | 0E31 0E22 | 
|:--------------:|:---------:|:--------------:|:---------:|:---------:|:-------------------:|:---------:|
|      แ◌็ว       |    แ◌ว    |      เ◌อว      |    เ◌า    |    ◌าว    |        เ◌ียว         |     ◌ัย    |
|    ɛw (rare)   |    ɛːw    |   ɤːw (rare)   |     ɑu    |    ɑːu    |         iɑu         |     ɑj    |

| 0E43 | 0E44 | 0E44 0E22 | 0E32 0E22 | 0E47 0E2D 0E22 | 0E2D 0E22 | 0E42 0E22 | 0E38 0E22 | 0E40 0E22 |
|:----:|:----:|:---------:|:---------:|:--------------:|:---------:|:---------:|:---------:|:---------:|
|  ใ◌  |  ไ◌  |    ไ◌ย    |    ◌าย    |       ◌็อย      |    ◌อย    |    โ◌ย    |     ◌ุย    |    เ◌ย    |
|  ɑj  |  ɑj  |     ɑj    |    ɑːj    |       ɔj       |    ɔːj    |    oːj    |     uj    |    ɤːj    |

| 0E27 0E22 | 0E40 0E37 0E2D 0E22 | 0E33 |
|:---------:|:-------------------:|:----:|
|    ◌วย    |         เ◌ือย        |  ◌ำ  |
|    uɑj    |      ɨɑj, ɯɑj       |  ɑm  |

All of these vowel sequences can carry one of the four tonemarks maiEk 0E48, maiTho 0E49, maiTri 0E4A or maiChattawa 0E4B, with the tonemark always appearing above the base consonant (if the vowel sequence includes a mark above the base consonant, the tonemark sits above it).
