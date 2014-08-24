# hubot-yourface

Your face is a hubot script. It replies with "your face"isms.

See [`src/yourface.coffee`](src/yourface.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-yourface --save`

Then add **hubot-yourface** to your `external-scripts.json`:

```json
["hubot-yourface"]
```

## Sample Interaction

<pre>
user1>> Well gosh this hubot-script is terrible
hubot>> user1: Your face is terrible.
</pre>

<pre>
user1>> Yeah, I've had to make a lot of changes. It was pretty sketchy
user2>> hubot: How is user1's face?
hubot>> user1: Your face was pretty sketchy.
</pre>

## TODO

The "how is" command conflicts with a hubot default script. I'll need to come up with something better someday.
