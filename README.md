# SheCodes-Projects

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Museum 🎨</title>
    <style>
      body {
        text-align: center;
        transition: all 150ms ease-in-out;
        font-family: Georgia, 'Times New Roman', Times, serif;
        margin: 10px;
        background: white 
      }
      h2 {
        font-weight: 200;
        font-style: italic;
      }
      p {
       font-size: larger;
      }
      a {
        margin: 0 auto;
        display: block;
      }
      a:hover {
        color: red;
      }
      img {
        margin: 0 auto;
        display: block;
        width: 90%;
      }
     button {
        display: block;
        margin: 20px auto;
        border: 1px solid ;
        background: #65451F;
        color: #EAC696;
        font-size: 16px;
        line-height: 22px;
        padding: 16px 24px;
        border-radius: 30px;
        box-shadow: rgba(37, 39, 89, 0.5) 0px 8px 8px 0;
        cursor: pointer;
      }

      button:hover {
        background: black;
        color: white;
        border: 1px solid #EAC696;
      }
      .art {
        background-image: linear-gradient(to top, #FFE3CA 0%, #E2BFB3 100%);
        border-radius: 20px;
        width: 40%;
        margin: 25px auto;
        padding: 25px;
        box-shadow: rgba(201, 194, 164, 0.5) 0px 10px 10px 0px; 
      }
    </style>
  </head>
  <body>
    <div class="art">
    <h1>MUSEUM 🖼️</h1>
    <h2>
      "A visit to a museum is a search for beauty, truth, and meaning in our
      lives. Go to museums as often as you can.” – Maira Kalman
    </h2>
    <p>
      Art is everywhere and museums bring a one of a kind experience, curated in
      a way that takes you on a certain journey (obviously the experience is
      different for each person). <br />
      South Africa currently has 51 museums with my favourite being the
      Apartheid museum. 
      <hr>
      <img
        src="https://www.apartheidmuseum.org/uploads/_imager/uploads/files/10295/apartheidmuseum35-5_cf6e8a615b8ba10f48641f1fa46732ab_cf6e8a615b8ba10f48641f1fa46732ab.webp"
        alt="Apartheid museum"
      />
      <hr>
      <span>
        The <strong>Apartheid Museum</strong> located in <em>Johannesburg, South Africa</em> opened in 2001 and is acknowledged as the pre-eminent museum in the world dealing with 20th century South Africa, at the heart of which is the apartheid story. The Apartheid
      Museum, the first of its kind, illustrates the rise and fall of apartheid.
      An architectural consortium, comprising several leading architectural
      firms, conceptualised the design of the building on a seven-hectare stand.
      The museum is a superb example of design, space and landscape offering the
      international community a unique South African experience. The exhibits
      have been assembled and organised by a multi-disciplinary team of
      curators, film-makers, historians and designers. They include provocative
      film footage, photographs, text panels and artefacts illustrating the
      events and human stories that are part of the horrific period in our
      history, known as apartheid.<br />
      <a href="https://www.apartheidmuseum.org/about-the-museum" target="_blank">
        Learn more about the Apartheid Museum</a>
      </span>
      
  
    </p>
    <button> Book museum visit</button>
  </div>

  <script>
    function museumVisit() {
      let name = prompt("What is your name");
      let province = prompt("Which province are you in?");
      let email = prompt("What is your email address?");
      province = province.toLowerCase().trim();


      if (province.length) {
       alert('Thanks, ' + name + ' an email will be sent for museums in ' + province);
      }
      else {
        alert("Please provide the province");
    }
  }

    let clickButton = document.querySelector("button");

    clickButton.addEventListener("click", museumVisit);

  </script>
</body>
</html>
