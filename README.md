# Identicon-Elixir

Create your own unique Github default profile image

## Getting Started

1. Make sure you have Elixir installed. If you don't, then install Homebrew (or run `brew update` if you already have it installed) then run `brew install elixir`. It will take a while.

2. Clone this repo with `git clone https://github.com/thomasrobertgee/identicon-elixir.git`

3. Go into the main directory, open the virtual code runner thing with `iex -S mix`

4. Run `Identicon.main("foo")` but you can replace `foo` with whatever you like, try your name!

5. If successful, the terminal will return `:ok` and a file called foo.png will have been created in the main directory of the app

6. Simply run `open foo.png` to see the file! And there you go, each image will be unique as long as the string you entered is unique. Enjoy!

### This app is part of an Elixir & Phoenix course on Udemy by Stephen Grider, which can be found [here](https://www.udemy.com/the-complete-elixir-and-phoenix-bootcamp-and-tutorial/). I highly recommend this course!
