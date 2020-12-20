<template>
    <div>
        <b-navbar toggleable="lg" type="dark" variant="info">
            <b-navbar-brand href="#"><router-link :to="{name: 'Home'}" class="nav-link text-white">Inicio</router-link></b-navbar-brand>

            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

            <b-collapse id="nav-collapse" is-nav>
            <!-- Right aligned nav items -->
            <b-navbar-nav class="ml-auto text-white">
                <b-navbar-brand href="#"><router-link :to="{name: 'Registro'}" class="nav-link text-white"><strong>Regitro</strong></router-link></b-navbar-brand>
                <b-navbar-brand href="#"><router-link :to="{name: 'Login'}" class="nav-link text-white">Ingresar</router-link></b-navbar-brand>
            </b-navbar-nav>
            </b-collapse>
        </b-navbar>
        </div>
</template>