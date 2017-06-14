
<html>
<head>
<meta charset="utf-8" />
<!-- Website Design By: www.happyworm.com -->
<title>The Eye of God</title>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<link href="/dist/skin/blue.monday/css/jplayer.blue.monday.min.css" rel="stylesheet" type="text/css" />
<script type="text/javascript" src="/lib/jquery.min.js"></script>
<script type="text/javascript" src="/dist/jplayer/jquery.jplayer.min.js"></script>
<script type="text/javascript" src="/dist/add-on/jplayer.playlist.min.js"></script>
<script type="text/javascript">
//<![CDATA[
$(document).ready(function(){

	var myPlaylist = new jPlayerPlaylist({
		jPlayer: "#jquery_jplayer_N",
		cssSelectorAncestor: "#jp_container_N"
	}, [
		{
		   title:"El Ojo de Dios - the eye of god",
				artist:"Quetzal Eckhart",
				mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/whistles.mp3",
				poster: "http://data.elmisterio.org/assets/images/ojodedios.jpg"
		}
	], {
		playlistOptions: {
			enableRemoveControls: true
		},
		swfPath: "/dist/jplayer",
		supplied: "webmv, ogv, m4v, oga, mp3",
		useStateClassSkin: true,
		autoBlur: false,
		smoothPlayBar: true,
		keyEnabled: true,
		audioFullScreen: true
	});

	// Click handlers for jPlayerPlaylist method demo

	// Audio mix playlist

	$("#playlist-setPlaylist-audio-mix").click(function() {
		myPlaylist.setPlaylist([
			{
			title:"Pictures At An Exhibition - Mussorgsky",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/pictures-at-an-exhibition.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{				
				title:"Adagio",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/adagio.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
					title:"Andalouse",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/andalouse.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
					title:"Meditation",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/meditation.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
				title:"Dvorak",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/dvorak.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
                title:"Whistles",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/whistles.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
                title:"John Dowland Songs",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/dowland.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
                title:"Nocturne - Chopin",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/nocturne.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
                title:"Anandamurti Melodies",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/anandamurti.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
                title:"William Enckhausen plays Heinrich Enckhausen, Handel, and Telemann",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/enckhausen.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
                title:"Reverie - Debussy",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/reverie.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
                title:"Dance Of The Blessed Spirits",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/blessed-spirits.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
                title:"Los Doraditos",
			artist:"Quetzal Eckhart",
			mp3:"http://data.elmisterio.org/music/Contemplations-On-A-Quena/los-doraditos.mp3",
			poster: "http://elmisterio.org/assets/images/cross-quena.jpg"                                                                                     
			}
		]);
	});

	// Video mix playlist

	$("#playlist-setPlaylist-video-mix").click(function() {
		myPlaylist.setPlaylist([
			{
			    title:"Govinda",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/govinda.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
            {
			    title:"Topilejo",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/topilejo.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
			{
				title:"Padmasambhava",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/padmasambhava.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
			{
				title:"Baba Nam Kevalam",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/babanamkevalam.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
			{
				title:"Soja",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/soja.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
			{
				title:"Om Ah Hum Vajra Guru",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/om-ah-hum-vajra-guru.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
			{
				title:"Nikte Ha Kiirtan",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/nikteha.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
			{
				title:"Reverie Kiirtan",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/reverie-kiirtan.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
			{
				title:"Desierto",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/desierto2.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
			{
				title:"Tiny Green Island",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/tiny-green-island.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
			{
				title:"La Gracia",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/gracia.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			},
			{
				title:"Los Doraditos",
				artist:"El Misterio",
				mp3:"http://data.elmisterio.org/music/Kiirtan-El-Misterio/los-doraditos.mp3",
				poster: "http://elmisterio.org/assets/images/kiirtan.jpg"
			}
		]);
	});

	// Media mix playlist

	$("#playlist-setPlaylist-media-mix").click(function() {
		myPlaylist.setPlaylist([
			{
				title:"Gavotte And Minuet",
				artist:"Quetzal Eckhart",
				mp3:"http://data.elmisterio.org/music/Bach-On-Bamboo/gavotte-minuet.mp3",
				poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
				title:"Air and Gavotte",
				artist:"Quetzal Eckhart",
				mp3:"http://data.elmisterio.org/music/Bach-On-Bamboo/air-gavotte.mp3",
				poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
				title:"Christmas Oratorio",
				artist:"Quetzal Eckhart",
				mp3:"http://data.elmisterio.org/music/Bach-On-Bamboo/christmas-oratorio.mp3",
				poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
				title:"Sonata in B-minor",
				artist:"Quetzal Eckhart",
				mp3:"http://data.elmisterio.org/music/Bach-On-Bamboo/sonata-b-minor.mp3",
				poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			},
			{
				title:"Minuet, Air, and Bouree",
				artist:"Quetzal Eckhart",
				mp3:"http://data.elmisterio.org/music/Bach-On-Bamboo/minuet-air-bouree.mp3",
				poster: "http://elmisterio.org/assets/images/cross-quena.jpg"
			}
		]);
	});

	


	// The remove commands

	$("#playlist-remove").click(function() {
		myPlaylist.remove();
	});

	$("#playlist-remove--2").click(function() {
		myPlaylist.remove(-2);
	});
	$("#playlist-remove--1").click(function() {
		myPlaylist.remove(-1);
	});
	$("#playlist-remove-0").click(function() {
		myPlaylist.remove(0);
	});
	$("#playlist-remove-1").click(function() {
		myPlaylist.remove(1);
	});
	$("#playlist-remove-2").click(function() {
		myPlaylist.remove(2);
	});

	// The shuffle commands

	$("#playlist-shuffle").click(function() {
		myPlaylist.shuffle();
	});

	$("#playlist-shuffle-false").click(function() {
		myPlaylist.shuffle(false);
	});
	$("#playlist-shuffle-true").click(function() {
		myPlaylist.shuffle(true);
	});

	// The select commands

	$("#playlist-select--2").click(function() {
		myPlaylist.select(-2);
	});
	$("#playlist-select--1").click(function() {
		myPlaylist.select(-1);
	});
	$("#playlist-select-0").click(function() {
		myPlaylist.select(0);
	});
	$("#playlist-select-1").click(function() {
		myPlaylist.select(1);
	});
	$("#playlist-select-2").click(function() {
		myPlaylist.select(2);
	});

	// The next/previous commands

	$("#playlist-next").click(function() {
		myPlaylist.next();
	});
	$("#playlist-previous").click(function() {
		myPlaylist.previous();
	});

	// The play commands

	$("#playlist-play").click(function() {
		myPlaylist.play();
	});

	$("#playlist-play--2").click(function() {
		myPlaylist.play(-2);
	});
	$("#playlist-play--1").click(function() {
		myPlaylist.play(-1);
	});
	$("#playlist-play-0").click(function() {
		myPlaylist.play(0);
	});
	$("#playlist-play-1").click(function() {
		myPlaylist.play(1);
	});
	$("#playlist-play-2").click(function() {
		myPlaylist.play(2);
	});

	// The pause command

	$("#playlist-pause").click(function() {
		myPlaylist.pause();
	});

	// Changing the playlist options

	// Option: autoPlay

	$("#playlist-option-autoPlay-true").click(function() {
		myPlaylist.option("autoPlay", true);
	});
	$("#playlist-option-autoPlay-false").click(function() {
		myPlaylist.option("autoPlay", false);
	});

	// Option: enableRemoveControls

	$("#playlist-option-enableRemoveControls-true").click(function() {
		myPlaylist.option("enableRemoveControls", true);
	});
	$("#playlist-option-enableRemoveControls-false").click(function() {
		myPlaylist.option("enableRemoveControls", false);
	});

	// Option: displayTime

	$("#playlist-option-displayTime-0").click(function() {
		myPlaylist.option("displayTime", 0);
	});
	$("#playlist-option-displayTime-fast").click(function() {
		myPlaylist.option("displayTime", "fast");
	});
	$("#playlist-option-displayTime-slow").click(function() {
		myPlaylist.option("displayTime", "slow");
	});
	$("#playlist-option-displayTime-2000").click(function() {
		myPlaylist.option("displayTime", 2000);
	});

	// Option: addTime

	$("#playlist-option-addTime-0").click(function() {
		myPlaylist.option("addTime", 0);
	});
	$("#playlist-option-addTime-fast").click(function() {
		myPlaylist.option("addTime", "fast");
	});
	$("#playlist-option-addTime-slow").click(function() {
		myPlaylist.option("addTime", "slow");
	});
	$("#playlist-option-addTime-2000").click(function() {
		myPlaylist.option("addTime", 2000);
	});

	// Option: removeTime

	$("#playlist-option-removeTime-0").click(function() {
		myPlaylist.option("removeTime", 0);
	});
	$("#playlist-option-removeTime-fast").click(function() {
		myPlaylist.option("removeTime", "fast");
	});
	$("#playlist-option-removeTime-slow").click(function() {
		myPlaylist.option("removeTime", "slow");
	});
	$("#playlist-option-removeTime-2000").click(function() {
		myPlaylist.option("removeTime", 2000);
	});

	// Option: shuffleTime

	$("#playlist-option-shuffleTime-0").click(function() {
		myPlaylist.option("shuffleTime", 0);
	});
	$("#playlist-option-shuffleTime-fast").click(function() {
		myPlaylist.option("shuffleTime", "fast");
	});
	$("#playlist-option-shuffleTime-slow").click(function() {
		myPlaylist.option("shuffleTime", "slow");
	});
	$("#playlist-option-shuffleTime-2000").click(function() {
		myPlaylist.option("shuffleTime", 2000);
	});

	// Equivalent commands

	$("#playlist-equivalent-1-a").click(function() {
		myPlaylist.add({
			title:"Your Face",
			artist:"The Stark Palace",
			mp3:"http://www.jplayer.org/audio/mp3/TSP-05-Your_face.mp3",
			oga:"http://www.jplayer.org/audio/ogg/TSP-05-Your_face.ogg",
			poster: "http://www.jplayer.org/audio/poster/The_Stark_Palace_640x360.png"
		}, true);
	});

	$("#playlist-equivalent-1-b").click(function() {
		myPlaylist.add({
			title:"Your Face",
			artist:"The Stark Palace",
			mp3:"http://www.jplayer.org/audio/mp3/TSP-05-Your_face.mp3",
			oga:"http://www.jplayer.org/audio/ogg/TSP-05-Your_face.ogg",
			poster: "http://www.jplayer.org/audio/poster/The_Stark_Palace_640x360.png"
		});
		myPlaylist.play(-1);
	});

	// AVOID COMMANDS

	$("#playlist-avoid-1").click(function() {
		myPlaylist.remove(2); // Removes the 3rd item
		myPlaylist.remove(3); // Ignored unless removeTime=0: Where it removes the 4th item, which was originally the 5th item.
	});


});
//]]>
</script>
</head>
<body>
<p style="margin-top:1em;">
				

<div id="jp_container_N" class="jp-video jp-video-270p" role="application" aria-label="media player">
	<div class="jp-type-playlist">
		<div id="jquery_jplayer_N" class="jp-jplayer"></div>
		<div class="jp-gui">
			<div class="jp-video-play">
				<button class="jp-video-play-icon" role="button" tabindex="0">play</button>
			</div>
			<div class="jp-interface">
				<div class="jp-progress">
					<div class="jp-seek-bar">
						<div class="jp-play-bar"></div>
					</div>
				</div>
				<div class="jp-current-time" role="timer" aria-label="time">&nbsp;</div>
				<div class="jp-duration" role="timer" aria-label="duration">&nbsp;</div>
				<div class="jp-controls-holder">
					<div class="jp-controls">
						<button class="jp-previous" role="button" tabindex="0">previous</button>
						<button class="jp-play" role="button" tabindex="0">play</button>
						<button class="jp-next" role="button" tabindex="0">next</button>
						<button class="jp-stop" role="button" tabindex="0">stop</button>
					</div>
					<div class="jp-volume-controls">
						<button class="jp-mute" role="button" tabindex="0">mute</button>
						<button class="jp-volume-max" role="button" tabindex="0">max volume</button>
						<div class="jp-volume-bar">
							<div class="jp-volume-bar-value"></div>
						</div>
					</div>
					<div class="jp-toggles">
						<button class="jp-repeat" role="button" tabindex="0">repeat</button>
						<button class="jp-shuffle" role="button" tabindex="0">shuffle</button>
						<button class="jp-full-screen" role="button" tabindex="0">full screen</button>
					</div>
				</div>
				<div class="jp-details">
					<div class="jp-title" aria-label="title">&nbsp;</div>
				</div>
			</div>
		</div>
		<div class="jp-playlist">
			<ul>
				<!-- The method Playlist.displayPlaylist() uses this unordered list -->
				<li>&nbsp;</li>
			</ul>
		</div>
		<div class="jp-no-solution">
			<span>Update Required</span>
			To play the media you will need to either update your browser to a recent version or update your <a href="http://get.adobe.com/flashplayer/" target="_blank">Flash plugin</a>.
		</div>
	</div>
</div>
			
&nbsp;


&nbsp;
<code></code><br />
&nbsp;
<li><a href="http://data.elmisterio.org/music/Contemplations-On-A-Quena/whistles.mp3">Download "Amazon Whistle"</a></li>
<p>The infinite being is beyond name and form yet bestows name and form to all things. Nothing exists apart from the causal matrix, the fundamental fractal that divides its very own Self so as to create the universe by infinite self division. Creation is the division and fragmentation of the original Self, as reflected in the fractal cross, that has created the "ten-thousand things."  The fundamental cross is a spiritual concept that is clearly reflected in the <a href="http://elmisterio.org/the-pure-mind">causal mind of the Vishuddha</a> with its 16 vortexes or "vrttis"(4x4). This primordial fractal, the 4x4, further multiplies itself into the the 4x4x4. Each time the essential cross divides, it is more “causal,” potentialized and capable of controlling more of its created objects in nature.  All of the parts exist within the whole, just as miniature crosses exist on the main arms of the fundamental cross.  Nothing is essentially separate from its source.  When this fundamental fractal divides itself into the 4x4x4 we get the 64 mayan tzolkien and the 64 hexagrams of the I-ching (4x4x4), which is an even deeper causal level than the human, semi-divine expressions at the Vishuddha chakra. The deeper Macrocosmic patterns of the tzolkein and I-ching impose themselves upon the microcosmic 4x4 patterns of the Vishuddha Vortex. For this reason the Vishuddha reflects the hidden laws of the universe, yet in a human and personalized form.</p>

<p>The "eye of god" is within all created beings.  The "eye" is the developed pineal gland which yogis activate to enter into states of super-consciousness.  All beings with 2 eyes have this "divine eye" within.</p>

&nbsp;
<li><img src="http://data.elmisterio.org/assets/images/hexagrams.jpg" alt="" /></li>
&nbsp;



<li>the following text is from <a href="https://en.wikipedia.org/wiki/God's_eye">Wikipedia</a>:</li>

A “God’s eye” is a yarn weaving and a spiritual object. The Ojo de Dios (Eye of God in Spanish) is woven with yarn and wood, often with several colors. The weaving of an Ojo de Dios is an ancient contemplative and spiritual practice for many indigenous peoples in the Americas[citation needed], and beliefs surrounding them vary with location and history. Some people believe they were originally part of the religion of the Ancient Pueblo Peoples.[citation needed]
In many of the Pueblos of New Mexico (U.S.) Ojos de Dios have traditionally been created for celebration or blessing, presented as a gift or designed to bless a home.[citation needed] Often they reflect a confidence in all-seeing Providence. The spiritual eye of the Ojo de Dios is thought by some believers to have the power to see and understand things unknown to the physical eye. During Spanish colonial times in New Mexico, from the 16th to the 19th centuries, Ojos de Dios were placed where people worked, or where they walked along a trail (Mager, 2012).

Traditional Ojos de Dios are frequently woven in solitude, as part of an extended meditation or prayer. In other settings, their construction is one aspect of longstanding communal engagement and connection. For centuries, young people in the mountains of New Mexico have made Ojos de Dios in learning circles (wisdom circles) with their elders.[citation needed] In other parts of the ‘New World’ they were used as ritual objects or for rites of passage. Today, artisans weave complicated or variegated versions of the traditional Ojo de Dios, selling them as decorations or religious objects. There has also been a huge increase in the use of Ojos de Dios as an easy and fun craft for children, but with the meditative and collaborative aspects removed.
The Ojo de Dios or God’s eye is a ritual tool, magical object, and cultural symbol evoking the weaving motif and its spiritual associations for the Huichol and Tepehuan Indians of western Mexico. The God’s Eye is symbolic of the power of seeing and understanding that which is unknown and unknowable, The Mystery. The four points represent the elemental processes: earth, fire, air, and water. The Huichol call their God’s eyes Sikuli, which means “the power to see and understand things unknown.” When a child is born, the central eye is woven by the father, then one eye is added for every year of the child’s life until the child reaches the age of five. Original Tepehuan Crosses are extremely rare to come by. There are many that are being made for the tourist market, but they do not carry the same traditional and spiritual significance.

In the traditional Huichol ranchos, the nieli’ka or nierika is an important ritual artifact. Negrín states that one of the principal meanings of nierika is that of “a metaphysical vision, an aspect of a god or a collective ancestor."[1] Importantly, it is the term the Tepehuan use to refer to deities. Negrín quotes Lumholtz as stating that for the Huichol and Tepehuan “a nierika means a picture, an appearance, or a sacred representation.”[1] The term “nierika” is etymologically rooted in the verb “nieriya”, “to see”. Nierika are found in Huichol and Tepehuans’ most sacred places: house shrines (xiriki), springs, caves and temples. Some Natives of northwest Mexico and throughout the southwest U.S. had visions during peyote ceremonies. Natives have received guidance from Gods who appeared before them in many shapes, though the eyes of the God was so intense and overwhelming many Natives could only see the eye of the God. To show others the vision they had, became the God’s eye woven on sticks with handspun yarn, colored with various types of berries, flowers, and other materials that contribute to the sense of the God’s eye.
Negrín states that: “The votive nierika is generally a round offering, symbolizing an ancestor and prayer offerings sanctified by the blood of a sacrificed animal."[1] Nierika as a ritual object may be attached to votive arrows with bamboo and yarn, or wood-and-wax-embedded objects. Similarly, Lumholtz states that the nierika “evokes an ancestor, thanks it with blood offerings, and invokes its favors.” The nierika may take different forms and fabrication may differ greatly: a small round or square tablet with a hole in the center covered on one or both sides with a mixture of beeswax and pine resin into which threads of yarn are pressed; when the image is not round, it may be considered a resting mat for the ancestors, or a prayer mat or itari.

Negrín states the elaborate interwoven nierika that Lumholtz called “namma” (which is close to the pronunciation of Namkha) from which originated the detailed and now prized yarn paintings of the commercial art world, are now rarely if ever seen.[1] Namma were generally rectangular or square in shape, with yarn woven onto a grid of bamboo sticks. These God’s Eyes are also called by the Spanish term “ojo de dios”. One understanding of the ojo de dios according to Harvey is of a: “wand” (the eye) through which the eye of god will see the supplicant. Harvey states that: “The cross of the ojo de dios is that of the legendary four directions: earth, fire, water, and air.”[2]

The nierika may also be understood as a shield which we interpret as a metaphorical protective device shielding against temptations or distractions along the ritual and spiritual path. Nierika is also referred to as a mirror with two faces; often both sides are covered with yarn designs and the hole in the middle of some forms of nierika is considered a mirror or often a small glass mirror is evident. The nierika is a reciprocal magical conduit or path: the ‘eye’, ‘hole’ or ‘mirror’ is the magical portal through which humanity and deity perceive each other.

The nierika, in ritual use, is a face; of the sun, of the earth, of a deer, the wind, the peyote, and the face of the person making the offering. The nierika is also a portalling device that facilitates entry into other states of consciousness or the “spiritual world”. For the Huichol there are five directions, each of the cardinal points and the fifth, the central point or “eye” is the spiritual, source of visions, power and enlightenment.
Beginning about thirty years ago the yarn painting evolved to its high state today from the "nierika’. A small square or round tablet with a hole in the center is a nierika (nearika) or sacred magical offering. These tablets are covered on one or both sides with a mixture of beeswax and pine resin into which threads of yarn are pressed. Nierikas are found in all Huichol sacred places such as temples, springs and caves.

The first large yarn paintings were exhibited in Guadalajara in 1962, a direct outgrowth of the nierika - simple and uncomplicated. At present with the availability of a larger spectrum of commercial dyed and synthetic yarn, more finely spun yarn paintings have evolved into high quality works of art. Realism, based on mythology, is the basis of yarn paintings. Peyote cactus is much revered by the Huichol, a veritable gift from the Gods. Through the use of peyote, the Huichol create the elaborate designs used in their artwork. It symbolizes the essence, the very life, sustenance, health, accomplishment, good fortune of the Huichol. Plus through peyote’s hallucinogenic effects, enlightenment and shamanic powers can be achieved. Annual pilgrimages are taken to Wirikuta to collect the peyote. Only the ‘purified ones’ can participate in the harvest or the peyote will not be found. Peyote mandalas or neakilas (nierika) symbolize the entrance to the spiritual world. As important power objects they are often found at the center of yarn paintings. Each mandala is individual, Utilizing many of the same sacred designs and patterns as seen in yarn painting and weaving, the Huichol create anklets, bags, belts, bracelets, chokers, earrings and rings with the seed beads. “Life is a constant object of prayer for the Huichol, it is, in the conception, hanging somewhere above them, and must be reached out for,” explains Lumholtz, "thus all phases of their lives are prayer - the planting, harvesting, peyote pilgrimages - all art, weaving, bead work, face painting and yarn paintings, embody prayer within symbols. With this introduction one can better understand the Huichol, their art and their constant communication with the spiritual realm. Ramon Mara Torres sums it all up by observing, “This ancient art, modernized as a result of circumstances entirely outside Huichol culture itself, has become like an exotic flower, eagerly sought after by the cognoscenti.” The following information on sikuli has been reworked from the sales spiel included on the site by Zelaya as background material for the sale of the sikuli.[3] A specific type of nierika namma or Huichol Cross is called sikuli by the Huichol and is specifically crafted to protect children and is constructed in several periods. The central woven design, or eye, is made at the child’s birth, and four more are added, one each upon each consecutive birthday. The weavings are connected by two perpendicular sticks which are actually used to support the first eye when it is crafted in this format. This Sikuli was bought from a Shamanistic family from the Highlands of Jalisco that travels to the central part of the state.

The four points that result represent the elemental processes of Earth, Fire, Water and Air. Zelaya states that: “the ‘Eye of God’ design is sometimes included in larger flat weavings as a reminder of the power of holistic unity that is central to Huichol beliefs, but this is not the same as the actual Cross made for each child.” The sikuli is well guarded through the person’s life as a talisman of spiritual protection, health and well being and may be used by the individual or by shamans in healing or other rituals.

Hung in a child’s hair or on the walls of homes, or tied to the ends of arrows, the sikuli’s main purpose is to ensure children a long and healthy life.[4] When a child is born, the central eye is woven by the father. Then one eye is added for every year of the child’s life until the youngster reaches the age of five. The resulting design in the shape of a cross symbolizes the four elements of earth, air, fire and water. The Ojo de Dios is the most well known symbol. The Indians believe the design of the eye has the power to heal and to protect. The Ojo de Dios is hung on the wall and used in ceremonies and prayer. The colours used have different meanings: red - life itself; yellow - sun moon and stars; blue - sky and water; brown - soil; green - plants; black - death.</p>





&nbsp;
<li>Hear other albums and tracks:  <a href="http://elmisterio.org/la-flauta-de-bambu"> La Flauta De Bambu</a></li>







