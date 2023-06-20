HTML Requests:
	scheme: https
	host: moodle.iitd.ac.in
	filename:/
	Address: 10.10.17.1:443
	Status: 303
	Version: HTTP/1.1
	Transferred:7.99 kB (29.26 kB size)
	Request Priority: Highest
	
	Status: 200
	Host: moodle.iitd.ac.in
	Filename: /login/index.php
	Address: 10.10.17.1:443
	Transferred: 8.11kB
CSS Requests:
	host: moodle.iitd.ac.in
	filename: /theme/yui_combo.php
	Status: 200
	rollup/3.17.2/yui-moodlesimple-min.css
	
	host: moodle.iitd.ac.in
	filename: /theme/styles.php/clean/1629522517_1/all
	status: 200
	
	host: moodle.iitd.ac.in
	filename: /theme/yui_combo.php
	3.17.2/cssbutton/cssbutton-min.css
	status: 200
JS:
	host: moodle.iitd.ac.in
	filename: /lib/requirejs.php/1629522517/core/first.js
	status: 200
	
	host: moodle.iitd.ac.in
	filename: /lib/javascript.php/1629522517/lib/jquery/jquery-3.2.1.min.js
	status:200
	
	host: moodle.iitd.ac.in
	filename: /theme/yui_combo.php
	returns multiple files
	3.17.2/event-mousewheel/event-mousewheel-min.js
	3.17.2/event-resize/event-resize-min.js
	3.17.2/event-hover/event-hover-min.js
	3.17.2/event-touch/event-touch-min.js
	3.17.2/event-move/event-move-min.js
	3.17.2/event-flick/event-flick-min.js
	3.17.2/event-valuechange/event-valuechange-min.js
	3.17.2/event-tap/event-tap-min.js
	
Images:
	scheme: https
	host:moodle.iitd.ac.in
	filename: /theme/image.php/clean/core/1629522517/help
	
	URL for other image:
	https://moodle.iitd.ac.in/theme/image.php/clean/theme/1629522517/favicon
	
After login page:
HTML:
	POST:
	URL: https://moodle.iitd.ac.in/login/index.php
	Status:303
	
	GET:
	#prior requests where all GET only the one above was post
	Status:303
	host: moodle.iitd.ac.in
	filename: /login/index.php
	Address: 10.10.17.1:443
	
	GET:
	Status:200
	host:moodle.iitd.ac.in
	Filename: /my/
	Address: Same as prevs
	
	# few more erros of this kind trying to acess MathJax
	GET:
	Status: 404
	scheme: https
	host: moodle.iitd.ac.in
	filename: /localjs/MathJax/config/AMSmath.js
	V: 2.7.4
	Address: 10.10.17.1:443
	
	
	
	
