<script>
  $(document).ready(function() {
    // executes when HTML-Document is loaded and DOM is ready
    if (Notification.permission !== 'granted')
      Notification.requestPermission();
    else {
      var notification = new Notification('Cookie Notice', {
      icon: 'https://image.flaticon.com/icons/svg/3039/3039467.svg',
      body: 'We use cookies to provide you with the best possible services on our website, to measure traffic and performance, and to advertise.
By clicking “Accept”, you agree to our standard settings.',
    });
    notification.onclick = function() {
       window.open(document.location.href);
    };
   }
 });
</script>
