# Welcome to me trying to set up multiple web pages on github
<head>
<html>
<body>
<p>
This page has the embed code generated after the refactor on 2/24/21. It has been updated on 3/1/21.</p>


        <script>
  (() => {
    const resizer = document.createElement('script')
    resizer.src = 'https://cdn.jsdelivr.net/npm/iframe-resizer@4.2.11/js/iframeResizer.min.js'
    document.body.appendChild(resizer)
    resizer.addEventListener('load', function () {
      const iframe = document.createElement('iframe')
      iframe.id = 'crowdsmart-embed-app'
      iframe.src = 'https://www.crowdsmartstage.ai/embed/evaluation/logohere/38a8b05e-72d3-11eb-82b2-0ad589fedacf/47c28d76-72d3-11eb-bc0f-0ad589fedacf'
      document.body.appendChild(iframe)
      iframe.addEventListener('load', function () {
        iFrameResize({}, '#crowdsmart-embed-app')
      })
    })
  })()
</script>
        <style>
  #crowdsmart-embed-app {
    background: transparent;
    border: none;
    bottom: 0;
    max-height: 100vh;
    max-width: 100vw;
    position: fixed;
    right: 0;
    width: 420px;
  }
</style>
      
