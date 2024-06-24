<html>

<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DWK000000Axek',
				'MessagingInAppAndWebEmbedded',
				'https://procoretechnologies--serv2value.sandbox.my.site.com/ESWMessagingInAppAndWebEm1718288070365',
				{
					scrt2URL: 'https://procoretechnologies--serv2value.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://procoretechnologies--serv2value.sandbox.my.site.com/ESWMessagingInAppAndWebEm1718288070365/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  
</html>
