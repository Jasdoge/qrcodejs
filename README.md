# QRCode.js
This is a fork of QRCode.js javascript library for making QRCode. This one simply takes in a bit of text and outputs an inline SVG. That's it.
This fork has no dependencies.

## Basic Usages
```
<div id="qrcode"></div>
<script type="text/javascript">
	document.getElementById("qrcode").innerHTML = QRCode("Ello ello! I am an inline SVG!");
</script>
```

You can set the error correction as the second argument:
```
QRCode("Ello ello! I am an inline SVG!", QRCode.CorrectLevel.M);
```

Set the width and height of the QR code with regular ol fashioned CSS:
```
#qrcode{
	width:256px;
	height:256px;
	background:#FFF;
}
```

## Browser Compatibility
No idea :D

## License
MIT License

## Contact
twitter @jasdoge

Make sure you check out the original repo for this fork if you need to do fancier stuff!

