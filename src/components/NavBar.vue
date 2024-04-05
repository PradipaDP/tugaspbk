<template>
     <header class="header">
      <!-- Navigation -->
      <nav class="navigation">
        <a href="#home">Home</a>
        <a href="#Biodata">Biodata</a>
        <a href="#Portofolio">Portofolio</a>
        <a href="#Galeri">Galeri</a>
        <a href="#Prestasi">Prestasi</a>
      </nav>
      <a href="#" class="btn-talk">. . .</a>
    </header>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>


<style scoped>
body {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Poppins', sans-serif;
}

.header {
    position: fixed;
    top: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 100%;
    padding: 20px 10%;
    background: transparent;
    display: flex;
    justify-content: center;
    align-items: center;
    z-index: 100;
}

.navigation {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    margin: 0;
    padding: 0;
    list-style-type: none;
    display: flex;
    justify-content: center;
    align-items: center;
}

.navigation li {
    margin-right: 20px; /* Reduce margin between navigation links */
}

.navigation a {
    font-size: 1.1em;
    color: #fbf5f5;
    text-decoration: none;
    font-weight: 500;
    transition: color 0.3s; /* Apply transition to color change */
}

.navigation a:hover {
    color: #ad2831;
}

.btn-talk {
    color: #fff;
    text-decoration: none;
    padding: 5px;
    background: #ad2831;
    border-radius: 10px;
    border: 2px solid #ad2831;
    font-weight: 1000;
    transition: background 0.3s, color 0.3s; /* Apply transition to background and color */
    margin-left: auto;
}

.btn-talk:hover {
    color: #ad2831;
    background: transparent;
}

</style>


