<svelte:head>
	<link rel="stylesheet" href="/src/main.css" />
</svelte:head>

<!-- <div class="navbar-container sticky-top bg-primary-1">
  <div class="main-container navbar-container">
      <div data-collapse="medium" data-animation="default" data-duration="400" data-easing="ease"
          data-easing2="ease" role="banner" class="navbar w-nav">
          <div class="navbar-row"><a href=""
                  class="mobile-brand w-nav-brand"><img
                      src="./Optic - Webflow HTML Website Template_files/5f0e4596d2be691a8d68fc57_Optic-White.svg"
                      alt=""></a>
              <nav role="navigation" class="nav-menu-wide w-nav-menu"><a href=""
                      class="desktop-brand w-nav-brand"><img
                          src="./Optic - Webflow HTML Website Template_files/5f0e4596a483080f6f52f6aa_Optic.svg"
                          alt=""></a><a href="/"
                      class="nav-link text-white w-nav-link">TalentLoop</a>
                  <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                      <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-0"
                          aria-controls="w-dropdown-list-0" aria-haspopup="menu" aria-expanded="false"
                          role="button" tabindex="0">
                          <a href="./employers">
                          <div class="text-white">Hire Talent</div></a><img
                              src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                              alt="" class="dropdown-arrow">
                      </div>
                  </div>
                  <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                      <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-1"
                          aria-controls="w-dropdown-list-1" aria-haspopup="menu" aria-expanded="false"
                          role="button" tabindex="0">
                          <a href=""><div class="text-white">Find a job</div></a><img
                              src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                              alt="" class="dropdown-arrow">
                      </div>
                  </div>
                  <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                      <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-2"
                          aria-controls="w-dropdown-list-2" aria-haspopup="menu" aria-expanded="false"
                          role="button" tabindex="0">
                          <a href="./about"><div class="text-white">About us</div></a><img
                              src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                              alt="" class="dropdown-arrow">
                      </div>
                  </div>
                  <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                      <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-3"
                          aria-controls="w-dropdown-list-3" aria-haspopup="menu" aria-expanded="false"
                          role="button" tabindex="0">
                          <a href="./jobs"><div class="text-white">View jobs</div></a><img
                              src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                              alt="" class="dropdown-arrow">
                      </div>
                  </div>
              </nav>
          </div>
          <div class="w-nav-overlay" data-wf-ignore="" id="w-nav-overlay-0"></div>
      </div>
  </div>
</div> -->

