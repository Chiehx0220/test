# v3 — fixed: 136px card, fits the table cell's real content width

v2 broke because GitHub's mobile table `<td>` has 13px padding each side (can't be removed — CSS overrides the `cellpadding` attribute), so the real usable width per cell is ~154px, not 160px. Two side-by-side elements summing to 160px silently wrapped to separate lines. Shrunk the whole card to 136px (2×68px action buttons = 136px, safely under 154px) so nothing wraps.

<table align="center">
<tr>
<td align="center">

<a href="https://play.google.com/store/apps/details?id=tv.twitch.android.app"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact3/twitch-header.svg" alt="Twitch"></a><br><a href="https://github.com/RookieEnough/De-Vanced"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact3/twitch-repo.svg" alt="repo"></a><br><a href="https://github.com/Chiehx0220/Morphify/releases?q=Twitch&expanded=true"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact3/twitch-download.svg" alt="Download"></a><a href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/tv.twitch.android.app"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact3/twitch-obtainium.svg" alt="Obtainium"></a>

</td>
<td align="center">

<a href="https://play.google.com/store/apps/details?id=com.google.android.youtube"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact3/youtube-header.svg" alt="YouTube"></a><br><a href="https://github.com/MorpheApp/morphe-patches"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact3/youtube-repo.svg" alt="repo"></a><br><a href="https://github.com/Chiehx0220/Morphify/releases?q=YouTube&expanded=true"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact3/youtube-download.svg" alt="Download"></a><a href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/app.morphe.android.youtube"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact3/youtube-obtainium.svg" alt="Obtainium"></a>

</td>
</tr>
</table>
