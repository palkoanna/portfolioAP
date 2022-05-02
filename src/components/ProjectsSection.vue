<template>
    <div class="projectsection">
        <h2 class="projecttitle">Projects</h2>
        <div class="projectimg">
            <img src = "@/assets/img/projects1.png" alt="">
        </div>
        <div class="projectimg">
            <img src = "@/assets/img/trifolder1.png" alt="">
        </div>
        <div class="projectimg">
            <img src = "@/assets/img/trifolder2.png" alt="">
        </div>
    </div>
</template>

<script>

</script>


<style lang="css">
.projectsection {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 100%;
}

.projectimg {
    margin-bottom: 30px;
    height: 300px;
    width: auto;
}

img {
    height: 100%;
    width: 100%;
}
</style>