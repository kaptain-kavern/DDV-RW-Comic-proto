---
layout: twitch
title: My Twitch TV
permalink: /twitch/
---
<div class="row">
    <div class="col-md-8">
        <script src= "https://player.twitch.tv/js/embed/v1.js"></script>
        <div id="{PLAYER_DIV_ID}"></div>
        <script type="text/javascript">
            var options = {
                width: 768,
                height: 432,
                channel: "{bachheart}",
                //video: "{VIDEO_ID}"
            };
            var player = new Twitch.Player("{PLAYER_DIV_ID}", options);
            player.setVolume(0.5);
        </script>
    </div>
    <div class="col-md-4">
        <iframe frameborder="0"
            scrolling="no"
            id="chat_embed"
            src="https://www.twitch.tv/bachheart/chat"
            height="432"
            width="300">
        </iframe>
    </div>
</div>



<div class="mt50"></div>