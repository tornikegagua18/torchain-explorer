<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>🔮 TORCHAIN Explorer</title>
  <style>
    body {
      background-color: #0d0d0d;
      color: #00ffcc;
      font-family: monospace;
      padding: 20px;
    }
    h1 {
      color: #ffcc00;
    }
    .tx {
      margin-bottom: 20px;
      border-bottom: 1px dashed #444;
      padding-bottom: 10px;
    }
    .tx strong {
      color: #ff6666;
    }
    .tx em {
      color: #999;
    }
    .tx a {
      text-decoration: none;
      color: #ff6666;
    }
    .tx a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <h1>🔮 TORCHAIN Explorer</h1>
  <div id="tx-list">Loading ritual scroll...</div>

  <script>
    fetch("gateway_log.json", { cache: "no-store" })
      .then(res => res.json())
      .then(data => {
        const container = document.getElementById("tx-list");
        data.reverse().forEach(tx => {
          const div = document.createElement("div");
          div.className = "tx";
          const link = tx.explorer_url || `https://torchain.explorer/tx/${tx.tx_hash}`;
          div.innerHTML = `
            <a href="${link}" target="_blank">
              <strong>${tx.tx_hash}</strong>
            </a><br>
            ${tx.amount} ${tx.token} → ${tx.address}<br>
            <em>${tx.timestamp}</em>`;
          container.appendChild(div);
        });
      })
      .catch(err => {
        document.getElementById("tx-list").innerText = "⚠️ Scroll not found.";
        console.error("Scroll fetch failed:", err);
      });
  </script>
</body>
</html>

