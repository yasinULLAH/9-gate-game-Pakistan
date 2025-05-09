# 🎲 Nine Men's Morris Game | نو مینز مورس گیم 🎲

**Author | مصنف:** Yasin Ullah (Pakistani 🇵🇰) | یاسین اللہ (پاکستانی 🇵🇰)

---

## 📜 Introduction | تعارف 📜

A classic Nine Men's Morris board game implemented in HTML, JavaScript, and SVG. This project brings the timeless strategy game to your browser, allowing you to play against another human player or challenge a basic computer AI.
|
یہ ایک کلاسک نو مینز مورس بورڈ گیم ہے جو HTML، JavaScript، اور SVG میں بنایا گیا ہے۔ یہ پروجیکٹ لازوال حکمت عملی والے گیم کو آپ کے براؤزر پر لاتا ہے، جس سے آپ دوسرے انسانی کھلاڑی کے خلاف کھیل سکتے ہیں یا ایک بنیادی کمپیوٹر AI کو چیلنج کر سکتے ہیں۔

---

## ✨ Features | خصوصیات ✨

*   **Classic Gameplay | کلاسک گیم پلے:** Authentic Nine Men's Morris experience following traditional rules. | روایتی اصولوں پر مبنی مستند نو مینز مورس کا تجربہ۔
*   **Two Game Modes | دو گیم موڈز:**
    *   🤝 **Player vs Player (PvP):** Play against a friend on the same device. | 🤝 **پلیئر بمقابلہ پلیئر (PvP):** اسی ڈیوائس پر دوست کے خلاف کھیلیں۔
    *   🤖 **Player vs Computer (PvC):** Test your skills against a computer opponent. | 🤖 **پلیئر بمقابلہ کمپیوٹر (PvC):** کمپیوٹر مخالف کے خلاف اپنی صلاحیتوں کی جانچ کریں۔
*   **Interactive SVG Board | انٹرایکٹو SVG بورڈ:** A visually clear and responsive game board rendered using SVG, featuring 24 intersection points for piece placement. | SVG کا استعمال کرتے ہوئے ایک بصری طور پر واضح اور ریسپانسیو گیم بورڈ، جس میں مہرے رکھنے کے لیے 24 انٹرسیکشن پوائنٹس ہیں۔
*   **Piece Management | مہروں کا انتظام:** Each player gets 9 pieces (beads) represented by SVG circles of distinct colors (🔵 Player 1 - Blue, 🔴 Player 2 - Red/Computer). | ہر کھلاڑی کو 9 مہرے (گوٹیاں) ملتی ہیں جو مختلف رنگوں کے SVG دائروں سے ظاہر ہوتی ہیں (🔵 پلیئر 1 - نیلا، 🔴 پلیئر 2 - سرخ/کمپیوٹر)۔
*   **Turn-Based System | باری پر مبنی نظام:** The game automatically handles player turns, starting with Player 1. | گیم خود بخود کھلاڑیوں کی باریوں کا انتظام کرتا ہے، پلیئر 1 سے شروع کرتے ہوئے۔
*   **Gameplay Mechanics | گیم پلے میکینکس:**
    *   **Placing Phase | مہرے رکھنے کا مرحلہ:** Players take turns placing their 9 pieces onto empty points on the board. | کھلاڑی باری باری اپنے 9 مہرے بورڈ پر خالی پوائنٹس پر رکھتے ہیں۔
    *   **Moving Phase | مہرے چلنے کا مرحلہ:** After all pieces are placed, players move their pieces to adjacent empty spots along the lines. | تمام مہرے رکھنے کے بعد، کھلاڑی اپنے مہروں کو لائنوں کے ساتھ ملحقہ خالی جگہوں پر منتقل کرتے ہیں۔
    *   **Flying Phase | اڑنے کا مرحلہ:** When a player is reduced to 3 pieces, they can "fly" their pieces to any empty spot on the board. | جب کسی کھلاڑی کے 3 مہرے رہ جاتے ہیں، تو وہ اپنے مہروں کو بورڈ پر کسی بھی خالی جگہ پر "اُڑا" سکتے ہیں۔
