<template lang="html">
    <div class="app">
        <b-navbar>
            <b-navbar-brand>
                <img src="../assets/imagenes/fide-logo.svg" class="d-inline-block align-top" alt="Kitten">
                <h1>International Chess Federation</h1>
            </b-navbar-brand>
        </b-navbar>
    </div>
</template>

<script>
export default {
};
</script>

<style lang="scss" scoped>
$color_fondo: #334166;
$color_letras: #FFFFFF;

.app {
    background-color: $color_fondo;

    h1 {
        color: $color_letras;
    }
}
</style>