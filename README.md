<h2>qrcodejs Sample</h2>

### qrcodejs: https://davidshimjs.github.io/qrcodejs/

### cdn: https://cdn.rawgit.com/davidshimjs/qrcodejs/gh-pages/qrcode.min.js

### add above CDN in your html script tag like below,

```
<script src="https://cdn.rawgit.com/davidshimjs/qrcodejs/gh-pages/qrcode.min.js"></script>

you can create qrcode from above js library like below,
<body >
<div id="qrcode-1">
<script type="text/javascript">


var qrcode = new QRCode(document.getElementById("qrcode-1"), {
	text: "single qr",
	width: 100,
	height: 100,
	colorDark : "#000000",
	colorLight : "#ffffff",
	correctLevel : QRCode.CorrectLevel.H
});

</script>
</body>
```
