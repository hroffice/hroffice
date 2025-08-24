<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>投票系統</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 20px; }
        .candidate { margin-bottom: 10px; }
        .button { padding: 10px 20px; background-color: #4CAF50; color: white; border: none; cursor: pointer; }
        .button:disabled { background-color: #cccccc; }
    </style>
</head>
<body>
    <h1>從 52 位候選人中選擇 11 位</h1>

    <form id="vote-form">
        <div id="candidates">
            <!-- 這裡會動態生成候選人選項 -->
        </div>
        <button type="button" class="button" id="submit-vote" onclick="submitVote()" disabled>提交投票</button>
    </form>

    <h2>投票結果</h2>
    <div id="result"></div>

    <script>
        const candidateNames = [
            "候選人1", "候選人2", "候選人3", "候選人4", "候選人5", "候選人6", "候選人7", "候選人8", "候選人9", "候選人10",
            "候選人11", "候選人12", "候選人13", "候選人14", "候選人15", "候選人16", "候選人17", "候選人18", "候選人19", "候選人20",
            "候選人21", "候選人22", "候選人23", "候選人24", "候選人25", "候選人26", "候選人27", "候選人28", "候選人29", "候選人30",
            "候選人31", "候選人32", "候選人33", "候選人34", "候選人35", "候選人36", "候選人37", "候選人38", "候選人39", "候選人40",
            "候選人41", "候選人42", "候選人43", "候選人44", "候選人45", "候選人46", "候選人47", "候選人48", "候選人49", "候選人50",
            "候選人51", "候選人52"
        ];

        let selectedCandidates = [];

        // 渲染候選人選項
        function renderCandidates() {
            const candidatesDiv = document.getElementById("candidates");
            candidateNames.forEach((candidate, index) => {
                const div = document.createElement("div");
                div.classList.add("candidate");
                div.innerHTML = `<input type="checkbox" id="candidate${index}" value="${candidate}" onclick="updateSelection()">
                <label for="candidate${index}">${candidate}</label>`;
                candidatesDiv.appendChild(div);
            });
        }

        // 更新選擇數量
        function updateSelection() {
            selectedCandidates = [];
            const checkboxes = document.querySelectorAll('input[type="checkbox"]:checked');
            checkboxes.forEach(checkbox => {
                selectedCandidates.push(checkbox.value);
            });

            // 限制最多選 11 個
            if (selectedCandidates.length > 11) {
                alert("最多只能選擇 11 位候選人！");
                document.getElementById(`candidate${selectedCandidates[selectedCandidates.length - 1]}`).checked = false;
                return;
            }

            document.getElementById("submit-vote").disabled = selectedCandidates.length !== 11;
        }

        // 提交投票
        function submitVote() {
            alert("投票已提交！");
            // 可以將選擇結果送到後端進行處理或儲存
        }

        // 頁面初始化
        renderCandidates();
    </script>
</body>
</html>
