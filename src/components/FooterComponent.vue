<template>
    <footer class="bg-secondary">
        <section class="foot-parts foot-1">
            <div class="text-cont w-75 m-auto d-lg-flex justify-content-center align-items-center gap-5 text-light px-3 pt-4">
                <h3 class="text-center">Edoardo Lannino</h3>
                <ul class="list-group">
                    <li class="list-group-item bg-transparent text-light text-center"><b>Telefono:</b> +39 340 843 5438</li>
                    <li class="list-group-item bg-transparent text-light text-center"><b>Mail:</b> edlannino@tutanota.com</li>
                </ul>
            </div>
        </section>
        <section class="foot-parts foot-2 text-center text-light pt-2 pb-3">
            <p class="d-md-none pt-2">Per maggiori informazioni sui miei profili e le mie piattaforme vi rimando alla sezione <a href="#">Contatti</a>.</p>
            <h5 class="d-none d-md-block pt-2">Per maggiori informazioni sui miei profili e le mie piattaforme vi rimando alla sezione <a href="#">Contatti</a>.</h5>
        </section>
    </footer>
</template>
  
<script>
export default {
    name: 'FooterComponent',
    data() {
        return {

        }
    },
    methods: {

    },
    components: {

    },
    mounted() {

    }
}
</script>

<style lang="scss" scoped>
    footer {
        .foot-parts {
            background-color: rgba(49, 62, 80, 1);
            /*.text-cont {
                .list-group {
                    li:hover {
                        background-color: rgba(69, 85, 97, 1);
                    }
                }
            }*/
        }
    }
</style>