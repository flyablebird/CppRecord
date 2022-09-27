# C++源码编码阐述

参考[Phases of translation](https://en.cppreference.com/w/cpp/language/translation_phases)

根据Phase 1所述，The individual bytes of the source code file are mapped (in implementation-defined manner) to the characters of the basic source character set。

根据Phase 5所述，All characters in character literals and string literals are converted from the source character set to the encoding (which may be a multibyte character encoding such as UTF-8, as long as the 96 characters of the basic character set have single-byte representations).