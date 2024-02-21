<script>
    export let data;
</script>

<h1>BLOG</h1>

<ul>
    <!-- <li><a href="/blog/one">One</a></li> -->
    <!-- <li><a href="/blog/two">Two</a></li> -->
    <!-- <li><a href="/blog/three">Three</a></li> -->
    {#each data.summaries as { slug, title }}
        <li><a href="/blog/{slug}">{title}</a></li>
    {/each}
</ul>
