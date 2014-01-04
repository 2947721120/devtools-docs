# The Chrome DevTools documentation

This is the official [DevTools documentation](developers.google.com/chrome-developer-tools/). 

## Contributing

We regularly update the docs and welcome any contributions or bug-fixes.

Before submitting a pull request, please open a [new issue](https://github.com/GoogleChrome/devtools-docs/issues/new) to let us know you're working on. 

This will allow us to provide feedback and coordinate contribution efforts.

### Orientation

<dl>
  <dt> ./docs </dt>
  <dd> Contains all the working files. </dd>

  <dt> ./index.html </dt>
  <dd> Contains the project <a href="https://developers.google.com/chrome-developer-tools/">overview</a> page. </dd>

  <dt> ./images </dt>
  <dd> Contains images for index.html. </dd>

  <dt> ./_book.yaml </dt>
  <dd> Contains the titles and paths of individual docs. </dd>

  <dt> ./_redirect.yaml </dt>
  <dd> Contains redirects from one location to another. </dd>

</dl>


### Running the site

1. In the root of the project, start a [server] (https://github.com/paulirish/dotfiles/blob/3fa2e7dc1f1ea5eaf7f6a2531b937ff8bd8833f9/.functions#L25-L32).
  * It's easier if your server can also do a directory listing.
1. Open [http://localhost:8000/docs/_preview.html](http://localhost:8000/docs/_preview.html)
1. You will see the boilerplate along with a directory listing
![image](https://f.cloud.github.com/assets/39191/700223/d42cb838-dd3d-11e2-8bf3-af57e883cd80.png)
1. Click one of them.
1. It should bring you to a url like [http://localhost:8000/docs/_preview.html?settings.html](http://localhost:8000/docs/_preview.html?settings.html)
  * you can navigate to this directly if you like
  * it looks like this ![image](https://f.cloud.github.com/assets/39191/700211/6b936d08-dd3d-11e2-8d4b-19db48d65c56.png)
* Things mostly work.

### Deployment

Paul or Addy does the work of pushing this stuff live.
