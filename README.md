# Building the Repositary
You can download/clone the repository to your computer and copy
all the files in inside ```demo/html/webarch``` to ```vendor/assets/webarch_core```

# Or installing from scratch

The following will be a simple guide to use Webarch admin dashboard template with Ruby on Rails (Tested on **v5.1.4 Rails and Webarch v3.0**)

1. Create a new Rails App
```rails new myappp```

2. Create two folder called ```webarch_core``` and ```webarch_plugins```
inside ```vendor/assets``` folder

3. Copy all the files in inside ```demo/html/webarch``` to ```vendor/assets/webarch_core```

4. Copy all the files in inside ```demo/html/assets/plugins``` to ```vendor/assets/webarch_plugins```

5. In your ```config/application.rb``` file add the following code inside the class like this [application.rb](https://github.com/revoxltd/webarch-rails-sample/blob/master/config/application.rb)

6. Replace your ```app/assets/stylesheets/application.css``` like the following [application.css](https://github.com/revoxltd/webarch-rails-sample/blob/master/app/assets/stylesheets/application.css)

7. Replace your ```app/assets/javascripts/application.js``` like the following [application.js](https://github.com/revoxltd/webarch-rails-sample/blob/master/app/assets/javascripts/application.js)

8. Replace your ```app/views/layouts/application.html.erb``` like the following [application.html.erb](https://github.com/revoxltd/webarch-rails-sample/blob/master/app/views/layouts/application.html.erb)


###Done!
