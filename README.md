# mana93.github.io
Note: Anything that starts with "//" is not part of the terminal command but just a comment for explanation purposes. Ignore it.
cd Documents // navigates from home to "Documents" folder
mkdir portfolios // creates "portfolios" folder inside Documents
cd portfolios // navigates inside the created folder "portfolios"
// Bonus: To run all the above commands at once it would be
cd Documents && mkdir portfolios && cd portfolios
// Or even more advanced (I won't recommend for beginners)
mkdir -p Documents/portfolios && cd Documents/portfolios
Assuming my remote repo is the one I created in step 1
git clone https://github.com/brianmwevi/brianmwevi.github.io.git
In your case, the above command would look like this:
git clone https://github.com/yourusername/yourusername.github.io.git
Note: By "yourusername" I mean your github username (as in step 1)
