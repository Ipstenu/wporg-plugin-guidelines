<h4>13. Plugins must use WordPress' default libraries.</h4>

WordPress includes a number of useful libraries, such as jQuery, Atom Lib, SimplePie, PHPMailer, PHPass, and more. For security and stability reasons plugins may not include those libraries in their own code. Instead plugins must use the versions of those libraries packaged with WordPress.

For a list of all javascript libraries included in WordPress, please review <a href="https://developer.wordpress.org/reference/functions/wp_enqueue_script/#notes">Default Scripts Included and Registered by WordPress</a>.