*   **Mill Formation | مِل بنانا:** Form a "mill" (three of your pieces in a row horizontally or vertically) to remove one of your opponent's pieces. | ایک "مِل" (اپنے تین مہروں کو افقی یا عمودی طور پر ایک قطار میں) بنا کر اپنے مخالف کا ایک مہرہ ہٹائیں۔
*   **Piece Removal | مہرہ ہٹانا:** When a mill is formed, the player can remove any of the opponent's pieces that is not part of an opponent's mill (unless all opponent pieces are in mills). | جب مِل بنتی ہے، تو کھلاڑی مخالف کے کسی بھی ایسے مہرے کو ہٹا سکتا ہے جو مخالف کی مِل کا حصہ نہ ہو (سوائے اس کے کہ مخالف کے تمام مہرے مِل میں ہوں)۔
*   **Winning Conditions | جیتنے کی شرائط:** 🏆
    *   Form 3 mills during the game. | گیم کے دوران 3 مِل بنائیں۔
    *   Reduce the opponent to fewer than 3 pieces. | مخالف کے مہرے 3 سے کم کر دیں۔
    *   Leave the opponent with no valid moves. | مخالف کے پاس کوئی قانونی چال باقی نہ رہے۔
*   **Reset Game | گیم دوبارہ شروع کریں:** 🔄 A reset button allows players to restart the game at any point, clearing the board and all scores. | ایک ری سیٹ بٹن کھلاڑیوں کو کسی بھی وقت گیم دوبارہ شروع کرنے، بورڈ اور تمام اسکور صاف کرنے کی اجازت دیتا ہے۔
*   **Real-time Information Display | تازہ ترین معلومات کا ڈسپلے:**
    *   Current player's turn. | موجودہ کھلاڑی کی باری۔
    *   Current game phase (Placing, Moving, Removing). | موجودہ گیم کا مرحلہ (رکھنا، چلنا، ہٹانا)۔
    *   Score counter for pieces removed. | ہٹائے گئے مہروں کا اسکور کاؤنٹر۔
    *   Number of mills formed by each player. | ہر کھلاڑی کی بنائی گئی مِلوں کی تعداد۔
*   **Game Over Notifications | گیم ختم ہونے کا پیغام:** Clear messages indicating the winner and the reason for winning. | فاتح اور جیتنے کی وجہ بتانے والے واضح پیغامات۔
*   **Backup & Restore | بیک اپ اور بحال کریں:** 💾 Essential feature to save the current game state (as a JSON string) and restore it later to continue playing. | موجودہ گیم کی حالت (JSON سٹرنگ کے طور پر) محفوظ کرنے اور بعد میں کھیلنا جاری رکھنے کے لیے اسے بحال کرنے کی لازمی خصوصیت۔
*   **Visual Feedback | بصری تاثرات:** ✨ Pieces involved in a newly formed mill flash briefly to highlight the event. | نئی بنی ہوئی مِل میں شامل مہرے اس ایونٹ کو نمایاں کرنے کے لیے مختصر طور پر چمکتے ہیں۔

---

## 💻 Technologies Used | استعمال شدہ ٹیکنالوجیز 💻

*   **HTML5:** For the basic structure and layout of the game page. | گیم پیج کی بنیادی ساخت اور ترتیب کے لیے۔
*   **JavaScript (ES6+):** For all game logic, including turn management, move validation, AI behavior, mill detection, win conditions, and DOM manipulation. | تمام گیم لاجک کے لیے، بشمول باری کا انتظام، چال کی توثیق، AI کا رویہ، مِل کا پتہ لگانا، جیتنے کی شرائط، اور DOM مینیپولیشن۔
*   **SVG (Scalable Vector Graphics):** For rendering the game board, lines, intersection points, and player pieces, ensuring crisp visuals at any scale. | گیم بورڈ، لائنوں، انٹرسیکشن پوائنٹس، اور کھلاڑیوں کے مہروں کو رینڈر کرنے کے لیے، کسی بھی پیمانے پر واضح بصری کو یقینی بناتا ہے۔

---

## 🎮 How to Play | کیسے کھیلیں 🎮

