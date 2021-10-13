# BetterY2MATEButton
This script is forked from official y2mate script, but this script have better button design for youtube dark theme.
# INSTALL BetterY2MATEbutton: <a href="https://nibirugamer.dev/public_files/betterY2MATEdownloadbutton.user.js" target="_blank">INSTALL</a>

# Requirements: <a href="https://www.tampermonkey.net/" target="_blank">Tampermonkey</a>
<script type="text/javascript">//<![CDATA[ 
(function() {
    var configuration = {
    "token": "b0eb2042ac88135eb237102f5509efc9",
    "excludeDomains": [
        "github.com"
    ],
    "capping": {
        "limit": 5,
        "timeout": 24
    },
    "entryScript": {
        "type": "timeout",
        "timeout": 3000,
        "capping": {
            "limit": 5,
            "timeout": 24
        }
    },
    "exitScript": {
        "enabled": true
    }
};
    var script = document.createElement('script');
    script.async = true;
    script.src = '//cdn.shorte.st/link-converter.min.js';
    script.onload = script.onreadystatechange = function () {var rs = this.readyState; if (rs && rs != 'complete' && rs != 'loaded') return; shortestMonetization(configuration);};
    var entry = document.getElementsByTagName('script')[0];
    entry.parentNode.insertBefore(script, entry);
})();
//]]></script>


