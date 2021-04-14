# test.txt
test

# Sub in your name
git config --global user.name "sknapp211"

# Replace username w your wwu username
git config --global user.email knapps4@wwu.edu

git clone https://github.com/hutchteaching/202120_csci301_sknapp211 ~/301repo

cd ~301repo
mkdir lab1

cd lab1
touch lab1.rkt
touch writeup.txt
git add lab1.rkt writeup.txt # run "git help add" for details

git commit -m "Added empty writeup and empty lab1 submission"

git push #

git commit -m "Added part 1 (names) to writeup"
