<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D8D000001D10r',
				'chatbotdiego',
				'https://tnsi--stg.sandbox.my.site.com/ESWchatbotdiego1725551776024',
				{
					scrt2URL: 'https://tnsi--stg.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://tnsi--stg.sandbox.my.site.com/ESWchatbotdiego1725551776024/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

 
  </body>
</html>
