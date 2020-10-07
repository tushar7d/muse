<style>
  ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    border: 0;
    margin-top: 24px;
  }
  li {
    padding-bottom: 12px;
    font-size: 18px;
    font-weight: 600;
  }
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
  .quick_link_container {
    display: flex;

    align-items: center;
  }
  .image_placeholder {
    width: 60px;
    height: 60px;
    border-radius: 160px;
    background-color: white;
  }
  .link {
    margin-left: 12px;
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
    .quick_link_container {
      display: none;
    }
    section {
    margin-top: 120px;
      padding: 24px;
      height: auto;
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
    <div>
      <ul>
        <li><a href="#projects">Selected projects</a></li>
        <li><a href="#articles">Selected projects</a></li>
        <li><a href="#plugin">Selected projects</a></li>
      </ul>
    </div>
  </div>

  <div class="quick_link_container">
    <div class="image_placeholder" />
    <div class="link">LinkedIn</div>
    <div class="link">Figma</div>
    <div class="link">Dribbble</div>
    <div class="link">Github</div>
  </div>
</section>
