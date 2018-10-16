// /code/cheftubeapp App Tracking Notes

composer create-project laravel/laravel myprojectname

~Homestead$ vagrant up
~Homestead$ vagrant ssh

# Update NPM install and make sure everything is jazzy.


    $   vagrant@homestead:~/code/cheftubeapp$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
        vagrant@homestead:~$ nvm install --latest-npm
        vagrant@homestead:~/code/cheftubeapp$ sudo npm install -g npm
        vagrant@homestead:~/code/cheftubeapp$ npm rebuild node-sass
        vagrant@homestead:~/code/cheftubeapp$ npm install
        vagrant@homestead:~/code/cheftubeapp$ npm run dev

            // Sample Output

                DONE  Compiled successfully in 7589ms                                                                                                                                          8:38:42 PM

                Asset     Size  Chunks                    Chunk Names
                /js/app.js  1.38 MB       0  [emitted]  [big]  /js/app
                /css/app.css   198 kB       0  [emitted]         /js/app

            // Neatly Place CSS inside /sass/partials/_*.scss and import into /sass/app.scss for NPM compile.

    $ Run NPM Dev to view changes or npm watch for live.

# No errors 'first commit' git master branch here.

# PHP Artisan make authentication.


    $    vagrant@homestead:~/code/cheftubeapp$ php artisan make:auth
            Authentication scaffolding generated successfully.

// Create Clean Code with snippets of blade.php layouts and __.scss files to liking for base layout.
