EVEShip.fit is an online tool available on [https://eveship.fit](https://eveship.fit).
It allows you to view fits (via EFT or import one from in-game), create new fits, and share links to fits with others.

EVEShip.fit is designed with the following goals:
- Load quickly (< 500ms after first load), so it feels like a breeze to work with the tool.
- Mimic in-game where possible, to give an uniform look&feel.
- Make it easy to find better variants or to explore other designs.
- Keep data local in the browser (as in, do not send data to a server for processing).

Additionally, make it easy for others to reuse parts of this project, to embed it on their own website.

For more detailed look how these goals are accomplished, check out the individual repositories:

- [dogma-engine](https://github.com/EVEShipFit/dogma-engine) - Library to calculate statistics for EVE Online ship fits, written in Rust.
- [react](https://github.com/EVEShipFit/react) - React component library to quickly and easily show EVE Online ship fits in your own application.
- [eveship.fit](https://github.com/EVEShipFit/eveship.fit) - Public frontend for EVEShip.fit (hosted on [https://eveship.fit](https://eveship.fit)).

And lastly, there is a [roadmap](https://github.com/orgs/EVEShipFit/projects/1) to show you what is being worked on.
