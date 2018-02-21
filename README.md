//META{"name":"Niko","description":"A Oneshot theme","author":"Arupter","version":"2.0.0"}*//{}
@import url(https://fonts.googleapis.com/css?family=Karla);



:root {
	--main-color: rgba(75,0,130,1);
	--main-color-faded: rgba(255,255,0,0.2);
	--accent-color: rgba(102,102,0,1);
	--dark-color: #161921;


	--short-gradient: linear-gradient(45deg, rgba(29,101,134,0.5), rgba(37,172,232,0.5));
	--short-gradient-faded: linear-gradient(45deg, rgba(29,101,134,0.1), rgba(37,172,232,0.1));
}

.app,
.callout-backdrop {
	background: url(https://i.imgur.com/w0edtqa.png) !important;
	background-size: cover !important;
}


div>*:not(code) {
	font-family: 'karla',Whitney,Helvetica Neue,Helvetica,Arial,Lucida Grande,sans-serif !important;
}

textarea {
	background: transparent !important;
}

.scroller-wrap .scroller::-webkit-scrollbar-thumb {
	border: 3px solid rgba(255,255,255,0) !important;
	background-color: var(--accent-color) !important;
}

.scroller-wrap .scroller::-webkit-scrollbar-track-piece {
	border: 3px solid rgba(255,255,255,0) !important;
	background-color: rgba(0,0,0,0.3) !important;
}


.links,
.help-container {
	display: none;
}

.layers,
.container-RYiLUQ,
.container-2OU7Cz,
.theme-dark .layer-kosS71,
.theme-dark .layers-20RVFW,
.theme-dark .chat form {
	background: transparent !important;
}



.links,
.chat,
.typing-3eiiL_,
.content,
.guild-channels,
.private-channels,
.guild-header header,
.divider-red span,
.messages-wrapper,
#rtc-connection,
#voice-connection {
	background: transparent !important;
}


.guilds-wrapper { background:rgba(0,0,0,0.6) !important }


.channels-3g2vYe { background:rgba(0,0,0,0.7) }


.content .flex-spacer { background:rgba(0,0,0,0.8) }


.channel-members { background:rgba(0,0,0,0.9) !important }


.tooltip {
	background: var(--accent-color);
	color: #e0e0e0;
}

.tooltip.tooltip-right:after {
	border-right-color:var(--accent-color);
}

.tooltip.tooltip-top:after {
	border-top-color:var(--accent-color);
}

.tooltip.tooltip-bottom:after {
	border-bottom-color:var(--accent-color);
}


.typeMacOS-3IiWed {
	background: rgba(0,0,0,0.6);
	width: 71px;
	box-shadow: inset -10px 0px 20px -10px rgba(0,0,0,0.3);
}

.name-2SL4ev {
	font-size: 14px;
}

.icon-3tVJnl {
	width: 14px;
	height: 14px;
}

.unread-23Kvxk {
	background-color: var(--main-color);
}

.container-iksrDt {
	height: 75px;
	background: rgba(0,0,0,0.8);
	padding: 0 10px 0 15px;
}

.contentSelectedText-3j5CXt {
	background: rgba(0,0,0,0.8);
}

.contentSelectedText-3j5CXt:hover {
	background: rgba(0,0,0,0.8);
}

.contentHoveredText-2HYGIY,
.contentHoveredVoice-3qGNKh:active,
.contentSelectedVoice-gTtYM9:active {
	background: rgba(0,0,0,0.5);
}

.create-guild-container {
	background: none !important;
}

.create-guild-container .action {
	background: rgba(0,0,0,0.7);
}

.create-guild-container .create-or-join .actions .or {
	-webkit-filter: opacity(0.9) invert();
	color: #000;
}

.create-guild-container .action.create .action-icon,
.create-guild-container .action.join .action-icon {
	-webkit-filter:invert() hue-rotate(150deg);
}

.create-guild-container.deprecated .action {
	background: transparent !important;
	border: none !important;
	box-shadow: none !important;
}

.create-guild-container h5,
.create-guild-container .action.create .action-header {
	color:var(--main-color);
}

.create-guild-container .action.create .btn-primary {
	background-color:var(--main-color) !important;
}

.create-guild-container .action.create:hover .btn-primary {
	background-color:var(--accent-color) !important;
}

.create-guild-container .form-actions .btn-default {
	background: rgba(255,255,255,0.1);
	border: 0;
}

.create-guild-container .create-guild .guild-form .region-select {
	background: rgba(255,255,255,0.1);
}

.create-guild-container .create-guild .guild-form .region-select button {
	color:#000;
}

.create-guild-container .create-guild .guild-form .region-select:hover button {
	background-color:var(--main-color);
	border-color:var(--main-color);
	color:#fff;
}

.create-guild-container .create-guild .guild-form .region-select:hover .region-select-inner {
	border-color:var(--main-color);
}

.create-guild-container .create-guild .guild-form .region-select-name {
	color:#fff;
}

.avatar-uploader .avatar-uploader-inner {
	background-color: var(--main-color);
}

.region-select-modal {
	background:rgba(0,0,0,0.8);
}

.region-select-modal .region-select-modal-header {
	color:var(--main-color);
}

.region-select-modal .region-select-modal-option {
	background:rgba(255,255,255,0.1);
	border:2px solid rgba(255,255,255,0.1);
}

.region-select-modal .region-select-modal-option:hover {
	border-color: var(--main-color);
}

.region-select-modal .region-select-modal-option .region-select-name {
	color:#fff;
}

.guild-header {
	background: rgba(0,0,0,0.1);
	border-bottom: 1px solid rgba(0,0,0,0);
	padding-left: 82px;
	margin-left: -80px;
}

.guilds-wrapper .guilds .guild:first-of-type {
	
	margin-top: 1px;
	margin-left: -5px;
	border: 5px solid rgba(0,0,0,0);
	border-radius: 100% !important;
	transition: 200ms all ease-in-out;
}

.guilds-wrapper .guilds .guild:first-of-type:hover {
	border-radius: 100% !important;
}

.guilds-wrapper .guilds .guild.active {
	border-radius: 100% !important;
}

.guild-header-open ul {
	opacity:1 !important;
}

.guilds-add {
	opacity:0.5;
	font-size:22px !important;
	border: 1px dashed rgba(255,255,255,0.3) !important;
	margin-left: 0 !important;
	margin-top: 10px !important;
}

.platform-osx .guilds-wrapper {
	padding-top: 15px;
}

.guilds-wrapper {
	border-right:1px solid rgba(0,0,0,0.2);
	box-shadow:inset -10px 0px 20px -10px rgba(0,0,0,0.3);
}

.guilds-wrapper .guild-separator {
	margin-top:5px;
	margin-bottom:5px;
	margin-left:-5px;
	display:none;
}

.guilds-wrapper .guild-separator:after {
	background:transparent;
}

.guild-header header span {
	margin-left:-7px;
}

.guild-header header {
	box-shadow:none !important;
	color:#ddd;
}

.guild-channels header h2 {
	padding:0 18px;
}

.guild-channels .channel-text .channel-name,
.guild-channels .channel-voice .channel-name {
	font-size:0.9em;
}

.guild-channels .channel-text a {
	padding:8px 6px 10px 18px;
}

.guild-channels header h2,
.guild-channels .channel a {
	color: #fff;
}

.guilds-wrapper .guilds {
	padding: 18px 20px 85px 15px;
}

.guilds-add {
	font-size: 30px;
	background: #000;
}

.guilds-wrapper .guilds .friends-online {
	margin-top: 10px !important;
}

.guilds-wrapper .guilds .guild .guild-inner {
	background: #151515 !important;
}

.guilds-wrapper .guilds .guild.active:first-of-type .guild-inner {
	background: var(--main-color) !important;
}

.guilds-wrapper .guilds .guild .guild-inner a,
.guilds-wrapper .guilds .guild,
.guilds-wrapper .guilds .guild .avatar-small {
	width:40px;
	height:40px;
}

.guilds-wrapper .guilds .guild .avatar-small {
	width:40px;
	height:40px;
	background-size: 40px 40px;
}

.guilds-wrapper .guilds .guild .guild-inner {
	line-height:40px;
}

.guilds-wrapper .guilds .friends-icon {
	width:40px;
	height:40px;
	background-size:25px 19px;
}

.guilds-wrapper .guilds .friends-icon {
	background-color: rgba(0,0,0,0.3) !important;
	background-image: none !important;
	padding-top:0px;
}

.guilds-wrapper .guilds .friends-icon:after {
	display:block;
	width:40px;
	height:40px;
	content:'';
	background-image: url(https://i.imgur.com/52loYaP.gif) !important;
	background-size:110%;
	background-repeat:no-repeat;
	background-position:top center;
}

.guilds-wrapper .guilds .guild.audio .guild-inner:after {
	background-size:12px;
	background-color:rgba(0,0,0,0.8);
}

.guilds-wrapper .guilds .guild:before,
.guilds-wrapper .guilds .guild.unread:before,
.guilds-wrapper .guilds .guild.selected:before {
	left:-19px;
	transition:0.2s ease-in-out all;
}

.guilds-wrapper .guilds .guild.unread:not(.selected):before,
.guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before {
	background:var(--main-color);
}

.guilds-wrapper .guilds .guild.active .guild-inner:before {
	background:#fff !important;
}

.guilds-wrapper .guilds .friends-online {
	color: #ccc;
	font-size: 9px;
	margin: 15px 0 15px -7px;
	line-height: 20px;
	width: 55px;
	height: 20px;
	border-radius: 25px;
	overflow: hidden;
	background: rgba(0,0,0,0.3);
}

.guilds-wrapper .guilds-error {
	width:40px;
	height:40px;
	line-height:36px;
}

.guild-channels header h2,
.private-channels header {
	opacity:.6;
}

.guild-channels .channel:hover {
	background:rgba(0,0,0,0.3) !important;
}

.private-channels {
	overflow: visible !important;
}

.private-channels .search-bar {
	background: rgba(0,0,0,0) !important;
	box-shadow: none !important;
	border-radius: 0 !important;
	border-bottom: 1px solid rgba(0,0,0,.1);
}

.private-channels .search-bar .search-bar-inner {
	background: rgba(0,0,0,1) !important;
}

.private-channels .search-bar input {
	background: rgba(0,0,0,0.8) !important;
}

.guild-channels .channel.selected,
.private-channels .channel.selected a,
.private-channels .search-result.selected,
.private-channels .search-result:hover {
	background: rgba(0,0,0,0.6) !important;
}

.guild-channels ul .channel:not(.selected):hover,
.private-channels .channel:not(.selected) a:hover,
.private-channels .channel:not(.selected):hover a {
	background: rgba(0,0,0,0.3) !important;
}

.guild-channels .channel:not(.selected):before,
.guild-channels .channel.selected:before,
.guild-channels .channel.selected:hover:before,
.private-channels .channel:not(.selected):before,
.private-channels .channel.selected:before,
.private-channels .channel.selected:hover:before,
.private-channels .search-result.selected:before,
.private-channels .search-result:hover:before {
	border-left: 2px solid var(--accent-color) !important;
}

.guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before {
	left:-8px;
}



.base-3AoPqv {
	border-radius: 0 !important;
}

.menu-3BZuDT {
	background: var(--dark-color);
}

.item-rK1j5B:hover {
	background: var(--accent-color);
	color: #fff;
}

.item-rK1j5B.invite-YM1l0n {
	color: var(--main-color);
}

.separator-1hpa3S {
	border-bottom: 1px solid rgba(255,255,255,0.1);
}

.iconCollapsed-1INdMX, .iconDefault-xzclSQ, .nameCollapsed-3_ChMu, .nameDefault-Lnjrwm {
	color: #fff;
}

.nameDefaultText-QoumjC, .nameDefaultVoice-1swZoh, .nameLockedText-2fGz07, .nameLockedVoice-wNOMNa {
    color: rgba(255, 255, 255, 0.35);
}

.containerDefault-1bbItS {
	padding-top: 15px;
}

.unread-2TDDFN {
	background-color: var(--main-color);
}

.unread-mentions-indicator-bottom .unread-mentions-bar, .unread-mentions-indicator-top .unread-mentions-bar {
	box-shadow: none !important;
}

.icon-2qNMWC {
	margin-left: 0;
}

.bar-Y-RLyN {
    width: 70%;
    margin: 0 auto;
}

.channel-notices .channel-notice.quickswitcher-notice {
	background-color: rgba(0,0,0,0.7);
}

.channel-notices .channel-notice .message .btn {
	border: none;
	background-color: var(--accent-color);
	transition: all 100ms ease-in-out;
}

.channel-notices .channel-notice .message .btn:hover {
	color: #000;
  	font-weight: bold;
	background-color: var(--main-color);
}

.btn-hamburger {
	margin-right:-30px;
}

.btn-hamburger span {
	background:#fff;
}

.account {
	z-index:9;
	border-top:none !important;
	width:320px;
	margin-left:-80px;
	padding:0 15px !important;
	background:rgba(0,0,0,0.95);
	height:77px;
	box-sizing:border-box;
}

.account .status {
	border:2px solid rgba(0,0,0,1);
}

.account .btn {
	background:transparent;/*#000;*/
	box-shadow:none !important;
}

.account .btn:active {
	background:#000;
}

.account .btn-settings:after {
	opacity:0.3;
}

.account .btn-deafen,
.account .btn-mute {
	border-right:none;/*1px solid #101010;*/
}

#rtc-connection,
#voice-connection {
	z-index:9;
	border-top:none !important;
	/*width:285px;
	margin-left:-83px;*/
	padding:15px 20px 15px 18px !important;
}

#rtc-connection .btn,
#voice-connection .btn {
	background:#000;
	box-shadow:none !important;
}

