<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diretrizes do NAPED em Medicina</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" xintegrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0V4LLanw2qksYuRlEzO+tcaEPQogQ0KaoGN26/zrn20ImR1DfuLWnOo7aBA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
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
<body class="p-4 sm:p-8">
    <div class="max-w-6xl mx-auto bg-white p-6 sm:p-10 rounded-2xl shadow-lg">
        <header class="text-center mb-10">
            <img src="https://placehold.co/250x50/E91E63/ffffff?text=Afya+Faculdade+Redenção.+PA." alt="Logo Afya Faculdade Redenção. PA." class="mx-auto mb-4 rounded-lg">
            <h1 class="text-3xl sm:text-4xl font-extrabold text-gray-800 mb-2">Novo Modelo de Diretrizes para o NAPED em Medicina</h1>
            <p class="text-lg text-gray-600">Foco Docente e Preceptoria</p>
        </header>
        <section class="mb-12">
            <h2 class="text-2xl sm:text-3xl font-bold section-title mb-6">1. Parceria Estratégica e Governança Pedagógica</h2>
            <p class="text-gray-700 mb-6">O NAPED atua como um parceiro consultivo, contribuindo ativamente para a gestão e o desenvolvimento do curso.</p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6"
                Dinâmica 1.1: Parceria e Alinhamento com a Gestão do Curso
                <div class="card p-6">
                    <h3 class="text-xl font-semibold text-gray-800 mb-4 flex items-center"><i class="fas fa-handshake task-icon"></i> Parceria com a Gestão</h3>
                    <p class="text-gray-600 mb-4">Clique no espaço abaixo para revelar os tópicos!</p>
                    <div id="game-parceria-tasks" class="game-container flex-col cursor-pointer">
                        <p id="game-parceria-prompt" class="text-gray-500 text-lg font-semibold">Clique para começar!</p>
                    </div>
                /div
                Dinâmica 1.2: Atuação Proativa na Matriz Curricular
                <div class="card p-6">
                    <h3 class="text-xl font-semibold text-gray-800 mb-4 flex items-center"><i class="fas fa-sitemap task-icon"></i> Atuação na Matriz Curricular</h3>
                    <p class="text-gray-600 mb-4">Clique no espaço abaixo para revelar os tópicos!</p>
                    <div id="game-matriz-tasks" class="game-container flex-col cursor-pointer">
                        <p id="game-matriz-prompt" class="text-gray-500 text-lg font-semibold">Clique para começar!</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="mb-12">
            <h2 class="text-2xl sm:text-3xl font-bold section-title mb-6">2. Formação, Desenvolvimento e Acompanhamento Docente</h2>
            <p class="text-gray-700 mb-6">O NAPED será o motor da capacitação contínua, oferecendo suporte personalizado para professores e preceptores.</p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6"
                 !-- Dinâmica 2.1: Programas de Formação Contínua -->
                <div class="card p-6">
                    <h3 class="text-xl font-semibold text-gray-800 mb-4 flex items-center"><i class="fas fa-chalkboard-teacher task-icon"></i> Programas de Formação</h3>
                    <p class="text-gray-600 mb-4">Clique no espaço abaixo para revelar os tópicos!</p>
                    <div id="game-formacao-tasks" class="game-container flex-col cursor-pointer">
                        <p id="game-formacao-prompt" class="text-gray-500 text-lg font-semibold">Clique para começar!</p>
                    </div>
                </div>
    Dinâmica 2.2: Acompanhamento Pedagógico Individualizado
                <div class="card p-6">
                    <h3 class="text-xl font-semibold text-gray-800 mb-4 flex items-center"><i class="fas fa-user-friends task-icon"></i> Acompanhamento Individualizado</h3>
                    <p class="text-gray-600 mb-4">Clique no espaço abaixo para revelar os tópicos!</p>
                    <div id="game-acompanhamento-tasks" class="game-container flex-col cursor-pointer">
                        <p id="game-acompanhamento-prompt" class="text-gray-500 text-lg font-semibold">Clique para começar!</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="mb-12">
            <h2 class="text-2xl sm:text-3xl font-bold section-title mb-6">3. Apoio Pedagógico na Elaboração de Avaliações</h2>
            <p class="text-gray-700 mb-6">O NAPED assume um papel central na garantia da qualidade e validade das avaliações.</p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6"
                !-- Dinâmica 3.1: Assessoria na Construção de Itens
                <div class="card p-6">
                    <h3 class="text-xl font-semibold text-gray-800 mb-4 flex items-center"><i class="fas fa-clipboard-list task-icon"></i> Assessoria em Avaliações</h3>
                    <p class="text-gray-600 mb-4">Clique no espaço abaixo para revelar os tópicos!</p>
                    <div id="game-assessoria-tasks" class="game-container flex-col cursor-pointer">
                        <p id="game-assessoria-prompt" class="text-gray-500 text-lg font-semibold">Clique para começar!</p>
                    </div>
                </div>
             Dinâmica 3.2: Ações Pedagógicas Ativas no OSCE
                <div class="card p-6">
                    <h3 class="text-xl font-semibold text-gray-800 mb-4 flex items-center"><i class="fas fa-star-half-alt task-icon"></i> Ações no OSCE</h3>
                    <p class="text-gray-600 mb-4">Clique no espaço abaixo para revelar os tópicos!</p>
                    <div id="game-osce-tasks" class="game-container flex-col cursor-pointer">
                        <p id="game-osce-prompt" class="text-gray-500 text-lg font-semibold">Clique para começar!</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="mb-12">
            <h2 class="text-2xl sm:text-3xl font-bold section-title mb-6">4. Suporte aos Preceptores e Articulação Interdisciplinar</h2>
            <p class="text-gray-700 mb-6">A colaboração com os preceptores será o foco principal, fortalecendo a prática de ensino em campo.</p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                Dinâmica 4.1: Qualificação dos Preceptores
                <div class="card p-6">
                    <h3 class="text-xl font-semibold text-gray-800 mb-4 flex items-center"><i class="fas fa-graduation-cap task-icon"></i> Qualificação dos Preceptores</h3>
                    <p class="text-gray-600 mb-4">Clique no espaço abaixo para revelar os tópicos!</p>
                    <div id="game-qualificacao-tasks" class="game-container flex-col cursor-pointer">
                        <p id="game-qualificacao-prompt" class="text-gray-500 text-lg font-semibold">Clique para começar!</p>
                    </div>
                </div>
      Dinâmica 4.2: Articulação com a Psicopedagogia
                <div class="card p-6">
                    <h3 class="text-xl font-semibold text-gray-800 mb-4 flex items-center"><i class="fas fa-comments task-icon"></i> Articulação com a Psicopedagogia</h3>
                    <p class="text-gray-600 mb-4">Clique no espaço abaixo para revelar os tópicos!</p>
                    <div id="game-psicopedagogia-tasks" class="game-container flex-col cursor-pointer">
                        <p id="game-psicopedagogia-prompt" class="text-gray-500 text-lg font-semibold">Clique para começar!</p>
                    </div>
                </div>
            </div>
        </section>
        <footer class="text-center text-gray-500 mt-10 text-sm">
            <p>&copy; 2024 Afya. Todos os direitos reservados.</p>
        </footer>
    </div>
    <script>
        const tasks = {
            'game-parceria-tasks': [
                "Participação em reuniões de planejamento pedagógico.",
                "Contribuição na elaboração de planos de ação.",
                "Criação de canal de comunicação formal."
            ],
            'game-matriz-tasks': [
                "Análise crítica da matriz curricular para aprimoramento de metodologias.",
                "Integração com a Comissão de Matriz, atuando como consultor pedagógico."
            ],
            'game-formacao-tasks': [
                "Realizar a Semana de Desenvolvimento Docente.",
                "Oferecer Workshops de Metodologias Ativas (PBL, TBL, etc.).",
                "Promover Capacitação em Tecnologias Educacionais.",
                "Realizar Ciclos de Estudo Temáticos."
            ],
            'game-acompanhamento-tasks': [
                "Oferecer um sistema de mentoria e acompanhamento.",
                "Realizar Observação de Pares (com agendamento prévio).",
                "Fornecer Consultoria Pedagógica individualizada."
            ],
            'game-assessoria-tasks': [
                "Oficinas de Construção de Itens de avaliação.",
                "Consultoria na elaboração de Casos Clínicos.",
                "Serviço de Revisão de Provas pré-aplicação."
            ],
            'game-osce-tasks': [
                "Desenho e Validação de Estações do OSCE.",
                "Formação de Avaliadores, padronizando critérios.",
                "Análise de Dados após o OSCE para identificar lacunas."
            ],
            'game-qualificacao-tasks': [
                "Estruturar um Programa de Capacitação Contínua para preceptores.",
                "Criar uma Comunidade de Prática para troca de experiências.",
                "Monitorar e Avaliar o impacto da capacitação na prática diária."
            ],
            'game-psicopedagogia-tasks': [
                "Formar um Comitê de Apoio Multiprofissional.",
                "Colaborar na criação de materiais para o curso de preceptoria."
            ]
        };
        const gameStates = {};
        function initGames() {
            for (const id in tasks) {
                gameStates[id] = false;
                const container = document.getElementById(id);
                if (container) {
                    container.addEventListener('click', () => showAllTasks(id));
                }
            }
        }
        function showAllTasks(id) {
            if (gameStates[id]) return;
            const container = document.getElementById(id);
            const prompt = document.getElementById(`${id}-prompt`);
            if (prompt) {
                prompt.classList.add('hidden');
            }
            tasks[id].forEach(taskText => {
                const taskElement = document.createElement('div');
                taskElement.classList.add('task-list-item', 'text-gray-800', 'text-sm', 'my-2', 'p-2', 'bg-white', 'rounded-lg', 'shadow-md', 'w-full');
                taskElement.innerHTML = `<i class="fas fa-check-circle text-green-500 mr-2"></i>${taskText}`;
                container.appendChild(taskElement);
            });
            gameStates[id] = true;
        }
        window.onload = initGames;
    </script>
</body></html>
