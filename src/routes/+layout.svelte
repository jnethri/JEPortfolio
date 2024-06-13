<body class="text-primary-700 dark:text-primary-300 border dark:border-gray-800" >
    <div class="wrapper">
        
        <main>
            <slot></slot>
        </main>
        
        <!-- Footer -->
        <footer class="footer py-4 mt-8">
            <div class="container mx-auto px-4">
                <p>&copy; 2024 James Ethridge's Portfolio Site. All rights reserved.</p>
            </div>
        </footer>
    </div>
</body>

<script>
    import "../app.css";
</script>

<style>
    footer {
        height: 85%;
        margin: -10px;
    }
    .wrapper {
        display: grid;
        grid-template-rows: auto 1fr auto;
        min-height: 100vh;
    }
</style>