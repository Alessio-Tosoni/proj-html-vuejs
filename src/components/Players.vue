<script>
import PlayerCard from './PlayerCard.vue'
export default {
    name: "Players",
    components: {
        PlayerCard,
    },
    data() {
        return {
            players: [
                {
                    pic: ".\assets\player1.jpg",
                    Number: "07",
                    Name: "Adam Brown",
                    Position: "Forwarder",
                },
                {
                    pic: "\assets\player2.jpg",
                    Number: "09",
                    Name: "Michael Kayn",
                    Position: "Forwarder",
                },
                {

                    pic: "\assets\player3.jpg",
                    Number: "11",
                    Name: "Michael Lee",
                    Position: "Forwarder",
                },
                {

                    pic: "\assets\player4.jpg",
                    Number: "15",
                    Name: "Ethan Smith",
                    Position: "Midfielder",
                }]
            }        
    },

        
    


}
   

</script>

<template>
    <div class="container flex jc-sa ai-cen">
        <PlayerCard v-for="player in players" :players="player" />

    </div>
</template>

<style lang="scss">
@use '../Styles/general.scss'
</style>

<style  scoped>
.container{
    background-image: url('/assets/player.jpg');
    min-height: 600px;
    background: cover;
    background-size: cover;
    background-repeat: no-repeat;
}
</style>