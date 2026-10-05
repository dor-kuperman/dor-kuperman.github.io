<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Quote of the Day</title>
    <style>
      :root {
        --bg: #faf8f3;
        --card: #ffffff;
        --text: #23201a;
        --muted: #8a8577;
        --line: #ece7db;
        --accent: #9a7b4f;
        /* The tell. Default = extension NOT detected. */
        --dot: #d9d4c7;
      }
      @media (prefers-color-scheme: dark) {
        :root {
          --bg: #17160f;
          --card: #201e16;
          --text: #ece7d8;
          --muted: #9a9484;
          --line: #332f22;
          --accent: #cda86a;
          --dot: #3a362a;
        }
      }
      * {
        box-sizing: border-box;
      }
      body {
        margin: 0;
        min-height: 100vh;
        display: grid;
        place-items: center;
        padding: 24px;
        background: var(--bg);
        color: var(--text);
        font:
          17px/1.6 Georgia,
          "Times New Roman",
          serif;
      }
      .card {
        max-width: 560px;
        width: 100%;
        background: var(--card);
        border: 1px solid var(--line);
        border-radius: 16px;
        padding: 40px 36px;
        box-shadow: 0 10px 40px rgba(0, 0, 0, 0.06);
      }
      .eyebrow {
        font:
          600 12px/1 system-ui,
          sans-serif;
        letter-spacing: 0.14em;
        text-transform: uppercase;
        color: var(--accent);
        margin: 0 0 20px;
        display: flex;
        align-items: center;
        gap: 9px;
      }
      /* This dot is the indicator. Dull by default; turns green when the extension is live. */
      .eyebrow::before {
        content: "";
        width: 8px;
        height: 8px;
        border-radius: 50%;
        background: var(--dot);
        transition: background 0.4s;
      }
      blockquote {
        margin: 0;
        font-size: 25px;
        line-height: 1.45;
      }
      blockquote::before {
        content: "\201C";
        color: var(--accent);
        margin-right: 2px;
      }
      blockquote::after {
        content: "\201D";
        color: var(--accent);
        margin-left: 2px;
      }
      .author {
        margin-top: 18px;
        color: var(--muted);
        font-style: italic;
      }
      .foot {
        margin-top: 28px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        font:
          13px/1 system-ui,
          sans-serif;
        color: var(--muted);
      }
      button {
        font: inherit;
        padding: 8px 14px;
        border-radius: 8px;
        cursor: pointer;
        border: 1px solid var(--line);
        background: var(--bg);
        color: var(--text);
      }
      button:hover {
        border-color: var(--accent);
      }
      /* Off-screen probe: only moves if the extension injected its ncRotate animation. */
      #probe {
        position: absolute;
        left: -9999px;
        top: -9999px;
        width: 1px;
        height: 1px;
        animation: ncRotate 1s linear infinite;
      }
    </style>
  </head>
  <body>
    <div class="card">
      <p class="eyebrow">Quote of the Day</p>
      <blockquote id="quote">Loading…</blockquote>
      <div class="author" id="author"></div>
      <div class="foot">
        <span id="date"></span>
        <button id="next">Another one</button>
      </div>
    </div>
    <div id="probe"></div>

    <script>
      const QUOTES = [
        ["The best way to predict the future is to invent it.", "Alan Kay"],
        ["Simplicity is the soul of efficiency.", "Austin Freeman"],
        ["Make it work, make it right, make it fast.", "Kent Beck"],
        [
          "A problem well stated is a problem half solved.",
          "Charles Kettering"
        ],
        [
          "The computer was born to solve problems that did not exist before.",
          "Bill Gates"
        ],
        ["First, solve the problem. Then, write the code.", "John Johnson"],
        [
          "Any sufficiently advanced technology is indistinguishable from magic.",
          "Arthur C. Clarke"
        ],
        [
          "Perfection is achieved when there is nothing left to take away.",
          "Antoine de Saint-Exupery"
        ]
      ];

      const q = document.getElementById("quote");
      const a = document.getElementById("author");
      function show(i) {
        const [text, who] = QUOTES[i % QUOTES.length];
        q.textContent = text;
        a.textContent = "— " + who;
      }
      let idx = Math.floor(Math.random() * QUOTES.length);
      show(idx);
      document.getElementById("next").onclick = () => show(++idx);
      document.getElementById("date").textContent =
        new Date().toLocaleDateString(undefined, {
          weekday: "long",
          month: "long",
          day: "numeric"
        });

      document
        .getElementById("probe")
        .addEventListener("animationstart", () => {
          document.documentElement.style.setProperty("--dot", "#2e9e5b"); // green = extension is live
        });
    </script>
  </body>
</html>