.account .btn-deafen, .account .btn-settings {
	box-shadow:none !important;
}

.account .btn-group, 
#rtc-connection .btn-group,
#voice-connection .btn-group {
	border:none;
}

.account .avatar-small {
	margin:0 0 0 10px;
}

.message-group .comment {
	background:transparent !important;
	border:none !important;
}



.channel-text-area-default {
	margin: 10px 0 17px;
}

.inner-3if5cm {
	background: transparent !important;
	padding: 0 10px;
}

.search .search-bar {
	background-color: rgba(0, 0, 0, 0.55) !important;
}

.search-answer,
.search-filter {
	background-color: var(--accent-color) !important;
}

.search-popout {
	background-color: var(--dark-color);
	/*position: absolute !important;
	top: 55px !important;
	right: 162px !important;
	left: auto !important;*/
}

.search-popout .option:after {
	background: transparent;
}

.search-popout .option.selected {
	background-color: rgba(5, 5, 6, 0.9) !important;
	box-shadow: 0 0 5px rgba(0,0,0,0.8);
}

.search-popout .option.selected:after {
	background: transparent !important;
}

.search-results-wrap {
	background-color: rgba(0, 0, 0, 0.9) !important;
}

.search-results-wrap .search-header {
	background: transparent !important;
}

.search-results-wrap .channel-separator:before {
	border: none;
}

.search-results-wrap .channel-separator .channel-name {
	background-color: transparent !important;
}

.search-results-wrap .search-result:before {
	background: transparent !important;
	border-top: 1px solid rgba(0,0,0,0.3);
}

.search-results-wrap .search-result:after {
	background: transparent !important;
}

.search-results-wrap .search-result:not(.expanded) .search-result-message.hit, 
.search-results-wrap .search-result.expanded {
	border: 2px solid rgba(17, 21, 25, 0.6) !important;
}

.search-results-wrap .search-result .hit {
	background-color: rgba(0, 0, 0, 0.9) !important;
	box-shadow: 0 0 10px 6px rgba(0, 0, 0, 0.45) !important;
}

.theme-dark .search-results-wrap .action-buttons .jump-button {
	background-color: rgba(240, 240, 240, 0.07);
}

.search-popout .date-picker .date-picker-hint .hint-value {
	background: var(--main-color) !important;
}

.search-popout .date-picker .date-picker-hint {
	border-top: none !important;
}

.theme-dark .search-results-wrap .scroller-wrap .scroller::-webkit-scrollbar-track-piece {
	border:3px solid rgba(255,255,255,0) !important;
	background-color:rgba(0,0,0,0.3) !important;
}

.theme-dark .search-results-wrap .scroller-wrap .scroller::-webkit-scrollbar-thumb {
	border:3px solid rgba(255,255,255,0) !important;
	background-color:var(--accent-color) !important;
}

.search-popout .date-picker {
	border-top: none !important;
}

