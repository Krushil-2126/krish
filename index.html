<?php
session_start();

// Set the correct answer
$correctAnswer = 51;

// Initialize attempts if not set
if (!isset($_SESSION['attempts'])) {
    $_SESSION['attempts'] = 0;
}

// Reset game
if (isset($_POST['reset'])) {
    $_SESSION['attempts'] = 0;
    $_SESSION['message'] = '';
    $_SESSION['type'] = '';
    $_SESSION['disabled'] = false;
    $_POST['guess'] = '';
}

// Handle guess
if (isset($_POST['guess-btn']) && isset($_POST['guess']) && !$_SESSION['disabled']) {
    $guess = intval($_POST['guess']);
    if ($guess < 1 || $guess > 100) {
        $_SESSION['message'] = 'Please enter a valid number between 1 and 100';
        $_SESSION['type'] = 'error';
    } else {
        $_SESSION['attempts']++;
        if ($guess === $correctAnswer) {
            $_SESSION['message'] = "🎉 Congratulations! You guessed the correct number ($correctAnswer) in {$_SESSION['attempts']} attempts!";
            $_SESSION['type'] = 'success';
            $_SESSION['disabled'] = true;
        } elseif ($guess < $correctAnswer) {
            $_SESSION['message'] = 'Your guess is too low. Try again!';
            $_SESSION['type'] = 'warning';
        } else {
            $_SESSION['message'] = 'Your guess is too high. Try again!';
            $_SESSION['type'] = 'warning';
        }
    }
}
?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Guessing Game | KANERIA KRISH DIPAKBHAI 970ceda1</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        /* [All your CSS remains exactly the same, copied from your original] */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            color: #333;
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .container {
            background: white;
            border-radius: 15px;
            padding: 30px;
            width: 90%;
            max-width: 600px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
        }

        header {
            text-align: center;
            margin-bottom: 30px;
        }

        h1 {
            color: #1a2a6c;
            margin-bottom: 10px;
            font-size: 2.5rem;
        }

        h2 {
            color: #b21f1f;
            margin-bottom: 20px;
            font-size: 1.8rem;
        }

        .instructions {
            background-color: #f8f9fa;
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 25px;
            border-left: 5px solid #1a2a6c;
        }

        .instructions h3 {
            color: #1a2a6c;
            margin-bottom: 10px;
        }

        .instructions ul {
            padding-left: 20px;
        }

        .instructions li {
            margin-bottom: 8px;
        }

        .game-area {
            text-align: center;
        }

        .guess-form {
            margin-bottom: 25px;
        }

        input[type="number"] {
            width: 100%;
            padding: 12px 15px;
            border: 2px solid #ddd;
            border-radius: 8px;
            font-size: 1.2rem;
            margin-bottom: 15px;
            text-align: center;
        }

        button {
            background: linear-gradient(to right, #1a2a6c, #b21f1f);
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 8px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: transform 0.2s, box-shadow 0.2s;
            font-weight: bold;
        }

        button:hover {
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }

        .result {
            padding: 15px;
            border-radius: 8px;
            margin-bottom: 20px;
            font-size: 1.2rem;
            font-weight: bold;
            display: block;
        }

        .success {
            background-color: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }

        .error {
            background-color: #f8d7da;
            color: #721c24;
            border: 1px solid #f5c6cb;
        }

        .warning {
            background-color: #fff3cd;
            color: #856404;
            border: 1px solid #ffeeba;
        }

        .attempts {
            font-size: 1.1rem;
            margin-bottom: 15px;
            color: #1a2a6c;
        }

        .reset-btn {
            background: linear-gradient(to right, #fdbb2d, #b21f1f);
            margin-top: 15px;
        }

        footer {
            text-align: center;
            margin-top: 30px;
            color: #6c757d;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Guessing Game</h1>
            <h2>WA4E Assignment Solution</h2>
        </header>

        <div class="instructions">
            <h3>How to Play:</h3>
            <ul>
                <li>I'm thinking of a number between 1 and 100</li>
                <li>Try to guess the number in as few attempts as possible</li>
                <li>After each guess, I'll tell you if your guess is too high, too low, or correct</li>
                <li>The correct answer for this assignment is <strong>51</strong></li>
            </ul>
        </div>

        <div class="game-area">
            <div class="attempts">Attempts: <span id="attempt-count"><?php echo $_SESSION['attempts']; ?></span></div>

            <form method="post" class="guess-form">
                <input type="number" name="guess" min="1" max="100" placeholder="Enter your guess (1-100)"
                       <?php echo isset($_SESSION['disabled']) && $_SESSION['disabled'] ? 'disabled' : ''; ?> required>
                <button type="submit" name="guess-btn"
                        <?php echo isset($_SESSION['disabled']) && $_SESSION['disabled'] ? 'disabled' : ''; ?>>
                    Submit Guess
                </button>
            </form>

            <?php if (!empty($_SESSION['message'])): ?>
                <div class="result <?php echo $_SESSION['type']; ?>">
                    <?php echo $_SESSION['message']; ?>
                </div>
            <?php endif; ?>

            <form method="post">
                <button type="submit" name="reset" class="reset-btn">Reset Game</button>
            </form>
        </div>

        <footer>
            <p>Created by KANERIA KRISH DIPAKBHAI | Student Code: 970ceda1</p>
            <p>This assignment is part of the Building Web Applications in PHP course</p>
        </footer>
    </div>
</body>
</html>
