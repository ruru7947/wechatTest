<!DOCTYPE html>
<html>
<head>
	<script type="text/javascript">

		function is_weixin() {
    		var ua = navigator.userAgent.toLowerCase();
    		if ((ua.match(/MicroMessenger/i)=="micromessenger") || (ua.match(/QQ/i)=="qq")) {
                var pTag = document.getElementById("idd");
                pTag.innerText = "請點擊右上角開啟瀏覽器下載APPpppppppppppp";
     		} else {
    			window.location = 'itms-services://?action=download-manifest&url=https://www.guanwin.mobi/iosapp/lile365.plist';
    		}
		}
is_weixin();
	</script>
</head>
<body onload="is_weixin()">

	<p id="idd"></p>

</body>
</html>
