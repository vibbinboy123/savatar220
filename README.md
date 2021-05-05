@import url(https://css.reizu.moe/uwu/uwu.css);

:root {
	--text-color: #00a689;
	--accent-color: #cffff7;
	--health-color: #f246db;
	--ammo-color: #73f3ff;
	--premium-color: #cfbfff;
	--verified-color: #cfbfff;
	--menu-bg-color: rgba(255, 255, 255, 1);
	--menu-bg-color-secondary: rgba(230, 230, 230, 1);
	--ingame-bg-color: rgba(15, 15, 15, .2);
	--text-transform: none;
}

@font-face {
	font-family: gamefont;
	src: url(https://raw.githubusercontent.com/South-Paw/typeface-vag-rounded/master/files/vag-rounded-400.woff2);
}

@font-face {
	font-family: hpammo;
	src: url(https://fonts.gstatic.com/s/montserrat/v15/JTURjIg1_i6t8kCHKm45_dJE3gnD_g.woff2);
}

#newsHolder {
	display: none;
}

.topRightCounters {
	position: unset;
	bottom: unset;
	right: unset;
}

.countIcon {
	padding: 10px;
}

#killStreakHolder {
    bottom: 150px;
}

#challIcon {
	display: inline-block !important;
	position: fixed;
	width: 50px;
	height: 50px;
	left: 50px;
	bottom: 55px;
	filter: brightness(0) invert(1) drop-shadow(2px 2px 3px rgba(30, 30, 30, .5));
}

#ammoIcon {
	display: inline-block !important;
	position: fixed;
	width: 50px;
	height: 50px;
	right: 50px;
	bottom: 55px;
	margin-right: 0;
	margin-left: 0;
	filter: brightness(0) invert(1) drop-shadow(2px 2px 3px rgba(30, 30, 30, .5));
}

#healthValue {
	position: fixed;
	left: 125px;
	bottom: 25px;
	font-size: 96px;
}

#ammoDisplay {
	width: 50px;
	height: 5px;
	top: calc(50% + 35px);
	left: calc(50% - 25px);
}

#ammoVal {
	position: fixed;
	font-size: 96px;
	right: 125px;
	bottom: 25px;
}

#weapDisplay {
	display: none !important;
}

#reloadMsg {
	text-shadow: 2px 2px 3px rgba(30, 30, 30, .5);
}

#chatHolder {
    bottom: 175px !important;
    left: 20px !important;
    border-radius: 10px;
    background-color: var(--ingame-bg-color);
}

#uiBase.onMenu #chatHolder {
    bottom: 20px !important
}

#timerDisplay {
	width: 240px;
	height: 80px;
	background-color: var(--ingame-bg-color);
	will-change: unset;
}

#timerVal {
	font-size: 64px;
	padding-left: 0;
	will-change: unset;
	text-shadow: 2px 2px 3px rgba(30, 30, 30, .5);
}

#teamScores {
	position: fixed;
	top: 0;
	left: 50%;
	transform: translateX(-50%);
	width: 685px;
	height: 50px;
	padding: 10px;
	padding-left: 0;
	padding-top: 0;
	padding-right: 0;
	padding-bottom: 0;
	margin-left: 0;
	margin-top: 0;
	margin-right: 0;
	margin-bottom: 0;
	border-radius: 0;
	background-color: transparent;
	text-shadow: 2px 2px 3px rgba(30, 30, 30, .5);
}

.tScore {
	display: inline-block;
}

#tScoreV1 {
	position: fixed;
	left: -25%;
	top: 4px;
}

#tScoreV2 {
	position: fixed;
	left: 25%;
	top: 4px;
}

.tScoreT {
	width: 100%;
	margin-top: 20px;
	text-align: center;
	font-size: 24px;
	color: #fff;
	text-shadow: 2px 2px 3px rgba(30, 30, 30, .5);
	z-index: 2;
}

.tScoreM {
	display: none;
}

.tScoreF {
	left: 50%;
	width: 100px;
	height: 80px;
	margin-left: 123px;
	margin-right: 116px;
	padding-left: 0;
	padding-right: 0;
	background-color: #eb5656;
	color: transparent;
	opacity: 50%;
	z-index: 1;
}

.tScoreF.you {
	background-color: #5699eb;
	color: transparent;
	opacity: 50%;
	z-index: 1;
}

.tScoreC {
	left: 50%;
	width: 100px;
	height: 80px;
	margin-left: 123px;
	margin-right: 116px;
	background-color: var(--accent-color);
	opacity: 50%;
	z-index: 1;
}

.tScoreC.you {
	background-color: #fff;
	opacity: 50%;
	z-index: 1;
}

#gameMessage {
	top: 90px;
	font-size: 18px;
	text-shadow: 2px 2px 3px rgba(30, 30, 30, .5);
}

#ingameFPS {
	color: #fff !important;
	visibility: visible;
	text-shadow: 2px 2px 3px rgba(30, 30, 30, .5);
}

#pingText {
	color: #fff !important;
	text-shadow: 2px 2px 3px rgba(30, 30, 30, .5);
}

#pingIcon {
	color: var(--accent-color) !important;
	text-shadow: 2px 2px 3px rgba(30, 30, 30, .5);
}

#pingDisplay .material-icons {
	font-size: 20px;
	text-shadow: 2px 2px 3px rgba(30, 30, 30, .5);
}

.leaderNameM:before { /* leaderboard verified */
    font-family: 'Material Icons';
    font-weight: normal;
    font-style: normal;
    font-size: 25px;
    line-height: 1;
    letter-spacing: normal;
    text-transform: none;
    display: inline-block;
    white-space: nowrap;
    word-wrap: normal;
    direction: ltr;
    -webkit-font-smoothing: antialiased;
    content: "check_circle";
    color: #40C4FF;
    margin-top: -3px;
    vertical-align: middle;
    margin-right: 3px;
    margin-left: -4px;
}
