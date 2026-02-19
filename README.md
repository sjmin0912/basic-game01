# basic-game01




<!-- <!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>게임 맵 선택</title>
    <style>
        body {
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 100%);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            font-family: Arial, sans-serif;
        }

        .map-container {
            text-align: center;
            color: white;
        }

        h1 {
            margin-bottom: 40px;
        }

        /* 중앙 시작점 */
        .start-node {
            width: 80px;
            height: 80px;
            background: #51cf66;
            border-radius: 50%;
            margin: 0 auto 40px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            cursor: pointer;
        }

        /* 분기 */
        .branches {
            display: flex;
            justify-content: space-around;
            gap: 20px;
            flex-wrap: wrap;
        }

        /* 각 노드 */
        .node {
            width: 100px;
            height: 100px;
            background: #4a9eff;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 14px;
            cursor: pointer;
            transition: all 0.3s;
            border: 3px solid gold;
        }

        .node:hover {
            transform: scale(1.1);
            background: #6c5ce7;
        }

        .node.locked {
            background: #888;
            cursor: not-allowed;
            opacity: 0.5;
        }
    </style>
</head>
<body>
    <div class="map-container">
        <h1>🎮 게임 맵 선택</h1>
        
        <div class="start-node" onclick="selectMap('start')">
            START
        </div>

        <div class="branches">
            <div class="node" onclick="selectMap('easy')">
                🌱 Easy
            </div>
            <div class="node" onclick="selectMap('normal')">
                🔥 Normal
            </div>
            <div class="node" onclick="selectMap('hard')">
                ⚡ Hard
            </div>
        </div>
    </div>

    <script>
        function selectMap(difficulty) {
            console.log(difficulty + ' 선택됨');
            alert(difficulty + ' 난이도로 시작합니다!');
        }
    </script>
</body>
</html>
 -->