.react-datepicker {
	background-color: rgba(0,0,0,0.6) !important;
	color: rgba(255, 255, 255, 0.6) !important;
}

.react-datepicker .react-datepicker__header {
	background-color: transparent !important;
}

.react-datepicker .react-datepicker__day--disabled,
.react-datepicker .react-datepicker__day--outside-month {
	background-color: rgba(255, 255, 255, 0.07) !important;
	color: rgba(167, 167, 167, 0.6) !important;
}

.react-datepicker .react-datepicker__day {
	color: #fff;
	border-top: 1px solid rgba(255, 255, 255, 0.15) !important;
	border-left: 1px solid rgba(255, 255, 255, 0.15) !important;
}

.react-datepicker .react-datepicker__month>.react-datepicker__week:last-of-type .react-datepicker__day {
	border-bottom: 1px solid rgba(255, 255, 255, 0.15) !important;
}

.react-datepicker .react-datepicker__month .react-datepicker__week>.react-datepicker__day:last-of-type {
	border-right: 1px solid rgba(255, 255, 255, 0.15) !important;
}

.react-datepicker .react-datepicker__day.react-datepicker__day--today:after {
	background-color: var(--main-color) !important;
}

.react-datepicker .react-datepicker__day.react-datepicker__day--selected:hover, .react-datepicker .react-datepicker__day:hover {
	background-color: var(--main-color) !important;
}

.header-toolbar button span {
	background-size: 22px;
}

.header-toolbar button.popout-open {
	background:var(--main-color);
}

.channel-pins-wrap {
	background: rgba(0,0,0,0.9) !important;
}

.channel-pins-wrap .header,
.channel-pins-wrap .footer {
	background-color: rgba(0,0,0,0.95) !important;
	box-shadow: none !important;
}

.channel-pins .message-group {
	background-color: rgba(0,0,0,0.7) !important;
}

.channel-pins .message-group:hover {
	box-shadow: 0 0 4px 5px rgba(37, 172, 232, 0.1);
	border-color: rgba(37, 172, 232, 0.47) !important;
}

.channel-pins .message-group .action-buttons {
	box-shadow: none !important;
	background: none !important;
}

.channel-pins .message-group .action-buttons .jump-button {
	background-color: rgba(255,255,255,0.15) !important;
}

.spinner-wandering-cubes .spinner-item {
	background-color:var(--main-color);
	width:15px;
	height:15px;
	border-radius:4px;
}

.chat .has-more button {
	color:var(--main-color) !important;
	background:rgba(255,255,255,0.1) !important;
	border:none !important;
	box-shadow:none !important;
}

.highlight {
	color:var(--main-color);
}

.emoji-picker {
	background:rgba(0,0,0,0.85) !important;
}

.emoji-picker .search-bar input {
	color:rgba(255,255,255,0.7);
	background:rgba(255,255,255,0.1);
}

.emoji-picker .search-bar-clear {
	background:rgba(0,0,0,0.7);
}

.emoji-picker .sticky-header,
.emoji-picker .search-bar {
	background:rgba(0,0,0,0.95) !important;
}

.emoji-picker .categories .item.selected {
	border-bottom-color:var(--main-color);
}

.chat .title-qAcLxz {
	border-bottom: 1px solid rgba(0,0,0,0.3) !important;
	background: rgba(0,0,0,0.95) !important;
	box-shadow: none !important;
}

.header-1tSljs {
	border-bottom: 0px solid rgba(0,0,0,0.3) !important;
	background: rgba(0,0,0,0.15) !important;
	box-shadow: none !important;
	height: 49px !important;
}

.header-toolbar button.active {
	background-color:rgba(255,255,255,0.1);
}

.botTagRegular-288-ZL,
.need-help-modal .header {
	background:var(--main-color);
	padding: 2px 3px;
	font-size: 9px;
}

.form header {
	color:var(--main-color);
}

.markdown-modal,
.form .form-inner,
.form .form-header,
.form .form-actions,
.need-help-modal .footer,
.markdown-modal .markdown-modal-footer {
	background:rgba(0,0,0,0.85) !important;
	color: #fff;
}

.alert.form .form-inner .btn {
	padding: 0 !important;
	border: none !important;
}

.channel-notification-settings .content label,
.notification-settings-modal .mute-server .checkbox .label span {
	color:#fff;
}

.notification-settings-modal .notification-settings-modal-channel-settings-list {
	box-shadow:none !important;
}

.markdown-modal .markdown-modal-header {
	color:#fff;
}

.form .form-header,
.form .form-actions,
.need-help-modal .footer,
.channel-notification-settings,
.markdown-modal .markdown-modal-header,
.markdown-modal .markdown-modal-footer {
	border-color:rgba(255,255,255,0.2);
}

.modal-content {
	background: transparent !important;
}

.modal-content .user-name {
	color:#fff;
}

.modal-content .form-inner p {
	color:rgba(255,255,255,0.7);
}

.chat .new-messages-bar {
	background-color:rgba(29,101,134,.9);
}

.chat .new-messages-bar:hover {
	background-color:rgba(29,101,134,1);
}

.chat .new-messages-bar button:last-child {
	color:rgba(255,255,255,0.5);
}

.chat .empty-message {
	border: 0 !important;
	background: transparent !important;
	height: 40px;
}

.chat-empty {
	background:rgba(20,23,27,0.95);
}

.chat>.title-wrap>.title .channel-name {
	color:rgba(255,255,255,0.8);
}

.chat>.title-wrap>.topic {
	font-size:12px;
	margin-top:5px;
	color:#656565 !important;
}

.markdown-modal .highlight,
.chat .title-wrap .topic .highlight {
	background-color:rgba(255,255,255,.1) !important;
}

.markdown-modal .highlight:hover,
.chat .title-wrap .topic .highlight:hover {
	background-color:rgba(255,255,255,.2) !important;
	color:var(--main-color) !important;
}

.chat .divider {
	height:25px;
	background:none;
}

.chat .divider>div {
	display:none !important;
}
.chat .divider:not(.divider-red)>div {
	background:rgba(255,255,255,0.2) !important;
}

.chat .divider:before {
	background:rgba(255,255,255,0.06) !important;
	height:25px;
	border-radius: 3px;
}

.chat .divider.divider-red:before {
	background: rgba(240,71,71,.8) !important;
}

.chat .divider>span {
	background-color:transparent !important;
	font-size:12px;
	text-transform:uppercase;
	margin:10px 0px;
	border-radius: 0px;
	opacity: 1;
	padding: 8px 15px;
	line-height: 1px;
	width: 100%;
	text-align: center;
}

.chat .divider.divider-red>span {
	color: rgba(255,255,255,0.9) !important;
}

.chat .divider:not(.divider-red)>span {
	color:rgba(255,255,255,1) !important;
}

.chat .divider>div {
	display:none;
}

.chat form {
	border-top: none !important;
}

.messages .message-group:not(.has-divider) {
	border-bottom-color:hsla(0,0%,100%,.04) !important;
}

.messages .message-group {
	border-bottom: none !important;
}

.friends-table .messages .message-group .message-send-failed .markup,
.friends-table .messages .message-group .message-send-failed .markup a,
.messages .message-group .message-send-failed .markup,
.messages .message-group .message-send-failed .markup a {
	color:rgba(240,71,71,0.5) !important;
	font-style:italic;
}

.mentioned .message-text {
	border-radius: 0 !important;
	background: rgba(37,172,232,0.2) !important;
}

.mentioned .message-text:after {
	border-radius: 0 !important;
	border-color:var(--main-color) !important;
	background:rgba(37,172,232,0.2) !important;
}

.mention {
	color: var(--main-color) !important;
	background-color: var(--main-color-faded) !important;
	padding: 3px 5px;
	border-radius: 5px;
}

.messages a {
	color:var(--main-color) !important;
}

.messages h2 .user-name {
	font-size:0.85em;
	color:rgba(255,255,255,0.8);
}

.messages h2 span {
	color:rgba(255,255,255,0.2) !important;
}

.messages h2 .bot-tag {
	color:rgba(255,255,255,0.8) !important;
}

.messages .markup {
	font-size:0.85em !important;
	line-height:1.4em !important;
}

.messages .markup:not([data-colour="true"]) {
	color:rgba(255,255,255,0.5) !important;
}

