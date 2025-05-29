# Snippets

<!-- I know it's not good practice, but this is my shortcut code to place a footer and back link -->

    <style>
      footer {
        max-width: 60ch;
        margin-inline: auto;
        padding-block-start: 0.5em;
        padding-inline: 0.5em;
        text-align: center;
        font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
          Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue",
          sans-serif;
      }

      footer a {
        color: #2b7fff;
      }

      footer a:hover {
        text-decoration: underline;
      }
    </style>
    <footer>
      <p>
        <a href="/"> &lt;&lt; Back </a>
      </p>
      <p>
        <small
          ><em
            >Davina's Jupyter Notebooks &copy; <a href="/">Davina Leong</a>,
            2025</em
          ></small
        >
      </p>
    </footer>
