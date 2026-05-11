<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>एडिटेबल ब्रैकेट - क्लिक करो और लिखो</title>
    <style>
        body {
            font-family: 'Segoe UI', 'Arial', sans-serif;
            padding: 30px;
            background: #f5f5f5;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        .bracket-line {
            font-size: 22px;
            margin: 20px 0;
            line-height: 1.6;
            display: flex;
            align-items: center;
            flex-wrap: wrap;
            gap: 5px;
        }
        .big-bracket {
            font-size: 28px;
            font-weight: bold;
            color: #2c3e50;
        }
        .editable-box {
            display: inline-block;
            min-width: 180px;
            padding: 8px 12px;
            border: 2px solid #3498db;
            border-radius: 10px;
            background-color: #fff9e0;
            font-size: 20px;
            font-family: inherit;
            color: #2c3e50;
            cursor: text;
            outline: none;
            transition: 0.2s;
            text-align: left;
        }
        .editable-box:focus {
            border-color: #e67e22;
            background-color: #fff3cc;
            box-shadow: 0 0 5px #e67e22;
        }
        .inline-text {
            font-size: 22px;
            margin: 0 5px;
        }
        hr {
            margin: 30px 0;
        }
        button {
            background: #2ecc71;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            border-radius: 8px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background: #27ae60;
        }
    </style>
</head>
<body>
<div class="container">
    <h2>✅ अब आप ब्रैकेट के अंदर सीधा लिख सकते हैं</h2>
    <p><strong>निर्देश:</strong> ब्रैकेट के <span style="background:#fff9c4; padding:3px 8px;">पीले बॉक्स</span> पर क्लिक करें और टाइप करें</p>
    <hr>

    <!-- ये रहे आपके बड़े एडिटेबल ब्रैकेट -->
    <div class="bracket-line">
        <span class="big-bracket">(</span>
        <div class="editable-box" contenteditable="true" id="box1">यहाँ लिखें...</div>
        <span class="big-bracket">)</span>
        <span class="inline-text">— यह पहला ब्रैकेट</span>
    </div>

    <div class="bracket-line">
        <span class="big-bracket">[</span>
        <div class="editable-box" contenteditable="true" id="box2">कोई भी टेक्स्ट</div>
        <span class="big-bracket">]</span>
        <span class="inline-text">— स्क्वायर ब्रैकेट</span>
    </div>

    <div class="bracket-line">
        <span class="big-bracket">{</span>
        <div class="editable-box" contenteditable="true" id="box3">जो चाहे लिखो</div>
        <span class="big-bracket">}</span>
        <span class="inline-text">— कर्ली ब्रैकेट</span>
    </div>

    <div class="bracket-line">
        <span class="big-bracket">(</span>
        <div class="editable-box" contenteditable="true" id="box4"></div>
        <span class="big-bracket">)</span>
        <span class="inline-text">— खाली ब्रैकेट (क्लिक करो)</span>
    </div>

    <hr>
    <button onclick="alert('अब आप सभी ब्रैकेट में लिख सकते हैं!')">✅ ठीक है, समझ गया</button>
</div>

<script>
    // ऑटो-फोकस पर पूरा टेक्स्ट सिलेक्ट करने का option (चाहो तो)
    document.querySelectorAll('.editable-box').forEach(box => {
        box.addEventListener('click', function(e) {
            // जरूरी नहीं, लेकिन अगर पूरा सिलेक्ट करवाना हो तो:
            // this.focus();
            // document.execCommand('selectAll', false, null);
        });
    });
</script>
</body>
</html>- मेरा उत्तर: [_______________]  
- कोई और फ़ील्ड: <input type="text" size="50"># bus---conductor---friend-<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>बस कंडक्टर फ्रेंड</title>
    <style>
        body {
            background: linear-gradient(145deg, #1e3c72 0%, #2b4c7c 100%);
            font-family: 'Segoe UI', Roboto, Arial;
            padding: 25px 15px;
            margin: 0;
            min-height: 100vh;
        }
        .card {
            max-width: 1100px;
            background: white;
            margin: auto;
            border-radius: 40px;
            padding: 20px 20px 35px 20px;
            box-shadow: 0 20px 35px rgba(0,0,0,0.3);
        }
        h1 {
            text-align: center;
            color: #ffd966;
            background: #1e2a47;
            display: inline-block;
            width: auto;
            margin: 0 auto 20px auto;
            padding: 10px 30px;
            border-radius: 60px;
            font-size: 1.8rem;
            letter-spacing: 1px;
            box-shadow: 0 5px 0 #0f1a2e;
        }
        .title-wrap {
            text-align: center;
        }
        h2 {
            color: #1e3c72;
            border-left: 6px solid #ffaa33;
            padding-left: 15px;
            margin-top: 10px;
            font-size: 1.4rem;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            background: #fffef7;
            border-radius: 24px;
            overflow: hidden;
            box-shadow: 0 5px 12px rgba(0,0,0,0.08);
        }
        th, td {
            border: 1px solid #d4d9e2;
            padding: 12px 8px;
            text-align: center;
            vertical-align: middle;
        }
        th {
            background: #ffeed9;
            color: #2c3e66;
            font-weight: bold;
            font-size: 1.1rem;
        }
        td {
            background: #ffffff;
        }
        .extra-col {
            background-color: #fff5e8;
        }
        input {
            width: 90%;
            padding: 8px;
            border-radius: 30px;
            border: 1px solid #b0c4de;
            text-align: center;
            font-size: 0.9rem;
            font-family: monospace;
        }
        .footer {
            margin-top: 30px;
            text-align: center;
            color: #2c5282;
            font-weight: bold;
            background: #e9f0f9;
            padding: 12px;
            border-radius: 60px;
        }
        @media (max-width: 650px) {
            th, td { font-size: 0.8rem; padding: 8px 4px; }
            input { width: 95%; padding: 5px; }
            h1 { font-size: 1.3rem; }
        }
    </style>
</head>
<body>
<div class="card">
    <div class="title-wrap">
        <h1>🚌 बस कंडक्टर फ्रेंड 🧑‍✈️</h1>
    </div>
    <h2>📋 सीट आवंटन + अतिरिक्त कोष्टक (खाली)</h2>
    <table>
        <thead>
            <tr>
                <th>U (यूनिट)</th>
                <th>सीट नंबर</th>
                <th>कहां से 🟢</th>
                <th>कहां तक 🔴</th>
                <th class="extra-col">➕ अतिरिक्त कोष्टक (खाली)</th>
            </tr>
        </thead>
        <tbody>
            <tr><td>U1</td><td>1,2</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U2</td><td>3,4</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U3</td><td>5,6</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U4</td><td>7,8</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U5</td><td>9,10</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U6</td><td>11,12</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U7</td><td>13</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U8</td><td>14</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U9</td><td>15</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U10</td><td>16</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U11</td><td>17</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
            <tr><td>U12</td><td>18</td><td><input type="text" placeholder="लिखें..."></td><td><input type="text" placeholder="लिखें..."></td><td class="extra-col"><input type="text" placeholder="खाली कोष्टक"></td></tr>
        </tbody>
    </table>
    <div class="footer">
        ✍️ हर U के लिए "कहां से", "कहां तक" और "अतिरिक्त कोष्टक" भरें — यह आपका बस कंडक्टर फ्रेंड है।
    </div>
</div>
</body>
</html>
input type="text" size="50">
