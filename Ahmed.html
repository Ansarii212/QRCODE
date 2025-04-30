<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>تحويل إلى QR</title>
  <script src="https://cdn.jsdelivr.net/npm/qrcode/build/qrcode.min.js"></script>
</head>
<body style="text-align:center; font-family:Arial">

  <h2>مولد QR Code</h2>
  <input type="text" id="link" placeholder="ادخل الرابط" style="width:300px" />
  <button onclick="generateQR()">إنشاء</button>
  <br><br>

  <div id="qrcode" style="margin-top:20px;"></div>
  <br>
  <button onclick="downloadQR()" style="display:none;" id="saveBtn">حفظ الصورة</button>

  <script>
    let canvasElement;

    function generateQR() {
      const link = document.getElementById('link').value;
      const qrDiv = document.getElementById('qrcode');
      qrDiv.innerHTML = '';
      QRCode.toCanvas(link, { width: 250 }, function (err, canvas) {
        if (err) {
          console.error(err);
          return;
        }
        canvasElement = canvas;
        qrDiv.appendChild(canvas);
        document.getElementById('saveBtn').style.display = 'inline-block';
      });
    }

    function downloadQR() {
      if (!canvasElement) return;
      const link = document.createElement('a');
      link.download = 'qrcode.png';
      link.href = canvasElement.toDataURL("image/png");
      link.click();
    }
  </script>

</body>
</html>
