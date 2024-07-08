<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Vitória Nascimento - Desenvolvedora Front-end</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        h1 {
            color: #444;
            margin-bottom: 10px;
        }
        h3 {
            color: #666;
            margin-bottom: 20px;
        }
        .icons img {
            margin: 10px;
            transition: transform 0.2s;
        }
        .icons img:hover {
            transform: scale(1.1);
        }
        #stats {
            margin-top: 20px;
        }
        .header {
            font: 600 18px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #fe428e;
            animation: fadeInAnimation 0.8s ease-in-out forwards;
        }
        .stat {
            font: 600 14px 'Segoe UI', Ubuntu, "Helvetica Neue", Sans-Serif;
            fill: #a9fef7;
        }
        .stagger {
            opacity: 0;
            animation: fadeInAnimation 0.3s ease-in-out forwards;
        }
        .rank-text {
            font: 800 24px 'Segoe UI', Ubuntu, Sans-Serif;
            fill: #a9fef7;
            animation: scaleInAnimation 0.3s ease-in-out forwards;
        }
        .rank-percentile-header {
            font-size: 14px;
        }
        .rank-percentile-text {
            font-size: 16px;
        }
        .not_bold { font-weight: 400; }
        .bold { font-weight: 700; }
        .icon {
            fill: #f8d847;
            display: block;
        }
        .rank-circle-rim {
            stroke: #fe428e;
            fill: none;
            stroke-width: 6;
            opacity: 0.2;
        }
        .rank-circle {
            stroke: #fe428e;
            stroke-dasharray: 250;
            fill: none;
            stroke-width: 6;
            stroke-linecap: round;
            opacity: 0.8;
            transform-origin: -10px 8px;
            transform: rotate(-90deg);
            animation: rankAnimation 1s forwards ease-in-out;
        }
        @keyframes rankAnimation {
            from {
                stroke-dashoffset: 251.32741228718345;
            }
            to {
                stroke-dashoffset: 135.57045100717573;
            }
        }
        @keyframes scaleInAnimation {
            from {
                transform: translate(-5px, 5px) scale(0);
            }
            to {
                transform: translate(-5px, 5px) scale(1);
            }
        }
        @keyframes fadeInAnimation {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
    <script>
        function showMessage() {
            alert("Bem-vindo ao meu perfil no GitHub!");
        }
        window.onload = function() {
            setTimeout(showMessage, 1000);
        };
    </script>
</head>
<body>
    <h1>Olá! Eu sou Vitória Nascimento</h1>
    <h3>Desenvolvedora front-end</h3>

    <div class="icons">
        <a href="https://www.blender.org" rel="noreferrer" target="_blank">
            <img alt="Blender" src="https://download.blender.org/branding/community/blender_community_badge_white.png" width="40" height="50"/>
        </a>
        <a href="https://www.w3schools.com/cpp/" rel="noreferrer" target="_blank">
            <img alt="C++" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" width="40" height="40"/>
        </a>
        <a href="https://www.w3schools.com/cs/" rel="noreferrer" target="_blank">
            <img alt="C#" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" width="40" height="40"/>
        </a>
        <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" rel="noreferrer" target="_blank">
            <img alt="CSS3" src="https://upload.wikimedia.org/wikipedia/commons/d/d5/CSS3_logo_and_wordmark.svg" width="40" height="45"/>
        </a>
        <a href="https://www.w3.org/html/" rel="noreferrer" target="_blank">
            <img alt="HTML5" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="45" height="45"/>
        </a>
        <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" rel="noreferrer" target="_blank">
            <img alt="JavaScript" src="https://pcodinomebzero.neocities.org/Imagens/javascript1.png" width="46" height="46"/>
        </a>
    </div>

    <div id="stats">
        <img align="center" alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=vivihlopes&show_icons=true&locale=pt-BR"/>
    </div>

    <svg
        width="467"
        height="195"
        viewBox="0 0 467 195"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        role="img"
        aria-labelledby="descId"
    >
        <title id="titleId">Vitória Nascimento's GitHub Stats, Rank: B</title>
        <desc id="descId">Total Stars Earned: 133, Total Commits in 2024: 112, Total PRs: 15, Total Issues: 1, Contributed to (last year): 4</desc>

        <rect
            data-testid="card-bg"
            x="0.5"
            y="0.5"
            rx="4.5"
            height="99%"
            stroke="#e4e2e2"
            width="466"
            fill="#141321"
            stroke-opacity="1"
        />

        <g data-testid="card-title" transform="translate(25, 35)">
            <g transform="translate(0, 0)">
                <text x="0" y="0" class="header" data-testid="header">Vitória Nascimento's GitHub Stats</text>
            </g>
        </g>

        <g data-testid="main-card-body" transform="translate(0, 55)">
            <g data-testid="rank-circle" transform="translate(390.5, 47.5)">
                <circle class="rank-circle-rim" cx="-10" cy="8" r="40"/>
                <circle class="rank-circle" cx="-10" cy="8" r="40"/>
                <g class="rank-text">
                    <text x="-5" y="3" alignment-baseline="central" dominant-baseline="central" text-anchor="middle" data-testid="level-rank-icon">B</text>
                </g>
            </g>
            <svg x="0" y="0">
                <g transform="translate(0, 0)">
                    <g class="stagger" style="animation-delay: 450ms" transform="translate(25, 0)">
                        <svg data-testid="icon" class="icon" viewBox="0 0 16 16" version="1.1" width="16" height="16">
                            <path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01
