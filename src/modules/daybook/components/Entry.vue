<template>
    <div class="entry-container mb-3 pointer p-2">
        <!-- TItulo -->

        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5">Julio</span>
            <span class="mx-2 fw-light">2022, Domingo</span>
        </div>

        <div class="entry-description">
            Non labore occaecat laboris incididunt esse esse minim aute ea aliquip irure anim. Cillum nostrud mollit reprehenderit excepteur sunt anim irure sunt sunt incididunt officia esse voluptate non. Aliquip Lorem ad adipisicing ea magna in nulla non anim. Cillum deserunt ipsum fugiat aute enim do esse cupidatat aute commodo velit exercitation. Pariatur id proident consequat excepteur dolor qui aliquip in dolore minim reprehenderit Lorem ipsum sunt.
        </div>

    </div>
</template>

<style lang="scss" scoped>
    .entry-container{
        border-bottom: 1px solid #2c3e50;
        transition: all 0.2s ease-in;

        &:hover{
            background-color: lighten($color: grey, $amount: 45);
        }

        .entry-description{
            font-size: 15px;
        }
    }
</style>