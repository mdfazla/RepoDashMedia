# RepoDashMedia
Start MP4Box where the media file is located.
Then two make .mpd file with video and audio run the following command.
Merge two mpd file into one. Form audio take the <AdaptationSet> </AdaptationSet> portion and paste into video mpd file below the AdaptationSet of video.

<br/> For Video: MP4Box -dash 20000  -dash-profile on-demand -segment-name video_ winter_journey.mp4#video
<br/> For Audio: MP4Box -dash 20000  -dash-profile on-demand -segment-name video_ winter_journey.mp4#audio
