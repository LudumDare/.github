Ludum Dare is an online event where we challenge you to create a game from scratch in a weekend. We've been around since 2002.

If you're a user, you can find our support page here: https://ludumdare.com/support

If you're looking to help-out by reporting a bug or contributing a change or fix, then you've come to the right place! :smile:


## The Ludum Dare websites
Ludum Dare runs on two websites:

* [ludumdare.com](https://ludumdare.com) - the information website (Rules, FAQ, etc)
* [ldjam.com](https://ldjam.com) - the event website (theme selection, user blogs, submissions, and voting)

The event and the servers are run by [Mike](https://github.com/mikekasprzak) and the [Interactive Snacks](https://github.com/InteractiveSnacks) team.

The sources for information website (`ludumdare.com`) can be found here in the [/ludumdare.com](https://github.com/LudumDare/ludumdare.com) repository. It's a static website powered by [Zola](https://www.getzola.org/), built using [Tera](https://tera.netlify.app/) templates (very similar to other tech, but Mike is a Rust fan). If you'd like to contribute to the FAQ, fix a typo in the rules, that's where'd you go.

The sources for the event website (`ldjam.com`) have been spun-off into its own project called [**Jammer Core**](https://github.com/JammerCore). If you're familiar with the old `ludumdare/ludumdare` source code, or its toolchain DairyBox, you can find both over there. It's built on a PHP backend and a JavaScript frontend. We're committed to supporting what's there, but I'd like us to explore switching from JavaScript to TypeScript, and rewriting some of the PHP in Rust. 🦀

For the archivists, you can find [sources](https://github.com/LudumDare/ludumdare-2008/) for the WordPress website we ran in the 2000's until mid 2010. It's unsupported, but you can view the old website [here](http://ludumdare.com/compo).

_- Mike Kasprzak, the Ludum Dare guy_
