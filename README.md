<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <style>
        body {
            background-color: #0d1117; /* Fundo escuro similar ao GitHub */
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .stats-card {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 24px;
            width: 400px;
            color: #c9d1d9;
        }

        .stats-card h2 {
            color: #ae7de0;
            margin-top: 0;
            font-size: 24px;
            font-weight: 600;
        }

        .language-item {
            margin-bottom: 15px;
        }

        .label-container {
            display: flex;
            justify-content: space-between;
            margin-bottom: 8px;
            font-size: 14px;
        }

        .lang-name {
            font-weight: 600;
            color: #8b949e;
        }

        /* Barra de progresso */
        .progress-bg {
            background-color: #30363d;
            border-radius: 10px;
            height: 8px;
            width: 100%;
            overflow: hidden;
        }

        .progress-fill {
            height: 100%;
            border-radius: 10px;
        }

        /* Cores específicas das linguagens */
        .css { width: 22.86%; background-color: #563d7c; }
        .html { width: 22.82%; background-color: #e34c26; }
        .python { width: 22.29%; background-color: #3572a5; }
        .java { width: 16.71%; background-color: #b07219; }
        .js { width: 15.31%; background-color: #f1e05a; }

    </style>
</head>
<body>

<div class="stats-card">
    <h2>Most Used Languages</h2>

    <div class="language-item">
        <div class="label-container">
            <span class="lang-name">CSS</span>
            <span>22.86%</span>
        </div>
        <div class="progress-bg">
            <div class="progress-fill css"></div>
        </div>
    </div>

    <div class="language-item">
        <div class="label-container">
            <span class="lang-name">HTML</span>
            <span>22.82%</span>
        </div>
        <div class="progress-bg">
            <div class="progress-fill html"></div>
        </div>
    </div>

    <div class="language-item">
        <div class="label-container">
            <span class="lang-name">Python</span>
            <span>22.29%</span>
        </div>
        <div class="progress-bg">
            <div class="progress-fill python"></div>
        </div>
    </div>

    <div class="language-item">
        <div class="label-container">
            <span class="lang-name">Java</span>
            <span>16.71%</span>
        </div>
        <div class="progress-bg">
            <div class="progress-fill java"></div>
        </div>
    </div>

    <div class="language-item">
        <div class="label-container">
            <span class="lang-name">JavaScript</span>
            <span>15.31%</span>
        </div>
        <div class="progress-bg">
            <div class="progress-fill js"></div>
        </div>
    </div>
</div>

</body>
</html>
