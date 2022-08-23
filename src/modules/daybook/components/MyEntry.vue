<template>
  <div class="entry-container mb3 pointer p-2" @click="$router.push({name: 'entry', params: {id: 10}})">
    <!--Titulo-->
    <div class="entry-title d-flex">
        <span class="text-success fs-5 fw-bold">22</span>
        <span class="mx-1 fs-5">Agosto</span>
        <span class="mx-2 fw-light">2022, lunes</span>
    </div>

    <div class="entry-description">
        Consectetur ipsum ex nulla quis. Amet veniam laboris minim voluptate tempor. Culpa pariatur laboris reprehenderit do aliqua esse quis anim dolor adipisicing Lorem mollit. Magna magna cillum exercitation exercitation magna fugiat consequat aliquip.
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .entry-container{
        border-bottom: 1px solid #2c3e50;
        transition: 0.2s all ease-in;
        &:hover{
            background-color: lighten($color: grey, $amount: 45);
        }

        .entry-description{
            font-size: 12px;
        }
    }
</style>