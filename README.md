#DataSift Crazy Cart Leaderboard

A simple Jekyll build to generate the leaderboard.

##Adding a new time entry

Open up `_data/times.yml` and add a new entry in the following format:

    - name: Your name
      time: '00:00:00'

The `time` value *must* be wrapped in single quotes to avoid weirdness. If you have a video of your winning run, you can add in an optional `video` value:

    - name: Your name
      time: '00:00:00'
      video: 'https://www.youtube.com/watch?v=uC8_kW7P0BE'

As with the `time` value, the `video` value must be wrapped in single quotes.

GLHF.