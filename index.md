<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D3h0000066WtN',
				'Fan_Bot',
				'https://hometownticketing1.my.site.com/ESWFanBot1718379706705',
				{
					scrt2URL: 'https://hometownticketing1.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://hometownticketing1.my.site.com/ESWFanBot1718379706705/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
