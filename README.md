# sensorgnome-website

Files for the [Hugo](https://gohugo.io/) based sensorgnome website.

## Testing

In order to make sure changes render properly before commiting, Hugo can be run locally to test changes.

- Install Hugo.
- Clone this repo.
- Install the needed theme: `git submodule add https://github.com/zwbetz-gh/vanilla-bootstrap-hugo-theme.git themes/vanilla-bootstrap-hugo-theme`
- Run with Hugo's testing server. Example command: `hugo server -D --bind=0.0.0.0 --baseURL=localhost:1313 --port=1313`.
- Open browser to `localhost:1313`.

To access it on a remote system, edit the baseURL to include the server's hostname or FQDN so that all files are served correctly.
