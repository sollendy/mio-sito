<template>
    <footer class="bg-secondary">
        <section class="saluti">
            <div class="text-cont w-75 m-auto text-center text-light px-3 py-3">
                <h3>Edoardo Lannino</h3>
                <ul class="list-group">
                    <li class="list-group-item bg-transparent text-light"><b>Telefono:</b> +39 340 843 5438</li>
                    <li class="list-group-item bg-transparent text-light"><b>Mail:</b> edlannino@tutanota.com</li>
                </ul>
                <p class="d-md-none pt-2">Per maggiori informazioni sui miei profili e le mie piattaforme vi rimando alla sezione <a href="#">Contatti</a>.</p>
                <h5 class="d-none d-md-block pt-2">Per maggiori informazioni sui miei profili e le mie piattaforme vi rimando alla sezione <a href="#">Contatti</a>.</h5>
            </div>
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
        .saluti {
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