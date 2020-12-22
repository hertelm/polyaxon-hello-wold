# polyaxon hello world

1. Get the example files.<br>
    `git clone https://github.com/hertelm/polyaxon-hello-wold.git .`
1. Install the polyaxon CLI.<br>
    `pip3 install polyaxon-cli`
1. Add the polyaxon executable to `$PATH`.<br>
    `export PATH=$PATH:~/.local/bin`
1. Configure the CLI.<br>
    `polyaxon config set --host=perses.informatik.privat --port=31811`
1. Log in.<br>
    `polyaxon login --username=<USERNAME>`
1. Create the project.<br>
    `polyaxon project create --name=<my-project>`
1. Initialize the project.<br>
    `polyaxon init <my-project>`
1. Upload and run the job:
    `polyaxon run -u`
1. Access http://perses.informatik.privat:31811.
   You should see the project in your Dashboard.
   Click on the project and go to the tab *experiments* to see the status and result of the job.