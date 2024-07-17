Received a warning that \Users\rff\local\bin was not on my PATH. A ton of stuff is stored there!

added it to the \Users\rff\.zshrc file, and added it to my local terminal:


echo $PATH

export PATH=\Users\rff\local\bin:$PATH
