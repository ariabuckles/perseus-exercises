# Perseus Exercises

English language exercises from Khan Academy

exercises.json contains the data about how questions are grouped into a
practice exercise.

questions.json contains the questionIds referenced by exercises.json and the
questionData for perseus.

To view the data in these files, I recommend using [`jq`](https://stedolan.github.io/jq/):

```sh
cat exercises.json | jq '.[0]'  # shows the first exercise
cat question.json | jq '.[0]'   # shows the first question
```

## License

Khan Academy exercises, and this repository, are licensed under [`CC BY-NC-SA 3.0`](https://creativecommons.org/licenses/by-nc-sa/3.0/)

More information is available at:
https://support.khanacademy.org/hc/en-us/articles/202262954-Can-I-use-Khan-Academy-s-videos-name-materials-link-on-my-site-
