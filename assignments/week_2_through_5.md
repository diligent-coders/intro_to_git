# Week 2
So first off, I'd like to congratulate everyone for beginning this journey to learning programming.
I began this journey myself in April 2015, and I'll try and apply the best practices I've picked up over the years in teaching you all.
I'm primarily a [Ruby](https://www.ruby-lang.org/en/documentation/installation/) developer, so we'll use that as the base for exploring the basic concepts of programming.
I'll try to design this course in way where you can jump in and out whenever you want and you'll have different things to do.
We will take our *time* to do this and there will be *little to no pressure*.
Everyone has different responsibilities and lives and capacity of what they can handle, and this can be seem daunting at first, but you'll get there! Trust me, I had zero technical or programming knowledge before 2015.

# First Assignment (Multi Week Project) - Learn the Basics of Ruby

# How do I learn?
I started learning Ruby with Code Academy (which has a free and paid tier)- so we'll use their [https://www.codecademy.com/learn/learn-ruby](beginner's Ruby course).
Go ahead and use your Github account for authentication if you'd like, since you already made that!
The great thing about using Code Academy is that it is browser based and saves your progress, its easy to jump on and off and you won't need install anything further.
You'll learn the fundamentals of programming, and every single thing you learn in it will be applicable to the "projects" and "challenges".

# Assignment to submit
Once you've learned enough from the Code Academy course, I'd like you to submit pull request containing a `.rb` file (don't worry if you don't know what this is yet)
in the `submissions` directory (this might not exist yet by the time you see this message, check out [https://github.com/ZASMan/diligent_coders/issues/2](this Github issue) I made about it) containing solutions to the following questions.
It might take a while before you can do this assignment, so take your time. There's no rush!

1) You'll have to install Ruby locally. The official [Ruby website](https://www.ruby-lang.org/en/documentation/installation/) should have detailed instructions for your operating systems.
2) Create an [https://ruby-doc.org/core-2.7.0/Array.html](array) of [https://ruby-doc.org/core-3.0.0/String.html](strings) with each string value being equal to a video game console that you like. Call the variable, `favorite_video_game_systems`.
3) Search through the array documentation (linked in step one) for a way to check if a value is present in an array. Take note of that.
4) Now, I want you to create a [method](https://www.tutorialspoint.com/ruby/ruby_methods.htm) that will return `true` if any of your favorite video game systems are a home based Nintendo system. Here's an array of those values:
`nintendo_home_consoles = ['NES', 'SNES', 'N64', 'Gamecube', 'Wii', 'Wii U', 'Switch']`

So, the end result might look something like this:

# Remember, the video_game_console_list parameter will be an array of strings
`
def is_nintendo_system(video_game_console_list)
  nintendo_home_consoles = ['NES', 'SNES', 'N64', 'Gamecube', 'Wii', 'Wii U', 'Switch']
  # if video_game_console_list contains any Nintendo consoles, return true
  # Otherwise, it will return false

end
`
You could also refactor this into a [boolean method](https://medium.com/@sologoubalex/boolean-methods-in-ruby-94a2e907e5ea) to make your code even more DRY. You could also DRY your code up and use an implicit [falsey](https://learn.co/lessons/truthiness-in-ruby-readme) return signature if your method doesn't evaluate to `true`.
DRY is an acronym for "Do Not Repeat Yourself", you can learn more about that acronym [here](https://stackoverflow.com/questions/12368436/what-is-mean-by-this-code-is-dry-in-ror3#:~:text=order%20by-,3,keys%20getting%20worn%20out!)
