heroku login --interactive

heroku create mask-xxx

heroku git:remote -a mask-xxx

git config --global user.email ${your_mail}

git config --global user.name ${your_name}

heroku config:set LINE_BOT_CHANNEL_SECRET=${チャネルシークレット}

heroku config:set LINE_BOT_CHANNEL_ACCESS_TOKEN=${アクセストークン}

heroku config

git push heroku main
