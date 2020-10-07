<style>
  a:link {
    color: white;
  }
  a:hover {
    color: tomato;
  }
  a:active {
    color: tomato;
  }
  a {
    text-decoration: none;
    color: white;
  }
  section {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 80px;
    height: calc(100% - 120px);
  }
  h1 {
    font-size: 52px;
    line-height: 1.2;
    font-weight: 600;
    margin: 0px;
    margin-bottom: 28px;
  }
  p {
    font-size: 18px;
    line-height: 1.5;
    margin: 0px;
  }

  @media only screen and (max-width: 425px) {
    h1 {
      font-size: 32px;
      line-height: 1.2;
      font-weight: 600;
      margin: 0px;
      margin-bottom: 12px;
    }
    p {
      font-size: 14px;
      line-height: 1.5;
      margin: 0px;
    }

    section {
      margin-top: 80px;
      padding: 24px;
      height: auto;
    }
    .navbar {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
      width: calc(100% - 24px);
      padding: 12px;
      background-color: rgb(46, 46, 46);
      position: fixed ; 
      top: 0;
      z-index: 10000;
    }
    .navbar > a {
      text-align: center;
      color: white;
    }
  }
</style>



<section>
  <div>
    <h1>Hello, I’m Tushar Debnath</h1>
    <p class="paragraph">
      A Product designer & Design technologist living in New Delhi. Currently I
      am building consumer products and internal design tools at Zomato.
    </p>
  </div>
</section>
<div class="navbar">
    <a href="#projects">Projects</a>
    <a href="#articles">Writing</a>
    <a href="#plugin">Plugins</a>
  </div>
