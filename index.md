<html>
	.appBackground {
    position: relative;
    background-image: url(".../img/background.jpg");
    background-repeat:no-repeat;
    background-size:100% 100vh;
}
        <body>
		<script type='text/javascript'>
	              function initEmbeddedMessaging() {
		            try {
			          embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

          			embeddedservice_bootstrap.init(
				        '00DAe0000019s0b',
				        'UK_Owner_Cottages',
				        'https://awaze--msdevelop.sandbox.my.site.com/ESWUKOwnerCottages1705493623899',
				        {
					      scrt2URL: 'https://awaze--msdevelop.sandbox.my.salesforce-scrt.com'
				        }
			          );
		            } catch (err) {
			          console.error('Error loading Embedded Messaging: ', err);
		            }
	              };
                </script>
                <script type='text/javascript' src='https://awaze--msdevelop.sandbox.my.site.com/ESWUKOwnerCottages1705493623899/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
        </body>
</html>
