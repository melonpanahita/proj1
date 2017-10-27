# Q0: Why is this error being thrown?

There is no Pokemon model

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *

In the home_controller.rb, the index method makes it so that the home page will load a random trainlerless pokemon. The common fact is that they do not have trainers.

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.

Creates a form with a button that submits to the capture route which calls the capture function in the pokemons controller. The id that is specified in "capture_path(id: @pokemon)" is used for the id in the capture method to find that specific pokemon. 

# Question 3: What would you name your own Pokemon?

"Shooky"

# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?

I passed 'trainer_path(current_trainer)' into the redirect_to. 

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.

# Give us feedback on the project and decal below!

# Extra credit: Link your Heroku deployed app
