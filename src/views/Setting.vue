<template>
    <div class="settings-pages">
        <div class="container page">
            <div class="row">
                <div class="col-md-6 offset-md-3 col-xs-12">
                    <h1 class="text-xs-center">Settings</h1>
                    <form >
                        <fieldset>
                            <fieldset class="form-group">
                                <input type="text" class="form-control" placeholder="Profile Url">
                            </fieldset>
                            <fieldset class="form-group">
                                <input type="text" class="form-control form-control-lg" placeholder="Name">
                            </fieldset>
                            <fieldset class="form-group">
                                <textarea type="text" class="form-control form-control-lg" rows="8" placeholder="Description"></textarea>
                            </fieldset>
                            <fieldset class="form-group">
                                <input type="email" class="form-control form-control-lg" placeholder="Email">
                            </fieldset>
                            <fieldset class="form-group">
                                <input type="password" class="form-control form-control-lg" placeholder="Password">
                            </fieldset>
                        </fieldset>
                        <button class="btn btn-lg btn-secondary pull-xs-right">
                            Update
                        </button>
                    </form>

                </div>
            </div>
        </div>
    </div>
</template>