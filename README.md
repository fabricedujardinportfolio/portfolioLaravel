# portfolioLaravel
Portfolio personnel fait en laravel


<h2>HELP</h2>
<p>Crée un controller Ressource avec son model !</p>
<code>php artisan make:controller UserController --resource --model=User</code>


<p>Création d'une nouvel migration (create_ ... _table)</p>
<code>php artisan make:migration create_categorys_table </code>




<h2>Commande Migration :</h2>
<h3>Migration des table :</h3>
<p>php artisan migrate</p>
<h3>Refresh des migratioins des tables: </h3>
<p>php artisan migrate:fresh</p>

<h2>Intégration spécifique :</h2>

<h3>Pagination Bootstrap</h3>
<code>Pagination Bootstrap -> [App/Providers/AppServiceProvider.php]</code>
<code>Paginator::useBootstrap();</code>

<pre>
    <code>
    public function boot()
    {
        Paginator::useBootstrap();
    }
    </code>
</pre>
