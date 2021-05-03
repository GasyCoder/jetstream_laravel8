<h1>Laravel Jetstream</h1>
<p>Laravel Jetstream is a beautifully designed application starter kit for Laravel and provides the perfect starting point for your next Laravel application. Jetstream provides the implementation for your application's login, registration, email verification, two-factor authentication, session management, API via Laravel Sanctum, and optional team management features.</p>

<p>Jetstream is designed using Tailwind CSS and offers your choice of Livewire or Inertia scaffolding.</p>

<h1>Installing Jetstream</h1>
<p>You may use Composer to install Jetstream into your new Laravel project:</p>

<pre>
	<code>
composer require laravel/jetstream
	</code>
</pre>

<p>After installing the Jetstream package, you may execute the jetstream:install Artisan command. This command accepts the name of the stack you prefer (livewire or inertia). In addition, you may use the --teams switch to enable team support. The jetstream:install command will also install a suite of "feature" tests that provide test coverage for the features provided by Jetstream.</p>

<p>You are highly encouraged to read through the entire documentation of Livewire or Inertia before beginning your Jetstream project.</p>

<h1>Install Jetstream With Livewire</h1>
<pre>
	<code>
php artisan jetstream:install livewire
php artisan jetstream:install livewire --teams
	</code>
</pre>
<h1>Or, Install Jetstream With Inertia</h1>

<pre>
	<code>
php artisan jetstream:install inertia
php artisan jetstream:install inertia --teams
	</code>
</pre>

<h1>Finalizing The Installation</h1>
<p>After installing Jetstream, you should install and build your NPM dependencies and migrate your database:</p>
<pre>
	<code>
npm install
npm run dev
php artisan migrate
	</code>
</pre>

<h1>Livewire</h1>
<p>If you are using the Livewire stack, you should first publish the Livewire stack's Blade components:</p>
<pre>
	<code>
php artisan vendor:publish --tag=jetstream-views
	</code>
</pre>

<h1>After customizing these components, you should rebuild your assets:</h1>

<pre>
	<code>
npm run dev or npm run watch
	</code>
</pre>

<h1>Check this link to know more about Jetstream : </h1>
<a href="https://jetstream.laravel.com/2.x/installation.html">Jetstream</a> 
<br>

<h3>License</h3>
The MIT License (MIT). Please see <a href="https://github.com/bakateam/merakiui/blob/main/LICENSE" target="_blank">License File</a> for more information.
