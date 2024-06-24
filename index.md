<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DWK000000Axek',
				'MIAW_for_External_site',
				'https://procoretechnologies--serv2value.sandbox.my.site.com/ESWMIAWforExternalsite1719222344291',
				{
					scrt2URL: 'https://procoretechnologies--serv2value.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://procoretechnologies--serv2value.sandbox.my.site.com/ESWMIAWforExternalsite1719222344291/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
  
</html>
