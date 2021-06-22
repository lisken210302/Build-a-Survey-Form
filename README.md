# Build-a-Survey-Form
Build a Survey Form for Portpolio

<html lang="eng">
  <head>
    <style>
      body {
        font-family: arial;
        padding-left: 25%;
        padding-left: 20%;
      }
      label {
        font-size: 14px;
        display: block;
        padding-bottom: 12px
      }
      input, textarea, select {
        display: block;
        width: 100%;
        padding-bottom: 20px;
      }
     form {
        background-color: #CC1220;
        padding: 40px 40px 40px 40px;
      }
      #button-area {
        float: left;
        width: 50%;
        height: 50%;
      }
      
      input [tyoe=checkbox]:not(old) + label,
      input [tyoe=radio]:not(old) + label {
        display: inline-block;
        margin-left: -10px;
        padding-left: 10px;
      }
    </style>
  
  </head>
  
  <body>
    <h1 id="title">Tell Me about Fashion</h1>
    <p id="description">
      This is a survey where you can tell us about the the update fashion
    </p>
    <form id="survey-form">
      <label id="name-label">Name:</label>
      <input type="text" name="name" id="name" required placeholder="First Name"></input><br>
      <label id="email-label">Email:</label>
      <input type="email" name="email" id="email" required placeholder="Prime Name"></input><br>
      <label id="number-label">Number:</label>
      <input type="number" name="number" id="number" required placeholder="$"></input><br>

      <label id="fashion-type-label">Fashion Type:</label>
      <select id="dropdown" name="fashions" id="fashions">
        <option value="vintage">Vintage</option>
        <option value="trendy">Trendy</option>
        <option value="artsy">Artsy</option>
        <option value="bohemian">Bohemian</option>
        <option value="other">Other</option>
      </select>

      <br>
      <div id="button-area">
      <label id="gender-label">Gender:</label>
        <input type="radio" class="radio-inline" name="gender" value="male"> Male<br>
        <input type="radio" class="radio-inline" name="gender" value="female"> Female<br>
        <input type="radio" class="radio-inline" name="gender" value="other"> Other<br>
      </div>

      <br>
      <div id="button-area">
      <label id="fashion-Accessories-label">Fashion Accessories:</label>
        <input type="checkbox" id="fashion1" name="fashion1" value="Casual">
        <label for="fashion1"> I have a Watch</label><br>
        <input type="checkbox" id="fashion2" name="vehicle2" value="Sporty">
        <label for="fashion2"> I have a Bracelet</label><br>
        <input type="checkbox" id="fashion3" name="vehicle3" value="Gownball">
        <label for="fashion3"> I have a Ring</label><br>
       </div>
      
<br>
      <textarea placeholder="Additional Comment"></textarea><br>
      <input type="submit" id=submit>
     </form>
     <Script type="text/javascript" src="
    </body>
   </html>
