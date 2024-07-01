 <template>
    <div class="principal">
        <div class="jumbotron bg-light text-center">
        <h1 class="display-5 fw-bold">The rick And morty API</h1>
    </div>


    <div class="container mt-5">

        <div class="row d-flex justify-content-center">
            <div class="col-8 b-3">
                <input type="search" class="form-control form-control-lg" placeholder="Buscar...">

                
                <!--introducimos el card-->
                <div class="col-12 col-lg-6">
                    <div class="card mb-3 rounded-5 bg-black" >
                    <div class="row g-0">
                        <div class="col-12 col-md-4">
                            <img src="https://rickandmortyapi.com/api/character/avatar/70.jpeg" class="rounded-5" width="100%" height="100%" alt="...">
                        </div>
                        <div class="col-12 col-md-8">
                            <div class="card-body text-white">
                                <h4 class="card-title">Concerto</h4>
                                <p class="card-text">
                                🔴Dead Humanoid
                                </p>
                                <span class="text-danger"><b>Last known location:</b></span>
                                <p>Unknown</p>
                                <span class="text-danger"><b>Origin:</b></span>
                                <p>Pickle Rick</p>
                                
                            </div>
                        </div>
                    </div>
                </div>
                </div>
                
            </div>

        </div>
    </div>

    </div>
    
    




</template>
 <script>
 export default {
    
 }
 </script>
 <style>
    
 </style>