<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Project</title>
    <style>
      h1 {
        text-align: center;
        color: #8c5ba3;
      }

      h2 {
        text-align: center;
        font-size: 19px;
        border: 2px solid #8c5ba3;
        border-radius: 30px;
        padding: 15px;
      }

      button {
        font-size: 18px;
        border-radius: 30px;
        padding: 16px 21px;
        border: 1px solid #8c5ba3;
        box-shadow: rgba(37, 39, 89, 0.08) 0px 8px 8px 0;
        transition: all 200ms ease-in-out;
        display: block;
        margin: 20px auto;
        background: #8c5ba3;
        color: #fff;
      }

      button:hover {
        background: white;
        color: #8c5ba3;
        cursor: pointer;
        border: 1px solid #8c5ba3;
      }

      .link {
        font-size: 18px;
        text-decoration: none;
        color: #8c5ba3;
      }

      .link:hover {
        text-decoration: underline;
        cursor: pointer;
      }

      .me {
        text-align: center;
        text-decoration: none;
        color: #8c5ba3;
      }

      img {
        margin: 0 auto;
        display: block;
        max-width: 80%;
        border-radius: 12px;
      }

      .page {
        max-width: 600px;
        margin: 0 auto;
        padding: 60px;
      }

      .summary {
        font-family: Helvetica, Arial, san-serif;
        font-size: 14px;
        line-height: 1.6;
        color: #333;
      }

      .page {
        max-width: 500px;
        margin: 0 auto;
        padding: 55px;
        background-color: #fbd0f5;
        border-radius: 13px;
        box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 10px;
      }
    </style>
  </head>
  <body>
    <div class="page">
      <h1>
        <img
          class="gif"
          src="https://www.google.com/logos/fnbx/bts/kp_icon_dm.gif"
          alt="Heart"
        />
        <strong>BTS</strong>
      </h1>
      <h2>Boy Band</h2>
      <img
        src="https://cdn.i-scmp.com/sites/default/files/styles/768x768/public/d8/images/canvas/2021/07/08/62d30fc0-81a2-4093-b5aa-182a94855233_386389bf.jpg?itok=OKQim-8Z&v=1625719813"
        alt="bts"
      />
      <p class="summary">
        BTS, also known as <strong><em>Bangtan Boys</em></strong
        >, is a South Korean boy band formed by Big Hit Entertainment in 2013.
        The group consists of seven members: RM (leader, rapper), Jin
        (vocalist), Suga (rapper), J-Hope (rapper, dancer), Jimin (vocalist,
        dancer), V (vocalist), and Jungkook (vocalist, dancer). BTS debuted with
        the single album "2 Cool 4 Skool" and gained popularity for their
        energetic performances, meaningful lyrics, and active engagement with
        fans, known as <strong>ARMY.</strong> BTS's music spans various genres,
        including K-pop, hip-hop, R&B, and EDM. Their lyrics often touch on
        social issues, mental health, self-love, and the challenges of youth,
        resonating with a global audience. The group has released multiple
        successful albums, including "Wings" (2016), "Love Yourself" series
        (2017-2018), "Map of the Soul: Persona" (2019), "Map of the Soul: 7"
        (2020), and "BE" (2020).
      </p>
      <a
        class="link"
        href="https://ibighit.com/bts/eng/profile/"
        target="_blank"
      >
        Explore more on ibighit🧐
      </a>

      <button class="armyy">Become an ARMY💜</button>

      <p class="me">
        Coded by
        <a
          href="https://linkedin.com/in/nakedi-makgakga-33a64a273"
          target="_blank"
        >
          Nakedi Makgakga</a
        >
      </p>
    </div>
    <script>
      function purple() {
        let name = prompt("What is your name(이름이 뭐에요)?");
        let country = prompt("What is your home county(너의 고국은 어디야)?");
        let bias = prompt("Who is your bias(누가 너의 최애야)?");

        alert("Welcome to ARMY💜🎇 " + name + "! We purple you!😊");
      }

      let button = document.querySelector(".armyy");
      button.addEventListener("click", purple);
    </script>
  </body>
</html>

