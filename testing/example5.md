---
layout: page
title: "Testing: Example 5"
meta_title: "Testing - Example 5"
show_meta: false
header:
   image_fullwidth: "amc.jpg"
subheadline: ""
teaser: ""
permalink: "/testing/example5/"
---

## Example 5

<script type='text/javascript'>
    (function() {
        var f = function() {
              EF.init({ eventType: "transaction",
                        transactionProperties : "ev_quote_completed=1",
                        segment : "", 
                        searchSegment : "",
                        sku : "",
                        userid : "81",
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
<noscript><img src="https://pixel.everesttech.net/81/t?ev_quote_completed=1" width="1" height="1"/></noscript>
