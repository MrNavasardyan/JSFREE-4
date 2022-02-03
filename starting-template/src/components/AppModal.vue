<template>
    <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="exampleModalLabel">{{character.name}}</h5>
                    <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                </div>
                <div class="modal-body">


                    <img :src="character.thumbnail" class="img-fluid rounded-start" :alt="character.name">
                    <div>
                        <h5>Описание:</h5>
                        <p>Укушенный радиоактивным пауком, старшеклассник Питер Паркер обрел скорость, силу и силу паука. Приняв имя Человек-паук, Питер надеялся начать карьеру, используя свои новые способности. Наученный тому, что с большой силой приходит
                            большая ответственность, Паук поклялся использовать свои силы, чтобы помогать людям.</p>
                        <h5>Комиксы:</h5>
                        <ul>
                            <li>Spider-Man: 101 Ways to End the Clone Saga (1997) #1</li>
                            <li>Spider-Man: 101 Ways to End the Clone Saga (1997) #1</li>
                            <li>Spider-Man: 101 Ways to End the Clone Saga (1997) #1</li>
                        </ul>
                    </div>
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Закрыть</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "AppModal",
        props:['character']
    }
</script>

<style scoped>

</style>