<div class="navbar-container sticky-top bg-primary-1">
  <div class="main-container navbar-container">
      <div data-collapse="medium" data-animation="default" data-duration="400" data-easing="ease"
          data-easing2="ease" role="banner" class="navbar w-nav">
          <div class="navbar-row">   
              <a href="/"
                  class="mobile-brand w-nav-brand"><a href="/"
                  class="nav-link text-white w-nav-link">Talentloop</a></a>
              <nav role="navigation" class="nav-menu-wide w-nav-menu" style="transform: translateY(0px) translateX(0px);"><a href="/"
                      class="desktop-brand w-nav-brand"><a href="/"
                      class="nav-link text-white w-nav-link">Talentloop</a></a>
                  <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                      <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-0"
                          aria-controls="w-dropdown-list-0" aria-haspopup="menu" aria-expanded="false"
                          role="button" tabindex="0">
                          <a href="./employers">
                          <div class="text-white">Hire Talent</div></a><img
                              src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                              alt="" class="dropdown-arrow">
                      </div>
                  </div>
                  <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                      <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-1"
                          aria-controls="w-dropdown-list-1" aria-haspopup="menu" aria-expanded="false"
                          role="button" tabindex="0">
                          <a href="./talents"><div class="text-white">Find a job</div></a><img
                              src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                              alt="" class="dropdown-arrow">
                      </div>
                  </div>
                  <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                      <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-2"
                          aria-controls="w-dropdown-list-2" aria-haspopup="menu" aria-expanded="false"
                          role="button" tabindex="0">
                          <a href="./about"><div class="text-white">About us</div></a><img
                              src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                              alt="" class="dropdown-arrow">
                      </div>
                  </div>
                  <div data-hover="true" data-delay="300" class="nav-link text-white w-dropdown">
                      <div class="dropdown-toggle w-dropdown-toggle" id="w-dropdown-toggle-3"
                          aria-controls="w-dropdown-list-3" aria-haspopup="menu" aria-expanded="false"
                          role="button" tabindex="0">
                          <a href="./jobs"><div class="text-white">View jobs</div></a><img
                              src="./Optic - Webflow HTML Website Template_files/5f0e4ae264b9d44893514e33_icon-dropdown-arrow.svg"
                              alt="" class="dropdown-arrow">
                      </div>
                  </div>
              </nav>
              <!-- <div class="menu-button w-nav-button w--open" style="-webkit-user-select: text;" aria-label="menu" role="button"
                  tabindex="0" aria-controls="w-nav-overlay-0" aria-haspopup="menu" aria-expanded="false">
                  <img 
                  src="http://127.0.0.1:5500/web3x/page3/Optic%20-%20Webflow%20HTML%20Website%20Template_files/5f0e4e7cd7cb084980b643c7_icon-menu-white.svg" alt=""
                  class="menu-button-image"> 
                  
                <ul>
                    <li class="dropdown menu-button w-nav-button w--open" style="-webkit-user-select: text;" aria-label="menu" role="button"
                    tabindex="0" aria-controls="w-nav-overlay-0" aria-haspopup="menu" aria-expanded="false">
                      <a href="javascript:void(0)" class="dropbtn">Dropdown</a>
                      <div class="dropdown-content">
                        <a href="./employers">Hire Talent</a>
                        <a href="./talents">Find a job</a>
                        <a href="./about">About us</a>
                        <a href="./jobs">View jobs</a>
                      </div>
                    </li>
                </ul>
              </div> -->
               

                <ul>
                  <li class="dropdown">
                    <a href="javascript:void(0)" class="dropbtn">
                      <img
                      src="https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0e4e7cd7cb084980b643c7_icon-menu-white.svg"
                      alt=""
                      class="menu-button-image"
                      />
                    </a>
                    <div class="dropdown-content">
                      <a href="./employers">Hire Talent</a>
                      <a href="./talents">Find a job</a>
                      <a href="./about">About us</a>
                      <a href="./jobs">View jobs</a>
                    </div>
                  </li>
                </ul>
          </div>
          <div class="w-nav-overlay" data-wf-ignore="" id="w-nav-overlay-0" style="display: none;"></div>
      </div>
  </div>
</div>

<div class="section bg-primary-1">
    <div class="main-container top-layer">
      <div class="w-layout-grid grid-halves">
        <div class="grid-text-content">
          <div class="container align-center">
            <h1 class="display-heading-1 text-white">Matching you to your fullest potential. 100% free.</h1>
            <p class="text-large">You’re more than your resume. Create a free profile and let companies apply to interview you (with salary details upfront).</p>
          </div>
        </div>
        <div class="container align-center">
          <div class="hero-form-container shadow">
            <div class="form-block w-form">
              <form id="wf-form-Sign-Up-Form" name="wf-form-Sign-Up-Form" data-name="Sign Up Form"
                class="form-grid-vertical">
                <!-- <div class="label-form"><label for="name">First Name</label> <label for="name">Last Name</label></div> -->
                <div class="name-form" ><label style="width:246px" for="firstname">First Name</label>  
                    <input type="text" class="form-input w-input" maxlength="256"
                    name="firstname" data-name="FirstName" placeholder="" id="firstname">
                </div><div><label style="left: 0;" for="lastname">Last Name</label>
                    <input type="text" class="form-input w-input" maxlength="256"
                    name="lastname" data-name="LastName" placeholder="" id="lastname"></div>
                <div><label for="phone">Phone Number</label><input type="tel" class="form-input w-input"
                    maxlength="256" name="phone" data-name="Phone" placeholder="" id="email" required=""></div>
                <div><label for="email">Email Address</label><input type="email" class="form-input w-input"
                    maxlength="256" name="email" data-name="Email" placeholder="" id="email" required=""></div>
                <a href="./signup-talents"><input type="submit" value="Get Started" data-wait="Please wait..." class="button w-button"></a>
              </form>
              <div class="w-form-done">
                <div>Thank you! Your submission has been received!</div>
              </div>
              <div class="w-form-fail">
                <div>Oops! Something went wrong while submitting the form.</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="hero-form-decoration">
      <div class="decoration-bg bg-primary-3 round-top-left"></div>
      <div class="decoration-tall-inner bg-primary-5 round-top-right"></div>
    </div>
