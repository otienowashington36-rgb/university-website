<style>
    /* Styling for the About Section */
    #about {
        padding: 60px 20px;
        max-width: 900px;
        margin: 0 auto;
        font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        line-height: 1.8;
        color: #333;
        text-align: center;
    }

    .about-title {
        font-size: 2.5rem;
        margin-bottom: 20px;
        color: #2c3e50;
        position: relative;
        display: inline-block;
    }

    .about-title::after {
        content: '';
        display: block;
        width: 50%;
        height: 4px;
        background: #007bff;
        margin: 10px auto 0;
        border-radius: 2px;
    }

    .about-content {
        background: #f8f9fa;
        padding: 30px;
        border-radius: 15px;
        box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        border-left: 5px solid #007bff;
        text-align: left;
    }

    .about-content p {
        margin-bottom: 15px;
        font-size: 1.1rem;
    }

    .highlight {
        color: #007bff;
        font-weight: bold;
    }
</style>

<section id="about">
    <h2 class="about-title">About Me</h2>
    <div class="about-content">
        <p>
            Hello! I am <span class="highlight">Washington Edison</span>, a dedicated Web Developer based in Kenya. 
            I am passionate about creating digital experiences that are both visually stunning and technically robust.
        </p>
        <p>
            I specialize in <span class="highlight">Frontend Development</span>, utilizing modern technologies like HTML5, CSS3, and JavaScript to build responsive websites. My goal is to bridge the gap between complex backend logic and a seamless user interface.
        </p>
        <p>
            When I'm not coding, I'm focused on mastering industry-standard workflows—using tools like <span class="highlight">Git, VS Code, and ESLint</span> to ensure my code is clean, efficient, and ready for production.
        </p>
    </div>
</section>
