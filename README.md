# apex-audio-player
Audio Player Template Component Plug-in for Oracle APEX based on the media-chrome web component.

<img alt="Screen recording showing audio player plug-in" src="https://github.com/LouisMoreaux/apex-audio-player/blob/main/assets/apex-audio-player.gif?raw=true" ></img>

## Installation
Import the file located at plug-in/template_component_plugin_apex_lmoreaux_audio_player.sql

## configuration
### Region attributes
<table>
<tr>
<td> Attribute </td> <td> Description </td>
</tr>
<tr>
<td> Audio Source </td>
<td> Audio source file </td>
</tr>
<tr>
<td> Color </td>
<td> Choose the color.<br>Based on the Universal Theme colors, more info <a href="https://apex.oracle.com/pls/apex/r/apex_pm/ut/color-and-status-modifiers">here</a>. </td>
</tr>
<tr>
<td> Display Time? </td>
<td> Display the time (Y/N) </td>
</tr>
<tr>
<td> Show Duration? </td>
<td> Show the duration (Y/N) </td>
</tr>
<tr>
<td> Show Remaining? </td>
<td> Show the remaining time (Y/N) </td>
</tr>
<tr>
<td> No Toggle Current Time/Remaining? </td>
<td> Disable click or tap behavior that toggles between remaining and current time. </td>
</tr>
<tr>
<td> Seek Backward Button? </td>
<td> Display a button to allow seeking back a configurable amount of time (Y/N) </td>
</tr>
<tr>
<td> Seek Backward Offset </td>
<td> Adjusts how much time (in seconds) the playhead should seek backward. </td>
</tr>
<tr>
<td> Seek Forward Button? </td>
<td> Display a button to allow seeking forward a configurable amount of time (Y/N) </td>
</tr>
<tr>
<td> Seek Forward Offset </td>
<td> Adjusts how much time (in seconds) the playhead should seek forward. </td>
</tr>
<tr>
<td> Display Rates? </td>
<td> Display a button to change the playback speed of your media (Y/N) </td>
</tr>
<tr>
<td> Custom Playback Rates </td>
<td> Set custom playback rates for the user to choose from (ex: 0.25 0.5 0.75 1.5 1 2) </td>
</tr>
<tr>
<td> Mute Button? </td>
<td> Display a mute button (Y/N) </td>
</tr>
<tr>
<td> Volume Range? </td>
<td> Display a volume range (Y/N) </td>
</tr>
</table>

## Demo
A live demo can be found at [https://apex.oracle.com/pls/apex/r/louis/template-component/audio-player](https://apex.oracle.com/pls/apex/r/louis/template-component/audio-player)

## Credit
Based on the open source web component [media-chrome](https://github.com/muxinc/media-chrome)