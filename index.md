<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body onload="is_weixin()">

	<p id="idd"></p>

	<script type="text/javascript">

		function is_weixin() {
    		var ua = navigator.userAgent.toLowerCase();
    		if ((ua.match(/MicroMessenger/i)=="micromessenger") || (ua.match(/QQ/i)=="qq")) {
                var pTag = document.getElementById("idd");
                pTag.innerText = "請點擊右上角開啟瀏覽器下載APPpppppppppppp";
     		} else {
    			window.location = 'http://android6869.gwinplay.com/jin188_3.apk';
    		}
		}

	</script>

</body>
</html>
