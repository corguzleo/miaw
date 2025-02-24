<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
  </head>
  <body>
  </body>
  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DHu00000CIkCt',
				'SDO_Messaging_for_Web',
				'https://clozano-241105-36-demo.my.site.com/ESWSDOMessagingforWeb1730841210419',
				{
					scrt2URL: 'https://clozano-241105-36-demo.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://clozano-241105-36-demo.my.site.com/ESWSDOMessagingforWeb1730841210419/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</html>
