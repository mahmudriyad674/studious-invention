<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Class 7 & 8 Questions</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f0f0f5;
      padding: 30px;
      text-align: center;
    }
    h1 {
      color: #2e86de;
    }
    .btn-group {
      margin: 20px 0;
    }
    button {
      padding: 10px 20px;
      margin: 5px;
      font-size: 16px;
      background-color: #3498db;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #2d7cc0;
    }
    .question-box {
      display: none;
      max-width: 800px;
      margin: auto;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      text-align: left;
    }
    .question {
      font-weight: bold;
      margin-top: 15px;
    }
    .answer {
      margin-left: 20px;
    }
  </style>
</head>
<body>
  <h1>Class 7 ও 8 - প্রশ্ন ও উত্তর</h1>

  <div class="btn-group">
    <button onclick="showSection('class7')">Class 7</button>
    <button onclick="showSection('class8')">Class 8</button>
  </div>

  <div id="class7" class="question-box">
    <h2>Class 7 - বিজ্ঞান</h2>
    <div class="question">১। কোষ কাকে বলে?</div>
    <div class="answer">জীবদেহের গঠন ও কার্যগত একক হলো কোষ।</div>

    <div class="question">২। মাছ কিভাবে শ্বাস নেয়?</div>
    <div class="answer">মাছ গিলে পানি টানে ও গিলের সাহায্যে অক্সিজেন গ্রহণ করে।</div>

    <div class="question">৩। পাখি কীভাবে উড়ে?</div>
    <div class="answer">পাখি ডানা নেড়ে ও হালকা শরীরের মাধ্যমে উড়ে।</div>
  </div>

  <div id="class8" class="question-box">
    <h2>Class 8 - বিজ্ঞান</h2>
    <div class="question">১। পদার্থ কাকে বলে?</div>
    <div class="answer">যে সব কিছুর ওজন আছে ও স্থান দখল করে তাকে পদার্থ বলে।</div>

    <div class="question">২। পরমাণু কী?</div>
    <div class="answer">পদার্থের ক্ষুদ্রতম কণা যা রাসায়নিকভাবে অবিভাজ্য।</div>

    <div class="question">৩। সালোকসংশ্লেষণ কী?</div>
    <div class="answer">উদ্ভিদ সূর্যালোক, পানি ও CO₂ ব্যবহার করে খাদ্য তৈরি করে।</div>
  </div>

  <script>
    function showSection(classId) {
      document.getElementById('class7').style.display = 'none';
      document.getElementById('class8').style.display = 'none';
      document.getElementById(classId).style.display = 'block';
    }
  </script>
</body>
</html>

