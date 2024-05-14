<header class="py-4">
    <Navbar let:NavContainer color="primary">
        <NavContainer style="align-items: center" class="border px-5 py-2 rounded-lg">
            <NavBrand href="/">
                <h1 class="text-2xl font-bold">James Ethridge</h1>
            </NavBrand>
            <NavHamburger />
            <NavUl class="ml-auto">
                <NavLi href="/">Home</NavLi>
                <NavLi href="/about">About</NavLi>
                <NavLi href="/projects">Projects</NavLi>
                <NavLi href="/contact">Contact</NavLi>
            </NavUl>
            <DarkMode />
        </NavContainer>
    </Navbar>
    
</header>


<slot></slot>

<script>
    import "../app.css";
    import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
    import { DarkMode } from 'flowbite-svelte';
</script>

<style>

</style>