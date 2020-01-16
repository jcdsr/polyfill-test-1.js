pacckage.json version

"classlist.js": "1.1.20150312",
 "core-js": "~3.6.3",
 "event-source-polyfill": "^1.0.12",
 "js-polyfills": "^0.1.42",
 "web-animations-js": "2.3.2",
     "zone.js": "~0.10.2"
 
 
content of polyfill.ts

import 'classlist.js';  
import "core-js/stable";
import 'core-js/es/reflect';
import 'event-source-polyfill/src/eventsource.min.js'
import 'js-polyfills/polyfill.min.js'
import 'web-animations-js';  

    (window as any).__Zone_disable_requestAnimationFrame = true; // disable patch requestAnimationFrame
    (window as any).__zone_symbol__UNPATCHED_EVENTS = ['resize'];


import 'zone.js';

