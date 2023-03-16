<template>
  <div class="single-movie container">
    
    <div class="movie-info">
      <div class="movie-img">
        <img src="../assets/imgs/about.jpg" alt="" />
        <Contact />
      </div>
      <div class="movie-content">
        <h1>About us</h1>
        <p class="movie-fact tagline">
          Our company is a leading provider of video games, movies, and game subscriptions. We pride ourselves on delivering high-quality entertainment to our customers and constantly expanding our offerings to provide the latest and greatest in gaming and film.
<br>
  <br>Our video game selection includes a wide range of titles from all genres, including popular franchises like Call of Duty, Assassin's Creed, and Mario. We offer games for all major gaming consoles, as well as PC, so no matter what platform our customers prefer, they can find something they love.
  <br>
  <br>In addition to individual game purchases, we also offer game subscriptions that give our customers access to a library of games for a monthly fee. This provides a great value for gamers who want to try out a variety of titles without committing to buying each one individually.
  <br>
  <br>Our movie selection is equally diverse, featuring both new releases and classic films. We offer both physical copies of movies as well as digital downloads, so customers can choose how they want to watch their favorite films.
  <br>
  <br>For customers who are looking for a little bit of everything, we also offer bundled packages that include games and movies together, as well as subscriptions that provide access to both gaming and movie libraries.
  <br>
  <br>At our company, we are dedicated to providing the best customer service possible. Our knowledgeable staff is always available to answer questions and help customers find exactly what they're looking for. We also offer a hassle-free return policy, so customers can shop with confidence knowing that they can return any item that doesn't meet their expectations.
  <br>
  <br>In summary, our company is a one-stop shop for all things gaming and entertainment. From video games to movies and subscriptions, we have something for everyone. With our dedication to quality and customer service, we strive to provide the best possible experience for our customers.
        </p>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'about',
  
}
</script>

<style lang="scss">
.single-movie {
  color: #fff;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 32px 16px;

  .button {
    align-self: flex-start;
    margin-bottom: 32px;
  }

  .movie-info {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 32px;
    color: #fff;
    margin-top:100px;

    @media (min-width: 800px) {
      flex-direction: row;
      align-items: flex-start;
    }

    .movie-img {
      img {
        max-width: 500px;
        width: 50%;
        border-radius: 1%;


        @media (min-width: 800px) {
          max-width: 700px;
          width: initial;
        }
      }
    }

    .movie-content {
      h1 {
        font-size: 56px;
        font-weight: 400;
      }

      .movie-fact {
        margin-top: 12px;
        font-size: 20px;
        line-height: 1.5;

        span {
          font-weight: 600;
          text-decoration: underline;
        }
      }

      .tagline {
       

        span {
          font-style: normal;
        }
      }
    }
  }
}
</style>
