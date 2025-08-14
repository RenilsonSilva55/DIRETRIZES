<!DOCTYPE html> 
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diretrizes do NAPED em Medicina</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" 
          href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" 
          integrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0V4LLanw2qksYuRlEzO+tcaEPQogQ0KaoGN26/zrn20ImR1DfuLWnOo7aBA==" 
          crossorigin="anonymous" 
          referrerpolicy="no-referrer">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #333;
        }
        .card {
            background-color: #fff;
            border-radius: 1rem;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease-in-out;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .section-title {
            border-bottom: 2px solid #E91E63;
            padding-bottom: 0.5rem;
            margin-bottom: 1.5rem;
            color: #E91E63;
            animation: fadeIn 1s ease-in-out;
        }
        .task-icon {
            color: #E91E63;
            margin-right: 1rem;
            font-size: 1.5rem;
            flex-shrink: 0;
            animation: pulse 2s infinite;
        }
        .game-container {
            padding: 1.5rem;
            background-color: #f0f2f5;
            border-radius: 1rem;
            box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.06);
            margin-top: 1rem;
            text-align: center;
            cursor: pointer;
            min-height: 150px;
            transition: background-color 0.3s;
        }
        .game-container:hover {
            background-color: #e2e8f0;
        }
        .task-list-item {
            animation: popIn 0.5s ease-out;
            transform-origin: center;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        @keyframes popIn {
            from { opacity: 0; transform: scale(0.5); }
            to { opacity: 1; transform: scale(1); }
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body class="p-4 sm:p-8" <!-- resto do seu código permanece igual -->
</body>
</html>
