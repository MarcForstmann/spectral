---
title: Gottesdienst
layout: delight
menu:
sitemap: false
---
<div id="pano" style="width:100%;height:100%;">
	<noscript><table style="width:100%;height:100%;"><tr style="vertical-align:middle;text-align:center;"><td>ERROR:<br><br>Javascript not activated<br><br></td></tr></table></noscript>
	
	<div id="player"></div>
    <script type="text/javascript">
        var conf = {
            key: 'd4b1b6a7-17fc-47cf-84cc-4fb255ae4752',
            source: {
                title: "Gottesdienst",
                description: "Ein heiliges Experiment in VR/360°",
                dash: '//inside360.tv/assets/films/messe/dash',
                hls: '//inside360.tv/assets/films/messe/hls',
                poster: '//inside360.tv/assets/films/messe/thumbnail_web-gottesdienst-compressor.jpg',
                vr: {
                    startPosition: 0,
                    contentType: 'single',
                    initialRotation: 'true',
                    initialRotateRate: 0.07
                }
            }
        };
        var player = bitmovin.player("player");
            player.setup(conf).then(function(value) {
                // Success
                console.log("Successfully created bitmovin player instance");
            }, function(reason) {
                // Error!
                console.log("Error while creating bitmovin player instance");
            });
    </script>
	
</div>