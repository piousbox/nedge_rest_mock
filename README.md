
This thing helps test horizon_nexenta_dashboard. It's a static copy of the stats API exposed by the ReST admin worker.

=== Installation ===

Run

 sudo apt-get install apache2

Then, checkout this repo to /var/www/html:

 cd /var/www ; mv html html-old ; git clone <this-repo> ; mv <this-repo> html

This makes the API endpoints available as static json, which acts as a mock.


