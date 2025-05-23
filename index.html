<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI_Bond_Bot</title>
    <style>
        body {
            background: linear-gradient(135deg, #2d1b4e, #3a2d5f);
            color: #d8c4ff;
            font-family: 'Roboto', 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            height: 100vh;
            overflow-y: auto;
            animation: gentleFade 2s ease-in-out infinite;
        }
        @keyframes gentleFade {
            0% { filter: brightness(1); }
            50% { filter: brightness(1.05); }
            100% { filter: brightness(1); }
        }
        .container {
            width: 90%;
            max-width: 450px;
            text-align: center;
            animation: smoothRise 1s ease-out;
        }
        @keyframes smoothRise {
            from { transform: translateY(30px) scale(0.95); opacity: 0; }
            to { transform: translateY(0) scale(1); opacity: 1; }
        }
        .header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 12px;
            background: rgba(58, 45, 95, 0.9);
            border: 2px solid #6b48ff;
            border-radius: 12px 12px 0 0;
            box-shadow: 0 0 15px rgba(107, 72, 255, 0.5);
            transition: all 0.4s ease;
        }
        .header:hover {
            background: rgba(74, 45, 138, 0.9);
            transform: scale(1.02);
        }
        .logo {
            font-size: 1.9em;
            color: #6b48ff;
            text-shadow: 0 0 8px rgba(107, 72, 255, 0.8);
            animation: softPulse 2s infinite;
        }
        @keyframes softPulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); text-shadow: 0 0 12px rgba(107, 72, 255, 0.9); }
            100% { transform: scale(1); }
        }
        .agent {
            font-size: 1em;
            color: #b8a4e0;
            animation: gentleBlink 1.5s infinite;
        }
        @keyframes gentleBlink {
            50% { opacity: 0.7; }
        }
        .content {
            background: rgba(45, 27, 78, 0.9);
            border: 2px solid #6b48ff;
            border-top: none;
            border-radius: 0 0 12px 12px;
            padding: 20px;
            animation: smoothReveal 0.8s ease-in-out;
        }
        @keyframes smoothReveal {
            from { opacity: 0; transform: scale(0.96); }
            to { opacity: 1; transform: scale(1); }
        }
        .buttons {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 12px;
            margin: 20px 0;
        }
        .button {
            background: linear-gradient(45deg, #6b48ff, #4a2d8a);
            color: #f0e6ff;
            padding: 12px;
            border-radius: 8px;
            cursor: pointer;
            text-align: center;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
            font-weight: 500;
            box-shadow: 0 0 8px rgba(107, 72, 255, 0.4);
        }
        .button::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 0;
            height: 0;
            background: rgba(240, 230, 255, 0.2);
            border-radius: 50%;
            transform: translate(-50%, -50%);
            transition: width 0.6s, height 0.6s;
        }
        .button:hover::before {
            width: 150px;
            height: 150px;
        }
        .button:hover {
            background: linear-gradient(45deg, #4a2d8a, #3a1f66);
            transform: translateY(-4px) scale(1.03);
            box-shadow: 0 0 15px rgba(107, 72, 255, 0.6);
        }
        .section {
            background: rgba(58, 45, 95, 0.7);
            border: 1px solid #6b48ff;
            border-radius: 8px;
            padding: 15px;
            margin: 15px 0;
            text-align: left;
            animation: softGlow 1.5s infinite;
        }
        @keyframes softGlow {
            0% { box-shadow: 0 0 5px #6b48ff; }
            50% { box-shadow: 0 0 10px #4a2d8a; }
            100% { box-shadow: 0 0 5px #6b48ff; }
        }
        .stats-list, .missions-list, .scanner-list, .trades-list, .referrals-list, .chat-messages {
            padding-left: 15px;
        }
        .stat-item, .mission-item, .scanner-item, .trade-item, .referral-item, .chat-message {
            display: flex;
            justify-content: space-between;
            margin: 10px 0;
            animation: slideInGentle 0.6s ease-out;
        }
        @keyframes slideInGentle {
            from { transform: translateX(-15px); opacity: 0.5; }
            to { transform: translateX(0); opacity: 1; }
        }
        .risk-bar {
            width: 100%;
            height: 10px;
            background: #3a2d5f;
            border-radius: 5px;
            overflow: hidden;
            margin: 10px 0;
        }
        .risk-fill {
            height: 100%;
            background: #6b48ff;
            border-radius: 5px;
            transition: width 1s ease;
            animation: riskPulse 3s infinite;
        }
        @keyframes riskPulse {
            0% { box-shadow: 0 0 0 #6b48ff; }
            50% { box-shadow: 0 0 10px #6b48ff; }
            100% { box-shadow: 0 0 0 #6b48ff; }
        }
        .loading {
            border: 4px solid rgba(58, 45, 95, 0.9);
            border-top: 4application/x-www-form-urlencoded4px solid #6b48ff;
            border-radius: 50%;
            width: 20px;
            height: 20px;
            animation: softSpin 1.2s linear infinite;
            margin: 15px auto;
            display: none;
        }
        @keyframes softSpin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        .notification {
            background: #4a2d8a;
            color: #d8c4ff;
            padding: 10px;
            border-radius: 5px;
            margin: 10px 0;
            animation: fadeInOut 2.5s ease-in-out;
            display: none;
        }
        @keyframes fadeInOut {
            0% { opacity: 0; transform: scale(0.9); }
            10% { opacity: 1; transform: scale(1); }
            90% { opacity: 1; transform: scale(1); }
            100% { opacity: 0; transform: scale(0.9); }
        }
        .chat-input {
            width: 70%;
            padding: 10px;
            margin: 10px 5px 10px 0;
            background: rgba(58, 45, 95, 0.7);
            border: 1px solid #6b48ff;
            border-radius: 5px;
            color: #d8c4ff;
            transition: all 0.3s ease;
        }
        .chat-input:focus {
            border-color: #4a2d8a;
            box-shadow: 0 0 8px #6b48ff;
        }
        .send-button {
            background: #6b48ff;
            color: #f0e6ff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s ease;
        }
        .send-button:hover {
            background: #4a2d8a;
            transform: scale(1.05);
            box-shadow: 0 0 10px #6b48ff;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <span class="agent">AI_Bond_Bot</span>
            <span class="logo">AI_Bond_Bot</span>
        </div>
        <div class="content">
            <div class="buttons">
                <div class="button" onclick="showMissions()">🌌 Торговые миссии</div>
                <div class="button" onclick="showScanner()">🔍 Рыночный сканер</div>
                <div class="button" onclick="showRisk()">⚠️ Уровень риска</div>
                <div class="button" onclick="showTrades()">📈 Текущие сделки</div>
                <div class="button" onclick="showReferrals()">👥 Рефералы</div>
                <div class="button" onclick="showSettings()">⚙️ Настройки</div>
            </div>
            <div id="missionsSection" class="section" style="display: none;">
                <h3>Торговые миссии</h3>
                <div class="missions-list" id="missionsList">
                    <div class="mission-item">Миссия 1: 0/3 успешных сделок</div>
                </div>
                <div class="notification" id="missionNotification"></div>
            </div>
            <div id="scannerSection" class="section" style="display: none;">
                <h3>Рыночный сканер</h3>
                <div class="scanner-list" id="scannerList">
                    <div class="scanner-item">KAS (Binance): Вероятность роста 72%</div>
                </div>
                <div class="loading" id="scannerLoading"></div>
            </div>
            <div id="riskSection" class="section" style="display: none;">
                <h3>Уровень риска</h3>
                <div class="risk-bar">
                    <div class="risk-fill" id="riskFill" style="width: 30%;"></div>
                </div>
                <div class="stats-list">
                    <div class="stat-item">Риск: Низкий</div>
                </div>
            </div>
            <div id="tradesSection" class="section" style="display: none;">
                <h3>Текущие сделки</h3>
                <div class="trades-list" id="tradesList">
                    <div class="trade-item">KAS (Binance): +2.5% <button class="send-button" onclick="closeTrade()">Закрыть</button></div>
                </div>
                <button class="button" onclick="openTrade()">Открыть сделку</button>
            </div>
            <div id="referralsSection" class="section" style="display: none;">
                <h3>Реферальная программа</h3>
                <div class="referrals-list" id="referralsList">
                    <div class="referral-item">Приглашено: 5</div>
                    <div class="referral-item">Доход: $50</div>
                    <div class="referral-item">Ссылка: <a href="#">t.me/AI_Bond_Bot?start=123</a></div>
                </div>
            </div>
            <div id="settingsSection" class="section" style="display: none;">
                <h3>Настройки</h3>
                <div class="stats-list">
                    <div class="stat-item">Стратегия: <span>DCA</span></div>
                    <div class="stat-item">Монета: <span>BTC</span></div>
                    <div class="stat-item">Объём сделки: <span>$100</span></div>
                </div>
                <button class="button" onclick="updateSettings()">Обновить</button>
            </div>
        </div>
    </div>

    <script>
        // Показ/скрытие секций
        function hideAllSections() {
            document.querySelectorAll('.section').forEach(section => section.style.display = 'none');
        }

        function showMissions() {
            hideAllSections();
            document.getElementById('missionsSection').style.display = 'block';
            updateMissions();
            showNotification('Новая торговая миссия доступна!');
        }

        function showScanner() {
            hideAllSections();
            document.getElementById('scannerSection').style.display = 'block';
            updateScanner();
            document.getElementById('scannerLoading').style.display = 'block';
            setTimeout(() => document.getElementById('scannerLoading').style.display = 'none', 1500);
        }

        function showRisk() {
            hideAllSections();
            document.getElementById('riskSection').style.display = 'block';
            updateRisk();
        }

        function showTrades() {
            hideAllSections();
            document.getElementById('tradesSection').style.display = 'block';
            updateTrades();
        }

        function showReferrals() {
            hideAllSections();
            document.getElementById('referralsSection').style.display = 'block';
            updateReferrals();
        }

        function showSettings() {
            hideAllSections();
            document.getElementById('settingsSection').style.display = 'block';
        }

        // Обновление данных
        let missionProgress = 0;
        let riskLevel = 30;
        let scannerData = ['KAS (Binance): Вероятность роста 72%'];
        let trades = ['KAS (Binance): +2.5%'];
        let referrals = {
            invited: 5,
            income: 50,
            link: 't.me/AI_Bond_Bot?start=123'
        };

        function updateMissions() {
            const missionsList = document.getElementById('missionsList');
            missionsList.innerHTML = `<div class="mission-item">Миссия 1: ${missionProgress}/3 успешных сделок</div>`;
        }

        function updateScanner() {
            const scannerList = document.getElementById('scannerList');
            scannerList.innerHTML = scannerData.map(s => `<div class="scanner-item">${s}</div>`).join('');
        }

        function updateRisk() {
            document.getElementById('riskFill').style.width = `${riskLevel}%`;
            document.querySelector('#riskSection .stat-item').innerText = `Риск: ${riskLevel < 40 ? 'Низкий' : riskLevel < 70 ? 'Средний' : 'Высокий'}`;
        }

        function updateTrades() {
            const tradesList = document.getElementById('tradesList');
            tradesList.innerHTML = trades.map(t => `<div class="trade-item">${t} <button class="send-button" onclick="closeTrade()">Закрыть</button></div>`).join('');
        }

        function updateReferrals() {
            const referralsList = document.getElementById('referralsList');
            referralsList.innerHTML = `
                <div class="referral-item">Приглашено: ${referrals.invited}</div>
                <div class="referral-item">Доход: $${referrals.income}</div>
                <div class="referral-item">Ссылка: <a href="${referrals.link}">${referrals.link}</a></div>
            `;
        }

        function openTrade() {
            trades.push(`ETH (Bybit): 0%`);
            updateTrades();
            showNotification('Сделка открыта: ETH (Bybit)');
        }

        function closeTrade() {
            trades.pop();
            missionProgress = Math.min(missionProgress + 1, 3);
            updateTrades();
            updateMissions();
            showNotification('Сделка закрыта! Прибыль зафиксирована.');
        }

        function updateSettings() {
            showNotification('Настройки обновлены!');
        }

        function showNotification(message) {
            const notification = document.getElementById('missionNotification');
            notification.style.display = 'block';
            notification.innerText = message;
            setTimeout(() => notification.style.display = 'none', 2500);
        }

        // Динамика
        setInterval(() => {
            missionProgress = Math.min(missionProgress + 1, 3);
            updateMissions();
            if (missionProgress === 3) showNotification('Миссия завершена! Награда: +$50');
            scannerData = [`KAS (Binance): Вероятность роста ${Math.floor(Math.random() * 30 + 70)}%`];
            updateScanner();
            riskLevel = Math.min(Math.max(riskLevel + (Math.random() * 20 - 10), 0), 100);
            updateRisk();
        }, 5000); // Обновление каждые 5 секунд
    </script>
</body>
</html>
