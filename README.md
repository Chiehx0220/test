# gap test: `<br>` vs `<div>` stacking (same SVGs as v9)

Measuring the vertical gap between header/repo/actions. Left = current `<br>`-joined approach. Right = each piece wrapped in its own `<div>`, no `<br>`.

<table align="center">
<tr>
<td align="center">

**br (current)**

<a href="https://play.google.com/store/apps/details?id=tv.twitch.android.app"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact11/twitch-header.svg" alt="Twitch"></a><br><a href="https://github.com/RookieEnough/De-Vanced"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact11/twitch-repo.svg" alt="repo"></a><br><a href="https://github.com/Chiehx0220/Morphify/releases?q=Twitch&expanded=true"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact11/twitch-download.svg" alt="Download"></a><a href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/tv.twitch.android.app"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact11/twitch-obtainium.svg" alt="Obtainium"></a>

</td>
<td align="center">

**div-wrapped**

<div><a href="https://play.google.com/store/apps/details?id=tv.twitch.android.app"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact11/twitch-header.svg" alt="Twitch"></a></div><div><a href="https://github.com/RookieEnough/De-Vanced"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact11/twitch-repo.svg" alt="repo"></a></div><div><a href="https://github.com/Chiehx0220/Morphify/releases?q=Twitch&expanded=true"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact11/twitch-download.svg" alt="Download"></a><a href="https://apps.obtainium.imranr.dev/redirect?r=obtainium://app/tv.twitch.android.app"><img align="bottom" src="https://raw.githubusercontent.com/Chiehx0220/test/main/compact11/twitch-obtainium.svg" alt="Obtainium"></a></div>

</td>
</tr>
</table>
