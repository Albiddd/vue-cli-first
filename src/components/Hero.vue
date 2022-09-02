
<template>
    <div class="hero">
        <h2>Jumbotron</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt sunt quidem nisi dicta, ad ipsum culpa, assumenda, similique repellendus necessitatibus eaque delectus. Suscipit, totam? Dignissimos consectetur laborum quos quidem commodi?</p>
    </div>
</template>

<script>
    export default {
      name: 'JumboTron'
    }
 </script>

<style scoped lang="scss">
    .hero{
        height: 400px;
        background-image: url(../assets/jumbotron.jpg);
      color: whitesmoke;
    }
    h2{
        padding: 2rem;
        font-size: 3rem;
    }
    p{
        margin: 0 auto;
        max-width: 500px;
    }
    </style>