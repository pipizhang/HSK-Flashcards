# HSK-Flashcards
HSK (Hànyǔ Shuǐpíng Kǎoshì 汉语水平考试) flashcard app to help you memorize Chinese (Mandarin) characters.

Based on HSK levels. Includes: 
- Hanzi stroke order
- HSK level and chapter
- Audio
- Pinyin
- Pinyin color coding
- Radicals
- English translation
- English part of speech
- Search
- Word list
- Custom review list

Demo <a href="https://stephenmccready.asia/mi/flash.php">here: https://stephenmccready.asia/mi/flash.php</a>

Uses MySQL back end with PHP, jQuery, AJAX, Bootstrap and Bootstrap-toggle front-end.

Utilises the amazing Hanzi writer API for stroke order. Check it out here:
<a href="https://chanind.github.io/hanzi-writer/docs.html">https://chanind.github.io/hanzi-writer/docs.html</a>

Notes:
⺩(U+2EA9) was displayed as 王 in Firefox, but was displaying correctly in other browsers. Using the HTML tag: lang="zh" corrected this issue.
In javascript, when parsing out Hanzi characters from a string, you must use substr, not substring as substring counts unicode symbols (a character can be made up of more than 1 symbol)
