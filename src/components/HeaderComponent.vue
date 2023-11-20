<template>
    <header>
        <div class="nav-cont w-100 position-fixed">
            <nav class="navbar navbar-expand-lg bg-dark">
                <div class="container-fluid px-5">
                  <a class="navbar-brand text-light" href="#">Edoardo<br>Lannino</a>
                  <button class="navbar-toggler border-light" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon navbar-dark"></span>
                  </button>
                  <div class="collapse navbar-collapse d-lg-flex justify-content-end" id="navbarNavDropdown">
                    <ul class="navbar-nav text-center">
                      <li class="nav-item rounded-pill">
                        <a class="nav-link active" aria-current="page" href="#">Chi sono?</a>
                      </li>
                      <li class="nav-item rounded-pill">
                        <a class="nav-link" href="#">I miei lavori</a>
                      </li>
                      <li class="nav-item rounded-pill">
                        <a class="nav-link" href="#">Contattami</a>
                      </li>
                      <!-- <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle text-light" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                          Dropdown link
                        </a>
                        <ul class="dropdown-menu">
                          <li><a class="dropdown-item" href="#">Action</a></li>
                          <li><a class="dropdown-item" href="#">Another action</a></li>
                          <li><a class="dropdown-item" href="#">Something else here</a></li>
                        </ul>
                      </li> -->
                    </ul>
                  </div>
                </div>
            </nav>
        </div>
    </header>
</template>
  
<script>
export default {
    name: 'HeaderComponent',
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
  header {
    .nav-cont {
      .container-fluid {
        .collapse {
          .navbar-nav {
            .nav-item {
              .nav-link {
                color: white;
              }
            }
            .nav-item:active {
              background-color: white;
              .nav-link {
                color: black;
              }
            }
          }
        }
      }
    }
  }
</style>