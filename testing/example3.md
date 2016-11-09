---
layout: page
title: "Testing: Example 3"
meta_title: "Testing - Example 3"
show_meta: false
header:
   image_fullwidth: "amc.jpg"
subheadline: ""
teaser: ""
permalink: "/testing/example3/"
---

## Example 3

<script type='text/javascript'>
    (function() {
        var f = function() {
              EF.init({ eventType: "transaction",
                        transactionProperties : "ev_order_complete=1",
                        segment : "", 
                        searchSegment : "",
                        sku : "",
                        userid : "714",
                        pixelHost : "pixel.everesttech.net"
                        
                        , allow3rdPartyPixels: 1});
              EF.main();
        };
        window.EF = window.EF || {}; 
        if (window.EF.main) {
            f();
            return;
        }
        window.EF.onloadCallbacks = window.EF.onloadCallbacks || [];
        window.EF.onloadCallbacks[window.EF.onloadCallbacks.length] = f;
        if (!window.EF.jsTagAdded) {
            var efjs = document.createElement('script'); efjs.type = 'text/javascript'; efjs.async = true;
            efjs.src = 'https://www.everestjs.net/static/st.v3.js';
            var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(efjs, s);
            window.EF.jsTagAdded=1;
        }
    })();
</script>
<noscript><img src="https://pixel.everesttech.net/714/t?ev_order_complete=1" width="1" height="1"/></noscript>

