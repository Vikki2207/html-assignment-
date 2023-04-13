# html-assignment-
<!DOCTYPE html>
<html>
  <head>
    <title>Fixed Header and Footer, Centered Content Layout</title>
    <style>
      /* Set body to fill the viewport and remove default margin */
      body {
        margin: 0;
        height: 100vh;
        display: flex;
        flex-direction: column;
      }

      /* Header styles */
      header {
        background-color: #333;
        color: #fff;
        height: 50px;
        position: fixed;
        top: 0;
        left: 0;
        right: 0;
      }

      /* Content styles */
      main {
        flex-grow: 1;
        display: flex;
        align-items: center;
        justify-content: center;
      }

      /* Footer styles */
      footer {
        background-color: #333;
        color: #fff;
        height: 50px;
        position: fixed;
        bottom: 0;
        left: 0;
        right: 0;
      }
    </style>
  </head>
  <body>
    <header>
      <h1>Header Content Here</h1>
    </header>
    <main>
      <h2>Centered Content Here</h2>
    </main>
    <footer>
      <p>Footer Content Here</p>
    </footer>
  </body>
</html>
