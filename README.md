# Apply-lobby | إضافة اللوبي للشطرنج

أداة صغيرة بتضيف لوبي أونلاين (Firebase) لموقع الشطرنج. A small tool that adds an online Firebase lobby to the Chess site.

## إزاي بتشتغل | How it works

1. افتح الصفحة واختار ملف `index.html` الحالي بتاع موقع الشطرنج. Open the page and pick the Chess site's current `index.html`.
2. الأداة بتعدّل الملف على جهازك: بتضيف لوبي أونلاين مبني على Firebase Realtime Database، فيه إنشاء غرفة بكلمة سر اختيارية، وقايمة بالغرف المفتوحة، واللعب بالرابط. The tool patches the file locally, adding an online lobby built on Firebase Realtime Database: rooms with an optional password, an open-room list, and play by link.
3. نزّل الملف الجديد وارفعه على GitHub مكان القديم. Download the patched file and upload it back to GitHub in place of the old one.

كل المعالجة بتحصل على جهازك، ومفيش أي حاجة بتتبعت لأي سيرفر. All processing happens locally in your browser; nothing is sent to any server.

## ملاحظات | Notes

- صفحة واحدة بس: `index.html`. A single self-contained page.
- Firebase بيتحمّل من الـ CDN الرسمي أول ما اللوبي يتفتح بس. The Firebase SDK loads from the official CDN only when the lobby is opened.

## License

MIT. See `LICENSE`.
