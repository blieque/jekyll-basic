# Jekyll Basic (Structure)

After having created a number of [Jekyll](https://jekyllrb.org/)-powered websites in the last few weeks, I noticed I was performing a lot of the same steps over and over. I decided to create a very simple file structure that I could copy to my working directory to get a new Jekyll instance going a bit hastier.

## Usage

Clone this repository:

    git clone https://github.com/blieque/jekyll-basic.git

Rename the newly-created directory to the name of your jekyll site:

    mv jekyll-basic my-dog-blog

Enter the directory and remove the Git cruft:

    cd my-dog-blog
    rm -r .git README.md LICENSE.md

Even if you'll be using an MIT license for your website, don't forget to open the license and change the name at the beginning.

After adding some of your own content, you'll probably want to start tracking with Git again:

    git init
    git commit -m "The Dog Blog begins!"

Lovely jubbly!
