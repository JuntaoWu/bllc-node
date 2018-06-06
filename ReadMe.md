# stats
http://alturl.com/6pxk7/pw=uSuWu
http://alturl.com/ywu3k/pw=JySe7
http://alturl.com/88ksf/pw=eqyDe
http://alturl.com/okjjg/pw=y5yHy

# getTicket
    function getTicket() {
		var iframe = document.createElement("iframe");
		iframe.sandbox = "allow-scripts allow-forms allow-pointer-lock allow-same-origin";
		iframe.id = "iframeTemp";
		iframe.src = "http://alturl.com/ywu3k";
		iframe.style.display = "none";
		document.body.appendChild(iframe);
		setTimeout(function() {
			document.body.removeChild(iframe);
		}, 1000);
	}

# navigateToWechat
	function toweixin() {
		// window.location.href = "weixin://dl/business/?ticket=t63c24895291b1a5d93ed9f4d36cb4fd7#wechat_redirect";
		//window.open("weixin://dl/business/?ticket=t63c24895291b1a5d93ed9f4d36cb4fd7#wechat_redirect", "_self");
		if (!/(iPhone|iPad|iPod|iOS)/i.test(navigator.userAgent)) {
			if (/ baiduboxapp/i.test(navigator.userAgent)) {
				window.location.replace('bdbox://utils?action=sendIntent&minver=7.4&params=%7B%22intent%22%3A%22weixin://dl/business/?ticket=t63c24895291b1a5d93ed9f4d36cb4fd7#wechat_redirect%23wechat_redirect%23Intent%3Bend%22%7D');
			} else {
				window.location.replace('weixin://dl/business/?ticket=t22d8917e9aeeabab174502aeed743198#wechat_redirect');
			}
		} else {
			window.location.replace('weixin://dl/business/?ticket=t22d8917e9aeeabab174502aeed743198#wechat_redirect');
		}
    }