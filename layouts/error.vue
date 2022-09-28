<template>
    <div>
        <slot name="header" />
        <div class="frown">
            <img src="https://media.istockphoto.com/photos/baby-crying-picture-id151557041?k=20&m=151557041&s=612x612&w=0&h=t1-IuC9uSWqY7V5-yngf-Vj8VluYugg5ls7vGkPOxUo="
                alt=":(">
        </div>
        <slot name="redirectEl" />
    </div>
</template>

<style scoped>
.frown img {
    width: 30rem;
}
</style>