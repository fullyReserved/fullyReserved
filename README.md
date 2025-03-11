## Hi there fellow programmers 👋

programming languages i use daily: C++, C#, nodejs, (html)
programming languages i know: C++, C#, nodejs, VisualBasic, Typescript, Postscript

<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>[ NF ]</title>
  <link href="/assets?file=index.css" rel="stylesheet" type="text/css" />
  <link rel="stylesheet" href="assets/?file=retro.css">
  <link rel="icon" href="assets/?file=icon.png" type="image/png">

  <style>
    body {
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      height: 100vh;
      overflow: hidden; 
    }

    .header-container {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-top: 20px;
      width: 100%;
      position: relative;
    }

    .button-container {
        display: flex;
        justify-content: center;
        margin-top: 10px;
        position: relative; 
        z-index: 10; 
    }

    .button-container button {
        margin: 0 10px;
        pointer-events: auto; 
        cursor: pointer;
    }


    .title {
      text-align: center;
      font-size: 2rem; 
      color: #fff; 
    }

    .container {
      display: flex;
      justify-content: center;
      align-items: center; 
      width: 100%;
    }

    .content {
      display: block;
      width: 1000px;
      height: 562px;
      position: relative;
    }

    .container-full {
      position: relative;
      width: 100%;
      height: 100%;
    }

    .title {
        text-align: center;
        font-size: 1rem; 
        color: #fff; 
        font-family: 'Pixelmania', sans-serif; 
    }



  </style>
</head>

<body>
  <div class="header-container">
    <div class="title"><h1>N<span id="colored-F" style="color: #fd0d5d;">F</span></h1></div>
    <div class="button-container">
      <button id="C2EButton1" class="btn btn-primary" type="button"
        style="background: rgb(38,0,11);border-radius: 0;border: 6px double var(--bs-primary);border-right-style: solid; border-left-style: solid;text-shadow: 0px 0px 8px var(--bs-primary);color: var(--bs-primary);font-size: 14px;font-family: Pixelmania;">FORUMS</button>
      <button id="C2EButton2" class="btn btn-primary" type="button"
        style="background: rgb(38,0,11);border-radius: 0;border: 6px double var(--bs-primary);border-right-style: solid; border-left-style: solid;text-shadow: 0px 0px 8px var(--bs-primary);color: var(--bs-primary);font-size: 14px;font-family: Pixelmania;">AVATAR</button>
      <button id="C2EButton3" class="btn btn-primary" type="button"
        style="background: rgb(38,0,11);border-radius: 0;border: 6px double var(--bs-primary);border-right-style: solid; border-left-style: solid;text-shadow: 0px 0px 8px var(--bs-primary);color: var(--bs-primary);font-size: 14px;font-family: Pixelmania;">STORE</button>
    </div>
</div>


  <div class="container">
    <div class="content">
      <div class="container-full">
        <div class="animated hue"></div>
        <img class="backgroundImage" src="/assets?file=room.jpg">
        <div class="container">
          <div class="cube">
            <div class="face top"></div>
            <div class="face bottom"></div>
            <div class="face left text"></div>
            <div class="face right text"></div>
            <div class="face front"></div>
            <div class="face back text"></div>
          </div>
        </div>
        <div class="container-reflect">
          <div class="cube">
            <div class="face top"></div>
            <div class="face bottom"></div>
            <div class="face left text"></div>
            <div class="face right text"></div>
            <div class="face front"></div>
            <div class="face back text"></div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <script src="/assets?file=index.js"></script>
</body>
</html>
