# livebook-announcement

This repo reproduces the Livebook code
presented in the initial Elixir Livebook
presentation by Jose' Valim:

https://www.youtube.com/watch?v=RKvqc-UEe34

There are a couple of minor modifications (checking for a 200 status code
when downloading the training data and ensuring the number of labels
matches the number of images).

The video running order is as follows:

* ??? - Intro
* ??? - Training a neural network to do handwriting recognition
* 20:28 - Running Tests in a Livebook

# Dependencies

* Elixir >= 1.12
* Erlang >= 24

# Use

```sh
livebook server
```

Open browser with indicted URL.

Select and open notebook.livemd.

The results of the final code block are the predictions for
the various images in the training data:

```
[5, 0, 4, 1, 9, 2, ...]
```