</div>

<div class="section no-bottom-padding"  style="margin-bottom: 100px;">
    <div class="main-container">
      <div class="w-layout-grid grid-halves">
        <div id="w-node-_077b8c0b-df57-30b5-1e1c-8dfde2961b72-8930f3e0" class="container">
          <div class="portrait-image-container align-content-right">
            <div class="portrait-image-bg left bg-primary-3"></div>
            <div class="blurred-image-container"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fa0e2057709539468ff6a_Portrait-02.jpg"
                srcset="https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e2057709539468ff6a_Portrait-02-p-500.jpeg 500w, https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e2057709539468ff6a_Portrait-02-p-800.jpeg 800w, https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e2057709539468ff6a_Portrait-02.jpg 836w"
                sizes="(max-width: 479px) 91vw, (max-width: 767px) 334px, 418px" alt=""
                class="portrait-image blurred-image"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fa0e2057709539468ff6a_Portrait-02.jpg"
                srcset="https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e2057709539468ff6a_Portrait-02-p-500.jpeg 500w, https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e2057709539468ff6a_Portrait-02-p-800.jpeg 800w, https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e2057709539468ff6a_Portrait-02.jpg 836w"
                sizes="(max-width: 479px) 91vw, (max-width: 767px) 334px, 418px" alt=""
                class="portrait-image focussed-image"></div>
            <div class="portrait-image-overlay left">
              <div class="padded-text">
                <div class="text-small">Turbocharge your job search. The best jobs only.
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="container">
          <h4 class="large-heading">Find your dream job, wherever you may be</h4>
          <p>Flexibility is the key to happiness. Whether you’re remote, hybrid, or fully in-office, Talentloop will connect you directly with hiring managers at the best companies that meet your needs best.</p>
          <div class="w-layout-grid vertical-icon-grid">
            <div class="horizontal-icon padded-large"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fb0771fc43a104975889a_icon-voice-id.svg" alt=""
                class="horizontal-icon">
              <h5 class="no-bottom-margin">Create a unique candidate profile</h5>
            </div>
            <div class="horizontal-icon padded-large"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fb077426c0142e96eb483_icon-security-cameras.svg"
                alt="" class="horizontal-icon">
              <h5 class="no-bottom-margin">Search and apply for jobs you want</h5>
            </div>
            <div class="horizontal-icon padded-large"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fb077426c0142e96eb483_icon-security-cameras.svg"
                alt="" class="horizontal-icon">
              <h5 class="no-bottom-margin">A Talentloop staff will get in touch asap</h5>
            </div>
          </div>
        </div>
      </div>
    </div>
</div>

