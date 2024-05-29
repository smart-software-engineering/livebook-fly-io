# Deploy Livebook on Fly

Use the fly.toml in this repo, then execute:

1. `fly launch --no-deploy`
2. `fly secrets set LIVEBOOK_PASSWORD=????`
3. `fly deploy --volume-initial-size 2` 
4. `fly apps open`

You can configure most parts during launch.
The initial size can also be less, depending on what
you plan to do with the livebook.

It will autostart and autostop, saving you money ;)
