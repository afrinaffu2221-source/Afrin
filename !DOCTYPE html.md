<!DOCTYPE html>  
  
<html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>For Aali ❤️</title>  
    <style>  
        * {  
            margin: 0;  
            padding: 0;  
            box-sizing: border-box;  
        }  
  
```  
    body {  
        font-family: 'Arial', sans-serif;  
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);  
        min-height: 100vh;  
        display: flex;  
        align-items: center;  
        justify-content: center;  
        padding: 20px;  
        overflow: hidden;  
    }  
      
    /* Floating hearts */  
    .heart {  
        position: fixed;  
        color: rgba(255, 255, 255, 0.3);  
        font-size: 30px;  
        animation: float 8s infinite;  
        pointer-events: none;  
    }  
      
    @keyframes float {  
        0% {  
            transform: translateY(100vh) rotate(0deg);  
            opacity: 0;  
        }  
        10% {  
            opacity: 0.6;  
        }  
        90% {  
            opacity: 0.6;  
        }  
        100% {  
            transform: translateY(-100vh) rotate(360deg);  
            opacity: 0;  
        }  
    }  
      
    .heart:nth-child(1) { left: 15%; animation-delay: 0s; }  
    .heart:nth-child(2) { left: 35%; animation-delay: 3s; }  
    .heart:nth-child(3) { left: 55%; animation-delay: 1.5s; }  
    .heart:nth-child(4) { left: 75%; animation-delay: 4.5s; }  
      
    .container {  
        max-width: 650px;  
        width: 100%;  
        background: white;  
        border-radius: 25px;  
        box-shadow: 0 30px 80px rgba(0, 0, 0, 0.3);  
        padding: 50px 40px;  
        text-align: center;  
        position: relative;  
    }  
      
    .progress-bar {  
        width: 100%;  
        height: 8px;  
        background: #f0f0f0;  
        border-radius: 10px;  
        margin-bottom: 30px;  
        overflow: hidden;  
    }  
      
    .progress-fill {  
        height: 100%;  
        background: linear-gradient(90deg, #667eea, #764ba2);  
        border-radius: 10px;  
        transition: width 0.5s ease;  
        width: 0%;  
    }  
      
    .step-indicator {  
        color: #764ba2;  
        font-size: 18px;  
        font-weight: bold;  
        margin-bottom: 20px;  
    }  
      
    .content {  
        min-height: 300px;  
        display: flex;  
        flex-direction: column;  
        align-items: center;  
        justify-content: center;  
    }  
      
    h1 {  
        color: #764ba2;  
        font-size: 42px;  
        margin-bottom: 20px;  
        animation: fadeIn 0.8s ease;  
    }  
      
    .message {  
        font-size: 20px;  
        color: #555;  
        line-height: 1.8;  
        margin: 20px 0;  
        animation: fadeIn 0.8s ease;  
    }  
      
    .question {  
        font-size: 24px;  
        color: #764ba2;  
        margin: 20px 0;  
        font-weight: bold;  
        animation: fadeIn 0.8s ease;  
    }  
      
    .button-group {  
        display: flex;  
        gap: 15px;  
        margin-top: 30px;  
        flex-wrap: wrap;  
        justify-content: center;  
    }  
      
    button {  
        padding: 15px 35px;  
        font-size: 18px;  
        border: none;  
        border-radius: 50px;  
        cursor: pointer;  
        transition: all 0.3s ease;  
        font-weight: bold;  
        box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);  
    }  
      
    .btn-primary {  
        background: linear-gradient(135deg, #667eea, #764ba2);  
        color: white;  
    }  
      
    .btn-primary:hover {  
        transform: translateY(-3px);  
        box-shadow: 0 6px 25px rgba(118, 75, 162, 0.4);  
    }  
      
    .btn-secondary {  
        background: #f0f0f0;  
        color: #764ba2;  
    }  
      
    .btn-secondary:hover {  
        background: #e0e0e0;  
        transform: translateY(-3px);  
    }  
      
    .emoji {  
        font-size: 80px;  
        margin: 20px 0;  
        animation: bounce 1s ease infinite;  
    }  
      
    @keyframes bounce {  
        0%, 100% { transform: translateY(0); }  
        50% { transform: translateY(-10px); }  
    }  
      
    @keyframes fadeIn {  
        from {  
            opacity: 0;  
            transform: translateY(20px);  
        }  
        to {  
            opacity: 1;  
            transform: translateY(0);  
        }  
    }  
      
    .final-message {  
        font-size: 19px;  
        color: #555;  
        line-height: 1.9;  
        margin: 30px 0;  
        animation: fadeIn 0.8s ease;  
        text-align: left;  
        max-height: 500px;  
        overflow-y: auto;  
        padding-right: 10px;  
    }  
      
    .final-message p {  
        margin-bottom: 18px;  
    }  
      
    .signature {  
        margin-top: 30px;  
        font-style: italic;  
        color: #764ba2;  
        font-size: 22px;  
        font-weight: bold;  
    }  
      
    .confetti {  
        position: fixed;  
        width: 10px;  
        height: 10px;  
        background: #667eea;  
        animation: confettiFall 3s linear;  
        pointer-events: none;  
    }  
      
    @keyframes confettiFall {  
        to {  
            transform: translateY(100vh) rotate(360deg);  
            opacity: 0;  
        }  
    }  
      
    .congrats {  
        font-size: 50px;  
        margin: 20px 0;  
    }  
      
    .reward {  
        background: linear-gradient(135deg, #ffd700, #ffed4e);  
        padding: 20px;  
        border-radius: 15px;  
        margin: 20px 0;  
        box-shadow: 0 4px 20px rgba(255, 215, 0, 0.4);  
    }  
      
    .reward-text {  
        font-size: 24px;  
        color: #764ba2;  
        font-weight: bold;  
    }  
</style>  
```  
  