<div class="section bg-primary-1">
    <div class="main-container">
      <div class="w-layout-grid grid-halves">
        <div class="container align-center">
          <div class="section-heading">
            <h3 class="display-heading-2 text-white no-bottom-margin">Start the next chapter in your career here.</h3>
          </div>
          <div class="w-layout-grid vertical-text-grid">
            <div>
              <h4 class="text-white">Companies apply to you</h4>
              <div>Sit back and let companies send you interview requests.</div>
            </div>
            <div>
              <h4 class="text-white">Transparent offers</h4>
              <div>Compare exclusive interview requests with salary details upfront.</div>
            </div>
            <div>
              <h4 class="text-white">No commitment</h4>
              <div>100% free and confidential. Choose which interview to accept, completely risk-free.</div>
            </div>
            <div>
                <h4 class="text-white">Skills-based profiles</h4>
                <div>Create a job search profile focused on your skills rather than experience to land your dream job.</div>
            </div>
          </div>
        </div>
        <div id="w-node-da199a86-e56e-7936-fbcc-482df5b10b60-8930f3e0" class="container align-center">
          <div class="portrait-image-container">
            <div class="portrait-image-bg bg-primary-3"></div>
            <div class="blurred-image-container"><img
                src="./Optic - Webflow HTML Website Template_files/5f0fa0e2261e39aa24e26d92_Portrait-04.jpg"
                srcset="https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e2261e39aa24e26d92_Portrait-04-p-500.jpeg 500w, https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e2261e39aa24e26d92_Portrait-04-p-800.jpeg 800w, https://assets.website-files.com/5f0cefea45df2a2a5af4fa7d/5f0fa0e2261e39aa24e26d92_Portrait-04.jpg 836w"
                sizes="(max-width: 479px) 91vw, (max-width: 767px) 334px, 418px" alt=""
                class="portrait-image focussed-image"></div>
          </div>
        </div>
      </div>
    </div>
</div>

<div class="section top-padding-small">
    <div class="main-container">
      <div class="logo-row-title">
        <div class="text-muted">From household names to emerging startups, and everything in between.</div>
      </div>
      <div class="logo-row"><img
          src="https://epicstartups.co/assets/sigma-logo.png" alt=""
          class="logo-row-item"><img
          src="" alt=""
          class="logo-row-item size:0.1" ><img
          src="https://epicstartups.co/assets/hantargo-logo.png" alt=""
          class="logo-row-item"><img
          src="https://epicstartups.co/assets/limitd-logo.png" alt=""
          class="logo-row-item"></div>
    </div>
</div>

<div class="rating-section bg-primary-1">
    <div class="main-container">
      <div class="container wide top-layer">
        <h1 class="display-heading-2 text-white">Build something you’re proud of.</h1>
        <p>If you're a developer, product manager, or designer, our employers want to meet you.</p>
        <a href="" class="button large w-inline-block">
            <div>Get Started</div>
        </a>
      </div>
    </div>
</div>

<div class="footer-2 border-bottom wf-section">
	<div class="main-container">
		<div class="w-layout-grid footer-2-grid">
			<div class="footer-2-contact-details">
				<!-- <a href="" class="footer-2-logo w-inline-block"><img src="" alt="" class="logo-large" /></a> -->
				<p>Lumi Tropicana, Persiaran Tropicana<br />47800, Selangor<br />Malaysia</p>
				<div class="w-layout-grid menu-vertical-grid">
					<a href="tel:+60183915232" class="hover-link icon-link w-inline-block">
						<div>+60183915232</div>
					</a><a href="mailto:hello@talentloop.co" class="hover-link icon-link w-inline-block">
						<div>hello@talentloop.co</div>
					</a>
				</div>
			</div>

			<div class="w-layout-grid footer-menus-grid footer-2-menus">
				<div>
					<div class="text-uppercase footer-menu-title">Company</div>
					<div class="w-layout-grid menu-vertical-grid">
						<a href="./about" class="hover-link">About Us</a><a href="./faq" class="hover-link"
							>FAQ</a
						><a href="./jobs" class="hover-link">Careers</a><a
							href="./blogs"
							aria-current="page"
							class="hover-link w--current">Blogs</a
						>
					</div>
				</div>
				<div>
					<div class="text-uppercase footer-menu-title">
						<a href="./talents" class="hover-link">Jobseekers</a>
					</div>
				</div>

				<div>
					<div class="text-uppercase footer-menu-title">
						<a href="./employers" class="hover-link">Employers</a>
					</div>
				</div>
			</div>
		</div>

		<div class="text-center">
			<div class="text-small muted">
				© Talentloop • Powered by <a href="https://sigmaschool.co/" target="_blank">Sigma School</a>
			</div>
		</div>
	</div>
</div>

