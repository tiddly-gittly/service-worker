# Wikitext plugin template for TiddlyWiki5

## Usage

See [documentation site](https://tiddly-gittly.github.io/service-worker/) for usage.

If you are using [Tiddlywiki-NodeJS-Github-Template](https://github.com/tiddly-gittly/Tiddlywiki-NodeJS-Github-Template), then you can skip the setup, they are included in the edition.

## Development

See [tiddly-gittly/Tiddlywiki-WikiText-Plugin-Template](https://github.com/tiddly-gittly/Tiddlywiki-WikiText-Plugin-Template) for detail.

There are some scripts you can run to boost your development.

After `npm i`:

- `npm run dev` to auto pack the plugin and run a demo site. Your change in the src directory will automatically refresh the site.
- `npm run dev-html` to see demo site with packed plugin after you finish your development, this can be your final check, this runs slower than `npm run dev`

### After the plugin is complete

#### Publish

Enable github action in your repo (in your github repo - setting - action - general) if it is not allowed, and when you tagging a new version `vx.x.x` in a git commit and push, it will automatically publish to the github release.

#### Demo

You will get a Github Pages demo site automatically after publish. If it is 404, you may need to manually enable Github Pages in your github repo:

Settings - Pages (on left side) - Build and deployment- Source - choose `"Github Actions"`

Next time you trigger a publish, the site will be updated. You can see the site link in Settings - Pages
