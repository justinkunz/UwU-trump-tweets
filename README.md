# Trump UwU Auto Tweeter

This app creates a Twitter stream of @realdonaldtrump's tweets, converts it to a cringey UwU format, then reposts the owo version. Heavily influenced by the [trump_owo twitter](https://twitter.com/trump_owo?lang=en).

Currently deployed through an heroku worker

### Example

###### Input

```
So pathetic to watch the Fake News Lamestream Media playing down the gravity and depravity of the Radical Left, looters and thugs, ripping up our Liberal Democrat run (only) cities. It is almost like they are all working together?
```

###### Output

```
*nuzzles* So pathetic to watch the Fake News Wamestweam Media pwaying down the gwavity and depwavity of the Wadicaw Weft, wootews and thugs, wipping up ouw Wibewaw Democwat wun (onwy) cities >.< It is awmost wike they awe aww wowking togethew?
```

### Local Set Up

To run this app locally you will need to have node installed.

1. Run the following commands:

```
git clone https://github.com/justinkunz/UwU-trump-tweets
cd UwU-trump-tweets
npm i
cp .env.example .env
```

2. Edit the [`config.json`](./config.json) file to change the target of the tweets. You can find a Twitter user Id [here](https://tweeterid.com/)

3. Set up a Twitter Developer account [here](https://developer.twitter.com/en/apps) and create a new app.

4. Generate your Twitter Access Key & secret and add it, along with your consumer key & secret to the `.env` file that was created.

5. Run `node .` to start the worker.
