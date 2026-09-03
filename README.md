# v4 — 120px card, fits the cell's actual content-box width

The real constraint was worse than v3's fix: table `<td>` border-box is 154px, but 13px padding on each side (unremovable, CSS overrides `cellpadding`) leaves only ~128px of actual content width — that's what `max-width:100%` clamps against. v3's 136px card still exceeded that. Shrunk to 120px (2×60px action buttons) for real margin under 128px.

<table align="center">
<tr>
<td align="center">

<a href="https://play.google.com/store/apps/details?id=tv.twitch.android.app"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact4/twitch-header.svg" alt="Twitch"></a><br><a href="https://github.com/RookieEnough/De-Vanced"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact4/twitch-repo.svg" alt="repo"></a><br><a href="https://github.com/Chiehx0220/Morphify/releases?q=Twitch&expanded=true"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact4/twitch-download.svg" alt="Download"></a><a href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/tv.twitch.android.app"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact4/twitch-obtainium.svg" alt="Obtainium"></a>

</td>
<td align="center">

<a href="https://play.google.com/store/apps/details?id=com.google.android.youtube"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact4/youtube-header.svg" alt="YouTube"></a><br><a href="https://github.com/MorpheApp/morphe-patches"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact4/youtube-repo.svg" alt="repo"></a><br><a href="https://github.com/Chiehx0220/Morphify/releases?q=YouTube&expanded=true"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact4/youtube-download.svg" alt="Download"></a><a href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/app.morphe.android.youtube"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact4/youtube-obtainium.svg" alt="Obtainium"></a>

</td>
</tr>
</table>