.markup pre {
	border-radius:0 !important;
	background:transparent !important;
	border-color:rgba(255,255,255,0.1) !important;
}

.markup pre code.hljs {
	background:rgba(255,255,255,0.1) !important;
	color:rgba(255,255,255,0.7) !important;
	padding:1em !important;
}

.modal-content .markup code.inline,
.markup code.inline {
	background:rgba(255,255,255,0.1) !important;
	color:rgba(255,255,255,0.7) !important;
	padding:0.3em 0.6em !important;
	border-radius:3px !important;
}

.messages .markup .highlight {
	background-color:rgba(29,101,134,.5) !important;
	color:#ddd !important;
	padding: 1px 4px;
	border-radius: 0;
}

.messages .markup .highlight:hover {
	background-color:rgba(29,101,134,1) !important;
	color:#fff !important;
}

.messages .invite-button {
	background: rgba(255,255,255,0.07) !important;
	border-color: rgba(255,255,255,0.1) !important;
}

.emotewrapper img {
	position: relative;
	top: 7px;
}

.textArea-20yzAH {
	font-size: 0.85rem;
}

.channel-textarea-upload {
	border-right-color: hsla(0,0%,100%,.1) !important;
}

.channel-textarea-inner {
	border: 2px solid rgba(255,255,255,0.1) !important;
	background:rgba(0,0,0,0.6) !important;
}

.channel-textarea-autocomplete-inner {
	border:none !important;
	background:rgba(0,0,0,0.95) !important;
}

.channel-textarea-autocomplete-inner header {
	border:none !important;
	background: rgba(37,172,232,0.5) !important;
	color: rgba(255,255,255,0.9) !important;
}

.channel-textarea-autocomplete-inner ul li.active {
	background:rgba(255,255,255,0.1) !important;
}

.channel-textarea-guard button {
	background:var(--accent-color) !important;
}

.channel-textarea-guard button:hover {
	background:var(--main-color) !important;
}

.typing-3eiiL_ {
	font-size:11px;
}

.spoiler span {display:none;}
.spoiler:before {
	min-height:18px;
	padding-top:2px;
	border-radius:5px;
	background:rgba(25,25,25,0.7);
}

#twitchcord-button {
	background-size: 24px;
	background-position: 20px;
	background-color: transparent;
	opacity:0.4;
}

#twitchcord-button:hover,
#twitchcord-button.twitchcord-button-open {
	opacity:1;
}

#twitchcord-button-container {
	right:30px !important;
}

/*** COMPACT MODE ***/

.message-group.compact {
	margin-left:0;
}

.message-group.compact .timestamp {
	color:rgba(255,255,255,0.3) !important;
	position:relative;
	top:-1px;
}

.message-group.compact .message .markup .user-name {
	margin-right:8px;
	font-size:14px;
}



#friends .btn,
.add-friend-popout .btn {
	background-color: var(--main-color) !important;
}

.add-friend-popout .btn:disabled {
	background-color: var(--accent-color) !important;
	opacity: 0.4;
}

.private-channels .channel.btn-friends .badge {
	margin-right: 10px;
}

.private-channels .channel .close {
	margin-right: 5px;
}

#friends {
	background: transparent !important;
}

.friends-header {
	background: rgba(0,0,0,0.95) !important;
}

.friends-table {
	background:rgba(0,0,0,0.85) !important;
	margin-top:0 !important;
}

.friends-header,
.friends-table .friends-table-header {
	border-bottom: 1px solid hsla(0,0%,100%,.1) !important;
}

.friends-header .tab-bar .tab-bar-separator,
.friends-table .friends-table-header .friends-column-separator {
	background-color:hsla(0,0%,100%,.1) !important;
}

.friends-table .friends-table-body {
	padding-top:20px !important;
}

.friends-table .friends-row:hover {
	background: rgba(0,0,0,0.7) !important;
}

/*
					   _ _     _                   _   _             
 _   _ ___  ___ _ __  | (_)___| |_   ___  ___  ___| |_(_) ___  _ __  
| | | / __|/ _ \ '__| | | / __| __| / __|/ _ \/ __| __| |/ _ \| '_ \ 
| |_| \__ \  __/ |    | | \__ \ |_  \__ \  __/ (__| |_| | (_) | | | |
 \__,_|___/\___|_|    |_|_|___/\__| |___/\___|\___|\__|_|\___/|_| |_|

*/

.channel-members .member.popout-open, 
.channel-members .member:hover {
	background: rgba(255,255,255,0.07) !important;
}

.channel-members .invite-btn {
	background:var(--accent-color);
}

.channel-members .invite-btn:hover {
	background:var(--main-color);
}

.channel-members .bot-tag {
	padding: 0px 3px;
}

.channel-members .member {
	border-radius: 0 5px 5px 0;
}

.channel-members .member:hover {
	background:rgba(255,255,255,0.07) !important;
}

.channel-members .member .member-username {
	font-size:12px;
}

.channel-members .member .member-game {
	font-size:10px;
}

.channel-members .avatar-small .status {
	border-color:rgba(0,0,0,0.7) !important;
}

.channel-members h2 {
	background: rgba(0,0,0,0);
	padding-top: 10px;
	padding-bottom: 10px;
}

.channel-members .member+h2 {
	margin-top:12px;
}

.channel-members h2:first-of-type {
	margin-top:0px !important;
}



.headerPlaying-2eYqm9,
.topSectionPlaying-3jAH9b,
.topSectionNormal-2LlRG1 {
	background: var(--main-color) !important;
}

.body-3_tdh6,
.body-3rkFrF,
.footer-2J5zqP {
	background-color: var(--dark-color) !important;
}

.headerNormal-1cioxU {
	background: var(--main-color) !important;
	position: relative;
	z-index: 1;
}

.buttonDefault-2OLW-v,
.buttonBrandInverted-VFL7Yc {
	background-color: var(--accent-color);
    color: #fff;
}

.buttonDefault-2OLW-v:hover,
.buttonBrandInverted-VFL7Yc:hover {
	background-color: #161921;
}

.tab-bar.TOP .tab-bar-item.selected {
    border-bottom: 2px solid #fff !important;
    color: #fff !important;
}

.user-popout .header:after {
	z-index: 2;
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background: rgba(0,0,0,0.5);
	content: '';
}

.user-popout .avatar-wrapper,
.user-popout .username-wrapper {
	z-index: 10;
}

.user-popout .avatar-wrapper .avatar-popout {
	border: none !important;
	background-color:rgba(0,0,0,0.9);
	box-shadow: 0 10px 40px -8px rgba(0,0,0,1);
}

.user-popout .body {
	background:rgba(0,0,0,0.8);
	border-left:1px solid rgba(255,255,255,0.2);
	border-right:1px solid rgba(255,255,255,0.2);
}

.user-popout .footer {
	background:rgba(0,0,0,0.8);
	border-top:1px solid rgba(255,255,255,0.2);
	border-left:1px solid rgba(255,255,255,0.2);
	border-right:1px solid rgba(255,255,255,0.2);
	border-bottom:1px solid rgba(255,255,255,0.2);
}

.quick-message {
	color: #fff;
	border: 1px solid rgba(224, 229, 232, 0.26);
	background: rgb(0, 0, 0);
}

.user-popout .username-wrapper .game,
.user-popout .username-wrapper.hasNickname .discriminator,
.user-popout .username-wrapper.hasNickname .username {
	color:rgba(0,0,0,0.7);
}

.popout header,
.slider-bar-fill {
	background-color:var(--main-color);
	border:1px solid var(--main-color);
}

.user-popout .user-popout-options .btn {
	background-color:var(--accent-color);
	border:1px solid var(--accent-color);
}

.user-popout .user-popout-options .btn:hover {
	background-color:var(--main-color);
	border:1px solid var(--main-color);
}

/* Admin buttons */
.user-popout .user-popout-options .btn.btn-server {
	color: rgba(255,255,255,0.7);
	background: rgba(240,71,71,0.4);
	border: none !important;
}

.user-popout .user-popout-options .btn.btn-server:hover {
	color: rgba(255,255,255,1);
	background: rgba(240,71,71,1);
	border: none !important;
}

.markdown-modal, .form .form-inner, .form .form-header, .form .form-actions, .need-help-modal .footer, .markdown-modal .markdown-modal-footer {
	background: #161921 !important;
}

.need-help-modal.deprecated .header input[type=text]:focus {
	border: none !important;
}

