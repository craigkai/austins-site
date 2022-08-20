
## Install "gem" to run static site locally:

    brew install ruby

## Run this to add the command to terminal

  echo 'export PATH=/usr/local/Cellar/ruby/2.4.1_1/bin:$PATH' >> ~/.zprofile

## Install jekyll

    gem install bundler jekyll

## Move to your website folder

  cd austin-coneys

## Run dev server

  bundle exec jekyll serve

## => Now browse to http://localhost:4000

## Jekyll generates our static website from out content

    https://jekyllrb.com/

## For styling we are using:

    https://daisyui.com/docs/install/

## For our frontend we are using JavaScript and Sveltejs

    https://svelte.dev/

## Running our frontend server

    cd svelte-components
    npm i daisyui
    npm run dev

