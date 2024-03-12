周处除三害HD百度视频在线观看-电影完整版-樱花动漫

資料來源: https://www.mayadc.com/dianying/zhouchuchusanhai/

<p>
	<video id="player" width="320" height="240" controls="" style="background:black;" src="https://github.com/jash-git/Html5-Video-Playlist/blob/master/code/videos/ts2mp4/01.mp4?raw=true">
	</video>
	
	<br>
	
	<script>
			var player = document.getElementById('player')
			var string1="https://github.com/jash-git/Html5-Video-Playlist/blob/master/code/videos/ts2mp4/"
			var string2="?raw=true"
			var playlist = [
			  "01.mp4",
			  "02.mp4",
			  "03.mp4",
			  "04.mp4",
			  "05.mp4",
			  "06.mp4",
			  "07.mp4",
			  "08.mp4",
			  "09.mp4",
			  "10.mp4",
			  "11.mp4",
			  "12.mp4",
			  "13.mp4",
			  "14.mp4",	  
			]
			var activeVideo = 0
			var fileurl = string1 + playlist[activeVideo]+ string2
			player.src = fileurl
			player.addEventListener('ended', function(e) {
			  // update the new active video index
			  activeVideo = (++activeVideo) % playlist.length
			  var string1="https://github.com/jash-git/Html5-Video-Playlist/blob/master/code/videos/ts2mp4/"
			  var string2="?raw=true"
			  var fileurl = string1 + playlist[activeVideo]+ string2
			  player.src = fileurl
			  player.play()
			})
	</script>
	
	<br>
	
</p>