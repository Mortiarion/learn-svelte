<script>
    export let data;
</script>

<h1>BLOG post {data.post.slug}</h1>
<p>This is the <strong>BLOG</strong> page {data.post.slug}</p>

<h2>{data.post.title}</h2>
<div>{@html data.post.content}</div>
