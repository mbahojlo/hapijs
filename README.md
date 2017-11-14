npm i -g npm-check-updates
npm-check-updates -u
npm install

to check
httpsstackoverflow.comquestions42493960error-starting-node-koa-application-on-heroku-related-to-webpack-and-babel-loade
httpsstackoverflow.comquestions41973338hosting-a-production-react-app-built-with-wepback-on-heroku42237745#42237745
httpsgithub.comHalahRaadSalihdeploy-to-heroku-with-db

heroku configunset NODEMODULESCACHE
heroku configset NODEMODULESCACHE=false
heroku logs --tail
heroku local web
heroku addonscreate papertrail
