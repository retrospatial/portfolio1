
<script>
    // images
    import fandometrics from '../assets/images/fandometrics.gif';
    import animorphs from '../assets/images/animorphs.png';
    import car from '../assets/images/car.png';
    import buffy from '../assets/images/buffy.png';
    import japan from '../assets/images/japan.png';
    import carlos from '../assets/images/design/carlos.jpeg';
    import charles from '../assets/images/design/charles.jpeg';
    import mixue1 from '../assets/images/design/mixue1.png';
    import mixue2 from '../assets/images/design/mixue2.png';
    import mixue3 from '../assets/images/design/mixue3.png';

    // files
    import resume from '../assets/files/FlorinaSutantoResume.pdf';
</script>

<main>
    <h1>FLORINA<br>SUTANTO</h1>
    <p class="links">
        <span><a href={resume}>resume</a></span>
        <span><a href="https://www.linkedin.com/in/florinasutanto/">linkedin</a></span>
        <span><a href="https://github.com/retrospatial">github</a></span>
        <span><a href="mailto:florinasutanto@gmail.com">email</a></span>
    </p>

</main>

<div class="projects" id="projects-section">
    <h2>PROJECTS</h2>

    <div class="project-grid"> 

        <div class="project-entry">
            <a href="https://florinasutanto.com/tumblr-fandometrics/">
                <img src={fandometrics} alt="fandometrics">
            </a>
                <div class="description">

                    <a href="https://florinasutanto.com/tumblr-fandometrics/">
                        <h3>SHIP AND LET SHIP</h3>
                    </a>
                    
                    <p class="org">LEDE PROGRAM</p>
                    <p class="desc">Charting top Tumblr ships using the annual Fandometrics rankings.</p>
                    <p class="skills">WRITING, DATA, DESIGN, DEVELOPMENT</p>
                </div>
        </div>

        <div class="project-entry">
            <a href="https://florinasutanto.com/animorphs/">
                <img src={animorphs} alt="animorphs">
            </a>
                <div class="description">

                    <a href="https://florinasutanto.com/animorphs/">
                        <h3>THE SEARCH FOR ANIMORPHS</h3>
                    </a>
                    
                    <p class="org">LEDE PROGRAM</p>
                    <p class="desc">A nostalgic look at libraries, maps, and K. A. Applegate’s seminal children’s series.</p>
                    <p class="skills">WRITING, MAPPING, DESIGN, DEVELOPMENT</p>
                </div>
        </div>

        <div class="project-entry">
            <a href="https://florinasutanto.com/buffy-podcasts/">
                <img src={buffy} alt="buffy">
            </a>
                <div class="description">

                    <a href="https://florinasutanto.com/buffy-podcasts/">
                        <h3>ARE PEOPLE STILL TALKING ABOUT BUFFY?</h3>
                    </a>
                    
                    <p class="org">LEDE PROGRAM</p>
                    <p class="desc">Let's look at Spotify podcast data to find out.</p>
                    <p class="skills">WRITING, DATA, DESIGN, DEVELOPMENT</p>
                </div>
        </div>

        <div class="project-entry">
            <a href="#">
                <img src={car} alt="formula1">
            </a>
                <div class="description">

                    <a href="#">
                        <h3>RACE AND SPACE IN F1</h3>
                    </a>
                    
                    <p class="org">DATA VIZ CLASS</p>
                    <p class="desc">Visualizing the demographic and geographic evolution of Formula 1.</p>
                    <p class="skills">RESEARCH, DATA, VISUALIZATION</p>
                </div>
        </div>

        <div class="project-entry">
            <a href="https://storymaps.arcgis.com/stories/0067c80743bb419e9a666a253255504b">
                <img src={japan} alt="formula1">
            </a>
                <div class="description">

                    <a href="https://storymaps.arcgis.com/stories/0067c80743bb419e9a666a253255504b">
                        <h3>JAPAN AND THE WEST</h3>
                    </a>
                    
                    <p class="org">DIGITAL SCHOLARSHIP FELLOWSHIP</p>
                    <p class="desc">Tracing the history of Japanese loanwords in English.</p>
                    <p class="skills">RESEARCH, DATA, VISUALIZATION</p>
                </div>
        </div>

    </div>

</div>

<div class="design" id="design-section">
    <h2>DESIGN</h2>

    <div class="design-grid">
        <!-- col 1  -->
        <img src={carlos} alt="carlos sainz edit">
        <img src={mixue3} alt="mixue3">

        <!-- col 2 -->
        <img src={charles} alt="charles leclerc edit">
        <img src={mixue2} alt="mixue2">
    </div>
</div>




