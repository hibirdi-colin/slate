# Bird.i API docs

# How to use

## Editing
Edit the Markdown file in `source/index.html.md`.

## Building and bundling

Run:
```bash
bundle exec middleman build --clean
```
This will generate a build directory.

Note: you will need bundle and middleman installed.

## Deploying

Go to AWS S3 and choose the docs.hibirdi.com bucket.
Upload all  the contents of the `build/` directory created during the bundling step.


# Forked from
This is forked from https://github.com/lord/slate. Go there for full documentation.
