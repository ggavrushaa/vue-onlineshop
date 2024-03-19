<script setup>
    import Card from './Card.vue';

    const onClickAdd = () => {
        alert('Add!')
    }

    const onClickFavorite = () => {
        alert('Favorite!')
    }
</script>

<template>
    <div class="grid grid-cols-4 gap-5">
              <Card 
                title="Man`s sneakers Nike Blazer Mid Suede" 
                imageUrl="/sneakers/sneakers-1.jpg" 
                :price="1200" 
                :isAdded="false"
                :isFavorite="false"
                :onClickAdd="onClickAdd"
                :onClickFavorite="onClickFavorite"
              />
    </div>
</template>