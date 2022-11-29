# What is this?

This is a script for scraping letterboxd, a social movie ranking website, and then getting magnet links for them to download them with a bittorrent client.

Why?

Because I wanted to.

# How to run?

Use these following commands:

    git clone https://github.com/amogusussy/lbd
    cd lbd
    chmod +x lbd
    sudo cp lbd /usr/bin/lbd
    pip install -r requirements.txt


Now you should be able to run the command!

To run it, use the following format:

    lbd https://letterboxd.com/example/list/this-is-an-example


# Other

By default, this uses qbittorrent. To change this, edit the file and change the `APPLICATION` variable to whatever application you want. If you're on windows, make sure to add the `.exe` to the end of it.

The default quality is `1080p`, if you want to change this, change the `QUALITY` variable to whatever waulity you want.

Thanks to the people who develop [librex](https://github.com/hnhx/librex), the API I use for getting the magnet links.

Everything here is licensed under the WTFPL license, so feel free to do WHATEVER THE FUCK YOU LIKE with it :)