</head>  
<body>  
    <!-- Floating hearts -->  
    <div class="heart">💕</div>  
    <div class="heart">💖</div>  
    <div class="heart">💗</div>  
    <div class="heart">❤️</div>  
  
```  
<div class="container">  
    <div class="progress-bar">  
        <div class="progress-fill" id="progressFill"></div>  
    </div>  
      
    <div class="step-indicator" id="stepIndicator">Step 1 of 5</div>  
      
    <div class="content" id="content">  
        <!-- Steps will be inserted here by JavaScript -->  
    </div>  
</div>  
  
<script>  
    let currentStep = 0;  
    const totalSteps = 5;  
      
    const steps = [  
        {  
            type: 'welcome',  
            content: `  
                <h1>Happy Valentine's Day ❤️</h1>  
                <p class="message">I made something for you</p>  
                <div class="button-group">  
                    <button class="btn-primary" onclick="nextStep()">Let's see it! 💖</button>  
                </div>  
            `  
        },  
        {  
            type: 'question',  
            content: `  
                <div class="emoji">🥰</div>  
                <p class="question">Do you have the cutest girlfriend ever?</p>  
                <p class="message">Click YES to unlock your surprise</p>  
                <div class="button-group">  
                    <button class="btn-primary" onclick="nextStep()">YES ❤️</button>  
                </div>  
            `  
        },  
        {  
            type: 'question',  
            content: `  
                <div class="emoji">💝</div>  
                <p class="question">Who stole your heart and refuses to give it back?</p>  
                <div class="button-group">  
                    <button class="btn-secondary" onclick="nextStep()">A) my girlfriend</button>  
                    <button class="btn-primary" onclick="nextStep()">B) ofc my girlfriend 💕</button>  
                </div>  
            `  
        },  
        {  
            type: 'reveal',  
            content: `  
                <div class="congrats">🎉</div>  
                <p class="question">Congratulations!</p>  
                <div class="reward">  
                    <p class="reward-text">You have unlocked your Valentine's reward 🏆</p>  
                </div>  
                <div class="button-group">  
                    <button class="btn-primary" onclick="nextStep()">Click here to continue 👇</button>  
                </div>  
            `  
        },  
        {  
            type: 'final',  
            content: `  
                <h1 style="font-size: 32px; margin-bottom: 15px;">No refunds. Girlfriend is permanent. 😌</h1>  
                <div class="final-message">  
                    <p>It's only been a month but somehow it already feels like you've been a part of my world forever. Every little thing about you – your laugh, your silly jokes, the way you care – it makes me feel more alive.</p>  
                      
                    <p>Being with you feels like coming home, like I've finally found someone who just gets me without me having to explain everything. And even in this short time, I feel so grateful for every conversation, every silly message, every moment we've shared.</p>  
                      
                    <p>I know it's early, and maybe it sounds crazy, but I can't help it – you've already become one of the most important parts of my life. You make me feel safe, seen, and genuinely happy in ways I didn't know I could.</p>  
                      
                    <p>So… thank you. Thank you for being you, for choosing to share your time, your smile, your heart with me. I can't wait to make more memories with you, to laugh until we cry, to annoy each other in the best ways, and to just be… us.</p>  
                      
                    <p class="signature">Happy Valentine's Day, my love.<br>I love you, and I'm so lucky it's you I get to call mine 🤍</p>  
                </div>  
            `  
        }  
    ];  
      
    function updateProgress() {  
        const progress = ((currentStep + 1) / totalSteps) * 100;  
        document.getElementById('progressFill').style.width = progress + '%';  
        document.getElementById('stepIndicator').textContent = `Step ${currentStep + 1} of 5`;  
    }  
      
    function showStep() {  
        const content = document.getElementById('content');  
        content.innerHTML = steps[currentStep].content;  
        content.style.animation = 'none';  
        setTimeout(() => {  
            content.style.animation = 'fadeIn 0.8s ease';  
        }, 10);  
          
        updateProgress();  
          
        // Confetti on final step  
        if (currentStep === totalSteps - 1) {  
            createConfetti();  
        }  
    }  
      
    function nextStep() {  
        if (currentStep < totalSteps - 1) {  
            currentStep++;  
            showStep();  
        }  
    }  
      
    function createConfetti() {  
        const colors = ['#667eea', '#764ba2', '#f093fb', '#4facfe', '#fa709a', '#ffd700'];  
        for (let i = 0; i < 60; i++) {  
            setTimeout(() => {  
                const confetti = document.createElement('div');  
                confetti.className = 'confetti';  
                confetti.style.left = Math.random() * 100 + '%';  
                confetti.style.background = colors[Math.floor(Math.random() * colors.length)];  
                confetti.style.animationDelay = Math.random() * 2 + 's';  
                confetti.style.width = Math.random() * 8 + 6 + 'px';  
                confetti.style.height = confetti.style.width;  
                document.body.appendChild(confetti);  
                  
                setTimeout(() => confetti.remove(), 3000);  
            }, i * 40);  
        }  
    }  
      
    // Initialize  
    showStep();  
</script>  
```  
  
</body>  
</html>  