.need-help-modal.deprecated .header input[type=text] {
	box-shadow: none !important;
}



.bd-minimal .channel-text a,
.bd-minimal .guild-channels ul .channel-voice {
	padding:5px 5px 5px 10px !important;
}

.bd-minimal .guilds-wrapper .guilds {
	padding-left:10px !important;
}

.bd-minimal .guilds-wrapper .guilds .friends-icon {
	background-size:60% !important;
}

.bd-minimal .guilds-wrapper .guilds .guild:before {
	width:10px;
	height:25px;
	border-radius:5px;
	margin-top:-13px;
	left:-16px;
}

.bd-minimal .guilds-wrapper .guilds .guild.unread:before {
	height:10px;
	margin-top:-5px;
}

.bd-minimal .guilds-wrapper .guilds .guild.selected:before {
	border-radius:5px;
	height:25px;
	margin-top:-13px;
}

.bd-minimal .guilds-wrapper .guilds .guild,
.bd-minimal .guilds-wrapper .guilds .guild .guild-inner,
.bd-minimal .guilds-wrapper .guilds .guild .guild-inner .avatar-small,
.bd-minimal .guilds-wrapper .guilds .guild .guild-inner .friends-icon {
	width:25px;
	height:25px;
	line-height:25px;
	background-size:25px 25px;
	font-size:10px !important;
}

.bd-minimal .guilds-wrapper .guilds .friends-online {
	font-size: 10px;
	word-spacing: 50px;
	line-height: 20px;
	margin-left: 0px;
	width: 25px;
	height: 20px;
	border-radius: 20px;
	overflow: hidden;
	background: rgba(0,0,0,0.5);
}

.bd-minimal .guilds-wrapper .guild-separator {
	width:25px;
	margin-left:0;
}

/* CHAT */
.bd-minimal .chat>.title-wrap>.title {
	font-size: 16px;
}

.bd-minimal .theme-dark .comment {
	border-left:none !important;
	padding-left:10px;
}

.bd-minimal .message-group {
	padding:10px 5px;
}

.bd-minimal .avatar-large {
	border-radius:100%;
}

.bd-minimal .message-group .edit-message .edit-container-outer {
	margin-left:50px;
}

.bd-minimal .message-group .edit-message .edit-container-inner {
	margin-left:10px;
}

/* MEMBERS */
.bd-minimal .channel-members h2 {
	margin-top:10px;
	margin-bottom:3px;
	padding-left:20px;
}

.bd-minimal .channel-members h2:first-of-type {
	margin-top:0px;
	margin-bottom:3px;
}

.bd-minimal .channel-members .member {
	padding:5px 15px 8px 20px;
}

/* CHANNELS */
.bd-minimal .guild-header header span {
	margin-left:-7px;
	font-size:14px;
}

.bd-minimal .guild-channels .channel-text .channel-name {
	padding-left:5px;
}

.bd-minimal .guild-channels header:first-of-type {
	margin-top:5px;
}

.bd-minimal .guild-channels .channel-text.unread:not(.selected):not(.channel-muted):before {
	top:9px;
	width:10px;
	height:10px;
}

.bd-minimal .guild-channels h2 {
	margin-left:15px;
}

/* ACCOUNT BAR */
.bd-minimal #rtc-connection,
.bd-minimal #voice-connection {
	width:176px;
	margin-left:-46px;
}

.bd-minimal .account {
	width:206px;
	margin-left:-46px;
}

.bd-minimal .account .avatar-small {
	display:block !important;
	margin-left:2px;
}

.bd-minimal .account .username {
	display:none;
}

.bd-minimal .account .btn-group {
	margin-left:10px;
}

.bd-minimal .account .btn-group .btn {
	width:30px;
}

/* BD Settings */

#bd-settingspane-container .content-column {
	color: rgba(255,255,255,0.9);
}

#bd-settingspane-container .content-column h2 {
	font-size: 22px;
	text-transform: uppercase;
	font-weight: bold;
}

#bd-settingspane-container .content-column .ui-switch-item,
#bd-settingspane-container .content-column .ui-switch-item div {
	justify-content: space-between !important;
}

#bd-settingspane-container .content-column .ui-switch-item {
	background: var(--dark-color) !important;
    margin-bottom: 20px;
    border-radius: 5px;
    padding: 15px 15px 0 15px;
}

#bd-settingspane-container .content-column .ui-switch-item .ui-form-text {
	font-size: 14px;
	font-weight: 500;
	color: rgba(255,255,255,0.35);
}

#bd-settingspane-container .ui-switch-item .style-description {
	border: none;
}

.ace_editor,
.ace_gutter {
	background: var(--dark-color) !important;
}

.ace_gutter {
	border-right: 1px solid rgba(255,255,255,0.1);
}

.ace_gutter-cell,
.ace_gutter-cell,
.ace-line,
.ace_text-input {
	height: 25px;
}



.bda-slist li {
	flex: 1 1 auto;
	display: flex;
	position: relative;
	justify-content: space-between;
	background: transparent !important;
	padding: 0;
	margin-bottom: 20px;
	border-bottom: 1px solid rgba(255,255,255,0.1) !important;
}

.ui-standard-sidebar-view .bda-slist li:nth-child(odd) {
	border-top: none !important;
}

.bda-slist .bda-left {
	width: 100% !important;
	padding: 0;
}

.bda-slist .bda-header {
	padding: 15px;
}

.bda-slist .bda-right {
	display: flex;
	justify-content: space-between;
	flex-direction: row-reverse;
	float: none;
	position: absolute;
	top: -2px;
	right: 0;
}

.bd-pfbtn {
	position: relative;
	top: -5px;
	left: 20px;
	height: 24px;
	padding: 0 8px;
	line-height: 22px;
	margin: 0 !important;
	background: var(--accent-color);
	transition: background 100ms ease-in-out;
}

.bd-pfbtn:hover {
	background: var(--main-color);
}

.ui-standard-sidebar-view .bda-slist .bda-right button {
	height: 24px;
	width: auto;
	padding: 0 11px;
	margin: 0 10px 0 0;
	background: var(--accent-color);
	transition: background 100ms ease-in-out;
}

.ui-standard-sidebar-view .bda-slist .bda-right button:hover {
	background: var(--main-color);
}

.bda-slist .bda-name {
	color: rgba(255,255,255,0.6);
	font-size: 16px;
	max-height: 30px;
	height: 20px;
}

.bda-slist .bda-name span:first-of-type {
	color: rgba(255,255,255,1);
	margin-right: 5px;
	font-size: 16px;
}

.bda-slist .bda-name span:last-of-type {
	color: var(--main-color);
}

.ui-standard-sidebar-view .bda-slist .bda-description {
	border: none !important;
	min-height: auto;
	max-height: 80px;
	line-height: 20px;
	color: rgba(255,255,255,0.4);
	margin: 45px 0 5px 0;
}

#emoteBlistTa {
	color: #fff;
	padding: 10px 10px 0 10px;
	margin: 10px 0;
	border-radius: 3px;
	background: rgba(0,0,0,0.4) !important;
	border-color: rgba(255,255,255,0.2);
	outline: none;
}

.bda-slist li div:not(.bda-right):not(.bda-left):not(.scroller-wrap):not(.scroller):nth-of-type(1) {
	float: none;
	position: absolute;
	right: 0;
	top: 0;
	width: 100%;
}

.bda-slist li div:not(.bda-right):not(.bda-left):not(.scroller-wrap):not(.scroller):nth-of-type(2) {
	margin-top: 0;
	width: 100%;
}

.bda-slist li[style*="max-height: 500px; overflow: auto;"] h2 {
	font-size: 18px !important;
	text-transform: none !important;
	margin: 0 0 20px 0 !important;
}

.bda-slist li[style*="max-height: 500px; overflow: auto;"] h2 span {
	font-size: 14px;
	margin-left: 10px;
}

.bda-slist li[style*="max-height: 500px; overflow: auto;"] h2 button {
	color: #fff;
	background: var(--accent-color);
	border-radius: 3px;
	padding: 0 8px;
	height: 24px;
	transition: background 100ms ease-in-out;
}

.bda-slist li[style*="max-height: 500px; overflow: auto;"] h2 button:hover {
	background: var(--main-color);
}

