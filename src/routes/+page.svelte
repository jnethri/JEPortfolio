<!-- Content -->
<div id="content">
    <div id="main" class="full-width-div">
        <span style="font-size: 85px;">Hi, I'm James! A <span class="intro-bold">back-end</span> developer.</span><br />
        <span style="position:relative; left:80px; top:-40px">I have been a programmer and tech enthusiast for nearly 15 years, primarily focused on Back-End Development, Javascript/Typescript, and Svelte. Feel free to browse through my portfolio, and if you're intrigued, please don't hesitate to reach out!</span>
    </div><br />
    <div id="about" class="full-width-div title">
        About
    </div>
    <div id="projects" class="full-width-div title">
        Projects
    </div>
    <div id="contact" class="full-width-div title">
        Contact
    </div>
</div>

<div class="container mx-auto px-4 py-8">
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Content Goes Here -->
        <div class="bg-white p-4 shadow rounded-lg">
            <h2 class="text-xl font-bold mb-4">Section 1</h2>
            <p>Your content here.</p>
        </div>
        <div class="bg-white p-4 shadow rounded-lg">
            <h2 class="text-xl font-bold mb-4">Section 2</h2>
            <p>Your content here.</p>
        </div>
        <div class="bg-white p-4 shadow rounded-lg">
            <h2 class="text-xl font-bold mb-4">Section 3</h2>
            <p>Your content here.</p>
        </div>
    </div>
</div>

<!-- Footer -->
<footer class="py-4 mt-8">
    <div class="container mx-auto px-4">
        <p>&copy; 2024 Your Website. All rights reserved.</p>
    </div>
</footer>

<script>
    import "../app.css";
</script>

<style>
    .intro-bold {
        font-weight: bold;
        font-size: 90px;
    }

    .title {
        font-weight: bold;
        font-size: 90px;
        max-width: fit-content;
    }

    .full-width-div {
        font-size: 35px;
        height: 100vh;
        width: 60%;
        margin: auto;
        padding: 10px;
    }

    #main {
        max-width: fit-content;
        margin-left: auto;
        margin-right: auto;
        display: flex;
        align-items: center;
    }

</style>