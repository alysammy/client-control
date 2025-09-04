The following code needs to be added to each website's all available themes

<script src="https://raw.githack.com/alysammy/client-control/main/safety.js" defer="defer"></script>
<script>
        document.addEventListener('DOMContentLoaded', function() {
          setTimeout(() => {
            let name = '[Your Channel Name Goes Here]';
            safetyChecker(name);
    },5000)
        });
    </script>
