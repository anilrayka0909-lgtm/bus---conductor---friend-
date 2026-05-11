# bus---conductor---friend-<!DOCTYPE html>
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
