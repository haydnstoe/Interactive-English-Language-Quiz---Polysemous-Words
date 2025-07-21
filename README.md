<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Intermediate British English Quiz</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      max-width: 800px;
      margin: 40px auto;
      padding: 0 20px;
      background: #f9f9f9;
      color: #333;
    }
    h1 {
      text-align: center;
      color: #003366;
      margin-bottom: 1rem;
    }
    .question {
      margin-bottom: 1.25rem;
    }
    .question label {
      display: block;
      margin-bottom: 0.25rem;
    }
    select {
      padding: 0.3rem;
      font-size: 1rem;
    }
    button {
      display: block;
      margin: 2rem auto;
      padding: 0.6rem 1.2rem;
      font-size: 1rem;
      background: #003366;
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    #result {
      text-align: center;
      font-size: 1.25rem;
      margin-top: 1.5rem;
      font-weight: bold;
    }
    .correct {
      color: green;
    }
    .incorrect {
      color: red;
    }
  </style>
</head>
<body>

  <h1>Intermediate British English Quiz</h1>

  <div id="quiz">
    <!-- 1 -->
    <div class="question">
      <label for="q1">1. They ____ (not/finish) the work on time.</label>
      <select id="q1">
        <option value="">— select —</option>
        <option value="finished">finished</option>
        <option value="didn't finish">didn't finish</option>
        <option value="don't finish">don't finish</option>
        <option value="did finish">did finish</option>
      </select>
    </div>

    <!-- 2 -->
    <div class="question">
      <label for="q2">2. He ____ to Australia last year.</label>
      <select id="q2">
        <option value="">— select —</option>
        <option value="go">go</option>
        <option value="has gone">has gone</option>
        <option value="went">went</option>
        <option value="had went">had went</option>
      </select>
    </div>

    <!-- 3 -->
    <div class="question">
      <label for="q3">3. She ____ (meet) the manager yesterday.</label>
      <select id="q3">
        <option value="">— select —</option>
        <option value="meets">meets</option>
        <option value="met">met</option>
        <option value="has met">has met</option>
        <option value="had meet">had meet</option>
      </select>
    </div>

    <!-- 4 -->
    <div class="question">
      <label for="q4">4. I ____ (not/eat) breakfast this morning.</label>
      <select id="q4">
        <option value="">— select —</option>
        <option value="didn't eat">didn't eat</option>
        <option value="didn't ate">didn't ate</option>
        <option value="haven't eaten">haven't eaten</option>
        <option value="don't eat">don't eat</option>
      </select>
    </div>

    <!-- 5 -->
    <div class="question">
      <label for="q5">5. We ____ (decide) to stay at home.</label>
      <select id="q5">
        <option value="">— select —</option>
        <option value="decide">decide</option>
        <option value="decided">decided</option>
        <option value="have decided">have decided</option>
        <option value="decideded">decideded</option>
      </select>
    </div>

    <!-- 6 -->
    <div class="question">
      <label for="q6">6. The concert ____ at 8 pm.</label>
      <select id="q6">
        <option value="">— select —</option>
        <option value="starts">starts</option>
        <option value="started">started</option>
        <option value="has started">has started</option>
        <option value="had started">had started</option>
      </select>
    </div>

    <!-- 7 -->
    <div class="question">
      <label for="q7">7. I ____ (not/see) that movie yet.</label>
      <select id="q7">
        <option value="">— select —</option>
        <option value="didn't see">didn't see</option>
        <option value="haven't seen">haven't seen</option>
        <option value="hadn't seen">hadn't seen</option>
        <option value="haven't saw">haven't saw</option>
      </select>
    </div>

    <!-- 8 -->
    <div class="question">
      <label for="q8">8. He ____ (travel) to Paris several times.</label>
      <select id="q8">
        <option value="">— select —</option>
        <option value="has travelled">has travelled</option>
        <option value="has travel">has travel</option>
        <option value="have travelled">have travelled</option>
        <option value="have travel">have travel</option>
      </select>
    </div>

    <!-- 9 -->
    <div class="question">
      <label for="q9">9. They ____ (live) here since 2010.</label>
      <select id="q9">
        <option value="">— select —</option>
        <option value="have lived">have lived</option>
        <option value="has lived">has lived</option>
        <option value="lived">lived</option>
        <option value="have lives">have lives</option>
      </select>
    </div>

    <!-- 10 -->
    <div class="question">
      <label for="q10">10. She ____ (finish) her homework.</label>
      <select id="q10">
        <option value="">— select —</option>
        <option value="finished">finished</option>
        <option value="has finished">has finished</option>
        <option value="have finished">have finished</option>
        <option value="has finish">has finish</option>
      </select>
    </div>

    <!-- 11 -->
    <div class="question">
      <label for="q11">11. We ____ (be) to that restaurant before.</label>
      <select id="q11">
        <option value="">— select —</option>
        <option value="have been">have been</option>
        <option value="has been">has been</option>
        <option value="were">were</option>
        <option value="was">was</option>
      </select>
    </div>

    <!-- 12 -->
    <div class="question">
      <label for="q12">12. You ____ (ever/read) Shakespeare?</label>
      <select id="q12">
        <option value="">— select —</option>
        <option value="have you ever read">have you ever read</option>
        <option value="have you read">have you read</option>
        <option value="had you ever read">had you ever read</option>
        <option value="have been reading">have been reading</option>
      </select>
    </div>

    <!-- 13 -->
    <div class="question">
      <label for="q13">13. Can you ____ up the volume?</label>
      <select id="q13">
        <option value="">— select —</option>
        <option value="turn up">turn up</option>
        <option value="turn on">turn on</option>
        <option value="turn off">turn off</option>
        <option value="turn down">turn down</option>
      </select>
    </div>

    <!-- 14 -->
    <div class="question">
      <label for="q14">14. She ____ off at dawn.</label>
      <select id="q14">
        <option value="">— select —</option>
        <option value="set off">set off</option>
        <option value="set out">set out</option>
        <option value="went off">went off</option>
        <option value="went out">went out</option>
      </select>
    </div>

    <!-- 15 -->
    <div class="question">
      <label for="q15">15. He ____ into politics.</label>
      <select id="q15">
        <option value="">— select —</option>
        <option value="went into">went into</option>
        <option value="went in">went in</option>
        <option value="went out">went out</option>
        <option value="went on">went on</option>
      </select>
    </div>

    <!-- 16 -->
    <div class="question">
      <label for="q16">16. I need to ____ on my homework.</label>
      <select id="q16">
        <option value="">— select —</option>
        <option value="work on">work on</option>
        <option value="work out">work out</option>
        <option value="bring on">bring on</option>
        <option value="join in">join in</option>
      </select>
    </div>

    <!-- 17 -->
    <div class="question">
      <label for="q17">17. They ____ across an old diary.</label>
      <select id="q17">
        <option value="">— select —</option>
        <option value="came across">came across</option>
        <option value="came up">came up</option>
        <option value="came over">came over</option>
        <option value="came in">came in</option>
      </select>
    </div>

    <!-- 18 -->
    <div class="question">
      <label for="q18">18. The plane ____ off late.</label>
      <select id="q18">
        <option value="">— select —</option>
        <option value="took off">took off</option>
        <option value="took on">took on</option>
        <option value="took up">took up</option>
        <option value="took in">took in</option>
      </select>
    </div>

    <!-- 19 -->
    <div class="question">
      <label for="q19">19. To “break the ice” means to:</label>
      <select id="q19">
        <option value="">— select —</option>
        <option value="start a conversation">start a conversation</option>
        <option value="freeze water">freeze water</option>
        <option value="avoid others">avoid others</option>
        <option value="ruin a relationship">ruin a relationship</option>
      </select>
    </div>

    <!-- 20 -->
    <div class="question">
      <label for="q20">20. “Hit the nail on the head” means to:</label>
      <select id="q20">
        <option value="">— select —</option>
        <option value="describe exactly">describe exactly</option>
        <option value="play music">play music</option>
        <option value="build a house">build a house</option>
        <option value="find something missing">find something missing</option>
      </select>
    </div>

    <!-- 21 -->
    <div class="question">
      <label for="q21">21. “Cost me an arm and a leg” means it:</label>
      <select id="q21">
        <option value="">— select —</option>
        <option value="was very expensive">was very expensive</option>
        <option value="resulted in injury">resulted in injury</option>
        <option value="was comfortable">was comfortable</option>
        <option value="was a gift">was a gift</option>
      </select>
    </div>

    <!-- 22 -->
    <div class="question">
      <label for="q22">22. Which meaning of “run” is used in “He went for a quick run before breakfast”?</label>
      <select id="q22">
        <option value="">— select —</option>
        <option value="jog">jog</option>
        <option value="control">control</option>
        <option value="operate">operate</option>
        <option value="flow">flow</option>
      </select>
    </div>

    <!-- 23 -->
    <div class="question">
      <label for="q23">23. Which meaning of “set” is used in “The sun will set at 7 pm”?</label>
      <select id="q23">
        <option value="">— select —</option>
        <option value="descend">descend</option>
        <option value="put in place">put in place</option>
        <option value="establish">establish</option>
        <option value="decide">decide</option>
      </select>
    </div>

    <!-- 24 -->
    <div class="question">
      <label for="q24">24. Which meaning of “light” is used in “This box is very light”?</label>
      <select id="q24">
        <option value="">— select —</option>
        <option value="not heavy">not heavy</option>
        <option value="pale">pale</option>
        <option value="small">small</option>
        <option value="bright">bright</option>
      </select>
    </div>

    <!-- 25 -->
    <div class="question">
      <label for="q25">25. Which meaning of “face” is used in “He had to face the facts”?</label>
      <select id="q25">
        <option value="">— select —</option>
        <option value="confront">confront</option>
        <option value="look at">look at</option>
        <option value="stand before">stand before</option>
        <option value="oppose">oppose</option>
      </select>
    </div>

    <button onclick="submitQuiz()">Submit Answers</button>
  </div>

  <div id="result"></div>

  <script>
    const answers = {
      q1: "didn't finish",
      q2: "went",
      q3: "met",
      q4: "didn't eat",
      q5: "decided",
      q6: "started",
      q7: "haven't seen",
      q8: "has travelled",
      q9: "have lived",
      q10: "has finished",
      q11: "have been",
      q12: "have you ever read",
      q13: "turn up",
      q14: "set off",
      q15: "went into",
      q16: "work on",
      q17: "came across",
      q18: "took off",
      q19: "start a conversation",
      q20: "describe exactly",
      q21: "was very expensive",
      q22: "jog",
      q23: "descend",
      q24: "not heavy",
      q25: "confront"
    };

    function submitQuiz() {
      let score = 0;
      for (let i = 1; i <= 25; i++) {
        const qid = 'q' + i;
        const select = document.getElementById(qid);
        const parent = select.parentElement;
        parent.classList.remove('correct', 'incorrect');

        if (select.value === answers[qid]) {
          score++;
          parent.classList.add('correct');
        } else {
          parent.classList.add('incorrect');
        }
        select.disabled = true;
      }

      const resultDiv = document.getElementById('result');
      resultDiv.textContent = `You scored ${score} out of 25.`;
    }
  </script>

</body>
</html>
