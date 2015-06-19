# Rocker.Chat

[Roket.Chat](https://github.com/RocketChat/Rocket.Chat) app for IndieHosters.

## How to run this

Modify `docker-compose.yml` `ROOT_URL` value to match your URL.

And then:

```bash
./RUN
```

And all the data will be located under the `./data` folder.

## How to Backup this

Just run:

```bash
./BACKUP
```

This will create a dump of the mongo database. Then just copy the data folder to a safe location and you should be fine!

## Question?

If you have any questions, don't hesitate to open issues.
