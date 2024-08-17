<title>GitHub Stats</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f7f7f7;
        }
        .container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .tech-stack, .github-stats {
            margin-bottom: 30px;
        }
        h2 {
            font-size: 24px;
            color: #333;
            margin-bottom: 10px;
        }
        .tech-stack img {
            width: 50px;
            height: 50px;
            margin-right: 10px;
        }
        .github-stats {
            text-align: center;
        }
        .github-stats .stats-summary {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
        }
        .github-stats .stats-summary div {
            flex: 1;
            margin: 0 10px;
        }
        .github-stats .stats-summary .circle {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 5px solid #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto;
            font-size: 36px;
            color: #666;
        }
        .github-stats .streak-summary {
            display: flex;
            justify-content: space-around;
            margin-top: 20px;
        }
        .github-stats .streak-summary div {
            text-align: center;
        }
        .most-used-languages {
            margin-top: 30px;
        }
        .most-used-languages ul {
            list-style: none;
            padding: 0;
        }
        .most-used-languages li {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }
        .most-used-languages .color-box {
            width: 20px;
            height: 20px;
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="tech-stack">
            <h2>Tech Stack:</h2>
            <img src="https://img.icons8.com/color/50/000000/c-plus-plus-logo.png" alt="C++">
            <img src="https://img.icons8.com/color/50/000000/javascript.png" alt="JavaScript">
            <img src="https://img.icons8.com/color/50/000000/html-5.png" alt="HTML5">
            <img src="https://img.icons8.com/color/50/000000/css3.png" alt="CSS3">
        </div>

        <div class="github-stats">
            <h2>GitHub Stats:</h2>
            <div class="stats-summary">
                <div>
                    <p>Total Stars Earned:</p>
                    <p>0</p>
                </div>
                <div>
                    <p>Total Commits (2024):</p>
                    <p>0</p>
                </div>
                <div>
                    <p>Total PRs:</p>
                    <p>0</p>
                </div>
                <div>
                    <p>Total Issues:</p>
                    <p>0</p>
                </div>
                <div>
                    <p>Contributed to (last year):</p>
                    <p>0</p>
                </div>
            </div>

            <div class="circle">C</div>

            <div class="streak-summary">
                <div>
                    <p>Total Contributions</p>
                    <p>0</p>
                    <p>Aug 17 - Present</p>
                </div>
                <div>
                    <p>Current Streak</p>
                    <p>0</p>
                    <p>Aug 17</p>
                </div>
                <div>
                    <p>Longest Streak</p>
                    <p>0</p>
                    <p>Jan 1, 2018</p>
                </div>
            </div>
        </div>

        <div class="most-used-languages">
            <h2>Most Used Languages</h2>
            <ul>
                <li><div class="color-box" style="background-color: #f34b7d;"></div>C++ 41.30%</li>
                <li><div class="color-box" style="background-color: #f1e05a;"></div>JavaScript 27.66%</li>
                <li><div class="color-box" style="background-color: #555555;"></div>C 11.67%</li>
                <li><div class="color-box" style="background-color: #3581ba;"></div>Papyrus 9.98%</li>
                <li><div class="color-box" style="background-color: #4f5d95;"></div>PHP 6.42%</li>
                <li><div class="color-box" style="background-color: #178600;"></div>C# 2.96%</li>
            </ul>
        </div>
    </div>
