<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Comparatives & Superlatives Practice</title>
<style>
    body {
        font-family: Arial, sans-serif;
        background: #f4f4f4;
        margin: 0;
        padding: 0;
    }
    .slide {
        display: none;
        max-width: 900px;
        margin: 40px auto;
        background: #ffffff;
        padding: 30px;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .slide.active {
        display: block;
    }
    h1, h2 {
        color: #333;
    }
    p, li {
        line-height: 1.6;
    }
    input[type="text"] {
        padding: 5px;
        width: 120px;
    }
    button {
        padding: 8px 15px;
        margin: 10px 5px 0 0;
        cursor: pointer;
        border: none;
        border-radius: 4px;
        background: #0077cc;
        color: white;
    }
    button:hover {
        background: #005fa3;
    }
    .feedback {
        margin-left: 10px;
        font-weight: bold;
    }
    .correct {
        color: green;
    }
    .wrong {
        color: red;
    }
    .navigation {
        text-align: center;
        margin-bottom: 40px;
    }
</style>
</head>

<body>

<!-- SLIDE 1: THEORY -->
<div class="slide active">
    <h1>Comparatives and Superlatives</h1>

    <p>
        Explaining the use of <strong>"more"</strong> and <strong>"-er"</strong> in comparative forms
        can be approached by understanding the number of syllables in the adjective.
        Here's a simple guideline:
    </p>

    <ol>
        <li>
            <strong>One-Syllable Adjectives</strong><br>
            Use the <strong>-er</strong> ending.<br>
            <em>Examples:</em> tall → taller, fast → faster, big → bigger
        </li>

        <li>
            <strong>Two-Syllable Adjectives Ending in -y</strong><br>
            Change <strong>-y</strong> to <strong>-ier</strong>.<br>
            <em>Examples:</em> happy → happier, busy → busier
        </li>

        <li>
            <strong>Two-Syllable Adjectives Not Ending in -y</strong><br>
            Use <strong>more</strong>.<br>
            <em>Examples:</em> modern → more modern, famous → more famous
        </li>

        <li>
            <strong>Adjectives with Three or More Syllables</strong><br>
            Use <strong>more</strong>.<br>
            <em>Examples:</em> beautiful → more beautiful, interesting → more interesting
        </li>
    </ol>

    <p>
        Remember: there are some irregular adjectives (good → better → best, bad → worse → worst),
        so practice is essential!
    </p>
</div>

<!-- SLIDE 2: MORE / MOST ONLY -->
<div class="slide">
    <h2>Exercise 1: More or Most</h2>
    <p><strong>Instructions:</strong> Use only <em>more</em> or <em>most</em>.</p>

    <ol>
        <li>I like this book <input data-answer="more"> than the other one.</li>
        <li>She is <input data-answer="more"> excited about her birthday party.</li>
        <li>This is the <input data-answer="most"> delicious cake I have ever tasted.</li>
        <li>He is <input data-answer="more"> intelligent than his brother.</li>
        <li>She has <input data-answer="more"> friends than I do.</li>
        <li>This is the <input data-answer="most"> interesting movie I have seen this year.</li>
        <li>He is the <input data-answer="most"> talented musician in the band.</li>
        <li>She is <input data-answer="more"> confident than she was before.</li>
        <li>This is the <input data-answer="most"> beautiful dress I have ever worn.</li>
        <li>They have <input data-answer="more"> experience in this field than we do.</li>
    </ol>

    <button onclick="checkAnswers(this)">Check answers</button>
</div>

<!-- SLIDE 3: MIXED FORMS -->
<div class="slide">
    <h2>Exercise 2: Choose the Correct Form</h2>
    <p><strong>Instructions:</strong> Use <em>-er</em>, <em>-est</em>, <em>more</em>, or <em>most</em>.</p>

    <ol>
        <li>That was the <input data-answer="most fun"> game I've played all year.</li>
        <li>The new software is <input data-answer="more efficient"> than the old one.</li>
        <li>Your presentation was the <input data-answer="most informative"> of all.</li>
        <li>This city is <input data-answer="more crowded"> during rush hour.</li>
        <li>Her artwork is <input data-answer="more creative"> than anything I've seen.</li>
        <li>The final exam was <input data-answer="harder"> than the practice tests.</li>
        <li>Winter is the <input data-answer="coldest"> season.</li>
        <li>My dog is <input data-answer="more energetic"> in the morning.</li>
        <li>The Grand Canyon is the <input data-answer="most breathtaking"> natural wonder.</li>
        <li>The concert was <input data-answer="more enjoyable"> than I expected.</li>
        <li>The movie was <input data-answer="more boring"> than the one on Friday.</li>
        <li>Mount Everest is the <input data-answer="highest"> peak in the world.</li>
        <li>This is the <input data-answer="most expensive"> painting here.</li>
        <li>The journey was <input data-answer="more arduous"> than we thought.</li>
        <li>Chocolate cake is the <input data-answer="most delicious"> dessert.</li>
    </ol>

    <button onclick="checkAnswers(this)">Check answers</button>
</div>

<!-- SLIDE 4: SENTENCE TRANSFORMATION -->
<div class="slide">
    <h2>Exercise 3: Rewrite the Sentence</h2>
    <p><strong>Instructions:</strong> Complete the sentence using the correct comparative or superlative.</p>

    <ol>
        <li>This test is ________ (easy) than the last one. <input data-answer="easier"></li>
        <li>She is the ________ (organized) person in the office. <input data-answer="most organized"></li>
        <li>Today is ________ (hot) than yesterday. <input data-answer="hotter"></li>
        <li>This explanation is the ________ (clear) so far. <input data-answer="clearest"></li>
        <li>Learning languages is ________ (interesting) than people think. <input data-answer="more interesting"></li>
    </ol>

    <button onclick="checkAnswers(this)">Check answers</button>
</div>

<!-- SLIDE 5: ERROR CORRECTION -->
<div class="slide">
    <h2>Exercise 4: Correct the Mistake</h2>
    <p><strong>Instructions:</strong> Rewrite the adjective correctly.</p>

    <ol>
        <li>She is <em>more happier</em> now → <input data-answer="happier"></li>
        <li>This is the <em>most fastest</em> way → <input data-answer="fastest"></li>
        <li>This book is <em>interestinger</em> → <input data-answer="more interesting"></li>
        <li>He is the <em>more talented</em> student → <input data-answer="most talented"></li>
        <li>This task is <em>difficulter</em> → <input data-answer="more difficult"></li>
    </ol>

    <button onclick="checkAnswers(this)">Check answers</button>
</div>

<div class="navigation">
    <button onclick="prevSlide()">Previous</button>
    <button onclick="nextSlide()">Next</button>
</div>

<script>
let currentSlide = 0;
const slides = document.querySelectorAll('.slide');

function showSlide(index) {
    slides.forEach(slide => slide.classList.remove('active'));
    slides[index].classList.add('active');
}

function nextSlide() {
    if (currentSlide < slides.length - 1) {
        currentSlide++;
        showSlide(currentSlide);
    }
}

function prevSlide() {
    if (currentSlide > 0) {
        currentSlide--;
        showSlide(currentSlide);
    }
}

function checkAnswers(button) {
    const inputs = button.parentElement.querySelectorAll('input');
    inputs.forEach(input => {
        let answer = input.dataset.answer.toLowerCase().trim();
        let user = input.value.toLowerCase().trim();
        input.nextSibling?.remove?.();

        const span = document.createElement('span');
        span.classList.add('feedback');

        if (user === answer) {
            span.textContent = " ✓";
            span.classList.add('correct');
        } else {
            span.textContent = " ✗ (" + answer + ")";
            span.classList.add('wrong');
        }
        input.after(span);
    });
}
</script>

</body>
</html>
