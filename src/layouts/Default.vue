<template>
  <main class="layout" role="main">
    <slot />
    <div class="footer">
      <p>
        <a class="link" href="//twitter.com/Js_frontendguy">Twitter</a>
      </p>
    </div>
  </main>
</template>

<style>
body {
  font-family: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.5;
  border: 15px solid #8e40b2;
  min-height: 100vh;
}

.layout {
  max-width: 760px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}

.footer {
  padding-top: calc(30em / 4);
  text-align: center;
  font-size: 1em;
}

.link {
  border: 2px dashed #8e40b2;
  padding: 7px;
  color: #333;
  text-decoration: none;
}
</style>