.content-region .CodeMirror, 
.content-region .cm-s-material .CodeMirror-gutters, 
#bd-customcss-detach-container .CodeMirror, 
#bd-customcss-detach-container .cm-s-material .CodeMirror-gutters {
	background: rgba(0, 0, 0, 0.5)!important;
	border-radius: 5px;
}

.content-region #bd-customcss-attach-controls, 
#bd-customcss-detach-container #bd-customcss-attach-controls {
	background: rgba(0, 0, 0, 0.8)!important;
	box-shadow: 0 1px 0 0 rgba(255, 255, 255, 0.1) inset;
}

#bd-customcss-attach-controls {
	padding: 10px 15px 10px 25px;
	height: 75px;
	display: flex;
	justify-content: space-between;
	align-items: center;
}

.ui-standard-sidebar-view #bd-customcss-attach-controls button, 
.bd-detached-css-editor #bd-customcss-attach-controls button {
	width: auto !important;
	border-radius: 3px !important;
	border: none !important;
	margin-left: 7px;
	padding: 5px 15px;
}

#bd-customcss-attach-controls button {
	
	background: var(--accent-color) !important;
	transition: background 100ms ease-in-out;
}

#bd-customcss-attach-controls button:hover {
	background: var(--main-color) !important;
}

#bd-customcss-detach-controls-button {
	text-align: right;
}

#bd-customcss-detach-controls-button span {
	display: block;
	text-align: right;
	padding-top: 10px;
	color: rgba(255,255,255,0.5);
}

#bd-customcss-detach-container {
	background-color: rgba(0,0,0,1);
}

#bd-customcss-detach-container .ui-standard-sidebar-view #bd-customcss-attach-controls button, 
#bd-customcss-detach-container .bd-detached-css-editor #bd-customcss-attach-controls button {
	padding: 5px 7px;
}

#bd-customcss-detach-container #bd-customcss-attach-controls {
	padding: 10px 15px 10px 15px;
}

.content-region .CodeMirror-scroll {
	padding-top: 10px;
}

.CodeMirror-lines {
	padding: 4px 10px;
}

.CodeMirror pre {
	padding: 0 5px;
}

.CodeMirror-gutter {
	margin-right: 20px;
}


.wrapper-VSYYTS,
.modal-3HOjGZ,
.footer-1PYmcw,
.form-deprecated .form-header,
.form-deprecated .form-inner,
.wrapper-VSYYTS .instantInviteModal-5L33Qh .form-actions,
.wrapper-VSYYTS .instantInviteModalAdvanced-38f2M0 .form-actions {
	background: var(--dark-color) !important;
}

.form-deprecated .Select-control .Select-arrow {
    top: 0;
}

.form-deprecated .Select-option.is-focused {
    background: #050505;
    color: #dcddde;
}

.form-deprecated .btn-primary, .form.deprecated .btn-primary {
	background: var(--main-color) !important;
}

.Select-option {
	background: rgba(0,0,0,0.85);
}

.Select-option.is-selected {
	background: rgba(0,0,0,1);
}

.button-2t3of8 {
	margin-left: 10px;
}

.clipboardInputInner-oj8y-S,
.Select-control {
	border: none !important;
	background: rgba(0,0,0,0.8) !important;
}

.wrapper-VSYYTS .instantInviteModal-5L33Qh .clipboardInputInner-dxVheg input {
	color: rgba(255,255,255,0.7);
	background: rgba(0,0,0,0.85);
	font-size: 20px;
	padding-left: 15px;
}

.wrapper-VSYYTS .instantInviteModal-5L33Qh .copy-2xFKb_ {
	border: none !important;
	background: var(--main-color) !important;
}

.clipboardInputInner-oj8y-S button:first-of-type:before {
	background: none !important;
}

.side-2nYO0F .itemSelected-3XxAMf {
	background-color: var(--main-color);
}

.layer {
	background: rgba(0,0,0,0.4) !important;
}

.ui-text-input .input.editable:focus:focus, 
.ui-text-input .input.editable:hover:focus, 
.ui-text-input .input:focus {
	border-color: var(--main-color) !important;
}

.description-3MVziF,
.labelDescriptor-1BebCl {
	color: rgba(255,255,255,0.35);
}

.buttonBrandFilled-3Mv0Ra {
	background: var(--accent-color);
	box-shadow: 0 10px 30px -8px rgba(0,0,0,0);
	transition: all 100ms ease-in-out;
	transform: translate3d(0,0,0);
}

.buttonBrandFilledDefault-2Rs6u5:hover {
	color: rgba(0,0,0,0.8);
	font-weight: bold;
	background: var(--main-color);
	box-shadow: 0 10px 30px -8px rgba(0,0,0,0.8);
	transform: translate3d(0,-3px,0);
}

.ui-slider .slider-bar-fill {
	background: var(--main-color);
}

.ui-standard-sidebar-view {
	background: transparent !important;
}

.ui-standard-sidebar-view .sidebar-region,
.ui-standard-sidebar-view .sidebar-region .scrollbar {
	background: rgba(0,0,0,0.7) !important;
}

.ui-standard-sidebar-view .content-region,
.ui-standard-sidebar-view .content-region .scrollbar {
	background: rgba(0,0,0,0.8) !important;
}

.ui-tab-bar.SIDE .ui-tab-bar-item {
	font-size: 14px;
	line-height: 17px;
}

.ui-tab-bar.SIDE .ui-tab-bar-item.selected {
	color: rgba(255,255,255,1) !important;
	background: var(--short-gradient) !important;
}

.ui-tab-bar-item:hover {
	background: var(--short-gradient-faded) !important;
}

.ui-radiogroup .checked {
	border-color: rgba(0,0,0,1) !important;
	background: var(--short-gradient) !important;
}

.ui-tab-bar-item,
.ui-tab-bar.SIDE .ui-tab-bar-item.brand {
	color: rgba(255,255,255,0.6) !important;
}

.ui-button.brand.filled {
	color: rgba(255,255,255,0.6);
	box-shadow: 0 0px 20px 0px rgba(0,0,0,0);
	transform: translate3d(0,0,0);
	background: var(--short-gradient) !important;
	-webkit-transition: 200ms all cubic-bezier(0.13, 0.28, 0.19, 0.89);
}

.ui-button.brand.filled:hover {
	color: rgba(255,255,255,1);
	box-shadow: 0 10px 20px 0px rgba(0,0,0,0.5);
	transform: translate3d(0,-3px,0);
	background: var(--short-gradient) !important;
}

.ui-radiogroup .checked svg g polyline {
	stroke: #fff !important;
}

.ui-switch-checkbox:checked+.ui-switch {
	background: var(--short-gradient) !important;
}

.avatar-xxlarge {
	box-shadow: 0 10px 20px 2px rgba(0,0,0,0.5);
}

/* OLD SETTINGS */

.context-menu {
	background: rgba(0,0,0,0.95) !important;
}

.context-menu .item:hover,
.context-menu .item-subMenu {
	background-color:rgba(255,255,255,0.05) !important;
}

.avatar-uploader a {
	color:var(--main-color);
}

.avatar-uploader a:hover {
	color:var(--accent-color);
}

.settings .settings-header {
	background:#1a1d20 !important;
}

.form .btn-primary {
	background-color:var(--accent-color);
}

.form .btn-primary:hover {
	background-color:var(--main-color);
}

.user-settings-modal a {
	color:var(--accent-color);
}

.user-settings-modal a:hover {
	color:var(--main-color);
}

.channel-notification-settings .content .content-inner {
	background:transparent !important;
}

.callout-backdrop {
	opacity:0.55;
}

.tab-bar.SIDE {
	margin-right: -17px;
}

.tab-bar.SIDE .tab-bar-item.selected {
	background: rgba(0,0,0,0.7) !important;
}

.tab-bar.SIDE .tab-bar-item.selected:before {
	border-color:var(--main-color);
}

.tab-bar.SIDE .tab-bar-item:before {
	border-color:var(--accent-color);
}

.popout header,
.slider-bar-fill {
	border:none !important;
}

.slider-handle,
.Select-control {
	border:none !important;
}

.slider-bar {
	background: rgba(255,255,255,0.5);
}

.settings .settings-header {
	background:rgba(0,0,0,0.88) !important;
}

.settings .settings-inner,
.settings .settings-actions,
.deprecated-settings-modal .settings-inner,
.deprecated-settings-modal .settings-actions {
	background:rgba(0,0,0,0.75);
}

