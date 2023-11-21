<script setup>
    import articles from "../data/articles.json"
</script>
<template>
    <!-- CONTENT -->
    <section id="content">
        <article v-for="(article, index) in articles" :key="article.id" class="article">
            <h2>{{ article.title }}</h2>
            <p>{{ article.text }}</p>
        </article>
    </section>
    <!-- SIDEBAR -->
    <aside>
        <h2>SIDEBAR</h2>
        <input type="text">
        <input type="submit" value="Search" />
    </aside>
    <!-- Clear:Both - stop floating elements from overflowing into other elements -->
    <div style="clear: both;"></div>
</template>

<style scoped>
    #content {
        float: left;
        width: calc(80% - 80px);
        min-height: 500px;
        border-radius: 21px;
        margin-top: 5px;
        background: #252A2E;
        padding: 40px;

    }

    .article {
        color: #fff;
        margin-top: 15px;
        margin-bottom: 15px;
        padding-bottom: 10px;
        border-bottom: 1px solid #eee;
    }

    .article h2 {
        font-size: 25px;
    }

    aside {
        float: left;
        width: calc(20% - 20px);
        min-height: 500px;
        border-radius: 21px;
        background: #252A2E;
        padding: 10px;
        margin-top: 10px;
    }
</style>