<!-- Comment BEGIN -->
<div id="gitalk-container"></div>
<script>
  const gitalk = new Gitalk({
    clientID: '97d460ca7fc4d87afecc',
    clientSecret: 'b5541550b119c5532fa60e33ad663fb74759286e',
    repo: 'none',
    owner: 'imgs',
    admin: ['imgs'],
    language: 'zh-CN',
    id: location.pathname,      // Ensure uniqueness and length less than 50
    distractionFreeMode: false  // Facebook-like distraction free mode
  })

  gitalk.render('gitalk-container')
</script>
<!--
<div id="disqus_thread"></div>
<script>
-->
<!--
/**
*  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
*  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables*/
/*
var disqus_config = function () {
this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
};
*/
(function() { // DON'T EDIT BELOW THIS LINE
var d = document, s = d.createElement('script');
s.src = 'https://x55.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
-->
<!-- Comment END -->
