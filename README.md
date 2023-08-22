# Github recomendation system 

Important note: This repo has been archived. The [reasons.](https://github.com/jaimevalero/github-recommendation-engine/pull/179#issuecomment-1688749564) here.

## Demo site https://github-recommendation.herokuapp.com/char/index.html?busqueda=borja


![Demo site](https://github.com/jaimevalero/github-recommendation-engine/blob/master/views/img/webscreen_capture.gif)




  



Get famous repos that are similar to yours.
This system parses an user repos, label, names descriptipn, and it displays those repos that have resemblance with it.

The idea here is to find and learn new technologies, that are similar to the ones you already master, making a smooth learning curve.

Internally, it uses an euclidean distance matrix, calculated for 800 labels, where each label is a binary [0,1] dimension, to find similar repos.

TODO: Use a filter based recomendation system, with like/dislike buttons.

Links:


Info: [How the suggestions are calculated.]( https://www.kaggle.com/jaimevalero/github-reccomendation-engine)

Kudos: [Repo list info.](https://www.kaggle.com/chasewillden/topstarredopensourceprojects)

Kudos [Netflix like UI.](http://eng.wealthfront.com/2015/06/implementing-netflix-redesign.html)


   [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