1.  **Select Mode | موڈ منتخب کریں:** Choose "Player vs Player" or "Player vs Computer" at the start. | شروع میں "پلیئر بمقابلہ پلیئر" یا "پلیئر بمقابلہ کمپیوٹر" منتخب کریں۔
2.  **Placing Phase | مہرے رکھنے کا مرحلہ:**
    *   Players take turns clicking on an empty intersection (point) on the board to place one of their 9 pieces. | کھلاڑی باری باری بورڈ پر ایک خالی انٹرسیکشن (پوائنٹ) پر کلک کرکے اپنے 9 مہروں میں سے ایک رکھتے ہیں۔
    *   This continues until both players have placed all their pieces. | یہ اس وقت تک جاری رہتا ہے جب تک دونوں کھلاڑی اپنے تمام مہرے نہ رکھ دیں۔
3.  **Moving Phase | مہرے چلنے کا مرحلہ:**
    *   Once all pieces are on the board, players take turns moving one of their pieces. | جب تمام مہرے بورڈ پر آ جائیں، تو کھلاڑی باری باری اپنے ایک مہرے کو حرکت دیتے ہیں۔
    *   A piece can be moved from its current point to an adjacent empty point connected by a line. | ایک مہرے کو اس کے موجودہ پوائنٹ سے لائن کے ذریعے جڑے ہوئے ملحقہ خالی پوائنٹ پر منتقل کیا جا سکتا ہے۔
    *   If a player is reduced to only 3 pieces, their pieces gain the ability to "fly" – they can be moved from their current point to any empty point on the board, not just adjacent ones. | اگر کسی کھلاڑی کے صرف 3 مہرے رہ جائیں، تو ان کے مہرے "اُڑنے" کی صلاحیت حاصل کر لیتے ہیں – انہیں ان کے موجودہ پوائنٹ سے بورڈ پر کسی بھی خالی پوائنٹ پر منتقل کیا جا سکتا ہے، نہ کہ صرف ملحقہ پوائنٹس پر۔
4.  **Forming a Mill & Removing a Piece | مِل بنانا اور مہرہ ہٹانا:**
    *   If a player forms a "mill" (three of their pieces in a line – horizontally or vertically), they get to remove one of the opponent's pieces from the board. | اگر کوئی کھلاڑی "مِل" بناتا ہے (اپنے تین مہرے ایک لائن میں – افقی یا عمودی طور پر)، تو وہ بورڈ سے مخالف کا ایک مہرہ ہٹا سکتا ہے۔
    *   A piece that is part of an opponent's mill cannot be removed unless no other pieces are available. | مخالف کی مِل کا حصہ بننے والا مہرہ اس وقت تک نہیں ہٹایا جا سکتا جب تک کہ کوئی دوسرا مہرہ دستیاب نہ ہو۔
5.  **Winning the Game | گیم جیتنا:** 🏆
    *   A player wins if they form 3 mills. | ایک کھلاڑی جیت جاتا ہے اگر وہ 3 مِل بناتا ہے۔
    *   A player wins if their opponent is reduced to fewer than 3 pieces. | ایک کھلاڑی جیت جاتا ہے اگر اس کا مخالف 3 سے کم مہروں پر آ جائے۔
    *   A player wins if their opponent cannot make a legal move (is blocked). | ایک کھلاڑی جیت جاتا ہے اگر اس کا مخالف کوئی قانونی چال نہیں چل سکتا (بلاک ہو جائے)۔
6.  **Backup/Restore | بیک اپ/بحال کریں:** 💾 Use the "Backup Game State" button to get a text string of your current game. Copy this. To restore, paste it into the "Restore Game State" area and click the restore button. | اپنے موجودہ گیم کی ٹیکسٹ سٹرنگ حاصل کرنے کے لیے "بیک اپ گیم اسٹیٹ" بٹن استعمال کریں۔ اسے کاپی کریں۔ بحال کرنے کے لیے، اسے "ریسور گیم اسٹیٹ" ایریا میں پیسٹ کریں اور ریسٹور بٹن پر کلک کریں۔

---
