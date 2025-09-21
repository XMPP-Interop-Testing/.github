These are repositories that relate to the [XMPP Interop Testing project](https://xmpp-interop-testing.github.io/). Amongst these is [a repository](https://github.com/XMPP-Interop-Testing/smack-sint-server-extensions) that contains Server-centric integration tests using Smack's Integration Test Framework, [another repository](https://github.com/XMPP-Interop-Testing/xmpp-interop-testing.github.io) that contains the public website and various repositories that contain integration with various continuous integration systems that are supported by the framework.

# XMPP Interop Testing project

One of XMPP’s largest challenges (and indeed of all open standards) is interoperability. We want to enable anyone to use the standards on any platform they like, written in the programming language they prefer, focussing design and utility toward any group, from enterprise to egg-cup enthusiasts.

When we came up with our idea for XMPP interop tests for server implementations, we knew we weren’t the first folk to ever have the idea. What was important for us wasn’t about getting the tests right, but about getting the tests used. With so many programming languages in play, we can’t get almost everyone to adopt an additional language into their toolchain. That’s a clear no-go.

Instead, we’re choosing to wrap our tests in the packaging of the common CI systems (a GitHub Action, a Circle CI Orb, etc) so that whatever your regular toolchain, you can slot the tests into the test phase of your build pipeline.

More information, as well as usage instructions, can be found on https://xmpp-interop-testing.github.io
