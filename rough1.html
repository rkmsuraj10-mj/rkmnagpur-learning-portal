<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Study Module & Self-Assessment</title>
  <style>
    * { box-sizing: border-box; }
    body {
      font-family: system-ui, -apple-system, sans-serif;
      background: #f8fafc;
      color: #1e293b;
      line-height: 1.6;
      margin: 0;
      padding: 2rem 1rem;
    }
    .container {
      max-width: 720px;
      margin: 0 auto;
      background: #ffffff;
      padding: 2.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.06);
    }
    h1 { margin-top: 0; color: #0f172a; border-bottom: 2px solid #e2e8f0; padding-bottom: 0.75rem; }
    h2 { color: #1e40af; margin-top: 1.5rem; font-size: 1.25rem; }
    .study-text {
      background: #f8fafc;
      border: 1px solid #e2e8f0;
      border-radius: 8px;
      padding: 1.25rem 1.5rem;
      margin-bottom: 2rem;
    }
    .question-block {
      background: #ffffff;
      border: 1px solid #e2e8f0;
      border-radius: 8px;
      padding: 1.25rem;
      margin-bottom: 1.25rem;
    }
    .question-title { font-weight: 600; margin-bottom: 0.75rem; }
    label {
      display: block;
      padding: 0.6rem 0.8rem;
      margin-bottom: 0.4rem;
      border-radius: 6px;
      background: #f1f5f9;
      cursor: pointer;
      transition: background 0.15s;
    }
    label:hover { background: #e2e8f0; }
    input[type="radio"] { margin-right: 0.5rem; }
    .btn-submit {
      background: #2563eb;
      color: #fff;
      border: none;
      padding: 0.8rem 1.75rem;
      font-size: 1rem;
      font-weight: 600;
      border-radius: 8px;
      cursor: pointer;
    }
    .btn-submit:hover { background: #1d4ed8; }
    .feedback {
      margin-top: 0.5rem;
      font-size: 0.9rem;
      font-weight: 500;
      display: none;
    }
    .score-banner {
      margin-top: 1.5rem;
      padding: 1rem;
      border-radius: 8px;
      font-size: 1.15rem;
      font-weight: bold;
      display: none;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Module 1: Study & Practice</h1>

    <!-- 1. Text Study Material -->
    <div class="study-text">
      <h2>Key Concepts & Overview</h2>
      <p>
        Insert your main study text, principles, rules, historical summaries, or grammar guidelines here. 
        You can write as many paragraphs as needed.
      </p>
      <p>
        <strong>Core Principle:</strong> Emphasize foundational takeaways here so the student can review them before attempting the assessment.
      </p>
    </div>

    <!-- 2. Practice Quiz -->
    <h2>Self-Assessment Quiz</h2>
    
    <div class="question-block" id="block-q1">
      <div class="question-title">1. Write your question here:</div>
      <label><input type="radio" name="q1" value="a"> Option A text</label>
      <label><input type="radio" name="q1" value="b"> Option B text (Correct)</label>
      <label><input type="radio" name="q1" value="c"> Option C text</label>
      <div class="feedback" id="feedback-q1"></div>
    </div>

    <div class="question-block" id="block-q2">
      <div class="question-title">2. Write another question here:</div>
      <label><input type="radio" name="q2" value="a"> Option A text (Correct)</label>
      <label><input type="radio" name="q2" value="b"> Option B text</label>
      <label><input type="radio" name="q2" value="c"> Option C text</label>
      <div class="feedback" id="feedback-q2"></div>
    </div>

    <button class="btn-submit" onclick="submitAssessment()">Submit Assessment</button>
    <div class="score-banner" id="score-banner"></div>
  </div>

  <script>
    const answerKey = {
      q1: { correct: 'b', explanation: 'Option B is correct because of rule X.' },
      q2: { correct: 'a', explanation: 'Option A is the correct answer according to the study text.' }
    };

    function submitAssessment() {
      let score = 0;
      let total = Object.keys(answerKey).length;
      let unanswered = 0;

      for (let q in answerKey) {
        const selected = document.querySelector(`input[name="${q}"]:checked`);
        const feedback = document.getElementById(`feedback-${q}`);
        feedback.style.display = 'block';

        if (!selected) {
          unanswered++;
          feedback.style.color = '#d97706';
          feedback.innerText = '⚠️ Please select an answer.';
          continue;
        }

        if (selected.value === answerKey[q].correct) {
          score++;
          feedback.style.color = '#16a34a';
          feedback.innerText = '✓ Correct! ' + answerKey[q].explanation;
        } else {
          feedback.style.color = '#dc2626';
          feedback.innerText = '✗ Incorrect. ' + answerKey[q].explanation;
        }
      }

      const banner = document.getElementById('score-banner');
      banner.style.display = 'block';
      if (unanswered > 0) {
        banner.style.background = '#fef3c7';
        banner.style.color = '#92400e';
        banner.innerText = `Please answer all questions. (${unanswered} remaining)`;
      } else {
        banner.style.background = score === total ? '#dcfce7' : '#fee2e2';
        banner.style.color = score === total ? '#15803d' : '#b91c1c';
        banner.innerText = `Your Score: ${score} / ${total} (${Math.round((score/total)*100)}%)`;
      }
    }
  </script>
</body>
</html>
