# oysttyer

The official fork and replacement for what was once [Floodgap's TTYtter](http://www.floodgap.com/software/ttytter/).

In order to get Cameron Kaiser's blessing, we've had to change the name, take out a new API key and keep the Floodgap Free Software License.

The master branch will be pretty much what I'm running, but that doesn't mean I've not managed to break it in someway. The mirror branch reflects all the historical official TTYtter updates.

## Switching from TTYtter

1. You have to re-authorise (you can't use your `.ttytterkey`) as we have a new API key
2. Move/rename your `.ttytterc` file to `.oysttyerrc`
3. If you use the `ttytteristas` pref it is now called `oysttyeristas`
4. Read the Changelog to see what's new since TTYtter 2.1

I think that's it?

#### Notes to extension developers

1. The `TTYtter_VERSION`, `TTYtter_PATCH_VERSION` and `TTYtter_RC_NUMBER` variables are now `oysttyer_VERSION`, `oysttyer_PATCH_VERSION` and `oysttyer_RC_NUMBER`.
2. User-agent string has changed to `oysttyer/$oysttyer_VERSION`.

## Recommendations

I strongly suggest, although it is by no means compulsory, tracking @oysttyer and #oysttyer as that way you become connected to a global support network.

Also, check out some available extensions:

* [oysttyer-profile](https://github.com/oysttyer/oysttyer-profile) shows more profile information about users
* [oysttyer-deshortify](https://github.com/oysttyer/oysttyer-deshortify) gets rid of shortlinks and displays final URLs
* [oysttyer-multigeo](https://github.com/oysttyer/oysttyer-multigeo) for all your geographical location needs

