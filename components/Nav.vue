<template>
    <div class="container navbar navbar-expand-lg">
        <div class="container shadow">
            <img class="image py-3" src="assets/logo-smkn4.webp" alt="">
            <h6 class="">SMK Negeri 4 Tasikmalaya</h6>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <nuxt-link to="/" class="nav-link active" aria-current="page" href="#">Beranda</nuxt-link>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Profil
                        </a>
                        <ul class="dropdown-menu">
                            <li><nuxt-link to="/profil/identitas" class="dropdown-item">Identitas Sekolah</nuxt-link></li>
                            <li><nuxt-link to="/profil/sejarah" class="dropdown-item">Sejarah</nuxt-link></li>
                            <li><nuxt-link to="/profil/visiMisi" class="dropdown-item">Visi & Misi</nuxt-link></li>
                            <li><nuxt-link to="/profil/kepsek" class="dropdown-item">Kepala Sekolah</nuxt-link></li>
                            <li><nuxt-link to="/profil/guru" class="dropdown-item">Guru & Staf</nuxt-link></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Kompetensi Keahlian
                        </a>
                        <ul class="dropdown-menu">
                            <li><nuxt-link to="/kompetensi/tsm" class="dropdown-item">Teknik dan Bisnis Sepeda Motor</nuxt-link></li>
                            <li><nuxt-link to="/kompetensi/tkj" class="dropdown-item">Teknik Jaringan Komputer</nuxt-link></li>
                            <li><nuxt-link to="/kompetensi/rpl" class="dropdown-item">Rekayasa Perangkat Lunak</nuxt-link></li>
                            <li><nuxt-link to="/kompetensi/dkv" class="dropdown-item">Desain Komunikasi Visual</nuxt-link></li>
                            <li><nuxt-link to="/kompetensi/toi" class="dropdown-item">Teknik Otomasi Industri</nuxt-link></li>
                        </ul>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            Kesiswaan
                        </a>
                        <ul class="dropdown-menu">
                            <li><nuxt-link to="/kesiswaan/organisasi" class="dropdown-item">Organisasi</nuxt-link></li>
                            <li><nuxt-link to="/kesiswaan/ekskul" class="dropdown-item">Ekstrakurikuler</nuxt-link></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="/galeri/" class="nav-link active" aria-current="page" href="#">Galeri</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="/berita/" class="nav-link active" aria-current="page" href="#">Berita</nuxt-link>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=League+Spartan:wght@500&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
.container{
    max-width: 100%;
    margin: 0;  
}

h5,ul,a .nav-item{
    font-family: "Poppins",serif;
}
.nav-link{
    color: black;
}
.image{
    width: 50px;
    margin-left: 5%;
    padding-bottom: 1%;
}

.nav-item {
    margin-right: 30px;
    font-weight: 500;
}

h6 {
    margin-left: 20px;
}

.judul{
    margin-right: 50%;
    font-size: 20px;
}

p{
    font-size: 10px;
}

</style>