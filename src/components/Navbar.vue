<template>
    <ul class="nav justify-content-center">
        <li class="nav-item">
            <a href="#" class="nav-link text">Home</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link text">Quiz</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link text">Index</a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link text">Info</a>
        </li>
    </ul>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>
#navboy-container {
    background-color: #FFE8D6 !important;
}
.nav-link {
    color: #6B705C;
    font-size: 18px;
}
a:hover {
    color:#A5A58D !important;
}
a:visited {
    color: #6B705C;
}
</style>