<template>
    <div>
        <!-- Banner -->
      <section id="banner">
        <div class="inner">
          <div class="logo">
            <img src="images/Q.svg" alt="Q" style="width: 3%; fill: white" />
          </div>
          <h1>Welcome to AdquateZone</h2>
          <p>
            and yes I do know that it is spelt wrong
          </p>
        </div>
      </section>

      <!-- Wrapper -->
      <section id="wrapper">
        <!-- One -->
        <section id="one" class="wrapper spotlight style0">
          <div class="inner">
            <a href="#" class="image"><img src="images/pic01.jpg" alt="" /></a>
            <div class="content">
              <h1 class="major">3D Printing</h2>
              <p style="padding: 1% 1%;">
                Here you will find all my 2D printing escapades through using a
                2D printer:<br />
                I have a Creality resin LCD printer I aquiered off
                <a href="https://kiwi2d.co.nz">Kiwi3D</a>.<br />More information
                can be found in the <a href="sSheet.html">Equipment</a> spec
                sheet on this website.
              </p>
              <a href="#" class="special">See more</a>
            </div>
          </div>
        </section>

        <!-- Two -->
        <section id="two" class="wrapper alt spotlight style1">
          <div class="inner">
            <a href="#" class="image"><img src="images/pic02.jpg" alt="" /></a>
            <div class="content">
              <h1 class="major">Design Work</h2>
              <p style="padding: 1% 1%;">
                This is where I will have all my: 
				<ul>
					<li>2D modeling and deisgns from <a href="www.blender.org">Blender</a></li>
					<li>Art work from 2 years of design in highschool on Photoshop and Illustrator. <i style="opacity: 0.2;">{Torture}</i></li>
				</ul>
              </p>
              <NuxtLink to="/dWork" class="special">See more</NuxtLink>
            </div>
          </div>
        </section>

        <!-- Three -->
        <section id="three" class="wrapper spotlight style2">
          <div class="inner">
            <a href="#" class="image"><img src="images/pic03.jpg" alt="" /></a>
            <div class="content">
              <h1 class="major">Electrician Log</h2>
              <p style="padding: 1% 1%;">
                See if this works out but wanna be an electrician,<br> if that doesnt pan out it will be filled with practical electronics and circuit projects.
              </p>
              <a href="#" class="special">See more</a>
            </div>
          </div>
        </section>
      </section>
      <FooterB/>
    </div>
</template>