.settings .settings-actions {
	border-top:none !important;
}

.form .radio-group .radio,
.form .checkbox-group .checkbox,
.checkbox .checkbox-inner+span {
	color:rgba(255,255,255,0.7) !important;
	font-size: 0.95em;
}

.form .control-group input[type=email],
.form .control-group input[type=password],
.form .control-group input[type=text],
.form .control-group textarea {
	padding:5px 10px 5px 10px;
	border-radius:5px;
	box-sizing:border-box;
	border:1px solid rgba(255,255,255,0.1);
	background:rgba(0,0,0,0.5);
	color:rgba(255,255,255,0.5);
	font-size:14px;
}

.form .control-group input[type=email]:focus,
.form .control-group input[type=password]:focus,
.form .control-group input[type=text]:focus,
.form .control-group textarea:focus {
	border-color:rgba(255,255,255,0.3);
	background:rgba(0,0,0,0.7);
	color:rgba(255,255,255,1);
	font-size:14px;
}

.form .Select-control,
.form .Select-option {
	border:1px solid rgba(255,255,255,0.1) !important;
	background:rgba(0,0,0,0.5);
	color:rgba(255,255,255,0.5);
	font-size:14px;
}

.form .Select-option {
	border-top:none !important;
	background:rgba(0,0,0,0.7);
	color:rgba(255,255,255,0.4);
}

.form .Select-option.is-focused {
	border-top:none !important;
	background:rgba(0,0,0,1);
	color:rgba(255,255,255,1);
}

.Select-menu-outer {
	background:rgba(0,0,0,0.5);
	border:none !important;
}

.has-value>.Select-control>.Select-placeholder {
	color:rgba(255,255,255,0.8);
}

.form .btn-default {
	padding:10px 0 !important;
	width: 75px;
	height: 35.5px;
	border-radius: 3px;
}

.form hr,
.form .control-groups.control-separator,
.instant-invites .instant-invites-header,
.guild-settings-modal-integrations .guild-settings-modal-integrations-header,
.guild-settings-modal-members .guild-settings-modal-members-header,
.guild-settings-modal-members .guild-settings-modal-list .member+.member,
.guild-settings-modal-members .guild-settings-modal-members-footer,
#settings-roles .roles header,
#user-profile-modal .tab-bar {
	border-color:rgba(255,255,255,0.2);
	box-shadow:none;
}

.form .control-group input[type=email]:disabled,
.form .control-group input[type=password]:disabled,
.form .control-group input[type=text]:disabled,
.form .control-group textarea:disabled {
	background:rgba(255,255,255,0.2) !important;
}

.guild-settings-modal-members {
	background:none !important;
}

#settings-roles .roles {
	border-right:1px solid rgba(255,255,255,0.2);
}

#settings-roles .roles li:hover:before {
	background:var(--accent-color);
}

#settings-roles .roles li:hover:not(.selected) {
	background:rgba(0,0,0,0.9) !important;
}

#settings-roles .roles li.selected {
	background:rgba(0,0,0,0.5) !important;
}

#settings-roles .roles li.selected:before {
	background:var(--main-color);
}

.btn-help {
	font-size: 11px;
	background: rgba(255,255,255,0.3);
}

.btn-help:hover,
.radio:hover span:after {
	background:var(--accent-color);
}

.radio .radio-inner span:after {
	background:var(--main-color);
}

.user-settings-modal-keybinds .user-settings-modal-keybinds-header {
	border-bottom:1px solid rgba(255,255,255,0.2);
}

.user-settings-modal .voice-settings .reset-voice-settings {
	color:var(--accent-color);
}

.user-settings-modal .voice-settings .reset-voice-settings:hover {
	color:var(--accent-color);
	opacity:0.6;
}

.checkbox .checkbox-inner input[type=checkbox]:checked+span {
	background:var(--main-color);
	border-color:var(--main-color);
}

.user-settings-modal-connections .user-settings-modal-accounts-list .connect-container .name {
	color:rgba(255,255,255,0.8);
}

.user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-integrations.no-integrations {
	color:rgba(255,255,255,0.8);
}

.user-settings-modal-connections .user-settings-modal-connections-list .connection .connection-integrations {
	border-color:#643DA7 !important;
}

.user-settings-modal-connections .user-settings-modal-connections-list {
	box-shadow: 0 -1px rgba(255,255,255,0.2);
}

.tab-bar.TOP {
	border-color:rgba(255,255,255,0.2);
}

.tab-bar.TOP .tab-bar-item.selected {
	border-color:var(--main-color);
	color:var(--main-color);
}

.user-settings-streamer-mode {
	background:none;
}

.user-settings-modal-games {
	background:rgba(255,255,255,0.05) !important;
	border:none !important;
}

.user-settings-modal-games .games-table .games-row .item-game,
.user-settings-modal-games .games-table .games-row .item-overlay {
	border-color:rgba(255,255,255,0.2) !important;
}

.user-settings-modal-games .games-table .games-row .item-game .game-input,
.user-settings-modal-games .games-table .games-row .item-game .game-name {
	color:#fff;
}

.user-settings-modal-games .games-table .games-row .item-game .last-played {
	color:rgba(255,255,255,0.5);
}

.now-playing {
	background:var(--main-color) !important;	
}

.now-playing.no-detection {
	background: rgba(0,0,0,0.8);
}

.bd-g-table tbody tr,
.bd-g-table thead th,
.bd-g-table tbody tr:nth-child(odd) {
	background:transparent !important;
}

.bd-g-table textarea {
	color: rgba(255,255,255,0.4) !important;
	background: rgba(255,255,255,0.2) !important;
	padding: 8px 10px !important;
	box-sizing:border-box;
}

#bd-pane .scroller-wrap div[style*="background:#2E3136; color:#ADADAD; height:30px; position:absolute; bottom:0; left:0; right:0;"] {
	background:rgba(0,0,0,0.95) !important;
}

.CodeMirror {
	background: rgba(255,255,255,0.15) !important;
	border-radius: 0px;
	color: rgba(255,255,255,0.8) !important;
}

.CodeMirror-gutters {
	background: rgba(255,255,255,0.25) !important;
	border:none !important;
}

.CodeMirror-linenumber {
	color: #fff !important;
}

.cm-s-neat span.cm-builtin {
	color:var(--main-color);
}

.cm-s-neat span.cm-atom,
.cm-s-neat span.cm-number {
	color:var(--main-color);
}

.member-roles .member-role {
	background-color: rgba(255,255,255,0.1);
	border:none;
	padding: 6px 8px;
	color: #fff;
}

.popout section {
	background:rgba(0,0,0,0.95) !important;
}

.popout.popout-bottom header:before {
	border-bottom-color:var(--accent-color);
}

#autocomplete-popout .row.selected,
#autocomplete-popout .row:hover {
	background:rgba(255,255,255,0.2) !important;
}

#permissions .permission-actions {
	color:rgba(255,255,255,0.7) !important;
}

#autocomplete-popout .empty h4,
#permissions .permissions-helpdesk,
.guild-settings-modal-members .guild-settings-modal-members-footer a {
	color:var(--main-color);
}

#permissions .permissions-helpdesk:hover,
.guild-settings-modal-members .guild-settings-modal-members-footer a:hover {
	color:var(--accent-color);
}

#user-profile-modal {
	border-radius: 5px;
}

#user-profile-modal .header {
	border-radius: 5px 5px 0 0;
	background: var(--main-color-faded);
	background-image: none !important;
}

#user-profile-modal .header:after {
	background-image: none !important;
	background-color: rgba(0, 0, 0, 0.6);
}

#user-profile-modal .btn {
	background:var(--main-color);
}

#user-profile-modal .guilds .section .connected-accounts .connected-account {
	border: 1px solid rgba(255, 255, 255, 0.15);
	background: rgba(0, 0, 0, 0.65);
}

#user-profile-modal .sub-header,
#user-profile-modal .tab-bar-container,
#user-profile-modal .scroller,
#user-profile-modal .empty,
#user-profile-modal footer {
	background:rgba(0,0,0,0.85) !important;
}

#user-profile-modal .tab-bar-container {
	border-bottom: 1px solid rgba(240, 240, 240, 0.15) !important;
}

#user-profile-modal .guilds .section+.section {
	border-top: 1px solid rgba(240, 240, 240, 0.15) !important;
}

