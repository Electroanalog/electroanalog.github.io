---
layout: default
title: Home
---

<div class="home">
	<img src="/img/electroanalog_logo.png" alt="Electroanalog" class="logo" />
	<img src="/img/vice.png" alt="Vintage Integrated Custom Electronics" class="logo" />

	<div style="display: grid; place-items: center; position: relative;">
	  <img src="/img/projects-title.png" alt="GitHub DIY Projects" width="280" class="project-title" />
	  <a style="position: absolute; left: calc(50% - 175px); top: 50%; transform: translateY(-50%);">
	    <svg height="32" width="32" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" style="filter: drop-shadow(2px 2px 0px black);">
	      <path fill="#f0f6fc" d="M12 1C5.923 1 1 5.923 1 12c0 4.867 3.149 8.979 7.521 10.436.55.096.756-.233.756-.522 
	          0-.262-.013-1.128-.013-2.049-2.764.509-3.479-.674-3.699-1.292-.124-.317-.66-1.293-1.127-1.554
	          -.385-.207-.936-.715-.014-.729.866-.014 1.485.797 1.691 1.128.99 1.663 2.571 1.196 3.204.907
	          .096-.715.385-1.196.701-1.471-2.448-.275-5.005-1.224-5.005-5.432 0-1.196.426-2.186 
	          1.128-2.956-.111-.275-.496-1.402.11-2.915 0 0 .921-.288 3.024 1.128a10.193 10.193 0 0 1 
	          2.75-.371c.936 0 1.871.123 2.75.371 2.104-1.43 3.025-1.128 3.025-1.128.605 1.513.221 2.64.111 
	          2.915.701.77 1.127 1.747 1.127 2.956 0 4.222-2.571 5.157-5.019 5.432.399.344.743 1.004.743 
	          2.035 0 1.471-.014 2.654-.014 3.025 0 .289.206.632.756.522C19.851 20.979 23 
	          16.854 23 12c0-6.077-4.922-11-11-11Z" />
	    </svg>
	  </a>
	</div>

	<div class="projects">
	  <div class="project">
		<a href="/sat-srb">Saturn Smart Reset Button</a>
		<div class="description">
		  Switchless mod for Sega Saturn using PIC16F630/76 to control multi-BIOS, region, frequency and reset with RGB LED feedback.
		</div>
		<div class="project-code">SAT-SRB</div>
	  </div>

	<div class="project project-with-image">
	  <div class="project-title-text">
		<a href="/psx-flash-bios">PSX Flash BIOS 40 / 32</a>
		<div class="description">
		  An adapter to replace the original PlayStation (PS1) BIOS with a patched SST39VF040 EEPROM to enable Game ID support for both 40-pin and 32-pin BIOS.
		</div>
		<div class="project-code">PSX-Flash-BIOS</div>
	  </div>
	  <div class="thumb">
		<div style="display: flex; align-items: center; gap: 1rem;">
		  <a href="/psx-flash-bios">
			<img src="/img/psx-fb40.png" alt="PSX Flash BIOS thumbnail"/>
		  </a>
		  <div style="display: flex; flex-direction: column; align-items: center;">
			<div class="also-available" style="margin-bottom: 1px;">Also available at</div>
			<a href="https://oshwlab.com/electroanalog/psx-flash-bios" target="_blank" style="text-align: center;">
			  <img src="https://www.electroanalog.com/img/thumbnail_OSHWLab-logo.png" alt="OSHWLab" style="width: 85px; transition: none; transform: none;" />
			</a>
		  </div>
		</div>
	  </div>
	</div>
		
	<div class="project project-with-image">
	  <div class="project-title-text">
		<a href="/psx-sio-qsb">PSX SIO-qsb for PSIO</a>
		<div class="description">
		  A Quick Solder Board (QSB) alternative to PSIO switchboard for original PlayStation (PS1) consoles. Reduces installation wiring with a more convenient integration point.
		</div>
		<div class="project-code">PSX-SIO-qsb</div>
	  </div>
	  <div class="thumb">
		<div style="display: flex; align-items: center; gap: 1rem;">
		  <a href="/psx-sio-qsb">
			<img src="/img/psx-sioqsb.png" alt="PSX SIO-qsb thumbnail"/>
		  </a>
		  <div style="display: flex; flex-direction: column; align-items: center;">
			<div class="also-available" style="margin-bottom: 1px;">Also available at</div>
			<a href="https://oshwlab.com/electroanalog/psx_sio-qsb" target="_blank" style="text-align: center;">
			  <img src="https://www.electroanalog.com/img/thumbnail_OSHWLab-logo.png" alt="OSHWLab" style="width: 85px; transition: none; transform: none;" />
			</a>
		  </div>
		</div>
	  </div>
	</div>

	  <div class="project">
		<a href="/psx-igr">PSX In-Game Reset</a>
		<div class="description">
		  A reset mod for original PlayStation (PS1) activated via button combo on the controller, built with PIC16F18325/26. Features timing safeguards to avoid unintended resets and optional LED feedback.
		</div>
		<div class="project-code">PSX-IGR</div>
	  </div>
	</div>
</div>
<footer class="footer">
  <div class="contact">
    <strong>Contact:</strong> Wilson F. | <a href="mailto:wilson@electroanalog.com.br">wilson@electroanalog.com.br</a>
  </div>
</footer>
