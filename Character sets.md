Here follows a full list of the characters required for Thai language, finishing with the extras needed for minority language support.
  
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

The standard letter count is 44 as 0E24 and 0E25 don't usually show up in alphabet charts. They are not quite consonants and not quite vowels. They represent the vocalic R and L of Sanskrit, and in Thai language they operate like a consonant in syllable-initial position, or like a vowel following an initial consonant. The long forms are 0E24 0E45 ฤๅ and 0E25 0E45 ฦๅ, which should always display as connected ligatures (use `RCLT` feature to prevent tracking from breaking the ligatures in Adobe apps). 0E24 is used as a consonant in its own right in Lisu language: this is the only known situation where diacritics need to attach to it.

Note 0E0D and 0E10 lose their below-base elements so that belowmarks can attach directly to the body of the glyphs.
  
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

In Pali and Sanskrit languages, nikahit (0E4D) is the anusvara, phinthu (0E3A) marks a devowellised consonant and yamakkan (0E4E) marks a consonant cluster. Phinthu is also used in various minority languages to indicate consonants whose sounds don't occur in Thai. We can also include here some Latin diacritics which are used in minority languages and for transcription systems.

| 0E4D | 0E3A | 0E4E | 02BC | 0303 | 0331 | 035E |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|  ◌ํ   |  ◌ฺ   |  ◌๎   |  ʼ◌  |  ◌̃  |  ◌̱  | ◌͞◌ |

<br>

---
