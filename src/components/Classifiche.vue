<script>
    export default {
    name: "Classifiche",
    }
</script>

<template>
    <div class="container">
        <div class="col-sx flex clmn jc-cen-ai-cen w40">
            <table class="table">
  <thead>
    <tr>
      <th scope="col">TEAM</th>
      <th scope="col">W</th>
      <th scope="col">D</th>
      <th scope="col">L</th>
      <th scope="col">PTS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>1 <img src="\assets\league-club-1.png" alt=""> <p>Istanbul Sports</p></td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>        
        </div>
        <div class="col-dx w40">

        </div>
    </div>
</template>

<style lang="scss">
@use '../Styles/general.scss'
</style>

<style lang="scss" scoped>
@use '../Styles/parziali/_variabili.scss' as *;
.container{
    background: $whitetheme;
}
.col-sx{
    border: 2px solid black;
}
</style>
