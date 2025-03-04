<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Typing Animation</title>
  <style>
    /* Container for the typing animation */
    .typing-container {
      font-family: 'Courier New', monospace;
      font-size: 24px;
      color: #36BCF7;
      overflow: hidden; /* Ensures text doesn't overflow */
      white-space: nowrap; /* Keeps text in one line */
      border-right: 3px solid #36BCF7; /* Cursor effect */
      animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
    }

    /* Typing animation */
    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }

    /* Cursor blink animation */
    @keyframes blink-caret {
      from, to { border-color: transparent; }
      50% { border-color: #36BCF7; }
    }
  </style>
</head>
<body>
  <div class="typing-container">
    Hey There! I'm Ajay Joseph. Full Stack Developer. MERN Stack Enthusiast.
  </div>
</body>
</html>
