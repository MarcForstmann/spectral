---
title: |
  HL Cruises MS Europa 2
layout: page
image_path: "../images/fanmeile-euro2016-berlin-coca-cola.jpg"
menu: main
sitemap: false
bitmovin: true
---

<div class="align-center">
<h1>Preview HL-Cruises MS Europa 2 - 2016 <br />Mediterranean Sea</h1>

<div id="player">
</div>
<script type="text/javascript">

    var conf = {
        key:       "04cee7a5-3b04-467d-ac22-e8dfa60ccc7d",
        source: {
          dash:        "//eu-storage-bitcodin.storage.googleapis.com/bitStorage/10697_11d1eadd57b1de2a3db2366f9edd13d2/377887_d017515730aed923b7fddc832a56add2/377887.mpd",
          vr: {
               startupMode       : bitdash.VR.STARTUP_MODE.MONO_2D,
               startPosition     : 180,
               initialRotation   : true,
               initialRotateRate : 0.025
            }
        }
    };
    var player = bitdash("player");
    player.setup(conf).then(function(value) {
        // Success
        console.log("Successfully created bitdash player instance");
    }, function(reason) {
        // Error!
        console.log("Error while creating bitdash player instance");
    });
</script>

</div>
