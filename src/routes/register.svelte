<div class="container-fluid d-flex justify-content-center align-items-center">
    <div class="card card-connexion">
        <div class="card-body">
            <form>
                <div class="form-floating mb-3">
                    <input type="pseudo" class="form-control" id="floatingInputPseudo"
                    placeholder="Pseudo">
                    <label for="floatingInputPseudo">
                        Nom d'utilisateur
                    </label>
                </div>
                <div class="form-floating mb-3">
                    <input type="email" class="form-control" id="floatingInputEmail" aria-describedby="emailHelp" placeholder="name@example.com">
                    <div id="emailHelp" class="form-text">
                        Nous ne partageons pas votre email.
                    </div>
                    <label for="floatingInputEmail">
                        Email
                    </label>
                </div>
                <div class="form-floating mb-5">
                    <input type="password" class="form-control" id="floatingInputPassword" placeholder="Mot de passe">
                    <label for="floatingInputPassword">
                        Mot de passe
                    </label>
                </div>
                <button class="w-100 btn btn-lg btn-dark text-uppercase" type="submit">S'enregistrer</button>
                <p class="mt-3 text-muted text-center border-top pt-2">Déjà inscrit ?</p>
                <button class="w-100 btn btn-lg btn-outline-dark text-uppercase" type="submit">Se connecter</button>
                <p class="mt-5 mb-3 text-muted text-center">&copy; 2017–2021</p>
            </form>
        </div>
    </div>
</div>

<style>
    .card {
        width: 400px;
    }
</style>