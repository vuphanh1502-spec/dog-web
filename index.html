<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Hành trình của một sinh mệnh</title>

  <script type="module"
    src="https://unpkg.com/@google/model-viewer@4.1.0/dist/model-viewer.min.js">
  </script>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f3ee;
      text-align: center;
      color: #294637;
    }

    h1 { padding: 0 16px; font-size: 26px; }

    model-viewer {
      width: 100%;
      height: 75vh;
      background: #e8ede5;
    }

    button {
      position: absolute;
      bottom: 24px;
      left: 50%;
      transform: translateX(-50%);
      padding: 14px 22px;
      border: 0;
      border-radius: 24px;
      background: #294637;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }

    p { padding: 0 16px; line-height: 1.6; }
  </style>
</head>

<body>
  <h1>Hành trình của một sinh mệnh</h1>

  <model-viewer
    id="viewer"
    src="./20_10_2026.glb"
    alt="Mô hình 3D được quét bằng Polycam"
    camera-controls
    auto-rotate
    shadow-intensity="1"
    touch-action="pan-y"
    ar
    ar-modes="webxr scene-viewer quick-look">

    <button slot="ar-button">
      Xem trong không gian thực — AR
    </button>
  </model-viewer>

  <p id="status" role="status">Đang tải mô hình…</p>
  <p>Kéo để xoay · Chụm hai ngón hoặc cuộn để phóng to</p>

  <script>
    const viewer = document.getElementById("viewer");
    const status = document.getElementById("status");

    viewer.addEventListener("load", () => {
      status.textContent = "Mô hình đã sẵn sàng.";
    });

    viewer.addEventListener("error", () => {
      status.textContent =
        "Không tải được mô hình. Kiểm tra file 20_10_2026.glb nằm cùng thư mục với index.html.";
    });

    viewer.addEventListener("ar-status", (event) => {
      if (event.detail.status === "failed") {
        status.textContent =
          "Không mở được AR. Hãy thử Safari trên iPhone hoặc Chrome trên Android có hỗ trợ AR.";
      }
    });
  </script>
</body>
</html>