#user-profile-modal .guilds .guild:hover {
	background:rgba(255,255,255,0.2) !important;
	color:rgba(255,255,255,0.7);
}

#user-profile-modal .avatar-profile {
	width: 126px !important;
	height: 126px !important;
}

#user-profile-modal .header .header-info .header-info-inner .discord-tag {
	font-size: 22px !important;
	font-weight: bold !important;
	color: #fff;
}

#user-profile-modal .header .header-info .header-info-inner .discord-tag .discriminator {
	color: rgba(255, 255, 255, 0.5);
	padding-left: 3px;
}

#user-profile-modal .header .header-info .header-info-inner .activity {
	color: rgba(255, 255, 255, 0.5);
}

#user-profile-modal .avatar-wrapper {
	background-color: transparent;
	box-shadow: 0 8px 40px -5px rgba(0,0,0,1);
	border-radius: 100%;
}

.bda-slist li {
	border: none !important;
}

.bda-slist li:first-of-type {
	border-top:none !important;
}

.bda-slist .bda-right .bda-plugin-reload {
	margin-top:25px;
}

.bda-slist .bda-right .btn {
	margin-left:-5px;
}

.bda-slist .bda-right .btn:disabled {
	opacity:0.3;
}

.bda-slist .checkbox {
	margin-left:10px;
	position:relative;
	top:8px;
}

/* Add checkbox cause jiiks hasnt added the new class yet */
.bda-slist .bda-right .ui-switch-wrapper {
	-webkit-user-select: none;
	-moz-user-select: none;
	-ms-user-select: none;
	user-select: none;
	position: relative;
	width: 44px;
	height: 24px;
	display: block;
	-webkit-box-flex: 0;
	-ms-flex: 0 0 auto;
	flex: 0 0 auto;
	border-radius: 50px;
	background: var(--accent-color);
}

.bda-slist .bda-right .ui-switch-wrapper .ui-switch-checkbox {
	position: absolute;
	opacity: 0;
	cursor: pointer;
	width: 100%;
	height: 100%;
	z-index: 1;
	transition: background .15s ease-in-out,box-shadow .15s ease-in-out,border .15s ease-in-out;
}

.ui-switch-checkbox {
	background: blue !important;
}

.ui-switch-checkbox+.ui-switch {
	background: rgba(255,255,255,0.2) !important;
}

.ui-switch-checkbox:checked+.ui-switch {
	background: var(--main-color) !important;
	/*transform: translateX(20px);*/
}

.bda-slist .bda-right .ui-switch-wrapper .ui-switch {
    content: "";
    display: block;
    width: 18px;
    height: 18px;
    position: absolute;
    top: 3px;
    left: 3px;
    bottom: 3px;
    background: #f6f6f7;
    border-radius: 10px;
    transition: all .15s ease;
    box-shadow: 0 3px 1px 0 rgba(0,0,0,.05),0 2px 2px 0 rgba(0,0,0,.1),0 3px 3px 0 rgba(0,0,0,.05);
}

.bda-slist {
	margin-bottom:25px;
}

.bda-slist-top {
	height: 35px;
}

#bd-themes-pane .bda-plugin-reload {
	margin-top:60px;
}

#bda-qem-favourite-container,
#bda-qem-twitch-container,
.emoji-picker {
	background-color: rgba(0,0,0,0.95) !important;
	border: 0px solid rgba(255,255,255,0.1) !important;
	border-top: none !important;
}

.emoji-picker .category {
	background-color: rgba(0,0,0,0.7) !important;
	border: 0px solid rgba(255,255,255,0.2) !important;
	border-top: none !important;
}

#bda-qem {
	padding-right: 0px !important;
	border-bottom: 0px solid rgba(0,0,0,0.5) !important;
	background: rgba(0,0,0,0.95) !important;
}

#bda-qem button {
	background: rgba(255,255,255,0.1) !important;
	box-shadow: rgba(0,0,0,0.5) 1px 0 0 0 !important;
}

#bda-qem button:hover {
	background: rgba(0,0,0,0.6) !important;
}

#bda-qem button.active {
	background: rgba(0,0,0,1) !important;
}

/* Scrollbar drag bar */
.emoji-picker .scroller::-webkit-scrollbar-thumb,
#bda-qem-twitch-container .scroller::-webkit-scrollbar-thumb,
#bda-qem-favourite-container .scroller::-webkit-scrollbar-thumb {
	background:rgba(255,255,255,0.4) !important;
	border-color:rgba(255,255,255,0) !important;
}

/* Scrollbar background */
.emoji-picker .scroller::-webkit-scrollbar,
.emoji-picker .scroller::-webkit-scrollbar-track,
.emoji-picker .scroller::-webkit-scrollbar-track-piece,
#bda-qem-favourite-container .scroller::-webkit-scrollbar,
#bda-qem-favourite-container .scroller::-webkit-scrollbar-track,
#bda-qem-favourite-container .scroller::-webkit-scrollbar-track-piece,
#bda-qem-twitch-container .scroller::-webkit-scrollbar,
#bda-qem-twitch-container .scroller::-webkit-scrollbar-track,
#bda-qem-twitch-container .scroller::-webkit-scrollbar-track-piece {
	background:rgba(255,255,255,0.1) !important;
	border-color:rgba(255,255,255,0) !important;
}

.instant-invite-modal {
	background: none;
}

#instant-invite-modal .copy {
	background-color: var(--main-color);
}

#instant-invite-modal .clipboard-input-inner input {
	color: var(--main-color);
}

.popout-menu {
	background: transparent !important;
}

.popout-menu.status-picker {
	background: transparent;
	width: 322px !important;
	margin-left: 0px !important;
	margin-bottom: 0 !important;
}

.popout-menu .popout-menu-separator {
	border-bottom: 1px solid rgba(255,255,255,0.2) !important;
}

.popout-menu .popout-menu-item {
	background: rgba(0,0,0,0.95) !important;
}

.popout-top .popout-menu .popout-menu-item {
	color: rgba(255,255,255,0.8) !important;
}

.popout-menu .popout-menu-item:hover {
	background-color: var(--accent-color) !important;
	color: rgba(255,255,255,0.8) !important;
}

.popout-top {
	top: auto !important;
	bottom: -126px !important;
}

.popout-bottom:not(.no-arrow):not(.search-popout) {
	/*left: 191px !important;*/
}

.themed-popout {
	background-color: #161921 !important;
	border: 1px solid rgba(255,255,255,0) !important;
}

.themed-popout .header, .themed-popout .footer {
	background-color: rgba(0, 0, 0, 0.4) !important;
}

.themed-popout .messages-popout .message-group {
	border-color: rgba(28,36,43,0.6) !important;
	background-color: rgba(0, 0, 0, 0) !important;
	box-shadow: none !important;
}

.themed-popout .messages-popout .message-group .comment .markup {
	font-size: 13px;
    line-height: 1.3;
}

.themed-popout .messages-popout .message-group:hover .action-buttons {
	box-shadow: 0 0 6px 4px rgba(0, 0, 0, 0.7) !important;
	background-color: rgba(0, 0, 0, 0.8) !important;
}

.themed-popout .messages-popout .message-group:hover .action-buttons .jump-button {
	background-color: rgba(240, 240, 240, 0.07) !important;
}



#slist,
#pubs-container {
	background-color:rgba(0,0,0,0.7) !important;
	border-radius:5px 5px 0 0;
}

#pubs-header {
	padding:10px;
	background-color:var(--main-color) !important;
	border-radius:5px 5px 0 0;
}

#pubs-header input {
	padding-left:10px;
}

#pubs-footer {
	padding:10px;
	font-size:12px;
	background:rgba(0,0,0,0.8) !important;
	border-radius:0 0 5px 5px;
}

.server-icon {
	width:50px;
	height:50px;
	border-radius:100%;
}

.server-row {
	padding:10px 10px 8px 10px;
}

.server-info {
	line-height:50px;
}

.server-info button {
	background-color:var(--accent-color) !important;
	width:70px;
	height:40px;
	margin-top:4px;
	margin-right:4px;
}

.server-info button:hover {
	background-color:var(--main-color) !important;
}

#slist span {
	color:white !important;
}

.server-row:nth-child(2n+1) {
	background-color:rgba(255,255,255,0.06) !important;
}

.server-row:nth-child(2n+2) {
	background-color:rgba(0,0,0,0) !important;
}
