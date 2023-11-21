<template>
    <!-- NAVBAR -->
    <nav>
        <ul>
            <li><a href="#home">HOME</a></li>
            <li><a href="#page1">PAGE1</a></li>
            <li><a href="#page2">PAGE2</a></li>
            <li><a href="#blog">BLOG</a></li>
            <li><a href="#contact">CONTACT</a></li>
        </ul>
    </nav>
    <!-- Clear:Both - stop floating elements from overflowing into other elements -->
    <div style="clear: both;"></div>
</template>

<style scoped>
    nav {
        background: #252A2E;
        height: 65px;
        border-radius: 21px;
        margin-top: 5px;
    }
    nav ul {
        margin-left: 15px;
    }
    nav ul li {
        float: left;
        list-style: none;
        margin: 10px;
        line-height: 40px;
    }

    nav ul li a {
        color: #1cb698;
        text-decoration: none;
        transition: 1.0s;
    }

    nav ul li a:hover {
        text-decoration: 1px solid #1cb698;
        transition: 1s;
        color: #fff;
    }
</style>