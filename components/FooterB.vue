<template>
    <!-- Footer -->
      <section id="footer">
        <div class="inner">
          <h2 class="major">Get in touch</h2>
          <p style="padding: 2% 1%;">
            Get in touch if you want some art work done or a model designed for
            game or 3d printing.
          </p>
          <form method="post" action="mailto:eamongreen59@gmail.com">
            <div class="fields">
              <div class="field">
                <label for="name">Name</label>
                <input id="name" type="text" name="name"  />
              </div>
              <div class="field">
                <label for="email">Email</label>
                <input id="email" type="email" name="email"  />
              </div>
              <div class="field">
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="4"></textarea>
              </div>
            </div>
            <ul class="actions">
              <li><input type="submit" value="Send Message" /></li>
            </ul>
          </form>
          <ul class="contact">
            <li class="icon solid fa-envelope">
              <a href="mailto:eamongreen59@gmail.com">eamongreen59@gmail.com</a>
            </li>
            <li class="icon brands fa-discord">
              <a href="https://discordapp.com/users/AdequateLumps🍑#7244/"
                >AdequateLumps🍑#7244</a
              >
            </li>
            <li class="icon brands fa-reddit">
              <a href="https://www.reddit.com/u/blazingbuns943"
                >u/blazzingbuns943</a
              >
            </li>
            <li class="icon brands fa-instagram">
              <a href="https://www.instagram.com/eamongreen943"
                >instagram.com/eamongreen943</a
              >
            </li>
            <li class="icon brands fa-github" style="color: #4c5c96">
              <a href="https://github.com/dualio26">dualio26</a>
            </li>
          </ul>
          <h2 class="major" style="margin-top: 1%"></h2>
          <div class="bottomNav">
            <p style="opacity: 0.2">Plz be nice </p>
            <NuxtLink to="/"><i class="icon solid fa-home icon-left" style="opacity:1;"/></NuxtLink>
          </div>
        </div>
      </section>
</template>